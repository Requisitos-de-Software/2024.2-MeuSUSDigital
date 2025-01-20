# Matriz de Rastreabilidade

## Introdução

A matriz de rastreabilidade é uma ferramenta essencial da engenharia de requisitos, utilizada para estabelecer e visualizar as relações entre diferentes elementos de um projeto. Esta matriz possui o formato de uma tabela e fornece uma abordagem sistemática para garantir que todos os requisitos sejam atendidos de forma completa e que a equipe de desenvolvimento possa acompanhar cada etapa do ciclo de vida do sistema. Por meio dela, é possível vincular os requisitos às técnicas de elicitação e aos artefatos gerados, garantindo mais clareza e eficiência no processo de desenvolvimento, seja na produção ou no rastreamento de erros.

Um exemplo de estrutura de matriz de rastreabilidade consiste em relacionar um requisito a [Observação](../elicitacao/tecnicas/observacao.md), aos [Casos de Uso](../modelagem/caso-de-uso.md) e aos Elos de Rastreabilidade, como será apresentado na **Tabela 2**. Dessa forma, cada requisito é devidamente acompanhado desde a concepção até a entrega final.



## Metodologia

Para a construção da matriz de rastreabilidade, considerando a quantidade significativa de requisitos existentes, foi permitido que cada integrante da equipe escolhesse dez requisitos para compor a matriz. Sendo assim, foram utilizados os mesmos requisitos presentes nas histórias de usuário previamente definidas no projeto.

A **Tabela 1** apresenta as siglas utilizadas neste documento:

<div align="center">
    <p><strong>Tabela 1 – Legenda para cada sigla utilizada</strong></p>
</div>

<center>

| Tipo | Descrição |
| :--: | --------- |
| RFn  | n-ésimo Requisito Funcional |
| RNFn | n-ésimo Requisito Não Funcional |
| ADn  | n-ésimo Requisito elicitado pela técnica de Análise de Documentos |
| ENn  | n-ésimo Requisito elicitado pela técnica de Entrevista |
| GFn  | n-ésimo Requisito elicitado pela técnica de Grupo de Foco |
| INTn | n-ésimo Requisito elicitado pela técnica de Introspecção |
| OBSn | n-ésimo Requisito elicitado pela técnica de Observação |
| QUEn | n-ésimo Requisito elicitado pela técnica de Questionário |
| MRn  | n-ésimo item da matriz de restreabilidade |
| EFBn | n-ésimo Elo Funcional de rastreabilidade Backward From |
| ENFBn | n-ésimo Elo Não Funcional de rastreabilidade Backward From |
| EFFn | n-ésimo Elo Funcional de rastreabilidade Forward From |
| ENFFn | n-ésimo Elo Não Funcional de rastreabilidade Forward From |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>

A matriz foi estruturada com os seguintes campos principais:

- **ID**: Identifica o item da matriz.

- **Tipo** e **Descrição**: Identificam o requisito escolhido do artefato de [Requisitos Elicitados](../elicitacao/requisitos-elicitados.md).

- **Implementado**: Indica se o requisito foi ou não implementado.

- **Pré-rastreabilidade**: Este campo indica a técnica de elicitação utilizada para originar o requisito.

- **Artefato**: Representa o artefato que contém o requisito.

- **Elos**: Este campo estabelece a ligação entre o requisito e artefatos mapeados nos documentos [Backward From](backward-from.md) e [Forward From](forward-from.md).

Com esta metodologia, garantimos uma rastreabilidade clara e precisa, promovendo a qualidade e a confiabilidade do sistema em desenvolvimento.



## Matriz de Rastreabilidade

<div align="center">
    <p><strong>Tabela 2 – Matriz de Rastreabilidade</strong></p>
</div>

