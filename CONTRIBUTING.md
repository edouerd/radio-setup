Contributing, for DJs and Devs

—

Index

1. [For Developers](#for-developers)
2. [For DJs](#for-djs)

—

##### For Developers

More later. If you're already here. Great job!

In summary, our tech stack:

https://www.rogueamoeba.com/nicecast/
https://www.airtime.pro/

Interesting leads:

http://libretime.org/
https://mpv.io/installation/
https://github.com/Kickball/awesome-selfhosted#media-streaming
https://github.com/n1trux/awesome-sysadmin#vpn

—

##### For DJs

Gaining access to the server

Before you can start anything, be sure you're 1. OKed by the radio team, and 2. you've been given an account to Bluecast. Mirko can do this for you.

Once you've been given access, log in an make sure Bluecast is 'On Air'. Simple enough.

![Bluecast](/images/1.png)

—

Downloading the streaming software

Next, navigate to https://www.rogueamoeba.com/nicecast/. Click the huge <kbd>Free Download</kbd> button.

![Bluecast](/images/2.png)

As soon as that's done downloading, open up Nicecast. You should be presented with the following interface:

![Bluecast](/images/3.png)

In the top menu, click on <kbd>Window</kbd> ➞ <kbd>Show Server</kbd>, or simply press <kbd>⌘ 2</kbd>. You should see the following:

![Bluecast](/images/4.png)

Open up the drawer using one of the tiny buttons on the top of the window. Click on the <kbd>+</kbd>, and a blank new Untitled Server should appear.

![Bluecast](/images/5.png)

Make sure that all the info you input matches the screenshot below. This information ensures your computer can send sound to the Bluecast server.

![Bluecast](/images/6.png)

Here's copypastable text:

- Name: `Bluecast`
- Server Type: `Icecast 2`
- Account: `*Leave Blank`
- Password: `REDACTED`
- Address: `bluecast-master.rtp.raleigh.ibm.com`
- Port: `8001`
- Mount Point: `/bluecast_master`
- Public URL: `Automatic`

Once this is all done, return to the original Nicecast window and click <kbd>Share</kbd>. You should see two fields with something along the lines of: `http://bluecast-master.rtp.raleigh.ibm.com:8001/bluecast_master.m3u`

![Bluecast](/images/7.png)

Click <kbd>Source</kbd>. You should be defaulted into 'System Audio'. You're basically all set!

![Bluecast](/images/8.png)

At this point, you could now click <kbd>Start Broadcast</kbd> to stream all the audio that would normally emanate from your device. In the next section, we'll explore how to stream with various applications.

—

Streaming Music

TBA

