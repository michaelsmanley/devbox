# MSM.dev/dx

Initially forked from [davetron5000/devbox](https://github.com/davetron5000/devbox).

This repo contains the scripts and templates for creating a development environment for MSM.dev projects.

## How to Use

1. Clone or check out the repo locally.
2. Set up your local environment by copying the sample `.envrc` file. This file is used by `direnv` to load environment variables.
   ```bash
   cp .envrc.sample .envrc
   ```
   After copying, review the variables in `.envrc` and allow `direnv` to load the new file by running:
   ```bash
   direnv allow
   ```
3. Run `bin/install -h` to read the installation help.
4. Gather all of the details for your project:
    1. Details TODO
5. When making changes, please update `docs/CHANGELOG.md` following the Keep a Changelog guidelines.

## How to Add Templates

TODO
