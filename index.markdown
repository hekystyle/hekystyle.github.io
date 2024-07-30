---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: "Public keys"
pubkeys:
    vpn: "Qm/edx+h+GDYi+jTOiw9+7CYs2AMyHxHDneXWK0bihk="
    pc: "ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIONax9HStki13OGyffBiO1kpCVInERwnjU95Og1V5d8K"
    kubuntu: "ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIE0PXSE5bXEisQV1Y8BpApZwes/wF0sWOutOLtk4ZzDO"
---

| Name | Key |
|------|-----|
{% for pubkey in page.pubkeys %}| {{ pubkey[0] }} | `{{ pubkey[1] }}` |
{% endfor %}
