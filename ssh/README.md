# ssh

Introduction to SSH: connecting to a remote server with an RSA key pair.

## Requirements

- Ubuntu 20.04 LTS
- Bash scripts start with `#!/usr/bin/env bash`, have a comment on line 2,
  are executable and end with a new line

## Files

| File | Description |
|------|-------------|
| `0-use_a_private_key` | Connects to the server as `ubuntu` using the private key `~/.ssh/school`. |
| `1-create_ssh_key_pair` | Creates a 4096-bit RSA key pair named `school`, protected by the passphrase `betty`. |
| `2-ssh_config` | SSH client configuration: uses `~/.ssh/school` and refuses password authentication. |

## Author

sanol-1
