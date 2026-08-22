# OFFZONE 2026 | Beyond Secure Desktop: Abusing and Hardening Windows Desktop Isolation

<!-- markdownlint-disable MD033 -->
<p align="center">  
  <a href="https://offzone.moscow/eng/program/beyond-secure-desktop-abusing-and-hardening-windows-desktop-isolation/">
    <img src="offzone_korkin_main_track.jfif" alt="Igor Korkin — OFFZONE 2026 speaker" width="400">
  </a>
</p>
<!-- markdownlint-enable MD033 -->

## Talk

* **Titles:**
  * **English:** Beyond Secure Desktop: Abusing and Hardening Windows Desktop Isolation
  * **Russian:** Практический анализ безопасности Windows Desktop: атаки кейлоггеров и способы защиты
* **Speaker:** Igor Korkin
* **Event:** OFFZONE 2026 — Seventh International Conference on Practical Cybersecurity
* **Organizer:** BI.ZONE
* **Type:** Conference presentation
* **Track:** Main Track
* **Level:** HARD
* **Date:** August 21, 2026
* **Time:** 15:00–16:00
* **Venue:** GOELRO
* **Location:** Moscow, Russia
* **Language:** Russian
* [OFFZONE 2026](https://offzone.moscow/eng/)
* [DesktopRanger on GitHub](https://github.com/IgorKorkin/DesktopRanger)

## Official Materials

* [Official talk page — English](https://offzone.moscow/eng/program/beyond-secure-desktop-abusing-and-hardening-windows-desktop-isolation/)
* [Официальная страница доклада — Русский](https://offzone.moscow/program/beyond-secure-desktop-abusing-and-hardening-windows-desktop-isolation/)

### Official Abstract — English

Running sensitive applications on a separate Windows Desktop is often treated as a reliable security boundary. The talk demonstrates practical attacks in which keyloggers abuse Windows Desktop isolation to intercept user keystrokes. It then introduces DesktopRanger, an open-source project that creates a hardened desktop through restrictive access control.

### Официальное описание — Русский

Запуск приложений, работающих с конфиденциальными данными, на отдельном Windows Desktop часто рассматривается как надежное решение по безопасности. В докладе демонстрируются практические атаки, в которых кейлоггеры используют недостатки Windows Desktop для перехвата нажатий клавиш. Затем представлен DesktopRanger — открытый проект, создающий защищенный рабочий стол за счет управления доступом к объектам Windows Desktop.

## Abstract

Running applications that handle sensitive data on a separate Windows Desktop is often treated as a reliable security boundary. The talk demonstrates practical attacks in which keyloggers abuse weaknesses in Windows Desktop isolation to intercept user keystrokes. It then introduces DesktopRanger, an open-source project that creates a hardened desktop through restrictive access control to Windows Window Station and Desktop objects.

## Extended Summary

Windows Desktop isolation can separate a sensitive application's user interface from the default interactive desktop, but the isolation boundary depends on access control to Window Station and Desktop objects. A sufficiently privileged user-mode attacker may still discover desktop objects, open them, relaunch code on a target desktop, or apply input-capture techniques from inside the target context.

The talk examines practical keyboard-input interception techniques including `SetWindowsHookEx`, `GetAsyncKeyState`, Raw Input, and DirectInput, and discusses how desktop enumeration, object access rights, and process placement affect the attack surface. The analysis also considers real-world secure-desktop implementations and the difference between hiding a desktop, restricting selected capabilities, and enforcing a restrictive access policy on the desktop object itself.

DesktopRanger demonstrates a sandbox-driven approach to protecting sensitive keyboard input without kernel hooks or continuous interception. The prototype creates a dedicated desktop, restricts access to the Window Station and Desktop objects, temporarily grants only the permissions required to launch a trusted process, and then returns the desktop to its protected state. Experiments on Windows 11 x64 evaluate attacks from regular-user, administrator, and `NT AUTHORITY\\SYSTEM` contexts.

The main conclusion is that a separate Windows Desktop should not be treated as a security boundary by itself: the effective boundary is the access policy applied to the underlying Windows objects.

## Описание доклада

Запуск приложений, работающих с конфиденциальными данными, на отдельном Windows Desktop часто рассматривается как надежная граница безопасности. Однако изоляция рабочего стола определяется не самим фактом создания отдельного Desktop, а политикой доступа к объектам Window Station и Desktop.

В докладе показаны практические техники перехвата клавиатурного ввода с использованием `SetWindowsHookEx`, `GetAsyncKeyState`, Raw Input и DirectInput, а также сценарии перечисления рабочих столов, открытия Desktop-объектов и запуска вспомогательного процесса на целевом рабочем столе. Отдельно рассматривается разница между сокрытием рабочего стола, запретом отдельных возможностей и строгим разграничением доступа к объекту Desktop.

Представлен DesktopRanger — open-source прототип, реализующий sandbox-driven подход к защите пользовательского ввода без драйверов ядра и постоянного перехвата событий. DesktopRanger создает отдельный рабочий стол, ограничивает доступ к объектам Window Station и Desktop, временно предоставляет только необходимые права для запуска доверенного приложения, после чего возвращает рабочий стол в защищенное состояние. Эксперименты в Windows 11 x64 рассматривают нарушителя с правами обычного пользователя, администратора и `NT AUTHORITY\\SYSTEM`.

Ключевой вывод: отдельный Windows Desktop сам по себе не является надежной границей безопасности; такой границей становится политика доступа к соответствующим объектам Windows.

## About OFFZONE 2026

OFFZONE 2026 was the seventh international conference on practical cybersecurity. The conference took place on August 20–21, 2026 at GOELRO in Moscow and brought together security specialists, developers, engineers, researchers, lecturers, and students. The program focused on technical and practical cybersecurity content, including real attack scenarios, vulnerability research, and defensive technologies.

## How to Cite

### ГОСТ

<!-- markdownlint-disable MD033 -->
<table>
<tr>
<td>
Коркин И. Ю. Практический анализ безопасности Windows Desktop: атаки кейлоггеров и способы защиты : доклад на VII Международной конференции по практической кибербезопасности OFFZONE 2026, Москва, 21 августа 2026 г.
</td>
</tr>
</table>
<!-- markdownlint-enable MD033 -->

### APA 7

<!-- markdownlint-disable MD033 -->
<table>
<tr>
<td>
Korkin, I. (2026, August 21). <em>Beyond Secure Desktop: Abusing and hardening Windows Desktop isolation</em> [Conference presentation]. OFFZONE 2026: Seventh International Conference on Practical Cybersecurity, Moscow, Russia.
</td>
</tr>
</table>
<!-- markdownlint-enable MD033 -->
