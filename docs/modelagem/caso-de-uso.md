# Casos de Uso

## Introdução

O Meu SUS Digital é uma plataforma oficial do Ministério da Saúde do Brasil que centraliza informações e serviços relacionados à saúde dos cidadãos. Por meio do site, os usuários podem acessar dados como histórico de atendimentos, vacinas aplicadas, exames realizados e outras informações de saúde. Além disso, a ferramenta busca facilitar o acesso a serviços de saúde e promover a digitalização e integração de informações no Sistema Único de Saúde (SUS).



## Metodologia

O diagrama de caso de uso é uma ferramenta visual que destaca as interações entre usuários e sistemas, como o site Meu SUS Digital, identificando funcionalidades principais como acesso ao histórico de saúde, consulta de vacinas e agendamento de serviços. Ele mapeia as principais funcionalidades do sistema, considerando as interações mais relevantes entre os usuários, como cidadãos e profissionais da saúde, e o site. Dessa forma, o diagrama auxilia na compreensão do funcionamento do sistema e na identificação de suas principais demandas.

<div align="center">
    <p><strong>Tabela 1 – Elementos do Diagrama de Casos de Uso</strong></p>
</div>

<center>

| Nome | Função | Elemento |
| :--: | ------ | :------: |
| Ator | Representam os diferentes tipos de usuários externos que interagem com o sistema | <figure class="usecaseElement" style="width: 20%; display: flex;">![actor](../imagens/actor.png)</figure> |
| Elipse<br>(Caso de Uso) | É usada para representar os casos de uso no diagrama. Um caso de uso descreve uma funcionalidade ou uma ação específica que o sistema pode realizar em resposta às interações dos atores. A elipse contém o nome do caso de uso | <figure class="usecaseElement" style="width: 40%; display: flex;">![elipse](../imagens/elipse.png)</figure> |
| Retângulo<br>(Sistema) | Usado para representar o sistema ou o bloco em análise. Ele envolve os casos de uso e atores relacionados | <figure class="usecaseElement" style="width: 40%; display: flex;">![retangulo](../imagens/retangulo.png)</figure> |
| Flecha<br>(Relações) | As flechas são usadas para representar as relações ou interações entre atores e casos de uso | <figure class="usecaseElement" style="width: 40%; display: flex;">![flechas](../imagens/flecha.png)</figure> |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
</div>

Além disso, no diagrama de casos de uso é possível especificar:

- Os requisitos externos de um sistema, ou seja, as funcionalidades necessárias que o sistema deve oferecer para atender às necessidades dos usuários.
- As funcionalidades disponíveis no sistema, ou seja, o que o sistema é capaz de fazer para satisfazer as necessidades dos usuários.
- Os requisitos impostos pelo sistema ao ambiente em que está inserido, definindo como o sistema interage com o ambiente para realizar suas funções.



## Diagrama de Casos de Uso

A **Figura 1** demonstra o diagrama de casos de uso do aplicativo Meu SUS Digital.

<div align="center">
    <p><strong>Figura 1 – Diagrama de Casos de Uso do Meu SUS Digital</strong></p>
</div>

<center>
 
<iframe frameborder="0" style="width:100%;height:1133px;" src="https://viewer.diagrams.net/?lightbox=1&highlight=0000ff&nav=1&title=use_case_dgram_-_Meus_SUS_Digital.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1P9X_m5Oynit55smT7AyenBk_km27mKQ4%26export%3Ddownload"></iframe>

</center>

<div align="center">
    <p>Autor: <a href=""></a>.</p>
</div>



## Especificação de Casos de Uso

As tabelas de 2 a 9 mostram a especificação dos casos de uso.

<div align="center">
    <p><strong>Tabela 2 – Histórico pré pandemia</strong></p>
</div>

<center>

