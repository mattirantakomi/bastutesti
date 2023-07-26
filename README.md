Asenna Ansible Community.General -moduuli:
`ansible-galaxy collection install community.general`

Testaa yhteyden toimivuus hosteille:
`ansible-playbook ping.yml`

Päivitä hostit:
`ansible-playbook update.yml`

Lataa Ubuntu 20.04 LTS cloudimg hosteille:
`ansible-playbook ubuntu.yml`

Perusta padat:
`ansible-playbook padat.yml`

Poista padat:
`ansible-playbook poista_padat.yml`

Asenna wg-pinger pitämään WireGuard-tunnelit pystyssä:
`kubectl apply -f https://raw.githubusercontent.com/mattirantakomi/wg-pinger/master/namespace.yaml`
`kubectl apply -f https://raw.githubusercontent.com/mattirantakomi/wg-pinger/master/daemonset.yaml`

