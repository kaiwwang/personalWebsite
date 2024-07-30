---
date: 2024-06-18T00:00:00+01:00
draft: false
title: "Final Year Project"
jobTitle: "Final Year Project"
company: "University of Glasgow"
location: "Glasgow, UK"
duration: "September 2023 - March 2024"
---

### Concurrent Runtime for Pat Language

My final year project focused on tackling the complexities of concurrent programming, such as thread deadlocks and communication mismatches.

Building upon the foundation of the Pat language created by my supervisor, I developed a concurrent runtime for Pat. Pat introduces a mailbox type system and concurrent programming primitives to tightly constrain concurrent tasks and communication flows.

Although Pat had an existing type checker, it lacked a runtime interpreter. My project involved implementing this interpreter using a task scheduler based on the CEK machine execution model and a Round-Robin algorithm, thereby improving the efficiency and accuracy of concurrent programming.

Additionally, I implemented support for the unique "Free" guard through a garbage collection strategy.

This was the first instance of employing a mailbox type system at the programming language level, offering a novel programming model for concurrent tasks. Through a series of correctness tests and micro-benchmarks, we demonstrated that Pat can efficiently handle various concurrent programming tasks and performs well across multiple concurrency models.

These findings not only highlight the potential of the Pat language in concurrent programming but also pave the way for future research and development in concurrent programming models

For more details, you can refer to my [dissertation](https://github.com/kaiwwang/individual_project/blob/main/dissertation/individual_project.pdf) and [source code](https://github.com/kaiwwang/mbcheck).

