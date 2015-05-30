# Vagrant_LASP_server
Vagrantfile, shell provisioner, Apache conf file, and directory structure for a basic LASP (Linux, Apache, SQLite, PHP) server.

## System Requirements
To use this Vagrantfile you will need a basic Vagrant setup.  This includes [Vagrant](https://www.vagrantup.com/) and a VM provider, such as Oracle's [VirtualBox](https://www.virtualbox.org).  For more information on how to use Vagrant, see the Vagrant *[Getting Started](https://docs.vagrantup.com/v2/getting-started/index.html)* page.  You will also need root user (sudo) permissions to launch the VM, as we are assigning a custom hostname.

## Setup
Clone or download the ZIP archive of this Git repository to your project folder.  The directory structure will look like this:

Root Folder *This is the main folder for the project and can be of any name that you choose.*
|
- /public_html *This folder contains all the files for your site.*
|
- /conf *This folder contains the Apache .conf file for site configuration.*
|
- /vagrant *This folder contains the Vagrantfile and lasp.sh provisioner file.*

By default the site will be named lasp.dev.  If you wish to change this to a different name (e.g. my-site.dev) you must change every reference to lasp.dev in the following files to the custom name:
