# Welcome

## OpenOffice.org 2.4 ReadMe

For latest updates to this readme file, see <http://www.openoffice.org/welcome/readme.html>
Dear User

This file contains important information about this program. Please read this information very carefully before starting work.

The OpenOffice.org community, responsible for the development of this product, invites you to become members. As new users of OpenOffice.org, you will find precious information at this [page](http://www.openoffice.org/about_us/introduction.html).

Also read the sections below about getting involved in the OpenOffice.org project.

## Installation

System requirements:

- Microsoft Windows 98, ME, NT (Service Pack 6 or earlier versions), 2000 or XP
- PC compatible Pentium
- 64 MB of RAM
- 250 MB (CJK version: 300 MB) of free disk space
- 500 MB Disk space needed after installation is complete when deleting temporary installer files.
- Screen resolution of 800x600 minimum, at least 256 colors

## Is OpenOffice.org really free for any user?

OpenOffice.org is free for use by everybody (this includes Government, business, educational and private use). For further details see the license text delivered together with OpenOffice.org or <http://www.openoffice.org/license.html>

## Problems During Program Startup

Difficulties starting OpenOffice.org (e.g. applications hang) as well as problems with the screen display are often caused by the graphics card driver. If these problems occur, please update your graphics card driver or try using the graphics driver delivered with your operating system. Difficulties displaying 3D objects can often be solved by deactivating the option "Use OpenGL" under 'Tools - Options - OpenOffice.org - View - 3D view'.

You can install OpenOffice.org 2.4 alongside of an older version of OpenOffice.org. If you later choose to uninstall the older version of OpenOffice.org, you must call the installation program of the newer version and choose 'Repair'. This ensures that the new version is correctly registered in your system.

Please note that copy and paste via clipboard between OpenOffice.org 1.x and OpenOffice.org 2.4 might not work in OpenOffice.org format. If that happens, choose 'Edit - Paste Special' and choose a format other than OpenOffice.org, or open the document in OpenOffice.org 2.4 directly.

Please make sure you have enough free memory in the temporary directory on your system and that read, write and run access rights have been granted. Close all other programs before starting the installation.

Note: Please be aware that administrator rights are needed for the installation process.

Note for Windows 98 users only: If you choose to install Java during the OpenOffice.org installation program, the installer will ask you to reboot your system. You should either ignore this message or open the OpenOffice.org installation program again after the reboot.

## ALPS/Synaptics notebook touchpads in Windows

Due to a Windows driver issue, you cannot scroll through OpenOffice.org documents when you slide your finger across an ALPS/Synaptics touchpad.

To enable touchpad scrolling, add the following lines to the "C:\Program Files\Synaptics\SynTP\SynTPEnh.ini" configuration file, and restart your computer:

[OpenOffice.org]
FC = "SALFRAME"
SF = 0x10000000
SF |= 0x00004000

Note: The location of the configuration file might vary on different versions of Windows.

## Ai Squared ZoomText 7.11

If you wish to use Ai Squared ZoomText with OpenOffice.org 2.4, you must have version 7.11 or later. Only versions of Ai Squared ZoomText downloaded after June 12, 2002, offer the required features.

## Keyboard Shortcuts

You can only use keyboard shortcuts (key combinations) in OpenOffice.org that are not already used by the operating system. If a key combination in OpenOffice.org does not work as described in the OpenOffice.org help, it is possible that this shortcut is already used by the operating system. To resolve such conflicts, modify, for example, the shortcuts defined by your operating system. You can also modify most of the shortcuts defined in OpenOffice.org. For more information on this subject, refer to the OpenOffice.org help or your operating system help.

## Problems Sending Documents by Email from OpenOffice.org

The program may crash or freeze when you attempt to send a document by email by choosing File - Send - Document by Email or Document as PDF Attachment. This is because the Windows MAPI (Messaging Application Programming Interface) system file generates errors with certain file versions. Unfortunately, it is impossible to narrow this problem down to a specific number of versions. For more information, visit <http://www.microsoft.com>, then type "mapi dll" in the search field of the Microsoft Knowledge Base.

## Registration

We kindly ask you to follow the minimal product registration procedure during the software installation. Registration is optional, but we would appreciate it if you could take a few minutes to complete it, as the information provided would help the community in its effort to improve the software suite and directly respond to user needs. To protect your personal data, the OpenOffice.org community applies a strict privacy policy. If you did not follow the registration procedure during the product installation, you can do so at any time by visiting <www.openoffice.org/welcome/registration-site.html>

## User Survey

We also invite you to participate in the online user survey. The survey results will allow OpenOffice.org to more quickly define higher-level standards to offer you the next generation of the office suite. To protect your personal data, the OpenOffice.org community applies a strict privacy policy.

## User Support

For help with the OpenOffice.org 2.0 office suite, consult the archives where you will find answers to previously asked questions in the mailing list <users@openoffice.org> at <www.openoffice.org/mail_list.html>. If you prefer, post your questions to the list <users@openoffice.org>. Don't forget to subscribe to the mailing list to receive a response by email.

The FAQ section is also available in the navigation bar, on the left of the OpenOffice.org homepage. The most common questions can be found in this FAQ.<http://user-faq.openoffice.org/>.

## Reporting Bugs and Issues

The OpenOffice.org website hosts IssueZilla, our tool for generating, tracking, and resolving bugs and issues. We invite every user to report any problems they encounter on a particular platform. Systematic reporting of issues is one of the most important contributions users can make to the community for the development and continuous improvement of the software suite.

## Contribution

Your active participation in the development of this great Open Source project would bring much to the OpenOffice.org community.

As a user, you are already a valuable contributor to the development process of this office suite. We invite you to get even more involved by contributing to the community's activities in the long term. Join us and visit the user page at: <www.openoffice.org>

## Way to Start

The best way to start contributing is to subscribe to one or more of the mailing lists, lurk for a while, and gradually use the mail archives to familiarize yourself with many of the topics covered since the OpenOffice.org source code was released back in October 2000. When you're comfortable, all you need to do is send an email self-introduction and jump right in. If you are familiar with Open Source Projects, check out our To-Dos list and see if there is anything you would like to help with at <http://development.openoffice.org/todo.html>.

## Subscribe

Here are a few of the Project mailing lists to which you can subscribe at <http://www.openoffice.org/mail_list.html>

- News: <announce@openoffice.org> *recommended to all users* (light traffic)
- Main user forum: <discuss@openoffice.org> *easy way to lurk on discussions* (heavy)
- Marketing project: <dev@marketing.openoffice.org> *beyond development* (getting heavy)
- General code contributor list: <dev@openoffice.org> (moderate/heavy)

## Join one or more Projects

You can make major contributions to this important open source project even if you have limited software design or coding experience. Yes, you!

At <http://projects.openoffice.org/index.html> you will find projects ranging from Localization, Porting and Groupware to some real core coding projects. If you are not a developer, try the Documentation or the Marketing Project. The OpenOffice.org Marketing Project is applying both guerrilla and traditional commercial techniques to marketing open source software, and we are doing it across language and cultural barriers, so you can help just by spreading the word and telling a friend about this office suite.

You can help by joining the Marketing Communications & Information Network here: <http://marketing.openoffice.org/contacts.html> where you can provide point communication contact with press, media, government agencies, consultants, schools, Linux Users Groups and developers in your country and local community.

We wish you pleasant work with OpenOffice.org 2.4 and hope to meet you soon on the website.

The OpenOffice.org community

## Modified / Used Source Code

Portions Copyright 1998, 1999 James Clark. Portions Copyright 1996, 1998 Netscape Communications Corporation.
