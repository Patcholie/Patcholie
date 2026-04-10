![header](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:b8860b,100:1a1a2e&height=200&section=header&text=Aviv%20Shaked&fontSize=60&fontColor=FFD700&fontAlignY=38&desc=Cybersecurity%20Developer%20%26%20Researcher&descAlignY=55&descSize=20&animation=fadeIn)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&amp;size=18&amp;pause=1000&amp;color=FFD700&amp;center=true&amp;vCenter=true&amp;width=600&amp;height=50&amp;lines=Network+Steganography+%7C+Exploit+Dev;Reverse+Engineering+%7C+Binary+Exploitation;C%2B%2B20+%7C+Low-Level+Systems+%7C+Linux;Building+what+shouldn't+exist." />
</p>

<p align="center">
  <a href="https://linkedin.com/in/aviv-shaked-59a4b7271"><img src="https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=flat-square&amp;logo=linkedin&amp;logoColor=white"/></a>
  &nbsp;
  <a href="https://patcholie.github.io"><img src="https://img.shields.io/badge/patcholie.github.io-FFD700?style=flat-square&amp;logo=github&amp;logoColor=0d1117"/></a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=patcholie&amp;style=flat-square&amp;color=b8860b&amp;label=visitors"/>
</p>

---

C++20 systems programmer and cybersecurity researcher. I build at the deepest level of the stack: kernel-level packet interception, bit-precise protocol manipulation, production-grade cryptographic pipelines. Grounded in **Magshimim+**, Israel's elite national cybersecurity program, advanced track. Extended aggressively through independent research and self-teaching. Active investor and day trader, 2+ years.

---

## Featured Project

### [HitchHiker](https://patcholie.github.io) - Network Steganography Platform

*Co-developed with [Daniel Varkin](https://github.com/marmust) · Repo private · Architecture at [patcholie.github.io](https://patcholie.github.io)*

A production platform for covert communication via pure network steganography. Messages are **encrypted, fragmented, and embedded into unused fields of live network traffic**. No new packets are ever generated. Data rides what's already moving. **Undetectable by design.**

- **HitchHikerAPI** - a unified interface layer consumed by both client and server; neither side knows the underlying protocol mechanics
- **Pluggable carrier architecture** - steganographic embedding targets are fully modular; adding or removing a protocol carrier changes nothing else
- **Three independent CMake targets** - `hitchhiker_lib` (core: crypto, fragmentation, transport, embedding), `hitchhiker_server` (headless: packet interception, storage, routing), `hitchhiker_client` (full TUI via FTXUI)
- **Full applied cryptography stack** - key exchange, symmetric encryption, key derivation, password hashing, all in production via Crypto++
- Server deployed on AWS EC2, clients run on Linux via Docker

`C++20` `CMake` `Crypto++` `NFQueue` `iptables` `FTXUI` `Redis` `SQLite` `spdlog` `Docker` `OpenVPN` `AWS EC2`

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

**[HitchHiker](https://patcholie.github.io)** - C++20, 2025-26

Covert communication via network steganography. Zero new packets. Zero observable network presence.

</td>
<td width="50%" valign="top">

**Multiplayer Trivia System** - C++, 2024

Custom application-layer protocol, concurrent TCP server, C# Unity client, SQLite backend. Scored **130/100**.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Analisis](https://github.com/Patcholie/Analisis)** - Python, 2023

AI wound treatment platform. **2nd globally, AI4Y World Competition 2023.**

</td>
<td width="50%" valign="top">

**Mancala-AI** - Python, PyTorch, 2025-26

Multi-agent AI framework with a neural network agent trained via self-play. Full training and tournament evaluation pipeline.

</td>
</tr>
</table>

---

## Skills

**Languages**

![C++](https://img.shields.io/badge/C++20-%2300599C.svg?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-%2300599C.svg?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-%234EAA25.svg?style=flat-square&logo=gnubash&logoColor=white)
![x86-64 ASM](https://img.shields.io/badge/x86--64_ASM-%23444444.svg?style=flat-square)
![C#](https://img.shields.io/badge/C%23-%23512BD4.svg?style=flat-square&logo=csharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-%23003B57.svg?style=flat-square&logo=sqlite&logoColor=white)

**Security & Reversing**

![Binary Ninja](https://img.shields.io/badge/Binary_Ninja-%235C4EE5.svg?style=flat-square)
![IDA Pro](https://img.shields.io/badge/IDA_Pro-%23444444.svg?style=flat-square)
![Ghidra](https://img.shields.io/badge/Ghidra-%23FF0000.svg?style=flat-square)
![GDB](https://img.shields.io/badge/GDB-%23A42E2B.svg?style=flat-square)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-%23FF6633.svg?style=flat-square&logo=burpsuite&logoColor=white)
![HackTheBox](https://img.shields.io/badge/HackTheBox-%239FEF00.svg?style=flat-square&logo=hackthebox&logoColor=0d1117)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-%23557C94.svg?style=flat-square&logo=kalilinux&logoColor=white)

**Networking**

![Wireshark](https://img.shields.io/badge/Wireshark-%231679A7.svg?style=flat-square&logo=wireshark&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy-%233776AB.svg?style=flat-square&logo=python&logoColor=white)
![nmap](https://img.shields.io/badge/nmap-%230E83CD.svg?style=flat-square)
![tcpdump](https://img.shields.io/badge/tcpdump-%23444444.svg?style=flat-square)
![netcat](https://img.shields.io/badge/netcat-%23444444.svg?style=flat-square)

**Infrastructure & Tooling**

![Linux](https://img.shields.io/badge/Linux-%23FCC624.svg?style=flat-square&logo=linux&logoColor=0d1117)
![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=flat-square&logo=docker&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-%23064F8C.svg?style=flat-square&logo=cmake&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23FF4438.svg?style=flat-square&logo=redis&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-%23FF9900.svg?style=flat-square&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05032.svg?style=flat-square&logo=git&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-%23F7931E.svg?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-%23FFD21E.svg?style=flat-square&logo=huggingface&logoColor=0d1117)
![OpenAI](https://img.shields.io/badge/OpenAI-%23412991.svg?style=flat-square&logo=openai&logoColor=white)

**Domains:** Network Protocols (L2-L7) · Steganography · **Binary Exploitation** · **ROP Chains** · Format String Exploits · **Reverse Engineering** · Covert Channels · Threat Modeling · Web Security (SQLi, XSS/CSRF, JWT, JS Deobfuscation) · Anti-debug Bypass · Kernel-level Packet Interception · Protocol Analysis

---

## Education & Recognition

| | |
|---|---|
| **Magshimim+ Advanced Track** | Israel's elite national cybersecurity program, advanced track · 2023-2026 |
| **BOSMAT, Haifa** | Computer Science + AI · 10 study units (maximum track) · 2020-2026 |
| **2nd Place - AI4Y World Competition** | Global · 2023 |
| **Topstep Trading Certificate** | 2025-2026 |

---

## Stats

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=patcholie&amp;hide_border=true&amp;ring=FFD700&amp;fire=DAA520&amp;currStreakLabel=FFD700&amp;sideLabels=888888&amp;dates=888888&amp;background=0d1117&amp;sideNums=FFD700&amp;currStreakNum=FFD700&amp;stroke=b8860b"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=patcholie&amp;bg_color=0d1117&amp;color=FFD700&amp;line=b8860b&amp;point=DAA520&amp;area=true&amp;area_color=b8860b&amp;hide_border=true&amp;radius=8"/>
</p>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:b8860b,100:0d1117&height=120&section=footer)
