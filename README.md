# Vaultwarden with Quadlet

## What is this?

| Task         | Tool        |
|--------------|-------------|
| Provisioning | Ansible     |
| Testing      | Vagrant     |
| Managing     | Quadlet     |
| Service      | Vaultwarden |

## Ansible roles

### [vaultwarden](ansible/roles/vaultwarden/)

Create container and volume unit files, enable them and start them. The unit
files are stored in container manager user directory.

Check role variables for default values which can be modified for different
deployments.

## Author

Dušan Simić <dusan.simic1810@gmail.com>

## License

[MIT](LICENSE)
