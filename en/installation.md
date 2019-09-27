# Installation

  - [cPanel Control Panel](#cpanel)
  - [Other Control Panel and Non-control Panel](#othercpandnocp)

## Getting RVsitebuilder License

<a name="cpanel"></a>
### cPanel Control Panel

1. You can buy hosting service from our cPanel [hosting partners](https://rvsitebuilder.com/hosting-partner/) to get a control panel account with RVsitebuilder that's already installed.

2. Then you can access to RVsitebuilder immediately from [your cPanel control panel](https://user.rvsitebuilder.com/docs/7.2/en/create-new-website) and start your website!
 


<a name="othercpandnocp"></a>
### Other Control Panel Systems and Non-control panel

For other control panel systems or non-control panel domain name, you can simply follow these steps.
1. Get a control panel account or domain name on a server that already has RVsitebuilder license from your host provider or find one in our [hosting partners](https://rvsitebuilder.com/hosting-partner/) list.


2. Make your control panel account meet with the following requirements.
- Domain name must run on PHP7.1.3 or above. 
- php extension: 'mysqlnd','pdo','gd','curl','iconv','mbstring','zip','posix_getpwuid','json' 
- php ini config 'memory_limit' => 64M 
- Firewall on your server doesn't block the following domains.  
download.rvglobalsoft.com  
Files.mirror1.rvsitebuilder.com 



3. Install RVsitebuilder directly on your domain name.
- Download RVsitebuilder Setup wizard https://files.mirror1.rvsitebuilder.com/download/rvsitebuilderinstaller/setup to your local computer. 
- Unzip the setup file 
- Upload Folder rvsitebuilder to /public_html/ or /publc/ or /www/ 
- Call the setup.php script for your domain name on browser http://mydomainname.com/rvsitebuilder/setup.php 
- Follow the setup steps until finish. 
- Enter license at manage app.



4. Once the installation is completed.
RVsitebuilder CMS is ready to [create website](https://user.rvsitebuilder.com/docs/7.2/en/create-new-website) on your domain now!


