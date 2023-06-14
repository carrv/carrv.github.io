# Seventh Workshop on Computer Architecture Research with RISC-V (CARRV 2023)

## Saturday June 17th, 2023, Co-located with [ISCA 2023](https://iscaconf.org/isca2023/)


The Seventh Workshop on RISC-V for Computer Architecture Research (CARRV) seeks original
research papers with a focus on the <b>security of RISC-V cores</b>. However, papers on the design, 
implementation and verification of RISC-V cores, SoCs, and accelerators are also encouraged. 
Submission of early work is encouraged. The topics of specific
interest for the workshop include, but are not limited to:

* RISC-V security
* Security architectures and techniques
* Formal methods
* Verification methodologies
* RISC-V cores and SoC architectures
* RISC-V ISA extensions
* RISC-V-based hardware accelerators
* Hardware/software interfaces
* RISC-V ISA and implementation performance analysis
* RISC-V compilers and dynamic translation tools

## CARRV Preliminary Program

<table>
<tbody>

<tr>
<td>
9:30am - 11:00am EST - <b>Session 1</b>

<br><br>
<b>Welcome and opening remarks</b>

<br><br>
<b>Feature-Oriented Cache Designs</b><br>
Justin Deters (SimpleRose and Washington University) and Ron K. Cytron (Washington University)

<a href="papers/CARRV2023_paper_1_Deters.pdf">[paper]</a>

<br><br>
<b><u>Invited Talk</u> - Design and Implementation of the Labeled RISC-V Architecture</b><br>
Yungang Bao (Institute of Computing Technology (ICT), Chinese Academy of Sciences (CAS))



<br><br>
<b>Minimizing the Energy Usage of Tiny RISC-V Cores</b><br>
Asbjørn Djupdal, Magnus Själander, Magnus Jahre, and Snorre Aunet (Norwegian University of Science and Technology (NTNU))

<a href="papers/CARRV2023_paper_2_Djupdal.pdf">[paper]</a>

</td>
</tr>


<tr>
<td>
11:00am - 11:20am EST - <b>Coffee Break</b>

</td>
</tr>

<tr>
<td>
11:20am - 12:30pm EST - <b>Session 2</b>

<br><br>
<b>Cache Coherent Framework for RISC-V Many-core Systems</b><br>
Zexin Fu, Mingzi Wang, Yihai Zhang, Zhangxi Tan (Tsinghua University)

<a href="papers/CARRV2023_paper_3_Fu.pdf">[paper]</a>



<br><br>
<b><u>Invited Talk</u>  - The Double-Edged Sword: Uncovering Security Implications of Performance Optimization in TEE Design</b><br>
Mengyuan Li (MIT)
<details> <summary>Abstract</summary>For years, the main obstacle to cloud adoption has been a lack of trust in Cloud Service Providers (CSPs). The concept of confidential computing has been enabled by an emerging security feature in modern CPUs, dubbed Trusted Execution Environment (TEE), which removes the need to trust the CSP. Aiming to provide data-in-use protection, TEE uses hardware-enabled isolation to protect the cloud workload against both physical access attacks and privileged software-level attacks. Due to the enormous market potential, all main processor vendors have released or are working on releasing confidential VM features in their server CPU lines, including AMD Secure Encrypted Virtualization (SEV), Intel Trust Domain Extension (TDX), and ARM Confidential Compute Architecture (CCA). However, performance optimization in these TEE designs can introduce vulnerabilities.<br><br>

In this talk, I will present two vulnerabilities identified in AMD SEV resulting from inconsiderate performance optimization. The first vulnerability relates to SEV's improper use of the address space identifier (ASID), which plays a rather important role in improving performance during a context switch. Based on our exploration, we present CrossLine attacks, which exploit a momentary execution to breach the confidentiality and integrity of SEV VMs. The second vulnerability is related to the confidential VM's hardware-accelerated memory encryption engine. We then introduce the ciphertext side channel, a previously unexplored side-channel, allowing a privileged adversary to infer execution states and potentially break constant-time OpenSSL implementations within confidential VMs. Finally, I will discuss existing TEE designs on the RISC-V platform and future directions for TEE design with improved performance.</details>




<br><br>
<b>A Genetic Algorithm for a Spectre Attack Agnostic to Branch Predictors</b><br>
Dorian Bourgeoisat, Laurent Sauvage (Télécom Paris - Institut Polytechnique de Paris)

<a href="papers/CARRV2023_paper_4_Bourgeoisat.pdf">[paper]</a>

</td>
</tr>

<tr>
<td>
12:30pm - 2:00am EST - <b>Lunch</b>

</td>
</tr>

<tr>
<td>
2:00pm - 3:30pm EST - <b>Session 3</b>



