# modprobe

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&amp;logoColor=white)](https://github.com/rolehippie/modprobe)
[![General Workflow](https://github.com/rolehippie/modprobe/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/modprobe/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/modprobe/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/modprobe/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/modprobe/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/modprobe/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/modprobe)](https://github.com/rolehippie/modprobe/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.modprobe-blue)](https://galaxy.ansible.com/rolehippie/modprobe)

Ansible role to load or unload kernel modules.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [modprobe_extra](#modprobe_extra)
  - [modprobe_general](#modprobe_general)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`


## Default Variables

### modprobe_extra

List of extra modules to load

#### Default value

```YAML
modprobe_extra: []
```

### modprobe_general

List of general modules to load

#### Default value

```YAML
modprobe_general: []
```

## Discovered Tags

**_modprobe_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
