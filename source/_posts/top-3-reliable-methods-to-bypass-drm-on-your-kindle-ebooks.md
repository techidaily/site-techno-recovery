---
title: Top 3 Reliable Methods to Bypass DRM on Your Kindle Ebooks
date: 2024-08-20 13:41:51
updated: 2024-08-21 11:16:11
categories:
  - epubor
thumbnail: https://thmb.techidaily.com/23dc4857279699198e48a622a7713386fd30f7f47908caf6a0fe50229057f885.jpg
---

## Top 3 Reliable Methods to Bypass DRM on Your Kindle Ebooks

## 3 Tried-and-True Ways to Remove DRM from Kindle Books

Posted by [Ada Wang](https://plus.google.com/+AdaWang/posts) on 8/14/2024 4:37:32 PM.

4.7 [(68 comments)](http://www.epubor.com/#comment-area) 



![follow](http://www.epubor.com/images/follow.png)

If you've got some Kindle books, you've likely heard that they come with Amazon's Kindle DRM, which locks your books into Kindle devices ![remove drm from kindle books](https://epubor.com/images/uppic/remove-drm-from-kindle-books.png)and kindle reading apps. But as a consumer, when we have already paid these files, why should we be stopped from reading them just because we didn't buy a Kindle but an iPad or a Kobo e-ink reader instead? This deeply hurts us. Right?

So if you want to read Kindle books on non-Kindle devices or apps, the perfect solution is to remove the DRM. And in fact, it is also the best way to protect your purchases and enables you to read your own books more freely. Additionally, it allows you to back up, copy, print, and share Kindle books with friends. 

But, how to? You may have wondered this problem for a while. Don't worry, this article will introduce **3 ways to remove drm from Kindle books**. Keep reading to learn how to liberate your kindle books best.

* [Method 1: Remove DRM from Kindle books with Calibre Plugin](https://tools.techidaily.com/epubor/products/)
* [Method 2: Remove DRM from Kindle books with Python Scripts](https://tools.techidaily.com/epubor/products/)
* [Method 3: Remove DRM from Kindle books with Shareware--Epubor Ultimate](https://tools.techidaily.com/epubor/products/)

### First things first: Download Kindle books

To begin with, firstly I strongly recommend you get your kindle books prepared on your computer.

 If you have the Kindle e-ink device, you can just download Kindle books via your Kindle device. 

If you do not have Kindle device, you have to install Kindle App(kindle for pc/mac desktop application, or Kindle Cloud Reader web app). Launch the Kindle app, log in with your own amazon account, then all your purchased files in kindle store would be synced. Choose those files you want to deal with, double click on book cover, then downloading begins. Once you have done that, you can close the app, find your downloaded books files at destination folder ([kindle content folder location](https://tools.techidaily.com/epubor/products/)). 

### Method 1: Remove DRM from Kindle books with Calibre Plugin

Calibre is an excellent ebook library management tool, open source software, helps you remove drm from books and convert format to others.

Step 1  Install Calibre.

Install [Calibre](http://calibre-ebook.com/download)(v7.x) onto your computer if you haven't already get them installed.

Then [download the latest DeDRM-tools](https://github.com/noDRM/DeDRM%5Ftools/releases/download/v10.0.9/DeDRM%5Ftools%5F10.0.9.zip)(v10.0.9). It comes as a .zip archive, and you need to unzip it, then open the unzipped folder and put the "DeDRM\_calibre\_plugin" folder where you can find it.

![open calibre dedrm plugin folder from dedrm plugin zip](https://www.epubor.com/images/uppic/dedrm-plugin-zip-file.png)

Step 2  Install Calibre DeDRM Plugins.

Run Calibre on computer (here takes mac as an example, remove DRM from Kindle books with calibre mac).

From the pref pane "Preferences"--"Change calibre behavior".

![change calibre behavior on mac](https://epubor.com/images/uppic/change-calibre-behavior.png)

(**Note:** Do _not_ click “Get plugins to enhance calibre”).

Click on Plugins (under “Advanced”) --"Load plugin from file".

![load plugin files on mac](https://epubor.com/images/uppic/load-plugin.png)

Select the "DeDRM\_plugin.zip" file you placed in step 1 and click "Open". 

![select calibre DeDRM plugin on mac](https://epubor.com/images/uppic/select-dedrm-plugin-zip-mac.jpg)

Click on the “Add” button, "Yes" in the "Are you sure?" warning dialogue that appears. 

![calibre DeDRM plugin added on mac](https://epubor.com/images/uppic/add-calibre-plugin-zip-on-mac.png)

After succeed the plug-in has been installed. Calibre will add this plugin under its "File type plugins" list in the Preferences window, OK. Restart Calibre please.

![DeDRM under file type plugins](https://www.epubor.com/images/uppic/dedrm-location.png)

Step 3  Repeat the previous step to add the KFX-ZIP plugin to Calibre.

You should also have **[kfx input plugin](https://www.mobileread.com/forums/showthread.php?t=291290)** installed if trying to dedrm Kindle KFX books in 2024\. 

Step 4  Import DRMed books to Calibre.

If your kindle books are downloaded via Kindle desktop app, import your downloaded Kindle books to Calibre, then the DRM will be removed automatically. But if you've previously added books to calibre that with drm, you'd better import them again. Job done, you can click "click to open" at the right side, to get a preview in calibre library.

If your kindle books are downloaded via Kindle eReaders, you should customize the plugin and input the KSN info. 

![calibre kindle drm removal plugin](http://www.epubor.com/images/uppic/customize-dedrm-plugin.png)

**Update: (Due to a change in DRM) Calibre DeDRM plugins will no longer work with Kindle KFX books if Kindle for PC app updated to 2.4.1 (70946).** Re-install 2.4.70904, working as before, or you can also try to use the Epubor Ultimate as a better alternative. 

### Method 2: Remove DRM from Kindle books with Python Scripts

**Notice: This method is a little hard to use, so if you are not so familiar with computer or code, I don't think challenging this method is a wise choice.**

Nearly all the eBook DRM Removal softwares are Python scripts, including Calibre.

Step 1  Install Python at first.

Firstly you need [Python](https://www.python.org/download/) installed on your computer.

Step 2  Install Pycrypto.

Pycrypto is a basic DRM module that all the DRM removal tools are using. Download and install it please.

For Win: [pycrypto-2.1.0.win32-py2.6.exe](https://www.epubor.com/freesource/pycrypto-2.1.0.win32-py2.6.exe)

For Mac: [pycrypto-2.6.1.tar.gz](https://www.epubor.com/images/uppic/pycrypto-2.6.1.tar.gz)

Step 3  Run KindleBooks.pyw.

Run [KindleBooks.pyw](https://www.epubor.com/images/uppic/KindleBooks.zip), then input the information related to Kindle Books: input file, output file, and Kindle.info. As your kindle ebooks has been downloaded to your computer via Kindle for PC/Mac, so it is easy to find the Kindle.info, because it will be created when the desktop application installed.

![run KindleBooks.pyw](https://epubor.com/images/uppic/KindleBookspyw.jpg)

### Method 3: Remove DRM from Kindle books with Shareware (DRM-off-Able)

This method is applied to both beginners and experts. And I highly recommend you get it with a free trial. I do believe after you tried it, you will fall in love with her.

Learn how to remove kindle drm 2024 with Video

Step 1  download the powerful shareware [Epubor Ultimate for PC or Mac](https://tools.techidaily.com/epubor/ultimate/) to your computer.

Download Epubor Ultimate for free:

[](https://tools.techidaily.com/epubor/ultimate/) [](https://tools.techidaily.com/epubor/ultimate/) 

Step 2  Run Epubor Ultimate.

 Then the kindle books downloaded via Kindle for PC or Mac will be displayed under Kindle column in the left sidebar, while the Kindle books downloaded via Kindle devices will be displayed under Kindle Device column in the left sidebar after connecting Kindle e-ink reader to computer.

I highly recommend downloading Kindle books using [Kindle for PC 2.4.0](https://download.epubor.com/KindleForPC-installer-2.4.0-70904.exe) or [kindle for Mac 1.40](https://download.epubor.com/KindleForMac-installer-1.40.dmg) to avoid issues with Kindle book drm removing failures. 

![benefit of epubor](https://epubor.com/images/uppic/kindle-pc-241-tips.png)

Step 3  Rip Kindle DRM.

Add the Kindle books from the left sidebar to the right main window. Then all the books will be decrypted immediately.

![epubor decrypt kfx](https://epubor.com/images/uppic/epubor-decrypt-kfx.png)

It uses python scripts but much more easily to operate than method 2.

It provides more friendly interface than Calibre. Of course it's also easier than calibre to learn how to use.

![epubor works when calibre doesn't](http://www.epubor.com/images/uppic/epubor-kindle-better-calibre.jpg)

![](http://www.epubor.com/images/faq.png)Key Takeaways

1\. To active the drm-removing function on Calibre, you need to install extra drm plugin.

2\. Epubor Ultimate is definitely the most recommended tool for removing kindle drm because it is super easy-to-use and offers 7/24 customer support.

3\. DRM is intended to stop the illegal distribution of digital content, so please just keep the drm-free ebooks for yourself. Don't spread it. 

4\. For kindle manga to pdf conversion on Mac, there are two ways to handle them: [using kindle device](https://tools.techidaily.com/epubor/products/) or [using Epubor kindle converter.](https://tools.techidaily.com/epubor/kindle-converter/)

#### Review for Epubor Ultimate Software 

My theater group wants to stage a play. Unfortunately, the book we need does not exist in our country, Ecuador. The only place we find it is on Amazon, available to download for Kindle. Not all members of our theater group have a Kindle or a tablet to have the text available, so the most convenient thing is to print it. However, transferring a Kindle file to print is almost an impossible task. 

I tried to convert the book to pdf with the Caliber software, but it didn't recognize the book. I installed two plug-ins, one for Caliber to read KFX files and another to remove DRMs, but nothing. It was still useless. Also, I looked for converters online and they all failed. 

 Looking for more solutions, I came across [Epubor Ultimate](https://tools.techidaily.com/epubor/ultimate/) and it blew me away. I installed it, ran it and, immediately, it found the Kindle file, without me having to search for it, I hit convert and it converted it to PDF without any complications, without doing anything else, with one click, as if it were magic.

 Without a doubt, the best option for your Kindle files. 

![epubor ultimate review when dedrm kindle](http://www.epubor.com/images/uppic/ultimate-kindle-review.png)

![author](https://www.epubor.com/images/uppic/1-22-2013 12-03-06 AM.png)

[Ada Wang](https://plus.google.com/+AdaWang/posts) works for Epubor and writes articles for a collection of blogs such as ebookconverter.blogspot.com.

SHARING IS GREAT!

[Tweet](https://twitter.com/share) 

[SAVE PAGE AS PDF](https://tools.techidaily.com/epubor/products/) 



68 Comments

[reply](https://tools.techidaily.com/epubor/products/) 

[reply](https://tools.techidaily.com/epubor/products/) 

Alok

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

10/30/2016 13:24:58

Worked first option. Thank you.

[reply](https://tools.techidaily.com/epubor/products/) 

Joem

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

02/3/2017 00:30:39

do you have to install python and pycrypto if you're using calibre?

[reply](https://tools.techidaily.com/epubor/products/) 

Alen

[Re:Joem](https://tools.techidaily.com/epubor/products/)

02/15/2017 10:31:50

They are installed by Calibre, you do not need to install again.

[reply](https://tools.techidaily.com/epubor/products/) 

waqas

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

03/7/2017 18:15:43

hello please help me  
 i tried first method of calibre and i still getting error evan i installed successfully plugin in calibre but when i add drm book i got error  
 second i installed epubor and when i add drm book azw i got invailed format error also 

[reply](https://tools.techidaily.com/epubor/products/) 

Noswanna

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

09/30/2017 12:44:12

Worked very easily even for someone not very computer literate. Thanks.

[reply](https://tools.techidaily.com/epubor/products/) 

Ernie

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

09/8/2018 11:11:58

I followed your guide one by one, but finally I still choose your tool epubor ultimate as it's really very easy to go.

[reply](https://tools.techidaily.com/epubor/products/) 

Carolina 

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

01/24/2019 12:09:26

I already had the books on Calibre, followed the steps and added the books again after. Though it seems like the drm was removed, the images in the ebook are gone! can you help me please?

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor Angel

[Re:Carolina](https://tools.techidaily.com/epubor/products/)

01/24/2019 17:28:24

Contact epubor customer support please. We need to check your problem in detail.

 Thanks for your comment.

[reply](https://tools.techidaily.com/epubor/products/) 

mark

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

02/5/2019 16:33:22

I think it should be clearer above that this does NOT work with any books from Amazon Unlimited.

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:mark](https://tools.techidaily.com/epubor/products/)

02/11/2019 09:47:47

Thank you for your comments. Epubor software are not working on the rented books. As Kindle unlimited books are rented books, Epubor software will not handle them.

[reply](https://tools.techidaily.com/epubor/products/) 

a

[Re:Epubor](https://tools.techidaily.com/epubor/products/)

07/18/2019 00:39:27

DeDRM plugin for Calibre can remove DRM from Kindle books rented via Kindle Unlimited if you use Kindle for PC 1.17 (only this version!)

[reply](https://tools.techidaily.com/epubor/products/) 

Anthony

[Re:a](https://tools.techidaily.com/epubor/products/)

08/20/2019 10:06:41

Worked for me with 1.24, however, only the unlimited books that I actually started reading or have finished reading.

[reply](https://tools.techidaily.com/epubor/products/) 

Hugo

[Re:mark](https://tools.techidaily.com/epubor/products/)

02/16/2024 11:42:51

it does... I use it all the time. 

[reply](https://tools.techidaily.com/epubor/products/) 

alan p gibney

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

02/27/2019 01:35:09

doesn't work anymore

[reply](https://tools.techidaily.com/epubor/products/) 

De

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

03/1/2019 03:30:36

I have Kindle 1.23 on my mac, I've installed Calibre w/in the last 30 days and the latest deDrm plug-in from Alf (v. 6.6.1) and I can't convert a Kindle book purchased in January of 2019\. Could it be how I'm importing the actual book into Calibre? Right now all Kindle content is in my \~user/Library folder, which I only know how to access from the Finder app by choosing "Go" while pressing "Option" key. I don't know how to access \~user/Library from within Calibre. Adding the book to my library by dragging and dropping the .azw file is not working. Is there a reason a book purchased in Jan of 2019 can't be imported into Kindle 1.23 for Mac? Kindle says my last update was 9/2018 and I don't automatically update apps, so my Kindle version shouldn't have changed since then. I tried moving just the .azw file to my desktop and the errors were even worse. I also tried moving the whole folder to the desktop, and that did not work either. Please let me know if you have any suggestions!

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:De](https://tools.techidaily.com/epubor/products/)

03/1/2019 09:58:52

1\. Please delete the Kindle book from your mac and redownload it.  
 2\. Please try to use Epubor Ultimate to remove the DRM from them.  
 3\. If you are failed again, please contact us via support@epubor.com and describe your problem clearly. We will help you fix it.

[reply](https://tools.techidaily.com/epubor/products/) 

Lise Andreasen 

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

03/19/2019 14:25:53

I can't get any of these methods to work.

 Kindle fire, Windows, Ubuntu, Calibre with plugin (not sure where to input the serial number).

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor Angel

[Re:Lise Andreasen](https://tools.techidaily.com/epubor/products/)

03/25/2019 10:19:46

Use Kindle desktop to re-download your Kindle books, then Epubor Ultimate will works.

 We can't help you directly remove DRM from Kindle fire.

[reply](https://tools.techidaily.com/epubor/products/) 

Jim

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

08/24/2019 01:43:04

Wow, so easy. Works so quickly! Finally I can ditch multiple reader apps and stay with one reader for all my books. Thanks for posting this, the Calibre plugin works fast and easy!! 

 One note is you might want to mention to turn off auto update in the PC Kindle app. It might update itself to the newest version and "break" the plugin.

[reply](https://tools.techidaily.com/epubor/products/) 

Igor

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

09/2/2019 03:28:24

The Epubor works very well if you follow all steps. Only one point: the program only extract the DRM if you buy the license. It gives you a small demonstration but to have the hole kindle book available, you have to buy it.

[reply](https://tools.techidaily.com/epubor/products/) 

Pjcads

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

10/22/2019 04:44:13

Save your money if you have updated to the latest MacOS and just go with the Calibre option. The version of Kindle app they tell you to "downgrade" to is 32bit, thus will not work. Epubor was a much more efficient option until now. Maybe they'll come up with a "fix," but until they do, save your money.

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:Pjcads](https://tools.techidaily.com/epubor/products/)

10/22/2019 11:05:41

If you have upgrade your Kindle app to 1.26 before updating your mac os to catalina and also, use this code: sudo chmod -x /Applications/Kindle.app/Contents/MacOS/renderer-test and then right click your kindle books for downloading. Then use Epubor Ultimate to remove Kindle drm successfully. Then when you update your mac os to catalina, you can still use this method to remove Kindle drm. Please refer: <https://www.epubor.com/remove-kindle-drm-on-macos-1015-catalina.html>

[reply](https://tools.techidaily.com/epubor/products/) 

Elle

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

12/2/2019 15:59:54

I have a question. If I convert ebooks to mobi format and are reading them through my Kindle App, will Amazon have a way of seeing that I have mobi books I haven't bought through them??? I am concerned because I have invested a lot of money in my Kindle collection and don't want to risk them cancelling my Kindle account. Thanks.

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor Iris

[Re:Elle](https://tools.techidaily.com/epubor/products/)

12/3/2019 09:15:23

Thank you for contacting us. I don;t think Amazon will detect your personal files. If you have removed DRM and convert the file to mobi, it will become your personal file. Amazon has no right to detect your personal files. 

[reply](https://tools.techidaily.com/epubor/products/) 

Pedro

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

01/25/2020 06:48:28

I have installed the previous version of kindle for mac, but it doesn't open. It tells me that I must update.  
 I had followed the steps indicated.

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:Pedro](https://tools.techidaily.com/epubor/products/)

01/26/2020 14:23:04

For kindle textbooks, it cannot be downloaded via old kindle desktop.

[reply](https://tools.techidaily.com/epubor/products/) 

Louie Reynolds

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

02/4/2020 19:31:13

Kindle Mac 1.23 cannot be opened on Catalina as it is a 32 bit app and needs to be updated to 1.25+ to be a 64 bit app. Are there any other solutions, I have autism, I am just trying to move some of my books to voice dream so I can read/listen to them how I wish.

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:Louie Reynolds](https://tools.techidaily.com/epubor/products/)

02/6/2020 09:26:39

Yes, please follow this guide to remove kindle drm on mac catalina&gt;&gt;<https://www.epubor.com/remove-kindle-drm-on-macos-1015-catalina.html>

[reply](https://tools.techidaily.com/epubor/products/) 

Who cares?

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

03/17/2020 04:48:21

So this doesn't work anymore? Hell, my books aren't even in "My Kindle" folder to open. 

 If it doesn't work anymore, why don't you put that at hte top, instead of hte bottom of the article?

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:Who cares?](https://tools.techidaily.com/epubor/products/)

03/19/2020 15:53:27

Thank you for asking. The method 1 is still working only if you can download your kindle books via kindle for pc or mac 1.23 or older.

[reply](https://tools.techidaily.com/epubor/products/) 

Kimberley Matthews

[Re:Epubor](https://tools.techidaily.com/epubor/products/)

10/28/2020 06:48:33

Nope! Broken again. Last time I buy Amazon books.

[reply](https://tools.techidaily.com/epubor/products/) 

andy brown

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

03/18/2020 14:09:21

 Wanted to put my kindle rental books on my Kobo (azw files). Tried everything - then read this tutorial. Kindle 1.24 plus epubpor ultimate which decrypted and also converted to epub. Now that's the shizzle!

[reply](https://tools.techidaily.com/epubor/products/) 

Cole

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

07/21/2020 00:32:57

Hi, I have bought all your apps and now they are not longer working, including the latest app that uses the Kindle Cloud Reader. It no longers allow you to download and pin.

 Please HELP.

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:Cole](https://tools.techidaily.com/epubor/products/)

07/21/2020 09:05:14

Thank you for using our software. For downloading kindle cloud reader, you just need to open the book and a downloading progress will show at the bottom right corner. Then just keep this book open until the download finished.   
 If you have no way to download kindle cloud reader books, then kcr converter will not convert them.

 For further assistance, please contact support@epubor.com

[reply](https://tools.techidaily.com/epubor/products/) 

xkyrynn

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

07/28/2020 18:09:47

Hello, is there a way to remove DRM from amazon mobi books right from iPad? I don’t have a computer that I can use to use any of these services. I only use my iPad so I’m curious if there is a way to remove the DRM from a book I purchased on Amazon so that I can read the book on my Apple Books app. Thanks in advance! 

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:xkyrynn](https://tools.techidaily.com/epubor/products/)

07/29/2020 08:51:24

Thank you for asking. We are sorry to inform you that Epubor software only works on windows and Mac platform. Also, if you want to remove drm from kindle books, please download your kindle books via kindle for pc/mac, then use our software to remove DRM.   

[reply](https://tools.techidaily.com/epubor/products/) 

Tarisaande

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

08/14/2020 03:48:10

Thank you. I decided to get a kindle version of a knitting pattern book instead of a hard copy for the portability and wanted to be able to print parts of it. Thank you for pointing out copying it from the kindle is better than using the download and transfer option, because the file formats weren't the same and callibre couldn't read the downloaded version to convert. My PDF is about twice as long as the hard copy of the book and probably won't be printing much of it, but I guess the formatting works better on mobile where I will use it most often anyway. 

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:Tarisaande](https://tools.techidaily.com/epubor/products/)

08/17/2020 08:54:58

Thank you for your comments. Glad to know this can help you.

[reply](https://tools.techidaily.com/epubor/products/) 

vps

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

10/28/2020 20:26:56

great tutorial .. Keep it up.  
 First method worked for me along with kindle 1.17 PC.. Thank you so much.

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor 

[Re:vps](https://tools.techidaily.com/epubor/products/)

10/29/2020 09:29:47

Thank you for your feedback. We are glad to know that. 

[reply](https://tools.techidaily.com/epubor/products/) 

Taylor Francis

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

11/12/2020 06:15:23

Help!!!!

 getting this:

  
 calibre, version 5.4.2  
 ERROR: Unhandled exception: &lt;b&gt;SyntaxError&lt;/b&gt;:invalid syntax (calibre\_plugins.dedrm.\_\_init\_\_, line 167)

 calibre 5.4.2 embedded-python: True is64bit: True  
 macOS-10.15.7-x86\_64-i386-64bit Darwin ('64bit', '')  
 ('Darwin', '19.6.0', 'Darwin Kernel Version 19.6.0: Mon Aug 31 22:12:52 PDT 2020; root:xnu-6153.141.2\~1/RELEASE\_X86\_64')  
 Python 3.8.5  
 OSX: ('10.15.7', ('', '', ''), 'x86\_64')  
 Interface language: None  
 Traceback (most recent call last):  
 File "calibre/gui2/preferences/plugins.py", line 317, in add\_plugin  
 File "calibre/customize/ui.py", line 472, in add\_plugin  
 File "calibre/customize/ui.py", line 61, in load\_plugin  
 File "calibre/customize/zipplugin.py", line 285, in load  
 File "importlib/\_\_init\_\_.py", line 127, in import\_module  
 File "&lt;frozen importlib.\_bootstrap&gt;", line 1014, in \_gcd\_import  
 File "&lt;frozen importlib.\_bootstrap&gt;", line 991, in \_find\_and\_load  
 File "&lt;frozen importlib.\_bootstrap&gt;", line 975, in \_find\_and\_load\_unlocked  
 File "&lt;frozen importlib.\_bootstrap&gt;", line 671, in \_load\_unlocked  
 File "calibre/customize/zipplugin.py", line 177, in exec\_module  
 File "calibre/customize/zipplugin.py", line 173, in get\_code  
 File "calibre\_plugins.dedrm.\_\_init\_\_", line 167  
 print u" v: Copying needed library files from plugin's zip".format(PLUGIN\_NAME, PLUGIN\_VERSION)  
 ^  
 SyntaxError: invalid syntax  

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor 

[Re:Taylor Francis](https://tools.techidaily.com/epubor/products/)

11/12/2020 14:13:57

Here is the solution: <https://www.epubor.com/solutions-to-calibre-dedrm-plugin-not-working.html>

[reply](https://tools.techidaily.com/epubor/products/) 

joe

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

11/17/2020 20:42:58

DeDRM\_Plugin.zip is not a valid plugin. missing \_\_init\_\_.py

[reply](https://tools.techidaily.com/epubor/products/) 

Jonathan Hartley

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

11/18/2020 01:13:03

@joe said:  
 &gt; DeDRM\_Plugin.zip is not a valid plugin. missing \_\_init\_\_.py

 This is strange, because if you open up that zipfile yourself, it does contain an \_\_init\_\_.py.

 This is the exact error message you would get if you had used the wrong zipfile. Are you sure you didn't use the DeDRM tools zipfile by mistake?

[reply](https://tools.techidaily.com/epubor/products/) 

Kel

[Re:Jonathan Hartley](https://tools.techidaily.com/epubor/products/)

03/19/2022 06:34:40

I had the same error when I first tried so I moved only the De\_DRM\_calibre\_plugin file into a new _location_ and clicked on that rather than on the whole zip file.

[reply](https://tools.techidaily.com/epubor/products/) 

Rick Falck

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

12/2/2020 07:27:15

chat is offline so sending here. The deDRM plugin crashes on install:

 calibre, version 5.6.0  
 ERROR: Unhandled exception: &lt;b&gt;SyntaxError&lt;/b&gt;:invalid syntax (calibre\_plugins.dedrm.\_\_init\_\_, line 167)

 calibre 5.6 \[64bit\] embedded-python: True is64bit: True  
 Windows-10-10.0.19041 Windows ('64bit', 'WindowsPE')  
 ('Windows', '10', '10.0.19041')  
 Python 3.8.5  
 Windows: ('10', '10.0.19041', '', 'Multiprocessor Free')  
 Interface language: None  
 Traceback (most recent call last):  
 File "calibre\\gui2\\preferences\\plugins.py", line 317, in add\_plugin  
 File "calibre\\customize\\ui.py", line 472, in add\_plugin  
 File "calibre\\customize\\ui.py", line 61, in load\_plugin  
 File "calibre\\customize\\zipplugin.py", line 293, in load  
 File "importlib\\\_\_init\_\_.py", line 127, in import\_module  
 File "&lt;frozen importlib.\_bootstrap&gt;", line 1014, in \_gcd\_import  
 File "&lt;frozen importlib.\_bootstrap&gt;", line 991, in \_find\_and\_load  
 File "&lt;frozen importlib.\_bootstrap&gt;", line 975, in \_find\_and\_load\_unlocked  
 File "&lt;frozen importlib.\_bootstrap&gt;", line 671, in \_load\_unlocked  
 File "calibre\\customize\\zipplugin.py", line 185, in exec\_module  
 File "calibre\\customize\\zipplugin.py", line 181, in get\_code  
 File "calibre\_plugins.dedrm.\_\_init\_\_", line 167  
 print u" v: Copying needed library files from plugin's zip".format(PLUGIN\_NAME, PLUGIN\_VERSION)  
 ^  
 SyntaxError: invalid syntax

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:Rick Falck](https://tools.techidaily.com/epubor/products/)

12/2/2020 09:08:01

Thank you for your comments. For this error, please follow this guide to get it fixed: https://www.epubor.com/solutions-to-calibre-dedrm-plugin-not-working.html

 Any more problem, please feel free to contact us. Have a nice day.

[reply](https://tools.techidaily.com/epubor/products/) 

debi

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

01/26/2021 12:04:57

You need to stop saying that Calibre will remove the DRM from books. I have followed your instructions and downloaded the plugin and I HAVE NEVER HAD IT WORK - NEVER!!!!!!!!!!

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:debi](https://tools.techidaily.com/epubor/products/)

01/28/2021 10:00:30

Thank you for your comments. Removing ebook drm with calibre drm plugin is a little bit difficult, but it works.   
 If you want something simple, please just use Epubor Ultimate instead which is much simpler and easier.  
 If you have any problem when using epubor ultimate, please feel free to contact us via support@epubor.com  

[reply](https://tools.techidaily.com/epubor/products/) 

doxo

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

07/17/2021 16:31:05

now the kindle version 1.24 is not usable, flickers during registration, tried a lot..no use!

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:doxo](https://tools.techidaily.com/epubor/products/)

07/19/2021 11:24:08

Yes, please download the kindle for PC 1.17 and register it to download kindle books.  
 Sorry for the inconvenience caused.   
 Also, we will update our software to auto downgrade to kindle 1.17.

[reply](https://tools.techidaily.com/epubor/products/) 

Vico

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

01/21/2022 16:53:03

I have kindle and would like to do audio reading programs to read out loud my kindle books. What drm works for Android. Step by step instructions to be able to hear audio would be great. Thanks

[reply](https://tools.techidaily.com/epubor/products/) 

Chuck

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

03/29/2022 04:40:50

I tried to add plugin to Calibre but when I click on open with the zip file I get an error message.   

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:Chuck](https://tools.techidaily.com/epubor/products/)

03/29/2022 09:10:39

What's the error message?Can you please screenshot and send it to us via support@epubor.com? Then we will help you check this issue.  

[reply](https://tools.techidaily.com/epubor/products/) 

mehabr

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

05/6/2022 14:10:03

dont work its virus

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:mehabr](https://tools.techidaily.com/epubor/products/)

05/9/2022 10:22:01

Epubor software is 100% clean and safe.   

[reply](https://tools.techidaily.com/epubor/products/) 

Geopup

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

05/8/2022 18:34:41

Here is the error message :Syntaxerror: invalid syntax (calibre\_plugins.dedrm.\_\_init\_\_, line 167

 calibre, version 5.42.0  
 ERROR: Unhandled exception: &lt;b&gt;SyntaxError&lt;/b&gt;:invalid syntax (calibre\_plugins.dedrm.\_\_init\_\_, line 167)

 calibre 5.42 \[64bit\] embedded-python: True is64bit: True  
 Windows-10-10.0.19041 Windows ('64bit', 'WindowsPE')  
 ('Windows', '10', '10.0.19041')  
 Python 3.8.5  
 Windows: ('10', '10.0.19041', '', 'Multiprocessor Free')  
 Interface language: None  
 Successfully initialized third party plugins: Gather KFX-ZIP (from KFX Input) (1, 48, 0) && Package KFX (from KFX Input) (1, 48, 0) && KFX metadata reader (from KFX Input) (1, 48, 0) && KFX Input (1, 48, 0)  
 Traceback (most recent call last):  
 File "calibre\\gui2\\preferences\\plugins.py", line 326, in add\_plugin  
 File "calibre\\customize\\ui.py", line 476, in add\_plugin  
 File "calibre\\customize\\ui.py", line 64, in load\_plugin  
 File "calibre\\customize\\zipplugin.py", line 292, in load  
 File "importlib\\\_\_init\_\_.py", line 127, in import\_module  
 File "&lt;frozen importlib.\_bootstrap&gt;", line 1014, in \_gcd\_import  
 File "&lt;frozen importlib.\_bootstrap&gt;", line 991, in \_find\_and\_load  
 File "&lt;frozen importlib.\_bootstrap&gt;", line 975, in \_find\_and\_load\_unlocked  
 File "&lt;frozen importlib.\_bootstrap&gt;", line 671, in \_load\_unlocked  
 File "calibre\\customize\\zipplugin.py", line 184, in exec\_module  
 File "calibre\\customize\\zipplugin.py", line 180, in get\_code  
 File "calibre\_plugins.dedrm.\_\_init\_\_", line 167  
 print u" v: Copying needed library files from plugin's zip".format(PLUGIN\_NAME, PLUGIN\_VERSION)  
 ^  
 SyntaxError: invalid syntax

  
[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:Geopup](https://tools.techidaily.com/epubor/products/)

05/9/2022 10:34:09

Thank you for asking. Please follow this guide to fix your problem&gt;&gt; https://www.epubor.com/solutions-to-calibre-dedrm-plugin-not-working.html  
 Have a nice day!

[reply](https://tools.techidaily.com/epubor/products/) 

DanielC

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

07/1/2022 05:49:42

Cant install pycrypto with the current version of python... Calibre version doesnt work... this is all useless info

[reply](https://tools.techidaily.com/epubor/products/) 

DanielC

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

07/1/2022 07:18:36

Cant install pycrypto with the current version of python... Calibre version doesnt work... this is all useless info

[reply](https://tools.techidaily.com/epubor/products/) 

nance

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

07/12/2022 02:51:16

I think the point of all this is to frustrate one enough so that they will pay $24.95 for the Epubor ... joke's on us... pretty trashy marketing strategy... turned me off... I don't need the book.

[reply](https://tools.techidaily.com/epubor/products/) 

Keven Nelson

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

03/8/2023 08:23:30

mISS PAR IN CALL TO 'PRINT'. Did you mead print(...)? Henp!

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:Keven Nelson](https://tools.techidaily.com/epubor/products/)

03/13/2023 16:11:46

Can you please describe your problem more clearly and send them to us via support@epubor.com so that we can help you fix it?

[reply](https://tools.techidaily.com/epubor/products/) 

Larry

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

04/3/2023 06:18:02

Have kindle for pc version 1.17\. Can’t download books bought from amazon. Amazon wants to upgrade to version 1.3x. I have Epubor ultimate.how do I remove DRM from purchased books, please? Calibre drm plug-in doesn’t work!

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:Larry](https://tools.techidaily.com/epubor/products/)

04/10/2023 15:12:37

For the ebooks published in 2023, here is still another way to remove drm from this kind of kindle book if you have any Kindle eink device registered with your Amazon account. Please download the Kindle books via "Download and transfer via usb" and then remove kindle drm with Epubor Ultimate. Here is the detailed guide: <https://www.epubor.com/how-to-remove-drm-from-kindle-kfx-ebooks.html#meth4>

[reply](https://tools.techidaily.com/epubor/products/) 

DLT

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

06/29/2023 02:56:48

I have kindle for PC and was informed that I must updat to a new kindel for PC inorder to download and read a new book I had bought.  
 The version was 1.40.65535, from that point on I was unable to remove the new DRM. I am using epulor ulitimate. I went back to Kindle for PC 1.32 and again was told I could not download the book without upgrading to the new version. I did download the book to my Kindle 3g/wifi without any problem.  
 I found I could open my kindle documents file and locate the recently downloaded file. Epublor was able to decrypt AWZ3 file found in the documents and was able to convert to a Mobi.  
 This works just fine for me now, but would like to be able to do it from my kindle for PC.

[reply](https://tools.techidaily.com/epubor/products/) 

Barry 

[Re:3 Ways to Remove DRM from Kindle Books](https://tools.techidaily.com/epubor/products/)

10/24/2023 06:00:54

Could have been a great article if you'd included solutions for people like me that run linux (fedora).

[reply](https://tools.techidaily.com/epubor/products/) 

Epubor

[Re:Barry](https://tools.techidaily.com/epubor/products/)

10/24/2023 11:11:20

Hello, thanks for your feedback.

 Our software can only support Windows or MacOS. But we will consider your suggestions and discuss it with our developers in the future.

 Any other questions or concerns, please feel free to contact us via support@epubor.com.

 Best regards,  
 Epubor Team

[reply](https://tools.techidaily.com/epubor/products/) 

Leave a comment

| Rating |  |
| ------ |  |

| YourName | \*  1 to 50 chars |
| -------- | ----------------- |

| email | Internet Email |
| ----- | -------------- |

| Comments | UBB Editor |
| -------- | ---------- |

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
