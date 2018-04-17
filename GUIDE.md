# Using GloBee for OpenCart
## Prerequisites
Last Cart Version Tested: 3.0.2.0

You must have a GloBee merchant account to use this library.  It's free to [sign-up for a GloBee merchant account](https://globee.com/register).
You can also test this plugin with a test GloBee merchant account. For more information about setting up a test GloBee merchant account & a testnet bitcoin wallet, please see https://globee.com/docs#testnet

## Getting Started
Go to the [latest release](github.com/GloBee-Official/opencart3-plugin/releases/latest) and download the file called `globee-opencart.ocmod.zip`

Note: if you're running an older version of OpenCart (e.g. v2.2), please select the plugin from https://github.com/GloBee-Official/opencart-plugin/releases


## Install
### Via Extension Installer
In your OpenCart store's administration section, go to Extensions > Extension Installer

Upload `globee-opencart.ocmod.zip`

OpenCart needs a working FTP server to install files. If the progress bar hangs half way, it probably means that your OpenCart FTP settings are incorrect. You can configure the FTP credentials of your server under System -> Settings -> FTP

After the installation indicates it's successful, you can continue with the setup.

## Setup
### Install the Payment Extension
Go to Extensions > Payments.
Find the GloBee payment extension and click the green install button. The page will refresh, you'll see a success message, and the install button will turn into a red uninstall button.
Click on the edit button.  You are now at the GloBee plugin's configuration screen.

### Connect to GloBee
For live transactions, just press the Connect to GloBee button.  For test transactions, press the drop down button attached to the Connect to GloBee button and select testnet.
You will be redirected to your GloBee merchant account and asked to approve a token which connects your store to GloBee's API.
After pressing Approve, please go back to the GloBee/OpenCart plugin configuration screen.

Configure the settings that work best for you.  Each setting has a tooltip that can help explain what it does.
Set the status setting to enabled and click save at the top right of the page.

You're done!
