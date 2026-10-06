# Ghostty config

My personal configuration for the [Ghostty](https://ghostty.org) terminal emulator.

## Location

On macOS, Ghostty reads its config from:

```
~/Library/Application Support/com.mitchellh.ghostty/config.ghostty
```

## Settings

- **Font ligatures disabled** — the `calt`, `liga`, and `dlig` font features are turned off, so character sequences like `!=` and `=>` show as separate characters.

## Applying changes

Reload the config in Ghostty with `Cmd+Shift+,`, or restart the app.

## Reference

- [Ghostty configuration docs](https://ghostty.org/docs/config)
- List every option and its default: `ghostty +show-config --default --docs`
