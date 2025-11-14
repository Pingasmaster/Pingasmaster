<div align="center">
  
  # Hi 👋, I'm Adrian
  
  ### A sysadmin, security analyst, software engineer & web dev
  
  Computers, linux, servers, parkour, bike and chess, in that order.

  [![Linux badge](https://img.shields.io/badge/System-Linux-informational?style=flat&logo=linux&color=FCC624)](https://github.com/orgs/OpenMandrivaAssociation/people?query=Adrian)
  [![GPL Licence badge](https://badges.frapsoft.com/os/gpl/gpl.png?v=103)](https://opensource.org/licenses/GPL-3.0/)
  ![Profile views counter](https://komarev.com/ghpvc/?username=Pingasmaster)
  [![CVE counters](https://img.shields.io/badge/CVE_Counter-1-important)](https://nvd.nist.gov/vuln/detail/CVE-2025-64517)
  [![sudo-rs pwned badge](https://img.shields.io/badge/sudo_rs-pwned-important)](https://github.com/trifectatechfoundation/sudo-rs/security/advisories/GHSA-q428-6v73-fc4q)
  ![ESSSET](https://img.shields.io/badge/European_Systems,_Software_and_Security_Emergency_Taskforce_🇪🇺-French_Section_🇫🇷-white)
  
</div>

<details>
  <summary><h2>Current projects</h2></summary>

  * Security research on rust software already deployed in production, often rust rewrites like the git rust rewrite or the coreutils rewrite (uutils). See
  * Contributing to linux distributions like Openmandriva where I'm one of the 60 core team members.
  * Making fast software in C, secure software in rust or rapid prototypes in python
  * Creating [my own future-proof linux distribution](https://github.com/Pingasmaster/apexos) with near-native support for windows apps executing from the file manager as a PoC.

  Examples of my best work include:
  * finding [CVE-2025-64517](https://nvd.nist.gov/vuln/detail/CVE-2025-64517) in sudo-rs that allowed full root privilege escalation alongside a lot of [other](https://github.com/trifectatechfoundation/sudo-rs/issues/1309) [interesting](https://github.com/trifectatechfoundation/sudo-rs/issues/1311) [mild](https://github.com/trifectatechfoundation/sudo-rs/issues/1310) [issues](https://github.com/trifectatechfoundation/sudo-rs/issues/1310#issuecomment-3518897701). Here's the [github security advisory](https://github.com/trifectatechfoundation/sudo-rs/security/advisories/GHSA-q428-6v73-fc4q), the [debian security advisory](https://lists.debian.org/debian-security-announce/2025/msg00218.html). This vulnerability also got covered in a dedicated video by one of the most prominent [linux journals,](https://www.youtube.com/watch?v=R3SUTiAp9aw) the lunduke journal, wow!
  * and various other fun stuff along the way (peek at my PR/commit history and you'll probably see something fun!)
</details>

<details>
  <summary><h2>Linux distributions tier list (personal opinion):</h2></summary>

  ### S Tier:
  | TempleOS | Gentoo | Arch Linux | OpenMandriva |
  |:-:|:-:|:-:|:-:|
  <img title="TempleOS" alt="TempleOS" width="40px" src="https://templeos.org/favicon.ico"/>|<img title="Gentoo" alt="Gentoo" width="40px" src="https://www.gentoo.org/assets/img/logo/gentoo-signet.svg"/>|<img title="Arch Linux" alt="Arch Linux" width="40px" src="https://github.com/github/explore/blob/main/topics/archlinux/archlinux.png"/>|<img title="OpenMandriva" alt="OpenMandriva" width="40px" src="https://www.openmandriva.org/squelettes/icons/favicon.ico"/>

  ### A Tier:
  | Linux from Scratch | Debian |
  |:-:|:-:|
  <img title="LFS" alt="Linux From Scratch" width="40px" src="https://github.com/github/explore/blob/main/topics/linux/linux.png"/>|<img title="Debian" alt="Debian" width="40px" src="https://github.com/github/explore/blob/main/topics/debian/debian.png" />|

  ### B Tier:
  | Fedora | Bazzite |
  |:-:|:-:|
  <img title="Fedora" alt="Fedora" width="40px" src="https://github.com/github/explore/blob/main/topics/fedora/fedora.png"/>|<img title="Bazzite" alt="Bazzite" width="40px" src="https://raw.githubusercontent.com/bazzite-org/bazzite.gg/refs/heads/main/favicon.ico"/>

  ### C Tier:

  |:-:|

  ### D Tier:
  | ZorinOS | Ubuntu |
  |:-:|:-:|
  <img title="ZorinOS" alt="ZorinOS" width="40px" src="https://zorin.com/favicon-32x32.png"/>|<img title="Ubuntu" alt="Ubuntu" width="40px" src="https://github.com/github/explore/blob/main/topics/ubuntu/ubuntu.png"/>|

</details>

<details>
  <summary><h2>Philosophy</h2></summary>

  Some of the best software ever made in my opinion:
  - Linux and wine because they are impossible to create
  - tcc, openrc, dwm, doas because clean, simple and readable code is the hardest code to make
  - C because it was made by legends (and makes it simpler to write clean code)
  - Rust because it actually made it simpler to write error-free code (not just about mem safety but also the code style and "spirit")

  The perfect system is resilient and always up. Resistant to memory corruption via ECC and other technologies, resistant to power failures/spikes/brownouts via UPS and the likes, resitant to human tampering / unauthorized physical access, and resitant to human stupidity with High Availablitity VMs in redondant clusters and 3-2-1 backups. The perfect system only includes perfect software and therefore doesn't exist in real life.

  The perfect code is both error-free and clean. Error-free which means bug-free, both logically (sound program logic) and physically (memory safety, resitant to external errors like no more disk space or internet and unexpected bugs). Clean means simple, easy to understand, and small in LoC while still respecting these two principles. Perfect software is feature-complete (and therefore "done") but also always funded and maintained security-wise. Therefore, perfect software is extremely rare.

  I may be young but I am not a beginner, having over a decade of experience in linux systems and securing whole datacenters from the hardware to the end user. Able to learn new things fast and well if needed.

  I don't use github often for my own projects (I don't trust microsoft to maintain a proper uptime) hence my rather empty account, I prefer to use self-hosted free software such as [gogs](https://github.com/gogs/gogs).
</details>

If you read all this, have a nice day!
