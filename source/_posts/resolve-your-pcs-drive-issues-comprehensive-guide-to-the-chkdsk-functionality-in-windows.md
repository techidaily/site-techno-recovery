---
title: "Resolve Your PC's Drive Issues: Comprehensive Guide to the Chkdsk Functionality in Windows"
date: 2024-08-26T06:01:46.482Z
updated: 2024-08-27T06:01:46.482Z
categories:
  - BestProducts
description: "This Article Describes Resolve Your PC's Drive Issues: Comprehensive Guide to the Chkdsk Functionality in Windows"
excerpt: "This Article Describes Resolve Your PC's Drive Issues: Comprehensive Guide to the Chkdsk Functionality in Windows"
thumbnail: https://thmb.techidaily.com/d47941553c96756e0922bd70e1fb76549037277932507e29a378053d0b9798db.jpg
---

## Resolve Your PC's Drive Issues: Comprehensive Guide to the Chkdsk Functionality in Windows

Close 

 Short for "check disk," the chkdsk command is a Command Prompt command used to check a specified disk and repair or recover data on the drive if necessary.

 Chkdsk also marks any damaged or malfunctioning sectors on the hard drive or disk as "bad" and recovers any information still intact.

##  Chkdsk Command Availability 

 The chkdsk command is available via Command Prompt in Windows 11, Windows 10, Windows 8, Windows 7, Windows Vista, and Windows XP operating systems.

 The chkdsk command is also available in[ Advanced Startup Options](https://www.lifewire.com/advanced-startup-options-2625805) and[ System Recovery Options](https://www.lifewire.com/system-recovery-options-2626021) . It works from within the Recovery Console in Windows 2000 and Windows XP. Chkdsk is a DOS Command, too, available in most versions of MS-DOS.

[  13 Best Free Hard Drive Testing Tools (July 2024) ](https://www.lifewire.com/free-hard-drive-testing-programs-2626183) 

 The availability of certain chkdsk command switches and other chkdsk command[ syntax](https://www.lifewire.com/what-is-syntax-2626014) might differ from operating system to operating system.

## Chkdsk Command Syntax 

**chkdsk** \[_volume:_ \] \[**/F** \] \[**/V** \] \[**/R** \] \[**/X** \] \[**/I** \] \[**/C** \] \[**/L** :_size_ \] \[**/perf** \] \[**/scan** \] \[**/?** \]

[ How to Read Command Syntax ](https://www.lifewire.com/how-to-read-command-syntax-2618082) 

| Chkdsk Command Options |                                                                                                                                                                                                                                                                                                                                                                             |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Option**             | **Explanation**                                                                                                                                                                                                                                                                                                                                                             |
| _volume:_              | This is the drive letter of the[ partition](https://www.lifewire.com/what-is-a-partition-2625958) for which you want to check for errors.                                                                                                                                                                                                                                   |
| **/F**                 | This chkdsk command option will fix any errors found on the disk.                                                                                                                                                                                                                                                                                                           |
| **/V**                 | Use this chkdsk option on a[ FAT or FAT32](https://www.lifewire.com/what-is-file-allocation-table-fat-2625877) volume to show the full path and name of every file on the disk. If used on an[ NTFS](https://www.lifewire.com/ntfs-file-system-2625948) volume, it will show cleanup messages (if there are any).                                                           |
| **/R**                 | This option tells chkdsk to locate bad sectors and recover any readable information from them. This option implies**/F** when**/scan** is not specified.                                                                                                                                                                                                                    |
| **/X**                 | This command option implies**/F** and will force a dismount of the volume if necessary.                                                                                                                                                                                                                                                                                     |
| **/I**                 | This option will perform a less vigorous chkdsk command by instructing the command to run faster by skipping over certain regular checks.                                                                                                                                                                                                                                   |
| **/C**                 | Same as**/I** but skips over cycles within the folder structure to reduce the amount of time that the chkdsk command runs.                                                                                                                                                                                                                                                  |
| **/L:** _size_         | Use this chkdsk command option to change the size (in KB) of the log file. The default log file size for chkdsk is 65536 KB; you can check the current log file size by executing**/L** without the "size" option.                                                                                                                                                          |
| **/perf**              | This option allows chkdsk to run faster by using more[ system resources](https://www.lifewire.com/what-is-a-system-resource-2626016) . It has to be used with**/scan** .                                                                                                                                                                                                    |
| **/scan**              | This chkdsk option runs an online scan on an NTFS volume but does not try to repair it. Here, "online" means that the volume does not need to be dismounted, but can instead remain online/active. This is true for both internal and[ external hard drives](https://www.lifewire.com/what-is-an-external-drive-2625867) ; you can continue using them throughout the scan. |
| **/spotfix**           | This chkdsk option dismounts the volume only briefly to fix issues that were sent to the log file.                                                                                                                                                                                                                                                                          |
| **/?**                 | Use the[ help switch](https://www.lifewire.com/help-switch-2625896) with the chkdsk command to show detailed help about the commands listed above and other options you can use with chkdsk.                                                                                                                                                                                |

 Other less commonly used chkdsk command switches exist too, like**/B** to re-evaluate bad clusters on the volume,**/forceofflinefix** which runs an online scan (a scan while the volume is active) but then forces the repair to run offline (once the volume has been dismounted),**/offlinescanandfix** which runs an offline chkdsk scan and then fixes any problems that were found, and others that you can read more about through the**/?** switch.

 The**/offlinescanandfix** option is the same as**/F** except that it's only allowed on NTFS volumes.

 If you're using the chkdsk command from the Recovery Console in older versions of Windows, use**/p** in place of**/F** above to instruct chkdsk to perform an extensive check and[ repair errors on the hard drive](https://www.lifewire.com/check-and-fix-hard-drive-errors-3506860) .

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Chkdsk Command Examples 

 Here are some of the different ways you might use the chkdsk command:

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Read-Only Mode 


 `chkdsk`

 Since no drive or additional options were entered in the above example, chkdsk simply runs in read-only mode.

![The CHKDSK command in read-only mode](https://www.lifewire.com/thmb/0p8t7Npad9Bk-vVhkXAlMhm1l-w=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/chkdsk-read-only-mode-45b119cdfaea4c89b2c716c32269497c.png) 

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If problems were found when running this simple chkdsk command, you'll want to make sure to use the example from below to correct any issues.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Pre-Boot Scan & Fix 


 `chkdsk c: /r`

 In this example, the chkdsk command is used to perform an extensive check of the _C:_ drive to correct errors and locate recovery information from bad sectors. This is best used when running chkdsk from outside of Windows, like from a recovery disc where you need to specify which drive to scan.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
### Offline Repair 


 ` chkdsk c: /scan /forceofflinefix`

 This chkdsk command runs an _online scan_ on the _C:_ volume so that you don't have to dismount the volume to run the test, but instead of fixing any issues while the volume is active, the problems are sent to a queue that will be resolved in an offline repair.

### Fast Scan & Fix 


 ` chkdsk c: /r /scan /perf `

 In this example, chkdsk will fix problems on the _C:_ drive while you're using it and will use as many system resources as allowed so that it will run as quickly as possible.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
## Chkdsk Related Commands 

 Chkdsk is often used with many other Command Prompt commands and [ Recovery Console commands](https://www.lifewire.com/recovery-console-2625991) . It's similar to the scandisk command used to check a hard drive or floppy disk for errors in Windows 98 and MS-DOS.

[  The Complete List of Command Prompt (CMD) Commands ](https://www.lifewire.com/list-of-command-prompt-commands-4092302) 

Was this page helpful?

Thanks for letting us know!

 Get the Latest Tech News Delivered Every Day

[ Subscribe ](https://www.lifewire.com/#) 

Tell us why!

 Other  Not enough details  Hard to understand 

 Submit 

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


