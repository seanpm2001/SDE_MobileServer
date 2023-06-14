
***

<img src="/SDE_MobileServer_1024pxIcon_V1_HighCompression.png" alt="SDE MobileServer Logo failed to load" width="280" height="280">

# [SDE MobileServer](#SDE-MobileServer)

`🇸-🇩-🇪📱️🌐️💾️ SDE MobileServer is an experimental project chain with the goal of running an entire server off of a portable device (phones, phablets, and tablets)`

***

## [Project goals](#Project-goals)

This project has 2 major goals:

- To see if it is possible to run an entire server off of a mobile device
- To raise the default storage capacity in mobile devices to accommodate mobile servers (this can be done if the project is successful enough to create a demand for higher-capacity phones and tablets to run larger servers)

This project was made part of the SDE project, as I couldn't fit it in anywhere else, nor make it a separate project.

***

## [Original draft](#Original-draft)

### [Imager](#Imager)

The imager is a way to image the server and its data from a desktop computer to a mobile device. Since phones can't be used to program large applications, the imager is a very important component.

### [Test zone](#Test-zone)

The test zone is a set of sandbox servers and tools to test the server on your mobile device before deployment. It contains some basic webpages, along with the 3 acid tests (with some other standards checks) to test how devices display server webpages.

### [Connection types](#Connection-types)

- Wi-Fi 2.4 Ghz (limited server)
- Wi-Fi 5.0 Ghz (basic server)
- 1x mobile data (inapplicable) ❌️
- 2G mobile data (the most basic server)
- 3G mobile data (very limited server)
- 4G mobile data (limited server)
- 5G mobile data (be careful about billing)
- 6G mobile data (be careful about billing)
- Mobile hotspot 2.4 Ghz (limited server)
- Mobile hotspot 5.0 Ghz (basic server)
- Bluetooth (limited server)

### [Languages](#Languages)

SDE MobileServer is written in:

- Java (Android)
- Kotlin (FireOS)
- Swift (iOS)
- Objective-C++ (iPadOS)
- Python, Vala (Ubuntu, PostMarketOS)
- C (Core)

***

## [Documentation](#Documentation)

