# pw-manager

This is a simple password manager on Ubuntu.

You should use this after you copy this repository to your private repository because destination to save is github repository.

Account information is encrypted.

You have to register password for using this.

### Prerequisites
* Ubuntu 20.04

### Requires
* srm
* openssl

### Usage
```
# initialize
password new

# change master password
password change

# show all account information
password show

# backup to github
password save

# add account
password register <service name>

# show email
password <service name> -email

# show password
password <service name> -pw
```
