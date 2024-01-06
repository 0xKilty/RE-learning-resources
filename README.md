# RE-learning-resources
> Resources to learn more about reverse engineering and binary exploitation
## Contents
- [Tools](#tools)
    - [Disassemblers](#disassemblers)
    - [Programming](#programming)
- [Guides](#guides)
- [CTF Challenges](#ctf-challenges)
- [Papers](#papers)
- [Sites](#sites)
- [Heap Exploitation](#heap-exploitation)

## Tools
#### Disassemblers
- [Ghidra](https://ghidra-sre.org/) - A tool developed by the NSA for reverse engineering which is widely used
- [IDA Pro](https://hex-rays.com/ida-pro/) - A disassembler used for reverse engineering and debugging developed by Hex-Rays
#### Programming
- [angr](https://angr.io/) - an open-source binary analysis platform for Python, [angr examples](https://docs.angr.io/en/latest/examples.html) is very useful

## Guides
- [Binary Exploitation / Memory Corruption by LiveOverflow](https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN) - a great video series as an introduction to binary exploitation along with going in-depth into more advanced topics
- [Hack the Box: Intro to Assembly Language](https://academy.hackthebox.com/module/details/85) - an introduction to the assembly language along with surface level exploitation techniques
- [ctf101](https://ctf101.org/) - guides for various CTF categories including binary exploitation
- [NSA Codebreakers](https://nsa-codebreaker.org/resources) - the NSA codebreaker challenge is a yearly challenge but the resources to learn how to solve the challenges are on their resources page

## CTF Challenges 
- [crackmes](https://crackmes.one/)
- [picoCTF](https://picoctf.org/)

## Papers   
- [SOK: (State of) The Art of War: Offensive Techniques in Binary Analysis](https://ieeexplore.ieee.org/document/7546500)

## Sites
- [godbolt.org](https://godbolt.org/) - see how code is compiled
- [dogbolt.org](https://dogbolt.org/) - see how different disassemblers disassemble a binary
- [binvis.io](https://binvis.io/#/) - visual analysis of binary files

## Heap Exploitation
- [how2heap](https://github.com/shellphish/how2heap) - a repo for learning various heap exploitation techniques
- [heap-exploitation](https://heap-exploitation.dhavalkapil.com/) - a book about the internals of glibc malloc and free and exploitation techniques
- [Cueing up a calculator: an introduction to exploit development on Linux](https://github.blog/2023-12-06-cueing-up-a-calculator-an-introduction-to-exploit-development-on-linux/) - an article explaining heap exploitation used in [CVE-2023-43641](https://nvd.nist.gov/vuln/detail/CVE-2023-43641) and how the vulnerability was discovered along with the development of an exploit

### Motive
I'm trying to learn more about reverse engineering and binary explotation but it's such an information packed subject that the resources can be overwhelming. 

This repo tackles that problem by gathering all the resources in one spot and give a brief description.