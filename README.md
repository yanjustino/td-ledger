# Technical Debt Ledger (TDL)
> `authors.:` [MSc. Yan Justino](https://github.com/yanjustino)   
> `version.:` [1.0.0-beta]() . [03/2023]()  
> `language:` [pt-br](README.ptbr.md) . en-us

**Technical Debt (TD)** refers to the technical commitments made during software development when a quick solution is chosen over a more robust approach. Similar to financial debt, **Technical Debt** needs to be recognized and managed to ensure the sustainability and continuous quality of the software. In this context, **TDL** is a framework dedicated to the effective management of **Technical Debt** in software development, relying on two main pillars:

#### Self-Admitted Technical Debt (SATD)
> [!important]\
> Proactively recognize the existence of **Technical Debt** during development and document it for future corrective actions.

#### Technical Debt Management (TDM)
> [!important]\
> Use a structured approach to manage, monitor, and reduce **Technical Debt** throughout the project lifecycle.

**TDL** provides a comprehensive approach that promotes transparency, accountability, and continuous quality of the developed software. This is achieved through six key functionalities, as illustrated in `Fig. 1`.

<p align="center">
  <br/>
  <img width="600" alt="image" src="https://github.com/yanjustino/td-ledger/assets/357114/e5bd7ace-9580-49c2-acbb-c58c558e1c4a">
  <br/>
  <small>Fig. 1 - Overview of the framework's pillars and functionalities</small><br/>
  <small>Own source</small>
</p>

The following section details each of these **TDL** functionalities, as well as possible activities related to them.

## Framework Functionalities

### 1. Recognize
> Proactive identification of areas requiring technical attention

In this step, the team is encouraged to proactively recognize the presence of technical debt in their code, identifying areas that may require additional attention. Practices may include:

- [Code review](https://en.wikipedia.org/wiki/Code_review),
- [Architectural analysis techniques](https://www.sciencedirect.com/topics/computer-science/architecture-analysis),
- [Static analysis tools](https://en.wikipedia.org/wiki/Static_program_analysis)

### 2. Record
> Documentation for effective management

In this step, all instances of technical debt should be documented for effective management. Any tool that proves most productive for the team to record **Technical Debts** can be adopted. The use of collaborative tools that facilitate engagement is advised.

> [!Warning]\
> It is important that **Technical Debt** be registered as soon as possible after its identification. Delaying this registration may lead to underreporting. In this sense, registering **Technical Debt** without its immediate classification and prioritization may be admitted, given the importance of documenting **Technical Debt**.

### 3. Classify
> Categorization based on specific criteria

Allows the categorization of Technical Debt based on specific criteria, facilitating an understanding of areas with higher impact and urgency. Models of classification, such as:

- [Technical Debt Quadrant - Martin Fowler](https://martinfowler.com/bliki/TechnicalDebtQuadrant.html) (categorizes the team's debt behavior)
- [Product quality model - ISO/IEC 25010:2011](https://www.iso.org/obp/ui/#iso:std:iso-iec:25010:ed-1:v1:en) (categorizes product quality properties)

> [!important]\
> Classification models can be combined to obtain different perspectives on a **Technical Debt**.

### 4. Prioritize
> Establishment of priorities

This step aids in prioritizing the identified debts, considering factors such as project impact, urgency, and complexity. Approaches may include:

- [GUT Matrix (Gravity, Urgency, and Tendency)](https://www.sydle.com/blog/gut-priority-matrix-62d05b64675a2377260936ae) (prioritizes demands)
- [T-Shirt sizing](https://asana.com/resources/t-shirt-sizing) (project estimates)

### 5. Pay
> Development of strategies to address and rectify Technical Debt

In this step, the framework aims to facilitate the creation of strategies and plans to address and rectify Technical Debt, promoting the long-term health of the software. One of the strategies recommended by [Steve McConnell](https://www.construx.com/uploadedfiles/resources/whitepapers/Managing%20Technical%20Debt.pdf) in his book _Managing Technical Debt_ is:

> [!note]\
> **Maintain the debt list as part of a Scrum product backlog**. Each debt is treated as a Scrum “story,” and the estimated effort and schedule to pay off each debt is estimated the same way other stories are estimated in Scrum. 

## TDL Implementation Model
`COMING SOON`

## References
- [**Self-Admitted Technical Debt - SATD**](https://ieeexplore.ieee.org/search/searchresult.jsp?matchBoolean=true&queryText=%22Index%20Terms%22:Self-Admitted%20Technical%20Debt&newsearch=true)
  >SATD is when developers are aware that the current implementation is not optimal and leave comments in the source code or elsewhere to describe the presence of technical debt.
- [**Technical Debt Quadrant - Martin Fowler**](https://martinfowler.com/bliki/TechnicalDebtQuadrant.html)
  >Approach to dividing debt into prudent/prudent and deliberate/inadvertent that implies a quadrant.
- [**Product quality model - ISO/IEC 25010:2011**](https://www.iso.org/obp/ui/#iso:std:iso-iec:25010:ed-1:v1:en)
  >The product quality model categorizes product quality properties into eight characteristics (functional suitability, reliability, performance efficiency, usability, security, compatibility, maintainability and portability).
- [**GUT Matrix (Gravity, Urgency, and Tendency)**](https://www.sydle.com/blog/gut-priority-matrix-62d05b64675a2377260936ae)
  > The GUT priority matrix is a system for ranking the importance of issues and tasks to streamline company operations.
- [**T-Shirt sizing**](https://asana.com/resources/t-shirt-sizing) (project estimates)
  >T-shirt sizing is a project estimation and capacity planning tool that helps you track how much time or effort an initiative will take.
