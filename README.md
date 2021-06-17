![Img](Huawei.jpg)![Img](TUB_better.PNG) 

**Scope and Objective**

The 1st Network Verification workshop hosted by Huawei-TU Berlin innovation lab aims to provide a forum for the community to come together and rethink fundamental questions, breakthrough solutions in Network Verification. The networks were not designed with verification as indispensable requirement. However, as more and more applications rely on correct and secure network services provided by the underlying Cloud provider, the importance of network verification on Cloud provider becomes significant. In the near future, the verification of networks and distributed systems is poised to become a mandatory first-class design goal, just like performance, reliability, etc. In the past, one impediment in designing verified networks was that the Internet was very hard to change. Networking devices used to be proprietary and expensive blackboxes provided by few switch vendors. Despite many radical proposals, many of these useful ideas and designs cannot be easily integrated into the operational network without an expensive forklift upgrade.

Lately, researchers have realized that network verification is of paramount importance. Furthermore, with the advent of network programmability, lot of flexibility and customization can be leveraged to deliver in-house and homegrown solutions. Our networking community has already developed a range of new systems and in-network capabilities such as In-band Network Telemetry (INT), In-network caching, etc. In this workshop, we are soliciting talks from the pioneers in this field that focus on developing and examining the area of network verification while identifying missing or unaddressed gaps. We welcome contributions on early ideas in these areas, talks that outline upcoming cool solutions to hot problems, as well as preliminary ideas from ongoing projects that could benefit the audience as well as the presenter via brainstorming. The workshop seeks to bring together experts from academia and industry in networking, and systems, with the goal of identifying exciting opportunities for network verification in the area of cloud datacenter networks and follow-up on interesting collaboration opportunities. We strive to strengthen the community by working towards the common goal of solving the main challenges. 

**Key Objectives**:

• Build a resource/technology landscape 

• Identify current research trends and hot problems

• Future Research Directions

• Identify possible future collaboration partners

• Follow-up on possible future collaborations


**Topics of Interest**

We invite talks on a wide range of topics of interest, including, but not limited to:

•	The network verification problems and solutions in cloud datacenter

•	Formal methods or runtime verification solutions in network verification

•	The network security aspects in cloud datacenter

•	Architectural support for network verification

•	Incrementally deployable designs for network verification

•	Network and distributed systems access control

•	Verification and Security for emerging network scenarios (e.g., Home, IoT)

**Talk Submission Details**

By invitation only. 20 minutes talk followed by 10 mins Q&A.

**Dates and Agenda**

July 29, 2021

