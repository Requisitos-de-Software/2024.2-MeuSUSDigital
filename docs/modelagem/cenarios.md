# Cenários

## Introdução 


Os cenários são descrições detalhadas, geralmente em linguagem natural, que ilustram situações ou eventos envolvendo determinados atores. No contexto do site Meu SUS Digital, eles são úteis para analisar como os usuários interagem com a plataforma e como ela responde a diferentes situações. Esses cenários ajudam a compreender o funcionamento do sistema, seus comportamentos e fluxos em diversas situações práticas. As interações e funcionalidades analisadas estão organizadas nas tabelas de 1 a 5.


## Cenário 1

<div align="center">
    <p><strong>Tabela 1 – Exportar Carteira Nacional de Vacinação Digital</strong></p>
</div>

<center>

| **Campo**           | **Descrição** |
| ------------------- | ------------- |
| **Título**          | Exportar Carteira Nacional de Vacinação Digital |
| **Objetivo**        | Permitir que o usuário exporte ou realize o download do documento referente à sua Carteira Nacional de Vacinação Digital. |
| **Contexto**        | O usuário deseja obter um documento oficial referente à sua Carteira Nacional de Vacinação Digital para fins de comprovação. |
| **Atores**          | Usuário (paciente cadastrado no aplicativo). |
| **Recursos**        | Smartphone, aplicativo instalado e conta Gov.br autenticada. |
| **Episódios**       | <ul><li> O usuário acessa o menu principal do aplicativo e seleciona a opção "Vacinas". </li></ul> <ul><li> O sistema exibe diversas opções, como "Ajuda", "Documentos", "Histórico de vacinas", entre outras. </li></ul> <ul><li> O usuário seleciona a opção "Documentos". </li></ul> <ul><li> O usuário seleciona a opção "Suas vacinas". </li></ul> <ul><li> O usuário seleciona a opção "Exportar documento". </li></ul> <ul><li> O sistema gera o arquivo correspondente e o disponibiliza para exportação/download no dispositivo do usuário. </li></ul> |
| **Exceções**        | <ul><li> Não há Carteira Nacional de Vacinação Digital associada ao usuário. </li></ul> <ul><li> O sistema exibe uma mensagem informando que não há documento disponível. </li></ul> <ul><li> Ocorre uma falha no download do arquivo. </li></ul> <ul><li> O sistema exibe uma mensagem de erro e orienta o usuário a tentar novamente mais tarde. </li></ul> |
| **Data de Criação** | 08/12/2024 |
| **Rastreabilidade** | [RF5](../elicitacao/requisitos-elicitados.md/#RF5) |

</center>

---

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>



## Cenário 2

<div align="center">
    <p><strong>Tabela 2 – Exportação/Download de Certificado de Vacinação Nacional de Covid-19</strong></p>
</div>

<center>

| **Campo**           | **Descrição** |
| ------------------- | ------------- |
| **Título**          | Exportar Certificado de Vacinação Nacional de Covid-19 |
| **Objetivo**        | Permitir que o usuário exporte ou realize o download do documento referente ao Certificado de Vacinação Nacional de Covid-19. |
| **Contexto**        | O usuário deseja obter um documento oficial referente ao seu Certificado de Vacinação Nacional de Covid-19. |
| **Atores**          | Usuário (paciente cadastrado no aplicativo). |
| **Recursos**        | Smartphone, aplicativo instalado e conta Gov.br autenticada. |
| **Episódios**       | <ul><li> O usuário acessa o menu principal do aplicativo e seleciona a opção "Vacinas". </li></ul> <ul><li> O sistema exibe diversas opções, como "Ajuda", "Documentos", "Histórico de vacinas", entre outras. </li></ul> <ul><li> O usuário seleciona a opção "Documentos". </li></ul> <ul><li> O usuário seleciona a opção "Suas vacinas de Covid-19". </li></ul> <ul><li> O usuário seleciona a opção "Exportar documento". </li></ul> <ul><li> O sistema gera o arquivo correspondente e o disponibiliza para exportação/download no dispositivo do usuário. </li></ul> |
| **Exceções**        | <ul><li> Não há Certificado de Vacinação Nacional de Covid-19 associado ao usuário. </li></ul> <ul><li> O sistema exibe uma mensagem informando que não há documento disponível. </li></ul> <ul><li> Ocorre uma falha no download do arquivo. </li></ul> <ul><li> O sistema exibe uma mensagem de erro e orienta o usuário a tentar novamente mais tarde. </li></ul> |
| **Data de Criação** | 08/12/2024 |
| **Rastreabilidade** | [RF75](../elicitacao/requisitos-elicitados.md/#RF75) |

</center>

---

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>



## Cenário 3

<div align="center">
    <p><strong>Tabela 3 – Visualizar Histórico de Vacinas</strong></p>
</div>

<center>

| **Campo**           | **Descrição**     |
| ------------------- | ----------------- |
| **Título**          | Visualizar Histórico de Vacinas |
| **Objetivo**        | Permitir que o usuário consulte o histórico completo de suas vacinas no aplicativo. |
| **Contexto**        | O usuário deseja verificar informações sobre vacinas previamente aplicadas, como datas e locais. |
| **Atores**          | Usuário (paciente cadastrado no aplicativo). |
| **Recursos**        | Smartphone, aplicativo instalado e conta Gov.br autenticada. |
| **Episódios**       | <ul><li> O usuário acessa o menu principal do aplicativo e seleciona a opção "Vacinas". </li></ul> <ul><li> O sistema exibe as opções disponíveis, incluindo "Histórico de vacinas". </li></ul> <ul><li> O usuário seleciona "Histórico de vacinas". </li></ul> <ul><li> O sistema exibe a lista de vacinas registradas. </li></ul> <ul><li> O usuário pode selecionar um registro específico para ver detalhes, como data, local de aplicação e fabricante. </li></ul> |
| **Exceções**        | <ul><li> Não há registros de vacinas para o usuário. </li></ul> <ul><li> Falha na conexão impede o carregamento do histórico. </li></ul> |
| **Data de Criação** | 08/12/2024 |
| **Rastreabilidade** | [RF6](../elicitacao/requisitos-elicitados.md/#RF6) |

</center>

---

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>



## Cenário 4

<div align="center">
    <p><strong>Tabela 4 – Visualizar Consultas Marcadas</strong></p>
</div>

<center>

| **Campo**           | **Descrição**     |
| ------------------- | ----------------- |
| **Título**          | Visualizar Consultas Marcadas                                                   |
| **Objetivo**        | Permitir que o usuário visualize a lista de consultas médicas previamente agendadas. |
| **Contexto**        | O usuário deseja verificar informações sobre consultas já agendadas, como data, horário, local e especialidade. |
| **Atores**          | Usuário (paciente cadastrado no aplicativo).                                    |
| **Recursos**        | Smartphone, aplicativo instalado e conta Gov.br autenticada.                   |
| **Episódios**       | <ul><li> O usuário acessa o menu principal do aplicativo e seleciona a opção "Consultas". </li><li> O sistema exibe as opções disponíveis, incluindo "Consultas Agendadas". </li><li> O usuário seleciona "Consultas Agendadas". </li><li> O sistema exibe a lista de consultas previamente marcadas, com detalhes como data, horário, local e especialidade. </li><li> O usuário pode selecionar uma consulta específica para ver mais informações. </li></ul> |
| **Exceção**         | <ul><li> Não há consultas marcadas para o usuário. </li><li> Falha na conexão impede o carregamento da lista de consultas. </li></ul> |
| **Data de Criação** | 08/12/2024 |
| **Rastreabilidade** | [RF27](../elicitacao/requisitos-elicitados.md/#RF27) |

</center>

---

<div align="center">
    <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
</div>

</center>



## Cenário 5

<div align="center">
    <p><strong>Tabela 5 – Consultar receitas médicas</strong></p>
</div>

<center>

| **Campo**           | **Descrição**     |
| ------------------- | ----------------- |
| **Título**          | Consultar receitas médicas |
| **Objetivo**        | Permitir que o paciente consulte o histórico completo de suas receitas médicas no aplicativo. |
| **Contexto**        | O paciente deseja verificar informações sobre receitas médicas prescritas, como identificação do profissional de saúde, data da prescrição, nome do(s) medicamento(s), dosagem, posologia e duração do tratamento. |
| **Atores**          | Usuário (paciente cadastrado no aplicativo). |
| **Recursos**        | Smartphone, aplicativo instalado e conta Gov.br autenticada. |
| **Episódios**       | <ul><li> O usuário acessa o menu principal do aplicativo e seleciona a opção "Consultas". </li></ul> <ul><li> O sistema exibe as opções disponíveis, incluindo "Receitas médicas". </li></ul> <ul><li> O paciente seleciona "Receitas médicas". </li></ul> <ul><li> O sistema exibe a lista de receitas médicas. </li></ul> <ul><li> O paciente pode selecionar um registro específico para ver detalhes, como nome do(s) medicamento(s), dosagem e posologia. </li></ul> |
| **Exceções**        | <ul><li> Não há registros de receitas médicas associadas ao paciente. </li></ul> <ul><li> Falha na conexão impede o carregamento do histórico. </li></ul> |
| **Data de Criação** | 08/12/2024 |
| **Rastreabilidade** | [RF71](../elicitacao/requisitos-elicitados.md/#RF71) |

</center>

---

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>



## Cenário 6

<div align="center">
    <p><strong>Tabela 6 – Fazer pedido de medicamento</strong></p>
</div>

<center>

| **Campo**           | **Descrição**     |
| ------------------- | ----------------- |
| **Título**          | Fazer pedido de medicamento |
| **Objetivo**        | Permitir que o paciente faça o pedido do medicamento prescrito pelo aplicativo. |
| **Contexto**        | O paciente deseja verificar informações sobre o pedido de medicamento, como o estado do processamento do pedido, por exemplo, "Em processamento", "A caminho" ou "Entregue". |
| **Atores**          | Usuário (paciente cadastrado no aplicativo). |
| **Recursos**        | Smartphone, aplicativo instalado e conta Gov.br autenticada. |
| **Episódios**       | <ul><li> O usuário acessa o menu principal do aplicativo e seleciona a opção "Consultas". </li><li> O sistema exibe as opções disponíveis, incluindo "Acompanhar pedidos". </li><li> O usuário seleciona "Acompanhar pedidos". </li><li> O sistema exibe a lista de pedidos realizados, com detalhes como data, horário, medicamentos e estado do pedido. </li><li> O usuário pode selecionar um pedido específico para ver mais informações. </li></ul> |
| **Exceções**        | <ul><li> Não há registros de pedidos feitos pelo paciente. </li></ul> <ul><li> Falha na conexão impede a finalização do pedido. </li></ul> |
| **Data de Criação** | 08/12/2024 |
| **Rastreabilidade** | [RF67](../elicitacao/requisitos-elicitados.md/#RF67) |

</center>

---

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>



## Cenário 7

<div align="center">
    <p><strong>Tabela 7 – Consultar pedido de medicamento</strong></p>
</div>

<center>

| **Campo**           | **Descrição**     |
| ------------------- | ----------------- |
| **Título**          | Consultar pedido de medicamento |
| **Objetivo**        | Permitir que o paciente consulte o estado de um pedido do medicamento feito pelo aplicativo. |
| **Contexto**        | O paciente deseja pedir um medicamento pelo aplicativo para que ele possa retirar na farmácia de sua escolha ou receber em domicílio. |
| **Atores**          | Usuário (paciente cadastrado no aplicativo). |
| **Recursos**        | Smartphone, aplicativo instalado e conta Gov.br autenticada. |
| **Episódios**       | <ul><li> O usuário acessa o menu principal do aplicativo e seleciona a opção "Pedidos". </li></ul> <ul><li> O sistema exibe as opções disponíveis, incluindo "Receitas médicas". </li></ul> <ul><li> O paciente seleciona "Receitas médicas". </li></ul> <ul><li> O sistema exibe a lista de receitas médicas. </li></ul> <ul><li> O paciente pode selecionar uma receita médica e escolher os remédios que ele deseja. Por padrão os medicamentos estarão todos marcados, mas o paciente poderá desmarcar os que ele não deseja. </li></ul> <ul><li> O paciente confirma o pedido, que será analisado pela farmácia. </li></ul> |
| **Exceções**        | <ul><li> Não há registros de receitas médicas associadas ao paciente. </li></ul> <ul><li> Falha na conexão impede a finalização do pedido. </li></ul> <ul><li> A farmácia não possui o medicamento. </li></ul> |
| **Data de Criação** | 08/12/2024 |
| **Rastreabilidade** | [RF62](../elicitacao/requisitos-elicitados.md/#RF62) |

</center>

---

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>


## Cenário 8
<div align="center">
<p><strong>Tabela 8 – Visualizar Histórico de Vacinas</strong></p>
</div>

| **Campo** | **Descrição** |
| --------- | ------------- |
| **Título**          | Acessar conteúdo filtrado com falha no acesso à localização |
| **Atores**          | Paulo |
| **Objetivo**        | Paulo deseja se informar sobre doenças respiratórias em sua região |
| **Contexto**        | Paulo vive na região sul do Brasil, é professor e quer saber mais sobre prevenção de doenças respiratórias, principalmente pela proximidade do inverno. Ele se informar sobre algum possível surto em sua região e conscientizar seu alunos sobre o assunto. |
| **Recursos**        | Paulo possui um computador com navegador web moderno e atualizado, além de acesso à internet via Wi-Fi. |
| **Episódios**       | <ul> <li>Paulo entra com o gov.br no site do Meu SUS Digital. Um pop-up pedindo acesso à sua localização surge. Ele inicialmente nega, pois pensa ser desnecessário que o Meu SUS Digital tenha acesso à sua localização</li> <li>O sistema exibe a tela "Início". Mas uma caixa de diálogo sobre autodeclaração aparece logo em seguida. Paulo fica um pouco impaciente com isso, pois ela aparece sempre há um redirecionamento para a tela "Início"</li> <li>Paulo clica fora da caixa de diálogo para que ela suma, tornando a tela "Início" totalmente visível</li> <li>Paulo clica em "Conteúdos".  Há algum tempo ele já havia dado uma olhada nessa seção do site e ficou interessado desde então</li> <li>O site apresenta o conteúdo logo abaixo da barra de pesquisa e alguns filtros. Paulo escolhe filtrar o conteúdo pertinente para sua região</li> <li>O site informa que é necessário habilidar o acesso à localização, e dessa vez Paulo permite</li> <li>Adicionalmente, ele também ativa o filtro "Doenças", com a intenção de ver assuntos mais recentes relacionados a doenças em sua região</li> <li>O sistema apresenta o conteúdo filtrado, a partir do conteúdo mais recente, mas nenhum dos conteúdos estava relacionado à doenças respiratórias contagiosas, como Paulo desejava encontrar</li> <li>Paulo então fecha o site e procura pelo assunto em outros sites pela internet</li> </ul> |
| **Exceções**        | <ul> <li>Serviço de localização está indisponível</li> </ul> |
| **Data de Criação** | 08/12/2024 |
| **Rastreabilidade** | [RF72](../elicitacao/requisitos-elicitados.md/#RF72) |

<div align="center">
<p>Autor: <a href="https://github.com/JoosPerro">João Pedro</a>.</p>
</div>

---


## 📚 Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf). Acesso em: 4 dez. 2024.
>
> SILVA, Lyrene Fernandes da; LEITE, Julio Cesar Sampaio do Prado; BREITMAN, Karin Koogan. C&L: uma ferramenta de apoio à engenharia de requisitos. PUC-Rio, Departamento de Informática. MCC25/04, Julho de 2004. Disponível em: [https://www.dbd.puc-rio.br/depto_informatica/04_25_silva.pdf](https://www.dbd.puc-rio.br/depto_informatica/04_25_silva.pdf). Acesso em: 7 dez. 2024.
>
> CAMPELLO, Gabriel; ALVES, Douglas. Cenários. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: [https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/). Acesso em: 4 dez. 2024.



## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação do Documento | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 05/11/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 |
| `1.1`  | Adicionando Bibliografia | [Pedro Lopes](https://github.com/pLopess) | 08/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 |
| `1.2`  | Criação dos cenários 1, 2 e 3. | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 08/12/2024 |
| `1.3`  | Criação do cenário 4. | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 08/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 |
| `1.4`  | Coreção de historico de versão | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 08/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 |
| `1.5`  | Criação dos cenários 5, 6 e 7. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 08/12/2024 |  |  |



