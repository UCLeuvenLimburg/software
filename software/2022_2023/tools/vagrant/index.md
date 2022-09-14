---
layout: default
---

# Vagrant

**Installeer VMware vóór Vagrant**

## Installatie

1. Navigeer naar <a href="https://www.vagrantup.com/downloads" target="_blank">deze pagina</a>
1. Download de juiste installer afhankelijk van je besturingssysteem
    * Gebruik je Windows? Download dan de Amd64 installer (64bit)
1. Voer de installer uit
1. Navigeer naar <a href="https://www.vagrantup.com/vmware/downloads" target="_blank">deze pagina</a>
1. Download de installer voor de Vagrant vmware Utility
1. Voer de installer uit
1. Open een shell door...
     * op windows het startmenu te openen en `powershell` in te typen, gevolgd door enter
     * op macOS een terminal te openen (voer `terminal` in in Spotlight Search)
1. Voer dit commando uit `vagrant plugin install vagrant-vmware-desktop`


## Controle

1. De plugin is succesvol geïnstalleerd
1. Commando `vagrant -v` retourneert een versienummer
