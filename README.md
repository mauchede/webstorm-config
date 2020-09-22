# README

Global configuration for WebStorm

⚠️ This project is no longer maintained. ⚠

## Installation

Location of the WebStorm folder is depending on OS and WebStorm version. See section [Project and IDE settings](https://www.jetbrains.com/help/webstorm/project-and-ide-settings.html) for more information about the configuration directory structure.

### Linux

#### Xubuntu

```sh
# Use local installation

git checkout linux/xubuntu
bin/installer install

# Use remote installation

curl --location "https://gitlab.com/mauchede/webstorm-config/raw/linux/xubuntu/bin/installer" | bash -s -- install
```

__Note__: Make sure WebStorm is not running, or it will overwrite the changed files before shutting down.

### macOS

#### Darwin

```sh
# Use local installation

git checkout mac-os/darwin
bin/installer install

# Use remote installation

curl --location "https://gitlab.com/mauchede/webstorm-config/raw/mac-os/darwin/bin/installer" | bash -s -- install
```

__Note__: Make sure WebStorm is not running, or it will overwrite the changed files before shutting down.

## Links

* [project and ide settings](https://www.jetbrains.com/webstorm/help/project-and-ide-settings.html)
