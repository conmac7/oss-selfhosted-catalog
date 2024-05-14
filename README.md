<a id="top"></a><h1 align="center"> Open Source & Self-Hosted Catalog </h1>

<div align="center"> <img src="/images/Open_Source_Initiative.png" width="240" /> </div>
<div align="center"> <font size="5">This work is titled Open Source Initiative , created by Colin Viebrock licensed under CC BY 2.5 https://creativecommons.org/licenses/by/2.5/</font></div>

This is a curated collection of open-source and self-hosted software programs. This catalog serves as a comprehensive guide, featuring a title, an image, and a concise description for each listed software. 

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
- [OSS Self-Hosted](#oss-Self-hosted)
- [Home Server - Personal Cloud](#homeserver-personalcloud)
    - [Umbrel](#Umbrel)
    - [CasaOS](#casa-os)
    - [Nextcloud](#next-cloud)
- [Collaboration Platforms - Project Management - ERP- CRM](#colab-projectmngmt-erp-crm)
    - [Nextcloud](#next-cloud)
- [OSS](#oss)


--------------------

<h1 id="oss-operating-systems" align="center">OSS OPERATING SYSTEMS</h1>
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
