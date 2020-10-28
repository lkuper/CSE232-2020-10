---
title: "Schedule"
layout: splash
---

<style type="text/css">
span.discussion { color: darkmagenta; font-weight: bold }
span.lecture { color: darkslateblue; font-weight: bold }
</style>

## Schedule of topics and readings

This schedule is tentative, and it is neither [_sound_](https://en.wikipedia.org/wiki/Soundness) (that is, if a particular reading or topic is listed here, that doesn't mean we'll cover it!) nor [_complete_](https://en.wikipedia.org/wiki/Completeness_(logic)) (that is, if a particular reading or topic is *not* listed here, that doesn't mean we *won't* cover it!).

The course will alternate between <span class="discussion">Discussion</span> and <span class="lecture">Lecture</span> days.  For days marked <span class="discussion">Discussion</span>, you must turn in your [reading response](course-overview.html#what-to-include-in-your-reading-response) for that day's reading assignment on Canvas **by noon Pacific time on the day prior to the day of class**.  For example, for the paper to be discussed on Wednesday, October 7, you must turn in your reading response on Canvas by noon Pacific time on Tuesday, October 6.

| Date             | Topic                                          | Notes
|------------------|------------------------------------------------|------------------------------------------------------------------------------------------------------------
| Friday, 10/2     | [Course overview](course-overview.html)        | 
| Monday, 10/5     | <span class="lecture">Lecture</span>: distributed systems: what and why?; time and clocks; Lamport diagrams | Start-of-course survey due by start of class today
| Wednesday, 10/7  | <span class="discussion">Discussion</span>: Jim Waldo et al., ["A Note on Distributed Computing" (1994)](readings/note-distributed-computing.pdf) | Reading response due noon PT on 10/6; scribes' wiki write-up due 11:59:59pm PT on 10/14
| Friday, 10/9     | <span class="lecture">Lecture</span>: causality and happens-before; network models; state and events; partial orders; total orders; Lamport clocks
| Monday, 10/12    | <span class="discussion">Discussion</span>: Leslie Lamport, ["Time, Clocks, and the Ordering of Events in a Distributed System" (CACM 1978)](readings/time-clocks.pdf) **(skip the section "Physical Clocks")**  | Reading response due noon PT on 10/11; scribes' wiki write-up due 11:59:59pm PT on 10/19
| Wednesday, 10/14 | <span class="lecture">Lecture</span>: vector clocks; protocol runs and anomalies; delivery vs. receiving; FIFO delivery; causal delivery
	| Friday, 10/16    | <span class="discussion">Discussion</span>: Reinhard Schwarz and Friedemann Mattern, ["Detecting Causal Relationships in Distributed Computations: In Search of the Holy Grail" (_Distributed Computing_, 1994)](readings/holy-grail.pdf) **(sections 1-3 only)**  | Reading response due noon PT on 10/15; scribes' wiki write-up due 11:59:59pm PT on 10/26
| Monday, 10/19    | <span class="lecture">Lecture</span>: totally-ordered delivery; implementing FIFO delivery; implementing causal broadcast
| Wednesday, 10/21 | <span class="discussion">Discussion</span>: Kenneth Birman, André Schiper, and Pat Stephenson, ["Lightweight Causal and Atomic Group Multicast" (TOCS, 1991)](readings/cbcast.pdf) **(sections 1-5 only)** | Reading response due noon PT on 10/20; scribes' wiki write-up due 11:59:59pm PT on 10/28
| Friday, 10/23    | <span class="lecture">Lecture</span>: uses of causality in distributed systems; consistent snapshots; Chandy-Lamport snapshot algorithm
| Monday, 10/26    | <span class="discussion">Discussion</span>: K. Mani Chandy and Leslie Lamport, ["Distributed Snapshots: Determining Global States of Distributed Systems" (TOCS, 1985)](readings/chandy.pdf) | Reading response due noon PT on 10/25; scribes' wiki write-up due 11:59:59pm PT on 11/2
| Wednesday, 10/28 | <span class="lecture">Lecture</span>: Chandy-Lamport wrap-up: limitations, assumptions, properties; uses of snapshots; centralized vs. decentralized algorithms; recap of delivery guarantees and protocols; safety and liveness
	| Friday, 10/30    | <span class="discussion">Discussion</span>: Bowen Alpern and Fred B. Schneider, ["Defining Liveness" (_Information Processing Letters_, 1985)](readings/liveness.pdf) | Reading response due noon PT on 10/29; scribes' wiki write-up due 11:59:59pm PT on 11/6
| Monday, 11/2     | <span class="lecture">Lecture</span>: recap of safety and liveness; reliable delivery; fault classification and fault models; two generals problem
| Wednesday, 11/4  | <span class="discussion">Discussion</span>: Joseph Y. Halpern and Yoram Moses, ["Knowledge and Common Knowledge in a Distributed Environment" (JACM, 1990)](readings/common-knowledge.pdf) **(sections 1-4 only)** | Reading response due noon PT on 11/3; scribes' wiki write-up due 11:59:59pm PT on 11/11
| Friday, 11/6     | <span class="lecture">Lecture</span>: implementing reliable delivery; idempotence; at-least-once/at-most-once/exactly-once delivery; unicast/broadcast/multicast; reliable broadcast; implementing reliable broadcast; preview of replication
	| Monday, 11/9     | <span class="discussion">Discussion</span>: Felix C. Gärtner, ["Fundamentals of Fault-Tolerant Distributed Computing in Asynchronous Environments" (ACM _Computing Surveys_, 1999)](readings/fault-tolerance.pdf) | Reading response due noon PT on 11/8; scribes' wiki write-up due 11:59:59pm PT on 11/16
| Wednesday, 11/11 | No class (Veterans Day)
| Friday, 11/13    | <span class="lecture">Lecture</span>: replication; total order vs. determinism; consistency models: FIFO, causal, "strong"; primary-backup replication; chain replication; latency and throughput
	| Monday, 11/16    | <span class="discussion">Discussion</span>: Robbert van Renesse and Fred B. Schneider, ["Chain Replication for Supporting High Throughput and Availability" (OSDI 2004)](readings/chain-replication.pdf) | Reading response due noon PT on 11/15; scribes' wiki write-up due 11:59:59pm PT on 11/23
| Wednesday, 11/18 | <span class="lecture">Lecture</span>: handling node failure in replication protocols; introduction to consensus; problems equivalent to consensus; the FLP result; introduction to Paxos
| Friday, 11/20    | <span class="discussion">Discussion</span>: Michael J. Fischer, Nancy A. Lynch, and Michael S. Paterson, ["Impossibility of Distributed Consensus with One Faulty Process" (JACM 1985)](readings/flp.pdf) | Reading response due noon PT on 11/19; scribes' wiki write-up due 11:59:59pm PT on 11/27
| Monday, 11/23    | <span class="lecture">Lecture</span>: Paxos: the interesting parts
| Wednesday, 11/25 | <span class="discussion">Discussion</span>: Leslie Lamport, ["Paxos Made Simple" (2001)](readings/paxos-simple.pdf) | Reading response due noon PT on 11/24; scribes' wiki write-up due 11:59:59pm PT on 12/2
| Friday, 11/27    | No class (Thanksgiving break)
| Monday, 11/30    | <span class="lecture">Lecture</span>: Paxos wrap-up: nontermination, Multi-Paxos, fault tolerance; other consensus protocols: Viewstamped Replication, Zab, Raft; passive vs. active (state machine) replication
| Wednesday, 12/2  | <span class="discussion">Discussion</span>: Tushar Chandra, Robert Griesemer, and Joshua Redstone, ["Paxos Made Live: An Engineering Perspective" (invited talk, PODC 2007)](readings/paxos-made-live.pdf) | Reading response due noon PT on 12/1; scribes' wiki write-up due 11:59:59pm PT on 12/9
| Friday, 12/4     | <span class="lecture">Lecture</span>: eventual consistency; strong convergence and strong eventual consistency; intro to application-specific conflict resolution; network partitions; availability; the consistency/availability trade-off; anti-entropy with Merkle trees; gossip; quorum consistency
	| Monday, 12/7     | <span class="discussion">Discussion</span>: Giuseppe DeCandia et al., ["Dynamo: Amazon’s Highly Available Key-value Store" (SOSP 2007)](readings/amazon-dynamo.pdf)  | Reading response due noon PT on 12/6; scribes' wiki write-up due 11:59:59pm PT on 12/14
| Wednesday, 12/9  | <span class="lecture">Lecture</span>: sharding; consistent hashing
| Friday, 12/11    | <span class="discussion">Discussion</span>: Ion Stoica et al., ["Chord: A Scalable Peer-to-peer Lookup Service for Internet Applications" (SIGCOMM 2001)](readings/chord.pdf) | Reading response due noon PT on 12/10; scribes' wiki write-up due 11:59:59pm PT on 12/18
| Wednesday, 12/16 | **No final exam.**  Enjoy your winter break!
