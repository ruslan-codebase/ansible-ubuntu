---
  title: ubuntu ansible playbook
---

# Personal Ubuntu machine setup

## Roles

  - `common`:
    - Ensures specific folders are present
    - Ensures system is up to date
    - Installs basic dependencies
  
  - `desktopapps`:
    - Ensures my favorite applications are installed
  
  - `devtools`:
    - Ensures VCS, SDKs, runtimes, compilers, IDEs, fonts, shells, etc. are installed and configured

## Getting started

**! currently uptimized for Ubuntu 20.04 !**

  - ensure `ansible` is installed
  - execute **`ansible-playbook -K ubuntusetup.yml`** to setup the machine.

