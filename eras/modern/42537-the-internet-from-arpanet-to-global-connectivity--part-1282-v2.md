# The Invisible Architecture: The Evolution of BGP and Global Routing

While previous installments in this series have focused on the visible layers of the internet—the World Wide Web, the browser wars, and the rise of social media—the stability of the global network relies on a far more opaque mechanism. To understand how a packet of data travels from a server in Tokyo to a laptop in London, one must examine the history of the Border Gateway Protocol (BGP), the "postal service" of the internet.

In the early days of ARPANET, routing was relatively simple because the network was centrally managed. However, as the internet evolved into a "network of networks," a decentralized system was required to manage how different Autonomous Systems (AS)—large networks managed by ISPs, universities, or corporations—communicated their reachability to one another.

## From EGP to the Border Gateway Protocol

In the 1980s, the Exterior Gateway Protocol (EGP) served as the primary method for routing between networks. However, EGP was designed for a hierarchical structure where a central "core" network existed. As the internet shifted toward a more mesh-like, distributed architecture, EGP became inadequate. It could not handle the complexity of multiple paths or the dynamic nature of a rapidly expanding global web.

The solution arrived in 1989 with the introduction of BGP (specifically BGP-1), developed by Kirk Lougheed and Y.C. Rekhter. Unlike its predecessor, BGP was a "path-vector" protocol. Instead of simply knowing if a destination was reachable, BGP allowed networks to exchange routing and reachability information, enabling the internet to automatically reroute traffic if a specific link failed.

## The Trust Paradox and Route Hijacking

The historical development of BGP reveals a fundamental tension in the internet's design: the trade-off between efficiency and security. BGP was built on a foundation of implicit trust. When an Autonomous System announces that it owns a certain range of IP addresses, other networks generally believe it.

This "trust-based" architecture has led to a recurring historical phenomenon known as "BGP hijacking." This occurs when a network erroneously (or maliciously) claims to be the shortest path for traffic it does not own. Historians of technology often debate whether this vulnerability is a failure of original design or an inevitable byproduct of the internet's need for rapid, frictionless growth. The subsequent introduction of RPKI (Resource Public Key Infrastructure) represents the modern effort to retroactively add a layer of verification to a system that was never designed for a hostile environment.

## Key Facts
* **Autonomous Systems (AS):** The large networks (like Comcast or AT&T) that make up the internet's backbone.
* **Path-Vector Routing:** The method BGP uses to track the sequence of AS numbers a packet must traverse.
* **BGP-4:** The current widely used version, introduced in 1994 to support Classless Inter-Domain Routing (CIDR).
* **Convergence:** The process by which all routers on the internet agree on the best paths for data to travel.

## Did You Know?
* **The "Fat Finger" Effect:** Many of the largest global internet outages in history were caused by simple typographical errors in BGP configurations, not cyberattacks.
* **The Default-Free Zone:** There is a small group of "Tier 1" ISPs that do not pay anyone for transit because they are so large they can reach every other network on the internet.
* **Implicit Trust:** For decades, BGP operated without any built-in mechanism to verify that a network actually owned the IP addresses it was claiming.