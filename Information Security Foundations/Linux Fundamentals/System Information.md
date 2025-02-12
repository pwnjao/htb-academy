### Find out the machine hardware name and submit it as the answer.

##### Solution
* I use ``uname --help`` command to see details of the command on terminal
* Use ``uname -m`` to print machine name

___

### What is the path to htb-student's home directory?

##### Solution
* I search on Google how to find the path
* And discover the path on ``cd home/htb-student``

___

### What is the path to the htb-student's mail?

##### Solution

* I search on Google and locate this command:
```bash
env | grep MAIL
```

___

### Which shell is specified for the htb-student user?

##### Solution

* I search on Google and locate this command:
```bash
env | grep SHELL
```

___

### Which kernel release is installed on the system? (Format: 1.22.3)
##### Solution
* Use ``uname -r`` to see the kernel release

___

### What is the name of the network interface that MTU is set to 1500?

##### Solution
* I use this command:
```bash
ifconfig
```
