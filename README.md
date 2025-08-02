# Skyrim+ Installation Guide

This guide will help you install the modlist using [Wabbajack](https://www.wabbajack.org/).

---

## Introduction

Skyrim+ is a mod list for the Anniversary Edition of Skyrim that enhances the original feel while providing tons of bug and performance fixes, as well as light visual mods that enhance the characters and non-player characters (NPCs). It avoids conflicts and script-heavy mods as much as possible.

I've added many quest and new land mods, such as Wyrmstooth, Beyond Skyrim, and Faalskar.

New animations were added for first and third person, while keeping the vanilla combat untouched. The ice skating issues have been fixed.

Magic has been enhanced with new spells, and the vanilla spells have been rebalanced with mysticism magic to give the game a similar feel to previous entries in the series.

The emphasis is on your ability to play from beginning to end without worrying about bugs or crashes while experiencing as much content as possible.

You can check the full list [here](https://loadorderlibrary.com/lists/skyrim-5312054).

---

## Support & Community

- [Support me on Patreon](https://patreon.com/user?u=3502847&utm_medium=unknown&utm_source=join_link&utm_campaign=creatorshare_creator&utm_content=copyLink)
- [Join Discord](https://discord.gg/V3QyXVNUUv)
- [Support me on Ko-fi](https://ko-fi.com/K3K116XAYR)

---

## System Requirements

### Disclaimer

Owing to the need to clean master files and certain errors with Wabbajack, Skyrim+ only supports **English Steam** versions of Skyrim Anniversary Edition. **GOG and other Languages are not supported**. The version is 1.6.1170.

Only Windows 10 and 11 work with Wabbajack fully. LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK**. Your Windows version **must be 21H2 or newer** to run both Wabbajack and Skyrim+.

### Recommended System Requirements

Skyrim+ only modifies character textures and looks, along with Community shaders, Azurite weathers III, placed lights and window shadows. The remaining addons are SMIM and similar, SMP and fur shaders. The recommended specs below are based on using community shaders or not basically, so if it's not running smooth, you can safely disable it along with its addons.

#### Minimum for 1080p (Full HD Non-Ultrawide) Standard Profile

| Component | Requirement |
|-----------|-------------|
| CPU       | Intel Core i5-7400 / AMD Ryzen 3 1200 or better |
| RAM       | 16GB DDR4 RAM + 40GB Pagefile (If you have the space to spare, do it, for stability sake.) |
| Storage   | SATA SSD is preferred, for faster loading times |
| GPU       | NVIDIA GTX 1060 6GB / AMD Radeon RX 580 8GB or better |

#### Minimum for 1080p (Full HD Non-Ultrawide) Ultra Potato profile

| Component | Requirement |
|-----------|-------------|
| CPU       | Intel Core i5-4570 / AMD FX-8350 or better |
| RAM       | 8GB DDR4 RAM + 40GB Pagefile (If you have the space to spare, do it, for stability sake.) |
| Storage   | SATA SSD is preferred, for faster loading times |
| GPU       | NVIDIA GTX 970 4GB / AMD RX 570 4GB or better |

**Space Required:** 60GB Download Size ~120GB install Size ~180GB Total

> See how to setup a page file [here](https://www.tomshardware.com/news/how-to-manage-virtual-memory-pagefile-windows-10,36929.html)

---

## Installation

### Pre-Installation

Prior to installing Skyrim+, please complete the following steps:

1. Install [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe)
2. Install BOTH [.Net Runtime v6 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.36-windows-x64-installer) & [.Net Runtime v9 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.6-windows-x64-installer) then RESTART YOUR PC
3. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
4. Fully uninstall Skyrim by deleting the folder and the Skyrim Special Edition folder inside `\Documents\My Games`.
5. Fully disable OneDrive and any other programs which hook into user file areas.
6. Reinstall Skyrim into a location that is not Program Files. Somewhere like `C:\Games` is a good location. If you only have one drive, look into LostDragonist’s [SteamLibrary tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).
7. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
8. Launch the game to the main menu and allow it to download the paid addon files. **DO NOT VERIFY YOUR GAME FILES.** If you are having trouble with installing Creation Club content checkout the missing downloads section.
9. Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will** mess with the installation and, in the case of the latter, cause more problems than it solves.

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in Program Files, on your desktop, or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing Skyrim+

1. Download the latest Skyrim+ Wabbajack file from Nexusmods [**HERE**](https://www.nexusmods.com/skyrimspecialedition/mods/154341?tab=files)
2. Open Wabbajack and click on browse modlists.
3. Click on "Install from disk" button
4. Navigate to the folder where you downloaded the Skyrim+ Wabbajack file and select it.
5. Alternatively, you can download it from Wabbajack's GUI by ticking the "Non-featured"option and browsing for Skyrim+ or by using the search bar
6. Set the installation folder to be somewhere like `C:\SkyrimPlus`. **Do not install it to your desktop or downloads folder.**
7. The download location does not need to be on a SSD but it makes installing a bit faster.
8. Press the install button to begin.
9. If the installation is successful, you are ready to go. If the installation is unsuccessful, follow what is below.

#### Problems with installation

- **Could not download x:**
  - Big files can fail to download due to connection issues. You can either run Wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
  - **Make sure you have downloaded all the Paid AE update content!**
- **Wabbajack could not find my game folder:**
  - Either buy the game or go back to the [Pre-Installation](#pre-installation) step.
- **Antivirus reports a virus:**
  - You did not follow the steps in [Pre-Installation](#pre-installation). Go back and follow it.
  - Again, as listed in the previous steps: I recommend temporarily disabling Windows Defender during the download process if you get a false positive for DyndoLOD. DyndoLOD is safe, it is NOT a Trojan. Either that, or add an exception to the download path.
  - If you have followed it then you can fix this by [adding an exclusion for Mod Organizer in Windows Defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

---

## Missing Manual Downloads

Installing creation club content should be as simple as booting up Skyrim and letting it install your creation club content. But you may fall victim to Bethesda’s terrible system and be missing some content. Content needed to download this list as this list requires the **Anniversary Edition Creation Club content**.

### How to resolve

1. **Ensure you own the Anniversary Edition Upgrade DLC for Skyrim Special Edition.**  
   This is a necessary requirement for Skyrim+. You can confirm this by checking your Steam game properties and then the DLC tab.  
   > If your copy of Skyrim SE is shared from someone else’s Steam account via family sharing, you won’t be able to download the AE CC content.

2. **Make sure you’ve installed the Creation Club content.**  
   This requires booting up to the Skyrim main menu, at which point you should be prompted to download the content. If you do not get this option, or nothing happens when clicking it, you can trigger the download by doing the following:
   - Select Creations from the main menu.
   - Press for options.
   - Click “Download all owned Creation Club Creations”.
   > **Do not Alt-Tab or otherwise leave the game window while the download is ongoing.** Doing so is likely to cause the download to stop or skip files.

3. **Run Wabbajack once more, going through the same steps as on the initial install attempt.**  
   Before hitting run however, tick overwrite installation. This will identify the existing files you already downloaded and continue where you left off with the install.

### Troubleshooting

**I downloaded all of the content but it still says some files are missing.** There are two common causes for this.

- The first is that you may have the wrong version of some of the files. These can be seen in the Skyrim Data folder, where some of them have a capital letter instead of lowercase (for example: `ccbgssse037-Curios.esi` instead of `ccbgssse037-curios.esi`).  
  For this, go to your Skyrim Special Edition/Data folder, and delete all files that begin with `cc` (do not delete `skyrim.ccc`) and then boot the game again, you should be prompted with the option to download everything once more.

- **If you have tried everything suggested above and you are still missing some files**  
  You may just be a victim of Bethesda’s terrible system. You can try verifying the game files in Steam to reset the game and download all the content again from in-game.

- If nothing else works but you are able to get the missing manuals down to a small amount, you can use the UESP CK wiki to look up the corresponding creation for each missing manual:  
  [ck.uesp.net/wiki/Creation_Club_Content_by_Filename](https://ck.uesp.net/wiki/Creation_Club_Content_by_Filename)

---

## Stock Game & Root Builder

Skyrim+ utilizes a Wabbajack technology called Stock Game. What this essentially does is create a copy of your Skyrim installation within the installation location of the list. This enables greater compatibility with other mod-lists.

Skyrim+ also utilizes Root Builder alongside
