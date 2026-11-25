# Silence

A fantasy 2.5D Unity RPG prototype with a cathedral kingdom, an enchanted forest, and an editable Unity UI menu.

## Open the project

1. Install **Unity 6000.5.11f1** through Unity Hub.
2. Install Git LFS, run `git lfs install`, and clone this repository. If already cloned, run `git lfs pull`.
3. In Unity Hub, add the repository folder as a project. Allow Unity to restore packages and import assets.
4. Open `Assets/Scenes/_Menu.unity` and press **Play**.

## Play

- **WASD / arrow keys:** move.
- **Shift:** sprint.
- **Gamepad:** left stick moves; left-stick press or right trigger sprints.
- **Start Game:** enters the daytime kingdom.
- **Kingdom east gate:** travels to the nighttime forest.
- **Forest south entrance:** returns to the kingdom.
- **Settings:** adjusts menu music and button-sound volume using native Unity UI events.

Both realm scenes use Cinemachine follow cameras. The kingdom has a larger player and faster movement to suit its enlarged environment.

## Project folders

`Assets` groups scripts, editor utilities, scenes, input actions, models, materials, physics materials, sprites, textures, animations, audio, fonts, lighting, and prefabs by purpose. Required imported support assets are under `Assets/ThirdParty`.

The repository contains `Assets`, `Packages`, and `ProjectSettings`. Unity-generated caches, local captures, unused-asset archives, and duplicate checkouts are excluded. Git LFS stores large binary assets.

The Cinzel Decorative font license is included under `Assets/Fonts/CinzelDecorative`.
