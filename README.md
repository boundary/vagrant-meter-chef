# Vagrant Environment for Meter using Chef for provisioning

Example of using Vagrant to stand up a VM and deploy meter using Chef

## Prerequisites

- Vagrant version 1.7.4 or later [download here](https://www.vagrantup.com/downloads.html)
- Virtual Box 4.3.30 or later [download here](https://www.virtualbox.org/wiki/Downloads)
- Git version 1.7 or later

## Installation and Configuration

1. Download the contents of the GitHub repository
    ```bash
$ git clone
    ```

2. Modify `Vagrantfile` with your _api-token_
    ```json
chef.json = {'boundary_meter' => {'token' => '<api-token>' } }
    ```

## Starting the Virtual Machine

1. Run the following command:

    ```bash
    $ vagrant up --provider virtualbox
    ```


## Stopping the Virtual Machine


1. Run the following command:

     ```bash
$ vagrant halt
     ```
