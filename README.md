# Renovate presets

This repository contains [shared presets] for [Renovate] used in the repositories of this organization.

## Usage

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>eoehen/renovate-presets"]
}
```

## Available presets

| Preset                                                | Description                                                                  |
|-------------------------------------------------------|------------------------------------------------------------------------------|
| `github>cake-contrib/renovate-presets`                | [Default configuration](default.json)                                        |
| `github>cake-contrib/renovate-presets:github-actions` | [Configuration for GitHub actions](github-actions.json)                      |

[shared presets]: https://docs.renovatebot.com/config-presets/
[Renovate]: https://renovatebot.com/
