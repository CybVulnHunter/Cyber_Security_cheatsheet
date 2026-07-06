# Awesome CTF 

A curated list of (CTF) frameworks, libraries, resources, softwares and tutorials. This list aims to help starters as well as seasoned CTF players to find everything related to CTFs at one place.

### Contents

- [Awesome CTF](#awesome-ctf)
  - [Create](#create)
    - [Forensics](#forensics)
    - [Platforms](#platforms)
    - [Steganography](#steganography)
    - [Web](#web)
  - [Solve](#solve)
    - [Attacks](#attacks)
    - [Bruteforcers](#bruteforcers)
    - [Cryptography](#crypto)
    - [Exploits](#exploits)
    - [Forensics](#forensics-1)
    - [Networking](#networking)
    - [Reversing](#reversing)
    - [Services](#services)
    - [Steganography](#steganography-1)
    - [Web](#web-1)

- [Resources](#resources)
  - [Operating Systems](#operating-systems)
  - [Starter Packs](#starter-packs)
  - [Tutorials](#tutorials)
  - [Wargames](#wargames)
  - [Websites](#websites)
  - [Wikis](#wikis)
  - [Writeups Collections](#writeups-collections)


# Create

*Tools used for creating CTF challenges*

- [Kali Linux CTF Blueprints](https://www.packtpub.com/eu/networking-and-servers/kali-linux-ctf-blueprints) - Online book on building, testing, and customizing your own Capture the Flag challenges.


## Forensics

*Tools used for creating Forensics challenges*

- [Dnscat2](https://github.com/iagox86/dnscat2) - Hosts communication through DNS.
- [Kroll Artifact Parser and Extractor (KAPE)](https://learn.duffandphelps.com/kape) - Triage program.
- [Magnet AXIOM](https://www.magnetforensics.com/downloadaxiom) - Artifact-centric DFIR tool.
- [Registry Dumper](http://www.kahusecurity.com/posts/registry_dumper_find_and_dump_hidden_registry_keys.html) - Dump your registry.

## Platforms

*Projects that can be used to host a CTF*

- [CTFd](https://github.com/isislab/CTFd) - Platform to host jeopardy style CTFs from ISISLab, NYU Tandon.
- [echoCTF.RED](https://github.com/echoCTF/echoCTF.RED) - Develop, deploy and maintain your own CTF infrastructure.
- [FBCTF](https://github.com/facebook/fbctf) - Platform to host Capture the Flag competitions from Facebook.
- [Haaukins](https://github.com/aau-network-security/haaukins)- A Highly Accessible and Automated Virtualization Platform for Security Education.
- [HackTheArch](https://github.com/mcpa-stlouis/hack-the-arch) - CTF scoring platform.
- [Mellivora](https://github.com/Nakiami/mellivora) - A CTF engine written in PHP.
- [MotherFucking-CTF](https://github.com/andreafioraldi/motherfucking-ctf) - Badass lightweight plaform to host CTFs. No JS involved.
- [NightShade](https://github.com/UnrealAkama/NightShade) - A simple security CTF framework.
- [OpenCTF](https://github.com/easyctf/openctf) - CTF in a box. Minimal setup required.
- [PicoCTF](https://github.com/picoCTF/picoCTF) - The platform used to run picoCTF. A great framework to host any CTF.
- [PyChallFactory](https://github.com/pdautry/py_chall_factory) - Small framework to create/manage/package jeopardy CTF challenges.
- [RootTheBox](https://github.com/moloch--/RootTheBox) - A Game of Hackers (CTF Scoreboard & Game Manager).
- [Scorebot](https://github.com/legitbs/scorebot) - Platform for CTFs by Legitbs (Defcon).
- [SecGen](https://github.com/cliffe/SecGen) - Security Scenario Generator. Creates randomly vulnerable virtual machines.

## Steganography

*Tools used to create stego challenges*

Check solve section for steganography.

## Web

*Tools used for creating Web challenges*

*JavaScript Obfustcators*

- [Metasploit JavaScript Obfuscator](https://github.com/rapid7/metasploit-framework/wiki/How-to-obfuscate-JavaScript-in-Metasploit)
- [Uglify](https://github.com/mishoo/UglifyJS)


# Solve

*Tools used for solving CTF challenges*

## Attacks

*Tools used for performing various kinds of attacks*

- [Bettercap](https://github.com/bettercap/bettercap) - Framework to perform MITM (Man in the Middle) attacks.
- [Yersinia](https://github.com/tomac/yersinia) - Attack various protocols on layer 2.

## Crypto

*Tools used for solving Crypto challenges*

- [CyberChef](https://gchq.github.io/CyberChef) - Web app for analysing and decoding data.
- [FeatherDuster](https://github.com/nccgroup/featherduster) - An automated, modular cryptanalysis tool.
- [Hash Extender](https://github.com/iagox86/hash_extender) - A utility tool for performing hash length extension attacks.
- [padding-oracle-attacker](https://github.com/KishanBagaria/padding-oracle-attacker) - A CLI tool to execute padding oracle attacks.
- [PkCrack](https://www.unix-ag.uni-kl.de/~conrad/krypto/pkcrack.html) - A tool for Breaking PkZip-encryption.
- [QuipQuip](https://quipqiup.com) - An online tool for breaking substitution ciphers or vigenere ciphers (without key).
- [RSACTFTool](https://github.com/Ganapati/RsaCtfTool) - A tool for recovering RSA private key with various attack.
- [RSATool](https://github.com/ius/rsatool) - Generate private key with knowledge of p and q.
- [XORTool](https://github.com/hellman/xortool) - A tool to analyze multi-byte xor cipher.

## Bruteforcers

*Tools used for various kind of bruteforcing (passwords etc.)*

- [Hashcat](https://hashcat.net/hashcat/) - Password Cracker
- [Hydra](https://tools.kali.org/password-attacks/hydra) - A parallelized login cracker which supports numerous protocols to attack
- [John The Jumbo](https://github.com/magnumripper/JohnTheRipper) - Community enhanced version of John the Ripper.
- [John The Ripper](http://www.openwall.com/john/) - Password Cracker.
- [Nozzlr](https://github.com/intrd/nozzlr) - Nozzlr is a bruteforce framework, trully modular and script-friendly.
- [Ophcrack](http://ophcrack.sourceforge.net/) - Windows password cracker based on rainbow tables.
- [Patator](https://github.com/lanjelot/patator) - Patator is a multi-purpose brute-forcer, with a modular design.
- [Turbo Intruder](https://portswigger.net/research/turbo-intruder-embracing-the-billion-request-attack) - Burp Suite extension for sending large numbers of HTTP requests 

## Exploits

*Tools used for solving Exploits challenges*

- [DLLInjector](https://github.com/OpenSecurityResearch/dllinjector) - Inject dlls in processes.
- [libformatstr](https://github.com/hellman/libformatstr) - Simplify format string exploitation.
- [Metasploit](http://www.metasploit.com/) - Penetration testing software.
  - [Cheatsheet](https://www.comparitech.com/net-admin/metasploit-cheat-sheet/)
- [one_gadget](https://github.com/david942j/one_gadget) -  A tool to find the one gadget `execve('/bin/sh', NULL, NULL)` call.
  - `gem install one_gadget`
- [Pwntools](https://github.com/Gallopsled/pwntools) - CTF Framework for writing exploits.
- [Qira](https://github.com/BinaryAnalysisPlatform/qira) - QEMU Interactive Runtime Analyser.
- [ROP Gadget](https://github.com/JonathanSalwan/ROPgadget) - Framework for ROP exploitation.
- [V0lt](https://github.com/P1kachu/v0lt) - Security CTF Toolkit.

## Forensics

*Tools used for solving Forensics challenges*

- [Aircrack-Ng](http://www.aircrack-ng.org/) - Crack 802.11 WEP and WPA-PSK keys.
  - `apt-get install aircrack-ng`
- [Audacity](http://sourceforge.net/projects/audacity/) - Analyze sound files (mp3, m4a, whatever).
  - `apt-get install audacity`
- [Bkhive and Samdump2](http://sourceforge.net/projects/ophcrack/files/samdump2/) - Dump SYSTEM and SAM files.
  - `apt-get install samdump2 bkhive`
- [CFF Explorer](http://www.ntcore.com/exsuite.php) - PE Editor.
- [Creddump](https://github.com/moyix/creddump) - Dump windows credentials.
- [DVCS Ripper](https://github.com/kost/dvcs-ripper) - Rips web accessible (distributed) version control systems.
- [Exif Tool](http://www.sno.phy.queensu.ca/~phil/exiftool/) - Read, write and edit file metadata.
- [Extundelete](http://extundelete.sourceforge.net/) - Used for recovering lost data from mountable images.
- [Fibratus](https://github.com/rabbitstack/fibratus) - Tool for exploration and tracing of the Windows kernel.
- [Foremost](http://foremost.sourceforge.net/) - Extract particular kind of files using headers.
  - `apt-get install foremost`
- [Fsck.ext4](http://linux.die.net/man/8/fsck.ext3) - Used to fix corrupt filesystems.
- [Malzilla](http://malzilla.sourceforge.net/) - Malware hunting tool.
- [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) - Network Forensic Analysis Tool.
- [PDF Streams Inflater](http://malzilla.sourceforge.net/downloads.html) - Find and extract zlib files compressed in PDF files.
- [Pngcheck](http://www.libpng.org/pub/png/apps/pngcheck.html) - Verifies the integrity of PNG and dump all of the chunk-level information in human-readable form.
  - `apt-get install pngcheck`
- [ResourcesExtract](http://www.nirsoft.net/utils/resources_extract.html) - Extract various filetypes from exes.
- [Shellbags](https://github.com/williballenthin/shellbags) - Investigate NT\_USER.dat files.
- [Snow](https://sbmlabs.com/notes/snow_whitespace_steganography_tool) - A Whitespace Steganography Tool.
- [USBRip](https://github.com/snovvcrash/usbrip) - Simple CLI forensics tool for tracking USB device artifacts (history of USB events) on GNU/Linux.
- [Volatility](https://github.com/volatilityfoundation/volatility) - To investigate memory dumps.
- [Wireshark](https://www.wireshark.org) - Used to analyze pcap or pcapng files

*Registry Viewers*
- [OfflineRegistryView](https://www.nirsoft.net/utils/offline_registry_view.html) - Simple tool for Windows that allows you to read offline Registry files from external drive and view the desired Registry key in .reg file format.
- [Registry Viewer®](https://accessdata.com/product-download/registry-viewer-2-0-0) - Used to view Windows registries.

## Networking

*Tools used for solving Networking challenges*

- [Masscan](https://github.com/robertdavidgraham/masscan) - Mass IP port scanner, TCP port scanner.
- [Monit](https://linoxide.com/monitoring-2/monit-linux/) - A linux tool to check a host on the network (and other non-network activities).
- [Nipe](https://github.com/GouveaHeitor/nipe) - Nipe is a script to make Tor Network your default gateway.
- [Nmap](https://nmap.org/) - An open source utility for network discovery and security auditing.
- [Wireshark](https://www.wireshark.org/) - Analyze the network dumps.
  - `apt-get install wireshark`
- [Zeek](https://www.zeek.org) - An open-source network security monitor.
- [Zmap](https://zmap.io/) - An open-source network scanner.

## Reversing

*Tools used for solving Reversing challenges*

- [Androguard](https://github.com/androguard/androguard) - Reverse engineer Android applications.
- [Angr](https://github.com/angr/angr) - platform-agnostic binary analysis framework.
- [Apk2Gold](https://github.com/lxdvs/apk2gold) - Yet another Android decompiler.
- [ApkTool](http://ibotpeaches.github.io/Apktool/) - Android Decompiler.
- [Barf](https://github.com/programa-stic/barf-project) - Binary Analysis and Reverse engineering Framework.
- [Binary Ninja](https://binary.ninja/) - Binary analysis framework.
- [BinUtils](http://www.gnu.org/software/binutils/binutils.html) - Collection of binary tools.
- [BinWalk](https://github.com/devttys0/binwalk) - Analyze, reverse engineer, and extract firmware images.
- [Boomerang](https://github.com/BoomerangDecompiler/boomerang) - Decompile x86/SPARC/PowerPC/ST-20 binaries to C.
- [ctf_import](https://github.com/docileninja/ctf_import) – run basic functions from stripped binaries cross platform.
- [cwe_checker](https://github.com/fkie-cad/cwe_checker) - cwe_checker finds vulnerable patterns in binary executables.
- [demovfuscator](https://github.com/kirschju/demovfuscator) - A work-in-progress deobfuscator for movfuscated binaries.
- [Frida](https://github.com/frida/) - Dynamic Code Injection.
- [GDB](https://www.gnu.org/software/gdb/) - The GNU project debugger.
- [GEF](https://github.com/hugsy/gef) - GDB plugin.
- [Ghidra](https://ghidra-sre.org/) - Open Source suite of reverse engineering tools.  Similar to IDA Pro.
- [Hopper](http://www.hopperapp.com/) - Reverse engineering tool (disassembler) for OSX and Linux.
- [IDA Pro](https://www.hex-rays.com/products/ida/) - Most used Reversing software.
- [Jadx](https://github.com/skylot/jadx) - Decompile Android files.
- [Java Decompilers](http://www.javadecompilers.com) - An online decompiler for Java and Android APKs.
- [Krakatau](https://github.com/Storyyeller/Krakatau) - Java decompiler and disassembler.
- [Objection](https://github.com/sensepost/objection) - Runtime Mobile Exploration.
- [PEDA](https://github.com/longld/peda) - GDB plugin (only python2.7).
- [Pin](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool) - A dynamic binary instrumentaion tool by Intel.
- [PINCE](https://github.com/korcankaraokcu/PINCE) - GDB front-end/reverse engineering tool, focused on game-hacking and automation.
- [PinCTF](https://github.com/ChrisTheCoolHut/PinCTF) - A tool which uses intel pin for Side Channel Analysis.
- [Plasma](https://github.com/joelpx/plasma) - An interactive disassembler for x86/ARM/MIPS which can generate indented pseudo-code with colored syntax.
- [Pwndbg](https://github.com/pwndbg/pwndbg) - A GDB plugin that provides a suite of utilities to hack around GDB easily.
- [radare2](https://github.com/radare/radare2) - A portable reversing framework.
- [Triton](https://github.com/JonathanSalwan/Triton/) - Dynamic Binary Analysis (DBA) framework.
- [Uncompyle](https://github.com/gstarnberger/uncompyle) - Decompile Python 2.7 binaries (.pyc).
- [WinDbg](http://www.windbg.org/) - Windows debugger distributed by Microsoft.
- [Xocopy](http://reverse.lostrealm.com/tools/xocopy.html) - Program that can copy executables with execute, but no read permission.
- [Z3](https://github.com/Z3Prover/z3) - A theorem prover from Microsoft Research.

*JavaScript Deobfuscators*

- [Detox](http://relentless-coding.org/projects/jsdetox/install) - A Javascript malware analysis tool.
- [Revelo](http://www.kahusecurity.com/posts/revelo_javascript_deobfuscator.html) - Analyze obfuscated Javascript code.

*SWF Analyzers*
- [RABCDAsm](https://github.com/CyberShadow/RABCDAsm) - Collection of utilities including an ActionScript 3 assembler/disassembler.
- [Swftools](http://www.swftools.org/) - Collection of utilities to work with SWF files.
- [Xxxswf](https://bitbucket.org/Alexander_Hanel/xxxswf) -  A Python script for analyzing Flash files.

## Services

*Various kind of useful services available around the internet*

- [CSWSH](http://cow.cat/cswsh.html) - Cross-Site WebSocket Hijacking Tester.
- [Request Bin](https://requestbin.com/) - Lets you inspect http requests to a particular url.

## Steganography

*Tools used for solving Steganography challenges*

- [AperiSolve](https://aperisolve.fr/) - Aperi'Solve is a platform which performs layer analysis on image (open-source).
- [Convert](http://www.imagemagick.org/script/convert.php) - Convert images b/w formats and apply filters.
- [Exif](http://manpages.ubuntu.com/manpages/trusty/man1/exif.1.html) - Shows EXIF information in JPEG files.
- [Exiftool](https://linux.die.net/man/1/exiftool) - Read and write meta information in files.
- [Exiv2](http://www.exiv2.org/manpage.html) - Image metadata manipulation tool.
- [Image Steganography](https://sourceforge.net/projects/image-steg/) - Embeds text and files in images with optional encryption. Easy-to-use UI.
- [Image Steganography Online](https://incoherency.co.uk/image-steganography) - This is a client-side Javascript tool to steganographically hide images inside the lower "bits" of other images
- [ImageMagick](http://www.imagemagick.org/script/index.php) - Tool for manipulating images.
- [Outguess](https://www.freebsd.org/cgi/man.cgi?query=outguess+&apropos=0&sektion=0&manpath=FreeBSD+Ports+5.1-RELEASE&format=html) - Universal steganographic tool.
- [Pngtools](https://packages.debian.org/sid/pngtools) - For various analysis related to PNGs.
  - `apt-get install pngtools`
- [SmartDeblur](https://github.com/Y-Vladimir/SmartDeblur) - Used to deblur and fix defocused images.
- [Steganabara](https://www.openhub.net/p/steganabara) -  Tool for stegano analysis written in Java.
- [SteganographyOnline](https://stylesuxx.github.io/steganography/) - Online steganography encoder and decoder.
- [Stegbreak](https://linux.die.net/man/1/stegbreak) - Launches brute-force dictionary attacks on JPG image.
- [StegCracker](https://github.com/Paradoxis/StegCracker) - Steganography brute-force utility to uncover hidden data inside files.
- [stegextract](https://github.com/evyatarmeged/stegextract) - Detect hidden files and text in images.
- [Steghide](http://steghide.sourceforge.net/) - Hide data in various kind of images.
- [StegOnline](https://georgeom.net/StegOnline/upload) - Conduct a wide range of image steganography operations, such as concealing/revealing files hidden within bits (open-source).
- [Stegsolve](http://www.caesum.com/handbook/Stegsolve.jar) - Apply various steganography techniques to images.
- [Zsteg](https://github.com/zed-0xff/zsteg/) - PNG/BMP analysis.

## Web

*Tools used for solving Web challenges*

- [BurpSuite](https://portswigger.net/burp) - A graphical tool to testing website security.
- [Commix](https://github.com/commixproject/commix) - Automated All-in-One OS Command Injection and Exploitation Tool.
- [Hackbar](https://addons.mozilla.org/en-US/firefox/addon/hackbartool/) - Firefox addon for easy web exploitation.
- [OWASP ZAP](https://www.owasp.org/index.php/Projects/OWASP_Zed_Attack_Proxy_Project) - Intercepting proxy to replay, debug, and fuzz HTTP requests and responses
- [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en) - Add on for chrome for debugging network requests.
- [Raccoon](https://github.com/evyatarmeged/Raccoon) - A high performance offensive security tool for reconnaissance and vulnerability scanning.
- [SQLMap](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tool.
  ```pip install sqlmap```
- [W3af](https://github.com/andresriancho/w3af) -  Web Application Attack and Audit Framework.
- [XSSer](http://xsser.sourceforge.net/) - Automated XSS testor.


# Resources

*Where to discover about CTF*

## Operating Systems

*Penetration testing and security lab Operating Systems*

- [Android Tamer](https://androidtamer.com/) - Based on Debian.
- [BackBox](https://backbox.org/) - Based on Ubuntu.
- [BlackArch Linux](https://blackarch.org/) - Based on Arch Linux.
- [Fedora Security Lab](https://labs.fedoraproject.org/security/) - Based on Fedora.
- [Kali Linux](https://www.kali.org/) - Based on Debian.
- [Parrot Security OS](https://www.parrotsec.org/) - Based on Debian.
- [Pentoo](http://www.pentoo.ch/) - Based on Gentoo.
- [URIX OS](http://urix.us/) - Based on openSUSE.
- [Wifislax](http://www.wifislax.com/) - Based on Slackware.

*Malware analysts and reverse-engineering*

- [Flare VM](https://github.com/fireeye/flare-vm/) - Based on Windows.
- [REMnux](https://remnux.org/) - Based on Debian.

## Starter Packs

*Collections of installer scripts, useful tools*

- [CTF Tools](https://github.com/zardus/ctf-tools) - Collection of setup scripts to install various security research tools.
- [LazyKali](https://github.com/jlevitsk/lazykali) - A 2016 refresh of LazyKali which simplifies install of tools and configuration.

## Tutorials

*Tutorials to learn how to play CTFs*

- [CTF Field Guide](https://trailofbits.github.io/ctf/) - Field Guide by Trails of Bits.
- [CTF Resources](http://ctfs.github.io/resources/) -  Start Guide maintained by community.
- [How to Get Started in CTF](https://www.endgame.com/blog/how-get-started-ctf) - Short guideline for CTF beginners by Endgame
- [Intro. to CTF Course](https://www.hoppersroppers.org/courseCTF.html) - A free course that teaches beginners the basics of forensics, crypto, and web-ex.
- [IppSec](https://www.youtube.com/channel/UCa6eh7gCkpPo5XXUDfygQQA) - Video tutorials and walkthroughs of popular CTF platforms.
- [LiveOverFlow](https://www.youtube.com/channel/UClcE-kVhqyiHCcjYwcpfj9w) - Video tutorials on Exploitation.
- [MIPT CTF](https://github.com/xairy/mipt-ctf) - A small course for beginners in CTFs (in Russian).


## Wargames

*Always online CTFs*

- [Backdoor](https://backdoor.sdslabs.co/) - Security Platform by SDSLabs.
- [Crackmes](https://crackmes.one/) - Reverse Engineering Challenges.
- [CryptoHack](https://cryptohack.org/) - Fun cryptography challenges.
- [echoCTF.RED](https://echoctf.red/) - Online CTF with a variety of targets to attack.
- [Exploit Exercises](https://exploit-exercises.lains.space/) - Variety of VMs to learn variety of computer security issues.
- [Exploit.Education](http://exploit.education) - Variety of VMs to learn variety of computer security issues.
- [Gracker](https://github.com/Samuirai/gracker) - Binary challenges having a slow learning curve, and write-ups for each level.
- [Hack The Box](https://www.hackthebox.eu) - Weekly CTFs for all types of security enthusiasts.
- [Hack This Site](https://www.hackthissite.org/) - Training ground for hackers.
- [Hacker101](https://www.hacker101.com/) - CTF from HackerOne
- [Hacking-Lab](https://hacking-lab.com/) - Ethical hacking, computer network and security challenge platform.
- [Hone Your Ninja Skills](https://honeyourskills.ninja/) - Web challenges starting from basic ones.
- [IO](http://io.netgarage.org/) - Wargame for binary challenges.
- [Microcorruption](https://microcorruption.com) - Embedded security CTF.
- [Over The Wire](http://overthewire.org/wargames/) - Wargame maintained by OvertheWire Community.
- [PentesterLab](https://pentesterlab.com/) - Variety of VM and online challenges (paid).
- [PicoCTF](https://2019game.picoctf.com) - All year round ctf game. Questions from the yearly picoCTF competition.
- [PWN Challenge](http://pwn.eonew.cn/) - Binary Exploitation Wargame.
- [Pwnable.kr](http://pwnable.kr/) - Pwn Game.
- [Pwnable.tw](https://pwnable.tw/) - Binary wargame.
- [Pwnable.xyz](https://pwnable.xyz/) - Binary Exploitation Wargame.
- [Reversin.kr](http://reversing.kr/) - Reversing challenge.
- [Ringzer0Team](https://ringzer0team.com/) - Ringzer0 Team Online CTF.
- [Root-Me](https://www.root-me.org/) - Hacking and Information Security learning platform.
- [ROP Wargames](https://github.com/xelenonz/game) - ROP Wargames.
- [SANS HHC](https://holidayhackchallenge.com/past-challenges/) - Challenges with a holiday theme
  released annually and maintained by SANS.
- [SmashTheStack](http://smashthestack.org/) - A variety of wargames maintained by the SmashTheStack Community.
- [Viblo CTF](https://ctf.viblo.asia) - Various amazing CTF challenges, in many different categories. Has both Practice mode and Contest mode.
- [VulnHub](https://www.vulnhub.com/) - VM-based for practical in digital security, computer application & network administration.
- [W3Challs](https://w3challs.com) - A penetration testing training platform, which offers various computer challenges, in various categories.
- [WebHacking](http://webhacking.kr) - Hacking challenges for web.


*Self-hosted CTFs*
- [Damn Vulnerable Web Application](http://www.dvwa.co.uk/) - PHP/MySQL web application that is damn vulnerable.
- [Juice Shop CTF](https://github.com/bkimminich/juice-shop-ctf) - Scripts and tools for hosting a CTF on [OWASP Juice Shop](https://www.owasp.org/index.php/OWASP_Juice_Shop_Project) easily.

## Websites

*Various general websites about and on CTF*

- [Awesome CTF Cheatsheet](https://github.com/uppusaikiran/awesome-ctf-cheatsheet#awesome-ctf-cheatsheet-) - CTF Cheatsheet.
- [CTF Time](https://ctftime.org/) - General information on CTF occuring around the worlds.
- [Reddit Security CTF](http://www.reddit.com/r/securityctf) - Reddit CTF category.

## Wikis

*Various Wikis available for learning about CTFs*

- [Bamboofox](https://bamboofox.github.io/) - Chinese resources to learn CTF.
- [bi0s Wiki](https://teambi0s.gitlab.io/bi0s-wiki/) - Wiki from team bi0s.
- [CTF Cheatsheet](https://uppusaikiran.github.io/hacking/Capture-the-Flag-CheatSheet/) - CTF tips and tricks.
- [ISIS Lab](https://github.com/isislab/Project-Ideas/wiki) - CTF Wiki by Isis lab.
- [OpenToAll](https://github.com/OpenToAllCTF/Tips) - CTF tips by OTA CTF team members.

## Writeups Collections

*Collections of CTF write-ups*

- [0e85dc6eaf](https://github.com/0e85dc6eaf/CTF-Writeups) - Write-ups for CTF challenges by 0e85dc6eaf
- [Captf](http://captf.com/) - Dumped CTF challenges and materials by psifertex.
- [CTF write-ups (community)](https://github.com/ctfs/) - CTF challenges + write-ups archive maintained by the community.
- [CTFTime Scrapper](https://github.com/abdilahrf/CTFWriteupScrapper) - Scraps all writeup from CTF Time and organize which to read first.
- [HackThisSite](https://github.com/HackThisSite/CTF-Writeups) - CTF write-ups repo maintained by HackThisSite team.
- [Mzfr](https://github.com/mzfr/ctf-writeups/) - CTF competition write-ups by mzfr
- [pwntools writeups](https://github.com/Gallopsled/pwntools-write-ups) - A collection of CTF write-ups all using pwntools.
- [SababaSec](https://github.com/SababaSec/ctf-writeups) - A collection of CTF write-ups by the SababaSec team
- [Shell Storm](http://shell-storm.org/repo/CTF/) - CTF challenge archive maintained by Jonathan Salwan.
- [Smoke Leet Everyday](https://github.com/smokeleeteveryday/CTF_WRITEUPS) - CTF write-ups repo maintained by SmokeLeetEveryday team.


# Awesome Hacking 

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [System](#system)
    - [Tutorials](#tutorials)
    - [Tools](#tools)
    - [Docker](#docker-images-for-penetration-testing--security)
    - [General](#general)
- [Reverse Engineering](#reverse-engineering)
    - [Tutorials](#tutorials-1)
    - [Tools](#tools-1)
    - [General](#general-1)
- [Web](#web)
    - [Tools](#tools-2)
    - [General](#general-2)
- [Network](#network)
    - [Tools](#tools-3)
- [Forensic](#forensic)
    - [Tools](#tools-4)
- [Cryptography](#cryptography)
    - [Tools](#tools-5)
- [Wargame](#wargame)
    - [System](#system-1)
    - [Reverse Engineering](#reverse-engineering-1)
    - [Web](#web-1)
    - [Cryptography](#cryptography-1)
    - [Bug bounty](#bug-bounty)
- [CTF](#ctf)
    - [Competition](#competition)
    - [General](#general-2)
- [OS](#os)
    - [Online resources](#online-resources)
- [Post exploitation](#post-exploitation)
    - [tools](#tools-6)
- [ETC](#etc)

<!-- /MarkdownTOC -->

# System

## Tutorials
 * [Roppers Computing Fundamentals](https://www.roppers.org/courses/fundamentals)
    * Free, self-paced curriculum that builds a base of knowledge in computers and networking. Intended to build up a student with no prior technical knowledge to be confident in their ability to learn anything and continue their security education. Full text available as a [gitbook](https://www.hoppersroppers.org/fundamentals/).
 * [Corelan Team's Exploit writing tutorial](https://www.corelan.be/index.php/2009/07/19/exploit-writing-tutorial-part-1-stack-based-overflows/)
 * [Exploit Writing Tutorials for Pentesters](http://web.archive.org/web/20140916085343/http://www.punter-infosec.com/exploit-writing-tutorials-for-pentesters/)
 * [Understanding the basics of Linux Binary Exploitation](https://github.com/r0hi7/BinExp)
 * [Shells](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J)
 * [Missing Semester](https://missing.csail.mit.edu/2020/course-shell/)


## Tools
 * [Metasploit](https://github.com/rapid7/metasploit-framework) A computer security project that provides information about security vulnerabilities and aids in penetration testing and IDS signature development.
 * [mimikatz](https://github.com/gentilkiwi/mimikatz) - A little tool to play with Windows security
 * [Hackers tools](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuiujH1lpn8cA9dsyulbYRv) - Tutorial on tools.

### Docker Images for Penetration Testing & Security
 * `docker pull kalilinux/kali-linux-docker` [official Kali Linux](https://hub.docker.com/r/kalilinux/kali-last-release/)
 * `docker pull owasp/zap2docker-stable` - [official OWASP ZAP](https://github.com/zaproxy/zaproxy)
 * `docker pull wpscanteam/wpscan` - [official WPScan](https://hub.docker.com/r/wpscanteam/wpscan/)
 * `docker pull metasploitframework/metasploit-framework
` - [Official Metasploit](https://hub.docker.com/r/metasploitframework/metasploit-framework/)
 * `docker pull citizenstig/dvwa` - [Damn Vulnerable Web Application (DVWA)](https://hub.docker.com/r/citizenstig/dvwa/)
 * `docker pull wpscanteam/vulnerablewordpress` - [Vulnerable WordPress Installation](https://hub.docker.com/r/wpscanteam/vulnerablewordpress/)
 * `docker pull hmlio/vaas-cve-2014-6271` - [Vulnerability as a service: Shellshock](https://hub.docker.com/r/hmlio/vaas-cve-2014-6271/)
 * `docker pull hmlio/vaas-cve-2014-0160` - [Vulnerability as a service: Heartbleed](https://hub.docker.com/r/hmlio/vaas-cve-2014-0160/)
 * `docker pull opendns/security-ninjas` - [Security Ninjas](https://hub.docker.com/r/opendns/security-ninjas/)
 * `docker pull noncetonic/archlinux-pentest-lxde` - [Arch Linux Penetration Tester](https://hub.docker.com/r/noncetonic/archlinux-pentest-lxde)
 * `docker pull diogomonica/docker-bench-security` - [Docker Bench for Security](https://hub.docker.com/r/diogomonica/docker-bench-security/)
 * `docker pull ismisepaul/securityshepherd` - [OWASP Security Shepherd](https://hub.docker.com/r/ismisepaul/securityshepherd/)
 * `docker pull danmx/docker-owasp-webgoat` - [OWASP WebGoat Project docker image](https://hub.docker.com/r/danmx/docker-owasp-webgoat/)
 * `docker pull vulnerables/web-owasp-nodegoat` - [OWASP NodeGoat](https://github.com/owasp/nodegoat#option-3---run-nodegoat-on-docker)
 * `docker pull citizenstig/nowasp` - [OWASP Mutillidae II Web Pen-Test Practice Application](https://hub.docker.com/r/citizenstig/nowasp/)
 * `docker pull bkimminich/juice-shop` - [OWASP Juice Shop](https://github.com/bkimminich/juice-shop#docker-container--)
 * `docker pull phocean/msf` - [Docker Metasploit](https://hub.docker.com/r/phocean/msf/)

## General
 * [Exploit database](https://www.exploit-db.com/) - An ultimate archive of exploits and vulnerable software


# Reverse Engineering

## Tutorials
* [Begin RE: A Reverse Engineering Tutorial Workshop](https://www.begin.re/the-workshop)
* [Malware Analysis Tutorials: a Reverse Engineering Approach](http://fumalwareanalysis.blogspot.kr/p/malware-analysis-tutorials-reverse.html)
* [Malware Unicorn Reverse Engineering Tutorial](https://malwareunicorn.org/workshops/re101.html#0)
* [Lena151: Reversing With Lena](https://archive.org/details/lena151)

## Tools
### Disassemblers and debuggers
 * [IDA](https://www.hex-rays.com/products/ida/) - IDA is a Windows, Linux or Mac OS X hosted multi-processor disassembler and debugger
 * [OllyDbg](http://www.ollydbg.de/) - A 32-bit assembler level analysing debugger for Windows
 * [x64dbg](https://github.com/x64dbg/x64dbg) - An open-source x64/x32 debugger for Windows
 * [radare2](https://github.com/radare/radare2) - A portable reversing framework
 * [plasma](https://github.com/joelpx/plasma) - Interactive disassembler for x86/ARM/MIPS. Generates indented pseudo-code with colored syntax code.
 * [ScratchABit](https://github.com/pfalcon/ScratchABit) - Easily retargetable and hackable interactive disassembler with IDAPython-compatible plugin API
 * [Capstone](https://github.com/aquynh/capstone)
 * [Ghidra](https://ghidra-sre.org/) - A software reverse engineering (SRE) suite of tools developed by NSA's Research Directorate in support of the Cybersecurity mission

### Decompilers
*  JVM-based languages
  * [Krakatau](https://github.com/Storyyeller/Krakatau) - the best decompiler I have used. Is able to decompile apps written in Scala and Kotlin into Java code. JD-GUI and Luyten have failed to do it fully.
  * [JD-GUI](https://github.com/java-decompiler/jd-gui)
  * [procyon](https://bitbucket.org/mstrobel/procyon/wiki/Java%20Decompiler)
    * [Luyten](https://github.com/deathmarine/Luyten) - one of the best, though a bit slow, hangs on some binaries and not very well maintained.
  * [JAD](http://varaneckas.com/jad/) - JAD Java Decompiler (closed-source, unmaintained)
  * [JADX](https://github.com/skylot/jadx) - a decompiler for Android apps. Not related to JAD.

* .net-based languages
  * [dotPeek](https://www.jetbrains.com/decompiler/) - a free-of-charge .NET decompiler from JetBrains
  * [ILSpy](https://github.com/icsharpcode/ILSpy/) - an open-source .NET assembly browser and decompiler
  * [dnSpy](https://github.com/0xd4d/dnSpy) - .NET assembly editor, decompiler, and debugger

* native code
  * [Hopper](https://www.hopperapp.com) - A OS X and Linux Disassembler/Decompiler for 32/64-bit Windows/Mac/Linux/iOS executables.
  * [cutter](https://github.com/radareorg/cutter) - a decompiler based on radare2.
  * [retdec](https://github.com/avast-tl/retdec)
  * [snowman](https://github.com/yegord/snowman)
  * [Hex-Rays](https://www.hex-rays.com/products/decompiler/)

* Python
  * [uncompyle6](https://github.com/rocky/python-uncompyle6) - decompiler for the over 20 releases and 20 years of CPython.


### Deobfuscators
 * [de4dot](https://github.com/0xd4d/de4dot) - .NET deobfuscator and unpacker.
 * [JS Beautifier](https://github.com/beautify-web/js-beautify)
 * [JS Nice](http://jsnice.org/) - a web service guessing JS variables names and types based on the model derived from open source.

### Other
 * [nudge4j](https://github.com/lorenzoongithub/nudge4j) - Java tool to let the browser talk to the JVM
 * [dex2jar](https://github.com/pxb1988/dex2jar) - Tools to work with Android .dex and Java .class files
 * [androguard](https://code.google.com/p/androguard/) - Reverse engineering, malware and goodware analysis of Android applications
 * [antinet](https://github.com/0xd4d/antinet) - .NET anti-managed debugger and anti-profiler code
 * [UPX](http://upx.sourceforge.net/) - the Ultimate Packer (and unpacker) for eXecutables

### Execution logging and tracing
 * [Wireshark](https://www.wireshark.org/) - A free and open-source packet analyzer
 * [tcpdump](http://www.tcpdump.org/) - A powerful command-line packet analyzer; and libpcap, a portable C/C++ library for network traffic capture
 * [mitmproxy](https://github.com/mitmproxy/mitmproxy) - An interactive, SSL-capable man-in-the-middle proxy for HTTP with a console interface
 * [Charles Proxy](https://charlesproxy.com) - A cross-platform GUI web debugging proxy to view intercepted HTTP and HTTPS/SSL live traffic
 * [usbmon](https://www.kernel.org/doc/Documentation/usb/usbmon.txt) - USB capture for Linux.
 * [USBPcap](https://github.com/desowin/usbpcap) - USB capture for Windows.
 * [dynStruct](https://github.com/ampotos/dynStruct) - structures recovery via dynamic instrumentation.
 * [drltrace](https://github.com/mxmssh/drltrace) - shared library calls tracing.

### Binary files examination and editing

#### Hex editors
 * [HxD](http://mh-nexus.de/en/hxd/) - A hex editor which, additionally to raw disk editing and modifying of main memory (RAM), handles files of any size
 * [WinHex](http://www.winhex.com/winhex/) - A hexadecimal editor, helpful in the realm of computer forensics, data recovery, low-level data processing, and IT security
* [wxHexEditor](https://github.com/EUA/wxHexEditor)
* [Synalize It](https://www.synalysis.net/)/[Hexinator](https://hexinator.com/) -

#### Other
 * [Binwalk](https://github.com/ReFirmLabs/binwalk) -  Detects signatures, unpacks archives, visualizes entropy.
 * [Veles](https://github.com/codilime/veles) - a visualizer for statistical properties of blobs.
 * [Kaitai Struct](https://github.com/kaitai-io/kaitai_struct) - a DSL for creating parsers in a variety of programming languages. The Web IDE is particularly useful for reverse-engineering.
 * [Protobuf inspector](https://github.com/jmendeth/protobuf-inspector)
 * [DarunGrim](https://github.com/ohjeongwook/DarunGrim) - executable differ.
 * [DBeaver](https://github.com/dbeaver/dbeaver) - a DB editor.
 * [Dependencies](https://github.com/lucasg/Dependencies) - a FOSS replacement to Dependency Walker.
 * [PEview](http://wjradburn.com/software/) - A quick and easy way to view the structure and content of 32-bit Portable Executable (PE) and Component Object File Format (COFF) files
* [BinText](https://web.archive.org/web/http://www.mcafee.com/kr/downloads/free-tools/bintext.aspx) - A small, very fast and powerful text extractor that will be of particular interest to programmers.

## General
 * [Open Malware](http://www.offensivecomputing.net/)

# Web

## Tools
 * [Spyse](https://spyse.com/) -  Data gathering service that collects web info using OSINT. Provided info: IPv4 hosts, domains/whois, ports/banners/protocols, technologies, OS, AS, maintains huge SSL/TLS DB, and more... All the data is stored in its own database allowing get the data without scanning.
 * [sqlmap](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tool
 * [NoSQLMap](https://github.com/codingo/NoSQLMap) - Automated NoSQL database enumeration and web application exploitation tool.
 * [tools.web-max.ca](http://tools.web-max.ca/encode_decode.php) - base64 base85 md4,5 hash, sha1 hash encoding/decoding
 * [VHostScan](https://github.com/codingo/VHostScan) - A virtual host scanner that performs reverse lookups, can be used with pivot tools, detect catch-all scenarios, aliases and dynamic default pages.
 * [SubFinder](https://github.com/subfinder/subfinder) - SubFinder is a subdomain discovery tool that discovers valid subdomains for any target using passive online sources.
 * [Findsubdomains](https://findsubdomains.com/) - A subdomains discovery tool that collects all possible subdomains from open source internet and validates them through various tools to provide accurate results.
 * [badtouch](https://github.com/kpcyrd/badtouch) - Scriptable network authentication cracker
 * [PhpSploit](https://github.com/nil0x42/phpsploit) - Full-featured C2 framework which silently persists on webserver via evil PHP oneliner
 * [Git-Scanner](https://github.com/HightechSec/git-scanner) - A tool for bug hunting or pentesting for targeting websites that have open `.git` repositories available in public
 * [CSP Scanner](https://cspscanner.com/) - Analyze a site's Content-Security-Policy (CSP) to find bypasses and missing directives.
 * [Shodan](https://www.shodan.io/) - A web-crawling search engine that lets users search for various types of servers connected to the internet.
 * [masscan](https://github.com/robertdavidgraham/masscan) - Internet scale portscanner.
 * [Keyscope](https://github.com/SpectralOps/keyscope) - an extensible key and secret validation tool for auditing active secrets against multiple SaaS vendors
 * [Decompiler.com](https://www.decompiler.com/) - Java, Android, Python, C# online decompiler.

## General
 * [Strong node.js](https://github.com/jesusprubio/strong-node) - An exhaustive checklist to assist in the source code security analysis of a node.js web service.


# Network

## Tools
 * [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) - A Network Forensic Analysis Tool (NFAT)
 * [Paros](http://sourceforge.net/projects/paros/) - A Java-based HTTP/HTTPS proxy for assessing web application vulnerability
 * [pig](https://github.com/rafael-santiago/pig) - A Linux packet crafting tool
 * [findsubdomains](https://findsubdomains.com) - really fast subdomains scanning service that has much greater opportunities than simple subs finder(works using OSINT).
 * [cirt-fuzzer](http://www.cirt.dk/) - A simple TCP/UDP protocol fuzzer.
 * [ASlookup](https://aslookup.com/) - a useful tool for exploring autonomous systems and all related info (CIDR, ASN, Org...)
 * [ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project) - The Zed Attack Proxy (ZAP) is an easy to use integrated penetration testing tool for finding vulnerabilities in web applications
 * [mitmsocks4j](https://github.com/Akdeniz/mitmsocks4j) - Man-in-the-middle SOCKS Proxy for Java
 * [ssh-mitm](https://github.com/jtesta/ssh-mitm) - An SSH/SFTP man-in-the-middle tool that logs interactive sessions and passwords.
 * [nmap](https://nmap.org/) - Nmap (Network Mapper) is a security scanner
 * [Aircrack-ng](http://www.aircrack-ng.org/) - An 802.11 WEP and WPA-PSK keys cracking program
 * [Nipe](https://github.com/GouveaHeitor/nipe) - A script to make Tor Network your default gateway.
 * [Habu](https://github.com/portantier/habu) - Python Network Hacking Toolkit
 * [Wifi Jammer](https://n0where.net/wifijammer/) - Free program to jam all wifi clients in range
 * [Firesheep](https://codebutler.github.io/firesheep/) - Free program for HTTP session hijacking attacks.
 * [Scapy](https://github.com/secdev/awesome-scapy) - A Python tool and library for low level packet creation and manipulation
 * [Amass](https://github.com/OWASP/Amass) - In-depth subdomain enumeration tool that performs scraping, recursive brute forcing, crawling of web archives, name altering and reverse DNS sweeping
 * [sniffglue](https://github.com/kpcyrd/sniffglue) - Secure multithreaded packet sniffer
 * [Netz](https://github.com/spectralops/netz) - Discover internet-wide misconfigurations, using zgrab2 and others.
 * [RustScan](https://github.com/rustscan/rustscan) - Extremely fast port scanner built with Rust, designed to scan all ports in a couple of seconds and utilizes nmap to perform port enumeration in a fraction of the time.
 * [PETEP](https://github.com/Warxim/petep) - Extensible TCP/UDP proxy with GUI for traffic analysis & modification with SSL/TLS support.

# Forensic

## Tools
 * [Autopsy](http://www.sleuthkit.org/autopsy/) - A digital forensics platform and graphical interface to [The Sleuth Kit](http://www.sleuthkit.org/sleuthkit/index.php) and other digital forensics tools
 * [sleuthkit](https://github.com/sleuthkit/sleuthkit) - A library and collection of command-line digital forensics tools
 * [EnCase](https://www.guidancesoftware.com/products/Pages/encase-forensic/overview.aspx) - The shared technology within a suite of digital investigations products by Guidance Software
 * [malzilla](http://malzilla.sourceforge.net/) - Malware hunting tool
 * [IPED - Indexador e Processador de Evidências Digitais](https://servicos.dpf.gov.br/ferramentas/IPED/) - Brazilian Federal Police Tool for Forensic Investigation
 * [CyLR](https://github.com/orlikoski/CyLR) - NTFS forensic image collector 
 * [CAINE](https://www.caine-live.net/)- CAINE is a Ubuntu-based app that offers a complete forensic environment that provides a graphical interface. This tool can be integrated into existing software tools as a module. It automatically extracts a timeline from RAM.

# Cryptography

### Tools
 * [xortool](https://github.com/hellman/xortool) - A tool to analyze multi-byte XOR cipher
 * [John the Ripper](http://www.openwall.com/john/) - A fast password cracker
 * [Aircrack](http://www.aircrack-ng.org/) - Aircrack is 802.11 WEP and WPA-PSK keys cracking program.
 * [Ciphey](https://github.com/ciphey/ciphey) - Automated decryption tool using artificial intelligence & natural language processing.


# Wargame

## System
 * [OverTheWire - Semtex](http://overthewire.org/wargames/semtex/)
 * [OverTheWire - Vortex](http://overthewire.org/wargames/vortex/)
 * [OverTheWire - Drifter](http://overthewire.org/wargames/drifter/)
 * [pwnable.kr](http://pwnable.kr/) - Provide various pwn challenges regarding system security
 * [Exploit Exercises - Nebula](https://exploit-exercises.com/nebula/)
 * [SmashTheStack](http://smashthestack.org/)
 * [HackingLab](https://www.hacking-lab.com/) 

## Reverse Engineering
 * [Reversing.kr](http://www.reversing.kr/) - This site tests your ability to Cracking & Reverse Code Engineering
 * [CodeEngn](http://codeengn.com/challenges/) - (Korean)
 * [simples.kr](http://simples.kr/) - (Korean)
 * [Crackmes.de](http://crackmes.de/) - The world first and largest community website for crackmes and reversemes.

## Web
 * [Hack This Site!](https://www.hackthissite.org/) - a free, safe and legal training ground for hackers to test and expand their hacking skills
 * [Hack The Box](https://www.hackthebox.eu) - a free site to perform pentesting in a variety of different systems.
 * [Webhacking.kr](http://webhacking.kr/)
 * [0xf.at](https://0xf.at/) - a website without logins or ads where you can solve password-riddles (so called hackits).
 * [fuzzy.land](https://fuzzy.land/) - Website by an Austrian group. Lots of challenges taken from CTFs they participated in.
 * [Gruyere](https://google-gruyere.appspot.com/)
 * [Others](https://www.owasp.org/index.php/OWASP_Vulnerable_Web_Applications_Directory_Project#tab=On-Line_apps)
 * [TryHackMe](https://tryhackme.com/) - Hands-on cyber security training through real-world scenarios.

## Cryptography
 * [OverTheWire - Krypton](http://overthewire.org/wargames/krypton/)

## Bug bounty
  * [Awesome bug bounty resources by EdOverflow](https://github.com/EdOverflow/bugbounty-cheatsheet)

## Bug bounty -  Earn Some Money
  * [Bugcrowd](https://www.bugcrowd.com/)
  * [Hackerone](https://www.hackerone.com/start-hacking)
  * [Intigriti](https://www.intigriti.com/) Europe's #1 ethical hacking and bug bounty program.


# CTF

## Competition
 * [DEF CON](https://legitbs.net/)
 * [CSAW CTF](https://ctf.isis.poly.edu/)
 * [hack.lu CTF](http://hack.lu/)
 * [Pliad CTF](http://www.plaidctf.com/)
 * [RuCTFe](http://ructf.org/e/)
 * [Ghost in the Shellcode](http://ghostintheshellcode.com/)
 * [PHD CTF](http://www.phdays.com/)
 * [SECUINSIDE CTF](http://secuinside.com/)
 * [Codegate CTF](http://ctf.codegate.org/html/Main.html?lang=eng)
 * [Boston Key Party CTF](http://bostonkeyparty.net/)
 * [ZeroDays CTF](https://zerodays.ie/)
 * [Insomni’hack](https://insomnihack.ch/)
 * [Pico CTF](https://picoctf.com/)
 * [prompt(1) to win](http://prompt.ml/) - XSS Challenges
 * [HackTheBox](https://www.hackthebox.eu/)

## General

 * [Hack+](http://hack.plus) - An Intelligent network of bots that fetch the latest InfoSec content.
 * [CTFtime.org](https://ctftime.org/) - All about CTF (Capture The Flag)
 * [WeChall](http://www.wechall.net/)
 * [CTF archives (shell-storm)](http://shell-storm.org/repo/CTF/)
 * [Rookit Arsenal](https://amzn.com/144962636X) - OS RE and rootkit development
 * [Pentest Cheat Sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets) - Collection of cheat sheets useful for pentesting
 * [Movies For Hackers](https://github.com/k4m4/movies-for-hackers) - A curated list of movies every hacker & cyberpunk must watch.
 * [Roppers CTF Fundamentals Course](https://www.roppers.org/courses/ctf) - Free course designed to get a student crushing CTFs as quickly as possible. Teaches the mentality and skills required for crypto, forensics, and more. Full text available as a [gitbook](https://www.hoppersroppers.org/ctf/).

# OS

## Online resources

 * [Security related Operating Systems @ Rawsec](https://inventory.raw.pm/operating_systems.html) - Complete list of security related operating systems
 * [Best Linux Penetration Testing Distributions @ CyberPunk](https://n0where.net/best-linux-penetration-testing-distributions/) - Description of main penetration testing distributions
 * [Security @ Distrowatch](http://distrowatch.com/search.php?category=Security) - Website dedicated to talking about, reviewing and keeping up to date with open source operating systems


# Post exploitation

## tools
* [empire](https://github.com/EmpireProject/Empire) - A post exploitation framework for powershell and python.
* [silenttrinity](https://github.com/byt3bl33d3r/SILENTTRINITY) - A post exploitation tool that uses iron python to get past powershell restrictions.
* [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) - A PowerShell post exploitation framework
* [ebowla](https://github.com/Genetic-Malware/Ebowla) - Framework for Making Environmental Keyed Payloads

# ETC

 * [SecTools](http://sectools.org/) - Top 125 Network Security Tools
 * [Roppers Security Fundamentals](https://www.roppers.org/courses/security) - Free course that teaches a beginner how security works in the real world. Learn security theory and execute defensive measures so that you are better prepared against threats online and in the physical world. Full text available as a [gitbook](https://www.hoppersroppers.org/security/).
 * [Roppers Practical Networking](https://www.roppers.org/courses/networking) - A hands-on, wildly practical introduction to networking and making packets dance. No wasted time, no memorizing, just learning the fundamentals.
 * [Rawsec's CyberSecurity Inventory](https://inventory.raw.pm/) - An open-source inventory of tools, resources, CTF platforms and Operating Systems about CyberSecurity. ([Source](https://gitlab.com/rawsec/rawsec-cybersecurity-list))
 * [The Cyberclopaedia](https://cr0mll.github.io/cyberclopaedia/) - The open-source encyclopedia of cybersecurity. [GitHub Repository](https://github.com/cr0mll/cyberclopaedia)

