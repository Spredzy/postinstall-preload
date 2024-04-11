# Pre Load Job Templates

## Requirements

Make sure the following collections are installed:

  * infra.controller_configuration
  * ansible.controller (or awx.awx)


Ensure the following variable are exported

  * CONTROLLER_HOST
  * CONTROLLER_USERNAME
  * CONTROLLER_PASSWORD

## Run

```
#> ansible-playbook main.yml
```
