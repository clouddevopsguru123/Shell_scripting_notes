Passing the Arguments 
=======================

```
#!/bin/bash
#Author: ram
#Discription: Display the hello world message
#Date creation: 24/10/23
#Date of modify: 24/10/23

#echo Hello World
echo $0 $1 $2 
```

```
#!/bin/bash
#Author: ram
#Discription: Display the hello world message
#Date creation: 24/10/23
#Date of modify: 24/10/23

#echo Hello World
#echo $1 $2

args=("$@")

echo ${args[0]} ${args[1]}
```

```
#!/bin/bash
#Author: ram
#Discription: Display the hello world message
#Date creation: 24/10/23
#Date of modify: 24/10/23

#echo Hello World
#echo $1 $2

args=("$@")

echo $@

```

```

#!/bin/bash
#Author: ram
#Discription: Display the hello world message
#Date creation: 24/10/23
#Date of modify: 24/10/23

sudo apt update -y
sudo apt -y install $1 $2
#sudo apt install $2
```

```
#!/bin/bash
#Author: ram
#Discription: Display the hello world message
#Date creation: 24/10/23
#Date of modify: 24/10/23

Name=$1
age=$2

echo "this is $Name"
echo "$Name your are  $age old" 

echo $#
```

