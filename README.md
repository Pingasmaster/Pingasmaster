<div align="center">
  
  # Hi 👋, I'm Adrian
  
  ### A sysadmin, security analyst, software engineer & web dev
  
  Computers, linux, servers, parkour, bike and chess, in that order.
  
  <q><em>I don't know, but I'll find out.</em></q>

  [![Linux badge](https://img.shields.io/badge/System-Linux-informational?style=flat&logo=linux&color=FCC624)](https://github.com/orgs/OpenMandrivaAssociation/people?query=Adrian)
  [![GPL Licence badge](https://badges.frapsoft.com/os/gpl/gpl.png?v=103)](https://opensource.org/licenses/GPL-3.0/)
  ![Profile views counter](https://komarev.com/ghpvc/?username=Pingasmaster&base=10000)
  [![CVE counters](https://img.shields.io/badge/CVE_Counter-1-important)](https://nvd.nist.gov/vuln/detail/CVE-2025-64517)
  [![sudo-rs pwned badge](https://img.shields.io/badge/sudo_rs-pwned-important)](https://github.com/trifectatechfoundation/sudo-rs/security/advisories/GHSA-q428-6v73-fc4q)
  
</div>

<details>
  <summary><h2>Current projects</h2></summary>

  * Rewriting [all software in my linux distribution in pure amd64 assembly](https://github.com/Pingasmaster/white) by hand to make it faster (not a joke) so an OS can finally do modern work but also feel as snappy as windows 95 again. I may rename ApexOS into Linux 95 sooner or later.
  * Creating [my own future-proof linux distribution](https://github.com/Pingasmaster/apexos) with near-native support for windows apps executing from the file manager as a Proof of Concept.
  * Security research on rust software already deployed in production, often rust rewrites like the git rust rewrite or the coreutils rewrite (uutils).
  * Contributing to linux distributions like Openmandriva where I'm one of the 60 core team members.
  * Making fast software in assembly or C, secure software in rust or rapid prototypes in python.
  * Designing beautiful and secure android "Material you 3 expressive" apps in Java & Kotlin or progressive web apps (that are very performance-focused & written by hand with HTML/CSS/JS instead of using react or any other framework).

  Examples of my best work include:
  * finding [CVE-2025-64517](https://nvd.nist.gov/vuln/detail/CVE-2025-64517) in sudo-rs that allowed full root privilege escalation from any user alongside a lot of [other](https://github.com/trifectatechfoundation/sudo-rs/issues/1309) [interesting](https://github.com/trifectatechfoundation/sudo-rs/issues/1311) [mild](https://github.com/trifectatechfoundation/sudo-rs/issues/1310) [issues](https://github.com/trifectatechfoundation/sudo-rs/issues/1310#issuecomment-3518897701). Here's the [github security advisory](https://github.com/trifectatechfoundation/sudo-rs/security/advisories/GHSA-q428-6v73-fc4q), the [debian security advisory](https://lists.debian.org/debian-security-announce/2025/msg00218.html), the [ubuntu advisory](https://ubuntu.com/security/CVE-2025-64517). This vulnerability also got covered in a dedicated video by one of the most prominent [linux journals,](https://www.youtube.com/watch?v=R3SUTiAp9aw) the lunduke journal and this [Primetime video](https://youtu.be/_AsXnyi2Mus?si=gPidNFQ1PHzqV5e8&t=476), wow! The [guys at phoronix get it](https://www.phoronix.com/news/sudo-rs-security-ubuntu-25.10), deploying less than a year old software in prod won't do much good, while [itsfoss](https://itsfoss.com/news/sudo-rs-issue-ubuntu/) thinks it actually is a good thing. My take is that it's a good thing these were found, however it is certainly not a good sign that these basic logic holes exist in the first place. 
  * and various other fun stuff along the way (peek at my PR/commit history and you'll probably see something fun!)
</details>

<details>
  <summary><h2>OS tier list (personal opinion):</h2></summary>

  ### S Tier:
  | TempleOS | Gentoo | Arch Linux | OpenBSD |
  |:-:|:-:|:-:|:-:|
  |<img title="TempleOS" alt="TempleOS" width="40px" src="https://templeos.org/favicon.ico"/>|<img title="Gentoo" alt="Gentoo" width="40px" src="https://www.gentoo.org/assets/img/logo/gentoo-signet.svg"/>|<img title="Arch Linux" alt="Arch Linux" width="40px" src="https://github.com/github/explore/blob/main/topics/archlinux/archlinux.png"/>|<img title="OpenBSD" alt="OpenBSD" width="40px" src="https://upload.wikimedia.org/wikipedia/en/8/83/OpenBSD_Logo_-_Cartoon_Puffy_with_textual_logo_below.svg"/>|

  ### A Tier:
  | Linux from Scratch | Debian | CachyOS | OpenMandriva |
  |:-:|:-:|:-:|:-:|
  |<img title="LFS" alt="Linux From Scratch" width="40px" src="https://github.com/github/explore/blob/main/topics/linux/linux.png"/>|<img title="Debian" alt="Debian" width="40px" src="https://github.com/github/explore/blob/main/topics/debian/debian.png" />|<img title="CachyOS" alt="CachyOS" width="40px" src="https://upload.wikimedia.org/wikipedia/commons/b/b8/CachyOS_Logo.svg"/>|<img title="OpenMandriva" alt="OpenMandriva" width="40px" src="https://www.openmandriva.org/squelettes/icons/favicon.ico"/>|

  ### B Tier:
  | Fedora | Bazzite |
  |:-:|:-:|
  |<img title="Fedora" alt="Fedora" width="40px" src="https://github.com/github/explore/blob/main/topics/fedora/fedora.png"/>|<img title="Bazzite" alt="Bazzite" width="40px" src="https://raw.githubusercontent.com/bazzite-org/bazzite.gg/refs/heads/main/favicon.ico"/>|

  ### C Tier:
  | Linux Mint | Ubuntu |
  |:-:|:-:|
  |<img title="Linux Mint" alt="Mint" width="40px" src="https://raw.githubusercontent.com/linuxmint/brand-logo/master/badge.svg"/>|<img title="Ubuntu" alt="Ubuntu" width="40px" src="https://github.com/github/explore/blob/main/topics/ubuntu/ubuntu.png"/>|
  
  ### D Tier:
  | ZorinOS | RedHat Linux |
  |:-:|:-:|
  |<img title="ZorinOS" alt="ZorinOS" width="40px" src="https://zorin.com/favicon-32x32.png"/>|<img title="RedHat Linux" alt="RedHat" width="40px" src="https://www.redhat.com/rhdc/managed-files/rhb-logos-red_hat_logo-hero_image_1.svg"/>

  This is subjective (and highly personnal) and depends on a distro's usefulness to me and the code's beauty and distro's philosophies. For example, Ubuntu has a bad security track record and frankly often quite bad code but is very beginner friendly. Linux Ming is fine and the team is dedicated but it's not very useful to me and I think the ubuntu base is a poor decision they'll come to regret in the future for stability and security. Redhat is in D tier since it's not open source anymore (can't audit the source code so can't give a rating).
</details>

<details>
  <summary><h2>Philosophy</h2></summary>

  A company can fail, you see that all the time. Founders who promise the world and deliver nothing or get acquired then dump and rebuild another useless company. But if you just make an open source project yourself out of passion, there's no expectation, no failure. You can only succeed.

  Some of the best software ever made in my opinion:
  - Linux and wine because they are impossible to create
  - tcc, openrc, dwm, doas because clean, simple and readable code is the hardest code to write
  - C because it was made by legends (and makes it simpler to write clean code)
  - Rust because it actually made it simpler to write error-free code (not just about mem safety but also the code style and "spirit" with cargo, etc) and can be guaranteed "99.99%" secure if used well

  The perfect system is resilient and always up. Resistant to memory corruption via ECC and other technologies, resistant to power failures/spikes/brownouts via UPS and the likes, resitant to human tampering / unauthorized physical access, and resitant to human stupidity with High Availablitity VMs in redondant clusters and 3-2-1 backups. The perfect system only includes perfect software and therefore doesn't exist in real life.

  The perfect code is both error-free and clean. Error-free which means bug-free, both logically (sound program logic) and physically (memory safety, resitant to external errors like no more disk space or internet and unexpected bugs). Clean means simple, easy to understand, and small in LoC while still respecting these two principles. Perfect software is feature-complete (and therefore "done") but also always funded for the minimal but necessary security maintenance. Therefore, perfect software is extremely rare, if not also impossible.

  In the end, everyone is a beginner, and has more to learn. If you'd like my mindset but my current skills don't quite align with what do do right now, know that I got where I am by being able and willing to learn new things fast and well.

  I don't use github often for my own projects (I don't trust microsoft to maintain a proper uptime or with sensitive code) hence my rather empty account, I prefer to use self-hosted free software such as [gogs](https://github.com/gogs/gogs).
</details>

If you read all this, have a nice day!
