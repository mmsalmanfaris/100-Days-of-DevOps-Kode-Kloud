
## Switching User to Root

To switch to the root user, use:

```bash
sudo su -
```

## Connecting to a Remote Host via SSH

To connect to a remote server:

```bash
ssh user@hostname
```

## Creating a User with No Login Shell

To add a user who cannot log in:

```bash
sudo useradd -s /sbin/nologin username
```
