# Destination-Home-Online

Welcome to the official guide on how users can re-experience [PlayStation®Home](https://en.wikipedia.org/wiki/PlayStation_Home) online on the original PS3 &amp; [RPCS3](https://rpcs3.net/).

<h1 align="center">🌐 Destination Home Public DNS Setting: </h1>

<p align="center">
<a href="https://discord.gg/QguSBT3"><img src="https://img.shields.io/badge/Discord-Destination%20Home-%235865F2"></a>
</p>

![NPIA00005_screenshot_2022_04_27_22_05_25](https://user-images.githubusercontent.com/67494727/165727137-22142bb8-ff30-473c-afde-3e71f6fbdf8e.png)

<h1 align="center">📖 Table of Contents 📖</h1>
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#disclaimers">Disclaimers</a> |	
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#important-terminologies">Important terminologies!</a> |	
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#working-services--features">Working services & features</a> |
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#missing-servicesfunctions">Missing services/functions</a> |
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#%EF%B8%8F-playstationhome-minigame-compatibility-list">PlayStation®Home Minigame Compatibility List</a> |
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#prerequisites-for-playstation-3-users">Prerequisites for PlayStation 3 users</a> |	
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#how-to-play-playstationhome-on-ps3">How to play PlayStation®Home on PS3</a> |
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#how-to-play-playstationhome-on-rpcs3">How to play PlayStation®Home on RPCS3</a> |
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#contact-me">Contact Me!</a> |
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#%EF%B8%8F-joincheck-out-our-social-platforms">Join/Check out our social platforms</a> |
<a href="https://github.com/DestinationHome/Destination-Home-Online/blob/main/README.md#legal-information">Legal Information</a>
</p>

# Goals:

- Create a write-up on how users can reinstall Home on OFW.
- Make a detailed write-up of FAQ/Disclaimers.
- Be sure to review any final package files & RPCS3 builds.
- Create a release page for our public client builds.

# Disclaimers:

Despite the lengthy development of the Destination Home project, there will unfortunately still be some missing services & functions at or after release. These missing features will be documented in this thread. However, as time progresses such services *may* come back to Home once the necessary backend implementations have been created for our production servers.

# Important terminologies:

This section will give a general synopsis of some key terminologies that I think are important for users who might be new to the PS3 modding scene.

- CFW: **Custom Firmware** or *CFW* for short allows you to run unsigned code/homebrew on your PS3 system.
- HFW: **Hybrid Firmware** or *HFW* for short allows the end-user to run unsigned code/homebrew on your PS3 system. As a side note users will need to have HFW & HEN enabled in order to install PlayStation Home.
- HEN: HEN stands for Homebrew Enabler, which sounds exactly like its primary function. It allows users to run homebrew!
- OFW: In the context of PS3 **Official Firmware** or *OFW* for short can be detailed as the official OS/firmware that is distributed by a manufacturer in our case Sony. As of writing this guide, `5/1/2022` version [4.88](https://www.playstation.com/en-us/support/hardware/ps3/system-software/) is the latest PlayStation®3 System Software Update.
- PKG files: The term *.PKG* or *Package files* can be used interchangeably. Package files contain critical game data that is installed onto a user's PS3 HDD. 
- Rufus: **Rufus** is a utility that helps format and create bootable USB flash drives, such as USB keys/pen drives, memory sticks, etc.

# Working services & features:

- Official Firmware support on the [latest](https://www.playstation.com/en-us/support/hardware/ps3/system-software/) PS3 firmware. `As of 2022/4/29, v4.88 is the latest firmware for PS3.`
- We are using the [1.86 version of PlayStation®Home](https://www.ign.com/articles/2014/03/11/playstation-home-getting-trophies-in-new-update) for our production client.
- Trophy support will be available on PS3. RPCS3 will use its equivalent service for handling trophies.
- Rewards. `This includes furniture, clothing, apartments, etc.`
- Cross-region support `Users can access all regional spaces despite the origin country connected to their PSN account. For instance, a player who is from Japan can access North American scenes and vice-versa.`
- Users who have PlayStation®Plus on PSN will have access to additional font colors for their IDs in-game & have the ability to customize their avatar's hair in any color. For more information about this feature, feel free to view the video down below.

https://user-images.githubusercontent.com/67494727/166172201-69fa3657-f91f-4108-bfd2-a163809472bf.mp4

# Missing services/functions:

- Clans/Clubs. 
- Commerce Points "Stores" for RPCS3.
- [Inspect Feature for Avatars](https://blog.playstation.com/2013/09/18/new-to-playstation-home-inspect-items/).
- Teleporter System for core scenes e.g., _The Hub, First Floor Mall, Pier Park.
- PlayStation™Network Matching2 Services will not be available for RPCS3.
- [PlayStation®Home Challenge System](https://blog.playstation.com/archive/2013/10/29/playstation-home-update-do-you-accept-the-challenge).

# 🕹️ PlayStation®Home Minigame Compatibility List:

![NPIA00005_screenshot_2022_04_30_16_22_56](https://user-images.githubusercontent.com/67494727/166170289-8182e235-31be-4794-9fbb-303e93b5e579.png)

In regards to minigames, unfortunately for certain scenes, not all minigames will work as it requires some extra attention/time for the Destination Home team to get such services up and running in a stable environment. For our beta launch, I've created a straightforward [compatibility list](https://github.com/DestinationHome/Destination-Home-Online/blob/main/PlayStationHome_Minigame_Compatibility_List/PlayStationHome_Minigame_Compatibility_List_Beta.csv) that documents which minigames fully work or not in alphabetical order (A-Z).

# 🕷️Notice critical bugs in PlayStation&Home? Here is how you can report them to the Destination Home Team!

- As all with any major software project, even the best applications are known to have bugs, and PlayStation Home online is no exception. With that being said the Destination Home give serious consideration when it comes to stablility for our community. If you see any **critical bugs** please create a ticket/issue [here](https://github.com/DestinationHome/Destination-Home-Online/issues) on the official Destination Home Online repo. In order to fix bugs fast, we ask for users to provide as much documentation as possible. For instance:

- What client are your using (RPCS3/PS3)?
- Where did this bug occur? List the scene name.
- Provide pictures/videos of the error occurring.

# Prerequisites for PlayStation 3 users:

**1.** Your PS3 device needs to be fully working for this process. Any model PS3 will work for this process including FAT/SLIMS/SUPERSLIMS. This includes any model PS3 from any region as well, meaning if you have a Japanese PS3 or a European model this process will work regardless. Note this is for users who are currently on stock OFW Official Firmware systems. If you are already on a device that has custom firmware such as REBUG or 0HEN/HFW you can disregard this prerequisite. Additionally, if you happen to have a debug unit PS3 such as a testkit, you can also skip this step.

⚠️ | Be sure to verify that your PS3 USB slots are functioning for this process. You can plug in a `FAT32 USB` stick to test if both USBs are working. If you see your PS3 USB stick under the video/music icon in XMB, that means the PlayStation 3 can read your external USB drive just fine.
:---: | :---

⚠️ | Your PS3 needs to have a working Blu-ray drive with a working Wi-Fi Bluetooth module. In simplistic terms, your device disc drive should work as well as be able to connect to a network Wi-Fi connection regardless if it's wireless or by an ethernet cable. ```NOTE: IF YOUR PS3 HAS A BROKEN BluRay Drive or your Wi-Fi/BT adapter is broken STOP RIGHT NOW. Currently, there is no noBD HFW/HEN firmware at the moment for systems that have those issues stated. If you try to install HFW over a console that has a broken Blu-ray drive or a Wi-Fi/BT adapter it is possible that your system will be semi-bricked and stuck into a boot loop.```
:---: | :---

**2.** You will need a USB Flash Drive that is formatted to `FAT32`.

# How to play PlayStation®Home on PS3:

Note that the following guide will **require** you to be on either **HEN/HFW (Hybrid Firmware)** or **Custom firmware** to install our custom PlayStation®Home package file for PS3. The Destination Home Team extremely recommends for users convert back to OFW *Official Firmware*. 

In addition to this, users who **already** have PlayStation Home on their device should highly consider donating their data to the team as you will still need to download our custom package. By donating your PlayStation®Home data we can implement original Home content back into our online services. For more information on how you can help out the Destination Home Project check out the official guide PlayStation®Home Cache Extraction Guide [here](https://nagato.gitbook.io/playstation-home-cache-extraction-guide1/table-of-contents/updating-your-ps3-to-hybrid-firmware).

⚠️ | Lastly, I also strongly suggest for users to watch my [official latest HEN how-to video guide](https://www.youtube.com/watch?v=oJWhmBwlCcQ) as it covers all of the necessary steps to convert your official firmware system to HFW/HEN. ![YouTube Thumbnails (8)](https://user-images.githubusercontent.com/67494727/166142560-e4efbe78-ae59-40f2-936a-6c7c145ea7a6.png)
:---: | :---

<h1 align="center">Without further ado, let's get back 🏠</h1>

**1.** Download the latest [PlayStation®Home 1.86 OFW patched PKG file]() and download it to any file directory on your computer.

**2.** Download and install the [latest version of Hybrid Firmware](https://github.com/DestinationHome/Destination-Home-Online/releases/download/test/PS3UPDAT.PUP) "HFW" which is 4.88 `As of 5/1/2022`.

  ```
   MD5 Hash for 4.88 HFW: 23F60BAF3C3D38BC77AA452E770D1248
   ```

⚠️ | IMPORTANT INFORMATION: PLEASE CHECK YOUR MD5 Hash before updating your console to avoid any bricks. By checking your MD5 hash, you can verify that you're downloading the correct update and your firmware is not corrupt. You can use the [OnlineMD5](http://onlinemd5.com/) hash checker for this process. Please refer back to the [latest HEN tutorial](https://youtu.be/oJWhmBwlCcQ) if you need a reminder on how to check your MD5 hash.
:---: | :---
 
**3.** The third step is to format your USB to `FAT32` with either Windows File Explorer or [Rufus](https://rufus.ie/en/). If your USB is already on `FAT32` you can skip this step. You can use this video [here](https://www.youtube.com/watch?v=Wg1aVe-PxT0), if you need a visual representation of how to correctly format your USB to FAT32 or you can use my [HEN tutorial](https://youtu.be/oJWhmBwlCcQ).

**4.** The fourth step is to drag the PlayStation®Home 1.86 OFW patched PKG file to the `root` of your USB device.

**5.** Now that we are on file system `FAT32`, you will want to rename the HFW firmware to `PS3UPDAT.PUP`

ℹ️ | Make sure that the filename is in all capital letters: `PS3UPDAT.PUP`
:---: | :---

ℹ️ | As well before installing the firmware on your PS3 please verify the MD5 hash via with [OnlineMD5](http://onlinemd5.com/) hash. This is the MD5 Hash: `23F60BAF3C3D38BC77AA452E770D1248`
:---: | :---

⚠️ | NOT VERIFYING YOUR MD5 HASH CAN RESULT IN A BRICKED CONSOLE. 
:---: | :---

**6.** Step 6 deals with **Updating our console**. Now that your USB is now formatted to `FAT32` and has the update file you can now plug your USB into the rightmost USB port on your PS3 (The USB port that is nearest to your BluRay drive).

ℹ️ | Make sure as well to disable your Wi-Fi connection and take any disc that might be in your PS3 BluRay drive. This ensures that you’re not downloading the latest live firmware from Sony's Servers for the PS3.
:---: | :---

ℹ️ | Now go into System Settings and Update via Storage Media. If you have done everything correctly, you should see the following screen:![121427753-14917180-c943-11eb-9bae-1c2ba0e28576](https://user-images.githubusercontent.com/67494727/166143719-f3f0757c-21b8-4eeb-93d2-abe5352ac218.png)
:---: | :---

ℹ️ | If you see this screen just click OK and proceed with the on-screen instructions. Once your PS3 has successfully updated we can start on the next segment of this process which is activating **HEN Enabler**.
:---: | :---

<h2 align="center">⚙️ Activating HEN Enabler</h2>

<h4 align="center">Now that you have successfully installed HFW 4.88 onto your device. Now we need to install HEN.</h4>

ℹ️ | Installing HEN can take a while to install. The PS3 has to successfully receive a custom payload that will allow your PS3 to be hacked. This process can take multiple tries before HEN is initialized on your device. As well this process may require you to reset your PS3 MULTIPLE TIMES.
:---: | :---

**7.** First we need to configure our **Network Settings** in the PS3 **Internet Browser**. Under the `Network` column in *XMB*, please enter into the `Internet Browser` application. Once you're in the Internet Browser we're going to delete some files within the browser. Click `Triangle` on your PS3 controller which will display a side menu as showcased here:

![118722428-24ada980-b7fa-11eb-9a0a-ded123132166](https://user-images.githubusercontent.com/67494727/166163715-96343599-5919-4439-a8d0-ee5537a3b94e.png)

**8.** Assuming that the side menu is still activated on your PS3, go to the Tools tab. From the Tools tab we need to **disable/clear** the following features:

- `Confirm Browser Close` turn this setting `Off`
- `Home Page` make sure to set this setting as `Blank Page`
- Make sure to `Delete Cookies` and click `Yes` to confirm this setting.
- Make sure to `Delete Search History` and click `Yes`to confirm this setting.
- Make sure to `Delete Cache` and click `Yes` to confirm this setting.
- Make sure to `Delete Authentication Information` to confirm this setting.

**9.** Once all of the following settings have been initialized. Within the `Internet Browser` you want to go to [ps3xploit.com](http://ps3xploit.com/).

![118725001-58d69980-b7fd-11eb-9134-4bef78ea0d68](https://user-images.githubusercontent.com/67494727/166163886-85866265-49d2-487b-9d19-0e7ea2350891.png)

Now that you are on `ps3exploit.com` you want to hover over the `PS3HEN` tab. Within the PS3HEN tab, you want to select the `HEN Installer/Enabler` option. Once you have launched that option you should be redirected to the `PS3 HEN Installer page` which will download a file called `PS3HEN.p3t`

![118724992-570cd600-b7fd-11eb-8e7b-c7ea8aa3bc0a](https://user-images.githubusercontent.com/67494727/166164194-c512cd37-1ede-473d-bf80-1a57684327e3.png)

**10.** Once the `PS3HEN.p3t` file has been downloaded, within the `PS3 HEN Installer page` select the option that states `Initialize HEN installer` once the process has initialized you should see a green message stating that the HEN installer initialized successfully.

![STEP 5](https://user-images.githubusercontent.com/67494727/166164222-60302eac-0e88-4784-b768-28a7a6739142.png)

**11.** The next option that you want to select within the `PS3 HEN Installer page` is `Install HEN` only if you got the `HEN installer initialized successfully message`. Once HEN has been activated you should get an image that states `Welcome to HEN 3.03`.

![118724992-570cd600-b7fd-11eb-8e7b-c7ea8aa3bc0a](https://user-images.githubusercontent.com/67494727/166164317-e4899e47-05ba-43d9-8cdc-0b264b4cd4ec.png)

**12.** Once you see the `Welcome to HEN 3.03 message` you can exit out of the `Internet Browser`. Once you have exited the browser, you should see a package `.pkg file` being downloaded to your PS3. The file is 11MB and is called `Latest_HEN_Installer_signed.pkg` Let this package file be fully installed before restarting your PS3.

![Latest HEN installer signed pkg](https://user-images.githubusercontent.com/67494727/166173568-5a64d822-d1e0-4a6c-95fd-1d893f5e6095.png)

**13.** Once you start back up your PS3 head over to the `Game` column you should see 2 new options on your XMB which is `★ Enable HEN` & `★ Package Manager`. If you have these 2 new options that means HEN has been successfully installed.

![enable hennnnnnnnnnnnnnnnnn](https://user-images.githubusercontent.com/67494727/166165237-d04cc33e-ff4a-4ecc-a39e-8fb3343a860c.png)

**14.** Now that you have successfully installed HFW/HEN onto your device and you’ve just restarted your console, please connect your USB drive to the `right-most` USB slot (the one that is closest to your USB drive). Considering that you already have the PlayStation®Home 1.86 OFW patched PKG file on the `root` of your USB, please go to the `★ Enable HEN` option to launch the payload to allow you to run Homebrew. Once you get the HEN notification enabled you can now exit the browser.

⚠️ | Once again be sure that you are not connected to PlayStation®Network while utilizing any sort of Homebrew or you are at risk of getting your console banned.
:---: | :---

- Once you `★ Enable HEN` you should see `★ Package Manager` click `X` to open up Package Manager and go to the 2nd option that states `Install Package Files` you should see the PlayStation®Home 1.86 OFW patched PKG file. To install the PKG just hit `X` to install the package, once you installed the package you should see PlayStation®Home under the PlayStation™Network icon. 


<h2 align="center">🧰 Switching to our Public DNS Settings</h2>

**15.** On your PS3 XMB under the `Settings` column navigate to the `Network Settings` option.

![UEEEEE](https://user-images.githubusercontent.com/67494727/166166992-bd0d24ec-4b54-429a-a0d9-ff8f5d4253ea.png)

**16.** Scroll down to the third option `Internet Connection Settings` to modify your original network configuration.

![Screenshot Network 3](https://user-images.githubusercontent.com/67494727/166166887-cb9d6124-159e-4e57-9363-d956d8984c71.png)

**17.** As for the next step you need to choose `Custom`, as the `Easy` option will not allow you to change your DNS to be a custom value. 

![Screenshot_11](https://user-images.githubusercontent.com/67494727/166166919-e52e22f1-eda7-4455-88a1-27dc4f805e13.png)

**18** Once you have connected to your `WLAN Settings` for your Home network, and you see the `IP Address Setting` pane, please select `Automatic`

**19.** When you are on the `DHCP Host Name setting` select the option `Do Not Set`.

**20.** In the `DNS Setting` window, select the `Manual` option.

![dns settings ps3](https://user-images.githubusercontent.com/67494727/166167771-d0a2ccc2-09f9-4c20-b206-f9d4ee78e3b3.png)

**21.** This step is `vital` for you to access our Home servers, you will need to enter the following information in the DNS options

- **Primary DNS:**
- **Secondary DNS:** 8.8.8.8

**22.** On the `MTU Setting` window, select the `Automatic` option.

![automatic MTU](https://user-images.githubusercontent.com/67494727/166167750-f5d05957-dadf-4f88-b3d5-d512d6e66a07.png)

**23.** On the `Do Not Use` window, select the `Do Not Use` option.

![DO NOT USE](https://user-images.githubusercontent.com/67494727/166167740-75afc960-dbbd-4f29-b2fe-6f2ec64497d5.png)

**24.** On the `UPnP` window, select the `Enable` option.

![UPNP](https://user-images.githubusercontent.com/67494727/166167728-b71861d0-a80d-4bf1-80f0-37dcb4c859a0.png)

**25.** Lastly, confirm your networking settings & then sign back into PlayStation™Network. Once you are on PlayStation™Network, you should be able to finally replay PlayStation®Home on PS3!

![confirm your settingssssss](https://user-images.githubusercontent.com/67494727/166167725-71c487d2-bfd5-43fc-b0f2-1dad317e46a2.png)

<h2 align="center">🔄 Reverting back to Official Firmware</h2>

**26.** As stated before Official Firmware is the safest way to play PlayStation®Home as running any kind of *Custom firmware* you are at risk to get banned on PlayStation™Network. The Destination Home is not responsible for any accounts that may get banned for you using your account on custom firmware, as we have made it clear on the best option for our community to play Home. To revert back to OFW simply, just [download](https://www.playstation.com/en-us/support/hardware/ps3/system-software/) the latest PS3 System Software version and place the PS3UPDAT.PUP file, in the following directory: 

```
PS3/UPDATE/PS3UPDAT.PUP
```

Then go to `System Update` > `Update via Storage Media`. Next, follow the on-screen prompt to complete the update. Once your system has successfully updated, you will still be able to PlayStation®Home normal.

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
