# Technical Debt Ledger (TDL)
> `autores..:` [MSc. Yan Justino](https://github.com/yanjustino)  
> `versão...:` [1.0.0-beta]() - [03/2023]()  
> `línguas..:` pt-br . [en-us](README.md)

A **Dívida Técnica (DT)** refere-se aos compromissos técnicos assumidos durante o desenvolvimento de software, quando uma solução rápida é escolhida em detrimento de uma abordagem mais sólida. Assim como uma dívida financeira, a **DT** precisa ser reconhecida e gerenciada para garantir a sustentabilidade e qualidade contínua do software. Nesse contexto, o **TDL** é um _framework_ dedicado ao gerenciamento eficaz de **DT** no desenvolvimento de software, que se apoia em dois pilares principais:   

#### Self-Admitted Technical Debt (SATD)
> [!important]\
> Reconhecer proativamente a existência de **DT** durante o desenvolvimento e a documentar para futuras ações corretivas.

#### Technical Debt Management (TDM)
> [!important]\
> Utilizar uma abordagem estruturada para gerenciar, monitorar e reduzir a **DT** ao longo do ciclo de vida do projeto.

**TDL** proporciona uma abordagem abrangente que promove a transparência, a responsabilidade e a qualidade contínua do software desenvolvido. Isso se dá por meio de seis funcionalidades-chave, como ilustra a `Fig. 1`.

<p align="center">
  <br/>
  <img width="600" alt="image" src="https://github.com/yanjustino/td-ledger/assets/357114/e5bd7ace-9580-49c2-acbb-c58c558e1c4a">
  <br/>
  <small>Fig. 1 - visão geral dos pilares e funcionalidades do framework</small><br/>
  <small>Fonte própria</small>
</p>

Na seção a seguir, serão detalhados as características de cada uma dessas funcionalidade do **TDL**, bem como possíveis atividades que podem ser a elas relacionadas.

## Funcionalidades do Framework

### 1. Reconhecer
> Identificação proativa de áreas que requerem atenção técnica

Nessa etapa a equipe é estimulada a reconhecer proativamente a presença de dívida técnica em seu código, identificando áreas que podem exigir atenção adicional. Para isso, podem ser adotadas as seguintes práticas: 
- [Revisão de código](https://en.wikipedia.org/wiki/Code_review),
- [Técnicas de análise arquitetural](https://www.sciencedirect.com/topics/computer-science/architecture-analysis),
- [Ferramentas de análise estática](https://en.wikipedia.org/wiki/Static_program_analysis)

### 2. Registrar
> Documentação para um gerenciamento eficaz

Nessa etapa deve-se registrar todas as instâncias de dívida técnica, documentando detalhes importantes para um gerenciamento eficaz. Pode-se adotar qualquer ferramenta que se apresente mais produtiva para equipe realizar o registro de **DT's**. Aconselha-se o uso de ferramentas colaborativas e que facilitem o engajamento. 

> [!Warning]\
> É importante que a **DT** seja registrada o mais rápido possível após sua identificação. Tardar esse registro, pode ocasionar sub-notificações. Nesse sentido, o registro da **DT** sem sua imediata classificação e priorização pode ser admitido, dada a importância da documentação da **DT**.

### 3. Classificar
> Categorização com base em critérios específicos

Permite a categorização da Dívida Técnica com base em critérios específicos, facilitando a compreensão das áreas de maior impacto e urgência. Para isso, podem ser adotados modelos de classificação, como por exemplo:

- [Technical Debt Quadrant - Martin Fowler](https://martinfowler.com/bliki/TechnicalDebtQuadrant.html) (categoriza o comportamento de endividamento da equipe)
- [Product quality model - ISO/IEC 25010:2011](https://www.iso.org/obp/ui/#iso:std:iso-iec:25010:ed-1:v1:en) (categoriza propriedades de qualidade do produto)

> [!important]\
> Os modelos de classificação podem ser combinados afim de se obter diferentes perpectivas sobre uma DT.

### 4. Priorizar
> Estabelecimento de prioridades

Essa etapa ajuda na priorização das dívidas identificadas, considerando fatores como impacto no projeto, urgência e complexidade. Para essa finalidade, podem ser adotadas abordagens como:

- [Matriz GUT (Gravidade, Urgência e Tendência)](https://www.sydle.com/blog/gut-priority-matrix-62d05b64675a2377260936ae) (priorização das demandas)
- [T-Shirt sizing](https://asana.com/resources/t-shirt-sizing) (estimativas de projetos)

### 5. Quitar
>Desenvolvimento de estratégias para abordar e corrigir a Dívida Técnica

Nessa etapa procura-se facilitar a criação de estratégias e planos para abordar e corrigir a Dívida Técnica, promovendo a saúde a longo prazo do software. Uma das estratégias recomendadas por [Steve McConnell](https://www.construx.com/uploadedfiles/resources/whitepapers/Managing%20Technical%20Debt.pdf) em seu livro _Managing Technical Debt_ é:

> [!note]\
>Mantenha a lista de dívidas como parte de um backlog de produto Scrum. Cada dívida é tratada como
>uma “história”, e o esforço estimado e o cronograma para quitar cada dívida são estimados da mesma forma que outras histórias são estimadas no Scrum


## Modelo de implementação de TDL
`EM BREVE`

## Referências
- [**Self-Admitted Technical Debt - SATD**](https://ieeexplore.ieee.org/search/searchresult.jsp?matchBoolean=true&queryText=%22Index%20Terms%22:Self-Admitted%20Technical%20Debt&newsearch=true)
  >SATD is when developers are aware that the current implementation is not optimal and leave comments in the source code or elsewhere to describe the presence of technical debt.
- [**Technical Debt Quadrant - Martin Fowler**](https://martinfowler.com/bliki/TechnicalDebtQuadrant.html)
  >Approach to dividing debt into prudent/prudent and deliberate/inadvertent that implies a quadrant.
- [**Product quality model - ISO/IEC 25010:2011**](https://www.iso.org/obp/ui/#iso:std:iso-iec:25010:ed-1:v1:en)
  >The product quality model categorizes product quality properties into eight characteristics (functional suitability, reliability, performance efficiency, usability, security, compatibility, maintainability and portability).
- [**Matriz GUT (Gravidade, Urgência e Tendência)**](https://www.sydle.com/blog/gut-priority-matrix-62d05b64675a2377260936ae)
  > The GUT priority matrix is a system for ranking the importance of issues and tasks to streamline company operations.
- [**T-Shirt sizing**](https://asana.com/resources/t-shirt-sizing) (estimativas de projetos)
  >T-shirt sizing is a project estimation and capacity planning tool that helps you track how much time or effort an initiative will take. 
