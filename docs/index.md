## About Me

I'm an Associate Research Scholar at Princeton University, working at the intersection of hardware-accelerated networking, programming languages, and security. Some of the people I work closely with here at Princeton are Jennifer Rexford, David Walker, Pamela Zave, and Devon Loehr. I got my PhD at the University of Pennsylvania, where I was advised by Jonathan M. Smith and also worked closely with Andre DeHon, Boon Tau Loo, Vincent Liu, Eric Keller, and Adam Aviv. Before that, I completed an MSE in computer science at the University of Pennsylvania and a BS in mathematics at Villanova University. 

My main project right now is Lucid, a high-level language for programming configurable pipeline packet processors (e.g., the Intel Tofino). Lucid is about making the experience of programming these exotic architectures feel more like software engineering -- for example, it takes around 10X fewer lines of code to implement many data structures in Lucid vs. P4. Lucid has simple and composeable primitives, a type system that prevents you from combining those primitives in ways that are fundamentally incompatible with the underlying hardware, an interpreter for testing your algorithms, and an optimizing compiler that encodes many of the tricks that I've learned over the years for writing efficient packet processor code. Its an ongoing project, check it out at the [Sigcomm paper](https://dl.acm.org/doi/10.1145/3452296.3472903) and [Github page](https://github.com/PrincetonUniversity/lucid).

More broadly, my research interests are in networking, security, and distributed systems. My dissertation was on balancing performance and flexibility in hybrid telemetry systems. Prior to that, I did research on accelerating and modeling network security systems and, as an undergraduate, quantitative finance. 

I enjoy interdisciplinary research and often draw from areas including reconfigurable computing, machine learning, and programming languages. 		

## Publications

**Lucid: A Language for Control in the Data Plane.** John Sonchack, Devon Loehr, Jennifer Rexford, and David Walker. Sigcomm 2021.

**Flightplan: Dataplane Disaggregation and Placement for P4 Programs.** Nik Sultana, John Sonchack, Hans Giesen, Isaac Pedisich, Zhaoyang Han, Nishanth Shyamkumar, Shivani Burad, André DeHon, and Boon Thau Loo. NSDI 2021.

**Mantis: Reactive Programmable Switches.** Liangcheng Yu, John Sonchack, Vincent Liu. Sigcomm 2020.

**Balancing Performance and Flexibility in Hybrid Network Telemetry Systems.** John Sonchack. Dissertation, University of Pennsylvania 2020.

**tpprof: A Network Traffic Pattern Profiler.** Nofel Yaseen, John Sonchack, Vincent Liu. NSDI 2020.

**Ignis: scaling distribution-oblivious systems with light-touch distribution.** Nikos Vasilakis, Ben Karel, Yash Palkhiwala, John Sonchack, Andre DeHon, and Jonathan M Smith. PLDI 2019.

**TMC: Pay-as-you-Go Distributed Communication.** Henri Maxime Demoulin, Nikos Vasilakis, John Sonchack, Isaac Pedisich, Vincent Liu, Boon Thau Loo, Linh Thi Xuan Phan, Jonathan M. Smith, and Irene Zhang. AP-NET 2019.

**Synchronized Network Snapshots.** Nofel Yaseen, John Sonchack, Vincent Liu. Sigcomm 2018.

**In-network Computing to The Rescue of Faulty Links.** Hans Geisen, Lei Shi, John Sonchack, Anirudh Chelluri, Nishanth Prabhu, Nik Sultana, Latha Kant, Anthony J. McAuley, Alexander Poylisher, Andre DeHon, Boon Thau Loo. NetCompute 2018.

**Scaling Hardware Accelerated Network Monitoring to Concurrent and Dynamic Queries With \*Flow.** John Sonchack, Oliver Michel, Adam J. Aviv, Eric Keller, Jonathan M. Smith. ATC 2018.

**Packet-Level Analytics in Software without Compromises.** Oliver Michel, John Sonchack, Adam J. Aviv, Eric Keller, Jonathan M. Smith. Hotcloud 2018.

**TurboFlow: Information Rich Flow Record Generation on Commodity Switches.** John Sonchack, Adam J. Aviv, Eric Keller, Jonathan M. Smith. EuroSys 2018.

**Predictable Packet Processing with PathMiner.** John Sonchack and Jonathan M. Smith. BAR 2018.

**Enabling Practical SDN Security Applications with OFX (The OpenFlow eXtension Framework).** John Sonchack, Adam J. Aviv, Eric Keller, and Jonathan M. Smith. Proceedings of the 2016 Network and Distributed System Security Symposium (NDSS).

