# Australia Post Shipping Plugin

This plugin integrates J2Store with Australia Post Shipping rate API.

### Requirements
* **PHP 5.2 or higher**
* **Joomla 2.5 or above**
* **J2Store 2.7.3 or above**

### Installation
You can install this shipping plugin, using joomla installer.

1. In the J2Store admin, go to **Extensions -> Extension Manager**
2. Click on the *Browse* button and select **Australia Post Shipping** (type=j2store) and click on *Upload & Install*
3. Enable the plugin
4. Configure the shipping plugin by entering the plugin parameters

The installation procedure is illustrated in the image below:
![](aus-ship-plg-install.png)
![](aus-ship-doc-1.png)
![](aus-post-ship-method-list.png)
![](aus-ship-set-param)


### Parameters

##### Shipping Type
For this option, select **Domestic Shipping Service** or **International Shipping Service**

##### API Key
This is your Australia post API key. It will be given to you once you create an Australia Post account.

##### Show Delivery Time
If you want to show the Date/Time of delivery in checkout page, you can set this option to **Yes**

##### Tax Profile
If the shipping cost is also taxable, you can select a tax profile here.

##### Geozone
If you have limitations in applying this shipping method, you can select the areas that are eligible, by selecting the corresponding geozone here. 

##### Debug
If you enable this option, a log file will be maintained for error debugging. This debug file will be stored in cache folder. 

##### Handling Cost
If a handling cost is applicable for the shipping, you can enter the cost directly in this field. 

### Support
If you still have questions, you can reach us in **support@j2store.org**

Thankyou for using our extension.
