# Sixth Workshop on Computer Architecture Research with RISC-V (CARRV 2022)

## Sunday June 19th, 2022, Co-located with [ISCA 2022](https://iscaconf.org/isca2022/)
**Located at the [Union Square conference room (lower level)](https://www.iscaconf.org/isca2022/images/nycstf01.png)**

The Sixth Workshop on RISC-V for Computer Architecture Research (CARRV) seeks original
research papers on the design, implementation, verification, and security evaluation of RISC-V cores,
SoCs, and accelerators. Submission of early work is encouraged. The topics of specific
interest for the workshop include, but are not limited to:

* RISC-V cores and SoC architectures
* RISC-V security
* RISC-V ISA extensions
* RISC-V-based hardware accelerators
* Security architectures and techniques
* Formal methods
* Verification methodologies
* Hardware/software interfaces
* RISC-V ISA and implementation performance analysis
* RISC-V compilers and dynamic translation tools

## CARRV Invited Talk

<b>Hardware Support for Managed Languages: An Old Idea Whose Time Has Finally Come?</b><br>
Martin Maas (Google Research, Google Brain)

<b>Abstract</b><br>
A large number of workloads are written in managed languages, including server workloads in data centers, web applications in browsers, and client workloads on desktops or mobile devices. Due to their widespread adoption, improving the performance and efficiency of managed-language features such as garbage collection, JIT compilation, and dynamic runtime checks can have a significant impact on many real workloads. Hardware support for such features has been investigated since the 1970s, but still has not seen widespread practical adoption.

In this talk, I will discuss trends that make today a great time to revisit these ideas. I will describe work done at UC Berkeley that moves garbage collection into a small hardware accelerator close to the memory controller and performs GC more efficiently than a CPU. I will also talk about current work within the open-source RISC-V project on developing standard extensions for managed-language support in the context of the free and open RISC-V ISA. Finally, I will lay out opportunities for research in this area, and how open-source infrastructure can be used to build end-to-end prototypes of this work in an academic setting.

<b>Bio</b><br>
Martin Maas is a Staff Research Scientist at Google Research and part of the Google Brain team. His research interests are in language runtimes, computer architecture, systems, and machine learning, with a focus on applying machine learning to systems problems. He also chairs the J Extension group within the RISC-V project, which investigates managed-runtime extensions. Before joining Google, Martin completed his PhD in Computer Science at the University of California at Berkeley, where he worked on hardware support for managed languages and architectural support for memory-trace obliviousness (both based on RISC-V).

## CARRV Preliminary Program

<table>
<tbody>

<tr>
<td>
9:00am - 10:30am EST - <b>Session 1 - Platforms, Testing and Simulation</b>

<br><br>
<b>Welcome and opening remarks</b>

<br><br>
<b>Architecture and RISC-V ISA Extension Supporting Asynchronous and Flexible Parallel Far Memory Access</b><br>
Songyue Wang, Luming Wang, Tianyue Lu, Mingyu Chen (Institute of Computing Technology, Chinese Academy of Sciences)

<a href="papers/CARRV2022_paper_9_Wang.pdf">[paper]</a>
<a href="slides/CARRV2022_slides_9_Wang.pdf">[slides]</a>

<br><br>
<b>The Case for Using Guix to Enable Reproducible RISC-V Software & Hardware</b><br>
Christopher Batten (Cornell University), Pjotr Prins, Efraim Flashner, Arun Isaac (The University of Tennessee Health Science Center), Jan van Nieuwenhuizen (Joy of Source), Ekaitz Zarraga (ElenQ Technologies), Tuan Ta, Austin Rovinski (Cornell University), Erik Garrison (The University of Tennessee Health Science Center)

<a href="papers/CARRV2022_paper_1_Batten.pdf">[paper]</a>

<br><br>
<b>Automating Generation and Maintenance of a High-Quality Architectural Test Suite for RISC-V</b><br>
S Pawan Kumar (InCore Semiconductors), Shrreya Singh (IIT Gandhinagar), Neel Gala (InCore Semiconductors), Allen Baum (Esperanto Technologies)

<a href="papers/CARRV2022_paper_2_Kumar.pdf">[paper]</a>
<a href="slides/CARRV2022_slides_2_Kumar.pdf">[slides]</a>

<br><br>
<b>Enabling Heterogeneous, Multicore SoC Research with RISC-V and ESP</b><br>
Joseph Zuckerman, Paolo Mantovani, Davide Giri, Luca P. Carloni (Columbia University)

<a href="papers/CARRV2022_paper_3_Zuckerman.pdf">[paper]</a>
<a href="slides/CARRV2022_slides_3_Zuckerman.pdf">[slides]</a>

<br><br>
<b>Open-Source RISC-V Linux-Compatible NVMM Emulator</b><br>
Yu Omori, Keiji Kimura (Waseda University)

<a href="papers/CARRV2022_paper_4_Omori.pdf">[paper]</a>

</td>
</tr>


<tr>
<td>
10:30am - 11:00am EST - <b>Coffee Break</b>

</td>
</tr>

<tr>
<td>
11:00am - 12:00noon EST - <b>Invited Talk</b>

<br><br>
<b><u>Invited Talk</u> - Hardware Support for Managed Languages: An Old Idea Whose Time Has Finally Come?</b><br>
Martin Maas (Google Research, Google Brain)

</td>
</tr>

<tr>
<td>
12:00noon - 1:30am EST - <b>Lunch</b>

</td>
</tr>

<tr>
<td>
1:30pm - 2:30pm EST - <b>Session 2 - Security and Cryptography </b>

<br><br>
<b>AOS-RISC-V: Towards Always-On Heap Memory Safety</b><br>
Yonghae Kim, Anurag Kar, Siddant Singh, Ammar A. Ratnani (Georgia Tech), Jaekyu Lee (Arm Research, Intel), Hyesoon Kim (Georgia Tech)

<a href="papers/CARRV2022_paper_5_Kim.pdf">[paper]</a>
<a href="slides/CARRV2022_slides_5_Kim.pdf">[slides]</a>

<br><br>
<b>Protection and Relocation Extension for RISC-V</b><br>
Maja Malenko, Leandro Batista Ribeiro, Marcel Baunach (Graz University of Technology)

<a href="papers/CARRV2022_paper_6_Malenko.pdf">[paper]</a>

<br><br>
<b>HYDRA: A Multi-core RISC-V with Cryptographically Useful Modes of Operation</b><br>
Ben Marshall (PQShield), Dan Page, Thinh Pham, Max Whale (University of Bristol)

<a href="papers/CARRV2022_paper_7_Marshall.pdf">[paper]</a>
<a href="slides/CARRV2022_slides_7_Marshall.pdf">[slides]</a>

</td>
</tr>

<tr>
<td>
2:30pm - 3:30pm EST - <b>Coffee Break</b>

</td>
</tr>


<tr>
<td>
3:30pm - 4:30pm EST - <b>Session 3 - Acceleration and Extensions</b>

<br><br>
<b>RISC-V Instruction Set Extension for Graph Applications</b><br>
Mehmetali Semi Yenimol, Gülce Pulat, Ozcan Ozturk (Bilkent University)

<a href="papers/CARRV2022_paper_8_Yenimol.pdf">[paper]</a>

<br><br>
<b>Shared Vector Register of RISC-V for the Future Hardware Acceleration</b><br>
Tomoaki Tanaka, Ryosuke Higashi, Hidetaro Tanaka (Tokyo University of Agriculture and Technology), Takefumi Miyoshi (WasaLabo, LLC.), Yasunori Osana (University of the Ryukyus), Jubee Tada (Graduate School of Science and Engineering, Yamagata University), Kiyofumi Tanaka (Japan Advanced Institute of Science and Technology), Hironori Nakajo (Tokyo University of Agriculture and Technology)

<a href="papers/CARRV2022_paper_10_Tanaka.pdf">[paper]</a>

<br><br>
<b>Implementing Hardware Extensions for Multicore RISC-V GPUs</b><br>
Tine Blaise, Hyesoon Kim (Georgia Institute of Technology)

<a href="papers/CARRV2022_paper_11_Blaise.pdf">[paper]</a>

</td>
</tr>

</tbody>
</table>

## Important Dates

* Full paper submission deadline: May 6, 2022, 23:59 PST
* Author notification: May 13, 2022
* Camera-ready due: June 3, 2022
* Workshop date: June 19, 2022


## Workshop Information

The ISCA 2022 conference organizers have informed us that ISCA 2022,
and the workshops and tutorials, will take place in-person this year.


## Organizers

* Krste Asanović (University of California, Berkeley)
* Yungang Bao (ICT)
* Hyesoon Kim (Georgia Institute of Technology)
* Alex Bradbury (lowRISC CIC)
* Trevor E. Carlson (National University of Singapore)
* Silviu Chiricescu (Draper)
* G S Madhusudan (IIT-Madras)
* Robert Mullins (Cambridge)
* Arun Thomas (Google)

## Submission Guidelines

All papers should be submitted electronically to
[HotCRP](https://carrv2022.hotcrp.com). Submissions
in PDF format must be limited to 6 pages including figures and tables,
plus as many pages as needed for references. Papers must be in PDF
format and the submission should be anonymous.

Papers must be formatted in accordance to the ACM two column
style. ACM Word or LaTeX style templates are available
[here](http://www.acm.org/publications/proceedings-template).

Note: Workshop publications do not preclude publishing at future
conference venues.

## Contact

All questions about submissions can be emailed to:
schirice at ieee dot org.

## Past CARRVs

* [CARRV 2021](https://carrv.github.io/2021/)
* [CARRV 2020](https://carrv.github.io/2020/)
* [CARRV 2019](https://carrv.github.io/2019/)
* [CARRV 2018](https://carrv.github.io/2018/)
* [CARRV 2017](https://carrv.github.io/2017/)
