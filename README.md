# MiniMap

A small Unity project used to explore how a minimap can be added to a 3D scene.

## Status

This repository is currently an **early prototype**. The Unity project and sample scene are set up, but the minimap camera and UI are not implemented yet.

That work is tracked separately so this repository does not imply features that are not present.

## Open the project

**Unity:** 6000.3.5f1

1. Clone the repository.
2. Open the folder in Unity Hub.
3. Use Unity 6000.3.5f1.
4. Open `Assets/Scenes/SampleScene.unity`.

## Project structure

```text
Assets/             Unity scenes and project assets
Packages/           Unity package manifest
ProjectSettings/    Unity project settings
```

The current build scene is:

```text
Assets/Scenes/SampleScene.unity
```

## Planned minimap work

The next useful step is to add:

- a top-down minimap camera
- a Render Texture
- a UI element that displays the minimap
- a player marker
- basic zoom and rotation behaviour

See [Issue #2](https://github.com/jumiknows/MiniMap/issues/2) for the implementation plan.

## Notes

This is a Unity learning prototype rather than a finished game. It is kept public to show the project setup and the planned approach without overstating the current implementation.
