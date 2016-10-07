---
title: Lab Startup
author: kleinen
layout: lab
---


Welcome to the laboratory - that's what we call these rooms filled with computer equipment. Each computer in WH C 576 and WH C 579 is a so-called dual-boot computer that can boot to Windows or Ubuntu Linux, or Mac OS in WH C 537. As computer science students we expect you to be able to deal with Windows, Unix, and Mac OS operating systems.

We have lots of rules for the labs, as they are used by many different people during the week. Usually we're in one of three available labs, you find an overview of them including a link to the rules ("Laborordnung") [here](http://imi-bachelor.htw-berlin.de/studium/labore/).

Two really important rules are:

- **No food.** We don't like crumbs in the keyboards. Drinks are okay if they are in a container with a screw-on lid and the lid is screwed on. No coffee cups! They get knocked over and we have to get new machines.
- **Don't change the configuration.** We don't care if you have spent half your life "optimizing" computers. We have them set up this way because that is the way we do it. It's ok to use your own laptop in the lab, we've provided extra VGA cables and Power Plugs to connect them.

If something goes wrong, don't panic. Speak with the lab leader or the lab engineer.

It is usually a good idea to save your work at regular intervals. We sometimes have issues with the power here. Then you only have what you last saved.

## Pre-Lab

Each lab assignment comes with a pre-lab section. Usually, it includes excercises and research questions that prepare you for the lab assignment.
You're expected to complete these *before* you come to the lab.

This week, you should prepare your own computer for the lab if you plan to use it during the lab. You can, of course, do that later, or switch between using your own computer and those in the lab (there's a description below on how to transfer files). *But you should not start the lab with installing software on your own computer. You will loose the opportunity to ask questions on the lab assignment this way and spend way more time trying to solve them later this way!*

### Download and Install Greenfoot and BlueJ:

* Download and install Greenfoot as described on their page: http://www.greenfoot.org/download - the most convenient way will be to install the dedicated version for your operating system.

* If you want to save space, you can download and install Java and the pure Java Versions of Greenfoot
and BlueJ. This is a tad more complicated.

HERE
* http://www.oracle.com/technetwork/java/javase/downloads/index.html
* Download and install BlueJ as described on their page:
* you should also, even if you have installed the platform-specific versions
 [http://www.greenfoot.org/download](http://www.greenfoot.org/download)
 *  Then download the first kara scenario from [github][1] (there is a "ZIP" Button!) and unpack it in your scenarios folder. Then open Greenfoot and open the scenario - now you can play around with Kara! For this first exercise, there is no special programming assignment. But you could create a second Kara, try to make it permanent by finding the "save the world" menu item or even modify the act() method within MyKara.


1.   [Download the Kara Scenarios][1] from github: use the "Download ZIP" button in the lower right corner if you're not familiar with git and github or use [this direct link](https://github.com/htw-imi-info1/kara/archive/ws2016.zip). You will use the scenarios 01-01 through 01-08 for this lab.

## Assignment

### 1. Logbook

You need to get used to keeping a logbook in the lab. It can be analog (i.e. on paper) or digital. Make sure that you label and date your logbook. Keep track of everything you do in the logbook - even if you are really excited and want to keep playing. You will save time later if you can easily retrace your steps. Your lab leader will show you how to set up an online logbook. Make a logbook for today and take notes on what we do. This will be turned in as a lab report this week. Don't forget your name!

### 2. Logging in and Getting Ready for the Exercises

Now that you have your FB 4 username, you also have a home directory. This is where all your files can be placed. You can access it both from Mac OS, Windows and from Ubuntu. Since BlueJ is installed under MacOS, we will be using it here, although there are also versions for Ubuntu and Windows.

After you have logged in, look around - where do you find a browser? How many browsers are there? Is there any way to print from the lab? How do you make a screen shot? How can you make a pdf file? Where is the Java JDK installed? Note down the path. Open up a command line and find out the active java version by typing

    > java -version

### 3. Download and Install Greenfoot:

***Update 21.20.2014: Greenfoot is already installed in 576, 579 and on MacOS in 537***

### 4. Take a Photo and Write Something about Your Team Members

* In your groups, take a photo of each one of you to include in the report(s).
* Briefly introduce each one to me in the report: the two others should interview and write something about each person. Ask him or her what brought you here, and something that helps me remember his or her name.


### 5. Logging Out

When it comes time to log out, _be very careful._ Computers can be very fussy about this.
Think of it as a friend who will be insulted if you do not properly say goodbye.
The proper way is to click on the icon that looks like a power button and select "Benutzer
abmelden" or to click on the Start button (yes, Windows is a bit strange). You might be asked if you want to remember what you were doing, you can choose to do this, or not. Try out both sometime. This is also a choice "herunterfahren". Selecting this is the one and only way to safely prepare the machine for powering down.
**Never** power down the machine without doing this first. Once you have logged out, please turn the machine and screen off if they didn't shut off automatically, **put your chair back under the table, and clean up any garbage that may have accumulated.**


## Writeup

You will be doing your writeup at ***home***. If you do not have a computer at home, you can use the lab computers during times when there is no class. Hmm, you saved some information on your login area on the school server, can you access this from home? Yes! Your home directory is on the server uranus.f4.htw-berlin.de (or it was last week). There is a service called FTP that you can use to access these files. You will need to login to the FTP service with your FB 4 login to see your files. On Windows machines you open up a command window and use FTP. On Mac or Unix machines you open up a terminal and use ftp there.

Submit your writeup, explaining what you did and what you learned, as your post-lab to the Moodle area, as a practice - it will not be graded.

Make sure to include your name and a photo at the top of your report.

## For the Bored

This first lab is really about getting started, getting to know the infrastructure and make sure that you are able to run Kara programs in Greenfoot yourself during the next week. If you feel bored, you might start off right away with working on the the [prelab of next week lab](../exercise-01-a).

[1]: https://github.com/htw-imi-info1/kara-scenario1