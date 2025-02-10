# Avaliação Grupo 5

## Introdução

Conforme planejado, o Grupo 4 deve inspecionar os artefatos produzidos pelo [Grupo 5](https://github.com/Requisitos-de-Software/2024.2-TesouroDireto), visando feedback para o grupo sobre artefatos que não atendem às especificações propostas pelos colegas de turma.

## Objetivos

O objetivo deste documento é relatar os resultados da avaliação da 3ª etapa do projeto do [Grupo 5](https://github.com/Requisitos-de-Software/2024.2-TesouroDireto), em forma de inspeção. Será verificado se os artefatos produzidos nesta terceira etapa cumprem com as condições e padrões propostos pelo Grupo 4. É importante citar que essa verificação não tem como intuito diminuir os membros responsáveis por cada artefato ou seu trabalho, apenas aplicar os conceitos de verificação.

## Inspeção

A inspeção foi baseada na [lista de verificação da 3ª entrega](../../lista_verif/entrega3.md) produzida com a ajuda do professor e dos integrantes do Grupo 4.

### Tabela 1 ─ Resultado da Inspeção de Modelagem.

<center> 

**Tabela 1** – Resultados da Verificação de Modelagem: Cenários, Léxico, Caso de Uso e Especificação Suplementar


|        ID        | Descrição                                                                                                                                                                  | Avaliação   | Autor            | Data e Hora         |
| :--------------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | ----------------- | ------------------- |
| **Itens do desenvolvimentos do projeto** |                                                                                                                                                        |             |                   |                     |
|        1         | Todos os 9 itens       | - | André Barros      | -     |
| **Itens do conteúdo da disciplina** |                                                                                                                                                        |             |                   |                     |
|        1         | As especificações dos cenários para o projeto. <br> <a href="../referencias_png/especificacaocenarios.png" target="_blank">Exemplo de especificação dos cenários?</a> <a id="anchor_2" href="#REF2"><sup>2</sup></a>       | Sim | André Barros      | 09/12/2024 20:25      |
|        2         | Os cenários possuem os elementos básicos de um cenário (Título, Metas/Objetivo, Contexto, Atores, Recursos, Exceção e Episódios). <br> <a href="../referencias_png/elementoscenarios.png" target="_blank">Quais elementos dos cenários?</a> <a id="anchor_2" href="#REF2"><sup>2</sup></a>     | Sim | André Barros      |  09/12/2024 20:25     |
|        3         | As especificações dos léxicos. <br> <a href="../referencias_png/oqsaolexicos.png" target="_blank">O que são léxicos?</a> <a id="anchor_1" href="#REF1"><sup>1</sup></a>                                          | Sim | André Barros      | 09/12/2024 20:25   |
|        4         | A definição do usuário nos léxicos.                                                                                                                                        | Sim | André Barros      | 09/12/2024 20:25  |
|        5         | Os léxicos possuem ligações entre si (hiperlinks).                                                                                                                         | Incompleto, existe a referência mas a ancoragem não funciona | André Barros      |  09/12/2024 20:25  |
|        6         | Os léxicos utilizam a estrutura de dicionário (verbo, objeto, estado). <br> <a href="../referencias_png/tiposlexicos.png" target="_blank">O que é o dicionário dos léxicos?</a><a id="anchor_1" href="#REF1"><sup>1</sup></a>       | Sim | André Barros      | 09/12/2024 20:25       |
|        7         | A especificação do caso de uso.                                                                                                                                             | Sim | André Barros      |    09/12/2024 20:25    |
|        8         | Os atores principais e secundários no diagrama de caso de uso. <br> <a id="anchor_1" href="#REF1">1 [min. 3:27]</a>.                            |Sim | André Barros      | 09/12/2024 20:25        |
|        9         | O ator principal está do lado esquerdo do sistema no diagrama de caso de uso. <br> <a id="anchor_1" href="#REF1">1 [min. 3:57]</a>             | Sim | André Barros      | 09/12/2024 20:25    |
|       10         | Os atores estão fora da caixa de limite do sistema no diagrama de caso de uso. <br> <a id="anchor_1" href="#REF1">1 [min. 2:55]</a>            | Sim | André Barros      | 09/12/2024 20:25      |
|       11         | A especificação do diagrama de caso de uso (com Nome, Descrição, Atores, Pré-Condição, Pós-Condição, Fluxo Principal, Fluxo Alternativo e Fluxo de Exceção etc.).           | Sim | André Barros      | 09/12/2024 20:25    |
|       12         | No diagrama de caso de uso há ao menos um caso de uso com pontos de extensão? <br> <a id="anchor_1" href="#REF1">1 [min. 8:35]</a>   | Não | André Barros      | 09/12/2024 20:25    |
|       13         | A participação do cliente e/ou persona na validação do diagrama de caso de uso.                                                                                            | Sim | André Barros      | 09/12/2024 20:25    |
|       14         | A especificação suplementar. <br> <a href="../referencias_png/oqesuplementar.png" target="_blank">O que é especificação suplementar?</a> <a id="anchor_2" href="#REF2"><sup>2</sup></a>                                      | Sim | André Barros      | 09/12/2024 20:25  |
|       15         | O artefato segue o modelo FURPS+.                                                                                                                                          | Sim | André Barros      | 09/12/2024 20:25   |
|       16         | O documento especifica o tempo de resposta, no desempenho?                                                                                                                 | Sim | André Barros      | 09/12/2024 20:25    |
|       17         | O documento especifica qual plataforma o aplicativo pode ser executado?                                                                                                    | Sim | André Barros      | 09/12/2024 20:25    |
|       18         | Todos os requisitos podem ser testados (RF e RNF)? <br> **Identificar quais requisitos não são testáveis/verificáveis.**                                                    | Não, RNF04 | André Barros      |  09/12/2024 20:25   |
|       **Itens desenvolvidos pelo grupo**          |   |  |  |  |
|       P1         |  O diagrama representa o sistema, que é o software modelado, como um retângulo intitulado pelo nome do sistema?          | Sim | Pedro Lopes | 09/12/2024 20:25    |
|       P2         | São especificadas respostas para situações anormais, como recuperação de erros?                        | Sim | João Pedro      |   09/12/2024 20:25      |
|       P3         |  Estão anotadas, junto às extensões, as observações que descrevem as condições para que elas ocorram? | Não | Emivalto Junior      |  09/12/2024 20:25      |
|       P4         |  O cenário descreve uma situação concreta de uso do sistema? | Incompleto, faltou uma descrição maior| Artur Ricardo      |  09/12/2024 20:25   |
|       P5         |      Cada símbolo é caracterizado por um, e apenas um, dos seguintes tipos: sujeito, verbo, objeto ou estado?         | Sim | Matheus Henrick      | 09/12/2024 20:25      |

Autores: [Pedro Lopes](https://github.com/pLopess), [Emivalto Júnior](https://github.com/EmivaltoJrr), [João Pedro](https://github.com/JoosPerro), [Artur Ricardo](https://github.com/algorithmorphic), [Matheus Henrick](https://github.com/MatheusHenrickSantos) e André Barros

</center>

<center>
## Gravação da Inspeção do Grupo 5
</center>

<center>
  
<iframe width="560" height="315" src="https://www.youtube.com/embed/8DTOlmgPkP0?si=973rMKDJQon2Rm7p" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
_Autor: Pedro Lopes_

</center>

## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação do documento. | [Pedro Lopes](https://github.com/pLopess) | 09/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 17/12/2024 |
