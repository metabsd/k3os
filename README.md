# k3os with proxmox

Using cloud-init workaround with k3os.

To find the right <id> `qm list`

```
mkdir -p /var/lib/vz/snippets
cp -p k3os-01-config.yaml /var/lib/vz/snippets/
qm set <id> --cicustom user=local:snippets/k3os-01-config.yaml
```
