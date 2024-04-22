# <p align="center">Этичный Хакинг
</p>

![h](https://gist.githubusercontent.com/Samsar4/62886aac358c3d484a0ec17e8eb11266/raw/89f706846f97cd3e59880dbc03e4f1d5f8023783/header-ehl.jpg)

* * *

> **⚠️ ДИСКЛЕЙМЕР**:
*Данный репозиторий является ни чем инным как "фанатской" адоптацией(локализцией) [оригинального репозитория](https://github.com/Samsar4/Ethical-Hacking-Labs) на русский язык.*

* * * 

Данная подборка туториалов и лаб сделана сугубо для людей изучающих этичный хакинг, кибербезопасность, сеть и системное администрирование. Эти туториалы приводят информацию содержащуюся на [CEH](https://www.eccouncil.org/train-certify/certified-ethical-hacker-ceh-v12/) и прочих источников из интернета.

⌨️ Данные туториалы ориентированы на практическую составляющую. Не волнуйтесь, если вы полный нуб, вам не нужно быть техножрецом 80+ лвл, чтобы начать изучение этичного хакинга. **Помните, Гугл - ваш лучши друг.** Этот репозиторий проведёт вас по пути от самых основ до более продвинутых приёмов.

**✅ Системные требования**:
* Любой компьютер с как минимум 8ГБ RAM (рекомендуется 16ГБ)
* Хотя бы 80ГБ свободного места на вашем жёстком диске
* Аппаратная поддержка виртуализации

* * *

> **⚠️ Дисклеймер**:
*Данный материал предоставлен сугубо в академических целях. НЕ используйте следующие техники в любых публичных сетях. Потому как, если вас признают виновным в причинении какого-либо вреда какому-либо лицу, правительству, корпоративному органу, некоммерческой организации и т. д., вам будет предъявлен иск по обвинению в киберпреступлении/ях. Я рекомендую вам попрактиковаться в уроках этого курса на вашей собственной системе и ваших собственных данных в частной или локальной сети.*

* * * 

## ⚙️ Базовые знания
Итак, для начала вам нужно разобраться как всё работает, прежде чем приступать к разборке и поиску уязвимостей. Чем больше вы поймёте, тем более хорошим хацкером вы станете. "Базовые знания" (модуль 0) представляет собой быстрый ввод в курс дела.

**Базовые знания содержат введение по работе с сетями, системами Linux, виртуализацией, созданием лабораторий, написанием скриптов, а также темами информационной безопасности. Если вы знакомы с этими темами, вы можете сразу перейти к модулю Этического взлома.**

* [Сеть 101](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/0-Core-Knowledge/0-Networking-101.md)
* [Создание лаборатории / Виртуализация](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/0-Core-Knowledge/1-Lab-Building.md)
* [Введение в Linux](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/0-Core-Knowledge/2-Intro-to-Linux.md)
* [Скриптование]
* [Информационная безопасность 101](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/0-Core-Knowledge/4-Infosec-101.md)

## ⚔️ Этичный Хакинг
1. **Футпринтинг и Разведка**
    * [Введение](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/1-Footprinting-and-Reconnaissance/0-What-is-Footprinting.md)
    * [Командная строка Windows](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/1-Footprinting-and-Reconnaissance/1-Windows-CommandLine.md)
    * [Основы Maltego](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/1-Footprinting-and-Reconnaissance/2-Maltego-Basics.md)
    * [Recon-ng](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/1-Footprinting-and-Reconnaissance/3-Recon-ng.md)
    * [OSRFramework](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/1-Footprinting-and-Reconnaissance/4-OSRFramework.md)
    * [Metasploit](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/1-Footprinting-and-Reconnaissance/5-Metasploit-Basics.md)
    * [theHarvester](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/1-Footprinting-and-Reconnaissance/6-theHarvester.md)
    * [Прочие инструменты для Разведки](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/1-Footprinting-and-Reconnaissance/7-Other-Tools.md)
2. **Scanning Networks**
    * [Introduction](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/2-Scanning-Networks/0-Scanning-a-Target-Network.md)
    * [hping3](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/2-Scanning-Networks/1-hping3.md)
    * [Detect OS's by TTL using Wireshark](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/2-Scanning-Networks/2-TTL.md)
    * [Mega Ping](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/2-Scanning-Networks/3-MegaPing.md)
    * [Nmap Basics](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/2-Scanning-Networks/4-Nmap.md)
    * [Avoid Detection with Nmap](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/2-Scanning-Networks/5-NmapDecoyIP.md)
    * [More Windows GUI Tools](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/2-Scanning-Networks/6-WindowsTools.md)
3. **Enumeration**
    * [Introduction](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/3-Enumeration/0-Introduction.md)
    * [Enumeration with Nmap](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/3-Enumeration/1-Enumerating-with-Nmap.md)
    * [SNMP Enumeration](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/3-Enumeration/2-SNMP-Enumeration.md)
    * [Enum4Linux](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/3-Enumeration/3-Enum4linux-Win-and-Samba-Enumeration.md)
    * [More Windows GUI Tools](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/3-Enumeration/4-Windows-EnumerationTools.md)
4. **Vulnerability Analysis**
    * [Overview and Tools](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/4-Vulnerability-Analysis/Overview-and-Tools.md) 
5. **System Hacking**
    * [Introduction](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/5-System-Hacking/0-Introduction.md)
    * [LLMNR / NBT-NS Spoofing](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/5-System-Hacking/1-LLMNR-NBT-NS.md)
    * [Dumping and Cracking SAM hashes](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/5-System-Hacking/2-SAM-Hashes.md)
    * [Rainbow Tables](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/5-System-Hacking/3-Rainbow-tables.md)
    * [Establishing a VNC Session](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/5-System-Hacking/4-VNC-Session.md)
    * [Escalating Privileges](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/5-System-Hacking/5-Escalating-Privileges.md)
    * [Hacking Windows with MS Word file](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/5-System-Hacking/6-Hacking-Windows-with-Doc-file.md)
    * [Hacking Windows with Msf/Meterpreter - Post Exploitation](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/5-System-Hacking/7-Hacking-Windows-with-Metasploit-PostExploitation.md)
    * [Hiding Data - NTFS streams](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/5-System-Hacking/8-NTFS-Streams.md)
    * [Hiding Data - Steganography](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/5-System-Hacking/9-Steganography.md)
    * [Using Covert_TCP](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/5-System-Hacking/10-Covert_TCP.md)
    * [Auditpol basics](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/5-System-Hacking/11-Auditpol.md)
    * [More Windows GUI Tools](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/5-System-Hacking/12-WindowsTools.md)
6. **Malware** 
    * [Introduction](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/6-Malware/0-Introduction.md)
    * [njRAT](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/6-Malware/1-Using-njRAT.md)
    * [HTTP RAT Trojan](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/6-Malware/2-HTTP-Trojan.md)
    * [Obfuscating a Trojan using SwayzCryptor](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/6-Malware/3-Obfuscating-Trojan-SwayzCryptor.md)
    * [Malware Analysis Lab](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/6-Malware/4-Malware-Analysis-Lab.md)
    * [Windows Tools](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/6-Malware/5-Windows-Tools.md)
7. **Sniffing**
    * [Introduction](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/7-Sniffing/0-Introduction.md)
    * [MITM using BetterCAP](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/7-Sniffing/1-MITM-with-Bettercap.md)
    * [MAC Address Spoofing](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/7-Sniffing/2-Spoofing-MAC-address.md)
    * [Windows Tools](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/7-Sniffing/x-Windows-Tools.md)
8. **Social Engineering**
    * [Introduction](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/8-Social-Engineering/0-Introduction.md)
    * [Using SET](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/8-Social-Engineering/1-Using-SET.md)
    * [Tools](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/8-Social-Engineering/X-Tools.md)
9. **Denial-of-Service**
    * [Introduction](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/9-Denial-of-Service/0-Introduction.md)
    * [SYN Flooding](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/9-Denial-of-Service/1-SYN-Flooding.md)
    * [DDoS using HOIC](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/9-Denial-of-Service/2-DDoS-using-HOIC.md)
    * [Detecting DoS Traffic](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/9-Denial-of-Service/3-Detecting-DoS-Traffic.md)
10. **Session Hijacking**
    * [Introduction](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/10-Session-Hijacking/0-Introduction.md)
    * [Using ZAP - Zed Attack Proxy](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/10-Session-Hijacking/1-Using-ZAP.md)
    * [Intercepting HTTP Traffic](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/10-Session-Hijacking/2-Intercepting-HTTP-Traffic.md)
11. **Bonus - 🔬 The Forensic Approach**
    * [TCPDump](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/11-Bonus/TCPDump-Tutorial.md)
    * [Dissecting Packets](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/11-Bonus/Dissecting-packets.md)
    * [ExifTool](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/11-Bonus/ExifTool-Tutorial.md)
    * [hdparm & dd command](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/11-Bonus/Using-hdparm-and-dd-command.md)
    * [Recovering a Deleted Partition](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/11-Bonus/Recovering-Deleted-Partition.md)
    * [Recovering Deleted Files](https://github.com/BezShkvark0/Ethical-Hacking-Labs/blob/master/11-Bonus/Recovering-Deleted-Files.md)

* * * 

**💭 To Do**:
- ![](https://img.shields.io/badge/status-in%20progress-orange)
- Add Foundational level modules (~~networking~~, ~~virtualization~~, crypto, linux kernel and scripting).
- Bonus modules to add:
    - ~~Introduction to Infosec terms and methodologies (from [CEH Study Guide](https://github.com/Samsar4/CEH-v10-Study-Guide))~~
    - More Reconnaissance techniques.
    - Active Directory: Lab build and attack vectors.
    - Web application: Enumeration and exploitation using some OWASP Top 10 vulnerabilities and Bug Bounty techniques.
    - Wireless hacking (WPA)
