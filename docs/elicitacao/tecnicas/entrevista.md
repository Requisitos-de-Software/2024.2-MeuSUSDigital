# Entrevista

## Introdução

A técnica de entrevista é uma das formas de obtenção de dados e requisitos que envolvem a participação de um entrevistado, um indivíduo que utiliza ou poderá utilizar o sistema que está sendo estudado. A entrevista é uma conversa guiada por um roteiro <a href="#REF1">(BARBOSA, 2021)</a>. Esse roteiro é composto por tópicos ou perguntas motivadoras para a coleta de dados.

A entrevista conduzida e relatada neste documento foi conduzida por um roteiro de perguntas abertas, com caráter exploratório, objetivando obter conhecimento sobre o domínio da aplicação Meu SUS Digital. A entrevista também foi conduzida de maneira semiestruturada, ou seja, as perguntas não foram feitas necessariamente em ordem e o entrevistador teve a liberdade de fazer perguntas adicionais, a fim de se aprofundar em algum tópico que julgasse importante um conhecimento mais aprofundado.

## Planejamento

O planejamento geral da aplicação das técnicas empregadas pelo grupo pode ser visto no [cronograma de elicitação](../planejamento/cronograma-tecnicas.md).

O planejamento da entrevista envolveu a construção de um [roteiro](#roteiro) e a busca de usuários do Meu SUS Digital com disponibilidade para serem entrevistados. Dois usuários foram encontrados: Damácio, que foi entrevistado, e Verdiana, que devido a contratempos, não pôde ser entrevistada no período planejado.

### Roteiro

O roteiro que foi seguido começa com uma breve introdução para o entrevistado, que inclui: comunicação dos objetivos e motivações da entrevista, os tipos de informações buscadas, a quem estarão disponíveis, e declaração dos termos (como os direito de imagem e direitos de recusar-se a responder a alguma pergunta ou cancelar a entrevista caso desejado). As perguntas planejadas em roteiro foram:

1. Qual o seu nome?
2. Qual o seu grau de escolaridade?
3. Qual cargo você ocupa?
4. Quanta experiência você possui nesse cargo?
5. Você se sente a vontade de usar qualquer tipo de tecnologia? Tem receio no uso se alguma tecnologia?
6. Os serviços públicos de saúde são importantes você? Por quê?
7. Você prefere usar serviços de Saúde presencialmente ou virtualmente?
8. Você possui algum conhecimento do funcionamento SUS, seja profissionalmente ou por utilização dos seus serviços?
9. Quais serviços do SUS você utilizou?
10. Qual sua experiência com aparelhos eletrônicos?
11. Tem alguma preferência quanto à aparelhos eletrônicos?
12. Você conhece aplicativos/sistemas de saúde? Há quanto tempo você os utiliza? Em que aspectos eles são semelhantes ao Meu SUS Digital?
13. Por que o app Meu SUS Digital é útil pra você?
14. Que tipos de soluções ele te fornece? Existe alguma solução que ele não fornece ainda, mas que te ajudaria?

## Execução das Entrevistas

A execução da primeira entrevista foi realizada no local planejado, mas com um atraso, como pode ser visto na tabela abaixo e na gravação da entrevista. A segunda entrevista não foi realizada no dia e local planejados, devido à contratempos.

A segunda entrevista, diferente da primeira, considerou uma pequena interação da entrevistada com a interface do Meu SUS Digital, de forma que elucidace suas percepções sobre o app.

<div align="center">
    <p><strong>Tabela 1 – Execução das Entrevistas</strong></p>
</div>

| Técnica | Data | Horário | Ambiente/Local | Cliente/Persona | Responsável(eis) |
| ------- | :--: | :-----: | ----- | --------------- | ------------- |
| Entrevista | 22/11/2024 | 17:20 | Casa do entrevistado | Damácio | [João Pedro](https://github.com/JoosPerro) |
| Entrevista | 24/11/2024 | 14:00 | Casa do Damácio | Veridiana | [João Pedro](https://github.com/JoosPerro) |

<div align="center">
    <p>Autor: <a href="https://github.com/JoosPerro">João Pedro</a>.</p>
</div>

<div align="center">
    <p><strong>Vídeo 1 ─ Gravação da Entrevista com Damácio</strong></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/JCqsTKHLMBQ?si=b3hYLv9Tk_VGs_5k" frameborder="0" allowfullscreen></iframe>
    <p>Autor: <a href="https://github.com/JoosPerro">João Pedro</a>.</p>
</div>

<div align="center">
    <p><strong>Vídeo 2 ─ Gravação da Entrevista com Veridiana</strong></p>


<iframe width="560" height="315" src="https://www.youtube.com/embed/NaoBLobf0Bo?si=dDnX4-giqXhwFk96" frameborder="0" allowfullscreen></iframe>
    <p>Autor: <a href="https://github.com/JoosPerro">João Pedro</a>.</p>
</div>


## Requisitos Elicitados

A partir da revisão da entrevista, requisitos foram elicitados e documentados. Eles também serão classificados como funcionais (**RF**) ou não funcionais (**RNF**) e ordenados quanto à prioridade.

<div align="center">
    <p><strong>Tabela 2 – Requisitos Elicitados</strong></p>
</div>

<center>

| Tipo | Rastreamento | Descrição | Implementado |
| :-:  | :----------: | :-------: | :----------: |
| RNF  | <a id="EN01"></a>EN01 | A aplicação pode receber informações do usuário através de biosensores | Não |
| RF   | <a id="EN02"></a>EN02 | A aplicação permite agendar consultas | Não |
| RF   | <a id="EN03"></a>EN03 | A aplicação permite agendar exames | Não |
| RF   | <a id="EN04"></a>EN04 | a aplicação permite ao servidor solicitar licença saúde | Não |
| RF   | <a id="EN05"></a>EN05 | A aplicação permite acompanhar o andamento de solicitações (licença, medicamentos) | Não |
| RF   | <a id="EN06"></a>EN06 | A aplicação permite acompanhar a vacinação | Sim |
| RF   | <a id="EN07"></a>EN07 | A aplicação permite consultar pedidos de medicamento | Não |
| RF   | <a id="EN08"></a>EN08 | A aplicação permite consultar recebimentos de medicamento | Sim |
| RF   | <a id="EN09"></a>EN09 | A aplicação permite consultar os agendamentos de exames | Sim |
| RF   | <a id="EN10"></a>EN10 | A aplicação permite consultar os resultados de exames | Sim |
| RF   | <a id="EN11"></a>EN11 | A aplicação notifica o cancelamento de agentamentos | Não |
| RF   | <a id="EN12"></a>EN12 | A aplicação permite realizar pedidos de medicamento | Não |
| RF   | <a id="EN13"></a>EN13 | A aplicação permite ao paciente aplicar filtro de pesquisa ("Em processamento", "A caminho", "Entregue") para a consulta de pedidos de medicamento | Não |
| RNF  | <a id="EN14"></a>EN14 | O fluxo para solicitar medicamentos deve ser concluído em até 5 cliques/telas | Não |
| RNF  | <a id="EN15"></a>EN15 | A aplicação deve processar a solicitação de medicamentos e fornecer uma resposta em até 5 segundos | Não |
| RNF  | <a id="EN16"></a>EN16 | O resultado da consulta de pedidos de medicamento deve ser exibido em ordem cronológica | Não |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/JoosPerro">João Pedro</a>.</p>
</div>

## 📚 Referência Bibliográfica

> <a id="REF1"></a>BARBOSA, Simone *et al*. **Interação humano-computador e experiência do usuário**. 1ª Edição. Rio de Janeiro : Simone Diniz Junqueira Barbosa. 2021. p.144-148. ISBN: 978-65-00-19677-1.

## 📑 Histórico de Versões

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
| `1.0`  | Criação do Documento | [João Pedro](https://github.com/JoosPerro)| 23/11/2024   |[Emivalto Júnior](https://github.com/EmivaltoJrr) | 24/11/2024 |
| `1.1`  | Listagem de Requisitos | [João Pedro](https://github.com/JoosPerro)| 24/11/2024   |[Emivalto Júnior](https://github.com/EmivaltoJrr)  | 2/11/2024|
| `1.2`  | Adição da segunda entrevista | [João Pedro](https://github.com/JoosPerro)| 24/11/2024   |[Emivalto Júnior](https://github.com/EmivaltoJrr)  | 24/11/2024 |
| `1.3`  | Adição de novos requisitos | [Matheus Henrick](https://github.com/MatheusHenrickSantos)| 07/12/2024   | [João Pedro](https://github.com/JoosPerro) | 07/02/2025 |