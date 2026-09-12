# Результаты исследований

[![Main Page](https://img.shields.io/badge/Main_Page-igorkorkin.github.io-0969DA?logo=githubpages&logoColor=white)](https://igorkorkin.github.io/)
[![Research Archive](https://img.shields.io/badge/Research_Archive-igorkorkin.github.io%2Fresearch-2E7D32?logo=openaccess&logoColor=white)](https://igorkorkin.github.io/research/)
[![GitHub Pages](https://img.shields.io/github/check-suites/IgorKorkin/research/main?label=GitHub%20Pages&logo=githubactions)](https://github.com/IgorKorkin/research/actions/workflows/pages/pages-build-deployment)

## Исследовательская линия

Основная линия исследований — **анализ и усиление границ безопасности операционных систем в условиях активного противодействия атакующего**.

| Период | Направление | Ключевой результат | Основные материалы |
| :---: | --- | --- | --- |
| 2009–2015 | **Memory Forensics for Rootkit Detection** | Выявление kernel-mode rootkits и скрытых структур ОС на основе анализа содержимого дампа памяти | [Applying Memory Forensics to Rootkit Detection](https://commons.erau.edu/adfsl/2014/wednesday/1/) |
| 2010–2014 | **Stealthy Hypervisor Detection** | Обнаружение скрытых гипервизоров, включая противодействие time cheating и нестабильности временных измерений | • [Кандидатская диссертация: «Методика обнаружения нелегитимного программного обеспечения, использующего технологию аппаратной виртуализации»](https://search.rsl.ru/ru/record/01005409054)<br>• [Two Challenges of Stealthy Hypervisors Detection: Time Cheating and Data Fluctuations](https://commons.erau.edu/jdfsl/vol10/iss2/2/) |
| 2016–2022 | **MemoryRanger — Hypervisor-based Kernel Protection** | Развитие гипервизорных механизмов защиты на базе VT-x/EPT: от ранних экспериментов с HyperPlatform до изоляции драйверов, памяти и объектов ядра Windows | • [GitHub](https://github.com/IgorKorkin/MemoryRanger)<br>• [Black Hat Europe 2018](https://blackhat.com/archive/europe/2018/speakers/Igor-Korkin.html) |
| 2019–2022 | **Security Telemetry Under Attack** | Разработка и исследование новых атак на ETW/WMI для ослепления EDR/SIEM и методов повышения устойчивости средств мониторинга | • [Black Hat Europe 2021 — ETW](https://blackhat.com/archive/europe/2021/briefings/schedule/speakers.html#igor-korkin-34812)<br>• [Black Hat USA 2022 — WMI](https://blackhat.com/archive/usa/2022/briefings/schedule/speakers.html#igor-korkin-34812)<br>• [Microsoft Defender Will Be Defended: MemoryRanger Prevents Blinding Windows AV](https://commons.erau.edu/adfsl/2022/presentations/7/) |
| 2025–2026 | **DesktopRanger — Windows Desktop Isolation** | Усиление Windows Desktop isolation и защита пользовательского ввода | • [GitHub](https://github.com/IgorKorkin/DesktopRanger)<br>• [OFFZONE 2026](https://offzone.moscow/eng/program/beyond-secure-desktop-abusing-and-hardening-windows-desktop-isolation/) |

Исследовательская линия: Memory Forensics → Hypervisor Detection → Kernel Protection → Trusted Telemetry → User Interaction Protection.

Полная хронология более ранних публикаций, докладов и исследовательских проектов доступна в [исследовательском архиве](https://sites.google.com/site/igorkorkin).

## Монография

| Год | Издание | Роль |
| :---: | --- | --- |
| 2026 | [Защита ядра операционных систем в условиях противодействия](https://igorkorkin.github.io/monograph/) | Систематизация исследований по защите ядра ОС, памяти, драйверов и механизмов изоляции в условиях активного воздействия атакующего |

## Актуальные исследования и выступления

| Год | Название работы | Тип | Площадка |
| :---: | --- | :---: | --- |
| 2025 | [О подходе к защите приложений класса «менеджер паролей» от перехвата клавиатурного ввода](2025/2025--Conference--KIB-MEPhI--Academic/README.md) | Тезисы доклада | КИБ-2025, МИФИ, Москва, Россия |
| 2026 | [Метод управления правами доступа к объектам рабочего стола Windows для защиты пользовательского ввода](2026/2026--Conference--MITSOBI--Academic/README.md) | Тезисы доклада | МИТСОБИ-2026, Санкт-Петербург, Россия |
| 2026 | [DesktopRanger Blocks Keystroke Spying: Hardening Windows Desktop Isolation](2026/2026--Conference--Pass-the-SALT/README.md) | Доклад | Pass the SALT 2026, Лилль, Франция |
| 2026 | [Secure Desktop Is Not Secure: DesktopRanger Against High-Privilege Keyloggers](2026/2026--Conference--Standoff-Talks/README.md) | Доклад | StandOff Talks 2026, Москва, Россия |
| 2026 | [Weaponizing Intelligence: AI in the Hacker's Arsenal](2026/2026--Paper--eForensics-HAKIN9/README.md) | Статья | eForensics, Варшава, Польша |
| 2026 | [Beyond Secure Desktop: Abusing and Hardening Windows Desktop Isolation](2026/2026--Conference--OFFZONE/README.md) | Доклад | OFFZONE 2026, Москва, Россия |
