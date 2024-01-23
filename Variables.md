what is the variable:
=====================

variable is nothing but the momory location where we can store the data.

there are two types of variables in shell script:
-------------------------------------------------
  - system variable
  - user defined variable

  system variables defined by the os
  we will define the user defined variable while writing shell or in ternminal


  syntax:
  ------
 ```
  variable_name=vaule_of_variable
  NAME="RAM"
 ```
 ```
  for use your variable you can use the $NAME
```
```
  install the web server in redhat machine

  webser package name is :  httpd

  sudo yum install httpd -y
  sudo systemctl enable httpd
  sudo systemctl start httpd


  sudo systemctl status httpd

```

```
#!/bin/bash
#Author: ram
#Discription: this is for install the httpd package
#Date creation: 15/10/23
#Date of modify:

sudo yum install vsftpd -y
sudo systemctl enable vsftd
sudo systemctl start vsftd
```

```
#!/bin/bash
#Author: ram
#Discription: this is for install the httpd package
#Date creation: 15/10/23
#Date of modify:
package_name=httpd

sudo yum install $package_name -y
sudo systemctl enable $package_name
sudo systemctl start $package_name

```

```
#!/bin/bash
#Author: ram
#Discription: this is for install the httpd package
#Date creation: 15/10/23
#Date of modify:
package_name=vsftpd

sudo yum install $package_name -y
sudo systemctl enable $package_name
sudo systemctl start $package_name
```



