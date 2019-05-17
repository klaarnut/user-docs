# Installation

## Getting RVsitebuilder License

You can buy hosting service from our [hosting partners](https://rvsitebuilder.com/hosting-partner/) to get a control panel account with RVsitebuilder is already installed in control panel.
 

## Server Requirement for non-control panel server

1. Domain name must run on PHP7.1.3 or above. 
1. php extension: 'mysqlnd','pdo','gd','curl','iconv','mbstring','fileinfo','exif','zip','posix_getpwuid','json' 
1. php ini config 'allow_url_fopen' = ON ,'memory_limit' => 64M 
1. Firewall on your server doesn't block the following domains.  
download.rvglobalsoft.com  
Files.mirror1.rvsitebuilder.com 

## Installation 

Please follow these steps: 

1. Download RVsitebuilder Setup wizard https://files.mirror1.rvsitebuilder.com/download/rvsitebuilderinstaller/setup to your local computer. 
1. Unzip the setup file 
1. Upload Folder rvsitebuilder to /public_html/ or /publc/ or /www/ 
1. Call the setup.php script for your domain name on browser http://mydomainname.com/rvsitebuilder/setup.php 
1. Follow the setup steps until finish. 
1. Enter license at manage app.

## .env configuration 

different between local and production 

- Local -  
- Production  

 
