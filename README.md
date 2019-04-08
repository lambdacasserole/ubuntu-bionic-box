# Vagrant Box (Ubuntu 18.04 Bionic Beaver)
Plain Vagrant box with Ubuntu 18.04 Bionic Beaver with desktop system installed.

## Prerequisites
You'll need [Oracle VM VirtualBox](https://www.virtualbox.org/wiki/Downloads) installed as well as [Vagrant](https://www.vagrantup.com/downloads.html).

### Plugins
You'll need the `vagrant-reload` plugin because the box needs a restart after provisioning. Install it like this:

```bash
vagrant plugin install vagrant-reload
```

## Setup
Like any Vagrant box, run:

```bash
vagrant up
```

From there, use:

```bash
vagrant ssh
```

To access the box over SSH.

## Usage
From a terminal, run:

```bash
sudo isabelle-utp-ide
```

Note that `sudo` is only needed on first run to permit write access to the directory for compilation. After this is complete, `isabelle-utp-ide` by itself will suffice.

## Details
The box is running Ubuntu "Bionic Beaver" 18.04 LTS (Desktop) with:

* Gnome 3 Desktop
* VirtualBox Guest Additions 6.0.4
