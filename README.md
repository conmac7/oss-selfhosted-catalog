<a id="top"></a><h1 align="center"> Open Source & Self-Hosted Catalog </h1>

<div align="center"> <img src="/images/Open_Source_Initiative.png" width="240" /> </div>

This is a curated collection of open-source and self-hosted software programs. This catalog serves as a comprehensive guide, featuring a title, corresponding links(homepage, github, git),a concise description and an image for each listed software. 

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
<h3 id="casa-os"> CASAOS </h3>

>Links: <div><a href="https://casaos.io"><img src="/images/web_homepage-icon.png" height="72" /></a><a href="https://github.com/IceWhaleTech/CasaOS"><img src="/images/git_hub-logo.png" height="72"/></a></div>

Community-based open source software focused on delivering simple home cloud experience around Docker ecosystem.

Democratizing data and giving service control back to your hands.

Project CasaOS started as a community-based open-source project focused on delivering a simple home cloud experience around the Docker ecosystem. CasaOS aims to redefine the private cloud digital experience for creators and developers through data democratization and enabling everyone to take that goal to a new scale.
<div align="center"> <img src="/images/casaos.png" width="800" /></a> </div>
<div align="center"><a href="#top"><img src="/images/back-to-top_v1.png" width="120" /></div>
<br><br>
