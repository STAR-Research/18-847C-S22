# 18-847C: Data Center Computing (Spring 2022)

## Announcements

| Date      | Note |
| ----------- | ----------- |
| **1/19/22**      | - Fill in the [18-847C student information form](https://forms.gle/aZxPn6Dp5SSaiVUf6)<br /> - If you are enrolled, you should have received an invitation to join the 18-847C slack channel and to create an account on the [paper review hotcrp website](https://cmu-18847-s22.hotcrp.com/) (please create a hotcrp account asap).  <br/> - Final paper templates can be found [here](https://www.usenix.org/conferences/author-resources/paper-templates)<br/> - We intend to make course recordings available. However, a large fraction of your grade is based on class participation.<br/> - You can use the "project-groups" channel on slack to discuss your background and interests (with the ultimate goal of finding your team members) <br/> |
| **1/24/22** | - Paper presentation schedule was out last week. Please check your assignment below. <br/> - You should have received an invitation to view a document with a list of potential research directions for your course project. <br/> - You should have ideally found your project partners by today. Please continue to use the #project-groups Slack channel for this. <br/> - Start preparing a paragraph or two to let us know about the broad research direction of your project (due Jan 26). <br/>| 

## Administrivia

### Course information

**Instructor:**  Akshitha Sriraman <br/>		
**Office Location:**  CIC 4122  
**Email Address:**  akshitha@cmu.edu  
**Office Hours:**  Mondays, 3:30 - 4:30 pm ET 

**Teaching Assistants:**  Youssef Kallel, Shreya Srinarasi <br/>
**Email Address:**  ykallel@andrew.cmu.edu, ssrinara@andrew.cmu.edu <br/>	
**Office Hours:**	  TBA	

**Course Support:**  Academic Services Center <br/>
**Office Location:**  HH 1113 <br/>
**Website:**  https://www.ece.cmu.edu/academics/academic-services-center.html

**Course Description:**  Hyperscale data centers host a wide range of online services such as cloud computing, social networks, video streaming, online messaging, web search, and online banking. This course will focus on studying the systems software, hardware, and distributed systems technology that compose modern data centers. The course will also expose students to cross-cutting data center issues related to service level objectives, latency unpredictability, total cost of ownership, energy efficiency, scalability, and availability.

The course is a combination of lectures, paper reading, and a semester-long project. Students will read up to two seminal papers per topic and submit brief summaries. In the classroom, we will start with a student presentation of the papers followed by an interactive discussion on the papers in terms of design innovation and challenges. Students will work in groups of three on a semester-long, open-ended research project on a cutting-edge data center topic.

This course is appropriate for graduate and advanced undergraduate students from ECE and CS who are interested in a vertical study of advanced cloud computing and data center systems. It is also appropriate for ECE and CS students who want to gain some experience with a semester-long research project on a cutting-edge computer systems topic.

Students are expected to attend class meetings and actively participate in the discussions. Paper summaries, presentations, and class participation are part of the grade. There is no formal prerequisite for this course. However, it would be helpful if students have a basic understanding of systems and architecture concepts and are comfortable with C/C++ and/or Python programming.

**Number of Units:**  12 	

**Pre-requisites:**  There is no formal prerequisite for this course.   	
However, it would be helpful if students have a basic understanding of systems and architecture concepts and are comfortable with C/C++ and/or Python programming.

**Graduate Area:**  Computer Systems	

**Class lecture and recordings:**  MW 4:40 - 6 pm ET at WEH 4625 (which is contingent on whether/when we move to in-person instruction. Until then, please use the Zoom link available in canvas "announcements".) Class lectures will be audio/video recorded and made available to other students in this course. As part of your participation in this course, you may be recorded.

**Paper reviews:** https://cmu-18847-s22.hotcrp.com/ (Create an account ASAP!)
To submit a review after logging in, click on the paper you wish to review and follow the prompts to enter your review in terms of "strengths," "weaknesses," etc. The paper reviews allotted for each class are due on the day of the class by noon ET. Please submit your review exactly once. You may view other students' reviews after you submit your own review. Feel free to click on the "Good review" button for the reviews you like. Please refrain from clicking on the "Needs work" button for other students' reviews (you will be penalized for this).

**Required Textbook:**  None

**Suggested Reading:**  The Datacenter as a Computer

**Other Supplemental Materials:**  Papers that will be shared through the course

**Brief List of Topics Covered:**
* Microservices
* Architectural analysis of data center applications
* Hardware acceleration
* Compilation techniques to improve data center efficiency
* Tail latency
* The killer microsecond problem
* Concurrency/threading
* Operating systems for data center applications
* Resource management and scheduling
* Resource disaggregation
* Networking in data centers
* Data center caching
* Monitoring infrastructure at scale
* Data center systems for machine learning
* Machine learning for data center systems
* Serverless computing
* Data center storage
* Data center energy efficiency
* Security

**Course Canvas:** 
Canvas login page: https://canvas.cmu.edu/courses/. 

**Course Website:** You should check this website daily for announcements and handouts. 

**Discussion Platform:**  Students enrolled in the course should have received a Slack invitation. Please contact the instructors via email if you did not receive an invite. 

**Projects:** Students will work in groups of three on a semester-long, open-ended research project on a cutting-edge data center topic.  

**Reading Assignments:** We will read and review roughly two research papers before each class. Each student will present two such papers during the course of the semester. 

### Grading Algorithm
* **(45%) Course Project:** Students will work in teams of three on a research project related to improving the efficiency of data center systems. Deliverables will include a proposal, mid-term presentation, final presentation, and final research paper. This assignment will provide students with the experience of performing research in the field of large-scale computing.
* **(20%) Paper Reviews:** We will be writing reviews for the papers that we read in this course. These reviews will help practice critical examination of research papers related to data center computing. Each student can skip a total of three reviews across the semester (choose wisely!). Each miss beyond three will result in 25% decrease in grade for this portion of the course (i.e., 5% out of the 20% alloted for the Paper Reviews component). Missing seven or more paper reviews will result in getting 0% out of the 20% possible for the Paper Reviews component. Reviews will be submitted through [hotCRP](https://cmu-18847-s22.hotcrp.com/). We will discuss the guidelines for writing reviews during the first couple of lectures.
* **(15%) Paper Presentations:** Each student will be responsible for presenting and leading the discussion of two papers that we read this semester. Each student will be able to choose the papers that they present. We will discuss guidelines for presentations during the first couple of lectures.
* **(20%) Participation:** Much of the discovery and learning in this course will be driven by in-class discussion. Participation will be assessed by engagement during in-class discussions. Therefore, it is critical that students attend lectures. 

### Project milestones

* **(Jan 24/ASAP) Find project partners:** Create a group of three like-minded students
* **(Jan 26) Contact instructors:** Email the instructors with your group's proposal (~2 paragraphs)
* **(Feb 2) Finalize deliverables:** Finalize project deliverables after regular back-and-forth discussions with the instructors
* **(March 2) First milestone:** Submit your first milestone document that defines and motivates the problem, surveys related work, forms initial hypothesis and idea, and potentially includes some preliminary result (email instructors)
*  **(April 4) Second milestone:** Submit your second milestone document with a brief description of the idea, your design and implementation details, and a portion of your evaluation (email instructors)
*  **(April 27) Final presentation:** Prepare a brief presentation (~10 minutes) of your project work
*  **(April 29) Final report:** Submit a final paper on your work (similar to the papers that we read and discussed in class)

### Compute resource options for your project

* [The ECE Numbers cluster](https://userguide.its.cit.cmu.edu/research-computing/computer-clusters/): You will likely have to share these resources with other folks. If your project involves fine-grained performance measurements on real hardware, this might not be the best option since you might encounter intereference effects from co-runners.
* [The ECE Data Science cloud](https://userguide.its.cit.cmu.edu/research-computing/computer-clusters/): You will likely have to share these resources with other folks. If your project involves fine-grained performance measurements on real hardware, this might not be the best option since you might encounter intereference effects from co-runners.
* [CloudLab](https://www.cloudlab.us/): Please contact the instructor with your email addresses. The instructor will create a project on CloudLab for you and add you to the project. You will get dedicated access to machine using CloudLab and will therefore not encounter intereference effects. 
* [Pittsburgh Supercomputing center](https://www.psc.edu/): If you need substantial computing, we can do an education allocation at the Pittsburg Supercomputing Center. Here, we can get access to the Bridges and Bridges-DL machine with 60,000 CPU cores and about 80+ A100 GPUs. Of course you wouldn't use the entire machine, but you have flexibility.
* [Google Cloud Platform](https://cloud.google.com/): Contact the instructor if you need access to GCP educational credits. If your project involves fine-grained performance measurements on real hardware, this might not be the best option since it might be harder to measure hardware performance counters, you might face interference effects from co-runners, might face overheads from virtualization, etc.
* Please contact the instructor if none of the above computing options work for you. We will work with you to meet your needs as best as we can. 

### Schedule
Please submit a review for all papers (from Jan 24) on hotcrp. Here is the review [template](https://gist.github.com/kasikci/49e7107dfdee281d6f6450b132555550) we will use.

| Date      | Topic | Readings | Notes | Presenter |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| Jan 19 (W) <br/> ([slides](https://drive.google.com/file/d/1rUD64nYI9CqlwQBVg3f2-iSoioYxN_R0/view?usp=sharing))<br/> ([lecture](https://ece.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=57f07c3c-ee5c-48e8-930e-ae2300021eab))| Introduction to Data center Computing | Introduction |[Form](https://forms.gle/aZxPn6Dp5SSaiVUf6) due|
| Jan 24 (M) <br/> ([lecture](https://ece.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=6df07813-1cdb-4015-86af-ae270185b9eb)) | [Profiling a Warehouse-Scale Computer](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44271.pdf) | Introduction | Guest: [Svilen Kanev](https://skanev.org/) (Google), Find project partners | Akshitha Sriraman |
| Jan 26 (W) <br/> ([lecture](https://ece.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=8034a6cc-2bc9-4373-8931-ae2a00025814)) <br/> ([slides](https://docs.google.com/presentation/d/1NJtWc8xfn2G0KstIuaUVmEzLShww08p7ou12-F5w3Tw/edit?usp=sharing))| - [Introduction to microservices](https://www.nginx.com/blog/introduction-to-microservices/) (read paper; review not required) <br/> - [An Open-Source Benchmark Suite for Microservices and Their Hardware-Software Implications for Cloud and Edge Systems](http://www.csl.cornell.edu/~delimitrou/papers/2019.asplos.microservices.pdf) | Microservices | Contact instructors about your project| 1. Akshitha Sriraman <br/> 2. Grace Fieni |
| Jan 31 (M) <br/> ([lecture](https://ece.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=5ed05a98-5ccf-4587-a459-ae2e01820762)) <br/> ([slides](https://drive.google.com/file/d/1mWfo9tnolx9NzobijxcaHkoXPMUrPP2a/view?usp=sharing))| - [SoftSKU: Optimizing Server Architectures for Microservice Diversity @Scale](https://dl.acm.org/doi/10.1145/3307650.3322227) <br/> - [Memory Hierarchy for Web Search](https://web.stanford.edu/~kozyraki/publications/2018.search.hpca.pdf) | Microarchitecture analysis | Guest: [Grant Ayers](https://research.google/people/GrantAyers/) (Google)| 1. Akshitha Sriraman <br/> 2. Akshay Revankar |  
| Feb 2 (W) <br/> ([lecture](https://ece.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=9428ab4d-713e-438e-9715-ae300182a844)) <br/> ([slides](https://docs.google.com/presentation/d/15vZu-JkQVhnN_KexnM1-9T5xRuzGHDWDc86R-Ae79jY/edit?usp=sharing)) <br/> ([slides](https://drive.google.com/file/d/1bUTxYi81VucDc7dm474ypadW9zGw9gp-/view?usp=sharing)) | - [Dagger: Efficient and Fast RPCs in Cloud Microservices with Near-Memory Reconfigurable NICs](https://www.csl.cornell.edu/~delimitrou/papers/2021.asplos.dagger.pdf) <br/> - [A hardware accelerator for protocol buffers](https://sagark.org/assets/pubs/protoacc-micro2021-preprint.pdf) | Accelerating data center tax | - Guest: [Sagar Karandikar](https://sagark.org/) (UC Berkeley) <br/> - Finalize project deliverables | 1. Sanil Rao <br/> 2. Balamurugan Marimuthu |
| Feb 7 (M) <br/> ([lecture](https://ece.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=a899049d-d712-4d3a-aac9-ae3501820be9)) <br/> ([slides](https://docs.google.com/presentation/d/1rPu6xqwHvvHYL1_vy4BMi4kHC7ZHP5yF/edit?usp=sharing&ouid=106982327082846840948&rtpof=true&sd=true)) <br/> ([slides](https://drive.google.com/file/d/1xRYlwPis9UVOvAUmO-bwX1IzAroW1604/view?usp=sharing))| - [A Reconfigurable Fabric for Accelerating Large-Scale Datacenter Services](http://dl.acm.org/citation.cfm?id=2665678) <br/> - [Warehouse-scale video acceleration: co-design and deployment in the wild](https://www.gwern.net/docs/cs/2021-ranganathan.pdf) | Hardware acceleration | | 1. Ali Hoffmann <br/> 2. Plava Kattamuri |
| Feb 9 (W) <br/> ([slides](https://drive.google.com/file/d/106bcxV4zJ-Lxcy_RVcYNWqqX0GQ-4GFw/view?usp=sharing)) <br/> ([lecture](https://ece.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=f01c8f8a-60da-437f-af29-ae370184e6ad)) | - [AsmDB: Understanding and Mitigating Front-End Stalls in Warehouse-Scale Computers](https://dl.acm.org/doi/pdf/10.1145/3307650.3322234) <br/> - [Twig: Profile-Guided BTB Prefetching for Data Center Applications](https://web.eecs.umich.edu/~takh/papers/khan-twig-micro-2021.pdf) | Compiler/PGO | Guest: [Tanvir Ahmed Khan](https://web.eecs.umich.edu/~takh/) (U. Michigan)  | 1. Sartaj Singh Wariah <br/> 2. Tanvir Ahmed Khan |
| Feb 14 (M) <br/> ([lecture](https://ece.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=fe146540-1ee9-4d82-a356-ae3c01877edd)) <br/> ([slides](https://drive.google.com/file/d/1s6Sud2dMZCu9KNo6OFEm8Z3NVjlasgcU/view?usp=sharing)) <br/> ([slides](https://docs.google.com/presentation/d/14dU3PpR-HwdwxZv_fyuOLgMPANgJlhnX/edit?usp=sharing&ouid=106982327082846840948&rtpof=true&sd=true))| - [The Tail at Scale](https://cacm.acm.org/magazines/2013/2/160173-the-tail-at-scale/fulltext) <br/> - [Amdahl’s Law for Tail Latency](https://www.csl.cornell.edu/~delimitrou/papers/2018.cacm.amdahlsTail.pdf) | Tail latency | | 1. Rishi Malladi <br/> 2. Grace Fieni |
| Feb 16 (W) <br/> ([lecture](https://ece.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=d22f4aa0-00b7-4385-a980-ae3e0181465c)) <br/> ([slides](https://drive.google.com/file/d/1BEpjCzfsmq0ARN-HZ_tdEhA5KqECoAgf/view?usp=sharing)) | - [uTune: Auto-Tuned Threading for OLDI Microservices](https://www.usenix.org/system/files/osdi18-sriraman.pdf) <br/> - [Few-to-Many: Incremental Parallelism for Reducing Tail Latency in Interactive Services](https://abelay.github.io/6828seminar/papers/haque:fewtomany.pdf) | Concurrency/Threading | Guest: [Md Haque](https://www.linkedin.com/in/md-ehtesam-haque-28b1a087/) (Google) | 1. Mihailo Rancic <br/> 2. Chenlyu Zhao |
| Feb 21 (M) <br/> ([slides](https://docs.google.com/presentation/d/132gJRCRk19-lUBoPBsrYxFSdCXSNomTOm04OwwPnahk/edit?usp=sharing)) <br/> ([slides](https://docs.google.com/presentation/d/12V5t75wwt-ZShDV3BGQF_OE9rZzEeZwI/edit?usp=sharing&ouid=106982327082846840948&rtpof=true&sd=true))| - [Attack of the Killer Microseconds](https://abelay.github.io/6828seminar/papers/barroso:killermicroseconds.pdf) <br/> - [Enhancing Server Efficiency in the Face of Killer Microseconds](https://docs.wixstatic.com/ugd/66fd54_b1a7b4d81fee4750a8cfd19107c8f55a.pdf) | Killer microseconds | | 1. Upasana Sridhar <br/> 2. Zunyan Wang |
| Feb 23 (W) <br/> ([lecture](https://ece.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=3699a254-80ef-4d9c-a74f-ae4501818790)) <br/> ([slides](https://docs.google.com/presentation/d/1qV0IYDMMNZa2WtgjZTlHmIc-WwZWubfD/edit?usp=sharing&ouid=106982327082846840948&rtpof=true&sd=true)) | - [IX: a protected dataplane operating system for high throughput and low latency](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-belay.pdf) <br/> - [The Demikernel Datapath OS Architecture for Microsecond-scale Datacenter Systems ](https://www.microsoft.com/en-us/research/publication/the-demikernel-datapath-os-architecture-for-microsecond-scale-datacenter-systems/) | OS | Guest: [Irene Zhang](https://irenezhang.net/) (Microsoft Research)| 1. Andrew Spaulding <br/> 2. Charan Renganathan|
| Feb 28 (M) <br/> ([lecture](https://ece.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=678bad47-4b11-446f-8af4-ae4a017f9800)) <br/> ([slides](https://docs.google.com/presentation/d/1RWnBJcU6nh02bll-k-kWDxmRZ1n3FlNg/edit?usp=sharing&ouid=106982327082846840948&rtpof=true&sd=true)) <br/> ([slides](https://drive.google.com/file/d/1pCc_JH6DZBNL5Cxv8qjG-yqR4hN6TqGI/view?usp=sharing)) | - [ghOSt: Fast & Flexible User-Space Delegation of Linux Scheduling](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/0ee589331b9bf270b13d40ba09453cde14006869.pdf) <br/> - [A Case Against (Most) Context Switches](https://sigops.org/s/conferences/hotos/2021/papers/hotos21-s01-humphries.pdf) | OS | | 1. Andrew Jacob <br/> 2. Nathan Levin |
| March 2 (W) <br/> ([lecture](https://ece.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=fa431086-3bf2-4186-a289-ae4c01831b91)) <br/> ([slides](https://drive.google.com/file/d/1xIQhODE9w-0L1MO4hBjGRmGY6kKLqpto/view?usp=sharing)) | - [Large-scale cluster management at Google with Borg](http://research.google.com/pubs/pub43438.html) <br/> - [Quasar: Resource-Efficient and QoS-Aware Cluster Management](https://www.csl.cornell.edu/~delimitrou/papers/2014.asplos.quasar.pdf) | Resource management/scheduling | First milestone due | 1. Syeda Sheherbano Rizvi <br/> 2. Rishi Malladi |
| March 7 (M) | **Spring break: No Classes** |  | |
| March 9 (W) | **Spring break: No Classes** |  | |
| March 14 (M) | - [PARTIES: QoS-Aware Resource Partitioning for Multiple Interactive Services](http://people.ece.cornell.edu/martinez/doc/asplos19.pdf) <br/> - [Resource Central: Understanding and PredictingWorkloads for Improved Resource Management inLarge Cloud Platforms](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/10/Resource-Central-SOSP17.pdf) | Resource management/scheduling | Guest: [Ricardo Bianchini](https://www.microsoft.com/en-us/research/people/ricardob/) (Microsoft Research)| 1. Mihailo Rancic <br/> 2. Plava Kattamuri |
| March 16 (W) | - [Network Requirements for Resource Disaggregation](https://www.usenix.org/system/files/conference/osdi16/osdi16-gao.pdf) <br/> - [LegoOS: A Disseminated, Distributed OS for Hardware Resource Disaggregation](https://www.usenix.org/system/files/osdi18-shan.pdf) | Resource disaggregation | | 1. Akshay Revankar <br/> 2. Sanil Rao |
| March 21 (M) | - [Azure Accelerated Networking: SmartNICs in the Public Cloud](https://www.usenix.org/system/files/conference/nsdi18/nsdi18-firestone.pdf) <br/> - [Snap: a Microkernel Approach to Host Networking](https://research.google/pubs/pub48630/) | Networking | Guest: [Lena Olson](https://www.linkedin.com/in/lena-olson-26477b91) (Google)| 1. Zunyan Wang <br/> 2. Andrew Spaulding |
| March 23 (W) | - [RobinHood: Tail Latency Aware Caching -- Dynamic Reallocation from Cache-Rich to Cache-Poor](https://www.usenix.org/system/files/osdi18-berger.pdf) <br/> - [Kangaroo: Caching Billions of Tiny Objects on Flash](https://www.pdl.cmu.edu/PDL-FTP/NVM/McAllister-SOSP21.pdf) | Datacenter Caching | Guest: [Sara McAllister](https://saramcallister.github.io/) (CMU)| 1. Andrew Jacob <br/> 2. Akshay Revankar|
| March 28 (M) | - [The Mystery Machine: End-to-end Performance Analysis of Large-scale Internet Services ](https://www.usenix.org/node/186168) <br/> - [Sage: Practical & Scalable ML-Driven Performance Debugging in Microservices](https://www.csl.cornell.edu/~delimitrou/papers/2021.asplos.sage.pdf) | Monitoring/Debugging | | 1. Charan Renganathan <br/> 2. Upasana Sridhar |
| March 30 (W) | - [Applied Machine Learning at Facebook: A Datacenter Infrastructure Perspective](https://abelay.github.io/6828seminar/papers/hazelwood:ml.pdf) <br/> - [In-Datacenter Performance Analysis of a Tensor Processing Unit](https://abelay.github.io/6828seminar/papers/jouppi:tpu.pdf) | Systems for ML | | 1. Ali Hoffmann <br/> 2. Sartaj Singh Wariah |
| April 4 (M) | - [Toward ML-Centric Cloud Platforms](https://www.microsoft.com/en-us/research/uploads/prod/2020/01/CACM20-produced.pdf) <br/> - [Software-defined far memory in warehouse-scale computers](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/9bb06ab825a127bef4e33c488eaa659d6856225a.pdf) | ML for datacenter systems | Second milestone due | 1. Chenlyu Zhao <br/> 2. Nathan Levin |
| April 6 (W) | - [Cost-Efﬁcient Overclocking in Immersion-Cooled Datacenters](https://www.microsoft.com/en-us/research/publication/cost-ef%ef%ac%81cient-overclocking-in-immersion-cooled-datacenters/) <br/> - [Chasing Carbon: The Elusive Environmental Footprint of Computing](https://arxiv.org/pdf/2011.02839.pdf) | Power/energy | Guest: [Carole-Jean Wu](https://carolewu.engineering.asu.edu/) (Meta) | 1. Nikhil Arora <br/> 2. Charan Renganathan |
| April 11 (W) | - [Nightcore: efficient and scalable serverless computing for latency-sensitive, interactive microservices](https://www.cs.utexas.edu/~zjia/nightcore-asplos21.pdf) <br/> - [Serverless in the Wild: Characterizing and Optimizingthe Serverless Workload at a Large Cloud Provider](https://www.microsoft.com/en-us/research/uploads/prod/2020/05/serverless-ATC20.pdf) | Serverless computing | Guest: [Mohammad Shahrad](https://mshahrad.github.io/) (UBC) | 1. Plava Kattamuri <br/> 2. Balamurugan Marimuthu |
| April 13 (M) | - [Pocket: Elastic Ephemeral Storage for Serverless Analytics](https://www.usenix.org/system/files/osdi18-klimovic.pdf) <br/> - [The Google File System](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf) | Datacenter storage | | 1. Nikhil Arora <br/> 2. Sanil Rao  |
| April 18 (M) | - [Bolt: I Know What You Did Last Summer... in the Cloud](https://www.csl.cornell.edu/~delimitrou/papers/2017.asplos.bolt) <br/> - [Hey, You, Get Off of My Cloud: Exploring Information Leakage in Third-Party Compute Clouds](https://hovav.net/ucsd/dist/cloudsec.pdf) | Security | | 1. Upasana Sridhar <br/> 2. Syeda Sheherbano Rizvi |
| April 20 (W) | Papers decided by the class |  | |  |
| April 25 (M) | Papers decided by the class |  | |  |
| April 27 (W) | Project presentations |  | |  |
| April 29 (F) | Final report due |  | |  |

### Education Objectives (Relationship of Course to Program Outcomes)

The ECE department is accredited by ABET to ensure the quality of your education.  ABET defines 7 Educational Objectives that are fulfilled by the sum total of all the courses you take.  The following list describes which objectives are fulfilled by this course and in what manner they are fulfilled. The objectives are numbered from “1” through “7” in the standard ABET parlance. Those objectives not fulfilled by this course have been omitted from the following list:

* an ability to identify, formulate, and solve complex engineering problems by applying principles of engineering, science, and mathematics
* an ability to apply engineering design to produce solutions that meet specified needs with consideration of public health, safety, and welfare, as well as global, cultural, social, environmental, and economic factors
* an ability to communicate effectively with a range of audiences
* an ability to recognize ethical and professional responsibilities in engineering situations and make informed judgments, which must consider the impact of engineering solutions in global, economic, environmental, and societal contexts
* an ability to function effectively on a team whose members together provide leadership, create a collaborative and inclusive environment, establish goals, plan tasks, and meet objectives
* an ability to develop and conduct appropriate experimentation, analyze and interpret data, and use engineering judgment to draw conclusions
* an ability to acquire and apply new knowledge as needed, using appropriate learning strategies.

### ECE Academic Integrity Policy 
([http://www.ece.cmu.edu/programs-admissions/masters/academic-integrity.html](http://www.ece.cmu.edu/programs-admissions/masters/academic-integrity.html)):

The Department of Electrical and Computer Engineering adheres to the academic integrity policies set forth by Carnegie Mellon University and by the College of Engineering. ECE students should review fully and carefully Carnegie Mellon University's policies regarding Cheating and Plagiarism; Undergraduate Academic Discipline; and Graduate Academic Discipline. ECE graduate student should further review the Penalties for Graduate Student Academic Integrity Violations in CIT outlined in the CIT Policy on Graduate Student Academic Integrity Violations. In addition to the above university and college-level policies, it is ECE's policy that an ECE graduate student may not drop a course in which a disciplinary action is assessed or pending without the course instructor's explicit approval. Further, an ECE course instructor may set his/her own course-specific academic integrity policies that do not conflict with university and college-level policies; course-specific policies should be made available to the students in writing in the first week of class.
This policy applies, in all respects, to this course.

CMU Academic Integrity Policy ([http://www.cmu.edu/academic-integrity/index.html](http://www.cmu.edu/academic-integrity/index.html)):
In the midst of self-exploration, the high demands of a challenging academic environment can create situations where some students have difficulty exercising good judgment. Academic challenges can provide many opportunities for high standards to evolve if students actively reflect on these challenges and if the community supports discussions to aid in this process. It is the responsibility of the entire community to establish and maintain the integrity of our university.
This site is offered as a comprehensive and accessible resource compiling and organizing the multitude of information pertaining to academic integrity that is available from across the university. These pages include practical information concerning policies, protocols and best practices as well as articulations of the institutional values from which the policies and protocols grew. The Carnegie Mellon Code, while not formally an honor code, serves as the foundation of these values and frames the expectations of our community with regard to personal integrity.  
This policy applies, in all respects, to this course.

### The Carnegie Mellon Code

Students at Carnegie Mellon, because they are members of an academic community dedicated to the achievement of excellence, are expected to meet the highest standards of personal, ethical and moral conduct possible.
These standards require personal integrity, a commitment to honesty without compromise, as well as truth without equivocation and a willingness to place the good of the community above the good of the self. Obligations once undertaken must be met, commitments kept.
As members of the Carnegie Mellon community, individuals are expected to uphold the standards of the community in addition to holding others accountable for said standards. It is rare that the life of a student in an academic community can be so private that it will not affect the community as a whole or that the above standards do not apply.
The discovery, advancement and communication of knowledge are not possible without a commitment to these standards. Creativity cannot exist without acknowledgment of the creativity of others. New knowledge cannot be developed without credit for prior knowledge. Without the ability to trust that these principles will be observed, an academic community cannot exist.
The commitment of its faculty, staff and students to these standards contributes to the high respect in which the Carnegie Mellon degree is held. Students must not destroy that respect by their failure to meet these standards. Students who cannot meet them should voluntarily withdraw from the university.

This policy applies, in all respects, to this course.

### Carnegie Mellon University's Policy on Cheating 
([http://www.cmu.edu/academic-integrity/cheating/index.html](http://www.cmu.edu/academic-integrity/cheating/index.html)) states the following:
According to the University Policy on Academic Integrity, cheating "occurs when a student avails her/himself of an unfair or disallowed advantage which includes but is not limited to:
* Theft of or unauthorized access to an exam, answer key or other graded work from previous course offerings.
* Use of an alternate, stand-in or proxy during an examination.
* Copying from the examination or work of another person or source.
* Submission or use of falsified data.
* Using false statements to obtain additional time or other accommodation.
* Falsification of academic credentials.”
* This policy applies, in all respects, to this course.  

### Carnegie Mellon University's Policy on Plagiarism 
([http://www.cmu.edu/academic-integrity/plagiarism/index.html](http://www.cmu.edu/academic-integrity/plagiarism/index.html)) states the following:
According to the University Policy on Academic Integrity, plagiarism "is defined as the use of work or concepts contributed by other individuals without proper attribution or citation. Unique ideas or materials taken from another source for either written or oral use must be fully acknowledged in academic work to be graded. Examples of sources expected to be referenced include but are not limited to:
* Text, either written or spoken, quoted directly or paraphrased.
* Graphic elements.
* Passages of music, existing either as sound or as notation.
* Mathematical proofs.
* Scientific data.
* Concepts or material derived from the work, published or unpublished, of another person."
* This policy applies, in all respects, to this course.  

### Carnegie Mellon University's Policy on Unauthorized Assistance 
(http://www.cmu.edu/academic-integrity/collaboration/index.html) states the following:

According to the University Policy on Academic Integrity, unauthorized assistance "refers to the use of sources of support that have not been specifically authorized in this policy statement or by the course instructor(s) in the completion of academic work to be graded. Such sources of support may include but are not limited to advice or help provided by another individual, published or unpublished written sources, and electronic sources. Examples of unauthorized assistance include but are not limited to:
Collaboration on any assignment beyond the standards authorized by this policy statement and the course instructor(s).
Submission of work completed or edited in whole or in part by another person.
Supplying or communicating unauthorized information or materials, including graded work and answer keys from previous course offerings, in any way to another student.
Use of unauthorized information or materials, including graded work and answer keys from previous course offerings.
Use of unauthorized devices.
Submission for credit of previously completed graded work in a second course without first obtaining permission from the instructor(s) of the second course. In the case of concurrent courses, permission to submit the same work for credit in two courses must be obtained from the instructors of both courses."
This policy applies, in all respects, to this course.

### Carnegie Mellon University's Policy on Research Misconduct 
(http://www.cmu.edu/academic-integrity/research/index.html) states the following:

According to the University Policy for Handling Alleged Misconduct in Research, “Carnegie Mellon University is responsible for the integrity of research conducted at the university. As a community of scholars, in which truth and integrity are fundamental, the university must establish procedures for the investigation of allegations of misconduct of research with due care to protect the rights of those accused, those making the allegations, and the university. Furthermore, federal regulations require the university to have explicit procedures for addressing incidents in which there are allegations of misconduct in research.”

The policy goes on to note that “misconduct means:

* fabrication, falsification, plagiarism, or other serious deviation from accepted practices in proposing, carrying out, or reporting results from research;

* material failure to comply with Federal requirements for the protection of researchers, human subjects, or the public or for ensuring the welfare of laboratory animals; or

* failure to meet other material legal requirements governing research.”

“To be deemed misconduct for the purposes of this policy, a ‘material failure to comply with Federal requirements’ or a ‘failure to meet other material legal requirements’ must be intentional or grossly negligent.”

To become familiar with the expectations around the responsible conduct of research, please review the guidelines for Research Ethics published by the Office of Research Integrity and Compliance.

This policy applies, in all respects, to this course.

### Take care of yourself.  
Do your best to maintain a healthy lifestyle this semester by eating well, exercising, avoiding drugs and alcohol, getting enough sleep and taking some time to relax. This will help you achieve your goals and cope with stress. 

All of us benefit from support during times of struggle. You are not alone. There are many helpful resources available on campus and an important part of the college experience is learning how to ask for help. Asking for support sooner rather than later is often helpful. 

If you or anyone you know experiences any academic stress, difficult life events, or feelings like anxiety or depression, we strongly encourage you to seek support. Counseling and Psychological Services (CaPS) is here to help: call 412-268-2922 and visit their website at [http://www.cmu.edu/counseling/](http://www.cmu.edu/counseling/). Consider reaching out to a friend, faculty or family member you trust for help getting connected to the support that can help.  

If you have questions about this or your coursework, please let me know.

### Every individual must be treated with respect.
The ways we are diverse are many and are critical to excellence and an inclusive community. They include but are not limited to: race, color, national origin, sex, disability, age, sexual orientation, gender identity, religion, creed, ancestry, belief, veteran status, or genetic information. We at CMU, will work to promote diversity, equity and inclusion because it is just and necessary for innovation.  Therefore, while we are imperfect, we will work inside and outside of our classrooms, to increase our commitment to build and sustain a community that embraces these values.

It is the responsibility of each of us to create a safer and more inclusive environment. Bias incidents, whether intentional or unintentional in their occurrence, contribute to creating an unwelcoming environment for individuals and groups at the university. If you experience or observe unfair or hostile treatment on the basis of identity, we encourage you to speak out for justice and support in the moment and and/or share your experience anonymously using the following resources:

### Center for Student Diversity and Inclusion: 
csdi@andrew.cmu.edu, (412) 268-2150,  [www.cmu.edu/student-diversity](www.cmu.edu/student-diversity) 
Report-It online anonymous reporting platform: [www.reportit.net](www.reportit.net) username: tartans password: plaid

All reports will be acknowledged, documented and a determination will be made regarding a course of action.” All experiences shared will be used to transform the campus climate. 
 
### Disability Accommodation
* [ABLE CMU](https://thebridge.cmu.edu/organization/able-cmu)
* [Here for You](https://thebridge.cmu.edu/organization/here-for-you)
* Acute Medical Episodes: For example an accident, emergency surgery, etc: Seek a third party opinion (Diane Dawson at UHS). This offers confidential, retroactive excuses for exams/homeworks.

