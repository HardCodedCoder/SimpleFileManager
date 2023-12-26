# SimpleFileManager

This project is a Qt-based application built using CMake.

## Prerequisites

Ensure Qt 6.6.1 is installed on your system. The exact installation method may vary depending on your operating system.

## Setting Up the Environment Variable on macOS

Before building the project, you need to set an environment variable named `QT_CMAKE_PREFIX_PATH` that points to the Qt6 CMake configuration files on your system.

Open Terminal and enter the following command, replacing `<Path_to_Your_Qt>` with the actual path to your Qt installation:

### For `bash` users:

```bash
echo 'export QT_CMAKE_PREFIX_PATH=<Path_to_Your_Qt>/lib/cmake' >> ~/.bash_profile
source ~/.bash_profile
```

### For `zsh` users (default on macOS of version 10.15):

```zsh
echo 'export QT_CMAKE_PREFIX_PATH=<Path_to_Your_Qt>/lib/cmake' >> ~/.zshrc
source ~/.zshrc
```

## Building the Project
Once you've set the environment variable, you can open and build the project using the IDE of your choice.

## License
This project is licensed under the LGPL-3.0 License - see the [LICENSE](LICENSE) file for details.
