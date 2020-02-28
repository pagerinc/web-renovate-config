If you feel that some of the renovate PRs should be grouped, this is where to touch!

# web-renovate-config

Renovate bot [preset settings][presets] that can be extended or used directly in your projects.
Config can still be overriden in each individual project, for flexibility.

## How to use

Create a `renovate.json` in the root of your project like
```
{
  "extends": [
    "github>pagerinc/web-renovate-config"
  ]
}
```
Or, in `package.json` of the project, add the following section:
```
  "renovate":{
    "extends": [
      "github>pagerinc/web-renovate-config"
    ]
  }
```

[presets]: https://renovatebot.com/docs/config-presets
[defaultpresets]: https://docs.renovatebot.com/presets-default
[options]: https://docs.renovatebot.com/configuration-options
