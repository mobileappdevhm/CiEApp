Risks and Technical Debts
=========================
## What is Technical Debt?
Technical Debt is the time required by a rework, that might becomes neccessary if one chooses an easy over a better approach. If this debt piles up, it becomes harder and harder to make changes later in the project. It is not neccessary a bad thing, as it can also move a project forward by a significant ammount, but it is neccessary to keep them in check to ensure proper maintainability.

## Risks
-Incomplete definition: If our requirements are not fully defined, working on the app might cause us to have to change already implemented functionality. To avoid this, we should finalize our design of the basic functions before development starts.

-Parallel development: An inherent risk of working with VCS is that there are changes to merge in a single source base. To avoid this, please commit as often as neccessary and sensible.

-Lack of understanding: If desicions are made that ignore possible technical debts, it piles up and gets more difficult to deal with. To avoid this, please consider the possible technical debt if you make a project desicion.

-Lack of collaboration: Where knowledge isn't shared around or not every question a developer might have is answered. To avoid this, ensure that the group works in a good atmosphere. Every member of the group needs to give advice and help each other.

## Common Causes of Technical Debts
|Causes               |Solution or Advice|
| ------------------- |----------------------|
|**Tightly-coupled components**, where functions are not modular, the software is not flexible enough to adapt to changes.|Design the program carefully to ensure the flexibility|Using modular design to ensure the flexibility of the program.|
|**Lack of a test suite**, which encourages quick and risky band-aids to fix bugs.|If possible, keep common causes of errors in mind (no internet connection...) and ensure they are dealt with by writing tests using Flutter/native tests|
|**Delayed refactoring**, as the requirements for a project evolve, it may become clear that parts of the code have become inefficient or difficult to edit and must be refactored in order to support future requirements. The longer that refactoring is delayed, and the more code is added, the bigger the debt.|Adopt a newest technology approach to avoid Delayed refactoring. Also make sure to adhere to the Development Constraints layed out.|
|**Lack of alignment to standards**, where industry standard features, frameworks, technologies are ignored. Eventually, integration with standards will come, doing sooner will cost less.|Smiliar to Delayed refactoring, use the newest technology to avoid this problem and adhere to the Constraints.|
|**Poor technological leadership** where poorly thought out commands handed down the chain of command increases the technical debt rather than reduce it.|If a team lead makes a desicion that incurs technical debt, please make them aware of it.|
|**Last minute specification changes** these have potential to percolate throughout a project but no time or budget to see them through with documentation and checks.|We should consider our plan carefully and do most of the adjustment before developing.|
