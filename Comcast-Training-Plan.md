# Training Plan
### Contents
|SL No       | Contents           |
| :---       | :---               | 
| 1 | [Broadcast fundamentals](#broadcast-fundamentals)|    
| 2 | [IPTV-AAMP](#iptv-aamp)      | 
| 3 | [RDKV](#rdkv)           | 
| 4 | [C CPP and Linux](#c-cpp-and-linux)| 
| 5 | [OTT_APP_QA](#ott_app_qa)                  |
| 6 | [RDK Integration Matrix team](#rdk-integration-matrix-team)|  
| 7 | [New Device Integration](#new-device-integration)   |    
| 8 | [WPE Browser Training  Plan](#wpe-browser-training-plan) |    
| 9 | [DEV QA](#dev-qa)           |    
  

## Broadcast fundamentals


Master Link:     
https://tataelxsi.sharepoint.com/:w:/r/sites/RDK-Training/_layouts/15/Doc.aspx?sourcedoc=%7B58B368CE-BE43-46DB-8059-415A63008FC9%7D&file=Broadcast%20Basics%20-%20Video%20Links.docx&action=default&mobileredirect=true&cid=d70893d5-70d6-4e89-8e66-fc4f8016d7a7



|Sl No. | Topic | Link | Duration |
|----------|-------|------|----------|
|1| Broadcast Fundamentals| https://web.microsoftstream.com/video/ef8c079b-192e-4f77-9aa9-d855f9bd1390 | 01:55:40|
|2 | Broadcast Fundamentals| https://tataelxsi.sharepoint.com/:b:/s/RDK-Training/EXgzjvQXCmhKi_tZSvRdK2YBUCopgDeZlRqLde_pgH3HSw?e=fmftOv | Document|
|3| Transmission Overview – Part1 | https://web.microsoftstream.com/video/ef8c079b-192e-4f77-9aa9-d855f9bd1390  | 01:55:40|
|4| Transmission Overview – Part2 | https://web.microsoftstream.com/video/f5ed9a63-620c-4e2e-bd53-c6c0ae2f667d  | 01:35:48 |
|5 | Transmission Overview -Doc | https://tataelxsi.sharepoint.com/:b:/s/RDK-Training/ESYIhGkYV0JPtWtNNNZgnOMBz_L8sZIxSo-L73hqdGSbtw?e=DiWVvo   | Document|
|6| Comcast Devices overview | https://web.microsoftstream.com/video/dbf247a2-8c92-4296-ac1a-e2c807005cf5 | 01:12:19|
|7| Code download using rdk portal and mock CDL | Do | |
|8| ssh to devices | Do | |
|9| Build types (Sprint, Stable2 and release builds)| Do | |



## IPTV-AAMP
|SL No. |Topic   |Owner  |Link       | Duration (Days)  | Video Availbility|
|-------|--------|-------|-----------|-----------|-------|
| 1| Basics and History of AAMP | AKHIL BABU | https://etwiki.sys.comcast.net/pages/viewpage.action?pageId=363616203 |  1 | Yes |
|2| HLS Overview | NANDANA N RAJ | https://web.microsoftstream.com/video/59cf03aa-7827-4a26-8498-498263f3f6a4 | 1 | Yes |
|3 | MPEG Dash Overview | AKHIL BABU | https://web.microsoftstream.com/video/8e98a567-798d-47ab-bf10-13f1e284d6f2 | 1| Yes|
|4 | Playback Codeflow of HLS and MPEG-DASH | NANDANA N RAJ | https://web.microsoftstream.com/video/e4b703b8-6044-43f4-9cd3-83cea248bd04 | 1| Yes |
|5 | DASH - DRM workflow  in AAMP | 1.AKHIL BABU  2.ANURAG K| 1.https://web.microsoftstream.com/video/16bf223d-292c-4acf-a60b-6d2c627483b1  2.https://web.microsoftstream.com/video/b6ed151b-72b8-45e4-a6da-3c8407a3803b | 1| Yes |
|6 | HLS – DRM workflow in AAMP | NANDANA N RAJ | https://web.microsoftstream.com/video/40d4895b-56a0-4e95-87d7-1d5f37e58102 | 2| NO |
|7 | MP4 HLS – DRM workflow in AAMP | | | | |
|8| FOG Technologies and Code Walk through |AKHIL BABU  |https://web.microsoftstream.com/video/128cb698-3d0b-4426-9608-be5487af4975 | 2 | Yes |
|9| Fog DASH TSB generation |1.AKHIL BABU 2.ANURAG K  3.ANURAG K| 1. https://web.microsoftstream.com/video/937f2cc9-2fdd-4f94-a757-5d8c55bcfbdd   2.https://web.microsoftstream.com/video/b2e6f5f7-9703-4f55-982c-a99352ffe9b4 3.https://web.microsoftstream.com/video/35dfe22d-d5c5-4b0d-9b1e-b79465c21430 | 1 | Yes |
|10| JS Binding and Code Walk through | NANDANA N RAJ | https://web.microsoftstream.com/video/cf03855d-7aa5-4189-b831-b2e1385cd546 | 1 | Yes |
|11| ABR technologies and Code Walk through | ANURAG K| https://web.microsoftstream.com/video/cc7282d5-5cd5-4e75-a97e-737e35975204 | 1| Yes|
|12| UVE Reference Player, its usage , and Code walk | NANDANA N RAJ| https://web.microsoftstream.com/video/cf03855d-7aa5-4189-b831-b2e1385cd546 | 2 | Yes|
|13| DAI technologies in DASH , CDAI and Server Side DAI | ANURAG K| CDAI IN DASH  : https://web.microsoftstream.com/video/1e387df7-e39f-4f6e-be37-4f144762c304 | 3 | Yes |
|14|DAI technologies in HLS, and Discontinuity handling mechanism in HLS | | | | NO|
|15| Aamp gstreamer components and code walk through | JOTSNA | https://web.microsoftstream.com/video/d26feee6-11ec-4f84-8709-527a2d6c6a00 | 2 | Yes |
|16| Aamp-gst-plugin module and code walk through | | | 1| No|
|17| Building aamp for Linux/target and working with aamp-cli | | Only documents needed | 1 | No|
|18 | Building Fog and working with fogcli | | Only documents needed | 1| No |
|19 | Crash Analysis using Crashportal, Generate Core dump manually , Generate stack trace manually from minidump   | VINISH KB/PAUL | 1.https://web.microsoftstream.com/video/fa9f12f6-1a22-43f8-bbb3-da8065294894 2.https://web.microsoftstream.com/video/6c7db512-74ef-4cda-8c9d-a0ba66f7e1e2  3.https://web.microsoftstream.com/video/616ea5c3-c723-4097-acb4-d982f6a00678 4.https://etwiki.sys.comcast.net/display/CPE/Producing+stack+traces+from+google+breakpad+minidump | 2| Yes|
|20| Copy the modified aamp libs to box, run using aamp-cli and xre-receiver, and get the log file from box to the pc. | | Only documents needed | 1| No |
|21|Build full image with Aamp changes using Jenkins, Aamp gerrit update process and Aamp JIRA process  | |Only documents needed | 1| No |
|22| Quick triaging tips from the logs for aamp issues| |Only documents needed | 1| No |
|23|Accessing CATs box running tests, Accessing sling boxes, and fling url or 3rd part apps to the box | |Only documents needed | 1| No |
|24| Aamp coding standard | General | https://etwiki.sys.comcast.net/display/RDKV/AAMP+Coding+Guidelines | 1| Yes|



## RDKV
|Sl No. | Topic | Link | Duration  (Days)|
|----------|-------|------|----------|
|1|RDKV- Overview | https://tataelxsi.sharepoint.com/:w:/r/sites/RDK-Training/_layouts/15/doc2.aspx?sourcedoc=%7BFB5A2711-9F9C-4906-9F1B-9CBCA39E7287%7D&file=RDK-V%20Training%20Video%20Links.docx&action=default&mobileredirect=true&DefaultItemOpen=1&cid=e2608a20-22b5-4ade-b0d9-e3a4d695cb84 | 1 |
|2|1. RDKV- Concepts brush up 2.Breief report on RDK 3.History, Why RDK, Advantages and disadvantages, How RDK is maintained, How adopting RDK benefits for customer and end user 4.Objective: To make sure the engineers understand the relevence of the technology | https://tataelxsi.sharepoint.com/_forms/spfxsinglesignon.aspx# | 1 |
|3| IARM Module Introduction | https://tataelxsi.sharepoint.com/sites/RDK-Training/RDK_V%20Training%20April%202018/Forms/AllItems.aspx | 1| 
|4| Create HelloWorld Modules and communicate between them using IARM ||
|5| Introduction to Device settings | https://tataelxsi.sharepoint.com/sites/RDK-Training/RDK_V%20Training%20April%202018/Forms/AllItems.aspx|1|
|6| 1.Understanding different modules in devicesettings 2.CC specification and Module architecture 3.CEC module 4.CEC daemon code walk through in RDK wiki| 2.https://tataelxsi.sharepoint.com/sites/RDK-Training/RDK_V%20Training%20April%202018/Forms/AllItems.aspx 3.https://tataelxsi.sharepoint.com/sites/RDK-Training/RDK_V%20Training%20April%202018/Forms/AllItems.aspx 4.https://tataelxsi.sharepoint.com/sites/RDK-Training/RDK_V%20Training%20April%202018/Forms/AllItems.aspx|7|
|7| Device settings Code Walk through |https://tataelxsi.sharepoint.com/sites/RDK-Training/RDK_V%20Training%20April%202018/Forms/AllItems.aspx|3|
|8|Closed caption  code walkthrough | https://tataelxsi.sharepoint.com/sites/RDK-Training/RDK_V%20Training%20April%202018/Forms/AllItems.aspx|2|
|9| TR69 introduction |https://tataelxsi.sharepoint.com/sites/RDK-Training/RDK_V%20Training%20April%202018/Forms/AllItems.aspx| 1|
|10| TR69 Module Architecture | https://tataelxsi.sharepoint.com/sites/RDK-Training/RDK_V%20Training%20April%202018/Forms/AllItems.aspx| 2|
|11| WebPa Module architecture |https://tataelxsi.sharepoint.com/sites/RDK-Training/RDK_V%20Training%20April%202018/Forms/AllItems.aspx|1|
|12|Sample TR69 parameter implemetnation, Set and get using Tr69 and WebPa || 2 |
|13| Thunder proxy introduction |https://tataelxsi.sharepoint.com/sites/RDK-Training/RDK_V%20Training%20April%202018/Forms/AllItems.aspx|1|
|14| Thunder plugin for device settings - user story and code walk through ||3|
|15| SkyQ and XiOne platform introduction ||1|
|16| __tata_v__ ticket analysis | |5|
|17| 1.Log Analysis and triaging hands on 2.Reciever.log 3.uimanager.log 4.splunk query etc.| etwiki access availability. (Ticket and logs can be exported and provided ) | 3| 


## C CPP and Linux
|Sl No. | Topic | Link | Duration|
|----------|-------|------|----------|
|1| Multi-threaded programming – (creating and managing threads using pthread API, understanding race conditions and deadlocks, thread-safety using mutexes, semaphore, conditional variables, std::thread class in C++, std::mutex, std::lock_guard) |1.https://www.cs.cmu.edu/afs/cs/academic/class/15492-f07/www/pthreads.html 2.https://www.cplusplus.com/reference/mutex/mutex/3.https://www.cplusplus.com/reference/thread/thread/ 4.https://www.geeksforgeeks.org/condition-wait-signal-multi-threading/ 5.https://linuxhint.com/posix-semaphores-with-c-programming/ 6.https://en.wikipedia.org/wiki/Race_condition#In_software 7.https://www.bogotobogo.com/cplusplus/multithreaded4_cplusplus11B.php | 3days|
|2| C++ basics (feel free to skip known topics) | https://learningcentral.tataelxsi.co.in/local/catalog/coursedetails.php?id=778|4 days |
|3|C++ intermediate-advanced level (STL, range-based for loop, lambda functions, template classes and functions, smart pointers, std::async, RAII) | https://learningcentral.tataelxsi.co.in/local/catalog/coursedetails.php?id=9523 | 5 h 18 m Hands-on : 11 h 39 m |
|4| Design Patterns | https://learningcentral.tataelxsi.co.in/local/catalog/coursedetails.php?id=646 |Video - 5 h 40 m Hands On -13 h  12 m  |
|5| Linux command line fundamentals|https://learningcentral.tataelxsi.co.in/local/catalog/coursedetails.php?id=9168| 2h 18m|
|6| Linux system programming|https://learningcentral.tataelxsi.co.in/local/catalog/coursedetails.php?id=26|  Video : 6 h | Hands-on : 13h 58 m |
|7| Yocto | https://learningcentral.tataelxsi.co.in/local/catalog/coursedetails.php?id=576 | Video : 2 h | Hands-on : 4 h 39 m |
|8| GIT (how to clone, stage changes, commit changes, amend commits, branching, cherry-picking changes between branches, using reset to undo things) | Quick start videos available here:https://git-scm.com/videos More info available in https://git-scm.com/doc. Also See lerning central courses: https://learningcentral.tataelxsi.co.in/local/catalog/coursedetails.php?id=606| 3h|


## OTT_APP_QA

|Sl No. | Topic | Link | Duration|
|----------|-------|------|----------|
|1|1.Project Overview - General 2.STB boxes and OTT Apps in the box| https://tataelxsi.sharepoint.com/:v:/r/sites/TATA_ELXSI/EPD/BBU/tecomcasttechcentre/OTTAppQA/Shared%20Documents/40%20Reference/KT%20videos/RAMP%20UP%20-%20DAY1-20220413_103611-Meeting%20Recording%20(1).mp4?csf=1&web=1&e=l2cput | 55 m|
|2| Different Builds and Methods to Flash the devices(using RDK portal and Jenkins) | https://tataelxsi.sharepoint.com/:v:/r/sites/TATA_ELXSI/EPD/BBU/tecomcasttechcentre/OTTAppQA/Shared%20Documents/40%20Reference/KT%20videos/Different%20Builds%20and%20Methods%20to%20Flash%20the%20devices%20%20(using%20RDK%20portal%20and%20Jenkins)-20220414_115055-Meeting%20Recording.mp4?csf=1&web=1&e=7YMI3A | 1h 30m|
|3| Tools used in the project.[Example: ibis etc.] |https://tataelxsi.sharepoint.com/:v:/r/sites/TATA_ELXSI/EPD/BBU/tecomcasttechcentre/OTTAppQA/Shared%20Documents/40%20Reference/KT%20videos/Tools%20used%20in%20the%20project.%5BExample_%20ibis%20etc.%5D-20220418_153547-Meeting%20Recording.mp4?csf=1&web=1&e=rBSUR6 | 1h|
|4| Tools used in the project.[Example: ibis etc.]|https://tataelxsi.sharepoint.com/:v:/r/sites/TATA_ELXSI/EPD/BBU/tecomcasttechcentre/OTTAppQA/Shared%20Documents/40%20Reference/KT%20videos/Tools%20used%20in%20the%20project.%5BExample_%20ibis%20etc.%5D-20220419_150833-Meeting%20Recording.mp4?csf=1&web=1&e=XRMnkv | 44m|
|5| Manual App tsting using test cases -(example CBS App) | Video 1 : https://tataelxsi.sharepoint.com/:v:/r/sites/TATA_ELXSI/EPD/BBU/tecomcasttechcentre/OTTAppQA/Shared%20Documents/40%20Reference/KT%20videos/OnBoarding_%20Ramp%20Up%20OTT%20app%20testing-20220420_150752-Meeting%20Recording.mp4?csf=1&web=1&e=WvRAxC Video 2: https://tataelxsi.sharepoint.com/:v:/r/sites/TATA_ELXSI/EPD/BBU/tecomcasttechcentre/OTTAppQA/Shared%20Documents/40%20Reference/KT%20videos/OnBoarding_%20Ramp%20Up%20OTT%20app%20testing-20220420_155958-Meeting%20Recording.mp4?csf=1&web=1&e=t4g0fh | Video1 : 47 m Video2 : 40 m|
|6|Jira basics - Project specific | https://tataelxsi.sharepoint.com/:v:/r/sites/TATA_ELXSI/EPD/BBU/tecomcasttechcentre/OTTAppQA/Shared%20Documents/40%20Reference/KT%20videos/Jira%20basics%20-%20Project%20specific-20220427_123616-Meeting%20Recording.mp4?csf=1&web=1&e=9mBqwG| 35 m|
|7| Automation Testing (using WTH tool, Scripts, frameworks,  Github etc)| https://tataelxsi.sharepoint.com/:v:/r/sites/TATA_ELXSI/EPD/BBU/tecomcasttechcentre/OTTAppQA/Shared%20Documents/40%20Reference/KT%20videos/WTH%20tool,%20scripts%20,%20framework%20and%20Github-20220421_151625-Meeting%20Recording.mp4?csf=1&web=1&e=Y1Zhb1 | 1h 42min|
|8|Pre Certification testing - (Cobalt youtube, , Netflix NTS )| ||


## RDK Integration-Matrix team
|Sl No. | Topic | Description| Link | Duration|
|----------|-------|------|----------|--------|
|1| Yocto Build Framwork| Yocto is used for building RDK images. Awareness of yocto, different meta layers are required. Should know about manifest.xml, device specific confs and inc files, generic meta layers, SOC and OEM layers and different build systems like automake, makefile, cmake etc. Team is responsible for good health of the build. Any build breakage is a high priority issue and has to be fixed on priority. Yocto migration/opensource component version migration will come into Scott's bucket. | | |
|2| Generic awareness of RDKB and RDKV software stack | Knowledge about RDK-V and RDK-B is a must. Matrix team will have to work on new devices and platforms both in video and broadband arena. Team is responsible for the setting up builds, device bring up, integrating all the RDK components as per the device specification.|||
|3| Generic RDK Features | We have to work on Generic RDK features like reverse ssh, log upload and rotation, telemetry, RFC, coredump/minidump upload, etc. Integration and configuration of generic features on new platforms will come to Scott's team. | | |
|4| Networking Concepts | Should be aware of basic networking concepts like DHCP, DNS, different networking interfaces, iptables, routing tables, IPV4 and IPV6. It will help while working on RDK-B platforms and also on the bugs related to networking on video platforms. | | |
|5| Systemd Services | Need to get experience on systemd services, bootup sequence, dependency tree and different systemd configurations. | | |
|6| Webpa/Parodus, TR181 parameters| Awareness about webpa functionalities, TR181 parameters to get/set different device configurations. Need to debug issues on getting and setting values.| | |
|7| Xconf and Firmware upgrade| Device initiated and user initiated firmware upgrades are there in the device to upgrade firmwares on the go via webpa commands(RDK Portal) and xconf. It is good to know how xconf works for image upgrade, RFC and telemetry and different configs involved.| https://etwiki.sys.comcast.net/display/CPE/RDK+Firmware+Upgrade+API+Informations | ||
|8| Maintenance Manager| Maintenance manager is a new component introduced to RDK-V in Platco and xone platforms. An idea about its architecture will be good for debug. | https://etwiki.sys.comcast.net/display/RDKAR/RDK+Maintenance+Activities | | |
|9| JIRA workflow and understanding of different branches |Need to know about JIRA workflow, various branches used in the project and the process followed for a bug or a task. JIRA is usually used for bug reporting allocating tasks to team members.||| 
|10|Security Vulnerabilities |Team has to fix security vulnerabilities as directed by the security team which often be integrating  patches on opensource components, blocking or adding checks to different ports, changing versions of components and making it compliant with the stack. During bring up of new platforms, we need to make sure correct certificates are installed for the device for communicating with the server.| | |
|11|GIT and Gerrit|Should know about setting up git and different commands used in git. Should be aware of the process followed in gerrit commits|Video 1:https://web.microsoftstream.com/video/2c3e98f2-8d7a-4bdd-8dd3-063d76b0b803  Video2 :https://web.microsoftstream.com/video/915f559e-6ed1-4a3a-a807-f1b1b1ce4574| Video 1: 1hrs 17mins Video 2: 2h 31m|


## New Device Integration

|Sl No. | Topic | Link | Duration|
|----------|-------|------|----------|
|1| Comacast Device details | https://web.microsoftstream.com/video/dbf247a2-8c92-4296-ac1a-e2c807005cf5 | 1hrs 12mins|
|2| Yocto | https://web.microsoftstream.com/video/1d95944e-06ae-4696-9d88-accb62fd7883 | 1hrs 37mins|
|3| Typical device integration use cases| https://tataelxsi-my.sharepoint.com/:v:/g/personal/sudeeprk_tataelxsi_co_in/ERCvg-KN25lFp_Kzytj-BAkBfQDkI80cNPqeT-FrvbypIQ | 47mins 14sec|
|4| Keeping things in check -regarding latest changes| https://tataelxsi-my.sharepoint.com/:v:/g/personal/sudeeprk_tataelxsi_co_in/ESYFQMig-IBMlx9CNI0lPVcByQYCR1lEbWVywc0oAc9XcA | 49mins 14secs|
|5|An overview of RDKV infrastructure and modules|  https://web.microsoftstream.com/video/dbf247a2-8c92-4296-ac1a-e2c807005cf5 | 1hrs 12mins|
|6|Git/Gerrit Basics|Video 1: https://web.microsoftstream.com/video/915f559e-6ed1-4a3a-a807-f1b1b1ce4574 Video 2:https://web.microsoftstream.com/video/915f559e-6ed1-4a3a-a807-f1b1b1ce4574| Video 1: 1hrs 17mins Video 2: 2hrs 31mins 34secs|
|7| RDK refrence platforms, SoC, OEM Layer philosophy|   https://wiki.rdkcentral.com/courses/playcourse.action?course=93914662&capsule=1||
|8| Webkit understanding| https://web.microsoftstream.com/video/db4d4117-3e0e-4dbb-b8b1-6318a223fecf | 2hrs 18mins |
|9|  RDK architecture and TDK introduction| https://web.microsoftstream.com/video/48dc5493-5490-4bc2-b70c-d58ad53b14c0?list=studio | 1hrs 48mins 58 secs|
|10|  Gstreamer in RDK | https://wiki.rdkcentral.com/courses/playcourse.action?course=95618802&capsule=2 | 15min|
|11|Service manager and device setting | https://wiki.rdkcentral.com/courses/playcourse.action?course=87984778&capsule=1  | 21mins 58secs|
|12|IARM | https://wiki.rdkcentral.com/courses/playcourse.action?course=87984764&capsule=1 | 50 mins|
|13| Xconf training | https://wiki.rdkcentral.com/courses/playcourse.action?course=157321131&capsule=1 | 58mins 48 secs|
|14 | RDK Shell overview| https://wiki.rdkcentral.com/courses/playcourse.action?course=118620400&capsule=1| 53mins 30sec|
|15|Gstreamer cheat sheet | https://github.com/matthew1000/gstreamer-cheat-sheet | 1day |
|16|ffmpeg tutorial| http://dranger.com/ffmpeg/ffmpegtutorial_all.html | 2days|


## WPE Browser Training  Plan				
			
|Sl No. |Topic | Link | Duration|
|-------|----------|-----|------|
|1||https://etwiki.sys.comcast.net/pages/viewpage.action?spaceKey=CPE&title=Browser+Development	||
|2||https://etwiki.sys.comcast.net/pages/viewpage.action?pageId=332160295||
|3||https://etwiki.sys.comcast.net/pages/viewpage.action?spaceKey=RDKV&title=WPE ||
|4||https://etwiki.sys.comcast.net/display/CPE/Webkit+Topics||
|5||https://web.microsoftstream.com/video/db4d4117-3e0e-4dbb-b8b1-6318a223fecf||
|6||https://web.microsoftstream.com/video/db4d4117-3e0e-4dbb-b8b1-6318a223fecf	||
|7||https://tataelxsi-my.sharepoint.com/:v:/g/personal/matta_n_tataelxsi_co_in/Ed-VaF_EzhhHktFX370hhi4BYocwwESWps62vhgQgsvYug ||	
|8|Materials: | https://wiki.rdkcentral.com/display/RDK/WPE	||
|9|Materials:|https://github.com/rdkcentral/Thunder||
|10|Materials:|	https://tataelxsi.sharepoint.com/:p:/s/RDK-Training/Ebn9l-88A4dEsR-PERXph0UBwLl1xSxKZsLSS5KVXMLHzA?e=ocaQT4 ||
|11|Materials:|https://web.microsoftstream.com/video/db4d4117-3e0e-4dbb-b8b1-6318a223fecf	||
|12|Materials:| https://tataelxsi-my.sharepoint.com/:v:/g/personal/matta_n_tataelxsi_co_in/Ed-VaF_EzhhHktFX370hhi4BYocwwESWps62vhgQgsvYug||
|13|Materials:|	https://wiki.rdkcentral.com/display/RDK/WPE	||
|14|Materials:|https://github.com/rdkcentral/Thunder||
|15|Materials:|https://tataelxsi.sharepoint.com/:p:/s/RDK-Training/Ebn9l-88A4dEsR-PERXph0UBwLl1xSxKZsLSS5KVXMLHzA?e=ocaQT4 ||

## DEV QA

|Sl No. |Topic | Link | Duration|
|-------|----------|-----|------|				
|1|Gateway devices, MoCA client devices, Wi-Fi/Ethernet devices, Sky devices, Platco TV |https://web.microsoftstream.com/video/dbf247a2-8c92-4296-ac1a-e2c807005cf5||
|2|code download using rdk portal and mock CDL|Do||
|3|ssh to devices|Do||
|4|how to create tickets and attach logs to tickets|Do||
|5|Jira ticket flow |Do||
|6|Build types (Sprint, Stable2 and release builds)|Do||
|7|Review couple of features tickets and bug tickets for understanding…how they validated and approved by RM|Do||
|8|VBN builds advantages(ex: add devices to CDL exclusion list, pointing to different XRE server, etc..)|Do||
|9|About XRE|https://etwiki.sys.comcast.net/pages/viewpage.action?spaceKey=STBDRM&title=Sprint+Management ,https://etwiki.sys.comcast.net/display/CPE/CPE+RDKV+Release+Management ||
|10|Basic linux commands | https://www.crio.do/blog/20-basic-linux-commands/ ,https://www.hostinger.in/tutorials/linux-commands ||
|11|Linux command line fundamentals | https://learningcentral.tataelxsi.co.in/local/catalog/coursedetails.php?id=9168||






























