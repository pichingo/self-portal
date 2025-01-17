# Self Portal

##### Written by [Amado Tejada](https://www.linkedin.com/in/amadotejada/)

[![build](https://github.com/amadotejada/self-portal/actions/workflows/python.yml/badge.svg)](https://github.com/amadotejada/self-portal/actions/workflows/python.yml)

Self Portal is a **cross-platform** desktop application used to deploy software across your endpoints fleet while providing the same user experience across multiple software management solutions.

<img src="./screenshots/main.png" width="100%">

This is a front-end for users and does not connect directly with software management tools. Instead, it calls out to the software management tools [below](#supports) to install the packages.

Self Portal is in beta and should be tested extensively. 

<!-- To discuss Self Portal join the `#self-portal` channel on the [MacAdmins Slack](https://www.macadmins.org) -->

### Features

* cross-platform
* supports various deployment tools
* python framework bundled
* no end-user runtime dependencies
* dark & light themes
* log viewer

### Supports

| macOS | Windows | Linux |
|:---------------------:|:---------------------:|:---------------------:|
| [Chef](https://github.com/chef/chef) | [Chef](https://github.com/chef/chef) | [Chef](https://github.com/chef/chef) |
| [Jamf](https://docs.jamf.com/technical-articles/Manually_Initiating_a_Policy.html) | [Choco](https://github.com/chocolatey/choco) | [apt](https://manpages.ubuntu.com/manpages/xenial/man8/apt.8.html)/[yum](https://man7.org/linux/man-pages/man8/yum.8.html)/[dnf](https://man7.org/linux/man-pages/man5/dnf.conf.5.html)     |
| [pip](https://pip.pypa.io/en/stable/getting-started/) | [pip](https://pip.pypa.io/en/stable/getting-started/) | [pip](https://pip.pypa.io/en/stable/getting-started/)
| [autopkg](https://github.com/autopkg/autopkg) | [Scoop](https://github.com/ScoopInstaller/Scoop) | [snap](http://manpages.ubuntu.com/manpages/bionic/man1/snap.1.html)/[flatpak](https://docs.flatpak.org/en/latest/using-flatpak.html) |

* last tested: 04/21/22
* chef only tool with extensive testing
* testing [gorilla](https://github.com/1dustindavis/gorilla), [munki](https://github.com/munki/munki/wiki/managedsoftwareupdate), and [brew](https://github.com/Homebrew)

## User Interface

<details>
<summary>Preview UI Demo</summary>

![UI Demo](./screenshots/startdemo.gif)
</details>

### macOS

| Dark  | Light |
|:-----:|:-----:|
| <img src="./screenshots/mac_dark.png" width="100%">   | <img src="./screenshots/mac_light.png" width="100%">   |

### Windows

| Dark  | Light |
|:-----:|:-----:|
| <img src="./screenshots/win_dark.png" width="100%">   | <img src="./screenshots/win_dark.png" width="100%">   |

### Linux

| Dark  | Light |
|:-----:|:-----:|
| <img src="./screenshots/linux_dark.png" width="100%">   | <img src="./screenshots/linux_light.png" width="100%">   |

### Other

| Theme Chooser  | Log Viewer |
|:-----:|:-----:|
| <img src="./screenshots/themes.png" width="100%">   | <img src="./screenshots/logviewer.png" width="100%">   |

## Getting Started

[Wiki - work in progress](https://github.com/amadotejada/self-portal/wiki)

##
### Disclaimer

This software {Self Portal} has not been endorsed or supported by any of the software mentioned [above](#supports) and is in no way associated with them and/or its subsidiaries or affiliate.

### License

Self Portal is released under the [Apache 2.0 License](https://github.com/amadotejada/self-portal/blob/main/LICENSE)
####
