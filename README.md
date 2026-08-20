# Robert A. Getschmann

Software Engineer / Team Lead

<rob@getschmann.net> • +1.603.930.0918 • [github.com/robgetschmann](https://github.com/robgetschmann) • [linkedin.com/in/robgetschmann](https://www.linkedin.com/in/robgetschmann/)

## SYNOPSIS

I am a software engineer and technical lead with over twenty-five years of experience building carrier grade telecommunications and networking systems, spanning Mobile Core and Radio Access Network infrastructure, and network security products.  I have architected, implemented, and delivered highly scalable, standards compliant systems for tier 1 carriers and enterprise customers.  I am comfortable across the full depth of the stack, from hardware and device drivers through protocol stacks and network services.

## EXPERIENCE

### Dräger Medical Systems

**Senior Staff Software Engineer / Lead** — Andover, MA (May 2020-Present)

- I am the technical lead for Dräger’s *Infinity Central Real Time Monitoring Station*, a C++ Red Hat Linux platform on Intel COTS hardware deployed world-wide. My geographically dispersed team owns design, implementation, requirements, cyber hardening, and field issue support, and roughly half of my time remains hands on in implementation.
- Previously I was the platform team lead and scrum master for a next generation ARM/VxWorks bedside patient monitor, responsible for team coordination, requirements, and scheduling as well as the design of the monitor’s system state machine.

### Parallel Wireless

**Principal Software Engineer** — Nashua, NH (November 2013-May 2020)

- Over a seven year tenure I served as a technical lead across multiple groups in a fast paced startup building a unified end-to-end 2G, 3G, 4G, and 5G Open RAN solution for cellular networks. My largest effort was the architecture and implementation of a 3GPP compliant strongSwan based IKEv2/IPsec infrastructure which secured the Radio Access Network mesh and tunneled to the core on behalf of the virtualized eNodeB, along with the X.509v3 certificate based PKI used by peers throughout the Self Organizing Network. I was directly involved with deployment and debugging at customer sites.
- As Software Defined Networking reshaped the product line I architected the migration of the Small-Cell Yocto Linux Radio Access Network platform from dedicated ARM hardware onto LXC containers running on COTS Intel, and implemented the tooling used to stage and deploy the containers providing the different LTE functional splits. I also oversaw the team’s build server infrastructure and managed the release engineers through a redesign of the GNU tool based build system.

### Starent Networks (Cisco Systems)

**Principal Software Engineer** — Tewksbury, MA (July 2006-October 2013)

- I was the lead software engineer for the embedded security platforms of the *ASR5000* family of Mobile Internet infrastructure systems, deployed by Tier 1 carriers across 3G CDMA, UMTS, and 4G LTE networks. My principal contribution was a highly scalable RFC 4300 series multi-card IKEv2/IPsec stack supporting gateway to gateway tunneling as well as the Femto, PDG, PDIF, TTG, and LTE mobile subscriber models, scaling to two million simultaneous calls, alongside which I coordinated the tasks of the other IKEv2/IPsec and datapath engineers.
- I was the team lead for the datapath of a P-CSCF SRTP based secure voice over IP tunneling platform, coordinating network processor, datapath, and Linux driver development across three time zones. Closer to the hardware, I implemented the embedded Linux Cavium Nitrox and Intel Cavecreek and Coleto Creek device drivers backing the IPsec and SRTP call models, and my reference board work spanned the Intel Crystal Forest and Sandy Bridge through Haswell generations, including board bring-up and BIOS customization for the *ASR5500* data processing cards.

### Message Secure Corporation

**Senior Software Engineer** — Lowell, MA (February 2002-July 2006)

- I was the lead software architect and developer for a family of UN*X appliance and server based security products supporting more than five hundred installations. My primary product was a Microsoft compatible PPTP/PPP Virtual Private Network server for Solaris, for which I implemented in C the STREAMS kernel modules handling packet compression and MPPE RC4 encryption, a GDBM back end recording session accounting, and tooling for account maintenance and per-account packet filtering policy.
- I was also the lead architect for the company’s Network Intrusion Detection System, porting an open-source NIDS to Solaris, carrying alert traffic over a 3DES encrypted tunnel for central management, and authoring the per-customer and Zero Day signature sets rolled out to over two hundred customers.

### NaviPath

**Senior Software Engineer** — Andover, MA (May 2000-December 2001)

- I architected, implemented, and rolled out a fleet of approximately seventy FreeBSD Intel architecture servers deployed across points of presence to support enterprise network services and network statistic collection and analysis, including Apache, BIND, MRTG, RRDTool, and UCD-SNMP. I architected the platform security policy covering IPFW packet filtering, IP bandwidth limiting, and Tripwire file consistency checking, and designed a disk-less PXEBoot and GNU CFEngine framework which automated server installation, account provisioning, and package maintenance across the fleet.

## EDUCATION

### Master of Science

**Computer Science** — Rochester Institute of Technology

- Thesis: Enumeration of Small Triangle Free Ramsey Graphs (under Stanisław Radziszowski)
- Concentrations: Computational Theory, Combinatorics, Neural Networks, and Object-Oriented Systems

### Bachelor of Science

**Computer Science** — Rochester Institute of Technology

- Concentration: System Software (Compilers, Operating Systems, Computer Architectures)

## PATENTS

- [US20180205722A1: Multi-Stage Secure Network Element Certificate Provisioning in a Distributed Mobile Access Network](https://patents.google.com/patent/US20180205722A1/)
- [US20200162892A1: Secure Software Update in a Wireless Mesh Radio Network Using Peer-to-Peer File Sharing](https://patents.google.com/patent/US20200162892A1/)

## PRESENTATIONS

- [What’s New with FreeBSD (Boston Linux User’s Group)](https://blu.org/)
- [Recent Developments in FreeBSD (Boston Linux User’s Group)](https://blu.org/)
- [An Overview of FreeBSD, NetBSD, and OpenBSD (Boston Linux User’s Group)](https://blu.org/meetings/1999/10/)

## TECHNICAL SKILLS

- Programming Languages: C, C++, Go, Perl, Smalltalk-80, Shell Scripting, Flex/Bison, Various Assemblers
- Platforms: Ubuntu, Red Hat Enterprise Linux, Yocto, FreeBSD, NetBSD, OpenBSD, Solaris, VxWorks; Intel COTS and ARM Architectures
- Protocols: Ethernet, TCP/IP, IPsec/IKEv2, X.509v3 PKI, SRTP, PPTP/PPP, OSPF, SNMP, NetCONF/YANG
- Domains: Open RAN, 2G/3G/4G/5G Mobile Infrastructure, Self Organizing Networks, Embedded Real-Time Systems, Network Security Appliances, Medical Devices
- Suites: Atlassian (Confluence, Jira), Bitbucket, GitHub, GitLab
- Tools: CLang (LLVM), Containers (Docker/BSD Jails/LXC), GNU Tool Chain, Autotools, BitKeeper, CMake, GIT, LaTeX, SVN, Doxygen, OpenSSL, strongSwan, CFEngine, TMux, UN*X Command Line Tool Suite, Valgrind

