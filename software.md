# Software

[Home](README.md) | [Participants](participants.md) | [Papers](papers.md) | [Software](software.md)

------

All relevant software use in and developed by project participants
will be listed here.

The initial list of software follows:

- NFLambda is an NFV platform based on DPDK and written in C. Users can design network functions as a composition of micro-services. It has two components: Runtime as the execution environment of network functions with high-performance packet processing on COTS multi-core systems and Director for service provisioning and orchestration. 
  - It contains the following features:
    - NFlow and MVT abstraction for the stateful network functions for efficient state management.
    - Supports for granular decomposition of network functions into data and control components for fine-grained resource allocation.
  - Several examples have been developed, including:
    - A 5G UPF that is able to be configured through PFCP messages from the SMF and process the packets based on PDR (Packet Detection Rule), FAR (Forward Action Rule), BAR (Buffering Action Rule), QER (QoS Enforcement Rules) between the gNB and data network.
    - A load balancer mapping packets to different backend servers according to various policies such as round-robin, Maglev.
    - An IDS matching packets payload based on regular expression patterns and executing different actions such as dropping and forwarding as a result.
    - An ICMP echo server that can reply to ICMP Echo Request.
    - A TCP server that can establish TCP sessions with the clients. 

- [ableC](https://melt.cs.umn.edu/ableC/) is an extensible
  specification of C (C11 standard) using
  [Silver](https://melt.cs.umn.edu/silver/). Users may direct the
  supporting tools to construct new extended versions of C from a set
  of independently designed language extensions. The composition is
  automatic and guaranteed to succeed. Several extensions have been
  developed; these include
  - Algebraic data types, with pattern matching
  - SQLite, with type-checked queries
  - Cilk, for task-based parallel programming
  - Regular expressions, with matching
  - An extension that combines these two to allow regular expressions to be used as patterns when matching on strings as part of an algebraic data type
  - Matrix features from MATLAB and a matlab function construct that generates the boilerplate FFI types and code for calling such functions from MATLAB
  - Term rewriting, inspired by the TOM system and Kiama
  - Closures / lambda-expressions
  - A partial implementation of HALIDE, a DSL for high performance matrix processing
 
  [ableC GitHub repository](https://github.com/melt-umn/ableC)
