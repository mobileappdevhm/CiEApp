Risks and Technical Debts {#section-technical-risks}
=========================

## Common Causes of Technical Debts
|Causes               |Solution or Advice|
| ------------------- |----------------------|
| **Insufficient up-front definition**, where requirements are still being defined during development, development starts before any design takes place. This is done to save time but often has to be reworked later|We should start development after we have completed the design of basic functions.|
| **Business pressures**, where the business considers getting something released sooner before all of the necessary changes are complete, builds up technical debt comprising those uncompleted changes|We don't have business pressures and we will enjoy the process of developing our CiE App|
| **Lack of process or understanding**, where businesses are blind to the concept of technical debt, and make decisions without considering the implications|We should be understand what we should do at each step and consider carefully before developing something so that we can make good use of our time|
|**Tightly-coupled components** , where functions are not modular, the software is not flexible enough to adapt to changes in business needs.|Design the program carefully to ensure the flexibility |Using modular design to ensure the flexibility of the program|
|**Lack of a test suite**, which encourages quick and risky band-aids to fix bugs.|
|**Lack of documentation**, where code is created without necessary supporting documentation. The work to create any supporting documentation represents a debt that must be paid.|
|**Lack of collaboration**, where knowledge isn't shared around the organization and business efficiency suffers, or junior developers are not properly mentored.|
|**Parallel development** on two or more branches accrues technical debt because of the work required to merge the changes into a single source base. The more changes that are done in isolation, the more debt is piled up.|
|**Delayed refactoring** – As the requirements for a project evolve, it may become clear that parts of the code have become inefficient or difficult to edit and must be refactored in order to support future requirements. The longer that refactoring is delayed, and the more code is added, the bigger the debt.|
|**Lack of alignment to standards**, where industry standard features, frameworks, technologies are ignored. Eventually, integration with standards will come, doing sooner will cost less (similar to 'delayed refactoring').|
|**Lack of knowledge**, when the developer simply doesn't know how to write elegant code|
|**Lack of ownership**, when outsourced software efforts result in in-house engineering being required to refactor or rewrite outsourced code.|
|**Poor technological leadership** where poorly thought out commands handed down the chain of command increases the technical debt rather than reduce it.|
|**Last minute specification changes** these have potential to percolate throughout a project but no time or budget to see them through with documentation and checks.|
