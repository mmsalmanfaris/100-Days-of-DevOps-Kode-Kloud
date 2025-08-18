## Day 03

To connect to a remote server:

```bash
ssh user@hostname
```

To add a user who cannot log in:

```bash
sudo vi /etc/ssh/sshd_config
```

Change PermitRootLogin yes to:

```bash
PermitRootLogin no
```

Restart the sshd:

```bash
systemctl restart sshd
```

### Repeat on All 3 App Servers
### Remove # from PermitRootLogin