# NFR Framework

## Introdução

## Metodologia

Segundo seu criador <a id="anchor_bib_1" href="#REFBIB1">(CHUNG *et al*, 2000)</a>, o NFR Framework visa representar e analisar **Requisitos Não-Funcionais** (RNFs) para conduzir o desenvolvimento de uma solução adequada para um domínio particular. é prover e resgatar conhecimento adquirido sobre cada passo do processo de desenvolvimento de um software<a id="anchor_1" href="#REF1"><sup>1</sup></a>.

A Framework possui uma abordagem **orientada à processo** e **qualitativa**. Esses aspectos foram adotados pelo autor por dois motivos principais:

- O *processo de desenvolvimento* é grandemente influenciado pelas NFRs, podendo elas auxiliar o desenvolvedor a tomar de decisões acertadas no design e na implementação da solução durante o processo.
- A *abordagem qualitativa* é entendida como adequada para analisar um sistema de software ainda incompleto.

Essas duas qualidades são consideradas bastante adequadas no estágio de *Análise de Requisitos*, na qual o desenvolvedor ainda tem uma visão vaga da solução. Por outro lado, abordagens complementares à NFR Framework ─ orientadas à produto e quantitativas ─ que se mostram eficazes na *Definição de Requisitos*, fase onde a as noções sobre a solução já são mais sólidas e mensuráveis.

Um conceito essencial para o NFR Framework são os **softgoals**, elementos básicos para representação de RNFs, ainda que sejam *objetivos que carecem de clara definição ou critérios de satisfação*. Os softgoals relacionam-se entre si, demonstrando existência de *interdependências*, que conduzem em boa parte as decisões de design. Além disso, cada sofgoal está sujeito a uma análise qualitativa, para decidir, mas não determinar se ele foi satisfeito ou se é impossível de ser satisfeito.

----- continuar na página 5 ---------

As atividades consideradas no NFR Framework incluem:

- Adquirir conhecimento sobre o domínio, os **Requisitos Funcionais** (RF), os tipos de RNF e técnicas associadas às RNFs
- Identificar e decompor os RNFs do domínio
- Identificar alternativas de design possíveis (**operacionalizações**) favoráveis aos RNFs
- Gerir ambiguidades, prioridades, *tradeoffs* e interdependências das NRFs e das operacionalizações
- Avaliar o impacto das decisões

A Framework apresenta duas ferramentas principais:

- **SIGs** (do inglês, **Softgoal Interdependency Graphs**), uma estrutura que representa o processo de design em forma de grafo
- **Catálogos**, documentos onde se reúnem conhecimentos sobre tipos de RNFs, design, ou técnicas. Eles são um apoio ao qual o desenvolvedor pode recorrer para aprender, relembrar e decidir

### SIG ─ Softgoal Interdependency Graph

---

### Catálogo

É o documento que deve conter um corpo de conhecimento de design (incluindo técnicas, conceitos e terminologia) obtido através de experiências de diversas fontes. Três tipos de catálogo podem ser escolhidos: catálogo de tipos de RNF, catálogo de métodos (ou técnicas) e catálogo de interdependências entre os *softgoals*.

O tipo de catálogo escolhido foi o de tipos de NFR, onde os NFRs são organizados em uma estrutura hierárquica.

<center>
    <p><strong>Tabela 1 – </strong></p>

|  |  |  |
| --- | --- | --- |
|  |  |  |
|  |  |  |
|  |  |  |

<p>Fonte: <a id="anchor_bib_1" href="#REFBIB1">1</a>.</p>
<p>Autor: <a href="https://github.com/JoosPerro">João Pedro</a>.</p>

</center>

---

## Evidências

<center>
    <p><strong>Figura 1 – NFR Framework e softgoals</strong></p>

![NFR Framework e Softgoals](../verificacao/referencias/entr4-rnf-intro&softgoals.png)

<p>Fonte: <a id="anchor_bib_1" href="#REFBIB1">Non-Functional Requirements in Software Engineering</a>.</p>

</center>

## 📚 Referência Bibliográfica

> <a id="REFBIB1" href="#anchor_bib_1">1.</a>  CHUNG, Lawrence; NIXON, Brian A.; YU, Eric; MYLOPOULOS, Jhon. **Non-Functional Requirements in Software Engineering**. 1st ed. New York: Springer Science+Business Media. 2000.
> 

## 📚 Bibliografia

## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação do Documento |[João Pedro](https://github.com/JoosPerro) | 11/12/2024 |  |  |
