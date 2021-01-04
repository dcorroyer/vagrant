# Vagrantfile

A simple Vagrantfile to provide a debian virtual machine to make all my devs with the same OS everywhere.

If you are on windows, replace the line 6 of the Vagrantfile:

	config.vm.synced_folder "C:/Users/Cancel/Documents/projects/mycms/", "/var/www/mycms/"
