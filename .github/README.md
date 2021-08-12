<h4 align="center">In Development: An Ansible role for installing and configuring firewalld.</h4>

<p align="center">
    <a href="https://github.com/totaldebug/ansible-role-firewalld/commits/master">
    <img src="https://img.shields.io/github/last-commit/totaldebug/ansible-role-firewalld.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub last commit">
    <a href="https://github.com/totaldebug/ansible-role-firewalld/issues">
    <img src="https://img.shields.io/github/issues-raw/totaldebug/ansible-role-firewalld.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub issues">
    <a href="https://github.com/totaldebug/ansible-role-firewalld/pulls">
    <img src="https://img.shields.io/github/issues-pr-raw/totaldebug/ansible-role-firewalld.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub pull requests">
</p>

<p align="center">
  <a href="#configuration">Configuration</a> •
  <a href="#features">Features</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#author">Author</a> •
  <a href="#support">Support</a> •
  <a href="#donate">Donate</a> •
  <a href="#license">License</a>
</p>

---

## About

<table>
<tr>
<td>

**ansible-role-firewalld** is a **high-quality** _Ansible Role_ that deploys and configures **firewalld** to your ansible clients.

</td>
</tr>
</table>

## Configuration

### Install

```shell
ansible-galaxy install totaldebug.firewalld
```

### Role Variables

#### Deluge

| **Input** | **Default** | **Description** |
|:---------:|:-----------:|:---------------:|
| `deluge_service_user` | `deluge` | Username for the service account |


### Example Playbook

```yaml
---

- host: all
  roles:
    - totaldebug/firewalld
```

## Features

|                            |         🔰         |
| -------------------------- | :----------------: |
| Install firewalld          |         ✔️         |
| Enable at startup          |         ✔️         |
| Configure firewall rules   |         ✔️         |


## Contributing

Got **something interesting** you'd like to **share**? Learn about [contributing](https://github.com/totaldebug/.github/blob/main/.github/CONTRIBUTING.md).

### Versioning

This project follows semantic versioning.

In the context of semantic versioning, consider the role contract to be defined by the role variables.

- Breaking Changes or changes that require user intervention will increase the major version. This includes changing the default value of a role variable.
- Changes that do not require user intervention, but add new features, will increase the minor version.
- Bug fixes will increase the patch version.

## Author

| [![TotalDebug](https://totaldebug.uk/assets/images/logo.png)](https://linkedin.com/in/marksie1988) |
|:--:|
| **marksie1988 (Steven Marks)** |

## Support

Reach out to me at one of the following places:

- via [Discord](https://discord.gg/6fmekudc8Q)
- Raise an issue in GitHub

## Donate

Please consider supporting this project by sponsoring, or just donating a little via [our sponsor page](https://github.com/sponsors/marksie1988)

## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-orange.svg?style=flat-square)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

- Copyright © [Total Debug](https://totaldebug.uk "Total Debug").
