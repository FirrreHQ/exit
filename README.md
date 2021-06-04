# Project Firrre - Discontinued

Dear all,

First and foremost, I would like to take this opportunity to sincerely apologize for not providing ample updates on this project, and being inactive from IRC for some time, for personal reasons.

As of the last update titled *[Fiery Announcement](https://telegra.ph/Fiery-Announcement-06-15)* on June 15th 2019 &mdash; the project went on a steep decline, ending up in the official discontinuation of the project (with a heavy heart).

### Background as to what transpired and contributing factors
This project was initiated back in late 2013. The motive was to provide [Free Open Source Software (FOSS)](https://en.wikipedia.org/wiki/Free_and_open-source_software) projects (both developers and supporters) free hosted [Internet Relay Chat bouncer (proxy)](https://en.wikipedia.org/wiki/BNC_(software)) accounts. It took off slowly on [freenode](https://freenode.net/) IRC. However, as of late 2017 to early 2019, truth be told, there was a decline in our user base, utilizing our service. From the interactions, some choose to opt-in to host their IRC bouncers on their own and have full access to their chat logs, including utilizing bouncers on other networks (non-FOSS IRC networks), usage of personal [Reverse DNS (vhost)](https://en.wikipedia.org/wiki/Reverse_DNS_lookup), etc. These are some of the reasons given, which is understandable.

Later on, I ran into various issues, on the server level, in which to resolve it, was to re-build many aspects, including the OS. Taking into account that there were a total of 8 to 9 servers.

Examples: 

- OS required an upgrade from legacy version; [Debian](https://www.debian.org/) to [Gentoo](https://www.gentoo.org/) or [FreeBSD](https://www.freebsd.org/) was in the pipeline too
- Upgrade the primary server from an [OpenVZ](https://openvz.org/) to [KVM](https://www.linux-kvm.org/page/Main_Page) machine; a huge migration undertaking, web server, database, etc
- Around ~10 IPv4's and ~500 IPv6's will need to be reconfigured; including updating the rDNS entries and DNS-level changes; there were plans to downsize the amount of IPv6 too
- The bouncer software required an upgrade, but, to do so, the in-house web panel will be required to be rewritten prior, to support newer features and security fixes
- Web panel redesign was in the pipeline; planned to move away from [TukTukFramework](https://github.com/soyjavi/tuktuk) to an in-house, build-from-scratch, minimalist CSS framework
- Main website software redevelopment was in the pipeline; planned to explore [Jamstack](https://jamstack.org/what-is-jamstack/) 
- The issue with the Secure Socket Layer (SSL) software library and sorting out with the SSL provider on issuing the wildcard certificate before it expired; eventually expiring and was not able to fix some library issues; requires an OS upgrade
- And few minor issues that required extensive troubleshooting

Those who got to know me from IRC would be informed that this project is fully undertaken and maintained by myself (one-man show [sadly]). Therefore, this undertaking would require a ton of time and mental capacity, which at that point, I was not able to commit, due to personal reasons. Exhausting period juggling with life and full-time work in the IT industry, while keeping sane.

There were interested parties who contacted me regarding a possible acquisition of the project, however, I had to turn them down, as this project had never been about monetary gain, nor having a corporate entity running the project (*For the enthusiasts, by the enthusiasts*). It was build to serve the FOSS community in a small way.

This project helped me sharpen my knowledge in managing servers, networking, programming, and scripting. Including a better understanding of the various IRC specifications. I am glad that there is an [IRCv3 Working Group](https://ircv3.net/) comprising of bunch of talented people who helped developed various tools and applications, including the bouncer software that was utilize for this project ([ZNC](https://wiki.znc.in/ZNC)) that are helping to better the protocol and implementing useful features. I was fortunate to have had the opportunity to meet many developers and passionate members who are steadfast supporters of FOSS and the IRC protocol. It was awe-inspiring to get to know of their experiences in the Information Technology, Free Open Source Software, and Internet Relay Chat world via interacting with them on IRC.

A big thank you to all our members and sponsors, would not have been able to do it without your support and understanding thought out this rough yet tremendous journey.

Keep safe during this awful Covid-19 (SARS-CoV-2) period and try to keep your mental fitness at 100.
<br><br><br>
Best Regards,
<br>Isaiah Nathanael (admin)
