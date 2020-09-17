---
title: "Readings"
layout: splash
---

<style type="text/css">
span.discussion { color: lemonchiffon; font-weight: bold }
span.lecture { color: lightblue; font-weight: bold }
</style>

## Schedule of readings

This schedule is tentative, and it is neither [_sound_](https://en.wikipedia.org/wiki/Soundness) (that is, if a reading is listed here, that doesn't mean we'll cover it!) nor [_complete_](https://en.wikipedia.org/wiki/Completeness_(logic)) (that is, if a reading is *not* listed here, that doesn't mean we *won't* cover it!).

| Date             | Topic                                          | Presenter            | Reading                                             | Notes
|------------------|------------------------------------------------|----------------------|-----------------------------------------------------|---------------------------------
| Friday, 10/2     | [Course overview](course-overview.html)        | Lindsey              | (none)
| Monday, 10/5     | <span class="lecture">Lecture day</span>: distributed systems: what and why?; time and clocks; Lamport diagrams
| Wednesday, 10/7  | <span class="discussion">Discussion day</span>: The Trouble with Distributed Systems
| Friday, 10/9     | <span class="lecture">Lecture day</span>: causality and happens-before; network models; state and events; partial orders; total orders; Lamport clocks
| Monday, 10/12    | <span class="discussion">Discussion day</span>: Time, Clocks, and the Ordering of Events in a Distributed System
| Wednesday, 10/14 | <span class="lecture">Lecture day</span>: vector clocks; protocol runs and anomalies; delivery vs. receiving; FIFO delivery; causal delivery; totally-ordered delivery
| Friday, 10/16    | <span class="discussion">Discussion day</span>: Detecting Causal Relationships in Distributed Computations: In Search of the Holy Grail (sections 1-3 only)
| Monday, 10/19    | <span class="lecture">Lecture day</span>: implementing FIFO delivery; implementing causal broadcast
| Wednesday, 10/21 | <span class="discussion">Discussion day</span>: Lightweight Causal and Atomic Group Multicast (sections 1-5 only)
| Friday, 10/23    | <span class="lecture">Lecture day</span>: uses of causality in distributed systems; consistent snapshots; Chandy-Lamport snapshot algorithm
| Monday, 10/26    | <span class="discussion">Discussion day</span>: Distributed Snapshots: Determining Global States of Distributed Systems
| Wednesday, 10/28 | <span class="lecture">Lecture day</span>: Chandy-Lamport wrap-up: limitations, assumptions, properties; uses of snapshots; centralized vs. decentralized algorithms; recap of delivery guarantees and protocols; safety and liveness
| Friday, 10/30    | <span class="discussion">Discussion day</span>: Defining Liveness
| Monday, 11/2     | <span class="lecture">Lecture day</span>: recap of safety and liveness; reliable delivery; fault classification and fault models; two generals problem
| Wednesday, 11/4  | <span class="discussion">Discussion day</span>: The Byzantine Generals Problem
| Friday, 11/6     | <span class="lecture">Lecture day</span>: implementing reliable delivery; idempotence; at-least-once/at-most-once/exactly-once delivery; unicast/broadcast/multicast; reliable broadcast; implementing reliable broadcast; preview of replication
| Monday, 11/9     | <span class="discussion">Discussion day</span>: TODO
| Wednesday, 11/11 | No class (Veterans Day)
| Friday, 11/13    | <span class="lecture">Lecture day</span>: replication; total order vs. determinism; consistency models: FIFO, causal, "strong"; primary-backup replication; chain replication; latency and throughput
| Monday, 11/16    | <span class="discussion">Discussion day</span>: Chain Replication
| Wednesday, 11/18 | OOPSLA
| Friday, 11/20    | <span class="lecture">Lecture day</span>: handling node failure in replication protocols; introduction to consensus; problems equivalent to consensus; the FLP result; introduction to Paxos
| Monday, 11/23    | <span class="discussion">Discussion day</span>: Impossibility of Distributed Consensus with One Faulty Process
| Wednesday, 11/25 | <span class="lecture">Lecture day</span>: Paxos: the interesting parts
| Friday, 11/27    | No class (Thanksgiving)
| Monday, 11/30    | <span class="discussion">Discussion day</span>: Paxos Made Simple
| Wednesday, 12/2  | <span class="lecture">Lecture day</span>: Paxos wrap-up: nontermination, Multi-Paxos, fault tolerance; other consensus protocols: Viewstamped Replication, Zab, Raft; passive vs. active (state machine) replication
| Friday, 12/4     | <span class="discussion">Discussion day</span>: In Search of an Understandable Consensus Protocol
| Monday, 12/7     | TBD
| Wednesday, 12/9  | TBD
| Friday, 12/11    | TBD
| Wednesday, 12/16 | Final exam time slot, noon-3pm Pacific time

## Further reading

TBD
