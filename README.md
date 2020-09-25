# systems-lunch

The UMass CS Systems Lunch talk series is Fridays at 12:00pm ~~in room
A311 (LGRC)~~ on your laptop anywhere on the planet! Everyone interested
in systems is welcome to attend. Systems Lunch is a great opportunity
to hear exciting talks by visitors as well as to learn about projects
going on in the College.

All talks will be over Zoom and will require registration and a password.
To register, [fill out this Google form.](https://forms.gle/uV2Q8vxnZvZ5zaAh9)

## Fall 2020

### October 2, 2020

| Speaker              | Talk Info |
| :------------------- | :---- |
| [Adrian Sampson](http://www.cs.cornell.edu/~asampson/), Cornell | **Languages and Compilers for Accelerator Design** |
|         | We need to make it easier to design custom accelerators, especially for reconfigurable hardware (i.e., FPGAs). The current mainstream options are hardware description languages (HDLs), which are low-level languages that make it feel like you’re wiring up a circuit by hand, and high-level synthesis (HLS) tools, which compile legacy software languages like C or C++ to an HDL. The thesis of this talk is that better alternatives are possible. We find empirically (and unsurprisingly) that the semantic chasm between C++ and hardware circuits comes with myriad correctness and performance pitfalls. We advocate instead for more research on accelerator design languages: programming models that maintain computational semantics while not attempting to shield developers from thinking about hardware. Our lab is designing a programming language, Dahlia, that uses a type system to restrict HLS programs to a subset with predictable semantics and performance. Beyond Dahlia, we are designing an open-source compiler infrastructure to support the construction of new accelerator design languages. |
|        | **Bio:** Adrian Sampson is an assistant professor in the computer science department at Cornell. He works on programming languages, computer architecture, and the abstractions that separate them. He previously worked on approximate computing, the idea that we should allow machines to expose errors to some kinds of applications as a trade-off for computational efficiency. He sees approximate computing as an instance of a broader breakdown of airtight distinctions between hardware and software concerns. |

### November 13, 2020

|[Tianqi Chen](https://tqchen.com/), CMU | TVM: An automated deep learning compiler |
| :------------------- | :---- |
|                   | Data, models, and computing are the three pillars that enable machine learning to solve real-world problems at scale. Making progress on these three domains requires not only disruptive algorithmic advances but also systems innovations that can continue to squeeze more efficiency out of modern hardware. Learning systems are in the center of every intelligent application nowadays. However, the ever-growing demand for applications and hardware specialization creates a huge engineering burden for these systems, most of which rely on heuristics or manual optimization. In this talk, I will present a new approach that uses machine learning to automate system optimizations. I will describe our approach in the context of deep learning deployment problems. I will first discuss how to design invariant representations that can lead to transferable statistical cost models, and apply these representations to optimize tensor programs used in deep learning applications. I will then describe the system improvements we made to enable diverse hardware backends. TVM, our end-to-end system, delivers performance across hardware back-ends that are competitive with state-of-the-art, hand-tuned deep learning frameworks. |
|        | **Bio:** Tianqi Chen is currently an Assistant Professor at the Machine Learning Department and Computer Science Department of Carnegie Mellon University. He received his PhD. from the Paul G. Allen School of Computer Science & Engineering at the University of Washington, working with Carlos Guestrin on the intersection of machine learning and systems. He has created three major learning systems that are widely adopted: XGBoost, TVM, and MXNet (co-creator). |




