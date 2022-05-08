# Ansible Gentoo Installer

PLEASE REMEMBER! `hard_drive` will be ereased during the running.

## Usage

To install Gentoo Linux on your computer you have to define the default values
located in the `vars/main.yml`

## Values with description

| Value           | Description                                |
| --------------- | ------------------------------------------ |
| `hard_drive`    | Default hard drive e.g /dev/sda            |
| `hostname`      | Hostname for the Gentoo                    |
| `root_password` | Default root password after installation   |
| `arch`          | Architecture e.g amd64                     |
| `mirror`        | Mirror for downloading the repository tree |
