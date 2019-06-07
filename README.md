# README

Global configuration for WebStorm

## Installation

Location of the WebStorm folder is depending on OS and WebStorm version. See section [Project and IDE settings](https://www.jetbrains.com/help/webstorm/project-and-ide-settings.html) for more information about the configuration directory structure.

### Linux

#### Xubuntu

```sh
# Use local installation

git checkout linux/xubuntu
bin/installer install

# Use remote installation

curl --location "https://github.com/mauchede/webstorm-config/raw/linux/xubuntu/bin/installer" | bash -s -- install
```

__Note__: Make sure WebStorm is not running, or it will overwrite the changed files before shutting down.

### macOS

#### Darwin

```sh
# Use local installation

git checkout mac-os/darwin
bin/installer install

# Use remote installation

curl --location "https://github.com/mauchede/webstorm-config/raw/mac-os/darwin/bin/installer" | bash -s -- install
```

__Note__: Make sure WebStorm is not running, or it will overwrite the changed files before shutting down.

## Contributing

1. Fork it.
2. Create your branch: `git checkout -b my-new-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin my-new-feature`.
5. Submit a pull request.

If you like / use this project, please let me known by adding a [★](https://help.github.com/articles/about-stars/) on the [GitHub repository](https://github.com/mauchede/webstorm-config).

## Links

* [project and ide settings](https://www.jetbrains.com/webstorm/help/project-and-ide-settings.html)
