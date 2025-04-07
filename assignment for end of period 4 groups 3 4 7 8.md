# OpenOffice.org 2.4 – README

For the latest updates, visit: [OpenOffice.org ReadMe](http://www.openoffice.org/welcome/readme.html)

Welcome, and thank you for using OpenOffice.org 2.4. This document provides important information about the software. Please read it carefully before starting.

---

## Table of Contents

- [OpenOffice.org 2.4 – README](#openofficeorg-24--readme)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Installation](#installation)
  - [Is OpenOffice.org Really Free for Any User?](#is-openofficeorg-really-free-for-any-user)
  - [Problems During Program Startup](#problems-during-program-startup)
  - [ALPS/Synaptics Notebook Touchpads in Windows](#alpssynaptics-notebook-touchpads-in-windows)
  - [Ai Squared ZoomText 7.11](#ai-squared-zoomtext-711)
  - [Keyboard Shortcuts](#keyboard-shortcuts)
  - [Problems Sending Documents by Email from OpenOffice.org](#problems-sending-documents-by-email-from-openofficeorg)
  - [Registration](#registration)
  - [User Survey](#user-survey)
  - [User Support](#user-support)
  - [Reporting Bugs and Issues](#reporting-bugs-and-issues)
  - [Contribution](#contribution)
  - [Way to Start](#way-to-start)
  - [Subscribe](#subscribe)
  - [Join One or More Projects](#join-one-or-more-projects)
  - [Modified / Used Source Code](#modified--used-source-code)

---

## Introduction

We encourage new users to explore more about the OpenOffice.org community here: [Introduction to OpenOffice.org](http://www.openoffice.org/about_us/introduction.html).

## Installation

**System Requirements:**

- Microsoft Windows 98, ME, NT (SP6 or earlier), 2000, or XP
- Pentium-compatible PC
- 64 MB RAM
- 250 MB free disk space (300 MB for CJK version)
- 500 MB disk space after installation (to remove temporary files)
- 800x600 minimum screen resolution, 256 colors

**Installation Notes:**

- Ensure enough free memory in your system's temp directory
- Grant read, write, and run permissions
- Close all programs before installing
- Administrator rights are required

**Note for Windows 98 Users:** If installing Java, you may be asked to reboot. After rebooting, restart the installation manually.

## Is OpenOffice.org Really Free for Any User?

Yes! OpenOffice.org is free for everyone, including governments, businesses, schools, and individuals. See full license: [OpenOffice.org License](http://www.openoffice.org/license.html)

## Problems During Program Startup

Startup issues or display glitches are often caused by outdated graphics drivers. Try updating your drivers or using default OS drivers.

**3D Display Issues:** Disable "Use OpenGL" under:
`Tools -> Options -> OpenOffice.org -> View -> 3D view`

**Coexistence with Older Versions:**
You can install OpenOffice.org 2.4 alongside older versions. If you later uninstall the older version, run the 2.4 installer and choose "Repair" to properly register it.

**Clipboard Compatibility:** Copy/paste may fail between 1.x and 2.4. Use `Edit -> Paste Special` to choose another format or open the document directly in 2.4.

## ALPS/Synaptics Notebook Touchpads in Windows

Scrolling may not work due to Windows driver issues. To enable it, add this to:
`C:\Program Files\Synaptics\SynTP\SynTPEnh.ini`

```md
[OpenOffice.org]
FC = "SALFRAME"
SF = 0x10000000
SF |= 0x00004000
```

Then restart your computer. (Path may vary by OS.)

## Ai Squared ZoomText 7.11

To use ZoomText with OpenOffice.org 2.4, ensure you're running version 7.11 or later (downloaded after June 12, 2002).

## Keyboard Shortcuts

Some OS-level shortcuts may conflict with OpenOffice.org. Adjust your OS or OpenOffice.org shortcut settings as needed. See OpenOffice.org Help or your OS documentation for details.

## Problems Sending Documents by Email from OpenOffice.org

Crashes or freezes when emailing documents may be caused by MAPI issues on Windows. Visit [Microsoft Knowledge Base](http://www.microsoft.com) and search for "mapi dll" for more info.

## Registration

Registration is optional but encouraged. It helps improve OpenOffice.org based on real user needs. Register any time at:  
[OpenOffice.org Registration](http://www.openoffice.org/welcome/registration-site.html)

## User Survey

Participate in our user survey to help shape the future of OpenOffice.org. We respect your privacy.

## User Support

- Search mailing list archives: [OpenOffice.org Mailing Lists](http://www.openoffice.org/mail_list.html)
- Email questions to: `users@openoffice.org` (subscribe first)
- Check FAQs: [OpenOffice.org FAQ](http://user-faq.openoffice.org/)

## Reporting Bugs and Issues

Use our bug tracker **IssueZilla** to report problems: [OpenOffice.org IssueZilla](http://www.openoffice.org/issues/)

## Contribution

Whether you're a user or a developer, you can contribute! Explore opportunities here: [OpenOffice.org](http://www.openoffice.org)

## Way to Start

Subscribe to mailing lists, read archives, introduce yourself, and jump in! Check out the To-Do list:  
[OpenOffice.org To-Do](http://development.openoffice.org/todo.html)

## Subscribe

Join mailing lists here: [OpenOffice.org Mailing Lists](http://www.openoffice.org/mail_list.html)

- **News:** `announce@openoffice.org` *(recommended)*
- **Main Forum:** `discuss@openoffice.org`
- **Marketing Project:** `dev@marketing.openoffice.org`
- **Code Contributors:** `dev@openoffice.org`

## Join One or More Projects

Get involved in a variety of areas:

- [OpenOffice.org Projects](http://projects.openoffice.org/index.html)
- Documentation
- Localization
- Porting
- Marketing ([Join Marketing Network](http://marketing.openoffice.org/contacts.html))

Spread the word, tell friends, and help promote OpenOffice.org worldwide!

## Modified / Used Source Code

- Portions © 1998, 1999 James Clark  
- Portions © 1996, 1998 Netscape Communications Corporation

---

We wish you a productive and enjoyable experience with OpenOffice.org 2.4.  
Sincerely,  
**The OpenOffice.org Community**
