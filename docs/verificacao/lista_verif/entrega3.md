# Lista de Verificação - Entrega 3

## Introdução

O artefato apresenta o planejamento da verificação dos artefatos desenvolvidos pelo grupo 4 e grupo 5 durante a Etapa 3 (Modelagem de Requisitos).

## Objetivos

O objetivo deste documento é registrar a lista de verificação da 3ª etapa do Grupo 4, que será utilizada para verificar artefatos do próprio grupo e do Grupo 5.

## Metodologia

Através de reuniões, o grupo decidiu adotar a metodologia de verificação por inspeção desenvolvida por Fagan (Michael E. Fegan) em 1976. Dessa maneira, cada integrante participa na entrega do projeto nos prazos planejados. Cada artefato varificado gera um relatório anexado junto aos demais artefatos daquela entrega. Para responder às perguntas apresentadas nas listas de verificação o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador tambem poderá escrever observações para cada item, se achar necessário.

## Lista de Verificação


<center> 

**Tabela 1** – Casos de Uso

| ID  | Descrição | Fonte  | Autor |
| :-: | :-------- | :----- | :---: |
| 01  | O diagrama representa o sistema, que é o software modelado, como um retângulo intitulado pelo nome do sistema?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 01:46 | [João Pedro](https://github.com/JoosPerro) |
| 02  | O diagrama representa <a id="TERM1" href="#term_anchor_1">atores</a> como bonecos-palito posicionados fora do sistema?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 02:10 | [João Pedro](https://github.com/JoosPerro) |
| 03  | Cada ator é intitulado como um tipo ou categoria (como cliente ou banco), ao invés de uma entidade específica (como João ou Banco do Brasil)?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 02:53 | [João Pedro](https://github.com/JoosPerro) |
| 04  | Os atores que iniciam a utilização do sistema (chamados primários) estão posicionados à esquerda do sistema, enquanto os atores que reagem (chamados secundários) estão posicionados à direita?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 03:14 | [João Pedro](https://github.com/JoosPerro) |
| 05  | Os <a id="TERM2" href="#term_anchor_2">casos de uso</a> são representados por uma forma oval, posicionada dentro do sistema?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 04:09 | [João Pedro](https://github.com/JoosPerro) |
| 06  | Cada caso de uso é intitulado com uma frase que começa com um verbo?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 04:50 | [João Pedro](https://github.com/JoosPerro) |
| 07  | Os <a id="TERM3" href="#term_anchor_3">relacionamentos</a> entre ator e ator, entre caso de uso e caso de uso, e entre ator e caso de uso são denotados por algum estilo de linha? | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 05:41 | [João Pedro](https://github.com/JoosPerro) |
| 08  | Cada caso de uso está relacionado com pelo menos um ator ou outro caso de uso? | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 05:41 | [João Pedro](https://github.com/JoosPerro) |
| 09  | Os <a id="TERM3" href="#term_anchor_3">relacionamentos associativos</a> são representados como linhas sólidas? | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 05:17 | [João Pedro](https://github.com/JoosPerro) |
| 10  | Cada ator do diagrama está ligado a pelo menos um caso de uso através um relacionamento associativo?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 05:17 | [João Pedro](https://github.com/JoosPerro) |
| 11  | As flechas tracejadas que representam <a id="TERM3" href="#term_anchor_3">inclusão e extensão</a> de casos de uso são diferenciadas pelos títulos “<<incluir\>\>” e “<<estender\>\>”, respectivamente?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 08:30 e 09:26 | [João Pedro](https://github.com/JoosPerro) |
| 12  | Estão anotadas, junto às extensões, as observações que descrevem as condições para que elas ocorram?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 12:08 | [João Pedro](https://github.com/JoosPerro) |
| 13  | Cada <a id="TERM3" href="#term_anchor_3">generalização</a> está representada com setas sólidas que apontam para caso de uso (ou ator) geral? | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 11:10 | [João Pedro](https://github.com/JoosPerro) |
| 14  | Casos de uso com <a id="TERM3" href="#term_anchor_3">pontos de extensão</a> são representados como ovais divididas ao meio (um lado com o título, o outro com os pontos de extensão)?  | <a id="REF1" href="#anchor_1">Vídeo 1</a>, a partir de 11:41 | [João Pedro](https://github.com/JoosPerro) |
| 15  | O <a id="TERM3" href="#term_anchor_3">fluxo básico</a> é denotado quando múltiplos fluxos são possíveis?  | <a id="REF2" href="#anchor_2">Caso de Uso ─ Fluxo Alternativo</a> | [João Pedro](https://github.com/JoosPerro) |

</center>

> - <a id="term_anchor_1" href="#TERM1">**Ator**</a>: são entidades externas que interagem com o sistema modelado. Podem ser outros sistemas, pessoas, organizações, etc.
</br>
- <a id="term_anchor_2" href="#TERM2">**Caso de Uso**</a>: são tarefas realizadas por atores, cuja execução deve ser apoiada por funcionalidades contidas no sistema
</br>
- <a id="term_anchor_3" href="#TERM3">**Relacionamento**</a>: são as interações que um elemento do diagrama possui com outros elementos. Os tipos de relacionamentos são:
    - **Associação**: é uma interação entre um ator e uma tarefa que é realizada por ele
    - **Inclusão**: indica dependência entre casos de uso. Sempre que o *caso de uso base* é executado, o *caso de uso incluso* é executado como parte dele
    - **Extensão**: indica um *caso de uso base* que *pode* implicar na execução de outro caso de uso, chamado *estendido*, se cumpridas certas condições. **Pontos de extensão** podem ser informados para o caso de uso base quando ele possuir múltiplos casos de uso estendidos, a fim de especificar os caminhos alternativos
    - **Generalização**: estabelece um caso de teste geral, ou primário, e caso(s) de teste específico(s), ou secundário(s), que herdam todas as características do caso base, e ainda podem ter outras características distintas
</br>
- <a id="term_anchor_4" href="#TERM4">**Fluxo**</a>: é o caminho tomado pelo sistema, desde a ação de um ator, passando por casos de uso conectados por relacionamentos. O **fluxo básico** é o caminho esperado mais comum de ser tomado, geralmente composto por relacionamentos de inclusão. Um **fluxo alternativo** é um fluxo esperado diferente do fluxo básico, e geralmente são denotados por relacionamentos de extensão. Um **fluxo de exceção** é um fluxo que indica um erro ou um estado indesejado/inesperado, mas que foi previsto por ser possível de ocorrer.
</br>

<center>

**Tabela 2** ─ Especificação Suplementar

| ID  | Descrição | Fonte | Autor |
| :-: | :-------- | :---- | :---: |
| 16  | A especificação apresenta os Requisitos Não-Funcionais no modelo FURPS (Funcionalidade, Usabilidade, Confiabilidade (Reliability), Desempenho (Performance) e Suportabilidade)? | <a id="REF3" href="#anchor_3">Modelo de Especificação Suplementar</a> | [João Pedro](https://github.com/JoosPerro) |

**Tabela 3** ─ Cenários

| ID  | Descrição | Fonte | Autor |
| :-: | :-------- | :---- | :---: |
|  | O cenário descreve uma situação de uso do sistema estudado? | <a id="REF4" href="#anchor_4">Livro de IHC e UX</a> | [João Pedro](https://github.com/JoosPerro) |
|  | O cenário possui título? | <a id="REF5" href="#anchor_5">Livro de IHC e UX</a> | [João Pedro](https://github.com/JoosPerro) |
|  | O cenário descreve o ambiente em que se passa o cenário? | <a id="REF6" href="#anchor_6">Livro de IHC e UX</a> | [João Pedro](https://github.com/JoosPerro) |
|  | O cenário descreve o(s) ator(es) envolvidos e seus <a id="TERM5" href="#term_anchor_5">objetivos</a>? | <a id="REF7" href="#anchor_7">Livro de IHC e UX</a> | [João Pedro](https://github.com/JoosPerro) |
|  | O cenário descreve o <a id="TERM6" href="#term_anchor_6">planejamento</a> de cada ator | <a id="REF8" href="#anchor_8">Livro de IHC e UX</a> | [João Pedro](https://github.com/JoosPerro) |
|  | O cenário descreve a <a id="TERM7" href="#term_anchor_7">avaliação</a> do ator às situações experienciadas? | <a id="REF8" href="#anchor_8">Livro de IHC e UX</a> | [João Pedro](https://github.com/JoosPerro) |

> - <a id="term_anchor_5" href="#TERM5">**Objetivo**</a>: é o efeito desejado, é o que motiva o usuário a tomar uma atitude (que pode não se limitar à interação com o sistema em questão)
> - <a id="term_anchor_5" href="#TERM5">**Planejamento**</a>: é a atividade mental do ator para determinar a sequência ações que cumprem seu objetivo
> - <a id="#term_anchor_6" href="TERM6">**Avaliação**</a>: é a atividade mental do ator para interpretar a situação

**Tabela 4** ─ Léxico

| ID  | Descrição | Fonte | Autor |
| :-: | :-------- | :---- | :---: |

</center>  

# Evidências

<center>

<a id="anchor_1" href="#REF1">**Vídeo 1** ─ Diagrama de Caso de Uso </a><br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/ab6eDdwS3rA?si=8vzvkAbjoGo7eEGu" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; web-share" allowfullscreen></iframe>

Fonte: [Lucid Software Português](https://www.youtube.com/@lucid_software_portugues)

---

<a id="anchor_2" href="#REF2">**Imagem 2** ─ Fluxo Alternativo de Caso de Uso</a><br>

![Fluxo Alternativo](../referencias/entr3-fluxo-altern.png)

Fonte: [Até o Momento](https://www.ateomomento.com.br/caso-de-uso-fluxo-alternativo/)

---

<a id="anchor_3" href="#REF3">**Imagem 3** ─ Modelo FURPS na Especificação Suplementar </a><br>

![FURPS](../referencias/entr3-furps.png)

Fonte: [MCTIC](https://pdp.mctic.gov.br/MCTI-PDP/guidances/examples/Especificacao%20Suplementar_4C68A4F4.html)

---

<a id="anchor_4" href="#REF4">**Imagem 4** ─ </a><br>

![a](../referencias/a.png)

Fonte: [a]()

---

<a id="anchor_5" href="#REF5">**Imagem 5** ─ </a><br>

![a](../referencias/a.png)

Fonte: [a]()

---

<a id="anchor_6" href="#REF6">**Imagem 6** ─ </a><br>

![a](../referencias/a.png)

Fonte: [a]()

---

<a id="anchor_7" href="#REF7">**Imagem 7** ─ </a><br>

![a](../referencias/a.png)

Fonte: [a]()

---

<a id="anchor_8" href="#REF8">**Imagem 8** ─ </a><br>

![a](../referencias/a.png)

Fonte: [a]()

</center>

## 📚 Referências Bibliográficas

> 1. Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. Interação Humano-Computador e Experiência do usuário. Autopublicação. 2021. 172-177. ISBN: 978-65-00-19677-1.

## 📑 Histórico de versão

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão |
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação do documento  | [João Pedro](https://github.com/JoosPerro) | 06/12/2024 |  |  |
