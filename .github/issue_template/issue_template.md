---
name: Test scenario request
about: Suggest a test scenario for Project Oni to consider
title: "[test request] "
labels: hint/needs-analysis, hint/needs-triage, kind/test-scenario
assignees: Robmat05

---
**What portion of filecoin environment are you looking for us to test**

<!-- e.g. storage deal, retrieval deal, sector sealing, storage enrolment, drand LoE membership change? -->

**What specifically would you like us to test?**

<!-- A clear and concise description of what the test scenario looks like, e.g. I'd like you to test that/if/how [...] -->

**Technical implementation details.**

<!-- Provide any technical insight that would help us implement such scenario. Think about the setup, choreography between nodes, operations involved, etc. -->

**There are multiple paths to successful test. What is the expected outcome that would indicate the tested metric is successful?**

<!-- e.g. The Happy path: what the process should do when things operate properly? -->
<!-- The Natural fault paths: things that happen naturally; e.g. recoverable consensus faults -->
<!-- Induced fault paths / attacks: potential ways to test the resilience / recovery / liveness of the system -->
<!-- Scaling paths: to test the robustness of the system -->

**What should we measure?**

<!-- Test scenarios are behaviours we orchestrate. In most cases, you'll want measurements captured. What would those be? -->

**Which components are involved?**

<!-- Enumerate the Filecoin system components that are involved in this test scenario. Feel free to provide further details. -->

**On a scale from 0-10, what's the proposed _**discomfort factor**_? In other words, how uncomfortable would you be if we went live **without** having tested this? Explain why.**

<!-- 8/10. Because... -->

**Will your test require us to provide specific formal documentation post-test?**

<!--We understand that some testing will need the results formally documented so they can be stored/presented elsewhere. Please let us know here so we can plan for creating those docs -->

**Additional remarks.**

<!-- Anything else that Project Oni should know. -->
