Android Automation Tools
==========================

I like to automate stuff that I use very often in computers, phones and daily life. Sometimes, I automate to make a routine convenient. Here are some of the tools that I have developed using [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=en), [Autoapps](https://play.google.com/store/apps/details?id=com.joaomgcd.autoappshub&hl=en), [IFTTT](ifttt.com)       


1. Definitions from Merriam Webster and Collins using Google Assistant
------------
The tool gives better and comprehensive definitions of English words from multiple dictionaries ([Collins](https://www.collinsdictionary.com/), [Merriam-Webster](https://www.merriam-webster.com/)) using [Google Assistant](https://play.google.com/store/apps/details?id=com.google.android.apps.googleassistant&hl=en). I developed this tool during GRE exam preparation for obvious reasons. This is built on top of an earlier version which I developed to get an intuitive word's definitions from my favorite dictionary (Collins Advanced Learner's Dictionary) while reading magazines (Reader's Digest, National Geographic, Creative Gaga etc). All I had to do was to dictate right commands to Google Assistant.  Here's is a demo:

![Definitions from Merriam Webster and Collins using Google Assistant](https://img.youtube.com/vi/6H0bmf6u0gU/0.jpg)](https://www.youtube.com/watch?v=6H0bmf6u0gU)

**How it works:** When saying *define word* to Google Assistant, the query is passed through [IFTTT](ifttt.com), which makes a request back to my phone. After receiving the desired word, the automation pulls definitions from Merriam-Webster and Collins dictionary website and speaks back to the user.


2. Custom News Radio
------------------
 I developed this tool to listen to a customized news from a news website I trust. The tool speaks top five news from Worlds and India, Also it omits sports news. (I like to play sports more than following.)

![alt](https://img.youtube.com/vi/d1S5nuDJVrA/0.jpg)](https://www.youtube.com/watch?v=d1S5nuDJVrA)

**How it works:** The automation scripts pull top headlines and a brief overview from BBC website for specific geographies and speaks back to the user.


3. Calendar Events Classification and Custom Notification UI
---------------------
I set up my to-do list using Google Calendar. I wished to have a classification of 'critical', 'important' and 'flexible' to-do items. Also, I wished to have the notification to reflect the importance of the task as desired. Further, Isn't it cool to have the phone to speak up the to-do item when you are away from the phone?  

![alt](https://img.youtube.com/vi/-ucS2w9voHg/0.jpg)](https://www.youtube.com/watch?v=-ucS2w9voHg)

**How it works:** The automation intercepts calender notification in Android and based on the content the event title, the task is spoken to the user. The content can be specified to assert the importance of the task and specify whether to speak or not to speak the task.


4. Download UI Module
-----------------------
I have developed many automation tools which require a file download from the Internet. However, I wished that I could see download progress while I am doing some other work on my phone. So, I developed a minimal overlay UI which shows download progress and yet it allows the user to work on other without any interference. Also, this module can be integrated with any other [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=en) automation script for downloading any file from the Internet. See demo in next tool (TED Video Downloader).


**How it works:** It monitors the current download progress and uses progressbar.js library to show download progress in a pie-chart format.     

5. TED Video Downloader
--------------
For me, it is inconvenient to watch TED videos on android browsers. The nature of TED videos is such that sometimes it is desirable to review what speaker just said. Rewinding video backward on android browser screen is very inaccurate and clumsy. So, I developed a tool which can download TED video along with its English subtitle. A user can share any TED video web page with automation app either from PC or from android browser. After the download is complete, the video can be watched in MX player which have very accurate user controls. 

![alt](https://img.youtube.com/vi/zp4dM7IK5oU/0.jpg)](https://www.youtube.com/watch?v=zp4dM7IK5oU)

**How it works:** The automation gets the TED web page URL from the shared text and it pulls subtitles and appropriate high-quality video from the web page's HTML code. 