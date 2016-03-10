Stouts.docker-watchtower
========================

Ansible role to install and start Watchtower

#### Variables

```yaml
watchtower_enabled: yes

watchtower_image: centurylink/watchtower
watchtower_follow: ""
watchtower_options: ""
```

#### Usage

Add `Stouts.docker-watchtower` to your roles and set vars in your playbook file.

Example:

```yaml

- hosts: all

  roles:
    - Stouts.docker
    - Stouts.docker-watchtower
```

#### License

Licensed under the MIT License. See the LICENSE file for details.

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Stouts/Stouts.docker-watchtower/issues)!
