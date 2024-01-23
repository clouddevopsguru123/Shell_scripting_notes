if_elif_else:
=============

student can get 35 or more than 35
less than 60 more 60

35 below 60 then he is passed with second class
if student get more than or equal to 60 he is passed with 
first class.
if student get 75 or above 75 student passed with
distinction.

syntax:
-------
```
if [ express ]
then
elif [ expression ]
then
elif [ expression]
then
else
fi
```


```
#!/bin/bash
#Author: ram
#Discription: if elif else statement
#Date creation: 25/11/23
#Date of modify: 
marks=34

if [ "$marks" -ge 35 ]
then
  if [ "$marks" -ge 75 ]
  then
    echo "passed with distinction"
  elif [ "$marks" -ge 60 ]
  then
    echo "passed with first class"
  elif [ "$marks" -ge 35 ]
  then
    echo "passed with second class"
  fi
else
  echo " failed"
fi
```
