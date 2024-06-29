---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: "Public keys"
pubkeys:
    vpn: "Qm/edx+h+GDYi+jTOiw9+7CYs2AMyHxHDneXWK0bihk="
    pc: "ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIONax9HStki13OGyffBiO1kpCVInERwnjU95Og1V5d8K"
---

# VPN server

```plaintext
{{ page.pubkeys.vpn }}
```

## PC SSH

```plaintext
{{ page.pubkeys.pc }}
```