| **UC02** | **Informações** |
| ------- | ------------- |
| Descrição | O paciente é capaz de visualizar seu histórico de vacinação antes da pandemia (pré 2020) |
| Ator | Paciente |
| Pré-condições | <ul><li> O paciente deverá estar conectado à Internet. </li> <li> O paciente deverá ter feito autenticação no sistema. </li></ul> |
| Ação | O paciente vai acessar seu histórico de vacinação |
| Fluxo principal |  <ul><li> O paciente acessa o aplicativo. <ul><li> O paciente seleciona a opção "Vacinas" na página inicial. <ul><li> Dentro da aba "Histórico de Vacinas" o  paciente visualiza seu histórico de vacinação. <ul><li> O paciente seleciona a opção "Mais Detalhes". <ul><li> O aplicativo disponibiliza mais detalhes da vacina. </li></ul> </li></ul> </li></ul> </li></ul> </li></ul> |
| Fluxo alternativo | <ul><li> O paciente acessa o aplicativo. <ul><li> O paciente seleciona a opção "Vacinas" na página inicial. <ul><li> O paciente seleciona "Suas vacinas". <ul><li> O aplicativo exibe o histórico de vacinação completo. </li></ul> </li></ul> </li></ul> </li></ul>  |
| Fluxo de exceção | 1. O paciente não possui vacinas registradas. <ul><li> O paciente acessa a opção "Vacinas", mas não há registros no sistema. <ul><li> O sistema exibe uma mensagem informando que não há vacinas registradas. </li></ul> </li></ul> 2. Erro na atualização do histórico de vacinação. <ul><li> O sistema não consegue recuperar o histórico de vacinação do paciente devido a uma falha técnica. <ul><li> O sistema exibe uma mensagem informando que o histórico de vacinação não esta disponível no momento. </li></ul> </li></ul>  </li></ul> |
| Pós-condições | O histórico de vacinação completo é exibido ao paciente |
| Data de Criação | 08/12/2024 |
| Rastreabilidade | [RF69](../elicitacao/requisitos-elicitados.md/#requisitos) |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
</div>

---

<div align="center">
    <p><strong>Tabela 3 – Consultar receitas médicas</strong></p>
</div>

<center>

| **UC03** | **Informações** |
| ------- | ------------- |
| Descrição | O paciente é capaz de consultar uma receita médica no aplicativo. |
| Ator | Paciente |
| Pré-condições | <ul><li> O paciente deverá estar conectado à Internet. </li> <li> O paciente deverá ter feito autenticação no sistema. </li></ul> |
| Ação | O paciente buscará sua receita médica no aplicativo. |
| Fluxo principal | <ul><li> O paciente acessa o aplicativo. <ul><li> O paciente seleciona a opção "Consultar receitas médicas". <ul><li> O aplicativo exibe o histórico de receitas médicas. <ul><li> O paciente seleciona uma receita na lista. <ul><li> O aplicativo exibe a receita médica. </li></ul> </li></ul> </li></ul> </li></ul> </li></ul> |
| Fluxo alternativo | 1. O paciente busca por uma receita específica. <ul><li> Em vez de navegar pela lista completa, o paciente busca por uma receita médica através da função "Buscar". <ul><li> O aplicativo exibe o resultado da busca. </li></ul> </li></ul> 2. O paciente solicita o <em>download</em> ou compartilhamento da receita. <ul><li> O paciente seleciona uma receita na lista. <ul><li> O paciente seleciona a opção "Baixar" ou "Compartilhar". <ul><li> O sistema gera o arquivo PDF da receita. <ul><li> O paciente baixa o arquivo ou escolhe um aplicativo para compartilhar (e-mail, <em>WhatsApp</em>, etc.). </li></ul> </li></ul> </li></ul> </li></ul> |
| Fluxo de exceção | 1. Não há receitas médicas disponíveis. <ul><li> O paciente seleciona a opção "Consultar receitas médicas". <ul><li> O aplicativo exibe uma mensagem informando que não há receitas disponíveis. </li></ul> </li></ul> 2. Falha na conexão com o sistema. <ul><li> O sistema exibe uma mensagem informando que não foi possível realizar a operação devido a problemas na conexão. |
| Pós-condições | A receita médica é exibida ao paciente. |
| Data de Criação | 06/12/2024 |
| Rastreabilidade | [RF71](../elicitacao/requisitos-elicitados.md/#requisitos) |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>

---

<div align="center">
    <p><strong>Tabela 4 – Fazer pedido de medicamento</strong></p>
</div>

<center>

| **UC04** | **Informações** |
| ------- | ------------- |
| Descrição | O paciente é capaz de fazer pedido de medicamento pelo aplicativo. |
| Ator | Paciente |
| Pré-condições | <ul><li> O paciente deverá estar conectado à Internet. </li> <li> O paciente deverá ter feito autenticação no sistema. </li></ul> |
| Ação | O paciente fará um pedido de medicamento. |
| Fluxo principal | <ul><li> O paciente acessa o aplicativo. <ul><li> O paciente seleciona a opção "Fazer pedido de medicamento". <ul><li> O sistema exibe as receitas médicas disponíveis. <ul><li> O paciente escolhe uma receita médica. <ul><li> O sistema exibe a lista de medicamentos dessa receita. <ul><li> O paciente seleciona os medicamentos desejados e confirma o pedido. <ul><li> O sistema registra o pedido. </li></ul> </li></ul> </li></ul> </li></ul> </li></ul> </li></ul> </li></ul> |
| Fluxo alternativo | 1. Primeiro pedido. <ul><li> O paciente acessa o aplicativo pela primeira vez. <ul><li> O paciente seleciona a opção "Fazer pedido de medicamento". <ul><li> O aplicativo solicita que o paciente escolha a farmácia e a forma de entrega de medicamento. <ul><li> O paciente informa a sua preferência. <ul><li> O fluxo retorna ao passo 3 do fluxo principal. </li></ul> </li></ul> </li></ul> </li></ul> </li></ul> 2. Ativar notificação. <ul><li> Após confirmar o pedido, o paciente ativa a opção de notificações. <ul><li> O sistema confirma a ativação e notifica o paciente automaticamente em cada mudança de status. </li></ul> </li></ul> |
| Fluxo de exceção | 1. Não há receitas médicas disponíveis. <ul><li> O paciente seleciona a opção "Fazer pedido de medicamento". <ul><li> O aplicativo exibe uma mensagem informando que não há receitas disponíveis. </li></ul> </li></ul> 2. Medicamento não disponível no sistema. <ul><li> O paciente seleciona os medicamentos desejados e confirma o pedido. <ul><li> O sistema exibe uma mensagem informando a indisponibilidade do(s) medicamento(s). <ul><li> O paciente prossegue com o pedido dos medicamentos restantes ou aguarda reposição. </li></ul> </li></ul> </li></ul> 3. Falha na conexão com o sistema. <ul><li> O sistema exibe uma mensagem informando que não foi possível realizar a operação devido a problemas na conexão. |
| Pós-condições | O pedido foi registrado. |
| Data de Criação | 06/12/2024 |
| Rastreabilidade | [RF67](../elicitacao/requisitos-elicitados.md/#requisitos) |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>

---

<div align="center">
    <p><strong>Tabela 5 – Consultar pedido de medicamento</strong></p>
</div>

<center>

| **UC05** | **Informações** |
| ------- | ------------- |
| Descrição | O paciente é capaz de acompanhar um pedido de medicamento pelo aplicativo. |
| Ator | Paciente |
| Pré-condições | <ul><li> O paciente deverá estar conectado à Internet. </li> <li> O paciente deverá ter feito autenticação no sistema. </li></ul> |
| Ação | O paciente verifica o andamento do pedido de medicamento. |
| Fluxo principal | <ul><li> O paciente acessa o aplicativo. <ul><li> O paciente seleciona a opção "Acompanhar pedidos". <ul><li> O sistema exibe a lista de pedidos de medicamentos realizados pelo paciente, com os respectivos <em>status</em> (ex.: "Em processamento", "A caminho", "Entregue"). <ul><li> O paciente seleciona um pedido. <ul><li> O sistema exibe os detalhes do pedido, incluindo: <br> - Medicamentos solicitados; <br> - Previsão de entrega/retirada; <br> - Local de retirada (se aplicável); <br> - <em>Status</em> atual e histórico de movimentações. </li></ul> </li></ul> </li></ul> </li></ul> </li></ul> |
| Fluxo alternativo | 1. Refinar o resultado. <ul><li> O paciente aplica filtros, como status ("Em processamento", "Entregue") ou período de realização do pedido. <ul><li> O sistema exibe a lista de pedidos que atendem aos critérios informados. <ul><li> O fluxo retorna ao passo 4 do fluxo principal. </li></ul> </li></ul> </li></ul> |
| Fluxo de exceção | 1. O paciente não possui pedidos registrados. <ul><li> O paciente acessa a opção "Acompanhar pedidos", mas não há registros no sistema. <ul><li> O sistema exibe uma mensagem informando que não há pedidos registrados. </li></ul> </li></ul> 2. Erro na atualização do <em>status</em> do pedido. <ul><li> O sistema não consegue recuperar o status do pedido devido a uma falha técnica. <ul><li> O sistema exibe uma mensagem informando que os detalhes do pedido não estão disponíveis no momento. </li></ul> </li></ul> 3. Pedido cancelado ou inválido. <ul><li> O paciente tenta acessar um pedido que foi cancelado ou não é mais válido. <ul><li> O sistema exibe uma mensagem informando que o pedido foi cancelado ou não está disponível. </li></ul> </li></ul> |
| Pós-condições | O pedido é exibido. |
| Data de Criação | 06/12/2024 |
| Rastreabilidade | [RF62](../elicitacao/requisitos-elicitados.md/#requisitos) |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>

---

<div align="center">
    <p><strong>Tabela 6 – Agendamentos</strong></p>
</div>


<center>

| **UC06** | **Informações** |
| ------- | ------------- |
| **Descrição** | O paciente pode agendar consultas médicas de forma online pelo sistema Meu SUS Digital. |
| **Ator** | Paciente |
| **Pré-condições** | <ul><li> O paciente deve estar autenticado no sistema por meio de login no Gov.br. </li><li> O paciente deve estar conectado à Internet. </li></ul> |
| **Ação** | O paciente realiza o agendamento de uma consulta médica. |
| **Fluxo principal** | <ul><li> O paciente acessa o sistema Meu SUS Digital. <ul><li> O paciente seleciona a opção "Agendamentos". <ul><li> O paciente escolhe a especialidade médica desejada. <ul><li> O sistema exibe as datas e horários disponíveis. <ul><li> O paciente seleciona uma data e horário. <ul><li> O sistema confirma o agendamento. </li></ul></li></ul></li></ul></li></ul></li></ul></li></ul> |
| **Fluxo alternativo** | <ul><li> O paciente acessa o sistema Meu SUS Digital. <ul><li> O paciente seleciona a opção "Agendamentos". <ul><li> O sistema exibe uma lista de consultas disponíveis próximas à localização do paciente. <ul><li> O paciente escolhe uma consulta disponível. <ul><li> O sistema confirma o agendamento. </li></ul></li></ul></li></ul></li></ul></li></ul> |
| **Fluxo de exceção** | 1. O paciente não encontra horários disponíveis: <ul><li> O sistema informa que não há horários disponíveis para a especialidade escolhida. </li></ul> 2. Falha técnica no sistema: <ul><li> O sistema exibe uma mensagem informando que não foi possível realizar o agendamento no momento. </li></ul> |
| **Pós-condições** | O agendamento da consulta médica é registrado no sistema e o paciente recebe uma confirmação. |
| **Data de Criação** | 08/12/2024 |
| **Rastreabilidade** | [RF02](../elicitacao/requisitos-elicitados.md/#requisitos) |

</center>


<div align="center">
    <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
</div>
---


<div align="center">
    <p><strong>Tabela 7 – Exportar Carteira Nacional de Vacinação Digital</strong></p>
</div>

<center>

| **UC07**              | **Informações** |
| --------------------- | --------------- |
| **Descrição**         | O aplicativo deve permitir que o usuário exporte ou realize o download do documento referente à sua Carteira Nacional de Vacinação Digital. |
| **Ator**              | Usuário (paciente cadastrado no aplicativo). |
| **Pré-condições**     | <li> O usuário deve estar autenticado no aplicativo (login realizado com sucesso via conta Gov.br). </li> <li> O sistema deve conter a Carteira Nacional de Vacinação Digital atualizada para o usuário. </li> |
| **Ação**              | O usuário exporta ou realiza o download do documento referente à Carteira Nacional de Vacinação Digital. |
| **Fluxo principal**   | <li> O usuário acessa o menu principal do aplicativo e seleciona a opção "Vacinas". <ul><li> O sistema exibe diversas opções, como "Ajuda", "Documentos", "Histórico de vacinas", entre outras. <ul><li> O usuário seleciona a opção "Documentos". <ul><li> O usuário seleciona a opção "Suas vacinas". <ul><li> O usuário seleciona a opção "Exportar documento". <ul><li> O sistema gera o arquivo correspondente e o disponibiliza para o exportação/download no dispositivo do usuário. </li> </li></ul> </li></ul> </li></ul> </li></ul> </li></ul> |
| **Fluxo alternativo** | <li> O usuário acessa o menu principal do aplicativo e seleciona a opção "Vacinas". <ul><li> O sistema exibe, entre diversas outras, a opção "Acesse sua Carteira Nacional de Vacinação". <ul><li> O usuário seleciona a opção "Acessar", em "Acesse sua Carteira Nacional de Vacinação". <ul><li> O sistema gera o arquivo correspondente e o disponibiliza para o exportação/download no dispositivo do usuário. </li> </li></ul> </li></ul> </li></ul> </li></ul> </li></ul> <li> Não há Carteira Nacional de Vacinação Digital associada ao usuário. <ul><li> O sistema exibe uma mensagem informando que não há documento disponível para exportação/download. </li> </li></ul> <li> Ocorre uma falha no download do arquivo. <ul><li> O sistema exibe uma mensagem de erro e orienta o usuário a tentar novamente mais tarde. </li> </li></ul> |
| **Fluxo de exceção**  | Não aplicável. |
| **Pós-condições**     | 1. O usuário obtém uma cópia do documento referente à Carteira Nacional de Vacinação Digital. <br></br> 2. Nenhuma alteração nos dados do sistema ocorre durante este processo. |
| **Data de Criação**   | 07/12/2024 |
| **Rastreabilidade**   | [RF5](../elicitacao/requisitos-elicitados.md/#RF5) |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>

---

<div align="center">
    <p><strong>Tabela 8 – Exportar Certificado de vacinação nacional de Covid-19</strong></p>
</div>

<center>

| **UC08**              | **Informações** |
| --------------------- | --------------- |
| **Descrição**         | O aplicativo deve permitir que o usuário exporte ou realize o download do documento referente ao Certificado de vacinação nacional de Covid-19. |
| **Ator**              | Usuário (paciente cadastrado no aplicativo). |
| **Pré-condições**     | <li> O usuário deve estar autenticado no aplicativo (login realizado com sucesso via conta Gov.br). </li> <li> O sistema deve conter o Certificado de vacinação nacional de Covid-19 atualizado para o usuário. </li> |
| **Ação**              | O usuário exporta ou realiza o download do documento referente ao Certificado de vacinação nacional de Covid-19. |
| **Fluxo principal**   | <li> O usuário acessa o menu principal do aplicativo e seleciona a opção "Vacinas". <ul><li> O sistema exibe diversas opções, como "Ajuda", "Documentos", "Histórico de vacinas", entre outras. <ul><li> O usuário seleciona a opção "Documentos". <ul><li> O usuário seleciona a opção "Suas vacinas de Covid-19". <ul><li> O usuário seleciona a opção "Exportar documento". <ul><li> O sistema gera o arquivo correspondente e o disponibiliza para o exportação/download no dispositivo do usuário. </li> </li></ul> </li></ul> </li></ul> </li></ul> </li></ul> |
| **Fluxo alternativo** | <li> Não há Certificado de vacinação nacional de Covid-19 associada ao usuário. <ul><li> O sistema exibe uma mensagem informando que não há documento disponível para exportação/download. </li> </li></ul> <li> Ocorre uma falha no download do arquivo. <ul><li> O sistema exibe uma mensagem de erro e orienta o usuário a tentar novamente mais tarde. </li> </li></ul> |
| **Fluxo de exceção**  | Não aplicável. |
| **Pós-condições**     | 1. O usuário obtém uma cópia do documento referente ao Certificado de vacinação nacional de Covid-19. <br></br> 2. Nenhuma alteração nos dados do sistema ocorre durante este processo. |
| **Data de Criação**   | 07/12/2024 |
| **Rastreabilidade**   | [RF5](../elicitacao/requisitos-elicitados.md/#RF5) |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>

---

<div align="center">
    <p><strong>Tabela 9 – Visualizar histórico de vacinas</strong></p>
</div>

<center>

| **UC09**              | **Informações** |
| --------------------- | --------------- |
| **Descrição**         | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de vacinas. |
| **Ator**              | Usuário (paciente cadastrado no aplicativo). |
| **Pré-condições**     | <ul><li> O usuário deve estar autenticado no aplicativo (login realizado com sucesso via conta Gov.br). </ul></li> <ul><li> O sistema deve conter registros de vacinas para o usuário. </ul></li> |
| **Ação**              | O usuário acessa o histórico de vacinas. |
| **Fluxo principal**   | <li> O usuário acessa o menu principal do aplicativo e seleciona a opção "Vacinas". <ul><li> O sistema exibe diversas opções, como "Ajuda", "Documentos", "Histórico de vacinas", entre outras. <ul><li> O usuário seleciona a opção "Histórico de vacinas". <ul><li> O sistema exibe uma lista ou histórico com os registros de vacinação associados ao usuário. <ul><li> Em "Mais detalhes", o usuário pode selecionar um registro específico para visualizar detalhes, como data, local de aplicação, fabricante, entre outros. </li></ul> </li></ul> </li></ul> </li></ul> </li> |
| **Fluxo alternativo** | <li> Não há registros de vacinas para o usuário. <ul><li> O sistema exibe uma mensagem informando que não há vacinas registradas. </li></ul> </li> <li> Ocorre uma falha na conexão com o servidor. <ul><li> O sistema exibe uma mensagem de erro e orienta o usuário a tentar novamente mais tarde. </li></ul> </li> |
| **Fluxo de exceção**  | Não aplicável. |
| **Pós-condições**     | 1. O usuário visualiza o histórico completo de vacinas (se disponível). <br></br> 2. Nenhuma alteração nos dados do sistema ocorre durante este processo. |
| **Data de Criação**   | 07/12/2024 |
| **Rastreabilidade**   | [RF6](../elicitacao/requisitos-elicitados.md/#RF6) |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>

---

## 📚 Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13. 2017. Apresentação de slides. Disponível em:[https://aprender3.unb.br/pluginfile.php/2972480/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf](https://aprender3.unb.br/pluginfile.php/2972480/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf). Acesso em: 4 dez. 2024.
>
> Casos de Uso. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: [https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/). Acesso em: 4 dez. 2024.

## 📑 Histórico de Versão

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão |  
| :----: | :-------: | :-------: | :--------------: | :---------: | :-------------: |
| `1.0`  | Criação do Documento. | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 05/11/2024 | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 07/12/2024 |
| `1.1`  | Adição da especificação de casos de uso da funcionalidade relacionada a medicamentos. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 07/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 07/12/2024 |
| `1.2`  | Adição da especificação de casos de uso da funcionalidade relacionada às vacinas. | [Artur Ricardo](https://github.com/algorithmorphic) | 07/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 08/12/2024 |
| `1.3`  | Atualização da especificação de casos de uso das funcionalidades relacionada às vacinas. | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 08/12/2024 |
| `1.4`  | Atualização da especificação de casos de uso das funcionalidades relacionada às vacinas. | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 08/12/2024 |
| `1.5`  | Atualização da especificação de casos de uso das funcionalidades relacionada às vacinas. | [Pedro Lopes](https://github.com/pLopess) | 08/12/2024 | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 08/12/2024 |
| `1.6`  | Atualização da especificação de casos de uso das funcionalidades Agendamento. | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 08/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 |
