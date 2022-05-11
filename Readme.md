Ansible Playbook for installing nopcommerce application on Unix Machines
Reference URL - https://docs.nopcommerce.com/en/installation-and-upgrading/installing-nopcommerce/installing-on-linux.html

Steps to Install nopcommerce web application


- Register Microsoft key and feed
- Install the .NET Core Runtime
- Install MySql Server & set root password
- Install the nginx package
- Configure reverse proxy to forward requests to ASP.net core app
- Create directory Download & Unpack nopcommerce application
- Create 2 more directories for nopcommerce to run
- Change owner and group permissions for nopcommerce application file created
- Create nopCommerce as a service by editing content of nopCommerce450.service
- Start nopCommerce450.service and check status
- Restart nginx

