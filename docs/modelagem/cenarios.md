# Cenários

## Introdução 


Os cenários são descrições detalhadas, geralmente em linguagem natural, que ilustram situações ou eventos envolvendo determinados atores. No contexto do site Meu SUS Digital, eles são úteis para analisar como os usuários interagem com a plataforma e como ela responde a diferentes situações. Esses cenários ajudam a compreender o funcionamento do sistema, seus comportamentos e fluxos em diversas situações práticas. As interações e funcionalidades analisadas estão organizadas nas tabelas de 1 a 5.


## Cenário 1

<div align="center">
    <p><strong>Tabela 1 – Exportar Carteira Nacional de Vacinação Digital</strong></p>
</div>

---

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

---

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>



## Cenário 2

<div align="center">
    <p><strong>Tabela 2 – Exportação/Download de Certificado de Vacinação Nacional de Covid-19</strong></p>
</div>

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

---

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>



## Cenário 3

<div align="center">
    <p><strong>Tabela 3 – Visualizar Histórico de Vacinas</strong></p>
</div>

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

---

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>

---

## Cenário 4

<center>


Tabela 4: Visualizar Consultas Marcadas.

| **Cenário 4**       |                                                                                  |
|---------------------|----------------------------------------------------------------------------------|
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

---



Fonte: [????????](????????).

</center>

## Cenário 5

<center>

Tabela 5: ???????.

|**Cenário 5**  |
------------ ---|
|**Titulo**     |
| ???????????   |
|**Objetivo**   |
| ???????????   |
|**Contexto**   |
| ???????????   |
|**Atores**     |
| ???????????   |
|**Recursos**   |
| ???????????   |
|**Episódios**  |
| ???????????   |
|**Restrição**  |
| ???????????   |
|**Exceção**    |
| ???????????   |


Fonte: [????????](????????).

</center>



## 📚 Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf). Acesso em: 4 dez. 2024.
>
> CAMPELLO, Gabriel; ALVES, Douglas. Cenários. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: [https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/). Acesso em: 4 dez. 2024.



## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação do Documento | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 05/11/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 |
| `1.1`  | Adicionando Bibliografia | [Pedro Lopes](https://github.com/pLopess) | 08/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 |
| `1.2`  | Criação dos cenários 1, 2 e 3. | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 |  |  |
| `1.3`  | Criação do cenário 4. | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 08/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 |
| `1.4`  | coreção de historico de versão | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 08/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 |



