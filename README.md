# Enable-a-local-user-in-Windows11-no-microsoft-account-

![Windows 11](https://img.shields.io/badge/Windows-11-0078D4?logo=windows&logoColor=white)
![Local account, no Microsoft account](https://img.shields.io/badge/Account-local%20%28no%20Microsoft%20account%29-6f42c1)
![During Windows setup](https://img.shields.io/badge/During-setup%20%28OOBE%29-5c2d91)
[![Last updated](https://img.shields.io/github/last-commit/ImmuneMoon/Enable-a-local-user-in-Windows11-no-microsoft-account-?label=updated)](https://github.com/ImmuneMoon/Enable-a-local-user-in-Windows11-no-microsoft-account-/commits/main)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)](LICENSE)

**📄 [Download the PDF](Enable-a-local-user-in-Windows11-no-microsoft-account.pdf)**

## A guide for creating a local account on Windows 11, instead of using a microsoft account.

> **This may not work on newer versions of Windows 11.** Microsoft says Home and Pro need internet and a Microsoft account during setup, and it has been closing workarounds like this one. As of October 2026, reports conflict on whether this command still works, and it can depend on your Windows version. If it doesn't work for you, try the **Remove requirement for an online Microsoft account** option in Rufus (see my [Windows install guide](https://github.com/ImmuneMoon/Windows-Install-Guide)), though that may still ask for internet. Otherwise, you'll need to finish setup with a Microsoft account.

> **Got an older Windows 11 ISO?** This command may still work on older versions, since the block first showed up in newer builds. You could install from the older ISO with the network unplugged, make your local account, then update. Local accounts normally stay in place through updates, but I haven't found testing that shows exactly which versions work, so treat this as something to try.
>
> * **Getting one is the hard part.** Microsoft's site and Rufus's download option only offer the newest version, so an ISO or USB drive you already made is your best bet. [UUP dump](https://uupdump.net/) can build an older one from Microsoft's update files. Don't download a ready-made ISO from a random site, since you can't tell what's been changed.
> * **Update right away.** Older versions may not get security fixes anymore. For example, Windows 11 24H2 Home and Pro have reached end of updates, so run Windows Update before you use the PC for anything else.

  Start your windows install with **>>NO NETWORK CONNECTION<<** (i.e. **unplug the machine's ethernet** or **don't allow a wifi connection in setup**).

Continue the install as usual, until you reach this prompt:

<img width="707" height="528" alt="image" src="https://github.com/user-attachments/assets/80ba4606-9c61-4ef0-a420-39b7a157f5ef" />

Once here, open **command prompt** by pressing **SHIFT+F10** together on your keyboard.

Once the command prompt window is open, it should look like this:

<img width="708" height="526" alt="image" src="https://github.com/user-attachments/assets/b8c092f4-e380-496f-9cc3-c21be6b4d479" />

Type into the command prompt window the following:

**start ms-cxh:localonly**

It should look like this:

<img width="707" height="522" alt="image" src="https://github.com/user-attachments/assets/d9b7185f-34eb-4832-bf41-3e029c41d01e" />

Hit **ENTER**

You should see a dialog to create a local profile like:

<img width="707" height="526" alt="image" src="https://github.com/user-attachments/assets/548d3bb3-a6ae-43e5-87f3-7db4161b7778" />

Set your user and password. Hit **ENTER** when finished and continue set up.

When at desktop, you can now **plug in your ethernet**, or **connect to a wifi network**.

### Congrats! You are now using a local user profile on Windows 11!!!

## ☕ Support the Project

If you find this guide helpful and want to support further development by Fulllion Creative Works, consider leaving a tip!

* [Donate via PayPal](https://www.paypal.com/donate/?hosted_button_id=LCDZX75HR4CLC)
* [Support on Ko-fi](https://ko-fi.com/fulllion)