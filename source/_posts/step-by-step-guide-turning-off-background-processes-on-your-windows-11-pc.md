---
title: "Step-by-Step Guide: Turning Off Background Processes on Your Windows 11 PC"
date: 2024-08-27 22:59:16
updated: 2024-08-29 10:47:48
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/6d6520e192a843298c5f3fb60d79f701e9d849b7c957109090842f5892749c79.jpg
---

## Step-by-Step Guide: Turning Off Background Processes on Your Windows 11 PC

### Key Takeaways

* To disable background apps in Windows 11, open the Settings app and navigate to the Apps tab. Then, select the app you want to disable, go to Advanced options, and choose "Never" under Background Apps Permissions.
* If you're using a PC with multiple users, you can disable background apps for all users by making changes in the Registry Editor.

 There are a few things you can do to improve your computer's overall performance. One of these is to disable unnecessary applications running in the background. That way, important apps have all the CPU resources they need. Here are five ways to disable background apps on Windows.

##  Why You Should Disable Background Apps?

 Background applications running on Windows devices consume system resources, memory, and CPU power. These applications can impact system performance, such as increased boot time and slow response time. However, disabling background apps can help fix these issues.

 Even if you aren't facing any of these errors, disabling these applications can still have a significant impact. Here are some reasons why you should disable background apps in Windows 11:

* **Improve System Performance:** Applications running in the background, even when not being used, can consume system resources and make your PC slow. Disabling these applications can free up these resources and improve your system's performance.
* **Increase Battery Life:** Good battery life is critical on laptops. Disabling background applications can help extend the battery life of your device by reducing unnecessary power consumption.
* **Reduce Data Consumption:** Some applications consume network data when running in the background, eating away at any data limits you have. Disabling those apps gives you more control over your network resources.
* **Reduce Distractions:** Disabling background apps can make your computing experience more focused and less cluttered. This is because these apps generate notifications and pop-ups that can distract or interrupt your workflow.

##  How to Disable Background Apps in Windows 11

 As Windows 11 doesn't offer any direct approach to disabling background apps like Windows 10 formerly did, we'll be using some unconventional methods. But we'll start with the most straightforward method.

###  1\. Disable Background Apps Using Settings App

 Using the Settings app, you can disable apps individually from running in the background.

 Press the Start menu and click the "Settings" icon, or use the Windows+i key combination to open the Settings app.

![Click Start and select the Settings icon.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/open-windows-settings.png) 

 Navigate to the "Apps" tab in the left pane and click "Installed apps."

![Navigate to Apps in the left pane and select Installed apps](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/navigate-to-apps-in-the-left-pane-and-select-installed-apps.jpg) 

 Search the application you want to turn off the background permission for, click the three dots next to the app and select "Advanced options." If the option isn't available, the application doesn't support background permissions management.

![click three dots next to the app and select Advanced options](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/click-three-dots-next-to-the-app-and-select-advanced-options.jpg) 

 Once the Advanced Options tab opens, scroll down to "Background Apps Permissions" and click on the drop-down below "Let this app run in background."

 Select "Never" in the drop-down, and the app will now stop running in the background.

![Select Never in the drop-down under Background apps permissions](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/select-never-in-the-drop-down-under-background-apps-permissions.png) 

 All apps are set to the "Power optimized (recommended)" option by default. This option indicates that Windows will automatically decide when to run the app in the background and when to disable it. However, if it's set to "Always," the application will run continuously in the background.

###  2\. Disable Background Apps Using Power & Battery Settings

 If you're not sure which apps you should disable for the sake of preserving power, the [Power & Battery](https://win-answers.techidaily.com/expert-advice-overcoming-technical-hurdles-in-the-phasmophobia-vr-game/) tab in the Settings app provides insights on the power and battery consumption of all installed apps. It also shows the power and battery consumption of apps running in the background and allows to disable them based on the insights.

 Press "Start" and click the "Settings" icon, or click the Windows+i key combination to open the Settings app.

![Click Start and select the Settings icon.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/open-windows-settings.png) 

 Navigate to the "System" tab and click on "Power & battery."

![Navigate to the System tab and select Power & settings](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/open-power-and-battery-settings.jpg) 

 Here, click on "View detailed info" beside Power Insights.

![View detailed info](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/view-detailed-info.png) 

 Scroll down to "Power usage per app," click on three dots beside the app you want to disable running in the background, and select "Manage background activity."

![Manage background activity](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/manage-background-activity.jpg) 

 Again, scroll down to "Background Apps Permissions," click on the drop-down below "Let this app run in background" and select "Never."

![Select Never under Let this app run in background](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/select-never-under-let-this-app-run-in-background.jpg) 

 The app will now stop running in the background. This will decrease your device's power consumption and increase its battery life.

