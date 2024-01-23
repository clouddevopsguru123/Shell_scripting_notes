For loop in shell scripting:
===========================
loop is nothing but the repeative task will execute until the condition is met.

syntax:
-------
```
for <variable> in <list>
do
<commands>
done
```

echo "Hello world"
echo "Hello world"
echo "Hello world"
echo "Hello world"
echo "Hello world"



range for
{1..10}

```
#!/bin/bash
#Author: ram
#Discription: this is for understanding the for loop
#Date creation: 
#Date of modify:

for i in {1..10}
do 
 echo "Hello world"
done
```

```
#!/bin/bash
#Author: ram
#Discription: this is for understanding the for loop
#Date creation: 
#Date of modify:

for i in {10..1}
do 
 echo "$i"
done
```

weekday

"mon tue wed thur fri sat sun"

```
#!/bin/bash
#Author: ram
#Discription: this is for understanding the for loop
#Date creation: 
#Date of modify:

for i in "mon" "tue" "wed" "thur" "fri" "sat" "sun"
do 
 echo "$i"
done
```

```
#!/bin/bash
#Author: ram
#Discription: this is for understanding the for loop
#Date creation: 
#Date of modify:

weekdays=("mon" "tue" "wed" "thur" "fri" "sat" "sun")
for i in ${weekdays[@]}
do 
 echo "$i"
done
```

```
#!/bin/bash
#Author: ram
#Discription: this is for understanding the for loop
#Date creation: 
#Date of modify:

weekdays="mon tue wed thur fri sat sun"
for i in $weekdays
do 
 echo "$i"
done
```

```
#!/bin/bash
#Author: ram
#Discription: this is for understanding the for loop
#Date creation: 
#Date of modify:

packages=("tree" "nginx")
for i in ${packages[@]}
do 
 sudo apt update -y && sudo apt install -y "$i"
done

```

```
#!/bin/bash
#Author: ram
#Discription: this is for understanding the for loop
#Date creation: 
#Date of modify:

packages=("second" "first_second")
for i in ${packages[@]}
do 
mkdir "$i"
done

```









