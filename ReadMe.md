# Some important things used in this repo..
-----------------------------------------------------------------------------------------------------------
**--shell /bin/bash** ->it sets the login shell to /bin/bash.
/bin/bash. The login shell is the program that is started when the user logs in and provides an interactive command-line interface.

For eX::
sudo useradd --shell /bin/bash john
This command creates a new user named "john" and sets the default shell to /bin/bash for that user. 

-------------------------------------------------------------------------------------------------------------
**--shell /bin/false node_exporter**  ->Setting /bin/false as the shell for a user in Unix-like operating systems serves the purpose of creating a user account that cannot log in ,
/bin/false as their shell are typically created for the sole purpose of running specific system services or tasks without allowing direct login.Preventing Login for security purpose by any user for system services

-------------------------------------------------------------------------------------------------------------
**--no-create-home** ->--no-create-home: This option specifies that the user account being created should not have a home directory. The home directory is typically a directory where a user's personal files and configuration settings are stored.

-------------------------------------------------------------------------------------------------------------

Note::

**daemon-reload**: This is a subcommand of systemctl. It reloads the systemd manager configuration. 