# Easy Apache
Easily setup Apache server by using this script, it takes you step by step and setup everything you need

## How to use this script
#### Step 1
Clone this repository to your server  
```
git clone https://github.com/realpvn/easy-apache.git
```

#### Step 2
Change directory to `easy-apache` and give execute permission for `setup.sh`  
```
cd easy-apache
sudo chmod +x setup.sh
```

#### Step 3
Running the script
```
Usage: easy-apache [options]
Options:
-f:   Full setup, default option if none is provided
-a:   Adding new site (includes apache install)
-s:   Install SSL certificate for sites available
-h:   Help (shows all commands)

Example
./easy-apache -f   #for full installation i.e Apache & SSL certificate
./easy-apache -as  #for installating Apache server & SSL certificate
./easy-apache -h   #for help
```


## Works on
- Ubuntu servers  
(will update more once I test)

Give it a ⭐ if it helped you xD
