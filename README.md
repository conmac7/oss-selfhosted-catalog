<a id="top"></a><h1 align="center"> Open Source & Self-Hosted Catalog </h1>

<div align="center"> <img src="/images/Open_Source_Initiative.png" width="240" /> </div>

This is a curated collection of open-source and self-hosted software programs. This catalog serves as a comprehensive guide, featuring a title, corresponding links(homepage, github, git), a concise description and an image for each listed software. 

It aims to provide an organized and informative resource primarily for enthusiasts, home servers, homelabs, and end-users who value their privacy and security, and are seeking to explore and adopt various open-source and self-hosted solutions across different domains and use cases.

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
    - [Element](#element)
    - [Nextcloud](#nextcloud)
    - [Mattermost](#mattermost)
    - [Kanboard](#kanboard)
    - [WeKan](#wekan)
    - [OpenProject](#openproject)
    - [Redmine](#redmine)
    - [ERPNext](#erp-next)
    - [SuiteCRM](#suite-crm)
<br><br>
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

Colibri is a tiny yet incredibly powerful and fast operating system. This power requires only a few megabyte disk space and 8MB of RAM to run. Kolibri features a rich set of applications that include word processor, image viewer, graphical editor, web browser and well over 30 exciting games. Full FAT12/16/32 support is implemented, as well as read-only support for NTFS, ISO9660 and Ext2/3/4. Drivers are written for popular sound, network and graphics cards.

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
<div align="center"> <img src="/images/OpenIndiana.png" width="800" />&nbsp;&nbsp;&nbsp;<a href="#top"><img src="/images/back-to-top__.png" width="16" /></a>  </div>
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
<h3 id="casa-os"> CASAOS </h3><br><br><br>
<h2 id="oss-operating-systems" align="center">OSS OPERATING SYSTEMS</h2>
>Links: <div><a href="https://casaos.io"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/IceWhaleTech/CasaOS"><img src="/images/git_hub-logo.png" height="72"/></a></div>

Community-based open source software focused on delivering simple home cloud experience around Docker ecosystem.

Democratizing data and giving service control back to your hands.

Project CasaOS started as a community-based open-source project focused on delivering a simple home cloud experience around the Docker ecosystem. CasaOS aims to redefine the private cloud digital experience for creators and developers through data democratization and enabling everyone to take that goal to a new scale.
<div align="center"> <img src="/images/casaos.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br><br>
<h2 id="colab-erp-crm" align="center">COLLABORATION PLATFORMS - PROJECT MANAGEMENT - ERP - CRM</h2>
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
