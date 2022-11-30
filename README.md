<h1 align="center">
  Ansible Role for <a href="https://fishshell.com/">Fish Shell</a> & <a href="https://github.com/oh-my-fish/oh-my-fish/">Oh My Fish</a>
</h1>

<p>
  <a href="./LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" />
  </a>
</p>

> This repo contains a zero-configuration Linux-distro agnostic Ansible role that installs <a href="https://fishshell.com/">Fish Shell</a> and <a href="https://github.com/oh-my-fish/oh-my-fish/">Oh My Fish</a>.

## Requirements

- No additional requirements.

## Example Ansible Playbook

```yaml
- hosts: 127.0.0.1
  roles:
    - role: ansible-role-fish-omf
      vars:
        omf_packages:
          - https://github.com/edc/bass
          - https://github.com/derekstavis/plugin-nvm
          - https://github.com/oh-my-fish/plugin-aws
          - https://github.com/evanlucas/fish-kubectl-completions
```

## Author

👤 **Alexander Danilenko**

* Website: https://danilenko.in
* Github: [@alexander-danilenko](https://github.com/alexander-danilenko)
* LinkedIn: [@alexander-danilenko](https://linkedin.com/in/alexander-danilenko)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/alexander-danilenko/ansible-role-fish-omf/issues). 

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2022 [Alexander Danilenko](https://github.com/alexander-danilenko).<br />
This project is [MIT](./LICENSE) licensed.

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_