# NFR Framework

## Introdução

## Metodologia

Segundo seu criador <a id="anchor_bib_1" href="#REFBIB1">(CHUNG *et al*, 2000)</a>, o NFR *Framework* visa representar e analisar Requisitos Não-Funcionais (RNFs) para conduzir o desenvolvimento de uma solução adequada para um domínio particular. O papel da NFR *Framework* é prover alternativas de design e resgatar conhecimento adquirido sobre cada passo do processo de desenvolvimento de um software<a id="anchor_1" href="#REF1"><sup>1</sup></a>.

A *Framework* possui uma abordagem **orientada à processo** e **qualitativa**. Esses aspectos foram adotados pelo autor por dois motivos principais:

- O *processo de desenvolvimento* é grandemente influenciado por NFRs. Elas podem auxiliar o desenvolvedor a tomar de decisões acertadas no design e na implementação da solução durante o processo.
- A *abordagem qualitativa* é adequada para analisar um sistema de software ainda incompleto.

Essas duas qualidades são consideradas bastante adequadas no estágio de *Análise de Requisitos*, na qual o desenvolvedor ainda tem uma visão vaga da solução. Por outro lado, abordagens complementares à NFR *Framework* ─ orientadas à produto e quantitativas ─ que se mostram eficazes na *Definição de Requisitos*, fase onde a as noções sobre a solução já são mais sólidas e mensuráveis.

As atividades consideradas no NFR *Framework* incluem:

- Adquirir conhecimento sobre o domínio e o sistema em desenvolvimento, seus Requisitos Funcionais (RFs), tipos específicos de RNFs e suas técnicas associadas
- Identificar as RNFs específicas ao domínio domínio
- Decompor RNFs
- Identificar alternativas de design (soluções possíveis)
- Gerir ambiguidades, prioridades, *tradeoffs* e interdependências de NRFs e *operacionalizações*
- Racionalizar decisões de design
- Avaliar o impacto das decisões de design

Para entender o NFR Framework, deve-se conhecer os principais de seus componentes:

| Expressão | Descrição |
| --------- | --------- |
| ***Softgoal*** | objetivo que careçe de clara definição ou critérios de satisfação. Devido a sua dubiedade, *softgoals* não podem ser prontamente satisfeitos ou verificados. Eles representam restrições gerais ao sistema. Um *softgoal* é um elemento básico da *Framework* para representação de RNFs, alternativas de design e racionalização de design. Pode ser de um dos três tipos: <ul> <li>***softgoal* de RNF**: representa uma RNF</li> <li>***softgoal* de operacionalização**: representa uma **operacionalização**, que é uma solução que "satisfaz" um *softgoal* </li> <li>***softgoal* de argumentação**: servem de justificativa a uma decisão. Registram reflexões e características do domínio e ajudam na rastreabilidade</li> </ul> |
| **Interdependência** | relaciona e interliga *softgoals*, gerando um grafo, denominado **SIG** (*Softgoal Interdependence Graph*), um dos principais artefatos desta *framework*, representando o espaço de design sobre o qual deciões são tomadas. Uma interdependência pode ser do tipo *refinamento* ou *contriubuição*: <ul> <li>**Refinamento**: relaciona um softgoal ascendente com um ou mais *softgoals* descendentes. Subdivide-se em três *softgoals*: <ol> <li>**Decomposição**: decompõe um *softgoal* em *softgoals* de mesmo tipo, mas mais específicos. Um tipo especial de decomposição é a **priorização**, que deriva um *softgoal* igual ao seu softgoal ascendente, mas identificado como prioritário</li> <li>**Operacionalização**: deriva um ou mais *softgoals* de operacionalização a partir de um *softgoal* qualquer</li> <li>**Argumentação**: deriva um ou mais *softgoals* de argumentação a partir de um *softgoal* qualquer</li> </ol> </li> <li>**Contribuição**: relaciona *softgoals* descendentes ao ascendente, identificando que tipo de contribuição eles têm para a "satisfação" do softgoal ascendente. Os tipos de contribuição são: *AND*, *OR*, *MAKE*, *BREAK*, *HELP*, *HURT*, *UNKNOWN*, *EQUALS* e *SOME*</li><ol></ol> </ul> |
| **Procedimento de avaliação** | determina o grau com o qual as decisões de design tomadas "satisfazem" um softgoal. Para isso, são atribuídos **rótulos** ao *softgoals*: *satisfeito*, *fracamente satisfeito*, *negado*, *fracamente negado*, *conflitante*, *indeterminado*. As decisões de design (e consequente atribuição de rótulos) ocorrem na base do SIG, a partir dos *softgoals* derivados, e são propagados em ascendência |
| **Métodos** | também chamados **métodos de refinamento**, são procedimentos usados para refinamento sistemático de *softgoals* ou interdependências em um SIG. Possuem tipos análogos aos da interdependência: <ul> <li>Métodos de decomposição de NFR</li> <li>Métodos de operacionalização: aplicados após as NFRs (em forma de *softgoals*) estarem suficientemente refinadas pelo tipo de método anterior</li> <li>Métodos de argumentação</li> </ul> Cada instanciação de um método resulta em uma **interdependência explícita**. Métodos podem ser reunidos e organizados em **Catálogos** e consultados pelo desenvolvedor |
| **Correlações** | -------São?------- **interdependências implícitas/inferidas**. Correlações também ajudam a compor o SIG e podem ser reunidas em catálogos |

- **Catálogos**, documentos onde se reúnem conhecimentos sobre tipos de RNFs, design, ou técnicas. Eles são um apoio ao qual o desenvolvedor pode recorrer para aprender, relembrar e decidir.

### SIG ─ *Softgoal Interdependency Graph*

O SIG é uma estrutura em grafo constituída de nós, que são os *softgoals*. Um dos possíveis papéis de um *softgoal* é representar um requisito forma abstrata e pouco clara. Esse *softgoal* deve então ser decomposto em outros *softgoals*. Decomposições podem ser do tipo AND ou OR:

- AND: indica que todos os *softgoals* derivados devem ser atendidos

----por notação 1 aqui-----

Entretanto, mesmo que os *softgoals* sejam refinados, eles ainda não apresentam de forma clara como eles devem ser alcançados. Para que seja possível identificar as *operacionalizações* (isto é, as técnicas de desenvolvimento adequadas para atender aos *softgoals*), análises em diversas etapas do processo devem ser feitas sobre: ambiguidades, prioridades, *tradeoffs*, informações do domínio e das organizações envolvidas, etc. Operacionalizações são um segundo tipo de *softgoal* que faz parte do SIG.

----por notação 2 aqui------



### Catálogo

É o documento que deve conter um corpo de conhecimento de design (incluindo técnicas, conceitos e terminologia) obtido através de experiências de diversas fontes. Três tipos de catálogo podem ser escolhidos: catálogo de tipos de RNF, catálogo de métodos (ou técnicas) e catálogo de interdependências entre os *softgoals*.

Desenvolvedores podem se utilizar de catálogos preexistentes e extendê-los e refiná-los conforme o andamento do projeto.
O tipo de catálogo escolhido foi o de tipos de NFR, onde os NFRs são organizados em uma estrutura hierárquica.

---

## Evidências

<center>
    <p><strong>Figura 1 – NFR *Framework* e *softgoals*</strong></p>

![NFR Framework e softgoals](../verificacao/referencias/entr4-rnf-intro&softgoals.png)

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
