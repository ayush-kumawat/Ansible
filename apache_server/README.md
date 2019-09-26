apache_server
=============
This role is to configure a basic apache web server on two different distributions of linux. One is Ubantu and another one is RedHat linux.
After successfull run of the playbook we can check the website page by simple ip address on deafult port 80.
The output looks like:
			"Hello workstation on RedHat"
where "workstation" is the fqdn and "RedHat" is it's distribution.
Firewall is enabled and is handled by adding the port 80 to the firewall

Vars Used
=========
"docroot_dir" is used as the variable for document root directory to be formed on RedHat linux
"documentroot_dir" is used as the variable for the document root directory to be formed on Ubantu disribution
