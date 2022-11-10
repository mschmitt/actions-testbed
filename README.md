A simple proof-of-concept for ssh-agent and rsync in Github actions.

The receiving rsync is configured in ~/.ssh/authorized_keys as follows:

`restrict,command="rrsync /foo/deploy" ssh-ed25519 AAAAC3...`

Gitlab companion repository is here: https://gitlab.com/maschmitt/ci-cd-testbed
