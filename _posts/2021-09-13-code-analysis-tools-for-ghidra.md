---
title: 'Malware Analysis Tools for Ghidra'
date: 2021-09-13
permalink: /posts/2021/09/code-analysis-tools-for-ghidra/
tags:
  - cybersecurity
---

Below is a round up of some of my work at the Software Engineering Institute with Ghidra and developing automated tools for reverse engineering and static code analysis, particularly with an eye toward malware analysis.

[SEI Blog Post: Introducing CERT Kaiju: Malware Analysis Tools for Ghidra ](https://insights.sei.cmu.edu/blog/introducing-cert-kaiju-malware-analysis-tools-for-ghidra/)

[SEI Podcast: Building on Ghidra: Tools for Automating Reverse Engineering and Malware Analysis](https://insights.sei.cmu.edu/library/building-on-ghidra-tools-for-automating-reverse-engineering-and-malware-analysis/)

I co-authored the above article and podcast with Jeff Gennari. The Kaiju extension for Ghidra is also [available on GitHub](https://github.com/CERTCC/kaiju), although should be considered fairly experimental. It was a good way to learn about Ghidra's internals which are not well documented, and would probably approach it very differently if I start the project over today. Ghidra has also significantly improved in recent releases since its initial open sourcing, but that also means some of its API and tools have not been very stable.

I also contributed to some related code analysis tools within SEI including the [Pharos framework](https://insights.sei.cmu.edu/blog/the-pharos-framework-binary-static-analysis-of-object-oriented-code/), which is [available on GitHub](https://github.com/cmu-sei/pharos). In particular I worked on some of the Windows API database and logic.


(_Note: Updated 2022-02-10 to include the podcast on this topic that took a bit of time to get published on the SEI website._)
