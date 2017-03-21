# trellis-commands

## Remote server
```ansible-playbook server.yml -e env=production```

## Remote server only nginx
```ansible-playbook server.yml -e env=production --tags wordpress```
