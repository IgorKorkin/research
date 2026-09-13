# Research Results

[![Main Page](https://img.shields.io/badge/Main_Page-igorkorkin.github.io-0969DA?logo=githubpages&logoColor=white)](https://igorkorkin.github.io/)
[![Research Archive](https://img.shields.io/badge/Research_Archive-igorkorkin.github.io%2Fresearch-2E7D32?logo=openaccess&logoColor=white)](https://igorkorkin.github.io/research/)
[![GitHub Pages](https://img.shields.io/github/check-suites/IgorKorkin/research/main?label=GitHub%20Pages&logo=githubactions)](https://github.com/IgorKorkin/research/actions/workflows/pages/pages-build-deployment)

## Research Evolution

Rootkit Detection & Memory Forensics → Hypervisor Detection → Hypervisor-based Kernel Protection → Attacks on Telemetry → Desktop Protection.

| Period | Research direction and key result | Key materials |
| :---: | --- | --- |
| 2009–2015 | **Memory Forensics for Rootkit Detection**<br>Detection of kernel-mode rootkits and hidden OS structures through memory dump analysis | [Applying Memory Forensics to Rootkit Detection](https://commons.erau.edu/adfsl/2014/wednesday/1/) |
| 2010–2014 | **Stealthy Hypervisor Detection**<br>Detection of hidden hypervisors under compromised timing counters (time cheating) and unstable timing measurements | • [PhD dissertation (Russian): «Методика обнаружения нелегитимного программного обеспечения, использующего технологию аппаратной виртуализации»](https://search.rsl.ru/ru/record/01005409054)<br>• [Two Challenges of Stealthy Hypervisors Detection: Time Cheating and Data Fluctuations](https://commons.erau.edu/jdfsl/vol10/iss2/2/) |
| 2016–2022 | **MemoryRanger — Hypervisor-based Kernel Protection**<br>Development of hypervisor-based OS protection mechanisms using Intel VT-x/EPT: HyperPlatform, running drivers in isolated memory enclaves, and research into new attacks on Windows kernel objects | • [GitHub](https://github.com/IgorKorkin/MemoryRanger)<br>• [Black Hat Europe 2018](https://blackhat.com/archive/europe/2018/speakers/Igor-Korkin.html) |
| 2019–2022 | **Security Telemetry Under Attack**<br>Development and analysis of new attacks on ETW/WMI to blind EDR/SIEM systems and research into improving the resilience of security monitoring | • [Black Hat Europe 2021 — ETW](https://blackhat.com/archive/europe/2021/briefings/schedule/speakers.html#igor-korkin-34812)<br>• [Black Hat USA 2022 — WMI](https://blackhat.com/archive/usa/2022/briefings/schedule/speakers.html#igor-korkin-34812)<br>• [Microsoft Defender Will Be Defended: MemoryRanger Prevents Blinding Windows AV](https://commons.erau.edu/adfsl/2022/presentations/7/) |
| 2025–2026 | **DesktopRanger — Windows Desktop Isolation**<br>Hardening Windows Desktop isolation and protecting user input | • [GitHub](https://github.com/IgorKorkin/DesktopRanger)<br>• [OFFZONE 2026](https://offzone.moscow/eng/program/beyond-secure-desktop-abusing-and-hardening-windows-desktop-isolation/) |

A complete chronology of earlier publications, talks, and research projects is available in the [research archive](https://sites.google.com/site/igorkorkin).

## Monograph

A systematic treatment of research on OS kernel protection, memory, drivers, and techniques for detecting hidden code under active adversarial countermeasures.

| Year | Publication | Publisher |
| :---: | --- | --- |
| 2026 | [Защита ядра операционных систем в условиях противодействия](https://igorkorkin.github.io/monograph/)<br>*Kernel Protection of Operating Systems Under Countermeasures* | INFRA-M |

## Current Research and Talks

| Year | Work | Type | Venue |
| :---: | --- | :---: | --- |
| 2025 | [О подходе к защите приложений класса «менеджер паролей» от перехвата клавиатурного ввода](2025/2025--Conference--KIB-MEPhI--Academic/README.md) | Conference abstract | KIB-2025, MEPhI, Moscow, Russia |
| 2026 | [Метод управления правами доступа к объектам рабочего стола Windows для защиты пользовательского ввода](2026/2026--Conference--MITSOBI--Academic/README.md) | Conference abstract | MITSOBI-2026, Saint Petersburg, Russia |
| 2026 | [DesktopRanger Blocks Keystroke Spying: Hardening Windows Desktop Isolation](2026/2026--Conference--Pass-the-SALT/README.md) | Talk | Pass the SALT 2026, Lille, France |
| 2026 | [Secure Desktop Is Not Secure: DesktopRanger Against High-Privilege Keyloggers](2026/2026--Conference--Standoff-Talks/README.md) | Talk | StandOff Talks 2026, Moscow, Russia |
| 2026 | [Weaponizing Intelligence: AI in the Hacker's Arsenal](2026/2026--Paper--eForensics-HAKIN9/README.md) | Article | eForensics, Warsaw, Poland |
| 2026 | [Beyond Secure Desktop: Abusing and Hardening Windows Desktop Isolation](2026/2026--Conference--OFFZONE/README.md) | Talk | OFFZONE 2026, Moscow, Russia |
| 2026 | [ARTIFICIAL INTELLIGENCE IN THE ARSENAL OF AN INTRUDER: ANALYSIS OF NEW CHALLENGES TO INFORMATION SECURITY](2026/2026--Paper--Cyberrus_4(75)/README.md) <br> ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ В АРСЕНАЛЕ НАРУШИТЕЛЯ: АНАЛИЗ НОВЫХ ВЫЗОВОВ ИНФОРМАЦИОННОЙ БЕЗОПАСНОСТИ | Paper | Voprosy kiberbezopasnosti, Moscow, Russia |