Documentation is located in a separate repository: [:octocat: `SDE MobileServer Docs`](https://github.com/seanpm2001/SDE_MobileServer_Docs/)

***

## [Ports](#Ports)

Official Ports of SDE MobileServer are currently available for `6` operating systems, as of 2023, Wednesday, June 14th, which include:

| Logo | Repo link | Info | Language(s) | 
|---|---|---|---|
| <img src="/Graphics/OSPorts/Android/SVG/Android_logo_2019_(stacked).svg" alt="/Graphics/OSPorts/Android/SVG/Android_logo_2019_(stacked).svg" width="128" height="128"> | [:octocat: `SDE MobileServer for Android`](https://github.com/seanpm2001/SDE_MobileServer_Android/) | AndroidOS port | `Java` |
| <img src="/Graphics/OSPorts/FireOS/PNG/Amazon-Fire-Logo.png" alt="/Graphics/OSPorts/FireOS/PNG/Amazon-Fire-Logo.png" width="128" height="128"> | [:octocat: `SDE MobileServer for FireOS`](https://github.com/seanpm2001/SDE_MobileServer_FireOS/) | FireOS port | `Kotlin` |
| <img src="/Graphics/OSPorts/iOS/PNG/iOS_Logo.png" alt="/Graphics/OSPorts/iOS/PNG/iOS_Logo.png" width="128" height="128"> | [:octocat: `SDE MobileServer for iOS`](https://github.com/seanpm2001/SDE_MobileServer_iOS/) | iOS port | `Swift` |
| <img src="/Graphics/OSPorts/iPadOS/PNG/iPadOS-Logo.png" alt="/Graphics/OSPorts/iPadOS/iPadOS-Logo.png" width="128" height="128"> | [:octocat: `SDE MobileServer for iPadOS`](https://github.com/seanpm2001/SDE_MobileServer_iPadOS/) | iPadOS port | `Objective-C++` |
| <img src="/Graphics/OSPorts/PostMarketOS/SVG/PostmarketOS_logo.svg" alt="/Graphics/OSPorts/PostMarketOS/SVG/PostmarketOS_logo.svg" width="128" height="128"> | [:octocat: `SDE MobileServer for PostMarketOS`](https://github.com/seanpm2001/SDE_MobileServer_PostMarketOS) | PostMarketOS port | `Python` `Vala` |
| <img src="/Graphics/OSPorts/Ubuntu/PNG/UbuntuLogo1.png" alt="/Graphics/OSPorts/Ubuntu/PNG/UbuntuLogo1.png" width="128" height="128"> | [:octocat: `SDE MobileServer for Ubuntu`](https://github.com/seanpm2001/SDE_MobileServer_Ubuntu) | Ubuntu Touch port | `Python` `Vala` |

This is for the server itself. The [imager](#Imager), and other [utilities](#Utilities) are planned to have support on:

- Ubuntu 16.04 and up
- Fedora 26 and up
- Windows 7 and up
- MacOS 10.15 and up

***

## [Plugins](#Plugins)

There are currently `8` official plugins for SDE MobileServer, as of 2023, Wednesday, June 14th, which include:

| Logo | Repo link | Info | Language(s) | 
|---|---|---|---|
| <img src="/Graphics/Plugins/CraftCMS/JPEG/CraftCMS-Logo.jpeg" alt="/Graphics/Plugins/CraftCMS/JPEG/CraftCMS-Logo.jpeg" width="128" height="128"> | [:octocat: `SDE MobileServer CraftCMS Plugin`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_CraftCMS/) | CraftCMS support for MobileServer | `PHP` |
| <img src="/Graphics/Plugins/Ruffle/SVG/Ruffle_vector_logo.svg" alt="/Graphics/Plugins/Ruffle/SVG/Ruffle_vector_logo.svg" width="128" height="128"> | [:octocat: `SDE MobileServer RuffleRS Plugin`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_Ruffle/) | RuffleRS support for MobileServer | `Rust` |
| <img src="/Graphics/Plugins/WordPress/PNG/WordPress-Logo.png" alt="/Graphics/Plugins/WordPress/PNG/WordPress-Logo.png" width="128" height="128"> | [:octocat: `SDE MobileServer WordPress Plugin`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_WordPress/) | WordPress support for MobileServer | `PHP` |
| <img src="/Graphics/Plugins/MediaWiki/PNG/MediaWiki_logo_1-1536x1536.png" alt="/Graphics/Plugins/MediaWiki/PNG/MediaWiki_logo_1-1536x1536.png" width="128" height="128"> | [:octocat: `SDE MobileServer MediaWiki Plugin`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_MediaWiki/) | MediaWiki support for MobileServer | `PHP` |
| <img src="/Graphics/Plugins/SNU/PNG/SNU_blue_and_gold_legacy_icon.png" alt="/Graphics/Plugins/SNU/PNG/SNU_blue_and_gold_legacy_icon.png" width="128" height="128"> | [:octocat: `SDE MobileServer SNU Plugin`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_SNU/) | SNU support for MobileServer | `Python` |
| <img src="/Graphics/Plugins/XMPP/SVG/XMPP_logo.svg" alt="/Graphics/Plugins/XMPP/SVG/XMPP_logo.svg" width="128" height="128"> | [:octocat: `SDE MobileServer XMPP Plugin`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_XMPP/) | XMPP support for MobileServer | `XSLT` |
| <img src="/Graphics/Plugins/Jekyll/SVG/jekyll-test-tube.svg" alt="/Graphics/Plugins/Jekyll/SVG/jekyll-test-tube.svg" width="128" height="128"> | [:octocat: `SDE MobileServer Jekyll Plugin`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_Jekyll/) | Jekyll support for MobileServer | `Ruby` |
| <img src="/Graphics/Plugins/MdBook/PNG/MdBook_Logo_Small_196px.png" alt="/Graphics/Plugins/MdBook/PNG/MdBook_Logo_Small_196px.png" width="128" height="128"> | [:octocat: `SDE MobileServer MdBook Plugin`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_MdBook/) | MdBook support for MobileServer | `Rust` |

***

## [Utilities](#Utilities)

There are currently `2` official utilities for SDE MobileServer, as of 2023, Wednesday, June 14th, which include:

| Logo | Repo link | Info | Language(s) | 
|---|---|---|---|
| <img src="/SDE.png" alt="SDE Logo failed to load" width="128" height="128"> | [:octocat: `SDE MobileServer Imager`](https://github.com/seanpm2001/SDE_MobileServer_Imager/) | Server imaging utility | `C` |
| <img src="/SDE.png" alt="SDE Logo failed to load" width="128" height="128"> | [:octocat: `SDE MobileServer TestZone`](https://github.com/seanpm2001/SDE_MobileServer_TestZone/) | Server testing utility | `C` |

These are not to be confused with plugins. Utilities help configure and setup the server, plugins are additional components for the launched server.

***

## [Repositories](#Repositories)

As of 2023, Wednesday, June 14th, there are `18` repositories that are part of this project. They include:

- [:octocat: `SDE MobileServer (current repository)`](https://github.com/seanpm2001/SDE_MobileServer/) - Home repository
- [:octocat: `SDE MobileServer Docs`](https://github.com/seanpm2001/SDE_MobileServer_Docs/) - Documentation repository
- [:octocat: `SDE MobileServer Imager`](https://github.com/seanpm2001/SDE_MobileServer_Imager/) - Server imaging utility
- [:octocat: `SDE MobileServer TestZone`](https://github.com/seanpm2001/SDE_MobileServer_TestZone/) - Server testing utility
- [:octocat: `SDE MobileServer Android`](https://github.com/seanpm2001/SDE_MobileServer_Android/) - AndroidOS port of SDE MOBSVR
- [:octocat: `SDE MobileServer FireOS`](https://github.com/seanpm2001/SDE_MobileServer_FireOS/) - FireOS port for SDE MOBSVR
- [:octocat: `SDE MobileServer iOS`](https://github.com/seanpm2001/SDE_MobileServer_iOS/) - iOS port for SDE MOBSVR
- [:octocat: `SDE MobileServer iPadOS`](https://github.com/seanpm2001/SDE_MobileServer_iPadOS/) - iPadOS port for SDE MOBSVR
- [:octocat: `SDE MobileServer Ubuntu`](https://github.com/seanpm2001/SDE_MobileServer_Ubuntu/) - Ubuntu port for SDE MOBSVR
- [:octocat: `SDE MobileServer PostMarketOS`](https://github.com/seanpm2001/SDE_MobileServer_PostMarketOS/) - PostMarketOS port for SDE MOBSVR
- [:octocat: `SDE MobileServer Plugins CraftCMS`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_CraftCMS/) - CraftCMS plugin for SDE MOBSVR
- [:octocat: `SDE MobileServer Plugins RuffleRS`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_Ruffle/) - RuffleRS plugin for SDE MOBSVR
- [:octocat: `SDE MobileServer Plugins WordPress`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_WordPress/) - WordPress plugin for SDE MOBSVR
- [:octocat: `SDE MobileServer Plugins MediaWiki`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_MediaWiki/) - MediaWiki plugin for SDE MOBSVR
- [:octocat: `SDE MobileServer Plugins SNU`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_SNU/) - SNU plugin for SDE MOBSVR
- [:octocat: `SDE MobileServer Plugins XMPP`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_XMPP/) - XMPP plugin for SDE MOBSVR 
- [:octocat: `SDE MobileServer Plugins Jekyll`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_Jekyll/) - Jekyll plugin for SDE MOBSVR 
- [:octocat: `SDE MobileServer Plugins MdBook`](https://github.com/seanpm2001/SDE_MobileServer_Plugins_MdBook/) - MdBook plugin for SDE MOBSVR 
- More repositories coming soon.

***

## [SDE Project](#SDE-Project)

| <img src="/SDE.png" alt="SDE Logo failed to load" width="256" height="256"> |
|---|
| This project is a part of the [S Desktop Environment (SDE, or Skeuowie) project](https://github.com/seanpm2001/SDE/) |

***

# [File info](#File-info)

<details open><summary><p lang="en"><b><u>Click/tap here to expand/collapse this section</u></b></p></summary>

**File type:** `Markdown (*.md *.mkd *.mdown *.markdown)`

**File version:** `9 (2023, Wednesday, June 14th at 02:12 pm PST)`

**Line count (including blank lines and compiler line):** `392`

**Word count:** `2,475`

**Character count (including spaces):** `17,362`

**Character count (excluding spaces):** `15,124`

**Size (in bytes):** `17,390`

**Current article language:** `English (EN_USA)` / `Markdown (CommonMark)` / `HTML5 (HyperText Markup Language 5.3)`

**Encoding:** `UTF-8 (Emoji 12.0 or higher recommended)`

**All times are UTC-7 (PDT/Pacific Time)** `(Please also account for DST (Daylight Savings Time) for older/newer entries up until it is abolished/no longer followed)`

> **Note** _On 2022, Sunday, March 13th at 2:00 am PST, the time jumped ahead 1 hour to 3:00 am._

> **Note** **You may need special rendering support for the `<details>` HTML tag being used in this document**

</details>

***

## [File history](#File-history)

<details><summary><p lang="en"><b>Click/tap here to expand/collapse the file history section for this project</b></p></summary>

---

<details><summary><p lang="en"><b>Version 1 (2023, Tuesday, June 6th at 11:25 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Started the file
- [x] Added the title section
- [x] Added the `Project goal` section
- [x] Added the `Original draft` section
- - [x] Added the `Imager` subsection
- - [x] Added the `Test Zone` subsection
- - [x] Added the `Connection types` subsection
- - [x] Added the `Languages` subsection
- [x] Added the `Documentation` section
- [x] Added the `Repositories` section
- [x] Added the `file info` section
- [ ] No other changes in version 1

</details>

---

<details><summary><p lang="en"><b>Version 2 (2023, Wednesday, June 7th at 11:21 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Updated the `Repositories` section
- [x] Added the `SDE project` section
- [x] Updated the `file info` section
- [ ] No other changes in version 2

</details>

---

<details><summary><p lang="en"><b>Version 3 (2023, Thursday, June 8th at 10:05 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Added direct anchor links to all headings
- [x] Updated the `Project goals` section (renamed from `Project goal` to `Project goals`)
- [x] Updated the `Repositories` section
- [x] Updated the `file info` section
- [ ] No other changes in version 3

</details>

---

<details><summary><p lang="en"><b>Version 4 (2023, Friday, June 9th at 10:12 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Updated the `Repositories` section
- [x] Added the `Ports` section
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Added the line count
- [x] Added the `file history` section
- - [x] Added an entry for version 1
- - [x] Added an entry for version 2
- - [x] Added an entry for version 3
- - [x] Added an entry for version 4
- [x] Added the footer
- [ ] No other changes in version 4

</details>

---

<details><summary><p lang="en"><b>Version 5 (2023, Saturday, June 10th at 10:46 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Updated the `Repositories` section
- [x] Added the `Ports` section
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 5
- [x] Added the footer
- [ ] No other changes in version 5

</details>

---

<details><summary><p lang="en"><b>Version 6 (2023, Sunday, June 11th at 10:10 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Updated the `Repositories` section
- [x] Updated the `Ports` section
- - [x] Converted the list into a table with icons, and additional information
- [x] Added the `Plugins` section
- - [x] Added a table with the current 2 plugins, that includes icons, and additional information
- [x] Added the `Utilities` section
- - [x] Added a table with the current 2 utilities, that includes icons, and additional information
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 6
- [x] Added the footer
- [ ] No other changes in version 6

</details>

---

<details><summary><p lang="en"><b>Version 7 (2023, Monday, June 12th at 10:42 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Updated the `Repositories` section
- [x] Updated the `Plugins` section
- - [x] Added the latest 2 entries
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 7
- [x] Added the footer
- [ ] No other changes in version 7

</details>

---

<details><summary><p lang="en"><b>Version 8 (2023, Tuesday, June 13th at 02:16 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Updated the `Repositories` section
- [x] Updated the `Plugins` section
- - [x] Added the latest 2 entries
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 8
- [x] Added the footer
- [ ] No other changes in version 8

</details>

---

<details><summary><p lang="en"><b>Version 9 (2023, Wednesday, June 14th at 02:12 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

> Changes:

- [x] Updated the `Repositories` section
- [x] Updated the `Plugins` section
- - [x] Added the latest 2 entries
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 9
- [x] Added the footer
- [ ] No other changes in version 9

</details>

---

</details>

***

# [Footer](#Footer)

You have reached the end of this page.

###### [EOF](#EOF)

***
