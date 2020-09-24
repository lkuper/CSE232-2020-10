---
title: "Readings"
layout: splash
---

<style type="text/css">
span.discussion { color: lemonchiffon; font-weight: bold }
span.lecture { color: lightblue; font-weight: bold }
</style>

## Schedule

This schedule is tentative, and it is neither [_sound_](https://en.wikipedia.org/wiki/Soundness) (that is, if a particular reading or topic is listed here, that doesn't mean we'll cover it!) nor [_complete_](https://en.wikipedia.org/wiki/Completeness_(logic)) (that is, if a particular reading or topic is *not* listed here, that doesn't mean we *won't* cover it!).

For days marked <span class="discussion">Discussion</span>, you must turn in your <a href="course-overview.html#reading-responses">reading response</a> on Canvas **by noon Pacific time on the day prior to the day of class**.  For example, for the paper to be discussed on Wednesday, October 7, you must turn in your reading response on Canvas by noon Pacific time on Tuesday, October 6.

| Date             | Topic                                          | Presenter            | Reading                                             | Notes
|------------------|------------------------------------------------|----------------------|-----------------------------------------------------|---------------------------------
| Friday, 10/2     | [Course overview](course-overview.html)        | Lindsey              | (none)
| Monday, 10/5     | <span class="lecture">Lecture</span>: distributed systems: what and why?; time and clocks; Lamport diagrams
| Wednesday, 10/7  | <span class="discussion">Discussion</span>: Jim Waldo et al., ["A Note on Distributed Computing" (1994)](readings/note-distributed-computing.pdf)
| Friday, 10/9     | <span class="lecture">Lecture</span>: causality and happens-before; network models; state and events; partial orders; total orders; Lamport clocks
| Monday, 10/12    | <span class="discussion">Discussion</span>: Leslie Lamport, ["Time, Clocks, and the Ordering of Events in a Distributed System" (CACM 1978)](readings/time-clocks.pdf) **(skip the section "Physical Clocks")**
| Wednesday, 10/14 | <span class="lecture">Lecture</span>: vector clocks; protocol runs and anomalies; delivery vs. receiving; FIFO delivery; causal delivery; totally-ordered delivery
	| Friday, 10/16    | <span class="discussion">Discussion</span>: ["Detecting Causal Relationships in Distributed Computations: In Search of the Holy Grail" (_Distributed Computing_, 1994)](readings/holy-grail.pdf) **(sections 1-3 only)**
| Monday, 10/19    | <span class="lecture">Lecture</span>: implementing FIFO delivery; implementing causal broadcast
| Wednesday, 10/21 | <span class="discussion">Discussion</span>: Kenneth Birman, André Schiper, and Pat Stephenson, ["Lightweight Causal and Atomic Group Multicast" (TOCS, 1991)](readings/cbcast.pdf) **(sections 1-5 only)**
| Friday, 10/23    | <span class="lecture">Lecture</span>: uses of causality in distributed systems; consistent snapshots; Chandy-Lamport snapshot algorithm
| Monday, 10/26    | <span class="discussion">Discussion</span>: K. Mani Chandy and Leslie Lamport, ["Distributed Snapshots: Determining Global States of Distributed Systems" (TOCS, 1985)](readings/chandy.pdf)
| Wednesday, 10/28 | <span class="lecture">Lecture</span>: Chandy-Lamport wrap-up: limitations, assumptions, properties; uses of snapshots; centralized vs. decentralized algorithms; recap of delivery guarantees and protocols; safety and liveness
	| Friday, 10/30    | <span class="discussion">Discussion</span>: Bowen Alpern and Fred B. Schneider, ["Defining liveness" (_Information Processing Letters_, 1985)](readings/liveness.pdf)
| Monday, 11/2     | <span class="lecture">Lecture</span>: recap of safety and liveness; reliable delivery; fault classification and fault models; two generals problem
| Wednesday, 11/4  | <span class="discussion">Discussion</span>: Joseph Y. Halpern and Yoram Moses, ["Knowledge and Common Knowledge in a Distributed Environment" (JACM, 1990)](readings/common-knowledge.pdf) **(sections 1-4 only)**
| Friday, 11/6     | <span class="lecture">Lecture</span>: implementing reliable delivery; idempotence; at-least-once/at-most-once/exactly-once delivery; unicast/broadcast/multicast; reliable broadcast; implementing reliable broadcast; preview of replication
	| Monday, 11/9     | <span class="discussion">Discussion</span>: Felix C. Gärtner, ["Fundamentals of Fault-Tolerant Distributed Computing in Asynchronous Environments" (ACM _Computing Surveys_, 1999)](readings/fault-tolerance.pdf)
| Wednesday, 11/11 | No class (Veterans Day)
| Friday, 11/13    | <span class="lecture">Lecture</span>: replication; total order vs. determinism; consistency models: FIFO, causal, "strong"; primary-backup replication; chain replication; latency and throughput
	| Monday, 11/16    | <span class="discussion">Discussion</span>: Robbert van Renesse and Fred B. Schneider, ["Chain Replication for Supporting High Throughput and Availability" (OSDI 2004)](readings/chain-replication.pdf)
| Wednesday, 11/18 | <span class="lecture">Lecture</span>: handling node failure in replication protocols; introduction to consensus; problems equivalent to consensus; the FLP result; introduction to Paxos
| Friday, 11/20    | <span class="discussion">Discussion</span>: Michael J. Fischer, Nancy A. Lynch, and Michael S. Paterson, ["Impossibility of Distributed Consensus with One Faulty Process" (JACM 1985)](readings/flp.pdf)
| Monday, 11/23    | <span class="lecture">Lecture</span>: Paxos: the interesting parts
| Wednesday, 11/25 | <span class="discussion">Discussion</span>: Leslie Lamport, ["Paxos Made Simple" (2001)](readings/paxos-simple.pdf)
| Friday, 11/27    | No class (Thanksgiving)
| Monday, 11/30    | <span class="lecture">Lecture</span>: Paxos wrap-up: nontermination, Multi-Paxos, fault tolerance; other consensus protocols: Viewstamped Replication, Zab, Raft; passive vs. active (state machine) replication
| Wednesday, 12/2  | <span class="discussion">Discussion</span>: Jialin Li et al., ["Just say NO to Paxos Overhead: Replacing Consensus with Network Ordering" (OSDI 2016)](readings/network-ordering.pdf)
| Friday, 12/4     | <span class="lecture">Lecture</span>: eventual consistency; strong convergence and strong eventual consistency; intro to application-specific conflict resolution; network partitions; availability; the consistency/availability trade-off; anti-entropy with Merkle trees; gossip; quorum consistency
	| Monday, 12/7     | <span class="discussion">Discussion</span>: Giuseppe DeCandia et al., ["Dynamo: Amazon’s Highly Available Key-value Store" (SOSP 2007)](readings/amazon-dynamo.pdf)
| Wednesday, 12/9  | <span class="lecture">Lecture</span>: sharding; consistent hashing
| Friday, 12/11    | <span class="discussion">Discussion</span>: Ion Stoica et al., ["Chord: A Scalable Peer-to-peer Lookup Service for Internet Applications" (SIGCOMM 2001)](readings/chord.pdf)
| Wednesday, 12/16 | Video presentations, noon-3pm Pacific time