| ID  | Tipo | Descrição | Implementado | Pré-rastreabilidade | Artefatos | Elos |
| :-: | :--: | --------- | ------------ | ------------------- | --------- | ---- |
| MR1 | [RF1](../elicitacao/requisitos-elicitados.md#RF1) | O sistema deve permitir que o paciente realize login por meio de uma conta Gov.br. | Sim | [OBS1](../elicitacao/tecnicas/observacao.md#OBS1), [AD9](../elicitacao/tecnicas/analise-de-documentos.md#AD09) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB1](backward-from.md#EF1) |
| MR2 | [RF2](../elicitacao/requisitos-elicitados.md#RF2) | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Vacinas. | Sim | [OBS2](../elicitacao/tecnicas/observacao.md#OBS2) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md), [Casos de Uso](../modelagem/caso-de-uso.md) | [EFB2](backward-from.md#EF2) |
| MR3 | [RF3](../elicitacao/requisitos-elicitados.md#RF3) | O aplicativo deve disponibilizar ao usuário o acesso à sua Carteira Nacional de Vacinação Digital. | Sim | [OBS3](../elicitacao/tecnicas/observacao.md#OBS3) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB3](backward-from.md#EF3) |
| MR4 | [RF4](../elicitacao/requisitos-elicitados.md#RF4) | O aplicativo deve permitir que o usuário selecione o idioma do certificado referente à sua Carteira Nacional de Vacinação Digital. | Sim | [OBS4](../elicitacao/tecnicas/observacao.md#OBS4) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB4](backward-from.md#EF4) |
| MR5 | [RF5](../elicitacao/requisitos-elicitados.md#RF5) | O aplicativo deve permitir que o usuário exporte ou realize o download do documento referente à sua Carteira Nacional de Vacinação Digital. | Sim | [OBS5](../elicitacao/tecnicas/observacao.md#OBS5), [AD24](../elicitacao/tecnicas/analise-de-documentos.md#AD24) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md), [Casos de Uso](../modelagem/caso-de-uso.md), [Cenários](../modelagem/cenarios.md) | [EFB5](backward-from.md#EF5) |
| MR6 | [RF6](../elicitacao/requisitos-elicitados.md#RF6) | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de vacinas. | Sim | [OBS6](../elicitacao/tecnicas/observacao.md#OBS6) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md), [Casos de Uso](../modelagem/caso-de-uso.md), [Cenários](../modelagem/cenarios.md) | [EFB6](backward-from.md#EF16) |
| MR7 | [RF7](../elicitacao/requisitos-elicitados.md#RF7) | O aplicativo deve disponibilizar ao usuário o acesso aos detalhes de cada vacina. | Sim | [OBS7](../elicitacao/tecnicas/observacao.md#OBS7) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB7](backward-from.md#EF7) |
| MR8 | [RF8](../elicitacao/requisitos-elicitados.md#RF8) | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Exames. | Sim | [OBS8](../elicitacao/tecnicas/observacao.md#OBS8) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB8](backward-from.md#EF8) |
| MR9 | [RF9](../elicitacao/requisitos-elicitados.md#RF9) | O aplicativo deve permitir a visualização dos exames laboratoriais realizados. | Sim | [OBS9](../elicitacao/tecnicas/observacao.md#OBS9) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB9](backward-from.md#EF9) |
| MR10 | [RF10](../elicitacao/requisitos-elicitados.md#RF10) | O aplicativo deve permitir a visualização dos resultados e demais informações a respeito dos exames laboratoriais realizados. | Sim | [OBS10](../elicitacao/tecnicas/observacao.md#OBS10) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB10](backward-from.md#EF10) |
| MR11 | [RF11](../elicitacao/requisitos-elicitados.md#RF11) | O aplicativo deve permitir a exportação/download do documento contendo o resultado e demais informações a respeito de cada exame laboratorial realizado. | Sim | [OBS11](../elicitacao/tecnicas/observacao.md#OBS11) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB11](backward-from.md#EF11) |
| MR12 | [RF12](../elicitacao/requisitos-elicitados.md#RF12) | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Medicamentos. | Sim | [OBS12](../elicitacao/tecnicas/observacao.md#OBS12) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB12](backward-from.md#EF12) |
| MR13 | [RF13](../elicitacao/requisitos-elicitados.md#RF13) | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de medicamentos recebidos. | Sim | [OBS13](../elicitacao/tecnicas/observacao.md#OBS13) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB13](backward-from.md#EF13) |
| MR14 | [RF14](../elicitacao/requisitos-elicitados.md#RF14) | O aplicativo deve permitir que o usuário adicione um medicamento recebido por meio de programas de dispensação do Governo Federal através de um mecanismo de busca. | Sim | [OBS14](../elicitacao/tecnicas/observacao.md#OBS14) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB14](backward-from.md#EF14) |
| MR15 | [RF15](../elicitacao/requisitos-elicitados.md#RF15) | O aplicativo deve permitir que o usuário possa realizar a busca por um medicamento através do nome e dosagem do mesmo. | Sim | [OBS15](../elicitacao/tecnicas/observacao.md#OBS15) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB15](backward-from.md#EF15) |
| MR16 | [RF16](../elicitacao/requisitos-elicitados.md#RF16) | O aplicativo deve fornecer ao usuário, em adesão ao Programa Farmácia Popular, a opção de autorizar ou não a retirada de medicamentos em seu CPF. | Sim | [OBS16](../elicitacao/tecnicas/observacao.md#OBS16) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB16](backward-from.md#EF16) |
| MR17 | [RF17](../elicitacao/requisitos-elicitados.md#RF17) | O aplicativo deve permitir que o usuário possa verificar os medicamentos recebidos pelo Programa Farmácia Popular. | Sim | [OBS17](../elicitacao/tecnicas/observacao.md#OBS17) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB17](backward-from.md#EF17) |
| MR18 | [RF18](../elicitacao/requisitos-elicitados.md#RF18) | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Dignidade Menstrual. | Sim | [OBS18](../elicitacao/tecnicas/observacao.md#OBS18) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB18](backward-from.md#EF18) |
| MR19 | [RF19](../elicitacao/requisitos-elicitados.md#RF19) | Caso o usuário atenda aos critérios do Programa, o aplicativo deve permitir que o usuário emita uma autorização para participar do Programa Dignidade Menstrual. | Sim | [OBS19](../elicitacao/tecnicas/observacao.md#OBS19) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB19](backward-from.md#EF19) |
| MR20 | [RF20](../elicitacao/requisitos-elicitados.md#RF20) | O aplicativo deve permitir que o usuário exporte/baixe o documento referente à autorização de participação do Programa Dignidade Menstrual. | Sim | [OBS20](../elicitacao/tecnicas/observacao.md#OBS20) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB20](backward-from.md#EF20) |
| MR21 | [RF21](../elicitacao/requisitos-elicitados.md#RF21) | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Rede de Saúde. | Sim | [OBS21](../elicitacao/tecnicas/observacao.md#OBS21) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB21](backward-from.md#EF21) |
| MR22 | [RF22](../elicitacao/requisitos-elicitados.md#RF22) | O aplicativo deve pedir permissão de acesso à localização do dispositivo do usuário. | Sim | [OBS22](../elicitacao/tecnicas/observacao.md#OBS22), [AD5](../elicitacao/tecnicas/analise-de-documentos.md#AD05) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB22](backward-from.md#EF22) |
| MR23 | [RF23](../elicitacao/requisitos-elicitados.md#RF23) | O aplicativo deve armazenar a localização do dispositivo do usuário. | Sim | [OBS23](../elicitacao/tecnicas/observacao.md#OBS23), [AD6](../elicitacao/tecnicas/analise-de-documentos.md#AD06) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB23](backward-from.md#EF23) |
| MR24 | [RF24](../elicitacao/requisitos-elicitados.md#RF24) | O aplicativo deve oferecer opções de estabelecimentos de saúde a fim de que o usuário possa identificar àqueles próximos à sua localização, de acordo com o tipo de serviço desejado. | Sim | [OBS24](../elicitacao/tecnicas/observacao.md#OBS24) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB24](backward-from.md#EF24) |
| MR25 | [RF25](../elicitacao/requisitos-elicitados.md#RF25) | O aplicativo deve permitir que o usuário possa identificar os estabelecimentos de saúde recentes vinculados a ele. | Sim | [OBS25](../elicitacao/tecnicas/observacao.md#OBS25) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB25](backward-from.md#EF25) |
| MR26 | [RF26](../elicitacao/requisitos-elicitados.md#RF26) | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Agendamentos. | Sim | [OBS26](../elicitacao/tecnicas/observacao.md#OBS26) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB26](backward-from.md#EF26) |
| MR27 | [RF27](../elicitacao/requisitos-elicitados.md#RF27) | O aplicativo deve exibir as consultas médicas ou exames de saúde do usuário. | Sim | [OBS27](../elicitacao/tecnicas/observacao.md#OBS27) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md), [Cenários](../modelagem/cenarios.md) | [EFB27](backward-from.md#EF27) |
| MR28 | [RF28](../elicitacao/requisitos-elicitados.md#RF28) | O aplicativo deve possibilitar o agendamento de consultas médicas ou exames de saúde. | Sim | [OBS28](../elicitacao/tecnicas/observacao.md#OBS28), [AD27](../elicitacao/tecnicas/analise-de-documentos.md#AD27), [EN2](../elicitacao/tecnicas/entrevista.md#EN02), [GF2](../elicitacao/tecnicas/grupo-de-foco.md#GF02) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB28](backward-from.md#EF28) |
| MR29 | [RF29](../elicitacao/requisitos-elicitados.md#RF29) | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Atendimento e Internação. | Sim | [OBS29](../elicitacao/tecnicas/observacao.md#OBS29) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB29](backward-from.md#EF29) |
| MR30 | [RF30](../elicitacao/requisitos-elicitados.md#RF30) | O aplicativo deve exibir os registros de atendimentos ou internações do usuário. | Sim | [OBS30](../elicitacao/tecnicas/observacao.md#OBS30) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB30](backward-from.md#EF30) |
| MR31 | [RF31](../elicitacao/requisitos-elicitados.md#RF31) | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Contatos. | Sim | [OBS31](../elicitacao/tecnicas/observacao.md#OBS31) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB31](backward-from.md#EF31) |
| MR32 | [RF32](../elicitacao/requisitos-elicitados.md#RF32) | O aplicativo deve exibir contatos de profissionais de saúde. | Sim | [OBS32](../elicitacao/tecnicas/observacao.md#OBS32) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB32](backward-from.md#EF32) |
| MR33 | [RF33](../elicitacao/requisitos-elicitados.md#RF33) | O aplicativo deve permitir que o usuário adicione o contato de um profissional de saúde em casos de emergência. | Sim | [OBS33](../elicitacao/tecnicas/observacao.md#OBS33) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB33](backward-from.md#EF33) |
| MR34 | [RF34](../elicitacao/requisitos-elicitados.md#RF34) | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Diário de Saúde. | Sim | [OBS34](../elicitacao/tecnicas/observacao.md#OBS34) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB34](backward-from.md#EF34) |
| MR35 | [RF35](../elicitacao/requisitos-elicitados.md#RF35) | O aplicativo deve exibir todos os registros de saúde do usuário. | Sim | [OBS35](../elicitacao/tecnicas/observacao.md#OBS35) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB35](backward-from.md#EF35) |
| MR36 | [RF36](../elicitacao/requisitos-elicitados.md#RF36) | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Pressão. | Sim | [OBS36](../elicitacao/tecnicas/observacao.md#OBS36) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB36](backward-from.md#EF36) |
| MR37 | [RF37](../elicitacao/requisitos-elicitados.md#RF37) | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Pressão. | Sim | [OBS37](../elicitacao/tecnicas/observacao.md#OBS37) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB37](backward-from.md#EF37) |
| MR38 | [RF38](../elicitacao/requisitos-elicitados.md#RF38) | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Glicose. | Sim | [OBS38](../elicitacao/tecnicas/observacao.md#OBS38) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB38](backward-from.md#EF38) |
| MR39 | [RF39](../elicitacao/requisitos-elicitados.md#RF39) | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Glicose. | Sim | [OBS39](../elicitacao/tecnicas/observacao.md#OBS39) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB39](backward-from.md#EF39) |
| MR40 | [RF40](../elicitacao/requisitos-elicitados.md#RF40) | O aplicativo deve exibir os registros de saúde do usuário referentes ao seu IMC. | Sim | [OBS40](../elicitacao/tecnicas/observacao.md#OBS40) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB40](backward-from.md#EF40) |
| MR41 | [RF41](../elicitacao/requisitos-elicitados.md#RF41) | O aplicativo deve permitir que o usuário adicione um registro de saúde referente ao seu IMC. | Sim | [OBS41](../elicitacao/tecnicas/observacao.md#OBS41) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB41](backward-from.md#EF41) |
| MR42 | [RF42](../elicitacao/requisitos-elicitados.md#RF42) | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Alergias. | Sim | [OBS42](../elicitacao/tecnicas/observacao.md#OBS42) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB42](backward-from.md#EF42) |
| MR43 | [RF43](../elicitacao/requisitos-elicitados.md#RF43) | O aplicativo deve exibir as alergias que usuário possui. | Sim | [OBS43](../elicitacao/tecnicas/observacao.md#OBS43) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB43](backward-from.md#EF43) |
| MR44 | [RF44](../elicitacao/requisitos-elicitados.md#RF44) | O aplicativo deve permitir que o usuário adicione uma alergia. | Sim | [OBS44](../elicitacao/tecnicas/observacao.md#OBS44) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB44](backward-from.md#EF44) |
| MR45 | [RF54](../elicitacao/requisitos-elicitados.md#RF54) | O sistema deverá apresentar o status e posição do usuário na lista de espera para transplante de órgão e tecido. | Sim | [AD18](../elicitacao/tecnicas/analise-de-documentos.md#AD18) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB54](backward-from.md#EF54) |
| MR46 | [RF56](../elicitacao/requisitos-elicitados.md#RF56) | O sistema deverá permitir que o paciente preencha informações de autodeclaração com nome social, raça/cor e endereço. | Sim | [AD26](../elicitacao/tecnicas/analise-de-documentos.md#AD26) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB56](backward-from.md#EF56) |
| MR47 | [RF62](../elicitacao/requisitos-elicitados.md#RF62) | A aplicação permite consultar pedidos de medicamento. | Não | [EN7](../elicitacao/tecnicas/entrevista.md#EN07) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md), [Casos de Uso](../modelagem/caso-de-uso.md), [Cenários](../modelagem/cenarios.md) | [EFB62](backward-from.md#EF62) |
| MR48 | [RF67](../elicitacao/requisitos-elicitados.md#RF67) | A aplicação permite realizar pedidos de medicamento. | Não | [EN12](../elicitacao/tecnicas/entrevista.md#EN12) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md), [Casos de Uso](../modelagem/caso-de-uso.md), [Cenários](../modelagem/cenarios.md) | [EFB67](backward-from.md#EF67) |
| MR49 | [RF68](../elicitacao/requisitos-elicitados.md#RF68) | A aplicação permite ao paciente aplicar filtro de pesquisa ("Em processamento", "A caminho", "Entregue") para a consulta de pedidos de medicamento. | Não | [EN13](../elicitacao/tecnicas/entrevista.md#EN13) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md) | [EFB68](backward-from.md#EF68) |
| MR50 | [RF69](../elicitacao/requisitos-elicitados.md#RF69) | O aplicativo mostra o histórico de vacinação pré-pandemia. | Não | [GF1](../elicitacao/tecnicas/grupo-de-foco.md#GF01) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md), [Casos de Uso](../modelagem/caso-de-uso.md) | [EFB69](backward-from.md#EF69) |
| MR51 | [RF71](../elicitacao/requisitos-elicitados.md#RF71) | O aplicativo permite consultar receitas médicas. | Não | [GF4](../elicitacao/tecnicas/grupo-de-foco.md#GF04) | [Histórias de Usuário](../modelagem-agil/historias-de-usuario.md), [*Backlog*](../modelagem-agil/backlog.md), [Casos de Uso](../modelagem/caso-de-uso.md), [Cenários](../modelagem/cenarios.md) | [EFB71](backward-from.md#EF71) |

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>



## 📚 Bibliografia

> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 16 jan. 2025.
>
> SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 26. 2017. Apresentação de slides. Disponível em:[https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf](https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf). Acesso em: 16 jan. 2025.
>
> ALVES, Izabella; ARAÚJO, Lucas Víctor Ferreira de; OLIVEIRA, Lucas. Matriz de Rastreabilidade. Repositório do Grupo Economia-DF da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: [https://requisitos-de-software.github.io/2023.2-Economia-DF/rastreabilidade/matriz-de-rastreabilidade/#matriz-de-rastreabilidade_1](https://requisitos-de-software.github.io/2023.2-Economia-DF/rastreabilidade/matriz-de-rastreabilidade/#matriz-de-rastreabilidade_1). Acesso em: 19 jan. 2025.

## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0` | Criação do documento. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 18/01/2025 |  |  |
| `1.1` | Adicionando introdução e metodologia. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 19/01/2025 |  |  |
| `1.2` | Completando a tabela com os elos. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 19/01/2025 |  |  |
