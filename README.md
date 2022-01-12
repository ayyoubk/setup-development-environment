# setup-development-environment

This guide for setting up your development environment for Linux/Ubuntu users

## Installing and Updating the Linux App Manager

- open terminal and run the following command:

  ```bash
  sudo apt-get update && sudo apt-get upgrade -y
  ```

  ```bash
  sudo apt autoremove -y
  ```

  ```bash
  sudo apt-get build-essential -y
  ```

## Homebrew Installation

The Missing Package Manager for macOS (or Linux)

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- to check brew Installation state use :

  ```bash
  brew doctor
  ```

- to install important packages

  ```bash
  brew install wget
  ```

### [Next ❯](./git-installation.md)
