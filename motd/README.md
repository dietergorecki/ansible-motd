# Motd
## Description
This role deploys a motd to greet users and admins.
## Instructions
Define the `motd` variable, it will become your motd !
```
motd: |+2
  Welcome to the cluster !
```
On Ubuntu you can choose to remove the default motd or not with the `motd_remove_default` variable. Default is `false`.
```
motd_remove_default: true
```
On Ubuntu if you choose to keep the default motd you can choose in which order you want it displayed. Default is `20`.
```
motd_ubuntu_sequence: 50
```
