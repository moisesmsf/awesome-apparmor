# Awesome AppArmor
> A curated list of awesome things related to [AppArmor](https://apparmor.net/).

## Contents

- [Official Resources](#official-resources)
- [AppArmor at Kernel](#apparmor-at-kernel)
- [AppArmor at GNU\Linux Distributions](#apparmor-at-gnulinux-distributions)
- [apparmor.d Project](#apparmord-project)
- [Related Projects](#related-projects)
- [Articles](#articles)
- [Videos and Presentations](#videos-and-presentations)

---

### Official Resources

- [AppArmor Website](https://apparmor.net/)
- [AppArmor News](https://apparmor.net/news/)
- [AppArmor Mailing List](https://lists.ubuntu.com/mailman/listinfo/apparmor)
- AppArmor IRC Channel: **#apparmor** on [irc.oftc.net](https://irc.oftc.net)
- [AppArmor Wiki](https://gitlab.com/apparmor/apparmor/-/wikis/home)
- [AppArmor Documentation](https://gitlab.com/apparmor/apparmor/-/wikis/Documentation)
- [AppArmor Repo](https://gitlab.com/apparmor/apparmor)
- [AppArmor Website Repo](https://gitlab.com/apparmor/apparmor.net)
- [AppArmor Release](https://gitlab.com/apparmor/apparmor/-/releases)

---

### AppArmor at Kernel

- [AppArmor - Kernel Andmin Guide](https://docs.kernel.org/admin-guide/LSM/apparmor.html)
- [AppArmor Kernel Module Repo](https://git.kernel.org/pub/scm/linux/kernel/git/jj/linux-apparmor.git/)
- [LSM Patchwork](https://patchwork.kernel.org/project/linux-security-module/list/)
- [Linux ABI description](https://docs.kernel.org/admin-guide/abi.html)

---

### AppArmor at GNU\Linux Distributions

- AppArmor at Ubuntu
    - [AppArmor Ubuntu Repo](https://code.launchpad.net/ubuntu/+source/apparmor)
    - [AppArmor Ubuntu Wiki](https://wiki.ubuntu.com/AppArmor)
    - [AppArmor Ubuntu package](https://launchpad.net/ubuntu/+source/apparmor)
    - [AppArmor Ubuntu package - Bugs](https://bugs.launchpad.net/ubuntu/+source/apparmor)
    - [AppArmor Ubuntu Server Doc](https://documentation.ubuntu.com/server/how-to/security/apparmor/)
    - [AppArmor Ubuntu Community Wiki](https://help.ubuntu.com/community/AppArmor)
    - [AppArmor Ubuntu Tutorial](https://ubuntu.com/tutorials/beginning-apparmor-profile-development)
    - [Debugging AppArmor Ubuntu Wiki](https://wiki.ubuntu.com/DebuggingApparmor)
    - [Understanding AppArmor User Namespace Restriction](https://discourse.ubuntu.com/t/understanding-apparmor-user-namespace-restriction/58007)
    - [Ubuntu Desktop’s 24.10 Dev Cycle - Part 5: Introducing Permissions Prompting](https://discourse.ubuntu.com/t/ubuntu-desktop-s-24-10-dev-cycle-part-5-introducing-permissions-prompting/47963)
- AppArmor at Debian:
    - [AppArmor Debian Repo](https://salsa.debian.org/apparmor-team/apparmor)
    - [AppArmor Debian Wiki](https://wiki.debian.org/AppArmor)
    - [AppArmor Debian Package](https://tracker.debian.org/pkg/apparmor)
    - [AppArmor Debian Package Mailing List](https://alioth-lists.debian.net/cgi-bin/mailman/listinfo/pkg-apparmor-team)
    - [Report from the AppArmor BoF at DebConf18](https://people.debian.org/~intrigeri/blog/posts/Report:_AppArmor_BoF_at_DebConf18/)
    - [Let's enable AppArmor by default (why not?) - Debian Devel Mailing List](https://lists.debian.org/debian-devel/2017/08/msg00090.html)
- AppArmor at OpenSuse:
    - [AppArmor Geeks](https://en.opensuse.org/SDB:AppArmor_geeks)
    - [AppArmor - Security and Hardening Guide](https://doc.opensuse.org/documentation/leap/security/html/book-security/part-apparmor.html)
    - [Announcement: SELinux as default MAC system on new Tumbleweed installations](https://lists.opensuse.org/archives/list/factory@lists.opensuse.org/thread/G3W5NIY3OKRBHPHWTPYEUPSS4LKZN77N/)
    - [RFC: SELinux as default MAC system on new Tumbleweed installations](https://lists.opensuse.org/archives/list/factory@lists.opensuse.org/thread/YN4TCBCU4A2V5G2MWR5EWYF46267BO7F/)
- AppArmor at ArchLinux:
    - [AppArmor ArchLinux Wiki](https://wiki.archlinux.org/title/AppArmor)
    - [AppArmor ArchLinux Package](https://archlinux.org/packages/extra/x86_64/apparmor/)
    - [AppArmor ArchLinux repo](https://gitlab.archlinux.org/archlinux/packaging/packages/apparmor)
- AppArmor at Other Distributions:
    - [AppArmor Gentoo WIki](https://wiki.gentoo.org/wiki/Security_Handbook/Linux_Security_Modules/AppArmor)
    - [AppArmor Kicksecure WIki](https://www.kicksecure.com/wiki/AppArmor)
    - [Whonix AppArmor Profiles Development Discussion - Whonix Forums](https://forums.whonix.org/t/whonix-apparmor-profiles-development-discussion/108)
    - [Application Isolation - Tails](https://tails.net/contribute/design/application_isolation)
---

### apparmor.d Project

- [apparmor.d Website](https://apparmor.pujol.io/)
- [apparmor.d Repo](https://github.com/roddhjav/apparmor.d)
- [apparmor.d Matrix Chat](https://matrix.to/#/#apparmor.d:matrix.org)
- [apparmor.d Repo](https://github.com/roddhjav/apparmor.d)
- apparmor.d Presentations
    - Linux Security Summit North America 2023: [Slide](https://lssna2023.sched.com/event/1K7bI/building-the-largest-working-set-of-apparmor-profiles-alexandre-pujol-the-collaboratory-tudublin); [Video](https://www.youtube.com/watch?v=OzyalrOzxE8)
    - Ubuntu Summit 2023: [Slide](https://events.canonical.com/event/31/contributions/209/); [Video](https://www.youtube.com/watch?v=GK1J0TlxnFI)
- [apparmor.d Play Machine](https://play.pujol.io/)

---

### Related Projects

- [Kubernetes Security Profiles Operator - Github](https://github.com/kubernetes-sigs/security-profiles-operator) - The Security Profiles Operator (SPO) is an out-of-tree Kubernetes enhancement which aims to make it easier to create and use SELinux, seccomp and AppArmor security profiles in Kubernetes clusters.
- [apparmor-psp-policy - Github](https://github.com/kubewarden/apparmor-psp-policy)
- [KubeArmor - Github](https://github.com/kubearmor/KubeArmor) - Runtime Security Enforcement System. Workload hardening/sandboxing and implementing least-permissive policies made easy leveraging LSMs (BPF-LSM, AppArmor).
- [vArmor - Github](https://github.com/bytedance/vArmor) - vArmor is a cloud native container sandbox system based on AppArmor/BPF/Seccomp.
- [AppAnvil - Github](https://github.com/jack-ullery/AppAnvil) - Graphical user interface for the AppArmor security module
- [apparmemall - Gitlab](https://gitlab.com/morfikov/apparmemall)
- [apparmor-profiles - Github](https://github.com/krathalan/apparmor-profiles) - Krathalan's AppArmor profiles for Arch Linux
- [apparmor-profiles - Sourcehut](https://git.sr.ht/~krathalan/apparmor-profiles)
- [apparmor-even-more-profiles - Github](https://github.com/komachi/apparmor-even-more-profiles)
- [bane - Github](https://github.com/genuinetools/bane) - Custom & better AppArmor profile generator for Docker containers.
- [AppArmor RBAC for Gentoo Linux - Github](https://github.com/viewizard/gentoo-apparmor)

---

### Articles
- [AppArmor - c1b3rn0t3s](https://gitblanc.github.io/c1b3rn0t3s/notes/AppArmor)
- [Three bypasses of Ubuntu's unprivileged user namespace restrictions - Qualys Security Advisory](https://www.qualys.com/2025/three-bypasses-of-Ubuntu-unprivileged-user-namespace-restrictions.txt)
- [Abusing Ubuntu 24.04 features for root privilege escalation - Snyk](https://snyk.io/blog/abusing-ubuntu-root-privilege-escalation/)
- [AppArmor security profiles for Docker - Docker Documentation](https://docs.docker.com/engine/security/apparmor/)
- [Restrict a Container's Access to Resources with AppArmor - Kubernetes Documentation](https://kubernetes.io/docs/tutorials/security/apparmor/)
- [Container Hardening Process - Hardened Linux](https://hardenedlinux.org/blog/2024-10-13-container-hardening-process/)
- [Linux Sandboxing: a brief review - Hardened Linux](https://hardenedlinux.org/blog/2024-08-20-gnu/linux-sandboxing-a-brief-review)
- [Advanced Docker Security with AppArmor - GCORE](https://gcore.com/learning/advanced-docker-security-with-apparmor)
- [What is Apparmor and how to add a security layer with it in Docker? - theodo Cloud](https://security.theodo.com/en/blog/security-docker-apparmor)
- [Securing PHP-FPM with AppArmor - FREDERIK HIMPE](https://blog.frehi.be/2024/01/06/securing-php-fpm-with-apparmor)
- [Protecting systemd services with AppArmor - FREDERIK HIMPE](https://blog.frehi.be/2024/01/04/protecting-systemd-services-with-apparmor/)
- [Protecting your Linux server against security exploits with AppArmor - FREDERIK HIMPE](https://blog.frehi.be/2023/12/25/protecting-your-linux-server-against-security-exploits-with-apparmor/)
- [A Study of Application Sandbox Policies in Linux - Trevor Dunlap, William Enck, Bradley Reaves](https://www.enck.org/pubs/dunlap-sacmat22.pdf)
- [AppArmor Profile Generator as a Cloud Service - Hui Zhu, Christian Gehrmann](https://www.scitepress.org/Papers/2021/104341/104341.pdf)
- [A Comparative Analysis of Linux Mandatory Access Control Policy Enforcement Mechanisms - Brennon Brimhall et al](https://dl.acm.org/doi/pdf/10.1145/3578357.3589454)
- [Lic-Sec: An enhanced AppArmor Docker security profile generator - Hui Zhu; Christian Gehrmann](https://www.sciencedirect.com/science/article/pii/S2214212621001435)
- [Advanced Docker Security with AppArmor - An Overview - HACKERNOON](https://hackernoon.com/advanced-docker-security-with-apparmor-an-overview-k61m3xjf)
- [Security and Access Control - APERTIS](https://www.apertis.org/guides/app_devel/apparmor/)
- [Mitigating the Damage in the Compromised Webserver using AppArmor - tbhaxor's Blog ](https://tbhaxor.com/mitigating-the-damage-in-the-compromised-webserver-using-apparmor/)
- [Confining Resources inside Docker Containers with AppArmor - tbhaxor's Blog ](https://tbhaxor.com/confining-resources-inside-docker-containers-with-apparmor/)
- [Writing AppArmor Profile from Scratch - tbhaxor's Blog ](https://tbhaxor.com/writing-apparmor-profile-from-scratch/)
- [AppArmor - HackTricks ](https://book.hacktricks.wiki/en/linux-hardening/privilege-escalation/docker-security/apparmor.html)
- [Securing containers with AppArmor - Google Cloud Container-Optimized OS Guides](https://cloud.google.com/container-optimized-os/docs/how-to/secure-apparmor)
- [Lab: AppArmor - Dockerlabs Collabnix](https://dockerlabs.collabnix.com/advanced/security/apparmor/)

---

### Videos and Presentations

- [Restricting Unprivileged User Namespaces in Ubuntu - John Johansen & Maxime Bélair, Canonical - Linux Security Summit Europe 24](https://www.youtube.com/watch?v=GcVjng8WVeg) - A retrospective on the work to restrict unprivileged user namespaces by default in Ubuntu 24.04. This presentation will cover the challenges, problems, and the solutions that Ubuntu choose. It will also take a look at work to address the problems that remain. Video.
- [Linux Containers with AppArmor Policy Namespaces - Leesoo Ahn - DebConf 24](https://debconf24.debconf.org/talks/106-linux-containers-with-apparmor-policy-namespaces/)
- [Unprivileged Access Control in AppArmor - John Johansen & Georgia Garcia, Canonical - Linux Security Summit North America 2024](https://www.youtube.com/watch?v=HJ5BMX52dhI) - Video
- [LSM Updates: IMA, SELinux, AppArmor, SMACK &... - Roberto Sassu, Paul Moore, John Johansen & KP Singh - Linux Security Summit Europe 2023](https://www.youtube.com/watch?v=ifVioMPhEZE) - Video
- [Apply security to your servers with AppArmor - Brian Six - SUSECON 2022](https://www.youtube.com/watch?v=X8xMSIZAy7M) - Video
- [Securely protected Kubernetes Container environment with AppArmor - Hoon Jo - UbuCon Asia 2022](https://2022.ubucon.asia/sessions/safe-kubenetes-environment-with-apparmor/)
- Securing BIND 9 with AppArmor/Firejail/SecompBPF - Carsten Strotmann and the ISC Team - 2021: [Video](https://www.youtube.com/watch?v=Cez-RkSQEHY), [Slide](https://www.isc.org/docs/2021-10-webinar-bind9-security-apparmor.pdf), [Webpage](https://webinar.defaultroutes.de/webinar/07-apparmor.html)
- Firejail vs Apparmor for sandboxing Firefox - NapoleonWilson - 2021: [Video](https://www.youtube.com/watch?v=vRawf5eswac), [Notes](https://github.com/NapoleonWils0n/cerberus/blob/master/apparmor/apparmor-firefox.org)
- Binary Policy with IMA and AppArmor - Eric Chiang, Google - Linux Security Summit 2019: [Video](https://www.youtube.com/watch?v=Qqp_pb8qKFY), [Slide](https://docs.google.com/presentation/d/1BqLtBIIpibH4WwMAlIXKcz4PMn1shFvnSHZ5G8IHvgU/mobilepresent#slide=id.p)
- [AppArmor Crashkurs - Christian Boltz - FrosCon 2019](https://media.ccc.de/v/froscon2019-2399-apparmor_crashkurs)
- [AppArmor 3.0 - Seth Arnold - DebConf 18](https://debconf18.debconf.org/talks/106-apparmor-30/)
- Introduction To Firejail, AppArmor, and SELinux - Aaron Jones - Phoenix Linux Users Group's Security meeting 2018: [Video](https://www.youtube.com/watch?v=JFjXvIwAeVI), [Webpage](https://retro64xyz.gitlab.io/presentations/2018/10/16/firejail-and-apparmor/)
- [AppArmor Crash Course - Christian Boltz - OpenSuse Conference 2016](https://media.ccc.de/v/786-apparmor-crash-course)
- [AppArmor Crashkurs - Christian Boltz - Gulaschprogrammiernacht 16](https://media.ccc.de/v/gpn16-7573-apparmor_crashkurs)
- [AppArmor Crash Course - Christian Boltz - DebConf 15](https://saimei.ftp.acc.umu.se/pub/debian-meetings/2015/debconf15/AppArmor_Crash_Course.webm) - Video
- [AppArmor crash course and workshop - Christian Boltz - OpenSuse Conference 12](https://blog.cboltz.de/uploads/osc12/apparmor-english-2012-v2.pdf) - Slide
- Securing Linux Applications With AppArmor - Crispin Cowan - DEFCON 15: [Video](https://www.youtube.com/watch?v=mp23AO8qtE4), [Slide](https://www.defcon.org/images/defcon-15/dc15-presentations/dc-15-cowan.pdf)
