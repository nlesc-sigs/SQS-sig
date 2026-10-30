# Log of previous SQ&S SIGs

- Add most recent entry to top
- Normal SIG meeting info:
  - Title
  - Description/Abstract
  - Presenter
  - Optional additional notes
- Exceptions can be stored as free form

## 2026-10-01

- Title: What's New in Programming Languages
- Description: At the eScience center we do most of our work in a select few programming languages: Python, R, C++, Fortran, Julia, JS. These languages are all decades old. Meanwhile, programming languages are still being developed, and we should be aware of these developments when it comes to technology readiness. I will give an overview of what features set the newest programming languages apart.

  There is a wave of newer systems programming languages that try to achieve the applicability of C++, but without the shenanigans of OOP: think Zig, Odin, C3, Carbon, Jai. I may also touch upon where Rust lies in this landscape.

  All of these languages have subtly different views on how memory management should be done. An interesting new phenomenon is making the stage here. Functional languages are always heavily reliant on garbage collectors. However, efficient garbage collection is still an unsolved problem. This is why Rust is such an interesting option: it offers guarantees of memory safety without garbage collection. In newer functional lanugages: Koka and Roc, functional recursion is translated into loops with fixed stack based allocations: functional-but-in-place. Combined with reference counting this can give a complete solution with deterministic run times.

  Meanwhile Python is transforming into a new language, without the GIL, tight loop optimizations and a prominent place for a type checker. The Mojo language uses Python syntax and a similar typing system, but is compiled to a multitude of accelerated targets, for use with AI.

  When it comes to using GenAI for programming, indications are that writing in a strictly typed language gives more reliable results. There is an entire class of functional programming languages that use the type system to control what parts of a program have access to your database and what functions can throw exceptions. This is called an effect system. Haskell and OCaml have support for effects, but there is a new language that fully embraces this feature: Koka (again!).

  We can go one step further: full formal verification. Here are languages like Rocq, Lean, and Idris. You may need a PhD in mathematics to write meaningful programs in these languages, but they do give you absolute certainty that their programs work as advertised. The idea being that a type is a theorem about your program, and the implementation is its proof. Lean is also used extensively in computer aided algebra, and can be used to let GenAI prove your theorems.
- Presenter: Johan Hidding
- [Recording][rec-2026-10-29]

[rec-2026-10-29]: https://nlesc.sharepoint.com/:v:/r/sites/softwaresustainability/_layouts/15/stream.aspx?id=%2Fsites%2Fsoftwaresustainability%2FShared%20Documents%2FRecordings%2FSIG%20Software%20Quality%20_%20Sustainability%20(SQ_S)-20261029_140219-Meeting%20Recording.mp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&share=cQrp54iVBrqBTZLiWY4mhQCgEgUCfXkqi6RybislMXkCW4EWIA

## 2026-10-01

- Title: EVERSE, AI Declaration and AI Coding Agent Skills
- Description: In this session, I will cover a few key topics:
  - EVERSE Project: An introduction to this EU project focused on measuring and improving research software quality, including an overview of the metrics, services, and tools it provides.
  - AI Declaration Format: An overview of this initiative (<https://ai-declaration.org>).
  - AI Coding Agent Skills for Research Software Engineering: A look at skills and capabilities for AI agents in RSE (<https://github.com/fdiblen/rseng-agent-skills>).
- Presenter: Faruk Diblen
- [Recording][rec-2026-10-01]
- Extras
  - Link to CodiMD: <https://codimd.carpentries.org/-yHn034IQjScpCFJvt73Bg>

[rec-2026-10-01]: https://nlesc.sharepoint.com/:v:/s/softwaresustainability/IQCjV6jblv4aQod2PR-KekxlAXEiPvG8TGmc_0pH4DxIAgc?e=zT5sfi

## 2026-09-03

- Title: Secure Software Development Life Cycle Policy
- Description: Due to the increasing number of cybersecurity threats and the introduction of the Cyberbeveiligingswet (Cbw), which implements the EU NIS2 Directive, the management of the eScience Centre decided to implement an Information Security Management System (ISMS). The ISMS will be implemented in accordance with ISO 27001, the international standard for information security.

  The ISO 27001 controls cover four domains: Organisational, People, Physical, and Technical. Within the Technical domain, approximately six controls are related to software development. During this phase of the ISMS implementation, the required deliverables for each control are being defined, and a first draft has already been prepared.

  The objective of this session is to explain the proposed approach and deliverables, gather initial feedback, and discuss the process for collecting and incorporating feedback going forward.
- Presenter: Johan Ruiter
- [Recording][rec-2026-09-03]

[rec-2026-09-03]: https://nlesc.sharepoint.com/:v:/s/softwaresustainability/IQB2o9Rr4I3mRI3_6bgF-ZDDARCbLZl-NAIYCbPQDWASYN8?e=9jgzNw

## 2026-06-11

SIG gave place to internal presentation by Peter, Jason, and Elena about "Software quality score cards in and beyond OSS"

## 2026-04-16

- Title: Continuous localization with Weblate in the Dynamic3D project
- Description: Weblate is a service to embed localization into the development process. I will show how we have integrated Weblate into the Dynamic 3D project for handling translations.
- Presenter: Carsten Schnober
- [Content](./weblate/), [slides](./weblate/weblate-presentation.html), and [recording][rec-2026-04-16]

[rec-2026-04-16]: https://nlesc.sharepoint.com/:v:/s/softwaresustainability/IQAOY55IUN0vQYRmrqBu4Ax1ARQRYbzt385ixiAAXibiJ_4?e=67hBd8

## 2026-03-19

- Title: Software Quality Metrics
- Description: I will talk about a new way to evaluate SQ&S at the NLeSC, why it matters, what it is, and how to use it.
- Presenter: Abel Soares Siqueira
- [Recording][rec-2026-03-19]:

[rec-2026-03-19]: https://nlesc.sharepoint.com/:v:/s/softwaresustainability/IQDLLQr9HnV5RYdaXlsuDjxTAUJgyXctbhoh50bEZd8R0cM?e=mmAk3X
