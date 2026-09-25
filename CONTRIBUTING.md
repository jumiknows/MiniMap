# Contributing

MiniMap is an early Unity prototype. Keep changes small and make the implemented behavior match what the README claims.

## Setup

Use Unity `6000.3.5f1` and open:

```text
Assets/Scenes/SampleScene.unity
```

## Before opening a pull request

1. Open the project without Unity upgrade prompts.
2. Test the affected scene in Play Mode.
3. Check the Console for new errors.
4. Do not commit `Library`, `Temp`, `Logs`, generated IDE files, or local Unity settings.
5. Update the README when a planned minimap feature actually becomes implemented.

Use clear titles such as:

```text
feat: render top-down minimap camera
fix: keep player marker centered
docs: update implemented minimap features
```
