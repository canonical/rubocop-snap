<p align="center">
    <a href="https://rubocop.org//">
        <img src="images/banner.png" height="100" alt="RuboCop logo"/>
    </a>
</p>
<h2 align="center">Ruby linter and formatter</h2>
<p align="center" float="left">
    <a href="https://snapcraft.io/rubocop">
        <img src="https://snapcraft.io/rubocop/badge.svg" width="150" height="17" alt="Snapcraft's Version"/>
    </a>
    &nbsp; &nbsp;
    <a href="https://snapcraft.io/rubocop">
        <img src="https://img.shields.io/github/v/release/google/rubocop?label=RuboCop%20on%20GitHub%20Releases&color=1c8223" height="17" alt="PyPI's Version">
    </a>
    &nbsp; &nbsp;
    <a href="https://github.com/iosifache/rubocop-snap/actions/workflows/test-build.yaml">
        <img src="https://img.shields.io/github/actions/workflow/status/iosifache/rubocop-snap/test-build.yaml?label=Build%20Status&color=1c8223" height="17" alt="GitHub Build Workflow Status">
    </a>
</p>

# Description

Rubocop is a Ruby linter and formatter.

As a linter, it checks for aspects such as:
- Style: mosty the recommendations from the Ruby Style Guide;
- Linting: ambiguous ranges, debugger calls, etc.
- Code metrics: cyclomatic and perceieved complexity, the length of the module and methods, etc.;
- Naming: uniform names for constants, methods, modules, etc.
- Security: unsafe evaluation, YAML deserializations, calls to I/O functions, etc.
- Bundling: usual issues in the Bundler files.

The formatter capability can be used to fix many of the issues automatically.


[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/rubocop)

> Notice: If you want to view the officially recommended method of installing of the tool, refer to the [RuboCop documentation](https://docs.rubocop.org/rubocop/1.59/installation.html).

# Local Build

1. Clone this repository: `git clone https://github.com/iosifache/rubocop-snap`
2. Move into the cloned repository: `cd rubocop-snap`
3. Install Snapcraft: `sudo snap install snapcraft --classic`
4. Build the snap: `snapcraft --verbose`
5. Install the snap: `snap install --dangerous ./rubocop_*.snap`
6. Test the snap by running the `rubocop` command: `rubocop`

