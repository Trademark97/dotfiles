# Unified Dotfiles Repository
---
## Contents
```
/etc
-- /etc/portage
---- /etc/portage/make.conf
      My compilation and Portage options.
---- /etc/portage/package.accept_keywords
      Where I specify what ebuilds I want live (-9999 or -git) versions for.
---- /etc/portage/package.mask
      Where I specify what ebuilds should never be installed.
---- /etc/portage/package.unmask
      Where I specify what ebuilds to manually unmask (since I automask all ebuilds
      from overlays, to avoid potential issues with Portage).
---- /etc/portage/package.use
      My per-package USE flags.
/home
-- /home/<my_username>
---- /home/<my_username>/.config/
     This is where I store my configuration files for things like i3-gaps, polybar, irssi, et al.
---- /home/<my_username>/.scripts/
     Here I put some scripts that I find useful.
addenda
-- /desktop
     Where I put package.* modifications specific to my desktop.
-- /laptop
     Where I put package.* modifications specific to my laptop.
```
## System Information
### GUI
---
**WM**: <i><code>i3-gaps</code></i>  
**Statusbar**: <i><code>polybar</code></i>  
**Launcher**: <i><code>rofi</code></i>  
**File manager**: <i><code>thunar</code></i>  
**Web browser**: <i><code>Mozilla Firefox</code></i>
### Base
---
**Kernel sources**: <i><code>gentoo-sources</code></i>  
**System packages**: <i><code>~amd64 (unstable)</code></i>  
**Shell**: <i><code>bash or zsh</code></i>
