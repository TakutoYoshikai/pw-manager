# pw-manager

This is a simple password manager on Ubuntu.

Account information is encrypted.


### Prerequisites
* Ubuntu 20.04

### Requires
* srm
* openssl

### Usage
1. You have to use this after you copy this repository to your private repository because destination to save is github repository.
2. You have to register password for using this.
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
