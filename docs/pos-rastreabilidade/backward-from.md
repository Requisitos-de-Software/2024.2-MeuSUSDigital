# Backward From

## Introdução

## Metodologia

## Tabela de Requisitos Funcionais


<div align="center">
    <p><strong>Tabela 1 – Legenda para cada sigla utilizada</strong></p>
</div>

<center>

| Tipo  | Descrição                                                         |
| :---  | ----------------------------------------------------------------- |
| RF    | Requisito Funcional                                               |
| RNF   | Requisito Não Funcional                                           |
| ADn   | n-ésimo Requisito elicitado pela técnica de Análise de Documentos |
| ENn   | n-ésimo Requisito elicitado pela técnica de Entrevista            |
| GFn   | n-ésimo Requisito elicitado pela técnica de Grupo de Foco         |
| INTn  | n-ésimo Requisito elicitado pela técnica de Introspecção          |
| OBSn  | n-ésimo Requisito elicitado pela técnica de Observação            |
| QUEn  | n-ésimo Requisito elicitado pela técnica de Questionário          |
| ELOBn | n-ésimo Elo (ou Vínculo)                                          |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>

---

<div align="center">
    <p><strong>Tabela 2 – Backward Traceability dos requisitos funcionais</strong></p>
</div>

<center>

| ID    | Tipo | Descrição | Implementado | Rastreabilidade |
| :---: | :--: | --------- | :----------: | :-------------: |
| RF1   | Funcional | O sistema deve permitir que o paciente realize login por meio de uma conta Gov.br | Sim | [OBS1](tecnicas/observacao.md#requisitos-elicitados) e [AD09](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RF2   | Funcional | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Vacinas | Sim | [OBS2](tecnicas/observacao.md#requisitos-elicitados) |
| RF3   | Funcional | O aplicativo deve disponibilizar ao usuário o acesso à sua Carteira Nacional de Vacinação Digital | Sim | [OBS3](tecnicas/observacao.md#requisitos-elicitados) |
| RF4   | Funcional | O aplicativo deve permitir que o usuário selecione o idioma do certificado referente à sua Carteira Nacional de Vacinação Digital | Sim | [OBS4](tecnicas/observacao.md#requisitos-elicitados) |
| RF5   | Funcional | O aplicativo deve permitir que o usuário exporte ou realize o download do documento referente à sua Carteira Nacional de Vacinação Digital | Sim | [OBS5](tecnicas/observacao.md#requisitos-elicitados) e [AD24](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RF6   | Funcional | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de vacinas | Sim | [OBS6](tecnicas/observacao.md#requisitos-elicitados) |
| RF7   | Funcional | O aplicativo deve disponibilizar ao usuário o acesso aos detalhes de cada vacina | Sim | [OBS7](tecnicas/observacao.md#requisitos-elicitados) |
| RF8   | Funcional | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Exames | Sim | [OBS8](tecnicas/observacao.md#requisitos-elicitados) |
| RF9   | Funcional | O aplicativo deve permitir a visualização dos exames laboratoriais realizados | Sim | [OBS9](tecnicas/observacao.md#requisitos-elicitados) |
| RF10  | Funcional | O aplicativo deve permitir a visualização dos resultados e demais informações a respeito dos exames laboratoriais realizados | Sim | [OBS10](tecnicas/observacao.md#requisitos-elicitados) |
| RF11  | Funcional | O aplicativo deve permitir a exportação/download do documento contendo o resultado e demais informações a respeito de cada exame laboratorial realizado | Sim | [OBS11](tecnicas/observacao.md#requisitos-elicitados) |
| RF55  | Funcional | O aplicativo deve permitir que o usuário exporte ou realize o download do documento referente ao Certificado de vacinação nacional de Covid-19. | Sim | [AD25](tecnicas/analise-de-documentos.md#requisitos-elicitados), [OBS45](tecnicas/observacao.md#OBS45) |


</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>


## Tabela de Requisitos Não Funcionais


<div align="center">
    <p><strong>Tabela 3 – Backward Traceability dos requisitos não funcionais</strong></p>
</div>

<center>

| ID    | Tipo | Descrição | Implementado | Rastreabilidade |
| :---: | :--: | --------- | :----------: | --------------- |
| ELOBn | -    | -         | -            | [-]()           |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>


## Elos de rastreabilidade Backward From


<div align="center">
    <p><strong>Tabela 3 – Elos de rastreabilidade Backward From</strong></p>
</div>

<center>

| ID    | Requisitos | Tipo | Descrição |
| :---: | :--------: | :--: | --------- |
| ELOBn | [-]()      | -    | -         |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>


## Conclusão


## 📚 Bibliografia

> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. _Engenharia de Requisitos: software orientado ao negócio_. Rio de Janeiro: Brasport, 2016.
>
> WIEGERS, Karl; BEATTY, Joy. _Software Requirements. Third Edition_. Redmond, WA: Microsoft Press, 2013.


## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação da estrutura inicial do documento referente ao Backward From. | [Artur Ricardo](https://github.com/algorithmorphic) | 16/01/2025 |  |  |
| `1.1`  | Atualização da bibliografia. | [Artur Ricardo](https://github.com/algorithmorphic) | 17/01/2025 |  |  |
| `1.2`  | Adição da tabela de rastreabilidade para trás referente aos requisitos funcionais elicitados e correção de título. | [Artur Ricardo](https://github.com/algorithmorphic) | 19/01/2025 |  |  |