# Nexon'd Trainer [BETA] -- A Universal MapleStory Trainer

Nexon'd Trainer is a generic MapleStory trainer framework that can be used with any region and any version of MapleStory. The way this works is unique to Nexon'd Trainer in that it retrieves supported scripts from a defined GitHub repository, such as the [GMS Script Bank](https://github.com/md35-gk/GMS-Script-Bank). Nexon'd Trainer is the descendant of [Simple Trainer](https://github.com/md35-gk/Simple-Trainer), both created by md35.

![Nexon'd Trainer Image](https://i.gyazo.com/71dd89a9a2c2fc2dda7598782fbe74d1.png)

## Getting Started

Nexon'd Trainer is a special type of trainer, which may cause confusion for users new to the MapleStory cheating scene. Usage of this trainer is NOT recommended for these users.

### Prerequisites

In order to use Nexon'd Trainer, you must satisfy the following requirements:

* A working NGS (Nexon Game Security) bypass, or equivalent. This usually comes in the form of a dinput8.dll file.
* A set of Cheat Engine scripts for use.
* A file archiver utility, such as [WinRAR](https://www.rarlab.com/download.htm), to un-zip a .ZIP file.
* Disabled anti-virus software during use of the trainer OR the ability to add a folder as an exception from detection in your anti-virus software. Here's a [Windows Defender example](https://support.microsoft.com/en-us/help/4028485/windows-10-add-an-exclusion-to-windows-defender-antivirus).
* Personal computer with the ability to run programs as an administrator (preferably on an Administrative user profile).

### Installing

Installation is simple, but new users to the MapleStory cheating scene may have more difficulty setting the trainer up. **Please read this section carefully.**

1. Download Nexon'd Trainer as a .ZIP file from the given download link in the official thread where you can find Nexon'd Trainer.
2. Un-zip and extract the contents anywhere on your PC using the password found in the same thread.

Next, you will want to configure the Load.ini file, which contains the list of all script names the trainer supports and loads in during the initialization process. Keep in mind the following:

- Do not change anything in the Load.ini file apart from adding or removing a '#' symbol where needed.
- Adding script names will not do anything unless the trainer has built-in support for it (which the default Load.ini that comes with the zip has).

3. Start up Nexon'd Trainer.exe with administrative rights. If this is not your first time using the trainer, skip to Step 4. Otherwise, you will be prompted for additional required set-up steps:

- Complete the Security Checkpoint, which deters fraudulent activities involving the trading, selling, or re-posting/distribution of the trainer.
  - **Note:** The domain name is something like "website.net". Do not include anything before, or after, the domain name, including the forward slashes.
- Read and agree to the Disclaimer and Terms of Use.
- Complete the Trainer Settings and GitHub Settings tabs.
  - You can refer to [this image](https://i.imgur.com/2fMO8UZ.png) for guidance.
  - If you are using your own GitHub repository, be sure to make necessary changes based on the image above.
  - Once completed, Save the trainer settings and restart the trainer.
  
4. If no prompts appear, you can click "Select Process" on the top right to select the MapleStory process you wish to attach to.
5. [For Official Servers Only] Once attached, enable MSCRC Bypass *unless* your NGS Bypass already bypasses the MSCRC.

## Updating Nexon'd Trainer

When Nexon'd Trainer has new versions released (signified by a Build version change), a prompt will appear on start-up that will allow you to be redirected to the download thread, or ignore the new update.

If you choose to download the newer version, keep in mind the following:
- Included with the .ZIP file comes with a "README - Updating to new version Instructions", which will tell you what has changed in this update.
- Most of the time, only the trainer executable was updated, and so only the existing trainer that you have needs to be replaced by the new one.
- If changes were made to other files, such as Load.ini, appropriate how-to-update instructions are given in that README file.

You will be prompted to re-Save the trainer settings to confirm that your settings were not altered in the update.

## Updating for Game Updates

When MapleStory is updated, it is important to update the scripts being used. Failure to do so will result in crashes or bans. To update scripts, go ahead and use any Memory Scanner software, like Cheat Engine, to scan for Array of Bytes (AoBs) indicated on the scripts. Update each script as needed (please Google if you need help), and appropriately adjust anything in the GitHub Settings tab of the trainer.

Keep in mind the following:
- The official Script Bank (the default), can only be updated by approved contributors. If you have already forked a copy of the repo to your account, you can submit a Pull Request as indicated in several README files in the Script Bank.
- Scripts can be updated and used locally as long as you have "Local" set in the trainer's Local Control section.

After scripts and Settings have been updated, you can restart the trainer to load them in!

## Support

You are free to leave questions and comments on the official trainer thread, or on our Discord (which can be found on the thread). **Keep in mind that trivial questions that can be answered by looking at this page or on the trainer thread *will be ignored*. Such questions on our Discord will lead to consequences.** We are not here to spoonfeed you, regardless of the fact that this tool is being provided to you free of charge.

## Plans for the Future

Nexon'd Trainer is an on-going project. Improvements will always be made to the base application. The following features are planned, but *may never be added*, depending on the direction the trainer goes.
- DLL Injection
- Multi-Hotkey System
- and more (give your suggestions on our Discord!)

## Contributing

While Nexon'd Trainer is a closed source, single person project, any help with providing or updating scripts for the [GMS Script Bank](https://github.com/md35-gk/GMS-Script-Bank) is highly appreciated. You will be credited in the trainer's About tab.

## Copyright

You have no permission from the creator(s) of Nexon'd Trainer to distribute, modify, or extract content from the software, as stated in the Terms of Use in the trainer. Permission for such activites will not be granted under any circumstance.

## Donate

Feel free to drop a donation of any amount to support continued development of this trainer. Leave a name in the message to be added to the Donators list in the trainer's About tab.

**[Click here to donate!](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=PVJ9Y5BE26ACQ&lc=US&item_name=Nexon%27d%20Trainer%20Donation&currency_code=USD&bn=PP-DonationsBF%3abtn_donate_SM%2egif%3aNonHosted)**
