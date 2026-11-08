# KCon 2026 | When AI Agents Become Processes: Native Windows Isolation for Autonomous Code

<!-- markdownlint-disable MD033 -->
<p align="center">
  <img src="hello.webp" alt="Igor Korkin at 14th KCon Conference 2026" width="400">  
  <br>
  <img src="kcon.webp" alt="Pass the SALT 2026 logo" width="400">
</p>
<!-- markdownlint-enable MD033 -->

## Talk

* **Title:** When AI Agents Become Processes: Native Windows Isolation for Autonomous Code
* **Speaker:** Igor Korkin
* **Event:** 14th KCon Conference 2026 by Knownsec Security
* **Type:** Conference presentation
* **Date:** November 1, 2026
* **Venue:** Zhongguancun National Innovation Demonstration Zone Exhibition Center
* **Location:** Beijing, China
* **Language:** English
* [Watch the recorded talk](https://www.youtube.com/watch?v=BXX7slc5K9g)
* [DesktopRanger on GitHub](https://github.com/IgorKorkin/DesktopRanger)
* Letter-of-Appreciation:
  * [Chinese Original](./KCon-2026-Letter-of-Appreciation-chinese-original.pdf)
  * [Englishai-translated](./KCon-2026-Letter-of-Appreciation-english.pdf)
  * [Russian ai-translated](./KCon-2026-Letter-of-Appreciation-russian.pdf)

## Abstract

AI agents are evolving from conversational systems into autonomous applications capable of launching processes, invoking tools, accessing local resources, and interacting with the operating system on behalf of a user.

Once an AI agent becomes executable code, model-level controls are no longer sufficient; the resulting process must also be treated as potentially untrusted at the operating-system level.

This talk presents a practical Windows-native architecture for isolating autonomous AI code. At its core is the Windows Process Security Environment (PSEC). The prototype uses CreateProcessSecurityEnvironment, PROC_THREAD_ATTRIBUTE_SECURITY_ENVIRONMENT, and CreateProcessW to create processes inside a dedicated security environment. PSEC is also compared with the classic AppContainer model based on PROC_THREAD_ATTRIBUTE_SECURITY_CAPABILITIES.

This architecture is being implemented in a new tool, ZIL, which extends DesktopRanger with AppsIsolation—a layer combining three complementary Windows application-isolation techniques to provide both process-level and interactive isolation for autonomous code.

Process isolation is combined with process-tree containment and restricted resource access. The architecture then extends isolation into the Windows interactive subsystem by executing the agent on a dedicated Windows Desktop protected by a hardened security descriptor. This is critical because an autonomous process may attempt to interact with GUI objects, other Desktops, or user input.

Together, these mechanisms combine PSEC-based process isolation with Windows Desktop isolation to provide a broader execution boundary for autonomous and potentially untrusted code.

## Official Posts

* [WeiXin News](https://mp.weixin.qq.com/s/MYJU8bVitjiPVBrL350tkw)
* [Conference web-site](https://kcon.knownsec.com)

## How to Cite

### ГОСТ

<!-- markdownlint-disable MD033 -->
<table>
<tr>
<td>
Коркин И. Ю. When AI Agents Become Processes: Native Windows Isolation for Autonomous Code: доклад на конференции KCon 2026, Пекин, Китай, 1 ноября 2026 г.
</td>
</tr>
</table>
<!-- markdownlint-enable MD033 -->

### APA 7

<!-- markdownlint-disable MD033 -->
<table>
<tr>
<td>
Korkin, I. (2026, November 1). <em>When AI Agents Become Processes: Native Windows Isolation for Autonomous Code</em> [Conference presentation]. KCon 2026, Beijing, China.
</td>
</tr>
</table>
<!-- markdownlint-enable MD033 -->

### Letter of Appreciation

<!-- markdownlint-disable MD033 -->
<p align="center">
  <a href="KCon-2026-Letter-of-Appreciation-english.pdf">
    <img src="KCon-2026-Letter-of-Appreciation-english.png" alt="Letter of Appreciation" width="700">
  </a>
</p>
<!-- markdownlint-enable MD033 -->

### Official Announce Poster

<!-- markdownlint-disable MD033 -->
<p align="center">
  <img src="full-press-announce.webp" alt="Igor Korkin at 14th KCon Conference 2026" width="400">  
</p>
<!-- markdownlint-enable MD033 -->