# Predictive Input Buffer

Simulates your click a few ticks ahead. If clicking now kills you and a slightly later click survives, your input is held back and delivered later (1 tick = 0.25 frames @ 60fps).

## Controls
- **F6** (while GD is focused) cycles the max delay: 0.5f → 1f → 2f → 4f → 6f → 8f → custom → off
- **K** (in a level) opens/closes the panel: current stage + live log of saved inputs. Hidden by default.
- The custom stage, prediction budget, orb/pad/portal prediction and debug console are in the mod settings.

## v2
- Bigger windows (up to 8 frames, custom up to 16)
- Ghost simulates orbs, pads, gravity portals and speed portals
- Inputs during a delay keep their rhythm (no more swallowed taps)
- Per-click time budget, K panel with stage + live log, bug fixes

Ship isn't buffered. This mod changes your input timing, so completions made with it don't count as legit on lists.
