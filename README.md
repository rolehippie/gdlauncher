# gdlauncher

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&amp;logoColor=white)](https://github.com/rolehippie/gdlauncher)
[![General Workflow](https://github.com/rolehippie/gdlauncher/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/gdlauncher/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/gdlauncher/actions/workflows/readme.yml/badge.svg)](https://github.com/rolehippie/gdlauncher/actions/workflows/readme.yml)
[![Galaxy Workflow](https://github.com/rolehippie/gdlauncher/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/gdlauncher/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/gdlauncher)](https://github.com/rolehippie/gdlauncher/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.gdlauncher-blue)](https://galaxy.ansible.com/rolehippie/gdlauncher)

Ansible role to install gdlauncher minecraft client.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [gdlauncher_package](#gdlauncher_package)
  - [gdlauncher_version](#gdlauncher_version)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`


## Default Variables

### gdlauncher_package

Download URL for the package to install

#### Default value

```YAML
gdlauncher_package: https://github.com/gorilla-devs/GDLauncher/releases/download/v{{
  gdlauncher_version }}/GDLauncher-linux-setup.deb
```

### gdlauncher_version

Version for the package

#### Default value

```YAML
gdlauncher_version: 1.1.30
```

## Discovered Tags

**_gdlauncher_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
