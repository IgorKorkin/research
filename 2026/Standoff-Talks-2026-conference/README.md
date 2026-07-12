# StandOff Talks 2026 | DesktopRanger

<p align="center">
  <img src="2026-06-18%2015-09-41_lev4nko.jpg" alt="Igor Korkin speaking at StandOff Talks 2026" width="400">
  <img src="2026-06-18%2015-13-50_lev4nko.jpg" alt="DesktopRanger presentation at StandOff Talks 2026" width="400">
</p>

## Talk

* **Titles:** 
  * "Secure Desktop Is Not Secure: DesktopRanger Against High-Privilege Keyloggers"
  * "Не такой уж Secure Desktop: как DesktopRanger противостоит привилегированным кейлоггерам"
  * "Безопасный рабочий стол небезопасен: DesktopRanger против кейлоггеров с высокими привилегиями"

* **Speaker:** Igor Korkin
* **Event:** StandOff Talks 2026
* **Date:** June 18, 2026
* **Location:** Moscow, Russia
* **Format:** Conference presentation
* **Language:** Russian
* **Recorded Talk:**

  * [▶ Watch on YouTube](https://www.youtube.com/watch?v=JwTZBnUFuek&list=PLPRuLqtaT63c&index=14)
  * [▶ Watch on RuTube](https://rutube.ru/video/bce4a072dea4eadf58cb9501e07935b1/?playlist=1694167)
  * [▶ Watch on VK Video](https://vkvideo.ru/video-227564222_456239239?pl=-227564222_15)

## Citation

### ГОСТ

Коркин И. Ю. Не такой уж Secure Desktop: как DesktopRanger противостоит привилегированным кейлоггерам : доклад на конференции StandOff Talks 2026, Москва, 18 июня 2026 г. URL: https://github.com/IgorKorkin/research/tree/main/2026/Standoff-Talks-2026-conference (дата обращения: 12.07.2026).

### APA 7

Korkin, I. (2026, June 18). *Secure desktop is not secure: DesktopRanger against high-privilege keyloggers* [Conference presentation]. StandOff Talks 2026, Moscow, Russia. https://github.com/IgorKorkin/research/tree/main/2026/Standoff-Talks-2026-conference


## Abstract

### Secure Desktop Is Not Secure: DesktopRanger Against High-Privilege Keyloggers

We type secrets—passwords, documents, and private messages—and this sensitive input still passes through ordinary desktop applications. Windows Desktop isolation moves it away from the Default desktop and protects it from basic keyloggers.

However, high-privilege user-mode keyloggers can enumerate desktops, open them by name, switch to a target desktop, or launch a helper keylogger inside it. Under these conditions, Secure Desktop becomes a visual separation mechanism rather than a reliable input-confidentiality boundary.

The talk reviews open-source attacks against Secure Desktop and presents a research keylogger prototype that combines `SetWindowsHookEx`, `GetAsyncKeyState`, Raw Input, DirectInput, Desktop-object enumeration, and cross-desktop process relaunch.

The defensive part introduces **DesktopRanger**, an open-source prototype that hardens Windows Desktop isolation using a restrictive security descriptor, desktop-enumeration restrictions, and controlled trusted-application launch.

On a recent Windows 11 x64 build, DesktopRanger blocks the interception of a test password phrase across all implemented techniques, even when the keylogger runs as a regular user, administrator, or `NT AUTHORITY\SYSTEM`.

## Описание доклада

### «Не такой уж Secure Desktop: как DesktopRanger противостоит привилегированным кейлоггерам»

Мы вводим множество секретов: пароли, документы и сообщения. Механизм Windows Desktop позволяет перенести такой ввод с Default Desktop на отдельный рабочий стол, однако защищает его преимущественно от базовых кейлоггеров.

Привилегированные кейлоггеры могут перечислять рабочие столы, открывать их по имени, переключаться на целевой рабочий стол или запускать на нём собственный процесс. В этом случае Secure Desktop становится механизмом визуального разделения, но не полноценной границей конфиденциальности пользовательского ввода.

В докладе рассматриваются открытые проекты, реализующие атаки на Secure Desktop, и представлен исследовательский прототип кейлоггера, использующий `SetWindowsHookEx`, `GetAsyncKeyState`, Raw Input, DirectInput, перечисление Desktop-объектов и перезапуск процесса на других рабочих столах.

Защитная часть посвящена **DesktopRanger** — open-source прототипу, который усиливает изоляцию Windows Desktop с помощью ограничительного дескриптора безопасности, запрета перечисления защищённых рабочих столов и контролируемого запуска доверенных приложений.

На актуальной сборке Windows 11 x64 DesktopRanger блокирует перехват тестовой парольной фразы для всех реализованных техник, даже если кейлоггер запущен от имени пользователя, администратора или `NT AUTHORITY\SYSTEM`.

## Open-Source Project

* [DesktopRanger on GitHub](https://github.com/IgorKorkin/DesktopRanger)

## Conference Materials

* [StandOff Talks media archive](https://storage.ptsecurity.com/d/4686c3b14a0c42f0b062/?p=%2F18%20%D0%B8%D1%8E%D0%BD%D1%8F&mode=list)

## Additional Materials

* Official participation letter ([View PDF](letter_igor_korkin_STF-Talks.pdf))

<p align="center">
  <a href="letter_igor_korkin_STF-Talks.pdf">
    <img src="letter_igor_korkin_STF-Talks.png" alt="Official participation letter for StandOff Talks 2026" width="700">
  </a>
</p>
