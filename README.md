# absy (a notificaion app for Salesforce developed by ABSYZ Inc.)



[Download Setup File](https://github.com/harshvasisthaa/absy_setup/raw/36e798a37f5a4d5fe3e7be57649b18e60a029de3/absy_setup.exe)


## Installation

> Copy the loaction shown in the installation screen, as we have to setup the enviroment variable.
![installation screen](https://github.com/harshvasisthaa/absy_setup/blob/main/docs/installation.png?raw=true)

> Search for "Your Account" in windows search and select "Edit enviroment variable for your account"
![search env](https://github.com/harshvasisthaa/absy_setup/blob/main/docs/enviroment.png?raw=true)

> Add path and save
![Add Path](https://github.com/harshvasisthaa/absy_setup/blob/main/docs/addPath.png?raw=true)

> Open CMD and run comman "absy help"
![absy help](https://github.com/harshvasisthaa/absy_setup/blob/main/docs/absyHelp.png?raw=true)


## Authentication

> To authenticate with production org
```sh
absy -a alias
```

> To authenticate with sandbox org
```sh
absy -a alias -s
```

> To authenticate with custom URL org
```sh
absy -a alias -c https://yourdomain.salesforce.com
```

## Salesforce Installation

> Install below managed package in the Salesforce ORG.

For Production ORG
[https://login.salesforce.com/packaging/installPackage.apexp?p0=04t5g000000Imfb](https://login.salesforce.com/packaging/installPackage.apexp?p0=04t5g000000Imfb)

For Sandbox ORG
[https://test.salesforce.com/packaging/installPackage.apexp?p0=04t5g000000Imfb](https://login.salesforce.com/packaging/installPackage.apexp?p0=04t5g000000Imfb)

## Enable Subscription

> After the authentication, you can subscribe to notificaion using below command, on successful subscription windows will show the notificiaon.
```sh
absy subscribe
```
![absy subscribe](https://github.com/harshvasisthaa/absy_setup/blob/main/docs/subscribe.png?raw=true)


## Send notificaion from Salesforce to Desktop

> Go to app launcher and search for "Desktop Push Notification" tab (managed package).
> Enter title, content, and target id (only accepts record id, else throw error) and click on "notify ABSY"
![absy subscribe](https://github.com/harshvasisthaa/absy_setup/blob/main/docs/sfpublish.png?raw=true)

> You should receive a windows notificaion someting like below:
![app notificaion](https://github.com/harshvasisthaa/absy_setup/blob/main/docs/appNotification.png?raw=true)
