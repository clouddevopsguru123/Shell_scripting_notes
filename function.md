Function in shell scripting
===========================

function is nothing but the block statement or commands.
main usage of function is reusability.


syntax:
-------
```
function function_name () {
    command ......
}
```

```
#!/bin/bash

echo "Welcome to cloud devops guru cheannel Raj"
echo "Welcome to cloud devops guru cheannel Ram"
echo "Welcome to cloud devops guru cheannel sham"

```

```
#!/bin/bash

function welcome () {
    Name=$1
    echo "Welcome to cloud devops guru cheannel $Name"
}

welcome Raj
```
```
sudo apt update 
sudo apt install <package name>
```

```
#!/bin/bash

function install () {
    package=$1
    sudo apt update -y
    sudo apt install $package
}

install tree
```

```
#!/bin/bash

function remove () {
    package=$1
    sudo apt purge $package -y
}

remove tree

```

```
#!/bin/bash

package=$1
function install () {
    sudo apt update -y
    sudo apt install $package
}

install 

```

