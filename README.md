# How-to-do-Manual-Magento-Installation-
Magento installation process is similar to other popular site platforms. Magento is a complete solution for almost every e-commerce platform. There are two ways in which installation of Magento can be done. But Softaculous autoinstaller available in c-panel is the fastest and easiest one to use for Magento installation.  

These are the steps for manual installation of magento: 

1. First, we have to download the package of magento installation 

2. Secondly,  the Magento files should be uploaded to server 
 
3. Thirdly make a Mysql database which can later be used by Magento 
 
4. Fourthly, carefully carry out Magento installation process  

Step 1: The first thing to do in manual installation of magento is to download Magento installation package from official magento website.   

Step 2: Through the control panel, one must upload installation package on the hosting account. It can be done either using a file transfer protocol client or file manager. If magento installation is considered as primary for your domain then we can extract the content of the installation package in public-html folder. Otherwise you can extract the content to public-html/store/. Once the package is uploaded, you can extract it from control panel →file manager.    

Step 3: After creating MySQL database, assign user through the control panel and select MySQL databases. During the script installation one need to remember database details.  
 
Step 4: Go through the process of Magento installation.

After uploading and extracting the package, we will have a Mysql database. Here we need to navigate http://yoursite.com/store. Click on “I agree to the terms and conditions” and press continue button. Next we need to enter the details regarding database like name of the database, name of the user and password of the user.   Other options must be completed. “Skip Base URL validation before next step” this option must be checked on. 

After that you can click continue option for proceeding further. Here you should enter the personal information and the details regarding admin login which you want to use. Encryption key field can be left empty and the script and the script will generate one for you. Again click the continue button.   The` final step is to write your encryption key.  Magento Setup uses this encryption key to encrypt credit card details, passwords and other confidential information.     

After following all these steps, Magento installation will be successfully completed. One can either navigate to Frontend or Backend after the installation.
thankyou.
