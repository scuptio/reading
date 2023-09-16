# Reading
Distributed system && Database reading list


## Formal method

### TLA+

Lamport. Learning TLA+ [[link]](https://lamport.azurewebsites.net/tla/learning.html)


Hillel. Learn TLA+ [[link]](https://learntla.com/)

Hillel Wayne. Practical TLA+ Planning Driven Development [[link]](https://link.springer.com/book/10.1007/978-1-4842-3829-5)

### Industrial use

Formal Development of a Network-Centric RTOS [[pdf]](https://link.springer.com/book/10.1007/978-1-4419-9736-4)

How Amazon Web Services Uses Formal Methods  [[pdf]](https://cacm.acm.org/magazines/2015/4/184701-how-amazon-web-services-uses-formal-methods/abstract)


### Model-based for Testing
Andrey Kupriyanov, Igor Konnov. Model-based testing with TLA+ and Apalache [[pdf]](https://conf.tlapl.us/2020/09-Kuprianov_and_Konnov-Model-based_testing_with_TLA_+_and_Apalache.pdf)  [[video]](https://www.youtube.com/watch?v=aveoIMphzW8)


A. Jesse Jiryu Davis, Max Hirschhorn, Judah Schvimer. Extreme modelling in practice [[pdf]](https://dl.acm.org/doi/abs/10.14778/3397230.3397233)

[The seL4 Microkernel](https://sel4.systems/)

Sel4 is a high-assurance, high-performance operating system microkernel which uses formal verification.
The seL4 verification uses formal proof in the theorem prover [Isabelle/HOL](https://isabelle.in.tum.de/)


Model Checking Guided Testing for Distributed
Systems [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3552326.3587442)

Using Lightweight Formal Methods to Validate a Key-Value Storage Node in Amazon S3 [[pdf]](https://dl.acm.org/doi/10.1145/3477132.3483540)

Kayfabe: Model-based program testing with TLC - Star Dorminey [[video]](https://www.youtube.com/watch?v=lj31oIaYSj4)

### State explosion problem


Xiaosong Gu, Wei Cao, Yicong Zhu, Xuan Song, Yu Huang, Xiaoxing Ma. Compositional Model Checking of Consensus Protocols Specified in TLA+ via Interaction-Preserving Abstraction [[pdf]](https://arxiv.org/abs/2202.11385)

Using compositional model to check Raft and avoid the state explosion problem.


A. Methni, B. Ben Hedia, M. Lemerre, S. Haddad, K. Barkaoui. State Space Reduction Strategies for Model Checking Concurrent C Programs [[pdf]](https://hal-cea.archives-ouvertes.fr/cea-01844041/file/MLBHB-vecos15.pdf)


## Distributed System Theory

Distributed Algorithms,  Nancy A. Lynch [[link]](https://dl.acm.org/doi/book/10.5555/2821576)

## Distributed System Testing
Greybox Fuzzing of Distributed Systems[[pdf]](https://arxiv.org/pdf/2305.02601.pdf)

## Database

### NVME

What Modern NVMe Storage Can Do, And How To Exploit It: High-Performance I/O for High-Performance Storage Engines Gabriel Haas, Viktor Leis [[pdf]](https://www.vldb.org/pvldb/vol16/p2090-haas.pdf)

Exploiting Directly-Attached NVMe Arrays in DBMS
Gabriel Haas, Michael Haubenschild, Viktor Leis [[pdf]](https://www.cidrdb.org/cidr2020/papers/p16-haas-cidr20.pdf)

### MVCC

Memory-Optimized Multi-Version Concurrency Control for Disk-Based Database Systems [[pdf]](https://www.vldb.org/pvldb/vol15/p2797-freitag.pdf)


# System Tech

## io_uring

Efficient IO with io_uring [[pdf]](https://kernel.dk/io_uring.pdf)


Rust io_uring wrapper, [tokio-uring](https://docs.rs/tokio-uring/latest/tokio_uring/)

io_uring example, [io_uring-by-examplej](https://github.com/shuveb/io_uring-by-example)

[awesome-iouring](https://github.com/espoal/awesome-iouring)

[PostgreSQL io_uring support Discussion](https://www.postgresql.org/message-id/CA%2Bq6zcU9oa96K8qL26qTGnygzLmBrX%2BZXwBs_HP2TR5h_wnBDg%40mail.gmail.com)

## Rust programming language

[Rust](https://www.rust-lang.org/)

[Rust, The Book](https://doc.rust-lang.org/book/)

[Rust, The Async Book](https://rust-lang.github.io/async-book/)