<br><br>
<b><u>Invited Talk</u> - Instruction-Level Power Side-Channel Leakage Evaluation of Soft-Core CPUs on Shared FPGAs</b><br>
Ognjen Glamocanin (EPFL)
<details> <summary>Abstract</summary>Side-channel disassembly attacks recover CPU instructions
from power or electromagnetic side-channel traces measured during code
execution. These attacks typically rely on physical access, proximity
to the victim device, and high sampling rate measuring instruments. In
this work, however, we analyze the CPU instruction-level power
side-channel leakage in an environment that lacks physical access or
expensive measuring equipment. We show that instruction leakage is
present even in a multitenant FPGA scenario, where the victim uses a
soft-core CPU, and the adversary deploys on-chip voltage-fluctuation
sensors. Unlike previous remote power side-channel attacks, which
either require a considerable number of victim traces or attack large
victim circuits such as machine learning accelerators, we take an
evaluator’s point of view and provide an analysis of the
instruction-level power side-channel leakage of a small open-source
RISC-V soft processor core. To investigate whether the power
side-channel traces leak secrets, we profile the victim device and
implement various instruction opcode classifiers based on classical
machine learning algorithms used in disassembly attacks and novel deep
learning approaches. We explore how parameters such as placement,
trace averaging, profiling templates, and different FPGA families
(including a cloud-scale FPGA) impact classification accuracy. Despite
the limited leakage of the soft-core CPU victim and a reduced accuracy
and sampling rate of on-chip sensors, we show that in a worst-case
scenario for the evaluator, i.e., an attacker breaching physical
separation, we can identify the opcode of executed instructions with
an average accuracy as high as 86.46%. Our analysis shows that
determining the executed instruction type is not a classification
bottleneck, while leakages between instructions of the same type can
be challenging for deep learning models to distinguish. We also show
that the instruction-level leakage is significantly reduced in a
cloud-scale FPGA scenario with higher soft-core CPU frequencies.
Nevertheless, our results show that even small circuits, such as
soft-core CPUs, leak potentially exploitable information through
on-chip power side channels, and users should deploy mitigation
techniques against disassembly attacks to protect their proprietary
code and data.</details>


<br><br>
<b>QEMU-CAS: A Full-System Cycle-Accurate Simulation Framework based on QEMU</b><br>
Ye Cao, Zhixuan Xu, Zhangxi Tan (Tsinghua University)

<a href="papers/CARRV2023_paper_5_Cao.pdf">[paper]</a>



<br><br>
<b><u>Invited Talk</u> - Bringing Symbolic Execution to the Security Verification of Hardware Designs</b><br>
Kaki Ryan (UNC Chapel Hill)
<details> <summary>Abstract</summary>The verification of hardware designs is a key activity for ensuring the correctness and security of a design early in the hardware lifecycle. In this talk, I will discuss our work developing a new point in the hardware verification space: software-style symbolic execution. Symbolic execution generalizes testing by replacing concrete values with symbols, with each symbol representing the set of possible values of the variable. This path-based symbolic analysis allows for deep and precise exploration of the design’s state space.<br><br>

Unfortunately, symbolic execution infamously suffers from the path explosion problem. I will first present the piecewise composition search strategy we developed to leverage the modular and cyclical nature of hardware designs to manage the path explosion problem. Using a hardware-oriented symbolic execution engine, we are able to find vulnerabilities in RISC-V processors that commercial and open-source model checking tools do not find. I will also discuss our results using symbolic execution for information-flow analysis in which we eliminate many of the false-positive flows that static analysis or taint tracking can produce.</details>


<br><br>
<b>RGen: A Tool for Generating RISC-V Compiler, Simulator, and Application Support</b><br>
Derek Zijie Tu, Zhangxi Tan (Tsinghua University)

<a href="papers/CARRV2023_paper_6_Tu.pdf">[paper]</a>



</td>
</tr>

<tr>
<td>
3:30pm - 4:00pm EST - <b>Coffee Break</b>

</td>
</tr>


<tr>
<td>
4:00pm - 5:00pm EST - <b>Session 4</b>

<br><br>
<b><u>Invited Talk</u> - Uncovering Transmitter Instructions on the RISC-V CVA6 Processor</b><br>
Caroline Trippel (Stanford)




<br><br>
<b>Round Table - Implications for the Design and Validation of Secure Systems</b><br>
Mengyuan Li (MIT), Caroline Trippel (Stanford), Mengjia Yan (MIT)


</td>
</tr>

</tbody>
</table>


## Important Dates

* Early Full paper submission deadline*: April 3, 2023, 23:59 PST
* Author notification for Early submission: April 17, 2023
* Regular Full paper submission deadline: May 1, 2023, 23:59 PST
* Workshop date: June 17, 2023

*The early paper submission deadline is for those who need an early acceptance for visa purposes, however anyone is welcome to submit then.

## Workshop Information

The ISCA 2023 conference organizers have informed us that ISCA 2023,
and the workshops and tutorials, will take place in-person this year.


## Submission Guidelines

All papers should be submitted electronically to
[HotCRP](https://carrv2023.hotcrp.com/). Submissions 
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
tcarlson at comp nus edu sg.

## Past CARRVs

* [CARRV 2022](https://carrv.github.io/2022/)
* [CARRV 2021](https://carrv.github.io/2021/)
* [CARRV 2020](https://carrv.github.io/2020/)
* [CARRV 2019](https://carrv.github.io/2019/)
* [CARRV 2018](https://carrv.github.io/2018/)
* [CARRV 2017](https://carrv.github.io/2017/)
