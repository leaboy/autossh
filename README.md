# autossh
auto login ssh fast and easy
# usage
```
./autossh <ip>|<server name>|<ip mantissa> [user] [password] [port]
```
## example
```
./autossh 102.12.xx.101
./autossh dev
./autossh 101
./autossh 101 user_xx
./autossh 101 user_xx password
./autossh 101 user_xx password port
```
## config file
```
dev   102.12.xx.101		user_xx		password                  22
idc   102.12.xx.101		user_xx		/Users/xxx/.ssh/identity  22
```
