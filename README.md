# renovate-config

sharable renovate configs

## How to use

### For node.js application repository

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>openameba/renovate-config:main.json5",
    "github>openameba/renovate-config:npm.json5",
    "github>openameba/renovate-config:npm-app.json5"
  ]
}
```

### For node.js library repository

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>openameba/renovate-config:main.json5",
    "github>openameba/renovate-config:npm.json5",
    "github>openameba/renovate-config:npm-lib.json5"
  ]
}
```

### With automerge minor

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>openameba/renovate-config:main.json5",
    "github>openameba/renovate-config:automerge-minor.json5"
  ]
}
```

### With automerge all

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>openameba/renovate-config:main.json5",
    "github>openameba/renovate-config:automerge-all.json5"
  ]
}
```

## Links

- https://docs.renovatebot.com/
- https://docs.renovatebot.com/presets-default/
- https://developer.mend.io/github/openameba/renovate-config
