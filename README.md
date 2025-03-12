# MintMaker presets

This repository hosts presets for a dependency management service [MintMaker](https://github.com/konflux-ci/mintmaker).
If you want to use a preset in your configuration, use this as an example for your `renovate.json` configuration file:

```
{
    "extends": ["github>konflux-ci/mintmaker-presets:cve-automerge-critical"]
}
```

To learn more about MintMaker customizations, please visit our [documentation page](https://konflux.pages.redhat.com/docs/users/mintmaker/user.html).
