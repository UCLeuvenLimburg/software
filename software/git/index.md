---
layout: default
---
# Git

## Windows

1. Wees zeker dat je eerst [Visual Studio Code](/software/vscode/index.md) hebt geïnstalleerd.
2. Download [Git](https://git-scm.com/download/win). Kies voor "64-bit for Windows Setup".
3. Start het installatieprogramma. Je krijgt tal van vensters met opties te zien.
   * Kies voor de standaard locatie.
   * Wees zeker dat "Git Bash Here" aangevinkt staat.
   * Kies Visual Studio Code als editor.
   * Alle andere opties kan je op hun standaard instelling laten staan.
4. Nadat Git geïnstalleerd is, open Git Bash door het startmenu te openen en `git bash` in te typen, gevolgd door enter.
5. Voer in:
   ```bash
   git --version
   ```
   Dit zou `git version 2.28.0.windows.1` moeten weergeven, waarbij het versienummer mogelijk wat verschilt.
   Je wil vooral niet `command not found` zien tevoorschijn komen.
6. Voer in:
   ```bash
   git config --global user.email "jan.janssens@student.ucll.be"
   ```
   waarbij je het e-mailadres vervangt door het jouwe.
7. Voer in:
   ```bash
   git config --global user.name "Jan Janssens"
   ```
   waarbij je je eigen naam invult tussen de aanhalingstekens.

## MacOS

1. Download en installeer [Git](https://git-scm.com/download/mac).
2. Open een terminal (Voer `terminal` in in Spotlight Search).
3. Voer in:
   ```bash
   git --version
   ```
   Dit zou `git version 2.23.0` moeten geven, waarbij het versienummer mogelijk wat verschilt.
4. Voer in:
   ```bash
   git config --global user.email "jan.janssens@student.ucll.be"
   ```
   waarbij je het e-mailadres vervangt door het jouwe.
5. Voer in:
   ```bash
   git config --global user.name "Jan Janssens"
   ```
   waarbij je je eigen naam invult tussen de aanhalingstekens.


TODO: een `git commit` uitvoeren gaat enkel als ze de config-stappen hebben uitgevoerd. Dus misschien hen ter verificatie een kleine repo laten aanmaken (`git init`), een bestand aanmaken, dat adden en committen.
TODO: GitHub authenticatie kan ook soms problemen opleveren, is OS afhankelijk. Mac gebruikers hebben meestal extra hulp nodig (moeten werken met token als ik me goed herinner)