# StaticForge Installer

Composer installer for StaticForge themes.

## Description

This Composer plugin handles the installation of StaticForge themes. It hooks into Composer's install, update, and uninstall events to manage theme assets within your StaticForge project.

## Installation

You can install this package via Composer:

```bash
composer require eicc/staticforge-installer
```

## Usage

This plugin is automatically activated by Composer when required in your project. It will listen for package operations related to StaticForge themes.

## Uninstallation

If you run `composer remove` to remove a theme package, the package will be removed from your dependencies, but the installed theme files in the `themes` directory will remain. You will need to remove the theme directory manually.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
