

# Technical Debt Ledger (TDL)
> [!important]\
> authors..: **MSc. Yan Justino**  
> version..: [1.0.0-beta]() . [03/2023]()  
> Language.: [pt-br](README.md) . [en-us](README.md)

A Dívida Técnica (DT) refere-se aos compromissos técnicos assumidos durante o desenvolvimento de software, quando uma solução rápida é escolhida em detrimento de uma abordagem mais sólida. Assim como uma dívida financeira, a Dívida Técnica precisa ser reconhecida e gerenciada para garantir a sustentabilidade e qualidade contínua do software.

O TDL é um framework dedicado ao gerenciamento eficaz de Dívida Técnica no desenvolvimento de software. Essa dívida, resultante de decisões rápidas em detrimento de soluções mais robustas. TDL se apoia em dois pilares principais:   

- #### Self-Admitted Technical Debt (SATD)
> Reconhecer proativamente a existência de DT durante o desenvolvimento e a documentar para futuras ações corretivas.

- #### Technical Debt Management (TDM)
> Utilizar uma abordagem estruturada para gerenciar, monitorar e reduzir a DT ao longo do ciclo de vida do projeto.

## Funcionalidades do Framework
TDL proporciona uma abordagem abrangente para lidar com a DT, promovendo a transparência, a responsabilidade e a qualidade contínua do software desenvolvido. é abordada por meio de seis funcionalidades-chave, como ilustra a `Fig. 1`.

<p align="center">
  <br/>
  <img width="600" alt="image" src="https://github.com/yanjustino/td-ledger/assets/357114/e5bd7ace-9580-49c2-acbb-c58c558e1c4a">
  <br/>
  <small>Fig. 1 - visão geral dos pilares e funcionalidades do framework</small>
</p>

A seguir detalharemos os aspectos de cata funcionalidade do framework TDL.

### 1. Reconhecer
**Identificação proativa de áreas que requerem atenção técnica**\
Nessa etapa a equipe é estimulada a reconhecer proativamente a presença de dívida técnica em seu código, identificando áreas que podem exigir atenção adicional.
Para isso, podem ser adotadas as seguintes práticas: 
- [Revisão de código](https://en.wikipedia.org/wiki/Code_review),
- [Técnicas de análise arquitetural](https://www.sciencedirect.com/topics/computer-science/architecture-analysis),
- [Ferramentas de análise estática](https://en.wikipedia.org/wiki/Static_program_analysis)

### 2. Registrar
**Documentação para um gerenciamento eficaz**\
Nessa etápa deve-se registrar todas as instâncias de dívida técnica, documentando detalhes importantes para um gerenciamento eficaz. Pode-se adotar qualquer ferramenta que se apresente mais produtiva para equipe realizar o registro de DT's. Aconselha-se o uso de ferramentas colaborativas e que facilitem o engajamento. 

> [!Warning]\
> É importante que a DT seja registrada o mais rápido possível após sua identificação. Tardar esse registro, pode ocasionar sub-notificações.

### 3. Classificar
**Categorização com base em critérios específicos**\
Permite a categorização da Dívida Técnica com base em critérios específicos, facilitando a compreensão das áreas de maior impacto e urgência. Para isso, podem ser adotados modelos de classificação, como por exemplo:

- [Technical Debt Quadrant - Martin Fowler](https://martinfowler.com/bliki/TechnicalDebtQuadrant.html) (categoriza o comportamento de endividamento da equipe)
- [Product quality model - ISO/IEC 25010:2011](https://www.iso.org/obp/ui/#iso:std:iso-iec:25010:ed-1:v1:en) (categoriza propriedades de qualidade do produto)

> [!Note]\
> Os modelos de classificação podem ser combinados afim de se obter diferentes perpectivas sobre uma DT. Por exemplo, o 

### 4. Priorizar
**Estabelecimento de prioridades**
Essa etapa ajuda na priorização das dívidas identificadas, considerando fatores como impacto no projeto, urgência e complexidade. Para essa finalidade, podem ser adotadas abordagens como:

- [Matriz GUT (Gravidade, Urgência e Tendência)](https://scopi.com.br/blog/matriz-gut) (priorização das demandas)
- [T-Shirt sizing](https://asana.com/pt/resources/t-shirt-sizing) (estimativas de projetos)

### 5. Quitar
**Desenvolvimento de estratégias para abordar e corrigir a Dívida Técnica**
Nessa etapa procura-se facilitar a criação de estratégias e planos para abordar e corrigir a Dívida Técnica, promovendo a saúde a longo prazo do software. Uma das estratégias recomendadas por [Steve McConnell](https://www.construx.com/uploadedfiles/resources/whitepapers/Managing%20Technical%20Debt.pdf) em seu livro _Managing Technical Debt_ é:

>Mantenha a lista de dívidas como parte de um backlog de produto Scrum. Cada dívida é tratada como
>uma “história”, e o esforço estimado e o cronograma para quitar cada dívida são estimados da mesma forma que outras histórias são estimadas no Scrum


## Modelo de implementação de TDL
`EM BREVE`
