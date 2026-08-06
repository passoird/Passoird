# 🔒 Passoird  [![Latest Release](https://img.shields.io/github/v/release/passoird/Passoird)](https://github.com/passoird/Passoird/releases/latest)

A multi-user password manager with built-in application locking, for Linux.
*Gestionnaire de mots de passe multi-utilisateur avec verrouillage d'applications, pour Linux.*

---

## English

### Features
- 🗂 Vault organized into 6 categories: Web, Local, Network, Hardware, APK, Other
- 🔐 Reversible encryption (GPG/OpenSSL) + irreversible SHA-256 hash for the master password
- 🛡 Application locking (applock) — require authentication before an app launches
- ⌨️ Configurable keyboard shortcut (F2–F10) to open the app instantly
- 👥 Native multi-user support, isolated per session
- 🖥 X11 & Wayland compatible
- 🎲 Built-in password generator
- ☁️ Encrypted cloud backup (rclone)

### Installation

```bash
sudo apt update
sudo apt install ./passoird-1.0.deb
```

This pulls in all dependencies automatically (`zenity`, `jq`, `pwgen`, `rclone`, `xclip`, `wl-clipboard`, etc.). `keyd` (for the shortcut) is also installed automatically if possible.

The installer **automatically runs the keyboard shortcut setup** at the end (a Zenity window asks you to pick a key). If it doesn't appear, run it manually:

```bash
sudo /usr/lib/passoird/raccourci.bash
```

Then launch with:
```bash
passoird
```

---

## Français

### Fonctionnalités
- 🗂 Coffre organisé en 6 catégories : Web, Local, Réseau, Matériel, APK, Autre
- 🔐 Chiffrement réversible (GPG/OpenSSL) + hachage SHA-256 irréversible pour le mot de passe maître
- 🛡 Verrouillage d'applications (applock) — exige une authentification avant le lancement d'une app
- ⌨️ Raccourci clavier configurable (F2–F10) pour ouvrir l'app instantanément
- 👥 Support multi-utilisateur natif, isolé par session
- 🖥 Compatible X11 & Wayland
- 🎲 Générateur de mots de passe intégré
- ☁️ Sauvegarde cloud chiffrée (rclone)

### Installation

```bash
sudo apt update
sudo apt install ./passoird-1.0.deb
```

Cela installe automatiquement toutes les dépendances (`zenity`, `jq`, `pwgen`, `rclone`, `xclip`, `wl-clipboard`, etc.). `keyd` (pour le raccourci) est aussi installé automatiquement si possible.

L'installateur **lance automatiquement la configuration du raccourci clavier** à la fin (une fenêtre Zenity vous demande de choisir une touche). Si elle n'apparaît pas, relancez-la manuellement :

```bash
sudo /usr/lib/passoird/raccourci.bash
```

Puis lancez avec :
```bash
passoird
```

<!--
**passoird/Passoird** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
