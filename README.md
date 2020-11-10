# QRL-Share

![release](https://img.shields.io/github/v/release/BiswasJishnu/QRL-Share?style=flat-square)
![License](https://img.shields.io/github/license/BiswasJishnu/QRL-Share?style=flat-square)
![Kjua version](https://img.shields.io/npm/v/kjua?label=kjua.js&style=flat-square)

>Firefox extension for quickly sharing web pages through qr codes.
![Project Banner](./Images/Repobanner.png)
![Screenshot](./Images/Screenshot.png)

<br>

## Privacy Policy

**Information Collection and Use**
> * This application does **not provide** an option for **account creation** therefore, **we don't have any access to your data**.
> * This application **does not collect** any usage or crash reporting data **without** your **consent**.
> * To **properly** run, this application needs **access your data for all websites**. This permission is **automatically granted** when you install the extension. Changing this will render the extension defunct.
> * We do not use any kind of cloud computing hence, all **processing** is done on **your device** and your **data is stored locally** on your device. We **cannot access** this.
> * We may **update** our **privacy-policy** time to time . We will make sure to **inform** you about any **changes** in our policy.

<br>

## Project Structure

* **Extension** - This is the **front-end** folder for the extension. It contains **extension.html** and  **extension.css** which are responsible of how the extension is displayed.
* **Icons** - This folder contains all the **icons** required by the extension to be displayed properly.
* **Libraries** - This folder contains all the **libraries** required by the back-end of the extension.
* **manifest.json** - This is the file that **brings together** the extension. It contains all the basic and mandatory **metadata** that is required to **build** the extension, e.g. - **permissions**, **scripts** required by the extension,**version**, etc . DO NOT tamper with this file.
* **QRL-Share.js** - **Back-end** of the extension. This file is responsible for the **functionality** of the extension. 

## Libraries Used
* [**Kjua.js**](https://larsjung.de/kjua/)
> * Kuja.js is a small java-script library which is used for dynamic generation of qr codes in modern browsers.

<br>

## Instructions for developers

###  Testing extension

Follow the steps to test the extension yourself.

1. Clone this repository into your local working directory.

``` html
git clone https://github.com/BiswasJishnu/QRL-Share.git

``` 
> * Note : **No need** to download any **additional packages** for testing this extension. This repository **already** contains all the **packages** required to run this extension.

2. Tweak the extension, modify it to your liking.

3. Run firefox and go to about:debugging.

4. Select This FireFox > Load Temporary Add-on > Select **QRL-Share.js** and the extension will just run fine.

5. If you come up with a really cool feature dont feel shy to add it to this repository.

6. Mozilla provides a really nice documentation on creating extensions for developers.
   I recommend that you check out the documentation [here](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions)
