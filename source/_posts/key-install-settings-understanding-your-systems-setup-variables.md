---
title: "Key Install Settings: Understanding Your System's Setup Variables"
date: 2024-10-06T01:37:49.148Z
updated: 2024-10-10T16:29:06.717Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: "This Article Describes Key Install Settings: Understanding Your System's Setup Variables"
thumbnail: https://thmb.techidaily.com/c169b3dacf2f59341958f21d25bf2991aa2ae1cdaf45a12a73275ef22646d781.jpg
---

## Key Install Settings: Understanding Your System's Setup Variables

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Install Parameters](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Execution Level Settings Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Organization](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Builds](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Analytics](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [SCCM](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [ActiveSync](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
         * [User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
         * [System Changes](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Server](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Custom Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patch Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Merge Module Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Updates Configuration Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Store App Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Modification Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Optional Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Mobile CAB Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio Extension Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Software Installer Wizards - Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Alternative to AdminStudio/Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Replace Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Migrating from Visual Studio Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Keyboard Shortcuts](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Shell Integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer PowerShell Automation Interfaces](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)
* [Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Samples](https://tools.techidaily.com/advancedinstaller/products/)
* [How-tos](https://tools.techidaily.com/advancedinstaller/products/)
* [FAQs](https://tools.techidaily.com/advancedinstaller/products/)
* [Windows Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Deployment Technologies](https://tools.techidaily.com/advancedinstaller/products/)
* [IT Pro](https://tools.techidaily.com/advancedinstaller/products/)
* [MSIX](https://tools.techidaily.com/advancedinstaller/products/)
* [Video Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Advanced Installer Blog](https://tools.techidaily.com/advancedinstaller/products/)
* [Table of Contents](https://tools.techidaily.com/advancedinstaller/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Install Parameters

Windows Installer properties are used during the installation process.

![Install parameters](https://cdn.advancedinstaller.com/img/ui/install-parameters.png "Install parameters")  

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg) You can use the drop-down list in the toolbar to select the current build. Also, all the changes made in this view apply only to the current build. 

## Installation Folders

* **Application Folder** \- in this field, you can specify the default location for the Application Folder (APPDIR). This path is stored in the **APPDIR** property, and it is applicable only to those files and folders which are located under the "Application Folder" directory in the [Files and Folders Page - Installer Project](https://tools.techidaily.com/advancedinstaller/products/). During the installation, the user can modify this path by either using the \[Browse \] button in the "FolderDlg" (Select Installation Folder) dialog or by manually editing the Path Edit control on the same dialog. The default value of this field points to a sub-folder of the [ProgramFilesFolder](https://learn.microsoft.com/en-us/windows/win32/msi/programfilesfolder) for the per--machine installs.
* **Application Shortcut Folder** \- in this field, you can specify the default location for the Application Shortcut Folder (SHORTCUTDIR). This path is stored in the**SHORTCUTDIR** property, and it is applicable only to those files and folders which are located under the "Application Shortcut Folder" directory in the "Files and Folders" page. The default value of this field points to a sub-folder of the [ProgramMenuFolder](https://learn.microsoft.com/en-us/windows/win32/msi/programmenufolder).

These values are directly editable, with a suggested set of defaults available in the drop-down lists. Click the \[Edit... \] button to change them through the [Edit Formatted Type Dialog](https://tools.techidaily.com/advancedinstaller/products/).

## Installation Options

### Package Type

 Select between 32-bit, Arm64, 64-bit for Intel 64 Itanium processors, 64-bit for AMD64 or EM64T processors and mixed 32/64 bit packages.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)If the package runs on an x64 processor, the "64-bit package for x64 processors(AMD64, EM64T)" must be selected.

You can read more about the difference between those types in the [Package Types](https://tools.techidaily.com/advancedinstaller/products/) page.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130870/7443" target="_top" id="2130870">
  <img src="//a.impactradius-go.com/display-ad/7443-2130870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Installation Type

* **Per-user only** \- the application will be available only for the user who installed it.  
   * On Windows Vista or above, with this option set, the logged user will never be elevated to administrative privileges, so if the installation requires such privileges, it will fail.
* **Per-user only (with administrator rights required)** \- on Windows Vista or above, use this option to create a package which will be installed per user but requires administrator privileges (e.g. its application files need to be installed in a privileged location such as "Program Files").  
   * In this case, the user may see anElevation Prompt dialog that will ask for administrator privileges. If the logged user is a member of the "Administrators" user group, he will be asked to allow or deny the installation. Otherwise, he will be prompted to provide credentials for one of the computer administrators.  
   * On other Windows versions, this option behaves like the previous one.
* **Per-machine only (fails if the user is not administrator)** \- the application will be available for all the users of that machine.  
   * On Windows Vista or above the user may see an Elevation Prompt dialog that will ask for administrator privileges when installing the package. If the logged user is a member of the "Administrators" user group, he will be asked to allow or deny the installation. Otherwise, he will be prompted to provide credentials for one of the computer administrators.
* **Per-machine if the user is an administrator, per-user otherwise** \- the application will be installed "Per-machine" if the user has administrative rights and "Per-user" otherwise.  
   * To help with the appropriate install location, [AI\_UserProgramFiles property](https://tools.techidaily.com/advancedinstaller/products/) will be referenced in the application folder path.  
   * On Windows Vista and above this option has the same installation behavior as the previous one.  
   * On Windows 7 or above the installation will be _per-user_ with no UAC prompt only if the resources are installed in [per-user locations](https://tools.techidaily.com/advancedinstaller/products/). Besides this, the installation will also require the [InstallTypeDlg](https://tools.techidaily.com/advancedinstaller/products/) so the user can choose the _per-user_ option. This option will set the [MSIRunningElevated property](https://tools.techidaily.com/advancedinstaller/products/) which can be manually set instead of using the dialog.

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)The "Per-machine if the user is an administrator, per-user otherwise" option requires "InstallTypeDlg" dialog to be present in [Dialogs page](https://tools.techidaily.com/advancedinstaller/products/)

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)A per-user installation cannot upgrade a per-machine installation, and a per-machine installation cannot upgrade a per-user installation. However, you can try using a [Preserve Install Type of the old version](https://tools.techidaily.com/advancedinstaller/products/) predefined UI custom action.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)On Windows Vista or above, it is strongly recommended that you do not alter the value of the ALLUSERS property during install.

When performing a Per User installation, the package must respect some rules:

* it creates registry entries only under HKEY\_CURRENT\_USER
* it creates shortcuts only in the user's profile (not in per-machine locations)
* it writes information only in Per User locations (for example a normal user cannot write in the "Windows" or "Program Files" folders)

### Reboot Behavior

 Windows Installer can determine when a system reboot is required and automatically prompt the user at the end of the installation. For instance, if the installer needs to replace any files that are in use during the installation it will automatically prompt for a reboot once the installation is finished.

You can change this default behavior by specifying one of the options below to always prompt for a reboot or to suppress some or all reboot prompts.

* **Prompt for Reboot when required** \- let Windows Installer decide when a system reboot is necessary (for example, when it needs to replace any files that are in use during the installation).
* **Force Reboot after install** \- always prompt for a reboot at the end of the installation, even if a system reboot is not required.
* **Suppress Reboot after install, except for ForceReboot actions** \- Suppress prompts for a reboot at the end of the installation. If the installer encounters the ForceReboot action, it still prompts the user with an option to reboot during the installation.
* **Suppress all Reboots and Reboot prompts** \- all reboots and reboot prompts at the end of the installation and during the installation (initiated by the ForceReboot action) are suppressed.

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)A reboot request will discontinue a [chained installation](https://tools.techidaily.com/advancedinstaller/products/). If one of the chained packages requires a reboot, you should suppress it by setting the REBOOT property to ReallySuppress. For the main package, you can set the REBOOT property to Force. This way a reboot will be performed when the chained installation is complete.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425">
  <img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885947/19272" target="_top" id="1885947">
  <img src="//a.impactradius-go.com/display-ad/19272-1885947" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Perform the reboot if required without showing any prompts

This option makes the installer perform any required reboots automatically, without prompting the user.

<!-- affiliate ads begin -->
<span id="1834903">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834903.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834903">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834903.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834903%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834903/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Limit to a basic user interface (simple progress and error handling)

 This option directs Windows Installer to display only a dialog with a progress bar showing the evolution of the installation and the message boxes that display error messages. It is used especially for unassisted or automated installs (e.g. deployment through Group Policy). 

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)If you select this option, the “Disable Modify” option from “Programs and Features (Control Panel)” will also be selected.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047351/19272" target="_top" id="2047351">
  <img src="//a.impactradius-go.com/display-ad/19272-2047351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Enable Verbose Logging

By enabling this option, a log file will be generated each time the install package runs. This option sets the Windows Installer **MsiLogging** property to **vp** value. Windows Installer will automatically set the **MsiLogFileLocation** property to the path where the log file will be generated. By default, the **MsiLogFileLocation** will point to:

* _CurrentUser\\LocalSettings\\Temp\\MSI\*.LOG_ for Windows XP.
* _CurrentUser\\AppData\\Local\\Temp\\MSI\*.LOG_ for Windows Vista or later.

Where \* is a random set of letters and numbers.

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)The **MsiLogFileLocation** is a **Read-only** property and cannot be changed by the package author or by the user. Its value is automatically set**during** the runtime of the installation package.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)This option requires Windows Installer 5.0 on Windows Server 2008 R2 or Windows 7\. Windows Installer 4.0 or Windows Installer 4.5 on Windows Server 2008 or Windows Vista, Windows Installer 4.5 on Windows Server 2003 or Windows XP to work properly.

### Execution Level

**Run as administrator** \- enabling this option automatically sets the execution level to "Require Administrator". Disabling it will set the execution level back to "As Invoker" default.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)Checking "Run as administrator" doesn't give administrative permissions to the Control Panel instance of the application.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)Run as administrator does not work for MSI packages launched in maintenance mode.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148642/16836" target="_top" id="2148642">
  <img src="//a.impactradius-go.com/display-ad/16836-2148642" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148642/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Execution level...** \- this link displays the EXE bootstrapper's [Execution Level Settings](https://tools.techidaily.com/advancedinstaller/products/).

## Minimize Installation Time

### Fast Installation

These options enable you to drastically reduce the time it takes your application to install by:

* Moving files on the same volume rather than copy
* Suppressing installation progress estimate

Requirements:

* Installation is using the [Enhanced User Interface](https://tools.techidaily.com/advancedinstaller/products/).
* The install location selected by the user is on the same drive where the files have been extracted.
* Per-machine installation is performing.
* The first time the application is installing.
* No features are being advertised or installed to run from source.
* No isolated components are being installed.

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)On Windows 7 and above when _Fast Installation_ option is used, the standard users access to installed files will be restricted.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)The three following options can be used together but are ignored on machines with Windows Installer 4.0 or older. The installation time can be decreased with these options only when **Windows Installer 4.5** or higher is found on the target machine.

### Don't save system restore points for installation

If this option is set, Windows Installer will no longer create system restore points for the install process.

### Perform only file costing and skip checking other costs

If this option is set, Windows Installer will perform only file costing, ignoring the rest of costs.

### Reduce the frequency of progress messages

If this option is set, the installation progress is updated less frequently.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036486/19272" target="_top" id="2036486">
  <img src="//a.impactradius-go.com/display-ad/19272-2036486" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036486/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Topics

* [Execution Level Settings Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Dialog to set the execution level.

#### Did you find this page useful?

Please give it a rating:

 Thanks!

#### Report a problem on this page

Information is incorrect or missing

Information is unclear or confusing

Something else

#### Can you tell us what’s wrong?

Send message

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-leveraging-unwanted-scenes-for-creative-outcomes/"><u>[New] 2024 Approved Leveraging Unwanted Scenes for Creative Outcomes</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-the-ultimate-tripod-techniques-for-video-creators/"><u>[New] In 2024, The Ultimate Tripod Techniques for Video Creators</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-quick-tips-for-editing-igtv-content-to-stand-out/"><u>[New] Quick Tips for Editing IGTV Content to Stand Out</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-free-count-down-timers/"><u>Best Free Count Down Timers</u></a></li>
<li><a href="https://fox-sys.techidaily.com/best-music-visualizer-apps-of-2020-top-7-picks-for-immersive-audio-experience/"><u>Best Music Visualizer Apps of 2020: Top 7 Picks for Immersive Audio Experience</u></a></li>
<li><a href="https://fox-sys.techidaily.com/complete-step-by-step-instructions-capturing-screenshots-on-your-windows-8-system/"><u>Complete Step-by-Step Instructions: Capturing Screenshots on Your Windows 8 System</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/creating-funny-text-memes-a-step-by-step-guide/"><u>Creating Funny Text Memes A Step-by-Step Guide</u></a></li>
<li><a href="https://fox-sys.techidaily.com/easy-techniques-to-transform-videos-for-macos-mavericks-users/"><u>Easy Techniques to Transform Videos for macOS Mavericks Users</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effective-solutions-for-when-your-lenovo-laptop-camera-stops-functioning/"><u>Effective Solutions for When Your Lenovo Laptop Camera Stops Functioning</u></a></li>
<li><a href="https://fox-sys.techidaily.com/mastering-virtual-greeting-cards-top-picks-for-web-based-design-software-with-complete-beginners-guide/"><u>Mastering Virtual Greeting Cards: Top Picks for Web-Based Design Software with Complete Beginner's Guide</u></a></li>
<li><a href="https://fox-sys.techidaily.com/modify-parent-child-conversations-a-comprehensive-guide/"><u>Modify Parent-Child Conversations: A Comprehensive Guide</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-redmi-k70-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from Redmi K70.</u></a></li>
<li><a href="https://fox-sys.techidaily.com/solving-the-issue-why-cant-my-iphone-play-apple-music-and-how-to-get-it-working/"><u>Solving the Issue: Why Can't My iPhone Play Apple Music and How To Get It Working?</u></a></li>
<li><a href="https://fox-sys.techidaily.com/the-ultimate-tutorial-on-crafting-a-captivating-book-trailer-to-boost-your-sales/"><u>The Ultimate Tutorial on Crafting a Captivating Book Trailer to Boost Your Sales</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-infinix-note-30-vip-racing-edition-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Infinix Note 30 VIP Racing Edition? | Dr.fone</u></a></li>
<li><a href="https://fox-sys.techidaily.com/top-3-methods-for-converting-pdf-files-into-microsoft-word-format-on-pc/"><u>Top 3 Methods for Converting PDF Files Into Microsoft Word Format on PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unlock-a-new-world-of-sound-the-top-15-movies-featuring-dolby-atmos-technology-perfect-for-in-home-enjoyment/"><u>Unlock a New World of Sound: The Top 15 Movies Featuring Dolby Atmos Technology, Perfect for In-Home Enjoyment</u></a></li>
</ul></div>

