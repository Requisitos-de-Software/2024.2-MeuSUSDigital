# Entrevista

## Introdução

A técnica de entrevista é uma das formas de obtenção de dados e requisitos que envolvem a participação de um entrevistado, um indivíduo que utiliza ou poderá utilizar o sistema que está sendo estudado. Segundo Barbosa, a entrevista é uma conversa guiada por um roteiro (Barbosa, 2021). Esse roteiro é composto por tópicos ou perguntas motivadoras para a coleta de dados.

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
    <p><strong>Vídeo 1 ─ Gravação da Entrevista</strong></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/JCqsTKHLMBQ?si=b3hYLv9Tk_VGs_5k" frameborder="0" allowfullscreen></iframe>
    <p><strong>Entrevista com Damácio<em></em></strong></p>
    <p>Autor: <a href="https://github.com/JoosPerro">João Pedro</a>.</p>
</div>

<div align="center">
    <p><strong>Vídeo 2 ─ Gravação da Entrevista</strong></p>


<iframe width="560" height="315" src="https://www.youtube.com/embed/NaoBLobf0Bo?si=dDnX4-giqXhwFk96" frameborder="0" allowfullscreen></iframe>
    <p><strong>Entrevista com Veridiana<em></em></strong></p>
    <p>Autor: <a href="https://github.com/JoosPerro">João Pedro</a>.</p>
</div>


## Requisitos Elicitados

A partir da revisão da entrevista, requisitos foram elicitados e documentados. Eles também serão classificados como funcionais (**RF**) ou não funcionais (**RNF**) e ordenados quanto à prioridade, utilizando a [análise de impacto](../priorizacao/analise-de-impacto.md).

### Requisitos Elicitados

<div align="center">
    <p><strong>Tabela 2 – Requisitos Elicitados</strong></p>
</div>

<center>

| Tipo | Rastreamento | Descrição | Implementado |
| :-:  | :----------: | :-------: | :----------: |
| RNF  | EN01 | A aplicação pode receber informações do usuário através de biosensores | Não |
| RF   | EN02 | A aplicação permite agendar consultas | Não |
| RF   | EN03 | A aplicação permite agendar exames | Não |
| RF   | EN04 | a aplicação permite ao servidor solicitar licença saúde | Não |
| RF   | EN05 | A aplicação permite acompanhar o andamento de solicitações (licensa, medicamentos) | Não |
| RF   | EN06 | A aplicação permite acompanhar a vacinação | Sim |
| RF   | EN07 | A aplicação permite consultar pedidos de medicamento | Não |
| RF   | EN08 | A aplicação permite consultar recebimentos de medicamento | Sim |
| RF   | EN09 | A aplicação permite consultar os agendamentos de exames | Sim |
| RF   | EN10 | A aplicação permite consultar os resultados de exames | Sim |
| RF   | EN11 | A aplicação notifica o cancelamento de agentamentos | Não |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/JoosPerro">João Pedro</a>.</p>
</div>

## 📚 Referência Bibliográfica

> BARBOSA, Simone *et al*. **Interação humano-computador e experiência do
usuário**. 1ª Edição. Rio de Janeiro : Simone Diniz Junqueira
Barbosa. 2021. ISBN: 978-65-00-19677-1.

> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.

## 📑 Histórico de Versões

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
| `1.0`  | Criação do Documento | [João Pedro](https://github.com/JoosPerro)| 23/11/2024   | |  |
| `1.1`  | Listagem de Requisitos | [João Pedro](https://github.com/JoosPerro)| 24/11/2024   | |  |
| `1.2`  | Adição da segunda entrevista | [João Pedro](https://github.com/JoosPerro)| 24/11/2024   | |  |
