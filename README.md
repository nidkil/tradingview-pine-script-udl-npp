# Tradingview Pine Script for Notepad++
I have been working on Tradingview Pine Scripts (TPS) and it was irritating me that when the scripts get lager and more complex they are hard to read. So I decided to create syntax highlighting for TPS using Notepad++ (NPP). NPP is the go to editor for Windows. It provides an easy mechanism for adding custom syntax highlighting for languages using its User Defined Language (UDL) functionality.

This repository contains the User Defined Language (UDL) file for syntax highlighting Tradingview Pine Scripts (TPS) files in Notepad++ (NPP).

![Notepad++ with Tradingview Pine Script file with syntax highlighting](https://github.com/nidkil/tradingview-pine-script-udl-npp/images/NPP_Tradingview_Pine_Script_Syntax_Highlighting.png "Notepad++ with Tradingview Pine Script file with syntax highlighting")

## Features
This syntax highlighting for TPS has the following features.
* It incorporates many keywords from the official documentation.
* Keywords are broken into distinct groups that can be styled individually.
* It requires Notepad++ 6.2 or greater (supporting UDL 2.0)

## Install
Installation is easy and straight forward.

![Installing Tradingview Pine Script UDL file in Notepad++](https://github.com/nidkil/tradingview-pine-script-udl-npp/images/NPP_Language_Menu.png "Installing Tradingview Pine Script UDL file in Notepad++")

* Download the tradingview-pine-script-udl-npp.xml file
* Open Notepad++
* Navigate to Language -> Define your language...
* In the dialog that opens Select Import... 
* Select the tradingview-pine-script-udl-npp.xml file you downloaded
* Click Open
* Restart Notepad++ and the Language menu will show the newly added language option at the bottom

## Usage
Using the syntax highlighting for TPS is automatic if the TPS files have the right file extension, otherwise you need to set it manually.
* Open a Tradingview Pine Script (TPS) file 
* If the file has the extension .pine Notepad++ will automatically apply the syntax highlighting from the TPS UDL file
* If it does not have the extension .pine you need to help Notepad++ by manually selecting the TPS UDL from the bottom of the Language menu called Tradingview Pine Script

![Manually selecting Tradingview Pine Script syntax highlighting](https://github.com/nidkil/tradingview-pine-script-udl-npp/images/NPP_TPS_Menu_Option.png "Manually selecting Tradingview Pine Script syntax highlighting")

## Customize the syntax highlighting
The styling can be modified to your own preferences by setting the individual styling groups.

![Customizing the Tradingview Pine Script syntax highlighting](https://github.com/nidkil/tradingview-pine-script-udl-npp/images/NPP_UDL_Dialog.png "Customizing the Tradingview Pine Script syntax highlighting")

* Go to Language -> Define your language... 
* At the top of the dialog that opens select select Tradingview Pine Script from the User language drop down list

In this dialog you can also add missing keywords.

## Contributing
I would appreciate it if you can provide me with feedback of any changes you make.