**Welcome and Introduction to Munich Research Center** by [Dr. Goetz-Philip Brasche](https://www.linkedin.com/in/g%C3%B6tz-philip-brasche-7397b), CTO Cloud Europe (8:00 - 8:20 AM CEST)

**Introduction of the Ultra-scale AIOps Lab** by [Dr. Jorge Cardoso](https://jorge-cardoso.github.io/), Chief Architect, AIOps (8:20 AM - 8:50 AM CEST)

**Abstract**: This talk will give a brief overview of the Ultra-scale AIOps Lab. The lab was created to conduct R&D on the development of new tools and systems which rely on machine learning and deep learning techniques to automate IT operations (AIOps or AI for Operations), intelligently process data near its generation (Edge AI), and leverage AI to automate network tasks such as network verification, configuration, and optimization (AI for Networks). Another area of interest which we are fostering is AI for DevOps which relies on AI to improve the various phases of software development such as coding, testing, configuration and deployment.

**Moderator**: [Dr. Apoorv Shukla](https://www.apoorv.net), Senior Networks Researcher in Cloud at Huawei Munich Research Center

**Keynote: Practical (privacy preserving) federated ML for networked system behaviours** by [Prof. Jon Crowcroft](https://www.cst.cam.ac.uk/people/jac22), Full Professor at Cambridge University, London (8:30 - 9:00 AM CEST)

**Abstract**: In this talk I'll discuss ways for pragmatic (i.e. empirical) verification of syste behaviours through federated machine learning. I'll touch on ways to make the federated ML scale, and provide privacy (in case there are sensitivies about nodes behaviour). The same techniques apply in the edge (IoT, Smart Spaces) and the Cloud (data center, rack scale etc). CLassical simple ML like PCA and SGD can be deployed in this framework. Future challenges include whether full Bayesian Model Inferencing can be carried out within this framework. References: Colearn (edgesys), Moses (arxiv) and Pronto (arxiv).

**Talk: Performance Verification of Network Components** by [Prof. Georg Carle](https://www.net.in.tum.de/members/carle/), Full Professor at TU Munich, Munich (9:00 - 9:30 AM CEST)

**Abstract**: There is a need for predictable network services, implying the ability of network performance verification. This task gets more challenging with the shift from fixed-function network devices with limited configurability towards implementing network functionality using virtualisation and programmable network components. A prominent example of this development is P4 that provides a language and reference architecture model to design and program network devices. In the talk key challenges for providing predictable network services are identified, and approaches for performance verification are presented.

**Talk: Analyzing Learning-Based Networked Systems with Formal Verification** by [Prof. Marco Canini](https://mcanini.github.io/), Associate Professor at KAUST, Jeddah (9:30 - 10:00 AM CEST)

**Abstract**: As more applications of (deep) neural networks emerge in the computer networking domain, the correctness and predictability of a neural agent’s behavior for corner case inputs are becoming crucial. Enabling the formal analysis of agents with nontrivial properties, we bridge between specifying intended high-level behavior and expressing low-level statements directly encoded into an efficient verification framework. Our results support that within minutes, one can establish the resilience of a neural network to adversarial attacks on its inputs, as well as formally prove properties that were previously relying on educated guesses. Finally, we also show how formal verification can help create an accurate visual representation of an agent behavior to perform visual inspection and improve its trustworthiness.

**Keynote: Assessing the Performance of (Smart) Network Interface Cards** by [Prof. Marco Chiesa](https://marchiesa.bitbucket.io/), Assistant Professor at KTH, Stockholm (10:00 - 10:30 AM CEST)

**Abstract**: Network interface cards (NICs) are fundamental components of modern high-speed networked systems, supporting multi-100 Gbps speeds and increasing programmability. Offloading computation from a server’s CPU to a NIC frees a substantial amount of the server’s CPU resources, making NICs key to offer competitive cloud services. Therefore, verifying the performance benefits and limitations of offloading a networking application to a NIC is of paramount importance. In this paper, we measure the performance of four different NICs from one of the largest NIC vendors worldwide, supporting 100 Gbps and 200 Gbps. We show that while today’s NICs can easily support multihundred-gigabit throughputs, performing frequent update operations of a NIC’s packet classifier — as network address translators (NATs) and load balancers would do for each incoming connection — results in a dramatic throughput reduction of up to 70 Gbps or complete denial of service. Our conclusion is that all tested NICs cannot support high-speed networking applications that require keeping track of a large number of frequently arriving incoming connections. Furthermore, we show a variety of counter-intuitive performance artefacts including the performance impact of using multiple tables to classify flows of packets.

Break 10 mins (10:30 - 10:40 AM)

**Talk: Towards performance verification of datacenter networks** by [Prof. Costin Raiciu](http://nets.cs.pub.ro/~costin/), Associate Professor at University Politehnica of Bucharest, Bucharest (10:40 - 11:10 AM CEST)

**Abstract**: Network correctness verification is a maturing field, with tools available for finding configuration and hardware bugs in production networks. In this work we take the next logical step in this direction, asking whether we can automatically and conitnuously verify that the performance of datacenter networks is in line with the expected performance. We focus on datacenter networks, and show that key to performance verification is an efficient dataplane that can address both load balancing and incast issues that plague performance in traditional approaches. With such a dataplane deployed, we show it is possible to automatically verify the performance of a live datacenter network via encouraging results from a prototype systems’ implementation.

**Talk: Fast Automated What-if Analysis and Updates for Policy-Compliant Networks Even Under Failures** by [Prof. Stefan Schmid](https://www.univie.ac.at/ct/stefan/), Full Professor at TU Berlin, Berlin (11:10 - 11:40 AM CEST)

**Abstract**: Communication networks have become a critical infrastructure of our digital society. However, configuring and operating communication networks is complex, and many outages and policy issues today are due to human error. In this talk, I will first give an overview of the AalWiNes project (INFOCOM 2018, CoNEXT 2018, CoNEXT 2020). AalWiNes is a tool which allows to quickly and automatically verify whether network configurations are policy-compliant, even under failures. Unlike other tools, AalWiNes runs in polynomial time, and allows to account for quantitative aspects. In addition to discussing how to verify a given network configuration, we will also briefly consider the important question of how to update network configurations, i.e., change from one configuration to another one. To this end, I will present Latte (PERFORMANCE 2020), an automated tool to verify and synthesize efficient updates of network configurations. 

**Talk: Is Network Verification the right answer?** by [Dr. Artur Hecker](https://www.linkedin.com/in/artur-hecker-25027818), Director of networking research and Expert at the Advanced Wireless Technology Lab, Huawei Munich Research Center, Munich (11:40 AM - 12:10 PM CEST)

**Abstract**: As networks become programmable, they essentially become execution environments for software objects, and software is still brittle in comparison. Undeniably, network verification gains on importance in this context, most notably in a model, where network is provided as a service. Luckily, research has just recently reported quite impressive advances in this field, e.g., integrating INT, probing, classical software verification tools and AI methods.
Still, in the overall puzzle of software-driven networks, network verification might be just one piece, and we will argue that it might not be the most important one. The main problem of network verification is that it always “runs behind”, as an a posteriori process seeking to verify the correctness of the executed network(s). Hence, even if network verification concludes at a given time point, errors might still happen due to concurrency, conflicts with later allocations or due to errors in the executing environment. Trying to open a new research area, in this talk we argue that for a programmable environment to be successful, it would seem more important a) to isolate executed objects from each other, rendering negative influence impossible and b) to enforce the correctness of the executing environment regardless of the operating conditions.

Lunch Break (30 mins) (12:10 - 12:40 PM)

**Talk: From hardware to software, or from software to hardware? Abstractions for programmable packet processing in the NIC** by [Dr. Roberto Bifulco](https://www.robertobifulco.it/), Manager of Intelligent Software Systems Group at NEC, Heidelberg (12:40 - 13:10 PM CEST)

**Abstract**: As we enter a post-Moore's Law Era of computing, it is increasingly important to free a computer's CPU from workloads that could be handled elsewhere. Network accelerators, SmartNICs and Data Processing Units are processing engines specifically designed to perform packet processing, offloading the system's CPU of such task, and potentially providing better scalability, efficiency and performance in general.
Nonetheless, programming abstractions and technologies to program packet processing on such devices are in their infancy, with both the research and industrial communities actively working to define them. P4 and eBPF are relevant examples of two different approaches being currently explored to address the issue. In P4, the programming abstractions are informed by the hardware limitations of switching devices. In eBPF, the programming model evolved assuming a general purpose executor, e.g., a CPU.
In this talk we give an overview of the challenges in this area, and then we present our recent contribution hXDP (OSDI'20). hXDP leverages eBPF  to enable the programming of FPGA NICs using statically verified Linux’s eBPF programs. We discuss advantages and limitations of this approach, its relationship with ongoing NIC programmability efforts, and open research challenges.

**Talk: TBA** by [Prof. Katerina Argyraki](https://people.epfl.ch/katerina.argyraki), Associate Professor at EPFL, Lausanne (13:10 - 13:40 PM CEST)

**Abstract**: TBA

**Talk: Network telemetry on a budget** by [Prof. Gianni Antichi](https://gianniantichi.github.io/index.html), Assistant Professor at QMUL, London (13:40 - 14:10 PM CEST)

**Abstract**: The possibility to easily add new functionality to network data planes has lately opened new exciting research directions towards understanding how such a programmability can impact the design of networks as well as their services. In this talk, I will present some of the work I have been doing in rethinking the 
way programmable data planes can be employed for network monitoring. With a focus on the in-band network telemetry (INT), I will analyse its drawbacks and introduce our effort in reducing the overheads on packets that this fine-grained measurement mechanism requires. I will then discuss challenges and open research questions for next generation network monitoring solutions. 

**Closing Remarks**

**Workshop Organizers**

[Apoorv Shukla](https://www.apoorv.net/) (Huawei Munich Research Center)

[Jorge Cardoso](https://jorge-cardoso.github.io/) (Huawei Munich Research Center and University of Coimbra)

[Odej Kao](https://www.cit.tu-berlin.de/kao/) (TU Berlin)

**Diversity and Inclusion**

We are committed to creating an inclusive and welcoming workshop. We have strived to create a diverse program and participant pool for our workshop, and to share our workshop widely. However, we also are grateful for suggestions of any individual researchers who we might have missed.

Questions? Contact us at [apoorv.shukla@huawei.com](mailto:apoorv.shukla@huawei.com?subject=[GitHub]%20Source%20Han%20Sans).

**Sponsors**

This workshop is sponsored by **Huawei Technologies Co.**, Ltd on behalf of **Huawei-TU Berlin Innovation Lab**.



<!--- You can use the [editor on GitHub](https://github.com/NetworkVerification-workshop/NetworkVerification-workshop.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.
Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.
### Markdown
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for
```markdown
Syntax highlighted code block
# Header 1
## Header 2
### Header 3
- Bulleted
- List
1. Numbered
2. List
**Bold** and _Italic_ and `Code` text
[Link](url) and ![Image](src)
```
For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
### Jekyll Themes
Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/NetworkVerification-workshop/NetworkVerification-workshop.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.
### Support or Contact
Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out. just --->