**Timing Based Reconniasance and Defense in Software-defined Networks.** John Sonchack, Anurag Dubey, Adam J. Aviv, Eric Keller, and Jonathan M. Smith. Proceedings of the 32nd Annual Computer Security Applications Conference (ACSAC).

**Exploring Large Scale Security System Reproducibility with the LESS Simulator.** John Sonchack and Adam J. Aviv. Journal of Computer Security (JCS).
    
**Timing SDN Control Planes to Infer Network Configurations.** John Sonchack, Adam J. Aviv, and Eric Keller. Proceedings of the ACM International Workshop on Security in Software Defined Networks & Network Function Virtualization (SDN-NFV Sec).

**OFX: Enabling OpenFlow Extensions for Switch-Level Security Applications.** John Sonchack, Adam J. Aviv, Eric Keller, and Jonathan M. Smith. Proceedings of the 22nd ACM SIGSAC Conference on Computer and Communications Security (CCS).

**Cross-domain Collaboration for Improved IDS Rule Set Selection.** John Sonchack and Adam J. Aviv. Journal of Information Security and Applications 24 (JISA).

**LESS Is More: Host-Agent Based Simulator for Large-Scale Evaluation of Security Systems.** John Sonchack and Adam J. Aviv. Proceedings of ESORICS 2014.

**Bridging the Data Gap: Data Related Challenges in Evaluating Large Scale Collaborative Security Systems**. John Sonchack, Adam J. Aviv, and Johnathan M. Smith. In the proceedings of the 6th Workshop on Cyber Security Evaluation and Testing (CSET).

**Signature Correlations in Multiple Honeypot Defense System.** John Sonchack and Johnathan M. Smith. Future Internet Workshop.

<!-- 
    
    

    
**Packet-Level Analytics in Software without Compromises.** 
Oliver Michel, John Sonchack, Adam J. Aviv, Eric Keller, Jonathan M. 
Smith. Hotcloud 2018.
    

    
**TurboFlow: Information Rich Flow Record Generation on Commodity 
Switches.** John Sonchack, Adam J. Aviv, Eric Keller, Jonathan M. 
Smith. EuroSys 2018.
    

    
**Predictable Packet Processing with PathMiner.** John Sonchack 
and Jonathan M. Smith. BAR 2018.
    

    <h4> 2016 </h4>
    
**Enabling Practical SDN Security Applications with OFX (The 
OpenFlow 
    eXtension Framework).** John Sonchack, Adam J. Aviv, Eric Keller, 
and Jonathan M. Smith. Proceedings of the 
    2016 Network and Distributed System Security Symposium (NDSS).
    

    
**Timing Based Reconniasance and Defense in Software-defined 
Networks.** 
    John Sonchack, Anurag Dubey, Adam J. Aviv, Eric Keller, and Jonathan 
M. Smith. Proceedings of the 
    32nd Annual Computer Security Applications Conference (ACSAC).
    

    
    **Exploring Large Scale Security System Reproducibility with the 
LESS Simulator.** John Sonchack and Adam J. Aviv. Journal of Computer 
Security (JCS).
    

    
    **Timing SDN Control Planes to Infer Network Configurations.** 
John Sonchack, Adam J. Aviv, and Eric Keller. Proceedings of the ACM 
International Workshop on Security in Software Defined Networks & 
Network Function Virtualization (SDN-NFV Sec).
    

    <h4> 2015 </h4>
    
    **<i>(short paper)</i> **OFX: Enabling OpenFlow Extensions for 
Switch-Level Security 
    Applications.** John Sonchack, Adam J. Aviv, Eric Keller, 
    and Jonathan M. Smith. Proceedings of the 22nd ACM SIGSAC Conference 
on Computer and Communications Security (CCS).
    
    
    **Cross-domain Collaboration for Improved IDS Rule Set 
Selection.** John Sonchack and Adam J. Aviv. Journal of Information 
Security and Applications 24 (JISA).
    


    <h4> 2014 </h4>
    
**LESS Is More: Host-Agent Based Simulator for Large-Scale 
Evaluation 
    of Security Systems.** John Sonchack and Adam J. Aviv. 
Proceedings of ESORICS 2014.             
    
                <h4>2013</h4>
                
            **Bridging the Data Gap: Data Related Challenges in 
    Evaluating Large Scale Collaborative Security Systems**. John 
    Sonchack, Adam J. Aviv, and Johnathan M. Smith. In the proceedings 
of 
    the 6th Workshop on Cyber Security Evaluation and Testing (CSET).
                
                
                <h4>2011</h4>            
                 
                **Signature Correlations in Multiple Honeypot Defense 
System.**            
                John Sonchack and Johnathan M. Smith. Future Internet 
Workshop.
                
 -->
