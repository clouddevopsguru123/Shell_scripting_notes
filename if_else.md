conditional statement:
========================
conditional statement is used for evaluate the condition.

sysntax of if:
--------------
```
if [ exp ]
then 
  statement
fi
```

sysntax of if_else:
-------------------
```
if [ expression]
then
  statement
else
  statement
fi
```

operator:
---------
```
== : equal to 
!=: not equal to
&&: logic and
-eq: Equality check
-ne: inquality check
-lt: less than
-le: less than equal to 
-gt: greater than 
-ge: greater than or equal to 
```

```
#!/bin/bash
#Author: ram
#Discription: if else statement
#Date creation: 18/11/23
#Date of modify:
marks=34

if [ $marks -ge 35 ]
then
   echo "passed"
else
   echo "failed"

fi
```

