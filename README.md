# Ansible Workstation

Ansible configs to set up a personal workstation. Primary goals are
reproducibility and ease of use.

## Quick Start

1. Install these packages:

   - `git`
   - `ansible` (including `ansible-playbook`)

   On Debian-based systems (e.g. Debian, Ubuntu), run:

   ```
   sudo apt install ansible git
   ```

2. Download this repo locally and clone available git submodules.

   ```
   git clone git@github.com:akirabaruah/ansible-workstation.git --recurse-submodules
   ```

3. Run `ansible-playbook` to initialize the local system. This command uses
   default user configs.

   ```
   ansible-playbook init.yaml -i localhost
   ```
