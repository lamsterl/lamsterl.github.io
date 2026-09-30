---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download the CV as PDF]({{ base_path }}/files/cv.pdf){: .btn .btn--primary}

Education
======
* PhD in Computer Science, Graz University of Technology, March 2022 – present (expected spring 2027)
  * Advisor: Prof. Stefan Mangard
* MSc in Computer Science, Graz University of Technology, 2019 – 2021
  * Thesis: *DRAM Integrity Protection with Efficient Low-Latency Cryptographic Primitives*
  * Student Research Excellence Award, WKO Research Stipend
  * Graduated with distinction
* BSc in Computer Science, Graz University of Technology, 2015 – 2019
  * Thesis: *From Rowhammer to Nethammer – Utilizing Intel CAT to Remotely Induce Bit Flips*
  * Student Research Excellence Award
  * Graduated with distinction

Research experience
======
* March 2022 – present: Doctoral Researcher
  * Institute of Information Security (ISEC), Graz University of Technology
  * Exploring combinations of DRAM integrity protection and memory tagging
  * Developing novel hardware-based runtime security mechanisms
  * Multiple contributions towards memory safety, efficient memory tagging, and DRAM integrity protection schemes

* Summer 2019: Research Intern
  * Institute of Information Security (ISEC), Graz University of Technology
  * Improving the reverse engineering of processor-specific DRAM mapping functions

Work experience
======
* March – June 2026: Software Development Intern, Cloudflare, Lisbon, Portugal
  * Researching Rowhammer on large-scale computing infrastructure
  * Researching side channels and timers in Worker and Container products

* 2018 – 2020: Software Engineer, AVL, Graz, Austria
  * Jira plugin development
  * Developing compatibility layers for internal tooling

* 2016 – 2017: Software Engineer, Melecs EWS, Siegendorf, Austria
  * Development of drivers for assembly line equipment
  * Quality assurance tool development

Awards
======
* 2025: [Distinguished Artifact Reviewer Award](https://secartifacts.github.io/usenixsec2025/awards#-distinguished-reviewer-awards), USENIX Security 2025
* 2021: WKO Research Stipend, Master's Thesis (WKO)
* 2021: Student Research Excellence Award, Master's Thesis (ISEC)
* 2019: Student Research Excellence Award, Bachelor's Thesis (ISEC)

Skills
======
* Programming: C, C++, C#, Python, x86-64 assembly, RISC-V assembly, SystemVerilog
* Tools: git, gdb, pwndbg, Docker, LLM-assisted development, Ghidra
* Projects: Linux kernel development, gem5 development, qemu, Spike RISC-V ISA Simulator, OpenSBI
* Languages: German (native), English (fluent)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
* 2025 – present: Secure System Architecture, Lecture and Practicals, Graz University of Technology
  * Lectures, practical sessions, and grading for approx. 40 students per year
  * Topics range from memory tagging and pointer authentication to trusted computing and confidential virtual machines
* 2022 – present: Information Security, Practicals, Graz University of Technology
  * Introductory information security course, approx. 400 students per year
  * Focus on the system security part, which consists of CTF-style binary exploitation tasks
* 2022 – present: Computer Organization and Networks, Practicals, Graz University of Technology
  * Introductory computer organization course for Bachelor's students, approx. 500 students per year
  * Hardware design in SystemVerilog, state machines, integrating extensions into existing hardware designs, and RISC-V assembly
