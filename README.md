# Simple docker-compose.yml for running a mssql instance locally with docker
This docker-compose.yml file is for running a mssql instance locally. 

## HOWTO
Clone this repo to a directory you want or just download this repo as zip
### MacOS
https://docs.docker.com/desktop/mac/install/
### Windows
https://docs.docker.com/desktop/windows/install/
### Linux
You can find it yourself, else get a windows or macos machine ;)

### With visual studio code
install the extension SQL Server from Microsoft.

### Credentials and settings
Username: `sa`

Password: `iDTyjZx7dRL4` note: this password is just a random password created to meet the password policy enforced by mssql. never use this in production just change it or add a digit or character.

Port: `1433`

Host: `localhost` or `127.0.0.1` or the host name you have chosen for your machine

### How to start the mssql container
Use a terminal and go to the directory containing the `docker-compose.yml` from this repo and type in `docker-compose up` or `docker-compose up -d` if you don't want to see any output in your terminal.

