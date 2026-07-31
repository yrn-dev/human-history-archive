# The Invisible Architecture: The Evolution of BGP and Global Routing

While previous installments in this series have focused on the visible milestones of the internet—the birth of ARPANET, the rise of the World Wide Web, and the proliferation of broadband—the actual mechanism that allows these networks to communicate remains largely unseen. To understand global connectivity, one must examine the "glue" of the internet: the Border Gateway Protocol (BGP).

If the Internet is a network of networks, BGP is the navigational system that determines the most efficient path for data to travel across these disparate autonomous systems (AS). Without this protocol, the internet would be a collection of isolated digital islands rather than a cohesive global entity.

## The Transition from RIP to BGP

In the early days of networking, the Routing Information Protocol (RIP) was sufficient for small, homogenous environments. However, as the internet expanded in the late 1980s, RIP’s limitations became apparent; it could not handle the scale or the complex policy requirements of a global network. 

In 1989, engineers LouDescribe and Kirk Lougheed developed the first version of BGP. Unlike its predecessors, BGP was designed not just for speed, but for *policy*. It allowed network administrators to decide which paths data should take based on commercial agreements, security concerns, and political boundaries, rather than simply the shortest physical distance.

## The Fragility of Trust

A critical historical point regarding BGP is its inherent reliance on trust. The protocol was designed in an era when the internet consisted of a small group of trusted academic and government institutions. Consequently, BGP lacks built-in verification; it assumes that when a network claims to "own" a certain range of IP addresses, it is telling the truth.

This architectural legacy has led to "BGP hijacking," where a network erroneously (or maliciously) announces routes it does not control, effectively diverting global traffic. Historians and computer scientists continue to debate the best path forward: whether to implement a centralized authority for route validation or to rely on decentralized frameworks like RPKI (Resource Public Key Infrastructure).

## The Geopolitics of Routing

The evolution of BGP also mirrors the geopolitical shifts of the modern era. As the internet became the backbone of global commerce, the physical and logical paths of BGP routes became strategic assets. The realization that data can be routed around entire nations—or that a single misconfiguration in a regional ISP can "black hole" a global service—has transformed routing from a technical necessity into a matter of national security.

***

### Key Facts
* **BGP Definition:** The standardized exterior gateway protocol designed to exchange routing and reachability information among autonomous systems (AS) on the internet.
* **Introduction:** First specified in 1989 (RFC 1105) to replace the less scalable RIP.
* **Autonomous Systems:** The internet is divided into ASes (large networks managed by a single entity, like an ISP or a university), which BGP connects.
* **Path Vector Protocol:** BGP is classified as a path-vector protocol, meaning it tracks the sequence of ASes a packet must traverse.
* **The Trust Model:** Original BGP specifications did not include cryptographic authentication, leaving the system vulnerable to route leaks.

### Did You Know?
* **The "Fat Finger" Effect:** Many of the largest internet outages in history were not caused by hackers, but by simple BGP configuration errors (typos) by network engineers.
* **Non-Shortest Paths:** Because BGP is policy-based, your data often takes a longer physical route to save the provider money or comply with a legal agreement.
* **The BGP Table:** The "Global Routing Table" (the list of all reachable prefixes) has grown from a few thousand entries in the late 80s to over 900,000 today.