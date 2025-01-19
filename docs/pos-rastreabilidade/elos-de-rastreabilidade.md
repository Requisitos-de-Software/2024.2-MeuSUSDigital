# Elos de Rastreabilidade

## Introdução

Elos de rastrabilidade são os elementos básicos que ligam os requisitos aos demais artefatos do projeto de software. Um elo de rastreabilidade, é um relacionamento entre dois elementos (sejam eles artefatos, informações, requisitos), apesar de poder assumir formas concretas diversas (como links, tabelas, identificadores, etc). Os tipos de elos variam conforme o modelo utilizado.

O rastreamento é um aspecto de qualidade de software, pois integra os artefatos produzidos e obtidos a cada estágio, relacionando-os aos requisitos e relacionando os requisitos ao sistema. Com rastreamento, é possível verificar facilmente se um requisito é (ou não é) atendido pelo projeto. Outras vantagens do rastreamento incluem a capacidade de:

- Acompanhar a evolução dos requisitos
- Recuperar facilmente a origem de um requisito
- Identificar os impactos de mudanças nas necessidades e nos requisitos
- Estimar variações no cronograma e nos custos do desenvolvimento

## Metodologia

O modelo aqui adotado é o de Toranzo <a href="#anchor-1">(TORANZO, 2002)</a>, que propõe os seguintes tipos de elos (relacionamentos):

- Satisfação: estabelece uma dependência de um elemento de origem em relação a um elemento de destino. Essa dependência é do tipo *satisfação*
- Recurso: estabelece que o elemento de origem depende do elemento de destino, a fim de manter consistente as informações contidas no elemento de origem
- Responsabilidade: relaciona uma pessoa a um elemento do processo de software, estabelecendo seu papel em relação ao elemento
- Representação: relaciona um requisito à um elemento, geralmente um artefato, que o represente (como um diagrama, protótipo ou algoritmo)
- Alocado: estabelece que o elemento de destino é um subsistema do elemento de origem
- Agregação: estabeleçe uma composição de elementos

Instâncias desses elos podem ser representados conforme as tabelas abaixo.

<div align="center">
    <p><strong>Tabela 1 – Modelo de Elo de Satisfação</strong></p>
</div>

| Campo | Descrição |
| --- | --- |
| Tipo | Satisfação |
| Nome | *nome do elo* |
| Descrição | *descrição do elo* |
| Origem | *elemento de origem (que é satisfeito)* |
| Destino | *elemento de destino (que satisfaz)* |

<div align="center">
    <p><strong>Tabela 2 – Modelo de Elo de Recurso</strong></p>
</div>

| Campo | Descrição |
| --- | --- |
| Tipo | Recurso |
| Nome | *nome do elo* |
| Descrição | *descrição do elo* |
| Origem | *elemento de origem* |
| Destino | *elemento de destino* |

<div align="center">
    <p><strong>Tabela 3 – Modelo de Elo de Responsabilidade</strong></p>
</div>

| Campo | Descrição |
| --- | --- |
| Tipo | Responsabilidade |
| Nome | *nome do elo* |
| Descrição | *descrição do elo* |
| Responsável | *pessoa responsável* |
| Destino | *elemento de destino* |
| Papel | *tipo de responsabilidade* |
| Grau de Responsabilidade | *ex.: analista ou programador* |
| Ação | *o que o responsável faz em relação ao elemento de destino* |

<div align="center">
    <p><strong>Tabela 4 – Modelo de Elo de Representação</strong></p>
</div>

| Campo | Descrição |
| --- | --- |
| Tipo | Alocado |
| Nome | *nome do elo* |
| Descrição | *descrição do elo* |
| Origem | *elemento de origem* |
| Destino | *elemento de destino* |
| Tipo de representação | *tipo de representação (ex.: diagrama ou protótipo)* |

<div align="center">
    <p><strong>Tabela 5 – Modelo de Elo de Alocado</strong></p>
</div>

| Campo | Descrição |
| --- | --- |
| Tipo | Alocado |
| Nome | *nome do elo* |
| Descrição | *descrição do elo* |
| Origem | *elemento de origem* |
| Destino | *elemento de destino* |

<div align="center">
    <p><strong>Tabela 6 – Modelo de Elo de Agregação</strong></p>
</div>

| Campo | Descrição |
| --- | --- |
| Tipo | Agregação |
| Nome | *nome do elo* |
| Descrição | *descrição do elo* |
| Origem | *elemento de origem* |
| Destino | *elemento de destino* |

## Rastreabilidade



## 📚 Referências Bibliográficas

> <a id="anchor-1"></a>TORANZO, M.; CASTRO, J.; MELO, E. Uma proposta para melhorar o rastreamento de requisitos. **WER**, Valencia, Espanha, p. 194-209, nov. 2002.

## 📚 Bibliografia

> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 9 jan. 2025.

## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação do Documento | [Joãoo Pedro](https://github.com/JoosPerro) | 19/01/2025 |  |  |
