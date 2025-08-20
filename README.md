# Ansible Fedora 42 Configurations

This is my configurations for my Fedora 42 machine using the `ansible-pull` command.

![Desktop](https://raw.githubusercontent.com/Adnan-Najjar/ansible_personal_config/main/.github/images/Desktop.png)

## What does it do?

- **Make `dnf` faster** by enabling parrallel downloads and fastest mirrors.
- **Install packages** I use from:
  - `dnf`
  - `dnf COPR`
  - `flatpak`
  - `cargo` (if needed)
- **Enable and start** `dnf5` automatic updates.
- **Uninstall applications** installed by Fedora 42 that I don't use.
- **Install GNOME extensions** and apply GNOME settings using `dconf`.
- **Copy over** wallpaper and config files for programs I use (e.g., `zsh`, `nvim`, etc...).
- **Set up Zen Browser** (extensions and settings).

> So, running this will change your system, so **don't use it on your own machine!**

# How to run it
**Don't :)**

or 

Use this:
```bash
ansible-pull -KU https://github.com/adnan-najjar/ansible-fedora-config
```
