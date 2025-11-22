# Use Podman Quadlet with uptime-kuma

Deploy uptime-kuma with Podman Quadlet

## Installation

Make sure to have the linux podman role.

```bash
chmod +x requirements
./requirements.sh
```

## Usage

To start uptime-kuma on your device :
```bash
ansible-playbook start-run.yaml
```
To stop this installation of uptime-kuma on your device :
```bash
ansible-playbook stop-run.yaml
```

## License

[GPL](https://opensource.org/license/GPL-2.0)
