downloaddemo
============

A download demo to show how to use my android download 

We spent about 2 month to finish a full feature android  download manager in a video app. 
And we think it will help you when you want develop a app such as app market which need download manager feature. It support below features:

1. Download task management api and UI
Support add, start, pause,cancel or delete a download task by API or use download task manager UI. The UI can display each tasks progress and status.

2. Notification bar download progress and speed display, download finished alarm.
When click a downloading Notification will go to the  downloading task list. When a download task finished, it will pop in Notification bar with a ring alarm.

3.Large file download support. 
This download manager is designed for downloading flv video files, it can download files more than 200M and is full tested.
it also support continue transferring from breakpoint.

4.Support download item icon/image store in asset,sdcard,http url.

5.Easy intergration
it published as a zip file, you only need to copy resource files, jar file to you project,then add sevaral line code to the Androidmanifest.xml, then you can have a full feature download manager. Document and demo also provide to help you.

6.Custom friendly
You can change the UI by edit the layouts and icons as you wish.
You can change the download task click behavior by extend our DownloadListActivity.


You can clone the download demo from github. The update will always be pushed here.
git clone  https://github.com/offbye/downloaddemo

Now is opensource under Apache License, you can find the code from:
https://github.com/offbye/AndroidDownloadManger

<img src="http://img.my.csdn.net/uploads/201211/21/1353505828_7068.jpg" alt="" width="320" style="border: none;"/>
<img src="http://img.my.csdn.net/uploads/201211/21/1353505882_8971.jpg" alt="" width="320" style="border: none;"/>
