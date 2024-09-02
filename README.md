# 31147

Reproduction for [Renovate discussion 31147]([https://github.com/renovatebot/renovate/issues/12260](https://github.com/renovatebot/renovate/discussions/31147)).

## Current behavior

Renovate do not support docker compose YAML tags `reset` and `override` and can not parse the yaml file.

```
DEBUG: Parsing Docker Compose config YAML failed (repository=..., packageFile=docker-compose.production.yml)
       "err": {
         "name": "YAMLException",
         "reason": "unknown tag !<!reset>",
         "mark": {
           "name": null,
```

## Expected behavior

Renovate can parse docker compose files with YAML tags.

## Link to the Renovate Discussion

[Put your link to the Renovate issue or Discussion here.](https://github.com/renovatebot/renovate/discussions/31147)
