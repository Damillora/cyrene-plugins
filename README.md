# cyrene-plugins

> The `main` branch contains plugins for the git version of `cyrene`. Plugins for version `0.3` lives in the `0.3` branch.

Plugins for [cyrene](https://github.com/Damillora/cyrene), as I've written.

## Installation

```
mkdir -p $HOME/.local/share/cyrene
git clone https://github.com/Damillora/cyrene-plugins $HOME/.local/share/cyrene/plugins
```

## Writing a plugin

cyrene plugins are configured using TOML.

cyrene plugins are mainly concerned with two things: querying available versions, and installing a single version of an application. `cyrene` will handle version management.

For a simple example, check out [the plugin](flora.cyrene) for [flora](https://github.com/Damillora/flora), a command-line Wine prefix manager.

## Contributing

Create a pull request if you want your plugins here.

## License

Plugins in this repository are licensed under the [MIT License](LICENSE). [cyrene](https://github.com/Damillora/cyrene) itself is licensed under the [MIT License](LICENSE).
