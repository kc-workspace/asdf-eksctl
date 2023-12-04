<h1 align="center">
  asdf-eksctl
</h1>

<!-- Description section -->
<p align="center">
  <strong>a simple CLI tool for creating and managing clusters on EKS - Amazon's managed Kubernetes service for EC2.</strong>
</p>

<!-- Badges section -->
<p align="center">
  <a href="https://github.com/kc-workspace/asdf-eksctl/actions/workflows/main.yml">
    <img
      alt="github-main"
      src="https://img.shields.io/github/actions/workflow/status/kc-workspace/asdf-eksctl/main.yml?style=flat-square&logo=github">
  </a>
  <a href="https://github.com/kc-workspace/asdf-eksctl/releases">
    <img
      alt="version"
      src="https://img.shields.io/github/v/release/kc-workspace/asdf-eksctl?style=flat-square&logo=github">
  </a>
  <a href="https://github.com/kc-workspace/asdf-eksctl/commits/main">
    <img
      alt="version"
      src="https://img.shields.io/github/last-commit/kc-workspace/asdf-eksctl/main?style=flat-square&logo=github">
  </a>
</p>

<!-- Links section -->
<h3 align="center">
  <a href="https://eksctl.io/">eksctl</a>
  <span> · </span>
  <a href="https://asdf-vm.com">asdf</a>
</h3>

> This is an asdf-vm plugin generated from [template][template-gh].

## Before start

> If you still see this section, mean this plugin is not ready yet

There are several things template cannot generate for you,
below are a list of thing we should do:

1. make sure that your GitHub repository already exist at [kc-workspace/asdf-eksctl][plugin-gh]
2. please read [plugins create section][asdf-create-plugin] for more information
3. remove `before start` section once you completed

## Install

Plugin:

```sh
asdf plugin add "eksctl" "https://github.com/kc-workspace/asdf-eksctl.git"
```

App:

```sh
# Show all installable versions
asdf list all eksctl

# Install latest version
asdf install eksctl latest

# Set a version globally
asdf global eksctl latest
# Set a version locally
asdf local eksctl latest

# Now eksctl commands are available
eksctl
```

Check the [asdf][asdf-link] readme for instructions on
how to install & manage versions.

## Features

Plugins generated from asdf-plugin-template repository will
contains several extra features for every user including all below.

- `$DEBUG=<any-string>` to enabled debug mode (debug logs will guarantee to show regardless of other settings)
- `$ASDF_FORCE_DOWNLOAD=<any-string>` to always download even cache exist
- `$ASDF_INSECURE=<any-string>` to disable security features (e.g. checksum)
- `$ASDF_NO_CHECK=<any-string>` to disable pre-check features (e.g. check-cmd)
- `$ASDF_OVERRIDE_REF_REPO=<repository>` to override git repository URL when install with ref mode
- `$ASDF_OVERRIDE_OS=<os>` to override os name
- `$ASDF_OVERRIDE_ARCH=<arch>` to override arch name
- `$ASDF_OVERRIDE_EXT=<ext>` to override download extension
- `$GITHUB_TOKEN=<token>` to pass GitHub token on http request
- `$ASDF_LOG_FORMAT=<format>` to custom log format, there are several variables
  - **{datetime}** - for current datetime
  - **{date}** - for current date
  - **{time}** - for current time
  - **{level}** - for log level (always be 3 characters uppercase)
  - **{namespace}** - for formatted namespace (always have same length)
  - **{ns}** - for raw namespace (no formatting applied)
  - **{message}** - for log message
- `$ASDF_LOG_QUIET=<any-string>` - to disable only info logs
- `$ASDF_LOG_SILENT=<any-string>` - to disable all logs (including warning and error)

### Addition Features

The plugins might contains additional features
in addition to default features above.
You can take a look at [README.plugin.md][app-readme-md]

## Contributors

Read [CONTRIBUTING.md][contributing-md] file for more detail.

<!-- LINKS SECTION -->

[app-readme-md]: ./README.plugin.md
[contributing-md]: ./CONTRIBUTING.md
[plugin-gh]: https://github.com/kc-workspace/asdf-eksctl
[template-gh]: https://github.com/kc-workspace/asdf-plugin-template
[asdf-link]: https://github.com/asdf-vm/asdf
[asdf-create-plugin]: https://asdf-vm.com/plugins/create.html
