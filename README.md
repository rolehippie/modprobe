# modprobe

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/modprobe) [![Build Status](https://img.shields.io/drone/build/rolehippie/modprobe/master?logo=drone)](https://cloud.drone.io/rolehippie/modprobe) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/modprobe)](https://github.com/rolehippie/modprobe/blob/master/LICENSE) 

Ansible role to load or unload kernel modules. 

## Sponsor 

[![Proact Deutschland GmbH](https://proact.eu/wp-content/uploads/2020/03/proact-logo.png)](https://proact.eu) 

Building and improving this Ansible role have been sponsored by my employer **Proact Deutschland GmbH**.

## Table of content

* [Default Variables](#default-variables)
  * [modprobe_extra](#modprobe_extra)
  * [modprobe_general](#modprobe_general)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

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

## Dependencies

* None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
