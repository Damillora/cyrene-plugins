# cyrene-plugins

Plugins for [cyrene](https://github.com/Damillora/cyrene), as I've written.

## Installation

```
mkdir -p .local/share/cyrene/plugins
git clone https://github.com/Damillora/cyrene-plugins
```

## Writing a plugin

cyrene plugins are scripts written in the [Rune](https://rune-rs.github.io/) scripting language.

cyrene plugins are mainly concerned with two things: querying available versions, and installing a single version of an application. `cyrene` will handle version management.

For most uses, cyrene plugins are pretty simple to write. `cyrene` itself provides several helper functions so that e.g. querying GitHub releases is a function call away.

However, because cyrene plugins are written in a full scripting language, plugins using custom APIs, such as [the plugin for Node.js](node.rs), are more easily achievable.

For a simple example, check out [the plugin](flora.rn) for [flora](https://github.com/Damillora/flora), a command-line Wine prefix manager.

## Contributing

Create a pull request if you want your plugins here.

## License

Plugins in this repository are licensed under the [MIT License](LICENSE). [cyrene](https://github.com/Damillora/cyrene) itself is licensed under the [MIT License](LICENSE).
