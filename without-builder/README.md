# Manual EE build process

This builds a custom EE with collections installed from a private
automation hub.

Build the EE with

```
podman build -t ee . --build-arg ANSIBLE_GALAXY_SERVER_PRIVATE_HUB_TOKEN=<token>
```
