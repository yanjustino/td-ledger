# Technical Debt Ledger (TDL)
> `authors.:` [MSc. Yan Justino](https://github.com/yanjustino)   
> `version.:` [1.0.0-beta]() . [03/2023]()  
> `language:` [pt-br](README.ptbr.md) . en-us

Technical Debt (TD) refers to the technical commitments made during software development when a quick solution is chosen over a more robust approach. Similar to financial debt, Technical Debt needs to be recognized and managed to ensure the sustainability and continuous quality of the software.

TDL is a framework dedicated to the effective management of Technical Debt in software development, arising from quick decisions at the expense of more robust solutions. TDL relies on two main pillars:

#### Self-Admitted Technical Debt (SATD)
> [!important]\
> Proactively recognize the existence of TD during development and document it for future corrective actions.

#### Technical Debt Management (TDM)
> [!important]\
> Use a structured approach to manage, monitor, and reduce TD throughout the project lifecycle.

## Framework Functionalities
TDL provides a comprehensive approach to addressing TD, promoting transparency, accountability, and continuous quality of developed software. It is addressed through six key functionalities, as illustrated in `Fig. 1`.

<p align="center">
  <br/>
  <img width="600" alt="image" src="https://github.com/yanjustino/td-ledger/assets/357114/e5bd7ace-9580-49c2-acbb-c58c558e1c4a">
  <br/>
  <small>Fig. 1 - Overview of the framework's pillars and functionalities</small>
</p>

The following details each functionality of the TDL framework.

### 1. Recognize
>Proactive identification of areas requiring technical attention

In this step, the team is encouraged to proactively recognize the presence of Technical Debt in their code by identifying areas that may require additional attention. Practices may include:

- [Code review](https://en.wikipedia.org/wiki/Code_review),
- [Architectural analysis techniques](https://www.sciencedirect.com/topics/computer-science/architecture-analysis),
- [Static analysis tools](https://en.wikipedia.org/wiki/Static_program_analysis)

### 2. Record
>Documentation for effective management

In this step, all instances of Technical Debt should be documented for effective management. Any tool that proves most productive for the team to record TDs can be adopted. The use of collaborative tools that facilitate engagement is advised.

> [!Warning]\
> It is crucial to register TD as soon as possible after its identification. Delaying this registration may lead to underreporting.

### 3. Classify
>Categorization based on specific criteria

Allows the categorization of Technical Debt based on specific criteria, facilitating an understanding of areas with higher impact and urgency. Models of classification, such as:

- [Technical Debt Quadrant - Martin Fowler](https://martinfowler.com/bliki/TechnicalDebtQuadrant.html) (categorizes the team's debt behavior)
- [Product quality model - ISO/IEC 25010:2011](https://www.iso.org/obp/ui/#iso:std:iso-iec:25010:ed-1:v1:en) (categorizes product quality properties)

> [!important]\
> Classification models can be combined to obtain different perspectives on a TD. For example, the

### 4. Prioritize
>Establishment of priorities

This step aids in prioritizing identified debts, considering factors such as project impact, urgency, and complexity. Approaches may include:

- [GUT Matrix (Gravity, Urgency, and Tendency)](https://scopi.com.br/blog/matriz-gut) (prioritizes demands)
- [T-Shirt sizing](https://asana.com/pt/resources/t-shirt-sizing) (project estimates)

### 5. Pay
>Development of strategies to address and rectify Technical Debt

In this step, the framework aims to facilitate the creation of strategies and plans to address and rectify Technical Debt, promoting the long-term health of the software. One of the strategies recommended by [Steve McConnell](https://www.construx.com/uploadedfiles/resources/whitepapers/Managing%20Technical%20Debt.pdf) in his book _Managing Technical Debt_ is:

> [!note]\
> Keep the debt list as part of a Scrum product backlog. Each debt is treated as a "story," and the estimated effort and schedule to pay each debt are estimated in the same way as other stories are estimated in Scrum.

## TDL Implementation Model
`COMING SOON`
