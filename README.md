# ComScaN

[Home](README.md) | [Participants](participants.md) | [Papers](papers.md) | [Software](software.md)

## Composition and Scaling of Network Services

Network function virtualization (NFV) promises to simplify deployment
of network services, and enables them to dynamically evolve. Operators
can create, update, remove or scale out/in (virtualized) network
functions (NFs) running on commodity servers on demand, and form a
service function chain (SFC) comprised of a sequence of network
functions to meet certain service and policy requirements. Despite the
promise, realizing the scalability, availability, and performance
advantages of NFV has proved difficult. While building such systems to
be correct is challenging, having rigorous, verified reasons for
believing that the system will meet quantitative performance
objectives is not yet feasible. The work proposed here will
investigate the use of extensible domain-specific languages for
specifying different aspects of network functionality and formal
verification and synthesis techniques to ensure the correctness,
scalability, and performance of the developed systems to answer these
challenges. 

We advance ComScaN as an ambitious, innovative new paradigm for
re-architecting NFV based on formal foundations and principled
approaches to support future networks and emerging services. To
fundamentally tackle the many looming challenges in NFV, we take a
greenfield approach by developing a new NFV platform that enables
quantitative performance reasoning of NFV scaling. ComScaN is designed
from the ground up, with domain specific language support, automatic
verification and dynamic synthesis tools to make programming,
operating and managing an NFV system as easy and error-free as
possible, while fully taking advantage of multi-core server capacities
and special hardware capabilities such as SmartNIcs. At the base of
ComScaN is a flexible and extensible domain-specific language
framework using a novel actor model for programming network functions
and a library of combinators for composing them as service function
graphs (SFGs). This provides network operators and other personnel
with the capabilities to expressively specify their intents to meet
diverse service requirements, flexibly modify them and dynamically
adapt them to meet changing demands and evolving system
infrastructures. On top of this we will develop abstractions and
semantic models to support specification, verification and synthesis
techniques for formally assured correctness, scalability and
quantitative performance guarantees on SFCs. We will develop new
quantitative performance modeling and reasoning techniques to address
performance, scaling, and other concerns by extending prior work in
assume- guarantee architectural verification and reactive control
synthesis in new directions.

### Participants

Principle Investigators
- Sanjai Rayadurgam
- Eric Van Wyk
- Zhi-Li Zhang

Graduate Students
- Luke Bessant
- Dawn Michaelson
- Feng Tian
- Ziyan Wu

### Acknowledgments

We thank the National Science Foundation for supporting this work
under award [#2123987](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2123987&HistoricalAwards=false).

![NSF](nsf-logo.gif)

