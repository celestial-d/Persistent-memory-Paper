# SystemPaper

name	conference 	year	goal	tools	capture	following work
Multi-stage Replay with Crosscut	VEE	2010	a self-defined record and replay platform	vmware, record&replay	instruction	
Eidetic Systems	OSDI	2014	a practical eidetic computing platform	PIN, record&replay	instruction	Rain: Refinable Attack Investigation with On-demand Inter-Process Information Flow Tracking
Optimistic Hybrid Analysis: Accelerating Dynamic Analysis through Predicated Static Analysis	ASPLOS	2018	hybrid analysis for application, data race bug detection	llvm	state	
Rain: Refinable Attack Investigation with On-demand Inter-Process Information Flow Tracking	CCS	2017	a method to investigate attack by record and replay	PIN, record&replay	instruction	
PALLAS: Semantic-Aware Checking for Finding Deep Bugs in Fast Path	ASPLOS	2017				
Understanding Real-World Concurrency Bugs in Go	ASPLOS	2019				
SherLog: Error Diagnosis by Connecting Clues from Run-time Logs	ASPLOS	2010				
Improving Software Diagnosability via Log Enhancement	ASPLOS	2011				
Production-Run Software Failure Diagnosis via Hardware Performance Counters	ASPLOS	2013				
Leveraging the Short-Term Memory of Hardware to Diagnose Production-Run Software Failures	ASPLOS	2014				
Cross-Failure Bug Detection in Persistent Memory Programs	ASPLOS	2020				
Debugging operating systems with time-traveling virtual machines	ATC	2005	find a method to debug OS 	VMM, GDB, ptrace, ReVirt	system calls, signals,instructions	
Decoupling dynamic program analysis from execution in virtual environments	ATC	2008		qemu,Vmware		
Log2: A Cost-Aware Logging Mechanism for Performance Diagnosis	ATC	2015				
An Evolutionary Study of Linux Memory Management for Fun and Profit	ATC	2016				
Fast and Precise Retrieval of Forward and Back Porting Information for Linux Device Drivers	ATC	2017				
Engineering Record And Replay For Deployability	ATC	2017				
A DSL Approach to Reconcile Equivalent Divergent Program Executions	ATC	2017				
DSAC: Effective Static Analysis of Sleep-in-Atomic-Context Bugs in Kernel Modules	ATC	2018	analyze SAC bug features and detect SAC bugs 	LLVM+clang	bytecode	
Coccinelle: 10 Years of Automated Evolution in the Linux Kernel	ATC	2018	analyze coccinelle history	coccinelle		
Kernel-Supported Cost-Effective Audit Logging for Causality Tracking	ATC	2018				
Spindle: Informed Memory Access Monitoring	ATC	2018				
Effective Static Analysis of Concurrency Use-After-Free Bugs in Linux Device Drivers	ATC	2019				
Evaluating File System Reliability on Solid State Drives	ATC	2019				
Reverse Debugging of Kernel Failures in Deployed Systems	ATC	2020	data flow and control flow	PT, binary analysis	instruction	
FuZZan: Efficient Sanitizer Metadata Design for Fuzzing	ATC	2020				
Can Applications Recover from fsync Failures?	ATC	2020				
SPINFER: Inferring Semantic Patches for the Linux Kernel	ATC	2020				
HDDse: Enabling High-Dimensional Disk State Embedding for Generic Failure Detection System of Heterogeneous Disks in Large Data Centers	ATC	2020				
UniSan: Proactive Kernel Memory Initialization to Eliminate Data Leakages	CCS	2016				
DIFUZE: Interface Aware Fuzzing for Kernel Drivers	CCS	2017				
VMHunt: A Verifiable Approach to Partially-Virtualized Binary Code Simplification	CCS	2019				
Tappan Zee (North) Bridge: Mining Memory Accesses for Introspection	CCS	2013				
Mitigating Sync Amplification for Copy-on-write Virtual Disk Qingshu	FAST	2016				
On the Accuracy and Scalability of Intensive I/O Workload Replay	FAST	2017				
HopsFS: Scaling Hierarchical File System Metadata Using NewSQL Databases	FAST	2017				
Fail-Slow at Scale: Evidence of Hardware Performance Faults in Large Production Systems	FAST	2018				
The CASE of FEMU: Cheap, Accurate, Scalable and Extensible Flash Emulator	FAST	2018	emulate open-channel ssd	QEMU	/	
ScaleCheck: A Single-Machine Approach for Discovering Scalability Bugs in Large Distributed Systems	FAST	2019				
Don’t Panic: Reverse Debugging of Kernel Drivers	FSE	2015	Provide a general tool for debugging 	QEMU	kernel stack 	
Crowd Debugging	FSE	2015				
Automatically Computing Path Complexity of Programs	FSE	2015				
Systematic Testing of Asynchronous Reactive Systems	FSE	2015				
Time-Travel Debugging for JavaScript/Node.js	FSE	2016				
Automated Identification of Security Issues from Commit Messages and Bug Reports	FSE	2017				
Where Is the Bug and How Is It Fixed?An Experiment with Practitioners	FSE	2017				
Detecting Missing Information in Bug Descriptions	FSE	2017				
Reproducing Concurrency Failures from Crash Stacks	FSE	2017				
Automatically Diagnosing and Repairing Error Handling Bugs in C	FSE	2017				
On the Scalability of Linux Kernel Maintainers’Work	FSE	2017				
DESCRY: Reproducing System-Level Concurrency Failures	FSE	2017				
Specifying and Checking File System Crash-Consistency Models	ASPLAS 	2016				
HDDr: A Recursive Variant of the Hierarchical Delta Debugging Algorithm	FSE	2018				
A Survey of Recent Trends in Testing Concurrent Software Systems	FSE	2018				
Target-Driven Compositional Concolic Testing with Function Summary Refinement for Effective Bug Detection	FSE	2019				
Graph-based Root Cause Analysis for Service-Oriented and Microservice Architectures	FSE	2019				
Assessing the Quality of the Steps to Reproduce in Bug Reports	FSE	2019				
An Empirical Study of Real-World Variability Bugs Detected by Variability-Oblivious Tools	FSE	2019				
Finding and Understanding Bugs in Software Model Checkers	FSE	2019				
UBITect: A Precise and Scalable Method to Detect Use-before-Initialization Bugs in Linux Kernel	FSE	2020				
Practical Safe Linux Kernel Extensibility	HotOS	2019				
You can’t debug what you can’t see: Expanding observability with the OmniTable	HotOS	2019				
Failure Sketches: A BetterWay to Debug	HotOS	2015				
It’s Not Where Your Data Is, It’s How It Got There	Hotstorage	2015				
Lazy Analytics: Let Other Queries Do the Work For You	Hotstorage	2016				
Avoiding the Streetlight Effect: I/OWorkload Analysis with SSDs in Mind	Hotstorage	2016				
CrashMonkey: A Framework to Systematically Test File-System Crash Consistency	Hotstorage	2017				
Graphs Are Not Enough: Using Interactive Visual Analytics in Storage Research	Hotstorage	2019				
A Virtual Machine Introspection Based Architecture for Intrusion Detection	NDSS	2003				
K-Tracer: A System for Extracting Kernel Malware Behavior	NDSS	2009	Analyze the data manipulation behaviors of rootkits	qemu, slicing	qemu	device request
HYPER-CUBE: High-Dimensional Hypervisor Fuzzing	NDSS	2020	detect hypervisor bugs 	qemu. Bytecode interpreter	instruction	
FUSE: Finding File Upload Bugs via Penetration Testing	NDSS	2020				
HFL: Hybrid Fuzzing on the Linux Kernel	NDSS	2020				
Automated Cross-Platform Reverse Engineering of CAN Bus Commands From Mobile Apps	NDSS	2020				
Precisely Characterizing Security Impact in a Flood of Patches via Symbolic Rule Comparison	NDSS	2020				
What You Corrupt Is Not What You Crash: Challenges in Fuzzing Embedded Devices	NDSS	2018				
K-Miner: Uncovering Memory Corruption in Linux	NDSS	2018				
InstaGuard: Instantly Deployable Hot-patches for Vulnerable System Programs on Android	NDSS	2018				
PeriScope: An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary	NDSS	2019				
Towards Automated Dynamic Analysis for Linux-based Embedded Firmware	NDSS	2016				
VTrust: Regaining Trust on Virtual Calls	NDSS	2016				
ReVirt: Enabling Intrusion Analysis through Virtual-Machine Logging and Replay	OSDI	2002	record and replay	virtual machine	instruction	Debugging operating systems with time-traveling virtual machines
Lightweight, High-Resolution Monitoring for Troubleshooting Production Systems	OSDI	2008				
SymDrive: Testing Drivers without Devices	OSDI	2012				
Orca: Differential Bug Localization in Large-Scale Services	OSDI	2018				
REPT: Reverse Debugging of Failures in Deployed Software	OSDI	2018	data flow and control flow	PT, offline binary analysis on memory dump		
Finding Crash-Consistency Bugs with Bounded Black-Box Crash Testing	OSDI	2018				
Sledgehammer: Cluster-Fueled Debugging	OSDI	2018				
D4: Fast Concurrency Debugging with Parallel Differential Analysis	PLDI	2018				
Simple and Precise Static Analysis of Untrusted Linux Kernel Extensions	PLDI	2019				
HOPPITY: LEARNING GRAPH TRANSFORMATIONS TO DETECT AND FIX BUGS IN PROGRAMS	PLDI/ICLR	2020				
Scalable Statistical Bug Isolation	PLDI	2005				
Explaining Bug Provenance with Trace Witnesses	PLDI	2020				
SOBER: Statistical Modelbased Bug Localization	FSE	2005				
Virtuoso: Narrowing the Semantic Gap in Virtual Machine Introspection	S&P	2011				
Space Traveling across VM: Automatically Bridging the Semantic Gap in Virtual Machine Introspection via Online Kernel Data Redirection	S&P	2012				
Cross-Architecture Bug Search in Binary Executables	S&P	2015				
LAVA: Large-scale Automated Vulnerability Addition	S&P	2016				
Precise and Scalable Detection of Double-Fetch Bugs in OS Kernels	S&P	2018				
Understanding the Security of ARM Debugging Features	S&P	2019				
Razzer: Finding Kernel Race Bugs through Fuzzing	S&P	2019				
SAVIOR: Towards Bug-Driven Hybrid Testing	S&P	2020				
xMP: Selective Memory Protection for Kernel and User Space	S&P	2020				
KRACE: Data Race Fuzzing for Kernel File Systems	S&P	2020	a fuzzing method to detect data race (kernel) bug	qemu	instruction	
A Placement Vulnerability Study in Multi-Tenant Public Clouds	Security	2015				
Automatically Detecting Error Handling Bugs Using Error Specifications	Security	2016				
Adaptive Android Kernel Live Patching	Security	2017				
vTZ: Virtualizing ARM TrustZone	Security	2017				
DR. CHECKER: A Soundy Analysis for Linux Kernel Drivers	Security	2017				
BinSim: Trace-based Semantic Binary Diffing via System Call Sliced Segment Equivalence Checking 	Security	2017				
Ninja: Towards Transparent Tracing and Debugging on ARM	Security	2017				
Digtool: A Virtualization-Based Framework for Detecting Kernel Vulnerabilities	Security	2017				
kAFL: Hardware-Assisted Feedback Fuzzing for OS Kernels	Security	2017				
Seeing Through The Same Lens: Introspecting Guest Address Space At Native Speed	Security	2017				
Charm: Facilitating Dynamic Analysis of Device Drivers of Mobile Systems	Security	2018				
HardFails: Insights into Software-Exploitable Hardware Bugs	Security	2019				
Exploiting Unprotected I/O Operations in AMD’s Secure Encrypted Virtualization	Security	2019				
Aurora: Statistical Crash Analysis for Automated Root Cause Explanation	Security	2020				
Muzz: Thread-aware Grey-box Fuzzing for Effective Bug Hunting in Multithreaded Programs	Security	2020				
KOOBE: Towards Facilitating Exploit Generation of Kernel Out-Of-Bounds Write Vulnerabilities	Security	2020				
PHMon: A Programmable Hardware Monitor and Its Security Use Cases	Security	2020				
PartEmu: Enabling Dynamic Analysis of Real-World TrustZone Software Using Emulation	Security	2020				
(Mostly) Exitless VM Protection from Untrusted Hypervisor through Disaggregated Nested Virtualization	Security	2020				
USBFuzz: A Framework for Fuzzing USB Drivers by Device Emulation	Security	2020				
Agamotto: Accelerating Kernel Driver Fuzzing with Lightweight Virtual Machine Checkpoints	Security	2020	a fast method of fuzzing device drivers  	qemu, syzkaller	checkpoint,I/O requests	
An Observational Investigation of Reverse Engineers’ Processes	Security	2020				
Automatic Hot Patch Generation for Android Kernels	Security	2020				
Automatic Techniques to Systematically Discover New Heap Exploitation Primitives	Security	2020				
Cross-checking Semantic Correctness: The Case of Finding File System Bugs	SOSP	2015				
Failure Sketching: A Technique for Automated Root Cause Diagnosis of In-Production Failures	SOSP	2015				
Pivot Tracing: Dynamic Causal Monitoring for Distributed Systems	SOSP	2015				
Canopy: An End-to-End Performance Tracing And Analysis System	SOSP	2017				
Lazy Diagnosis of In-Production Concurrency Bugs	SOSP	2017	a diagnosis method to automate root cause	intel pt, llvm	instructions, control flow	
Efficient Scalable Thread-Safety-Violation Detection	SOSP	2019				
An Analysis of Performance Evolution of Linux’s Core Operations	SOSP	2019				
CrashTuner: Detecting Crash-Recovery Bugs in Cloud Systems via Meta-Info Analysis	SOSP	2019				
The Inflection Point Hypothesis: A Principled Debugging Approach for Locating the Root Cause of a Failure	SOSP	2019				
Finding Semantic Bugs in File Systems with an Extensible Fuzzing Framework	SOSP	2019				
Triage: Diagnosing Production Run Failures at the User’s Site	SOSP	2007				
CrashMonkey & Ace : Finding File System Crash-Consistency Bugs	Vault	2019				
Cooperative Crug Isolation	Vault	2009				
A Dataflow Approach to Event-based Debugging	SOFTWARE—PRACTICE AND EXPERIENCE	1991				
Execution Synthesis: A Technique for Automated Software Debugging	EuroSys	2010				
A Dataow Language for Scriptable Debugging						
Learning from Mistakes A Comprehensive Study on Real World Concurrency Bug Characteristics	ASPLOS	2008				
Failure Diagnosis of Complex Systems						
Differentiated Storage Services	SOSP	2011				
Deconstructing Commodity Storage Clusters	ISCA	2005				
Understanding Issue Correlations: A Case Study of the Hadoop System	SOCC	2015				
‘Real Time’ vs. ‘Real Fast’: How to Choose						
Rete: A Fast Algorithm for the Many PatternIMany Object Pattern Match Problem	AI	1982				
Stardust: Tracking Activity in a Distributed Storage System	SIGMETRICS	2006				
Vertical Profiling: Understanding the Behavior of Object Oriented Applications	OOPSLA	2004				
More with Less – Deriving More Translation Rules with Less Training Data for DBTs Using Parameterization	MICRO	2020		QEMU		
Learning Concise Models from Long Execution Traces	DAC	2020		QEMU		
toki: A Build- and Test-Platform for Prototyping and Evaluating Operating System Concepts in Real-Time Environments	ARXIV			QEMU		
Non-intrusive Virtual Machine Analysis and Reverse Debugging with SWAT	QRS	2020		QEMU		
Cybersecurity Analysis of Distribution Grid Operation with Distributed Energy Resources via Co-Simulation	POWER&ENERGY	2020		QEMU		
QEMU-Based Framework for Non-intrusive Virtual Machine Instrumentation and Introspection	FSE	2017		QEMU		
Program Analysis with a Loop-Function-based Tracing Tool on Virtual Platforms	RACS	2017		QEMU		
File Tracing by Intercepting Disk Requests	FSE	2019		QEMU		
HaRMony: Heterogeneous-Reliability Memory and QoS-Aware Energy Management on Virtualized Servers	ASPLOS	2020		QEMU		
Static/Dynamic Real-Time Legacy Software Migration – A Comparative Analysis	RAPIDO	2020		QEMU		
Qtrace: A Framework for Customizatble Full System Instrumentation	ISPAPP	2015		QEMU		
Branch Bitstream	IC-ICTES	2015		QEMU		
Platform-Independent Reverse Debugging of the Vitual Machines	ISPIT	2016		QEMU		
Configurable Fast Cycle-approximate Timing Estimation for Instruction-level Emulators	CANDAR	2017		QEMU		
PTfuzz: Guided Fuzzing With Processor Trace Feedback	access	2016		QEMU		
A Fault Injection Approach to Evaluate Soft-Error Dependability of System Calls	ISSREW	2018		QEMU		
SPDK vhost-NVMe: Accelerating I/Os in virtual machines on NVMe SSDs via user space vhost target	SC2	2018		QEMU		
Analyzing, Modeling, and Provisioning QoS for NVMe SSDs	UCC	2018		QEMU		
iConSnap: An Incremental Continuous Snapshots System for Virtual Machines	servicecomputing	2019		QEMU		
IoT Malware Dynamic Analysis Profiling System and Family Behavior Analysis	bigdata	2019		QEMU		
Secure Cryptography Infrastructures in the Cloud	Globalecom	2020		QEMU		
NVMe-over-RPMsg: A Virtual Storage Device Model Applied to Heterogeneous Multi-Core SoCs	CCWC	2020		QEMU		
FPU Bit-Width Optimization for Approximate Computing: A Non-Intrusive Approach	DTIS	2020		QEMU		
IFFSET: In-Field Fuzzing of Industrial Control Systems using System Emulation	DATE	2020		QEMU		
Experimental Evaluation of the Defense Capability of ARM-based Systems against Buffer Overflow Attacks in Wireless Networks	ICEIEC	2020		QEMU		
Chaser: An Enhanced Fault Injection Tool for Tracing Soft Errors in MPI Applications	DSN	2020		QEMU		
iScanU: A Portable Scanner for Undocumented Instructions on RISC Processors	DSN 	2020		QEMU		
SDN-based Order-aware Live Migration of Virtual Machines	INFOCOM	2020		QEMU		
A Thread Level SLO-Aware I/O Framework for Embedded Virtualization	PFS	2021		QEMU		
Fast and Correct Load-Link/Store-Conditional Instruction Handling in DBT Systems	Circuit	2020		QEMU		
Evaluation of the Runtime Intrusion Prevention of ARM-Based Systems in Wireless	CCE	2020		QEMU		
mcQEMU: Time-Accurate Simulation of Multi-core platforms using QEMU	DSD	2020		QEMU		
DADI: Block-Level Image Service for Agile and Elastic Application Deployment	ATC	2020		QEMU		
Finding Bugs Using Your Own Code: Detecting Functionally-similar yet Inconsistent Code	Security	2021		QEMU		
Say Goodbye to Virtualization for a Safer Cloud	HotCloud	2018		QEMU		
Virtualization Mechanisms and Tools: A Comprehensive Survey	IJCSE	2020		QEMU		
Learning Concise Models from Long Execution Traces	DAC	2020		QEMU		
Using Linux block integrity in building and testing storage systems	Vault	2020		QEMU		
QEMU, a Fast and Portable Dynamic Translator	ATC	2005		QEMU, TCG		
High Accuracy Attack Provenance via Binary-based Execution Partition	NDSS	2013			unit	
ProTracer: towards practical provenance tracing by alternating between logging and tainting	NDSS	2016			unit	
Trustworthy Whole-System Provenance for the Linux Kernel	Security	2015			syscall	
SPADE: support for provenance auditing in distributed environments	Middleware	2015			syscall	
RecProv: Towards Provenance-Aware User Space Record and Replay	IPAW	2016	see following work		syscall	
Layering in Provenance Systems	ATC	2009			syscall	
Looking inside the black-box: capturing data provenance using dynamic instrumentation	IPAW	2014			instruction	
Decoupling Provenace Capture and Analysis from Execution	TAPP	2015			instruction	
Panorama: capturing system-wide information flow for malware detection and analysis	CCS	2007	malware detection and analysis	qemu	instruction	
An Investigation of the Android Kernel Patch Ecosystem	Security	2021	kernel patch analysis			
Understanding and Detecting Disordered Error Handling with Precise Function Pairing	Security	2021	investigate a class of bugs in error-handling code bugs			
Re-Animator: Versatile High-Fidelity Storage-System Tracing and Replaying	SYSTOR	2020	system call record and replay			
Performance-Optimal Read-Only Transactions	OSDI	2020	Read only transactions (distributed storage system)			
Specification and verification in the field: Applying formal methods to BPF just-in-time compilers in the Linux kernel	ODSI	2020	just in time (JIT) bugs in virtual machine	BPF		
Precisely Characterizing Security Impact in a Flood of Patches via Symbolic Rule Comparison	NDSS	2020	bug identify			
What bugs cause production cloud incidents	HotOS	2019	cloud incidents survey			
Why does cryptographic software fail?A case study and open problems	ApSys	2014	cryptographic vulnerability study			
Linux kernel vulnerabilities: State-of-the-art defenses and open problems	ApSys	2011	cryptographic vulnerability study			
Reinforcement Learning-based Hierarchical Seed Scheduling for Greybox Fuzzing	NDSS	2021	fuzzing seed expeneded by refinforcement learning 	qemu, AFL		
KUBO: Precise and Scalable Detection of User-triggerable Undefined Behavior Bugs in OS Kernel	NDSS	2021	ub bug detection	static analysis,.slicing		
Who’s Debugging the Debuggers? Exposing Debug Information Bugs in Optimized Binaries	ASPLOS	2021	explore the debug info bugs			
PIBE: Practical Kernel Control-Flow Hardening with Profile-Guided Indirect Branch Elimination	ASPLOS	2021				
BPF for Storage: An Exokernel-Inspired Approach	HOTOS	2021	use ebpf for storage to reduce software stack latencies	ebpf	(just idea)	
Systems Research is Running out of Time	HOTOS	2021				
CrystalPerf: Learning to Characterize the Performance of Dataflow Computation through Code Analysis	ATC	2021				
MLEE: Effective Detection of Memory Leaks on Early-Exit Paths in OS Kernels	ATC	2021				
Argus: Debugging Performance Issues in Modern Desktop Applications with Annotated Causal Tracing	ATC	2021	revise kernel to trace application and debug performance issue			
Lossless Instruction-to-Object Memory Tracing in the Linux Kernel	SYSTOR	2021	revise kernel to capture memory operations	memory flame graph		
difuzzrtl: differential fuzz testing to find cpu bugs	S&P	2021				
Static Detection of Unsafe DMA Accesses in Device Drivers	Security	2021	find out the acceess variable to do the bug detection	llvm		
SelectiveTaint: Efficient Data Flow Tracking With Static Binary Rewriting	Security	2021	static instrumentation replace dynamic instrumentation			
Finding Bugs Using Your Own Code: Detecting Functionally-similar yet Inconsistent Code	Security	2021				
ExpRace: Exploiting Kernel Races through Raising Interrupts	Security	2021				
Undo Workarounds for Kernel Bugs	Security	2021				
SyzVegas: Beating Kernel Fuzzing Odds with Reinforcement Learning	Security	2021				
3MileBeach: A Tracer with Teeth	SOCC	2021	tracer with fault injection for microservice-based architectures			
tprof: Performance profiling via structural aggregation and automated analysis of distributed systems traces	SOCC	2021	debug performance issue through tracing aligning by time info			
Characterizing Microservice Dependency and Performance: Alibaba Trace Analysis	SOCC	2021	DFS tracing analysis through dependency analysis			
OptDebug: Fault-Inducing Operation Isolation for Dataflow Applications	SOCC	2021	identifies fault-inducing operations in a dataflow application through provenance			
Bonsai Merkle Forests: Efficiently Achieving Crash Consistency in Secure Persistent Memory	MICRO	2021				
ESCALATE: Boosting the Efficiency of Sparse CNN Accelerator with Kernel Decomposition	MICRO	2021				
Validation of Side-Channel Models via Observation Refinement	MICRO	2021		try to see how to analyze???		
MithriLog: Near-Storage Accelerator for High-Performance Log Analytics	MICRO	2021				
NDS: N-Dimensional Storage	MICRO	2021		new concept???		
HEALER: Relation Learning Guided Kernel Fuzzing	SOSP	2021	ML to change efficiency of fuzzing	HEALER learns the influence relations between system calls by dynamically analyzing minimized test cases		
Snowboard: Finding Kernel Concurrency Bugs through Systematic Inter-thread Communication Analysis	SOSP	2021	kernel concurrency bug detection 	potential memory communication (PMC)		
Witcher: Systematic Crash Consistency Testing for Non-Volatile Memory Key-Value Stores	SOSP	2021	crash consistency testing			
RUDRA: Finding Memory Safety Bugs in Rust at the Ecosystem Scale	SOSP	2021	validate the ownership of memory at compile time			
Understanding and Detecting Software Upgrade Failures in Distributed Systems	SOSP	2021	finally testing and find out bugs	study and testing		
Trace-Based Control-Flow Analysis	PLDI	2021	theory			
Chianina: An Evolving Graph System for Flow- and Context-Sensitive Analyses of Million Lines of C Code	PLDI	2021	a novel evolving graph system for scalable context- and flow-sensitive analysis for C code	static analysis		
Execution Reconstruction: Harnessing Failure Reoccurrences for Failure Reproduction	PLDI	2021				
Large-scale cluster management at Google with Borg	EuroSys	2015	how berg monitor works, it records all job submissions and task events, as well as detailed per-task resource usage information in Infrastore			
Pinpointing Crash-Consistency Bugs in the HPC I/O Stack: A Cross-Layer Approach	SC	2021	present an effective testing framework for identifying crash-consistency bugs in the HPC I/O stack			
Automated Bug Hunting With Data-Driven Symbolic Root Cause Analysis	CCS	2021				
Zero Knowledge Static Program Analysis	CCS	2021				
HyperFuzzer: An Efficient Hybrid Fuzzer for Virtual CPUs	CCS	2021				
ARCUS: Symbolic Root Cause Analysis of Exploits in Production Systems	Security	2021	record control flow by intel pt and memory snapshots by kernel module, then symbolic analyze the path and find out the buggy part. During the instruciton recovery,it uses backward taint analysis			
FUZE: Towards Facilitating Exploit Generation for Kernel Use-After-Free Vulnerabilities	Security	2018	based on angr and qemu and Syzkaller, imporve Exploitability (SMAP, SMEP)			
SymQEMU: Compilation-based Symbolic Execution for binaries	NDSS	2021				
What You See is Not What the Network Infers: Detecting Adversarial Examples Based on Semantic Contradiction	NDSS	2022				
An In-depth Analysis of Duplicated Linux Kernel Bug Reports	NDSS	2022				
Context-Sensitive and Directional Concurrency Fuzzing for Data-Race Detection	NDSS	2022				
Semantic-Informed Driver Fuzzing Without Both the Hardware Devices and the Emulators	NDSS	2022				
Progressive Scrutiny: Incremental Detection of UBI bugs in the Linux Kernel	NDSS	2022				
ClusterRR: A Record and Replay Framework for Virtual Machine Cluster	VEE	2022				
Container-aware I/O Stack: Bridging the Gap between Container Storage Drivers and Solid State Devices	VEE	2022				
PinSQL: Pinpoint Root Cause SQLs to Resolve Performance Issues in Cloud Databases	ICDE	2022	collect data and leverage machine learniong to detect bugs, then identify bug patterns based on logs and requests			
NVAlloc: Rethinking Heap Metadata Management in Persistent Memory Allocators	ASPLOS	2022				
Enzian: An Open, General, CPU/FPGA Platform for Systems Software Research	ASPLOS	2022				
GenStore: A High-Performance In-Storage Processing System for Genome Sequence Analysis	ASPLOS	2022				
Creating concise and efficient dynamic analyses with ALDA	ASPLOS	2022				
Finding Missed Optimizations through the Lens of Dead Code Elimination	ASPLOS	2022				
A Tree Clock Data Structure for Causal Orderings in Concurrent Executions	ASPLOS	2022				
RSSD: Defend against Ransomware with Hardware-Isolated Network-Storage Codesign and Post-Attack Analysis	ASPLOS	2022				
Yashme: Detecting Persistency Races	ASPLOS	2022				
Examiner: Automatically Locating Inconsistent Instructions between Real Devices and CPU Emulators for ARM	ASPLOS	2022				
Path-Sensitive and Alias-Aware Typestate Analysis for Detecting OS Bugs	ASPLOS	2022				
Efficiently Detecting Concurrency Bugs in Persistent Memory Programs	ASPLOS	2022				
Who goes first? detecting go concurrency bugs via message reordering	ASPLOS	2022				
Debugging in the Brave New World of Reconfigurable Hardware	ASPLOS	2022				
Characterizing the Performance of Intel Optane Persistent Memory	EuroSys	2022				
Hardening Binaries against More Memory Errors	EuroSys	2022				
Improving Automated Crash Reproduction	ICSE	2022				
Automatically Identifying Shared Root Causes of Test Breakages in SAP HANA	ICSE	2022				
Automatic Detection of Performance Bugs in Database Systems using Equivalent Queries	ICSE	2022				
On Debugging the Performance of Configurable Software Systems: Developer Needs and Tailored Tool Support	ICSE	2022				
How to Debug Inclusivity Bugs? A Debugging Process with Information Architecture	ICSE	2022				
Common Data Guided Crash Injection for Cloud Systems	ICSE	2022				
Mining Root Cause Knowledge from Cloud Service Incident Investigations for AIOps	ICSE	2022				
Pluto: Exposing Vulnerabilities in Inter-Contract Scenarios	ICSE	2022				
JuCify: A Step Towards Android Code Unification for Enhanced Static Analysis	ICSE	2022				
PerfSig: Extracting Performance Bug Signatures via Multi-modality Causal Analysis	ICSE	2022				
Detecting False Alarms from Automatic Static Analysis Tools: How Far are We?	ICSE	2022				
GIFdroid: An Automated Light-weight Tool for Replaying Visual Bug Reports	ICSE	2022				
GREBE: Unveiling Exploitation Potential for Linux Kernel Bugs	S&P	2022				
SAILFISH: Vetting Smart Contract State-Inconsistency Bugs in Seconds	S&P	2022				
Silent Data Corruption	ISCA	2022	https://www.youtube.com/watch?v=j1IvGZZSm3k			
PS-ORAM: efficient crash consistency support for oblivious RAM on NVM	ISCA	2022				
FFCCD: Fence-Free Crash-Consistent Concurrent Defragmentation for Persistent Memory	ISCA	2022				
Finding real bugs in big programs with incorrectness logic	PLDI	2022				
Debugging the OmniTable Way	OSDI	2022	record and replay based debugging for memeory related application			
XRP: In-Kernel Storage Functions with eBPF	OSDI	2022				
Upgradvisor: Early Adopting Dependency Updates Using Hybrid Program Analysis and Hardware Tracing	OSDI	2022				
Hubble: Performance Debugging with In-Production, Just-In-Time Method Tracing on Android	OSDI	2022				
Direct Access, High-Performance Memory Disaggregation with DirectCXL	ATC	2022				
KSG: Augmenting Kernel Fuzzing with System Call Specification Generation	ATC	2022				
DLOS: Effective Static Detection of Deadlocks in OS Kernels	ATC	2022				
Vinter: Automatic Non-Volatile Memory Crash Consistency Testing for Full Systems	ATC	2022	leverage PANDA to detect persisent memory file system by fault injection			
NVMe SSD Failures in the Field: the Fail-Stop and the Fail-Slow	ATC	2022				
Hello Bytes, Bye Blocks: PCIe Storage Meets Compute Express Link for Memory Expansion (CXL-SSD)	Hotstorage	2022				
Cache-Coherent Accelerators for Persistent Memory Crash Consistency	Hotstorage	2022				
![image](https://user-images.githubusercontent.com/37310481/200679424-67bc7a28-43dd-45e1-bd58-f4e5cea128d8.png)
