While Loop:
===========

while loop is nothing but the repeat the section of code or block unknow number of time until a specific condition met.

syntax:
-------
```
while [ condition ]
do
 commands
done
```


```
#!/bin/bash
#Author: ram
#Discription: this is for understand the while loop
#Date creation: 
#Date of modify:

while true
do 
 echo "welcome to loop"
done
```
```
#!/bin/bash
#Author: ram
#Discription: this is for understand the while loop
#Date creation: 
#Date of modify:

Number=1
while [[ ${Number} -le 10 ]]
do 
 echo "welcome to loop"
done
```

```
#!/bin/bash
#Author: ram
#Discription: this is for understand the while loop
#Date creation:
#Date of modify:

Number=1
while [[ ${Number} -le 10 ]]
do
 echo ${Number}
 ((Number++))
done
```

3 tables


```
#!/bin/bash
#Author: ram
#Discription: this is for understand the while loop
#Date creation:
#Date of modify:

read -p "please enter a number" number
start_number=1
while [[ ${start_number} -le 10 ]]
do
 echo $((start_number*number))
 ((start_number++))
done
```
```
#!/bin/bash
#Author: ram
#Discription: this is for understand the while loop
#Date creation:
#Date of modify:

while true
do
df -h |grep home
sleep 1
done
```







