# Easy Apache
Easily setup Apache server by using this script, it takes you step by step and setup everything you need

## How to use easy-apache
Install easy-apache on to your server (copy paste below lines to your terminal)
```
sudo add-apt-repository ppa:realpvn/easy-apache
sudo apt-get update
sudo apt-get install easy-apache
```

One command to setup everything, installs Apache & SSL
```
easy-apache -f
```
That is it! 🤩
  
  
## Options & Usage
```
Usage:
easy-apache [options]

Options:
-f:   Full setup, installs apache and ssl for sites
-a:   Adding new site (includes apache install)
-s:   Install SSL certificate for sites available
-h:   Help (shows all commands)

Example
easy-apache -f   #for full installation i.e Apache & SSL certificate
easy-apache -a   #for installating Apache server & SSL certificate
easy-apache -s   #for installating SSL certificate
```


## Works on
- Ubuntu 20.04 (focal)  
(will update more once I test)

Give it a ⭐ if it helped you xD
