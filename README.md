# parliament support

*description of the project*

**Timeframe** 2026-10-13 - 2027-01-19

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/parliament-support-2026](https://cra-test-arc.canada.ca/parliament-support-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-10-27

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(Support for Members of Parliament and their constituency offices)
    node4(Helping a constituent to solve a problem)
    node5(Problem Resolution program)
    node6(Who is the program for)
    node7(When to use the program)
    node8(How to use the program)
    node9(After you make a submission)
    node10(Getting help with the program)
    node11(Additional information)
    node12(Contact Problem Resolution)
    node13(Tax filing season)
    node14(Common forms)
    node15(Benefits and payment dates)
    node16(Debt collection)
    node1 --x node2
    node2 --x node3
    node3 --> node4
    node4 --> node5
    node5 --> node6
    node5 --> node7
    node5 --> node8
    node5 --> node9
    node5 --> node10
    node3 --> node11
    node3 --> node12
    node3 --> node13
    node3 --> node14
    node3 --> node15
    node3 --x node16

    classDef inscope stroke:#7636ab,stroke-width:3px
    class node3,node4,node5,node6,node7,node8,node9,node10,node11,node12,node13,node14,node15,node16 inscope
    classDef isnew fill:#00706f,color:#fff
    class node4,node6,node7,node8,node9,node10 isnew
    classDef ismoved fill:#eab308,color:#000
    class node5 ismoved
```
