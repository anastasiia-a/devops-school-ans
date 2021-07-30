## Task 1

1. Create a playbook that installs the Apache webserver on a managed host with the following requirements:
    - install the `httpd` package;
    - turn on the webserver service and check that it is running;
    - create a `/var/www/html/index.html` file with the text 'Welcome to my webserver';
    - use the `firewalld` module to open the ports of the brandmauer ports required for the webserver to work properly.
    
2. Create a playbook that:
    - remove the `httpd` from managed hosts;
    - remove the `/var/www/html/index.html` file;
    - close the ports on the firewall that the webserver use. 
    
3. Create a playbook to modify the `etc/default/grub` file. It should add
the parameters `net.ifnames=0 and biosdevname=0` to the line that runs the kernel boot.
Execute `grub2-mkconfig`, which will write changes to `/etc/default/grub`.
Use the `lineinfile` module to change the configuration file.
