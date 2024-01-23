user input:
==========
Taking input from the user using read command

```
#!/bin/bash
#Author: ram
#Discription: this is for install the httpd package
#Date creation: 19/10/23
#Date of modify: 19/10/23

echo "please insert the user name"
read name
echo "please insert the age "
read age
echo "please insert the city name"
read city

echo "Welcome to our shell script practice ${name} , ${name}, ${age} , ${city} "

```

```
#!/bin/bash
#Author: ram
#Discription: this is for install the httpd package
#Date creation: 15/10/23
#Date of modify:
echo "please enter the package for install in server"
read package_name

apt update -y
apt install $package_name
```

```
#!/bin/bash
#Author: ram
#Discription: this is for install the httpd package
#Date creation: 15/10/23
#Date of modify:

read -p "Enter package name " package_name

apt update -y
apt install $package_name

```


```
#!/bin/bash
#Author: ram
#Discription: this is for install the httpd package
#Date creation: 15/10/23
#Date of modify:

read -p "Enter user name " name
read -sp "Enter user password " passwd

echo "user name is ${name} and password is ${passwd}
```
