# NFR Framework

## Introdução

Segundo seu criador <a id="anchor_bib_1" href="#REFBIB1">(CHUNG *et al*, 2000)</a>, o NFR *Framework* visa representar e analisar Requisitos Não-Funcionais (RNFs) para conduzir o desenvolvimento de uma solução adequada para um domínio particular. O papel da NFR *Framework* é prover alternativas de design e resgatar conhecimento adquirido sobre cada passo do processo de desenvolvimento de um software.

## Metodologia

A *Framework* possui uma abordagem **orientada à processo** e **qualitativa**. Esses aspectos foram adotados pelo autor por dois motivos principais:

- O *processo de desenvolvimento* é grandemente influenciado por RNFs. Elas podem auxiliar o desenvolvedor a tomar de decisões acertadas no design e na implementação da solução durante o processo.
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
| ***Softgoal*** | objetivo que careçe de clara definição ou critérios de satisfação. Devido a sua dubiedade, *softgoals* não podem ser prontamente satisfeitos ou verificados. Um *softgoal* é um elemento básico da *Framework* para representação de RNFs, alternativas de design e racionalização de design. Pode ser de um dos três tipos: <ul> <li>***softgoal* de RNF**: representa uma RNF, é identificada por alguns atributos, dentre eles: *tipo de RNF* e *tópico(s)* (i. e., os sujeitos sobre os quais o *softgoal* se aplica)</li> <li>***softgoal* de operacionalização**: representa uma **operacionalização**, que é uma solução que "satisfaz" um *softgoal* </li> <li>***softgoal* de argumentação**: servem de justificativa a uma decisão. Registram reflexões e características do domínio e ajudam na rastreabilidade</li> </ul> |
| **Interdependência** | relaciona e interliga *softgoals*, gerando um grafo, denominado **SIG** (*Softgoal Interdependence Graph*), um dos principais artefatos desta *framework*, representando o espaço de design sobre o qual deciões são tomadas. Uma interdependência pode ser da forma *refinamento* ou *contriubuição*: <ul> <li>**Refinamento**: relaciona um softgoal ascendente com um ou mais *softgoals* descendentes. Subdivide-se em três *softgoals*: <ol> <li>**Decomposição**: decompõe um *softgoal* em *softgoals* de mesmo *tipo de RNF* ou *tópico*, porém mais específicos (especificado com *subtipo*, *subtópicos*, ou **prioritário**). </li> <li>**Operacionalização**: deriva um ou mais *softgoals* de operacionalização a partir de um *softgoal* qualquer</li> <li>**Argumentação**: deriva um ou mais *softgoals* de argumentação a partir de um *softgoal* qualquer</li> </ol> </li> <li>**Contribuição**: relaciona *softgoals* descendentes ao ascendente, identificando que formas de contribuição eles têm para a "satisfação" do softgoal ascendente. As formas de contribuição são: *AND*, *OR*, *MAKE*, *BREAK*, *HELP*, *HURT*, *UNKNOWN*, *EQUALS* e *SOME*</li><ol></ol> </ul> |
| **Procedimento de avaliação** | determina o grau com o qual as decisões de design tomadas "satisfazem" um softgoal. Para isso, são atribuídos **rótulos** ao *softgoals*: *satisfeito*, *fracamente satisfeito*, *negado*, *fracamente negado*, *conflitante*, *indeterminado*. As decisões de design (e consequente atribuição de rótulos) ocorrem na base do SIG, a partir dos *softgoals* derivados, e são propagados em ascendência |
| **Métodos** | também chamados **métodos de refinamento**, são *procedimentos* usados para refinamento sistemático de *softgoals* ou interdependências em um SIG. Podem ser representados visualmente ou textualmente. Divide-se de forma análoga à interdependência: <ul> <li>Métodos de decomposição de RNF: subdivide-se em *métodos de decomposição de RNF sobre o tipo* e *métodos de decomposição de RNF sobre o tópico*</li> <li>Métodos de operacionalização: aplicados após as RNFs (em forma de *softgoals*) estarem suficientemente refinadas pelo tipo de método anterior</li> <li>Métodos de argumentação</li> </ul> Cada instanciação de um método resulta em uma **interdependência explícita**. Métodos podem ser reunidos e organizados em **Catálogos** e consultados pelo desenvolvedor |
| **Correlações** | **interdependências implícitas/inferidas**. Correlações também ajudam a compor o SIG e podem ser reunidas em catálogos |

- **Catálogos**, documentos onde se reúnem conhecimentos sobre tipos de RNFs, design, ou técnicas. Eles são um apoio ao qual o desenvolvedor pode recorrer para aprender, relembrar e decidir.

### SIG ─ *Softgoal Interdependency Graph*

<center>
    <p><strong>Figura 1 – SIG do Meu SUS Digital</strong></p>

<iframe frameborder="0" style="width:100%;height:600px;" src="https://viewer.diagrams.net/?lightbox=1&highlight=0000ff&nav=1&title=NFR-Framework.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1DTp3LYv4LHlrZX6Y9QKq3W0XoNJpfAQ3%26export%3Ddownload"></iframe>

<p>Autores: <a href="https://github.com/algorithmorphic">Artur Ricardo</a> e <a href="https://github.com/JoosPerro">João Pedro</a>.</p>

</center>

O SIG é uma estrutura em grafo constituída de nós, que são os *softgoals*. Um dos possíveis papéis de um *softgoal* é representar um requisito forma abstrata e pouco clara. Esse *softgoal* deve então ser decomposto em outros *softgoals*. Decomposições podem ser do tipo AND ou OR:

Entretanto, mesmo que os *softgoals* sejam refinados, eles ainda não apresentam de forma clara como eles devem ser alcançados. Para que seja possível identificar as *operacionalizações* (isto é, as técnicas de desenvolvimento adequadas para atender aos *softgoals*), análises em diversas etapas do processo devem ser feitas sobre: ambiguidades, prioridades, *tradeoffs*, informações do domínio e das organizações envolvidas, etc. Operacionalizações são um segundo tipo de *softgoal* que faz parte do SIG.

### Catálogo

É o documento que deve conter um corpo de conhecimento de design (incluindo técnicas, conceitos e terminologia) obtido através de experiências de diversas fontes. Três tipos de catálogo podem ser escolhidos: catálogo de tipos de RNF, catálogo de métodos (ou técnicas) e catálogo de interdependências entre os *softgoals*.

Desenvolvedores podem se utilizar de catálogos preexistentes e extendê-los e refiná-los conforme o andamento do projeto.
O tipo de catálogo escolhido foi o de tipos de RNF, onde os RNFs são organizados em uma estrutura hierárquica.

---

## Evidências

<center>
    <p><strong>Figura 2 – NFR *Framework* e *softgoals*</strong></p>

![NFR Framework e softgoals](../verificacao/referencias/entr4-rnf-intro&softgoals.png)

<p>Fonte: <a id="anchor_bib_1" href="#REFBIB1">Non-Functional Requirements in Software Engineering</a>.</p>

</center>

## 📚 Referência Bibliográfica

> <a id="REFBIB1" href="#anchor_bib_1">1.</a>  CHUNG, Lawrence; NIXON, Brian A.; YU, Eric; MYLOPOULOS, Jhon. **Non-Functional Requirements in Software Engineering**. 1st ed. New York: Springer Science+Business Media. 2000.
> 

## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação do Documento. | [João Pedro](https://github.com/JoosPerro) | 11/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 17/12/2024 |
