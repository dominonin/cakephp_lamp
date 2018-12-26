# docker_lamp
Docker Compose container with LAMP-like properties
Includes the following containers for LAMP like experience:
- PHP 5.6.38
- Apache server
- PHPMyAdmin
- MariaDB SQL Server
- Composer installed in apache container
- Bind mount with src directory for apache server

How to use:

Make sure you have Docker and Docker Compose installed.
Download the files from this repo and shove them into any directory you want.
If you currently have source code that you want to be shared with the apache folder, put it into the src directory.

Open terminal or powershell if on windows and go to this directory, where the .yml file is stored.

Execute 'docker-compose up' in the terminal.

To exit, press Control + C on your keyboard when the terminal is focused.
