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
