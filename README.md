# npm-uninstall-unused 🛠️

![npm-uninstall-unused](https://img.shields.io/badge/npm--uninstall--unused-v1.0.0-blue.svg)
[![Releases](https://img.shields.io/badge/releases-latest-brightgreen.svg)](https://github.com/Nischal642/npm-uninstall-unused/releases)

Welcome to **npm-uninstall-unused**, a command-line interface (CLI) tool designed to help you detect and uninstall unused npm dependencies from your Node.js projects. Whether you are managing a single project or working within a monorepo, this tool simplifies the process of cleaning up your dependencies.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Command Options](#command-options)
5. [Examples](#examples)
6. [Contributing](#contributing)
7. [License](#license)
8. [Acknowledgments](#acknowledgments)

## Features

- **Detect Unused Dependencies**: Identify dependencies that your project no longer uses.
- **Uninstall with Ease**: Remove unnecessary packages with a simple command.
- **Support for Monorepos**: Works seamlessly with monorepo structures.
- **Lightweight**: Minimal footprint with no additional bloat.
- **Easy to Use**: Simple command-line interface that requires no configuration.

## Installation

To install **npm-uninstall-unused**, you can use npm. Run the following command in your terminal:

```bash
npm install -g npm-uninstall-unused
```

This command installs the tool globally, allowing you to use it in any of your Node.js projects.

## Usage

To start using **npm-uninstall-unused**, simply run the following command in your project directory:

```bash
npm-uninstall-unused
```

This command will scan your project for unused dependencies and prompt you to uninstall them.

For more details on how to use this tool, check the [Releases](https://github.com/Nischal642/npm-uninstall-unused/releases) section for the latest updates and documentation.

## Command Options

The CLI tool provides several options to customize its behavior. Here are some of the available commands:

- `--help`: Displays help information about the tool.
- `--verbose`: Provides detailed output during the scanning process.
- `--dry-run`: Shows which dependencies would be removed without actually uninstalling them.

## Examples

Here are some practical examples of how to use **npm-uninstall-unused**:

### Basic Usage

To find and uninstall unused dependencies, run:

```bash
npm-uninstall-unused
```

### Using the Dry Run Option

If you want to see what would be removed without making any changes, use:

```bash
npm-uninstall-unused --dry-run
```

### Verbose Output

For detailed information during the process, use:

```bash
npm-uninstall-unused --verbose
```

## Contributing

Contributions are welcome! If you have suggestions or improvements, please feel free to open an issue or submit a pull request. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push to your branch.
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Thanks to the open-source community for their contributions and support.
- Special thanks to the maintainers of the libraries that made this project possible.

## Additional Resources

For more information and updates, visit the [Releases](https://github.com/Nischal642/npm-uninstall-unused/releases) section. Here you can find the latest version and download it for execution.

Feel free to reach out with any questions or feedback. Happy coding!