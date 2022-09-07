---
layout: default
---

# Git

## Installatie

1. Navigeer naar <a href="https://git-scm.com/download" target="_blank">deze pagina</a>
1. Klik op je besturingssysteem om de laatste versie te downloaden
    * Gebruik je macOS en ben je vertrouwd met homebrew? Installeer dan via homebrew. Als je niet vertrouwd bent met homebrew download dan de binary installer.
1. Voer de installer uit
   * Laat git installeren op de standaard locatie
   * Installeer de standaard Componenten
       * Gebruik je Windows? Kijk zeker na dat `Git Bash Here` aangevinkt is.
   * Gebruik je Windows? Kies dan Visual Studio Code als editor (installeer dus eerst Visual Studio Code als je dat nog niet gedaan hebt).

## Controle

1. Open een shell door...
     * op windows het startmenu te openen en `git bash` in te typen, gevolgd door enter
     * op macOS een terminal te openen (voer `terminal` in in Spotlight Search)
1. Voer in:
   ```bash
   git --version
   ```
   Dit zou `git version 2.37.3` moeten weergeven, waarbij het versienummer mogelijks lichtjes anders is. Je wil vooral niet `command not found` zien.
1. Voer in:
   ```bash
   git config --global user.email "jan.janssens@student.ucll.be"
   ```
   waarbij je het e-mailadres vervangt door het jouwe
1. Voer in:
   ```bash
   git config --global user.name "Jan Janssens"
   ```
   waarbij je je eigen naam invult tussen de aanhalingstekens