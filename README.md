# Destination-Home-Online

Welcome to the official guide on how users can re-experience [PlayStation®Home](https://en.wikipedia.org/wiki/PlayStation_Home) online on the original PS3 &amp; [RPCS3](https://rpcs3.net/).

<p align="center">
<a href="https://discord.gg/QguSBT3"><img src="https://img.shields.io/badge/Discord-Destination%20Home-%235865F2"></a>
</p>

![NPIA00005_screenshot_2022_04_27_22_05_25](https://user-images.githubusercontent.com/67494727/165727137-22142bb8-ff30-473c-afde-3e71f6fbdf8e.png)

This is a work in progress/template for when we have our production servers online.

<h1 align="center">📖 Table of Contents 📖</h1>
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#disclaimers">Disclaimers</a> |	
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#important-terminologies">Important terminolgies!</a> |	
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#working-services--features">Working services & features</a> |
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#missing-servicesfunctions">Missing services/functions</a> |
<a href="https://github.com/NagatoDEV/PlayStation-Home-Master-Archive#general-information-about-this-archive">Prerequisites for PlayStation 3 users</a> |	
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#how-to-play-playstationhome-on-ps3">How to play PlayStation®Home on PS3</a> |
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#how-to-play-playstationhome-on-rpcs3">How to play PlayStation®Home on RPCS3</a> |
<a href="https://github.com/DestinationHome/Destination-Home-Online/edit/main/README.md#contact-me">Contact Me!</a> |
<a href="https://github.com/DestinationHome/Destination-Home-Online/edit/main/README.md#%EF%B8%8F-joincheck-out-our-social-platforms">Join/Check out our social platforms</a> |
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#legal-information">Legal Information</a>
</p>

# Goals:

- Create a write-up on how users can reinstall Home on OFW.
- Make a detailed write-up of FAQ/Disclaimers.
- Be sure to review any final package files & RPCS3 builds.
- Create a release page for our public client builds.

# Disclaimers:

Despite the lengthy development of the Destination Home project, there will unfortunately still be some missing services & functions at or after release. These missing features will be documented in this thread. However, as time progresses such services *may* come back to Home once the necessary backend implementations have been created for our production servers.

In regards to minigames, unfortunately for certain scenes, not all minigames will work as it requires some extra attention/time for the Destination Home team to get such services up and running in a stable environment. For our beta launch, I've created a straightforward [compatibility list](https://github.com/DestinationHome/Destination-Home-Online/blob/1073c10863923ae1218968f9e7c5903172e9c0ed/PlayStationHome_Minigame_Compatibility_List/PlayStationHome_Minigame_Compatibility_List_Beta.csv) that documents which minigames fully work or not in alphabetical order (A-Z).

# Important terminologies:

This section will give a general synopsis of some key terminologies that I think are important for users who might be new to the PS3 modding scene.

- CFW: **Custom Firmware** or *CFW* for short allows you to run unsigned code/homebrew on your PS3 system.
- HFW: **Hybrid Firmware** or *HFW* for short allows the end-user to run unsigned code/homebrew on your PS3 system. As a side note users will need to have HFW & HEN enabled in order to install PlayStation Home.
- HEN: HEN stands for Homebrew Enabler, which sounds exactly like its primary function. It allows users to run homebrew!
- OFW: In the context of PS3 **Official Firmware** or *OFW* for short can be detailed as the official OS/firmware that is distributed by a manufacturer in our case Sony. As of writing this guide `5/1/2022` version [4.88](https://www.playstation.com/en-us/support/hardware/ps3/system-software/) is the latest PlayStation®3 System Software Update.
- PKG files: The term *.PKG* or *Package files* can be used interchangeably. Package files contain critical game data that is installed onto a user's PS3 HDD. 

# Working services & features:

- Official Firmware support on the [latest](https://www.playstation.com/en-us/support/hardware/ps3/system-software/) PS3 firmware. `As of 2022/4/29, v4.88 is the latest firmware for PS3.`
- We are using the [1.86 version of PlayStation®Home](https://www.ign.com/articles/2014/03/11/playstation-home-getting-trophies-in-new-update) for our production client.
- Trophy support will be available on PS3. RPCS3 will use its equivalent service for handling trophies.
- Rewards. `This includes furniture, clothing, apartments, etc.`
- Cross-region support `Users can access all regional spaces despite the origin country connected to their PSN account. For instance, a player who is from Japan can access North American scenes and vice-versa.`
- Users who have PlayStation Plus on PSN will have access to additional font colors for their IDs in-game & have the ability to customize their avatar's hair in any color. For more information about this feature, feel free to view the video [here]().

# Missing services/functions:

- Clans/Clubs. 
- Commerce Points "Stores" for RPCS3.
- PlayStation®Network Matching2 Services will not be available for RPCS3.
- [PlayStation®Home Challenge System](https://blog.playstation.com/archive/2013/10/29/playstation-home-update-do-you-accept-the-challenge).

# Prerequisites for PlayStation 3 users:

1. Your PS3 device needs to be fully working for this process. Any model PS3 will work for this process including FAT/SLIMS/SUPERSLIMS. This includes any model PS3 from any region as well, meaning if you have a Japanese PS3 or a European model this process will work regardless. Note this is for users who are currently on stock OFW Official Firmware systems. If you are already on a device that has custom firmware such as REBUG or 0HEN/HFW you can disregard this prerequisite. Additionally, if you happen to have a debug unit PS3 such as a testkit, you can also skip this step.

⚠️ | Be sure to verify that your PS3 USB slots are functioning for this process. You can plug in a `FAT32 USB` stick to test if both USBs are working. If you see your PS3 USB stick under the video/music icon in XMB, that means the PlayStation 3 can read your external USB drive just fine.
:---: | :---

⚠️ | Your PS3 needs to have a working Blu-ray drive with a working Wi-Fi Bluetooth module. In simplistic terms, your device disc drive should work as well as be able to connect to a network Wi-Fi connection regardless if it's wireless or by an ethernet cable. ```NOTE: IF YOUR PS3 HAS A BROKEN BluRay Drive or your Wi-Fi/BT adapter is broken STOP RIGHT NOW. Currently, there is no noBD HFW/HEN firmware at the moment for systems that have those issues stated. If you try to install HFW over a console that has a broken Blu-ray drive or a Wi-Fi/BT adapter it is possible that your system will be semi-bricked and stuck into a boot loop.```
:---: | :---

2. You will need a USB stick that is formatted to `FAT32`.

# How to play PlayStation®Home on PS3:

Note that the following guide will **require** you to be on either **HEN/HFW (Hybrid Firmware)** or **Custom firmware** to install our custom PlayStation®Home package file for PS3. The Destination Home Team extremely recommends for users convert back to OFW *Official Firmware*. 

In addition to this, users who **already** have PlayStation Home on their device should highly consider donating their data to the team as you will still need to download our custom package. By donating your PlayStation®Home data we can implement original Home content back into our online services. For more information on how you can help out the Destination Home Project check out the official guide PlayStation®Home Cache Extraction Guide [here](https://nagato.gitbook.io/playstation-home-cache-extraction-guide1/table-of-contents/updating-your-ps3-to-hybrid-firmware).

⚠️ | Lastly, I also strongly suggest for users to watch my [official latest HEN how-to video guide](https://www.youtube.com/watch?v=oJWhmBwlCcQ) as it covers all of the necessary steps to convert your official firmware system to HFW/HEN. ![YouTube Thumbnails (8)](https://user-images.githubusercontent.com/67494727/166142560-e4efbe78-ae59-40f2-936a-6c7c145ea7a6.png)
:---: | :---

<h1 align="center">Without further ado, lets get back 🏠</h1>

1. Download the latest [PlayStation®Home 1.86 OFW patched PKG file]() and download it to any file directory on your computer.

2. Download and install
   If you don't know where to put psvimgtools and pkg2zip binaries, just put them in the `h-encore` folder.

3. Download the vulnerable DRM-free demo of [bitter smile](http://ares.dl.playstation.net/cdn/JP0741/PCSG90096_00/xGMrXOkORxWRyqzLMihZPqsXAbAXLzvAdJFqtPJLAZTgOcqJobxQAhLNbgiFydVlcmVOrpZKklOYxizQCRpiLfjeROuWivGXfwgkq.pkg) (yes, that's the user entry point).

4. Extract the demo using this command in terminal/cmd:
   ```
   pkg2zip -x PATH_OF_PKG
   ```

   This will output the files to `app/PCSG90096`.

5. Copy the contents of the output `app/PCSG90096` to the folder `h-encore/app/ux0_temp_game_PCSG90096_app_PCSG90096` (such that the files `eboot.bin` and `VITA_PATH.TXT` are within the same folder).

6. Copy the license file `app/PCSG90096/sce_sys/package/temp.bin` to the folder  
   `h-encore/license/ux0_temp_game_PCSG90096_license_app_PCSG90096` and rename the just pasted file `temp.bin` to ` 6488b73b912a753a492e2714e9b38bc7.rif`. Be careful with the file extension, it should not be `.rif.bin`. Again, this file should be in the same folder as `VITA_PATH.TXT`.

7. Start qcma and within the qcma settings set the option `Use this version for updates` to `FW 0.00 (Always up-to-date)` to spoof the System Software check.

8. Launch Content Manager on your PS Vita and connect it to your computer, where you then need to select `PC -> PS Vita System`, and after that you select `Applications`. If you see an error message about System Software, you should simply reboot your device to solve it (if this doesn't solve, then put your device into airplane mode and reboot). If this does still not work, then alternatively set DNS to `212.47.229.76` to block updates.
   This should create a folder at `PS Vita/APP/xxxxxxxxxxxxxxxx` on your computer (see qcma settings where this folder is), where the folder `xxxxxxxxxxxxxxxx` represents the AID (account ID that is 16 characters long) that you need to insert [here](http://cma.henkaku.xyz/). If the AID is valid, it will yield a key that you can now use to encrypt the demo.

9. Change directory to the `h-encore` folder in terminal/cmd and use the key to encrypt all folders using (make sure you don't confuse the key with the AID, the key is 64 characters long!):
   ```
   psvimg-create -n app -K YOUR_KEY app PCSG90096/app
   psvimg-create -n appmeta -K YOUR_KEY appmeta PCSG90096/appmeta
   psvimg-create -n license -K YOUR_KEY license PCSG90096/license
   psvimg-create -n savedata -K YOUR_KEY savedata PCSG90096/savedata
   ```

    The folder `h-encore/PCSG90096` should then contain `sce_sys` and all 4 folders from above, and within these folders you should find files called `X.psvimg` and `X.psvmd`, where `X` has the same name as the folder. Backup this folder, since if everything has been done correctly, you don't need to redo all the steps to install it onto another device with the same PSN account.

10. Copy the folder `h-encore/PCSG90096` to `PS Vita/APP/xxxxxxxxxxxxxxxx/PCSG90096` and then select `Refresh database` in qcma.

11. The *h-encore* bubble with a size of around `243 MB` should now appear in the Content Manager and that's what you finally need to transfer to your PS Vita. If the size does not match or you get the error `C2-12858-4`, then it's because you did not do it correctly! Please re-read the instructions more carefully then. If you get the error `You can only copy applications that your account is the owner of`, then it's because you have used an AID that is not of your account, go back to step 8.

12. Launch *h-encore* to exploit your device (if a message about trophies appears, simply click yes).
    The screen should first flash white, then purple, and finally open a menu called *h-encore bootstrap menu* where you can download [VitaShell](https://github.com/TheOfficialFloW/VitaShell) and install [HENkaku](https://github.com/henkaku).
    If it prompts the error `Cannot start this application. C0-11136-2`, then it's because you did not do step 6. correctly.

13. Enjoy. Note that you have to relaunch the exploit everytime you reboot or shutdown your device. Of course if you only put your device into standby mode, you don't need to relaunch.

# How to play PlayStation®Home on RPCS3

# Contact Me!
<img width="1000" alt="GitHubNagatoBanner" src="https://user-images.githubusercontent.com/67494727/140847055-8fe6ecb6-dca3-4ce9-b660-98068356aaed.png">

Have any questions about this release? Feel free to contact me at the following methods:

* My Twitter: [NagatoRevenge](https://twitter.com/NagatoRevenge)
* My Youtube Channel: [Nagato's Revenge](https://www.youtube.com/channel/UCXgz1g5ET8Un9gax-nGMjMw)

# ❤️ Join/Check out our social platforms:

[![name](https://discordapp.com/api/guilds/621722473695805450/widget.png?style=banner2&raw=true)](https://discord.gg/QguSBT3)

* [Destination Home Official Website](http://destinationho.me/)

* [Destination Home Preservation `Alternative Discord Link`](https://discord.gg/QguSBT3)

* [Destination Home Twitch Channel](https://www.twitch.tv/playstationhome/)

* [Destination Home Official YouTube Channel](https://www.youtube.com/channel/UCQhwhFevEgsRqMTHof7FwPQ)

* [Destination Home 1.86 Dev Offline Client Patches](https://github.com/NagatoDEV/Destination-Home-1.86-Offline-Client-Patches)

# Legal Information:

We are not affiliated with Sony Interactive Entertainment (SIE) or any other game developers licensed by SIE. This project is purely for preservation/educational purposes, and our team doesn't accept ANY forms of donations.

**All rights are reserved by Sony Interactive Entertainment Europe Limited, as well as the respective third-party companies responsible for implementing content into PlayStation®Home. Destination Home is working on PlayStation®Home as the adaptation of publicly leaked software, the usage of this software falling under abandonware due to the lack of copyright enforcement involving the tools. The online section of PlayStation®Home is protected by the laws implied by the Digital Millennium Copyright Act 17 U.S. Code § 1201 for the purpose of preservation, education, and public viewing as a museum effort. That the team's focus is to reproduce the functionality once accessible and hosted by Sony, PlayStation®Home. Tools that are provided to us will be to our best ability given the utmost protection unless stated otherwise by the provider. Our focus is the protection of Sony copyright and intellectual property while following the goal of reproduction of online functionality, and do not claim any of this as our own.**
