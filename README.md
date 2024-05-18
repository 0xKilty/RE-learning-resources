# RE-learning-resources
> Resources to learn more about reverse engineering and binary exploitation
## Contents
- [Tools](#tools)
    - [Disassemblers](#disassemblers)
    - [Programming](#programming)
    - [Other Tools](#other-tools)
- [Guides](#guides)
    - [Video Series](#video-series)
    - [Courses](#courses)
    - [Other Guides](#other-guides)
- [CTF Challenges](#ctf-challenges)
- [Papers](#papers)
- [Sites](#sites)
- [Heap Exploitation](#heap-exploitation)
- [Assembly](#assembly)

## Tools
#### Decompilers
- [Ghidra](https://ghidra-sre.org/) - developed by the NSA for reverse engineering which is widely used
- [IDA Pro](https://hex-rays.com/ida-pro/) - developed by Hex-Rays used for reverse engineering and debugging
- [retdec](https://github.com/avast/retdec) - open source decompiler based around LLVM
#### Programming
- [angr](https://angr.io/) - an open-source binary analysis platform for Python, [angr examples](https://docs.angr.io/en/latest/examples.html) is very useful
- [Capstone Engine](http://www.capstone-engine.org/) - a disassembly framework with the target of becoming the ultimate disasm engine for binary analysis and reversing in the security community.
#### Other Tools
- [wrestool](https://linux.die.net/man/1/wrestool) - a tool to extract resources from Microsoft Windows binaries
## Guides
#### Video Series
- [Binary Exploitation / Memory Corruption by LiveOverflow](https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN) - an introduction to binary exploitation along with going in-depth into more advanced topics
- [Reversing Wannacry by stacksmashing](https://www.youtube.com/playlist?list=PLniOzp3l9V83Yf52IXJTvW9rjstdqkduP) - reversing the well known malware [wannacry](https://en.wikipedia.org/wiki/WannaCry_ransomware_attack#:~:text=WannaCry%20is%20a%20ransomware%20cryptoworm,WanaCrypt0r%202.0%2C%20and%20Wanna%20Decryptor.) using Ghidra
#### Courses
- [Hack the Box: Intro to Assembly Language](https://academy.hackthebox.com/module/details/85) - an introduction to the assembly language along with surface level exploitation techniques
#### Other Guides
- [ctf101](https://ctf101.org/) - guides for various CTF categories including binary exploitation
- [NSA Codebreakers](https://nsa-codebreaker.org/resources) - the NSA codebreaker challenge is a yearly challenge but the resources to learn how to solve the challenges are on their resources page
- [exploit.education](http://exploit.education/) - provides various virtual machines that contain vulnerabilities along with explanations on the potential exploits

## CTF Challenges 
- [crackmes](https://crackmes.one/)
- [picoCTF](https://picoctf.org/)

## Papers   
- [SOK: (State of) The Art of War: Offensive Techniques in Binary Analysis](https://ieeexplore.ieee.org/document/7546500)

## Sites
- [godbolt.org](https://godbolt.org/) - see how code is compiled
- [dogbolt.org](https://dogbolt.org/) - see how different decompilers decompile an executable
- [binvis.io](https://binvis.io/#/) - visual analysis of binary files

## Heap Exploitation
- [how2heap](https://github.com/shellphish/how2heap) - a repo for learning various heap exploitation techniques
- [heap-exploitation](https://heap-exploitation.dhavalkapil.com/) - a book about the internals of glibc malloc and free and exploitation techniques
- [Cueing up a calculator: an introduction to exploit development on Linux](https://github.blog/2023-12-06-cueing-up-a-calculator-an-introduction-to-exploit-development-on-linux/) - an article explaining heap exploitation used in [CVE-2023-43641](https://nvd.nist.gov/vuln/detail/CVE-2023-43641) and how the vulnerability was discovered along with the development of an exploit

## Assembly
- [X86 Opcode and Instruction Reference](http://ref.x86asm.net/) - a reference for all x86 assembly opcodes

## Ghidra
- [Ghidra API reference](https://ghidra.re/ghidra_docs/api/ghidra/program/model/symbol/Reference.html) - documentation on Ghidra API which can be useful for scripting

## Motive
I'm trying to learn more about reverse engineering and binary explotation but it's such an information packed subject that the resources can be overwhelming. 

This repo tackles that problem by gathering all the resources in one spot and give a brief description.
