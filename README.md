# modprobe

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/modprobe) [![Testing Build](https://github.com/rolehippie/modprobe/workflows/testing/badge.svg)](https://github.com/rolehippie/modprobe/actions?query=workflow%3Atesting) [![Readme Build](https://github.com/rolehippie/modprobe/workflows/readme/badge.svg)](https://github.com/rolehippie/modprobe/actions?query=workflow%3Areadme) [![Galaxy Build](https://github.com/rolehippie/modprobe/workflows/galaxy/badge.svg)](https://github.com/rolehippie/modprobe/actions?query=workflow%3Agalaxy) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/modprobe)](https://github.com/rolehippie/modprobe/blob/master/LICENSE)

Ansible role to load or unload kernel modules.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Default Variables](#default-variables)
  - [modprobe_extra](#modprobe_extra)
  - [modprobe_general](#modprobe_general)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

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
