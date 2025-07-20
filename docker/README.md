# docker

## Install

- By brew:

  ```bash
  brew install --cask docker
  ```

- By apt:

  ```bash
  sudo apt install -y docker.io
  ```

- By [colima](https://github.com/abiosoft/colima) (brew):

  ```bash
  brew install colima docker
  colima start

  # Start colima in background and enable it to start on login:
  brew services start colima  # Or: `colima start --background`
  ```

## Uninstall

- By brew:

  ```bash
  # Ref: https://github.com/docker/for-mac/issues/7046#issuecomment-2579215790
  brew uninstall --cask docker --force --verbose --debug
  brew uninstall --formula docker --force --verbose --debug
  ```
