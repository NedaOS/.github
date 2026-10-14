# About This Setup

My automated setup for **[Fedora Everything 44](https://fedoraproject.org/misc/#everything)**, built around **[Hyprland](https://hyprland.org/)**, **[Wayland](https://wayland.freedesktop.org/)**, and **[Noctalia](https://noctalia.dev/)**.

The setup is managed with [Ansible](https://ansible.com) and [chezmoi](https://www.chezmoi.io), combining reproducible system provisioning with declarative dotfile management.

Its desktop configuration draws inspiration from [ML4W](https://github.com/mylinuxforwork/dotfiles), [Ryoku](https://github.com/ryoku-dev/ryoku), [Omarchy](https://github.com/basecamp/omarchy), and [Garuda Linux](https://gitlab.com/garuda-linux), bringing together ideas from their workflows, aesthetics, and desktop configurations into a personalized Fedora environment.

## Installation

Run the following command in your terminal:

```bash
curl -fsSL https://raw.githubusercontent.com/NedaOS/fedora-setup/main/scripts/bootstrap.sh | bash
```

**Requirements:**
- Fedora 44
- An internet connection
- A user account with `sudo` privileges
