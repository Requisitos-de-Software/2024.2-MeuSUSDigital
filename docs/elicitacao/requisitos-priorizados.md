# Priorização de Requisitos para o Meu SUS Digital

## Introdução

A priorização de requisitos é uma etapa essencial no desenvolvimento de software, pois permite a alocação eficiente de recursos e garante que as funcionalidades mais críticas sejam implementadas primeiro. Neste documento, serão apresentadas as técnicas utilizadas na priorização dos requisitos do *Meu SUS Digital*: [**Matriz GUT**](../elicitacao/priorizacao/matriz-gut.md) e [**$100**](../elicitacao/priorizacao/$100.md).

## Técnicas de Priorização

### Matriz GUT

A **Matriz GUT** é uma técnica de priorização que considera três fatores principais:

- **Gravidade (G):** impacto do problema caso não seja resolvido.
- **Urgência (U):** necessidade de implementação em curto prazo.
- **Tendência (T):** risco de agravamento caso não seja tratado.

A pontuação de cada requisito é calculada pelo produto:

`Prioridade = G × U × T`

Os valores atribuídos variam de 1 a 5, sendo 1 o menor e 5 o maior impacto. Após o cálculo, os requisitos são ordenados conforme a pontuação total, permitindo identificar aqueles com maior necessidade de implementação.

### Técnica dos $100

A técnica **$100** distribui um orçamento fictício de $100 entre os requisitos, onde cada stakeholder decide como alocar esse valor conforme a importância de cada item. O total acumulado de cada requisito reflete sua relevância e orienta a priorização.

Essa técnica promove participação ativa dos envolvidos no projeto e permite uma visão mais clara das prioridades do ponto de vista dos usuários e demais stakeholders.

## Aplicação no Projeto *Meu SUS Digital*

Para priorizar os requisitos do *Meu SUS Digital*, aplicamos ambas as técnicas e consolidamos os resultados. A seguir, apresentamos um exemplo de tabela com a priorização dos requisitos baseada nessas abordagens:

| Requisito | GUT (GxUxT) | $100 (Total Alocado) | Priorização Final |
|-----------|------------|--------------------|-----------------|
| O sistema deve permitir que o paciente realize login por meio de uma conta Gov.br | 125 (5x5x5) | $5 | 1° |
| O aplicativo deve disponibilizar ao usuário o acesso à sua Carteira Nacional de Vacinação Digital | 125 (5x5x5) | $5 | 1° |
| O aplicativo deve permitir que o usuário exporte/baixe o certificado referente à sua Carteira Nacional de Vacinação Digital | 125 (5x5x5) | $5 | 1° |
| O aplicativo deve possibilitar o agendamento de consultas médicas ou exames de saúde | 80 (5x4x4) | $4 | 4° |
| O aplicativo deve permitir a visualização dos exames laboratoriais realizados | 45 (5x3x3) | $3 | 5° |
| O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de medicamentos recebidos | 45 (5x3x3) | $3 | 5° |
| O aplicativo deve fornecer ao usuário, em adesão ao Programa Farmácia Popular, a opção de autorizar ou não a retirada de medicamentos em seu CPF | 45 (5x3x3) | $3 | 5° |
| O aplicativo deve permitir que o usuário possa verificar os medicamentos recebidos pelo Programa Farmácia Popular | 45 (5x3x3) | $3 | 5° |
| O aplicativo deve permitir que o usuário exporte/baixe o documento referente à autorização de participação do Programa Dignidade Menstrual | 45 (5x3x3) | $3 | 5° |

A ordenação final considera a combinação de ambas as técnicas, garantindo que requisitos críticos e de maior valor para os usuários sejam priorizados.

## Conclusão

A priorização de requisitos é fundamental para o sucesso do desenvolvimento do *Meu SUS Digital*. A combinação das técnicas **Matriz GUT** e **$100** proporciona uma abordagem equilibrada, considerando tanto impactos técnicos quanto percepção de valor pelos stakeholders. Essa metodologia permite um planejamento mais eficiente e alinhado às necessidades reais dos usuários.


## 📚 Bibliografia

> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.
>
> REINEHR, Sheila. Engenharia de requisitos [recurso eletrônico]. Revisão técnica: Marco Antônio Paludo. Porto Alegre: SAGAH, 2020.


## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação inicial da estrutura do documento referente aos requisitos priorizados. | [Artur Ricardo](https://github.com/algorithmorphic) | 10/02/2025 |  |  |