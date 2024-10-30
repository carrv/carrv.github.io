# Eighth Workshop on Computer Architecture Research with RISC-V (CARRV 2024)

## Sunday November 3rd, 2024, Co-located with [MICRO 2024](https://microarch.org/micro57/)

The Eighth Workshop on RISC-V for Computer Architecture Research (CARRV) seeks original
research papers on the design, implementation, verification, and evaluation of
RISC-V cores, SoCs, and accelerators. The topics of specific
interest for the workshop include, but are not limited to:

* RISC-V cores and SoC architectures
* RISC-V ISA extensions
* RISC-V-based hardware accelerators for AI/ML
* Security architectures and techniques
* Formal methods
* Verification methodologies
* Hardware/software interfaces
* RISC-V ISA and implementation performance analysis
* RISC-V compilers and dynamic translation tools

## Important Dates

* Full paper submission deadline: ~~August 4,~~ August 11,  2024, 23:59 PST
* Author notification: ~~September 1~~ September 9th, 2024
* Camera-ready due: ~~September 15~~ September 20th, 2024, 23:59 PST
* Workshop date: November 3, 2024

## CARRV Program

<table>
<tbody>

<tr><td>
8:30am - 9:30am CST
<br><br>
<b>Welcome and opening remarks</b>
<br><br>
<b><u>Invited Talk</u> - Pre-silicon Side-channel Leakage Assessment Across the Hardware/Software Boundary</b><br>
Patrick Schaumont (Worcester Polytechnic Institute (WPI))
<details> <summary>Abstract</summary>Side-channel leakage assessment is a crucial but challenging verification step for programmable systems that manage secure assets. A pre-silicon design method based on power modeling can significantly reduce the likelihood of side-channel design flaws. However, such an approach requires a comprehensive system model to bridge the gap between high-level secure software assets and the physical side-channel leakage in hardware. The trade-off between model accuracy and simulation performance is difficult, because more detailed models become less practical due to their simulation complexity. To address this challenge, we propose a top-down hierarchical pre-silicon side-channel leakage assessment methodology that spans three modeling levels commonly used in System-on-Chip design: architecture-level, microarchitecture-level, and gate-level. We classify side-channel leakage sources across these abstraction levels and show that each level introduces unique power-based leakage characteristics. Our hierarchical approach enables systematic debugging of side-channel vulnerabilities from higher abstraction levels down to lower ones. The methodology is illustrated with practical examples from a System-on-Chip design, demonstrating various cases of side-channel bugs and their resolution.</details>
<br><br>
</td></tr>

<tr><td>
9:30am - 10:00am CST
<br><br>
<b>GPGPU Pipeline Visualization for RISC-V SIMT Architecture</b><br>
Yu-Yu	Hsiao, Liang-Chou	Chen, Chung-Ho Chen (National Cheng Kung University)

<a href="papers/CARRV_2024_paper_4.pdf">[paper]</a>
<a href="slides/CARRV_2024_slides_4.pptx">[slides]</a>
<br><br>
</td></tr>

<tr><td>
10:00am - 10:30am CST - <b>Coffee Break</b>
</td></tr>

<tr><td>
10:30am - 11:00am CST  
<br><br>
<b>Advancing Cloud Computing Capabilities on gem5 by Implementing the RISC-V Hypervisor Extension</b><br>
George-Marios	Fragkoulis, Nikos	Karystinos, George Papadimitriou, Dimitris	Gizopoulos (University of Athens)

<a href="papers/CARRV_2024_paper_3.pdf">[paper]</a>
<a href="slides/3.pdf">[slides]</a>
<br><br>
</td>
</tr>


<tr>
<td>
11:00am - 12:00pm CST
<br><br>
<b><u>Invited Talk</u> - Hardware Fuzzing: What? Why? How?</b><br>
Jeyavijayan "JV" Rajendran (Texas A&M University)
<details> <summary>Abstract</summary>Hardware is at the heart of computing systems. However, recent years have seen increased attacks exploiting hardware vulnerabilities and exploits, which even traditional software-based protections cannot prevent. Hardware fuzzing has shown promise in detecting vulnerabilities in large-scale designs like modern processors. In this talk, I will describe the hardware vulnerabilities in hardware description languages, such as Verilog and VHDL. Then, I will explain a new and radical approach called hardware fuzzing to find these vulnerabilities and detail how fuzzing techniques can be combined with existing formal verification techniques to detect vulnerabilities efficiently. Finally, I will discuss a strategy for pinpointing vulnerabilities to accelerate the mitigation process and briefly talk about improving the efficiency of hardware fuzzing using ML/AI techniques, such as multi-armed bandit (MAB) and large language models (LLM).</details>
<br><br>
</td></tr>

<tr><td>
12:00pm - 1:00pm CST - <b>Lunch</b>
</td></tr>

<tr><td>
1:00pm - 1:30pm CST
<br><br>
<b>Virgo: Cluster-level Matrix Unit Integration in GPUs for Scalability and Energy Efficiency</b><br>
Hansung	Kim, Ruohan	Yan, Joshua	You, Tieliang Vamber, Yakun Sophia Shao (University of California, Berkeley)

<a href="papers/CARRV_2024_paper_5.pdf">[paper]</a>
<a href="slides/5.pdf">[slides]</a>
<br><br>
</td></tr>

<tr><td>
1:30pm - 2:00pm CST
<br><br>
<b>Extending RISC-V Keystone to Include Efficient Secure Memory</b><br>
Tamara Lehman and Zach Moolman (University of Colorado Boulder)

<a href="papers/CARRV_2024_paper_7.pdf">[paper]</a>
<a href="slides/7.pdf">[slides]</a>
<br><br>
</td></tr>

</tbody>
</table>

## Submission Guidelines

All papers should be submitted electronically to EasyChair. Submissions
in PDF format must be limited to 6 pages including figures and tables,
plus as many pages as needed for references. Papers must be in PDF
format and should include title, authors and affiliation, e-mail address
of the contact author.

Papers must be formatted in accordance with the ACM two column
style. ACM Word or LaTeX style templates are available
[here](http://www.acm.org/publications/proceedings-template).

Note: Workshop publications do not preclude publishing at future
conference venues.

The submissions should be done  via [EasyChair](https://easychair.org/conferences/?conf=carrv2024) 

## Contact

All questions about submissions can be emailed to:
komail dot dharsee+carrv at gmail dot com

## Past CARRVs

* [CARRV 2023](https://carrv.github.io/2023/)
* [CARRV 2022](https://carrv.github.io/2022/)
* [CARRV 2021](https://carrv.github.io/2021/)
* [CARRV 2020](https://carrv.github.io/2020/)
* [CARRV 2019](https://carrv.github.io/2019/)
* [CARRV 2018](https://carrv.github.io/2018/)
* [CARRV 2017](https://carrv.github.io/2017/)
