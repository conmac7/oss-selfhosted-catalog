<a id="top"></a><h1 align="center"> Open Source & Self-Hosted Catalog </h1>

<div align="center"> <img src="/images/Open_Source_Initiative.png" width="240" /> </div>

This is a curated collection of open-source and self-hosted software programs. This catalog serves as a comprehensive guide, featuring a title, corresponding links(homepage, github, git), a concise description and an image for each listed software. 

It aims to provide an organized and informative resource primarily for enthusiasts, home server owners/Admins, homelabbers and end-users who value their privacy and security, and are seeking to explore and adopt various open-source and self-hosted solutions across different domains and use cases.

Some more professional software for IT specialists, sysadmins, and developers/programmers is also listed, but the aim isn't to provide tools, software, and solutions for this specific category.

Finally, the aim of this collection is not to catalog every single open-source and self-hosted software that is available, but rather the most useful ones (in my opinion at least).



--------------------

## Table of contents

- [OSS Operating Systems](#oss-operating-systems)
  - [SerenityOS](#serenity-os)
  - [KolibriOS](#kolibri-os)
  - [illumos](#illumos)
  - [OpenIndiana](#open-indiana)
  - [Haiku](#Haiku)
- [Virtualization](#virtualization)
  - [Proxmox Virtual Environment](#proxmox)
  - [Xen Project](#xen-project)
  - [SmartOS](#smart-os)
- [Home Server - Personal Cloud](#homeserver-personalcloud)
    - [Umbrel](#umbrel) 
    - [CasaOS](#casa-os)
- [Collaboration Platforms - Project Management - ERP - CRM](#colab-erp-crm)
    - [Zulip](#zulip)
    - [Element](#element)
    - [Nextcloud](#nextcloud)
    - [Mattermost](#mattermost)
    - [Kanboard](#kanboard)
    - [WeKan](#wekan)
    - [OpenProject](#openproject)
    - [Redmine](#redmine)
    - [ERPNext](#erp-next)
    - [SuiteCRM](#suite-crm)
- [Social Networking - Chatting - Self-hosted Media Platforms - Youtube/Dailymotion Alternatives](#socials)
    - [mastodon](#mastodon)
    - [Pleroma](#pleroma)
    - [Diaspora](#diaspora)
    - [friendica](#friendica)
    - [PeerTube](#peertube)
    - [Funkwhale](#funkwhale)
    - [Jitsi Meet](#jitsi-meet)
- [Productivity - Office](#productivity-office)
    - [ONLYOFFICE](#only-office)
    - [TagSpaces](#tag-spaces)
    - [Baserow](#baserow)
    - [Firefly III](#firefly-iii)
    - [Turtl](#turtl)
    - [Standard Notes](#standard-notes)
    - [Notesnook](#notesnook)
    - [Xournal++](#xournalpp)
    - [Bookstack](#bookstack)
    - [Penpot](#penpot)
    - [Wallabag](#wallabag)
- [NAS](#nas)
    - [TrueNas](#true-nas)
    - [openmediavault](#openmediavault)
<br><br><br>
--------------------

<h2 id="oss-operating-systems" align="center">OSS OPERATING SYSTEMS</h2>

<br><br>
<h3 id="serenity-os"> SERENITYOS </h3>

>Links: <div><a href="https://www.serenityos.org"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/SerenityOS/serenity"><img src="/images/git_hub-logo.png" height="72" /></a></div>

SerenityOS is a free and open source desktop operating system that has been in continuous development since 2018. Initially the one-man project of Swedish programmer Andreas Kling, SerenityOS is now developed by a community of hobbyists.

The system supports the x86-64 instruction set, features a preemptive kernel, and hosts multiple complex applications including its own web browser and integrated development environment (IDE)

SerenityOS aims to be a modern Unix-like operating system, with a look and feel that emulates 1990s operating systems such as Microsoft Windows and Mac OS. Incorporating third-party code into the system is discouraged.

The web browser for instance, does not use a preexisting web engine such as WebKit, instead using its own known as LibWeb. There is a collection of ported software, such as GCC, Git and Doom, with varying levels of functionality.

Development does not adhere to a release cycle; as such, there are no releases. Additionally, no binary distributions are provided and prospects are expected to build the system from source.

The system is written in what the authors call "Serenity C++", a variant of C++ that lacks exceptions and features its own standard library.
<div align="center"> <img src="/images/serenity-os.png" width="800" /> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="kolibri-os"> KOLIBRIOS </h3>

>Links: <div><a href="https://kolibrios.org/en/"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/KolibriOS"><img src="/images/git_hub-logo.png" height="72" /></a></div>

Colibri is a tiny yet incredibly powerful and fast operating system. Requires only a few megabyte disk space and 8MB of RAM to run. Kolibri features a rich set of applications that include word processor, image viewer, graphical editor, web browser and well over 30 exciting games. Full FAT12/16/32 support is implemented, as well as read-only support for NTFS, ISO9660 and Ext2/3/4. Drivers are written for popular sound, network and graphics cards.

Applications that start instantly, immediately after clicking an icon, without annoying hourglass pointers. This speed is achieved since the core parts of KolibriOS (kernel and drivers) are written entirely in FASM assembly language
<div align="center"> <img src="/images/KolibriOS.png" width="800" /> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="illumos"> ILLUMOS </h3>

>Links: <div><a href="https://www.illumos.org"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/illumos/illumos-gate"><img src="/images/git_hub-logo.png" height="72" /></a></div>

illumos is a Unix operating system which provides next-generation features for downstream distributions, including advanced system debugging, next generation filesystem, networking, and virtualization options.
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="open-indiana"> OPENINDIANA </h3>

>Links: <div><a href="https://www.openindiana.org"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/openindiana"><img src="/images/git_hub-logo.png" height="72" /></a></div>

OpenIndiana is a free and open-source illumos distribution descended from UNIX System V Release 4 via the OpenSolaris operating system. Forked from OpenSolaris after OpenSolaris was discontinued by Oracle Corporation
<div align="center"> <img src="/images/OpenIndiana.png" width="800" /></div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="Haiku"> HAIKU </h3>

>Links: <div><a href="https://www.haiku-os.org"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://git.haiku-os.org"><img src="/images/git_share.png" height="72" /></a></div>

Haiku is an open source operating system under constant development. Specifically targeting personal computing, Haiku is a fast, efficient, simple to use, easy to learn, and yet very powerful system for computer users of all levels.

Additionally, Haiku offers something over other open source platforms which is quite unique: The project consists of a single team writing everything from the kernel, drivers, userland services, tool kit, and graphics stack to the included desktop applications and preflets

The key highlights that distinguish Haiku from other operating systems include:

- Specific focus on personal computing
- Custom kernel designed for responsiveness
- Fully threaded design for great efficiency with multi-processor/core CPUs
- Rich object-oriented API for faster development
- Database-like file system (BFS) with support for indexed metadata
- Unified, cohesive interface
<div align="center"> <img src="/images/maxresdefault.jpg" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br><br>
<h2 id="virtualization" align="center">VIRTUALIZATION</h2>
<br><br>
<h3 id="proxmox"> PROXMOX VIRTUAL ENVIRONMENT </h3>

>Links: <div><a href="https://www.proxmox.com/en/proxmox-virtual-environment/overview"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://git.proxmox.com"><img src="/images/git_share.png" height="72" /></a></div>

Proxmox Virtual Environment (Proxmox VE or PVE) is a hyper-converged infrastructure open-source software. It is a hosted hypervisor that can run operating systems including Linux and Windows on x64 hardware.

It is a Debian-based Linux distribution with a modified Ubuntu LTS kernel and allows deployment and management of virtual machines and containers. Proxmox VE includes a web console and command-line tools, and provides a REST API for third-party tools.

Two types of virtualization are supported: container-based with LXC (starting from version 4.0 replacing OpenVZ used in version up to 3.4, included, and full virtualization with KVM. It includes a web-based management interface.

Is described as 'complete and easy to use Open Source virtualization platform for running Virtual Appliances and Virtual Machines. Proxmox VE tightly integrates KVM hypervisor and LXC containers, software-defined storage and networking

functionality on a single' and is a very popular Virtualization tool in the network & admin category
<div align="center"> <img src="/images/proxmox.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="xen-project"> XEN PROJECT </h3>

>Links: <div><a href="https://xenproject.org"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://xenbits.xen.org/gitweb/?p=xen.git"><img src="/images/git_share.png" height="72" /></a><a href="https://github.com/xen-project/xen"><img src="/images/git_hub-logo.png" height="72" /></a></div>

Powerful open source industry standard for virtualization. It is a native (bare-metal) hypervisor providing services that allow multiple computer operating systems to execute on the same computer hardware concurrently.
<div align="center"> <img src="/images/xen.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="smart-os"> SMARTOS </h3>

>Links: <div><a href="https://www.tritondatacenter.com/smartos"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/TritonDataCenter/smartos-live"><img src="/images/git_hub-logo.png" height="72"/></a></div>

SmartOS is a specialized Type 1 Hypervisor platform based on Illumos. It supports two types of virtualization:

OS Virtual Machines (Zones): A light-weight virtualization solution offering a complete and secure userland environment on a single global kernel, offering true bare metal performance and all the features Illumos has, namely dynamic introspection via DTrace

KVM Virtual Machines: A full virtualization solution for running a variety of guest OS's including Linux, Windows, *BSD, Plan9 and more

SmartOS is a "live OS", it is always booted via PXE, ISO, or USB Key and runs entirely from memory, allowing the local disks to be used entirely for hosting virtual machines without wasting disks for the root OS. This architecture has a variety of advantages including increased security, no need for patching, fast upgrades and recovery.
<div align="center"> <img src="/images/smartos.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br><br>
<h2 id="homeserver-personalcloud" align="center">HOME SERVER - PERSONAL CLOUD</h2>
<br><br>
<h3 id="umbrel"> UMBREL </h3>
  
>Links: <div><a href="https://umbrel.com"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/getumbrel/umbrel"><img src="/images/git_hub-logo.png" height="72"/></a></div>

An OS for running a server in your home. Self-host open source apps like Nextcloud, Bitcoin/Lightning node, and more.

- De-google yourself
- Run your private cloud with Nextcloud
- Run your own node and achieve unparalleled privacy by connecting your wallet directly to your Bitcoin node. This ensures that your wallet company can’t spy on your transactions, or worse — lie to you.
<div align="center"> <img src="/images/umbrel.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="casa-os"> CASAOS </h3>

>Links: <div><a href="https://casaos.io"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/IceWhaleTech/CasaOS"><img src="/images/git_hub-logo.png" height="72"/></a></div>

Community-based open source software focused on delivering simple home cloud experience around Docker ecosystem.

Democratizing data and giving service control back to your hands.

Project CasaOS started as a community-based open-source project focused on delivering a simple home cloud experience around the Docker ecosystem. CasaOS aims to redefine the private cloud digital experience for creators and developers through data democratization and enabling everyone to take that goal to a new scale.
<div align="center"> <img src="/images/casaos.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br><br>
<h2 id="colab-erp-crm" align="center">COLLABORATION PLATFORMS - PROJECT MANAGEMENT - ERP - CRM</h2>
<br><br>
<h3 id="zulip"> ZULIP </h3>

>Links: <div><a href="https://zulip.com"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/zulip/zulip"><img src="/images/git_hub-logo.png" height="72"/></a></div>

Powerful group chat, with threaded conversations

Running a Zulip server, Self-host Zulip directly on Ubuntu or Debian Linux, in Docker

Zulip is the only modern team chat app that is designed for both live and asynchronous conversations. Zulip topics create a separate space for each discussion, so different conversations will never get in each other's way. Teams of all sizes rely on Zulip - Fortune 500 companies, open-source projects, startups, and many others. Zulip is 100% open-source enterprise-grade software, self-hosted or in the cloud.

Zulip can transform how your organization communicates:

- Leaders can prioritize their time and batch-reply to messages, and thus effectively participate in the chat community.
- More discussions can be moved from meetings and email to chat.
- Individual contributors can do focused work instead of paging through GIFs making sure they don’t miss anything important.
- Remote workers can participate in an equal way to people present in person.
- Employees don’t need to be glued to their keyboard or phone in order to avoid missing out on important conversations.
<div align="center"> <img src="/images/zulip.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="element"> ELEMENT </h3>

>Links: <div><a href="https://element.io"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/element-hq"><img src="/images/git_hub-logo.png" height="72"/></a></div>

A platform for the entire workforce. A consumer-feel messaging app for those on the frontline. A desktop collaboration tool for those in the office or at home.

Element is a Matrix-based end-to-end encrypted (E2EE) secure collaboration and messaging app.

It provides instant messaging, voice and video calls, screen sharing and file sharing; for 1:1s to huge chat rooms. It’s available to use across Web, Android, iOS, macOS, Windows & Linux.

Its decentralized design delivers digital sovereignty, enabling deployment on-premise or through any cloud provider.

To host your own copy of Element, the quickest bet is to use a pre-built released version of Element:

- Download the latest version from https://github.com/vector-im/element-web/releases
- Untar the tarball on your web server
- Move (or symlink) the element-x.x.x directory to an appropriate name
- Configure the correct caching headers in your webserver (see below)
- Configure the app by copying config.sample.json to config.json and modifying it. See the configuration docs for details.
- Enter the URL into your browser and log into Element!
<div align="center"> <img src="/images/element.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="nextcloud"> NEXTCLOUD </h3>

>Links: <div><a href="https://nextcloud.com"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/nextcloud"><img src="/images/git_hub-logo.png" height="72"/></a></div>

Regain control over your data

Nextcloud Hub integrates the four key Nextcloud products Files, Talk, Groupware and Office into a single platform, optimizing the flow of collaboration.

Nextcloud is a suite of client-server software for creating and using file hosting services. Nextcloud provides functionally similar to Dropbox, Office 365 or Google Drive when used with integrated office suites Collabora Online or OnlyOffice. It can be hosted in the cloud or on-premises. It is scalable from home office software based on the low-cost Raspberry Pi all the way through to full sized data centers that support millions of users
<div align="center"> <img src="/images/nextcloud.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="mattermost"> MATTERMOST </h3>

>Links: <div><a href="https://mattermost.com"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/mattermost"><img src="/images/git_hub-logo.png" height="72"/></a></div>

Mattermost is an open source alternative to Slack.

Mattermost is a secure, open source platform for communication, collaboration, and workflow orchestration across tools and teams.

As an alternative to proprietary SaaS messaging, Mattermost brings all your team communication into one place, making it searchable and accessible anywhere. It’s written in Golang and React and runs as a production-ready Linux binary under an MIT license with either MySQL or Postgres.
<div align="center"> <img src="/images/mattermost.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="kanboard"> KANBOARD </h3>

>Links: <div><a href="https://kanboard.org"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/kanboard"><img src="/images/git_hub-logo.png" height="72"/></a></div>

Kanboard is a free and open source Kanban project management software.

Kanboard is a simple visual task board software.

There is no fancy user interface, Kanboard focus on simplicity and minimalism. The number of features is voluntary limited.

- Visualize your work
- Limit your work in progress to focus on your goal
- Drag and drop tasks to manage your project
- Self-hosted
- Super simple installation
<div align="center"> <img src="/images/kanboard.gif" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="wekan"> WEKAN </h3>

>Links: <div><a href="https://wekan.github.io"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/wekan"><img src="/images/git_hub-logo.png" height="72"/></a></div>

Wekan is an open-source and collaborative kanban board application.

Wekan, formerly LibreBoard, is an open-source and collaborative Trello icon Trello -like kanban board application.
<div align="center"> <img src="/images/wekan.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="openproject"> OPENPROJECT </h3>

>Links: <div><a href="https://www.openproject.org"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/opf/openproject"><img src="/images/git_hub-logo.png" height="72"/></a></div>

OpenProject is an open source software for project management with a wide set of features and plugins and an active international community.

It supports project timelines / Gantt charts, issue tracking, wiki, document management, time and cost reporting, code management, Scrum and much more.

OpenProject can be installed on-premises in your own infrastructure, having full control and 100% data ownership. You know where your data is stored and what happens to it, without external influence.

OpenProject is a web-based project management software. Its key features are:

- Project planning and scheduling
- Product roadmap and release planning
- Task management and team collaboration
- Agile and Scrum
- Time tracking, cost reporting, and budgeting
- Bug tracking
- Wikis
- Forums
- Meeting agendas and meeting minutes
<div align="center"> <img src="/images/openproject.jpg" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="redmine"> REDMINE </h3>

>Links: <div><a href="https://www.redmine.org/projects/redmine"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://svn.redmine.org/redmine/"><img src="/images/source_repo.png" height="72"/></a></div>

Flexible project management web application

Redmine is a flexible project management web application. Written using Ruby on Rails framework, it is cross-platform and cross-database.

It integrates with a number of different SCM:s including Subversion and Git. It has multi language support and can be extended with the help of plugins.

- Multiple projects support
- Flexible role-based access control
- Flexible issue tracking system
- Gantt chart and calendar
- News, documents & files management
- Feeds & email notifications
- Per project wiki
- Per project forums
- Time tracking
- Custom fields for issues, time-entries, projects and users
- SCM integration (SVN, CVS, Git, Mercurial and Bazaar)
- Issue creation via email
- Multiple LDAP authentication support
- User self-registration support
- Multilanguage support
- Multiple databases support
<div align="center"> <img src="/images/REDMINE.jpg" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="erp-next"> ERPNEXT </h3>

>Links: <div><a href="https://erpnext.com"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/frappe/erpnext"><img src="/images/git_hub-logo.png" height="72"/></a></div>

ERPNext is a cost-effective ERP solution to run your business using on-demand, software-as-a-service platform.

Offers modules like Accounting, Sales, Purchase, Inventory, Human Resource, Projects, Production & Maintenance which are present in most of the real-world business processes.

Open source and licensed under GNU GPL v3. It's free to use on your own server. Built on Python.
<div align="center"> <img src="/images/erpnext.jpg" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="suite-crm"> SUITECRM </h3>

>Links: <div><a href="https://suitecrm.com"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/salesagility/SuiteCRM"><img src="/images/git_hub-logo.png" height="72"/></a></div>

SuiteCRM is a free open-source Customer Relationship Management application for servers that is written in PHP.

Powerful, customizable, easy to use, with hundreds of extensions and integrations, SuiteCRM is used by millions of people every day. Download and install SuiteCRM on your own server or within your development environment

SuiteCRM comprises the last release of the SugarCRM Community Edition plus the following additional modules:

- Products
- Quotes
- Contracts
- Invoices
- PDF Templates
- Workflow
- Reporting
- Search
- Events
- Google Maps
- Teams Security
- Portal
- Responsive Theme
- Outlook plugin
- Surveys

In addition to the new modules, extensive bug fixes and many enhancements to the core functionality have been made. There have been over fifty updates since the original project was released.

A six-month release cycle is maintained with bug fix and security releases being made available between major releases
<div align="center"> <img src="/images/suitecrm.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br><br>
<h2 id="socials" align="center">SOCIAL NETWORKING - CHATTING - SELF-HOSTED MEDIA PLATFORMS - YOUTUBE/DAILYMOTION ALTERNATIVES</h2>
<br><br>
<h3 id="mastodon"> MASTODON </h3>

>Links: <div><a href="https://mastodon.social/explore"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/mastodon/mastodon"><img src="/images/git_hub-logo.png" height="72"/></a></div>

Mastodon is a Social networking that's not for sale.

Your home feed should be filled with what matters to you most, not what a corporation thinks you should see. Radically different social media, back in the hands of the people.
<div align="center"> <img src="/images/mastodon.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="Pleroma"> PLEROMA </h3>

>Links: <div><a href="https://pleroma.social"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://git.pleroma.social/pleroma/"><img src="/images/git_share.png" height="72"/></a></div>

Pleroma is a free, federated social networking server built on open protocols. It is compatible with GNU Social, Mastodon, and many other ActivityPub

The project consists of several components:

Pleroma is the server implementation, and comes bundled with PleromaFE, the default frontend. Other useful utilities are also provided, such as an ActivityPub relay.

Start using Pleroma by joining an existing Pleroma instance or check the installation guide to setting up your own server.

<div align="center"> <img src="/images/pleroma.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="diaspora"> DIASPORA </h3>

>Links: <div><a href="https://diasporafoundation.org"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/diaspora/diaspora"><img src="/images/git_hub-logo.png" height="72"/></a></div>

Diaspora is a federated social networking service, designed to be a more privacy-aware alternative to Facebook icon Facebook. Share what you want, with whom you want.

Diaspora (stylized as diaspora*) is a nonprofit, user-owned, distributed social network. It consists of a group of independently owned nodes (called pods) which interoperate to form the network.

Find a pod that suits you. You might prefer a smaller pod, one which allows cross-posting to external services (such as Twitter), one based near you, or one based in a country that you know has good data security policies... The choice is yours! You can even host a pod yourself if you have some sysadmin skills.

The social network is not owned by any one person or entity, keeping it from being subject to corporate take-overs or advertising

The online social world where you are in control. based on three key philosophies:

- Decentralization
- Freedom
  You can be whoever you want to be in diaspora*. Unlike some networks, you don’t have to use your real identity. You can interact with people in whatever way you choose. The only limit is your imagination. diaspora* is also Free Software, giving you liberty over how you use it.
- Privacy
  In diaspora you own your data. You don’t sign over rights to a corporation or other interest who could use it. In addition, you choose who sees what you share, using Aspects. With diaspora*, your friends, your habits, and your content is your business ... not ours!
<div align="center"> <img src="/images/diaspora.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="friendica"> FRIENDICA </h3>

>Links: <div><a href="https://friendi.ca"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/friendica/friendica"><img src="/images/git_hub-logo.png" height="72"/></a></div>

Distributed social network. With focus on decentralization, privacy, interoperability.

Friendica is a distributed social network application. Which allow users to connect with others via their own Friendica server, but may also fully integrate contacts from other platforms including Twitter, diaspora*, Pump.io and StatusNet into their 'newsfeed'. In addition to these two-way connections, users can also use Friendica as a publishing platform to post content to Google+, Google Buzz, WordPress, Tumblr, GNU-social, and Libertree. The list of supported networks is growing. In addition, e-mail contacts and RSS feeds can be integrated.

The developers argue that decentralization on small servers is a key condition for the freedom of users and their self-determination.

There are two options to choose from to try Friendica:

The first option is to join one of the already installed Friendica server listed at http://dir.friendica.social/servers

The second option is to install your own server at https://github.com/friendica/friendica/releases Both options are fully free.

Friendica runs on commodity hosting platforms powered by PHP/MySQL/Apache. If you can install Drupal or Wordpress you can probably install Friendica. A single Friendica installation supports up to several thousand members.
<div align="center"> <img src="/images/friendica.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="peertube"> PEERTUBE </h3>

>Links: <div><a href="https://joinpeertube.org"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/Chocobozzz/PeerTube"><img src="/images/git_hub-logo.png" height="72"/></a></div>

PeerTube is a free, decentralized and federated video platform developed as an alternative to other platforms that centralize our data and attention, such as YouTube, Dailymotion or Vimeo.

If you have a minimum amount of time and technical skills, creating your own platform (also called "instance") on your server is the best way to take advantage of PeerTube.
<div align="center"> <img src="/images/peertube.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="funkwhale"> FUNWHALE </h3>

>Links: <div><a href="https://www.funkwhale.audio"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://dev.funkwhale.audio/funkwhale"><img src="/images/git_share.png" height="72"/></a></div>

Funkwhale is a community-driven project that lets you listen and share music and audio within a decentralized, open network. It is a free libre open source software alternative to SoundCloud, which can be self-hosted.

You can browse your Music by artist, album, genre, playlist, or record label, as well as by direct searches. Funkwhale gives you access to your playlists, favorite tracks, and artists everywhere, from a web interface or the wide range of compatible apps for every platform. Funkwhale music streaming is available on all Android and iOS devices via compatible applications like DSub, and on desktop computers for unlimited duration’s.
<div align="center"> <img src="/images/funkwhale.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="jitsi-meet"> JITSI MEET </h3>

>Links: <div><a href="https://meet.jit.si"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://jitsi.org/jitsi-meet/"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/jitsi/jitsi-meet"><img src="/images/git_hub-logo.png" height="72" /></div>

Secure, fully featured, and completely free video conferencing.

Go ahead, video chat with the whole team. In fact, invite everyone you know. Jitsi Meet is a fully encrypted, 100% open source video conferencing solution that you can use all day, every day, for free — with no account needed.

- Share your desktop, presentations, and more
- Invite users to a conference via a simple, custom URL
- Edit documents together using Etherpad
- Pick fun meeting URLs for every meeting
- Trade messages and emojis while you video conference, with integrated chat.
<div align="center"> <img src="/images/JITSIMEET.jpg" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h2 id="productivity-office" align="center">PRODUCTIVITY - OFFICE</h2>

<br><br><br>
<h3 id="only-office"> ONLYOFFICE </h3>

>Links: <div><a href="https://www.onlyoffice.com"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/ONLYOFFICE"><img src="/images/git_hub-logo.png" height="72"/></a></div>

Run your private office

ONLYOFFICE offers a secure online office suite highly compatible with MS Office formats.

- View, edit, and collaborate on docs, sheets, slides
- Build fillable PDF forms and fill them in online
- Read and edit PDFs, export/import to/from PDF
- Convert docs to Markdown and HTML
- Turn your textbooks into e-books
- Generate texts with the AI helper


<div align="center"> <img src="/images/onlyoffice.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="tag-spaces"> TAGSPACES </h3>

>Links: <div><a href="https://www.tagspaces.org"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/tagspaces/tagspaces"><img src="/images/git_hub-logo.png" height="72"/></a></div>

TagSpaces is privacy aware, cross-platform file browser with note-taking capabilities. It helps you organize your files and folders with tags and colors.

Cross-platform file tagging

Organize your documents, photos, e-books, music, recipes or invoices in the same way on almost every platform. We currently support Windows, macOS, Linux and Android. With the help of tags, you can do research better or you can manage projects using the GTD methodology or you can organize your tasks in Kanban boards. The application can persists the tags in the file names and as a consequence, the tagging information is not vendor locked. The absence of a database, makes syncing of the tag meta information easy across different devices with services like Dropbox, Google Drive or Nextcloud. TagSpaces features basic file management operations, so it can be used as tag-based file manager.
<div align="center"> <img src="/images/tagspaces.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="baserow"> BASEROW </h3>

>Links: <div><a href="https://baserow.io"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://gitlab.com/baserow/baserow"><img src="/images/git_share.png" height="72"/></a><a href="https://github.com/bram2w/baserow"><img src="/images/git_hub-logo.png" height="72"/></a></div>

Baserow organizes all your data into tables that are easy to create, collaborate on and look through. When there’s one database for all workflows running in your company, everyone knows exactly where to look for what.

Open source no-code database and Airtable alternative

Create your own online database without technical experience. Our user-friendly no-code tool gives you the powers of a developer without leaving your browser.

Self-hosted: Host your own instance on-premise or in the cloud
<div align="center"> <img src="/images/baserow.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="firefly-iii"> FIREFLY III </h3>

>Links: <div><a href="https://www.firefly-iii.org"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/firefly-iii"><img src="/images/git_hub-logo.png" height="72"/></div>

Financial manager. It can help you keep track of expenses, income, budgets and everything in between. It even supports credit cards, shared household accounts and savings accounts! It’s pretty fancy. You should use it to save and organize money.

Personal financial management is pretty difficult, and everybody has their own approach to it. Some people make budgets, other people limit their cashflow by throwing away their credit cards, others try to increase their current cashflow. There are tons of ways to save and earn money.
<div align="center"> <img src="/images/fireflyiii.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="turtl"> TURTL </h3>

>Links: <div><a href="https://turtlapp.com"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/turtl"><img src="/images/git_hub-logo.png" height="72"/></div>

A secure, collaborative notebook

Whether it's bookmarks or passwords, files or shopping lists...Turtl organizes it all and makes it easy to find later. Sync across your devices. Leave nothing behind.

Turtl uses high-end cryptography to protect your data. Whether you're worried about information leaks, competitive advantage, or blanket government surveillance, Turtl works hard to make sure only you, and those you choose, can see your data.

Want more control of your data? Install your own Turtl server at home or at work.
<div align="center"> <img src="/images/turtl-desktop-application.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="standard-notes"> STANDARDNOTES </h3>

>Links: <div><a href="https://standardnotes.com"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/standardnotes/app"><img src="/images/git_hub-logo.png" height="72"/></div>

Standard Notes helps you gain control in a world that often feels out of control. Protect your life's work with end-to-end encryption, advanced security, and unmatched privacy controls.
- App:End-to-end encrypted notes app
- Server ecosystem for Standard Notes; fully self-hostable
<div align="center"> <img src="/images/standard-notes.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="notesnook"> NOTESNOOK </h3>

>Links: <div><a href="https://notesnook.com"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/streetwriters/notesnook"><img src="/images/git_hub-logo.png" height="72"/></div>

Open source zero knowledge private note taking. Write notes with freedom, no spying, no tracking.

An end-to-end encrypted note taking alternative to Evernote
<div align="center"> <img src="/images/notesnook.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="xournalpp"> XOURNAL++ </h3>

>Links: <div><a href="https://xournalpp.github.io"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/xournalpp/xournalpp"><img src="/images/git_hub-logo.png" height="72"/></div>

Xournal++ is a hand note taking software written in C++ with the target of flexibility, functionality and speed.
<div align="center"> <img src="/images/xournalpp.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="bookstack"> BOOKSTACK </h3>

>Links: <div><a href="https://www.bookstackapp.com"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/BookStackApp/BookStack"><img src="/images/git_hub-logo.png" height="72"/></div>

BookStack is a simple, self-hosted, easy-to-use platform for organizing and storing information.

Documentation/wiki software aimed for a simple, self-hosted, and easy-to-use platform. Based on Laravel, a PHP framework, BookStack is released under the MIT License. It uses the ideas of books to organise pages and store information
<div align="center"> <img src="/images/bookstack.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="Penpot"> PENTOP </h3>

>Links: <div><a href="https://penpot.app"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/penpot/penpot"><img src="/images/git_hub-logo.png" height="72"/></div>

Penpot is the first open-source design and prototyping tool meant for Product teams.
<div align="center"> <img src="/images/penpot.jpg" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="wallabag"> WALLABAG </h3>

>Links: <div><a href="https://wallabag.org"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/wallabag/wallabag"><img src="/images/git_hub-logo.png" height="72"/></div>

wallabag is a self hostable application for saving web pages: Save and classify articles. Read them later.

- wallabag extracts the article's content (and only its content!) and displays it in a comfortable view
- If you're a developer and you want to connect your application to wallabag, we offer you an API.
- You can use wallabag on your computer, thanks to our web application. But you can also take wallabag everywhere. For example, it's possible to save an article on your laptop at work, start to read it on your smartphone in the subway and finish reading it on your ereader in your bed.
<div align="center"> <img src="/images/wallabag.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h2 id="nas" align="center">NAS</h2>
<br><br>
<h3 id="true-nas"> TRUENAS </h3>

>Links: <div><a href="https://www.truenas.com"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/truenas"><img src="/images/git_hub-logo.png" height="72"/></div>

(formerly FreeNAS) is a free NAS (Network-Attached Storage) server, supporting: CIFS (samba), FTP, NFS, AFP, RSYNC, iSCSI protocols, S.M.A.R.T., local user authentication, Software RAID (0,1,5) with a Full WEB configuration interface.

- File Sharing: TrueNAS allows you to create and manage network file shares using popular protocols like SMB/CIFS (for Windows), NFS (for Unix-like systems), and AFP (for macOS). These file shares can be accessed by multiple clients on the network simultaneously.
- Storage Management: TrueNAS provides a user-friendly web interface for managing various storage configurations, including disk pools (ZFS pools), RAID arrays, disk encryption, snapshots, and replication.
- Data Protection: TrueNAS leverages the robust ZFS file system, which offers features like data integrity, snapshots, and replication for backup and recovery purposes.
- Virtualization: TrueNAS includes support for running virtual machines (VMs) using bhyve (FreeBSD's hypervisor) or integrating with other virtualization solutions like Kubernetes and Docker.
- Cloud Integration: TrueNAS can integrate with various cloud storage services, such as Amazon S3, Microsoft Azure, and Google Cloud, enabling cloud backup, replication, and data transfer
- Plugins and Jails: TrueNAS supports plugins and FreeBSD jails, which allow users to install and run additional software or services on the NAS system, such as media servers, web servers, or backup tools.
- High Availability: TrueNAS can be configured for high availability setups, ensuring data redundancy and minimizing downtime in case of hardware failures.
<div align="center"> <img src="/images/true-nas.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
<h3 id="openmediavault"> OPENMEDIAVAULT </h3>

>Links: <div><a href="https://www.openmediavault.org"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/openmediavault"><img src="/images/git_hub-logo.png" height="72"/></div>

OpenMediaVault is the next generation network attached storage (NAS) solution based on Debian Linux. It contains services like SSH, (S)FTP, SMB/CIFS, DAAP media server, RSync, BitTorrent client and many more.

Thanks to the modular design of the framework it can be enhanced via plugins.

OpenMediaVault is primarily designed to be used in home environments or small home offices, but is not limited to those scenarios. It is a simple and easy to use out-of-the-box solution that will allow everyone to install and administrate a Network Attached Storage without deeper knowledge.
<div align="center"> <img src="/images/openmediavault.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
