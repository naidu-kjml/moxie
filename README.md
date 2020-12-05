# Project Moxie

## About
Moxie is a personal I.T. infrastructure passion project written in Ansible and executed using Jenkins. It is a growing collection of actualized systems, configuration management code, and automation used in exploring microservices. It also just keeps a handful of fun and useful projects managed and secured.

## Quick Start

To set this on a local virtual machine follow these simple steps.

### Prerequisites

Development and demonstrations are done using Vagrant and VirtualBox. You will need to install these before continuing.

### Installation

1. Clone this repository
   ```sh
   git clone https://github.com/krislamo/moxie
   ```
2. Set the `PLAYBOOK` environmental variable to a development playbook name in the `dev/` directory

   The following `PLAYBOOK` names are available: `dockerbox`, `hypervisor`, `minecraft`, `moxie`, `nextcloud`, `nginx`, `seedbox`.
   ```sh
   export PLAYBOOK=dockerbox
   ```
3. Bring the Vagrantbox up
   ```sh
   vagrant up
   ```