###  3\. Disable Background Apps for Current User

 If you're using a Windows 11 PC with multiple users and want to disable background apps for the current user, you can create a [Windows REG file](https://tech-revival.techidaily.com/diagnosing-and-resolving-interface-issues-chatgpts-trouble-with-plugin-connectivity/). A REG file is a text file generated by exporting values from the Windows Registry.

 To do so, open a new Notepad document. Paste the following code into the file:

        `[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\BackgroundAccessApplications]  
"GlobalUserDisabled"=dword:00000001  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search]  
"BackgroundAppGlobalToggle"=dword:00000000`
    
![Disable Background Apps using a REG file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/disable-background-apps-using-a-reg-file.png) 

 Click Ctrl+Shift+S, name the file "Disable Background Apps", and save the file with a ".reg" extension.

 Now, right-click on the reg file and click on "Open." A UAC prompt will appear. Click "Yes" to proceed.

![Open the Disable background applications REG file](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/open-the-disable-background-applications-reg-file.jpg) 

 Running the REG file will set the GlobalUserDisabled to 1 and the BackgroundAppGlobalToggle to 0 in the Registry Editor. Doing so will disable background access to applications.

 If you want to enable background applications for the current user, replace the code in the reg file with this:

        `[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\BackgroundAccessApplications]  
"GlobalUserDisabled"=-  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Search]  
"BackgroundAppGlobalToggle"=-`
    
###  4\. Disable Background Apps for All Users

 On a PC with multiple users, you can disable background apps for all users by making some changes in the Registry Editor.

 Before making any changes in the Windows Registry, [create a restore point](https://instagram-video-files.techidaily.com/updated-in-2024-multiplying-joy-sharing-a-pile-of-photos-and-videos-with-instagram/). A single mistake in the registries can make your device crash. Creating a restore point will help [restore Windows settings](https://screen-recording.techidaily.com/quick-start-guide-dells-simple-screen-recording-methods-for-2024/) if things go wrong.

 Press Windows+R to open Run, type "regedit" and hit Enter. A UAC will prompt up seeking permission—click "Yes."

 Now, in the Registry Editor, navigate to the following path:

        `HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows`
    
 Here, you'll need to create a new key under Windows. To do so, right-click on the "Windows" folder, select New > Key and name it "AppPrivacy."

![Create a new key under Windows folder](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/create-a-new-key-under-windows-folder.jpg) 

 Next, select the "AppPrivacy" key, right-click on the space in the right pane, and select New > DWORD (32-bit) Value.

![Create new DWORD value under AppPrivacy key](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/create-new-dword-value-under-appprivacy-key.jpg) 

 Rename the newly created DWORD (32-bit) value as "LetAppsRunInBackground" and hit "Enter" to proceed.

![Rename the DWORD value as LetAppsRunInBackground](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/rename-the-dword-value-as-letappsruninbackground.jpg) 

 Double-click on the "LetAppsRunInBackground" value, type "2" under Value Data, and click "OK" to save the changes.

![Set value data as 2 and click OK](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/set-value-data-as-2-and-click-ok.jpg) 

 Close the Registry Editor and restart your PC for the changes to take place. However, if you want to enable background apps again, set the Value data to 0.

###  5\. Disable Background Apps Using the Group Policy Editor

 Lastly, you can also use the [Group Policy Editor](https://youtube-clips.techidaily.com/2024-approved-building-a-custom-link-for-youtubes-auto-subscribe/) to disable background apps on your Windows Device. Before proceeding, know that the Group Policy Editor is only available on Pro, Education, and Enterprise editions of Windows 11\. If you're using the Home version, you'll have to stick to one of the previous methods.

 To begin, press the Windows+R key combination to open the Run toolbox, type "gpedit.msc", and hit "Enter."

 Once the Group Policy Editor opens, navigate to the following path:

        `Computer Configuration\Administrative Templates\Windows Components\App Privacy​`
    
 Double-click on the "Let Windows apps run in the background" policy in the right pane.

![Double-click on Let Windows apps run in the background policy](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/double-click-on-let-windows-apps-run-in-the-background-policy.jpg) 

 In the Let Windows apps run in the background properties window, select "Disable."

 Lastly, click on "Apply" and then on "OK" to save the changes.

![Disable the Let Windows apps run in the background](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/disable-the-let-windows-apps-run-in-the-background.jpg) 

 Restart your device once for the changes to kick in. To revert the changes made, follow the same steps and select Enabled.

---

 Congratulations! You've now disabled the background apps on your Windows 11 device. They won't consume your device's space and make it slow anymore. To make your desktop PC more fast and efficient, learn [how to disable startup programs in Windows](https://tech-recovery.techidaily.com/get-clarity-back-in-photos-how-to-repair-iphone-camera-focusing-problems/).

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
