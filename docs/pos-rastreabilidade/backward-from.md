# Backward From

## Introdução

A rastreabilidade de requisitos é um processo fundamental na engenharia de software, garantindo que as necessidades dos stakeholders sejam atendidas e que o ciclo de vida do software seja bem gerenciado. Este documento apresenta o processo de rastreabilidade retrospectiva, conhecido como "Backward From", aplicado no projeto Meu SUS Digital. O foco é estabelecer elos claros entre os requisitos elicitados e os artefatos resultantes, assegurando controle e rastreamento efetivos.

A rastreabilidade retrospectiva possibilita verificar como os requisitos elicitados através das técnicas de [Análise de Documentos](../elicitacao/tecnicas/analise-de-documentos.md), [Entrevista](../elicitacao/tecnicas/entrevista.md), [Grupo de Foco](../elicitacao/tecnicas/grupo-de-foco.md), [Observação](../elicitacao/tecnicas/observacao.md) e [Introspecção](../elicitacao/tecnicas/introspeccao.md) estão relacionados aos componentes e à implementação do sistema, promovendo coerência entre a análise inicial e os resultados obtidos.

## Metodologia

A metodologia utilizada para a rastreabilidade retrospectiva neste projeto baseia-se no modelo "Backward From" descrito por Toranzo. Esta abordagem classifica os requisitos em funcionais (RF) e não funcionais (RNF), e estabelece elos que descrevem as conexões entre eles e os artefatos gerados ao longo do ciclo de vida do projeto.

Os principais componentes da metodologia incluem:

1. **Identificação dos Requisitos**:

    Os requisitos foram elicitados utilizando técnicas como análise de documentos, entrevista, grupo de foco, observação e introspecção. Cada requisito foi classificado como funcional ou não funcional.

2. **Classificação de Níveis e Elos**:

    Os requisitos são organizados em níveis (ambiental, organizacional, gerencial e de desenvolvimento).

    Os elos estabelecem as relações de satisfação, recurso, responsabilidade, representação, alocação e agregação entre os requisitos e artefatos.

3. **Construção das Tabelas de Rastreabilidade**:

    As tabelas de rastreabilidade retrospectiva foram elaboradas para requisitos funcionais e não funcionais, com base nos elos identificados.

4. **Elaboração dos Elos**:

    Cada elo de rastreabilidade foi descrito em tabelas específicas, representando como os requisitos se conectam aos artefatos e ao sistema como um todo.

Ao final, foram geradas tabelas detalhadas que consolidam o processo de rastreabilidade, organizadas para facilitar a compreensão e a manutenção do projeto.

Vale ressaltar que também foi criada uma tabela contendo a legenda para cada sigla utilizada neste documento a fim de padronizar e facilitar a compreensão das informações apresentadas:

<div align="center">
    <p><strong>Tabela 1 – Legenda para cada sigla utilizada</strong></p>
</div>

<center>

| Tipo  | Descrição                                                         |
| :---  | ----------------------------------------------------------------- |
| RF    | Requisito Funcional                                               |
| RNF   | Requisito Não Funcional                                           |
| ADn   | n-ésimo requisito elicitado pela técnica de Análise de Documentos |
| ENn   | n-ésimo requisito elicitado pela técnica de Entrevista            |
| GFn   | n-ésimo requisito elicitado pela técnica de Grupo de Foco         |
| INTn  | n-ésimo requisito elicitado pela técnica de Introspecção          |
| OBSn  | n-ésimo requisito elicitado pela técnica de Observação            |
| QUEn  | n-ésimo requisito elicitado pela técnica de Questionário          |
| EFn   | n-ésimo elo (ou vínculo) funcional                                |
| ENFn  | n-ésimo elo (ou vínculo) não funcional                            |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>

## Rastreabilidade Retrospectiva dos Requisitos Funcionais

??? note "Tabela 2"

    <div align="center">
        <p><strong>Tabela 2 – Rastreabilidade retrospectiva dos requisitos funcionais elicitados</strong></p>
    </div>

    <center>

    | ID    | Descrição | Rastreabilidade |
    | :---- | --------- | :-------------- |
    | RF1   | O sistema deve permitir que o paciente realize login por meio de uma conta Gov.br            | [OBS1](../elicitacao/tecnicas/observacao.md#requisitos-elicitados), [AD09](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF2   | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Vacinas | [OBS2](../elicitacao/tecnicas/observacao.md#requisitos-elicitados)                          |
    | RF3   | O aplicativo deve disponibilizar ao usuário o acesso à sua Carteira Nacional de Vacinação Digital | [OBS3](../elicitacao/tecnicas/observacao.md#requisitos-elicitados)                          |
    | RF4   | O aplicativo deve permitir que o usuário selecione o idioma do certificado referente à sua Carteira Nacional de Vacinação Digital | [OBS4](../elicitacao/tecnicas/observacao.md#requisitos-elicitados)                          |
    | RF5   | O aplicativo deve permitir que o usuário exporte ou realize o download do documento referente à sua Carteira Nacional de Vacinação Digital | [OBS5](../elicitacao/tecnicas/observacao.md#requisitos-elicitados), [AD24](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF6   | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de vacinas             | [OBS6](../elicitacao/tecnicas/observacao.md#requisitos-elicitados)                          |
    | RF7   | O aplicativo deve disponibilizar ao usuário o acesso aos detalhes de cada vacina             | [OBS7](../elicitacao/tecnicas/observacao.md#requisitos-elicitados)                          |
    | RF8   | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Exames | [OBS8](../elicitacao/tecnicas/observacao.md#requisitos-elicitados)                          |
    | RF9   | O aplicativo deve permitir a visualização dos exames laboratoriais realizados                | [OBS9](../elicitacao/tecnicas/observacao.md#requisitos-elicitados)                          |
    | RF10  | O aplicativo deve permitir a visualização dos resultados e demais informações a respeito dos exames laboratoriais realizados | [OBS10](../elicitacao/tecnicas/observacao.md#requisitos-elicitados)                         |
    | RF11  | O aplicativo deve permitir a exportação/download do documento contendo o resultado e demais informações a respeito de cada exame laboratorial realizado | [OBS11](../elicitacao/tecnicas/observacao.md#requisitos-elicitados)                         |
    | RF12  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Medicamentos | [OBS12](../elicitacao/tecnicas/observacao.md#requisitos-elicitados)                          |
    | RF13  | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de medicamentos recebidos | [OBS13](../elicitacao/tecnicas/observacao.md#requisitos-elicitados)                          |
    | RF14  | O aplicativo deve permitir que o usuário adicione um medicamento recebido por meio de programas de dispensação do Governo Federal através de um mecanismo de busca | [OBS14](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF15  | O aplicativo deve permitir que o usuário possa realizar a busca por um medicamento através do nome e dosagem do mesmo | [OBS15](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF16  | O aplicativo deve fornecer ao usuário, em adesão ao Programa Farmácia Popular, a opção de autorizar ou não a retirada de medicamentos em seu CPF | [OBS16](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF17  | O aplicativo deve permitir que o usuário possa verificar os medicamentos recebidos pelo Programa Farmácia Popular | [OBS17](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF18  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Dignidade Menstrual | [OBS18](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF19  | Caso o usuário atenda aos critérios do Programa, o aplicativo deve permitir que o usuário emita uma autorização para participar do Programa Dignidade Menstrual | [OBS19](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF20  | O aplicativo deve permitir que o usuário exporte/baixe o documento referente à autorização de participação do Programa Dignidade Menstrual | [OBS20](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF21  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Rede de Saúde | [OBS21](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF22  | O aplicativo deve pedir permissão de acesso à localização do dispositivo do usuário         | [OBS22](../elicitacao/tecnicas/observacao.md#requisitos-elicitados), [AD05](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF23  | O aplicativo deve armazenar a localização do dispositivo do usuário                        | [OBS23](../elicitacao/tecnicas/observacao.md#requisitos-elicitados), [AD06](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF24  | O aplicativo deve oferecer opções de estabelecimentos de saúde a fim de que o usuário possa identificar àqueles próximos à sua localização, de acordo com o tipo de serviço desejado | [OBS24](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF25  | O aplicativo deve permitir que o usuário possa identificar os estabelecimentos de saúde recentes vinculados a ele | [OBS25](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF26  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Agendamentos | [OBS26](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF27  | O aplicativo deve exibir as consultas médicas ou exames de saúde do usuário                 | [OBS27](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF28  | O aplicativo deve possibilitar o agendamento de consultas médicas ou exames de saúde        | [OBS28](../elicitacao/tecnicas/observacao.md#requisitos-elicitados), [AD27](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados), [EN02](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados), [GF02](../elicitacao/tecnicas/grupo-de-foco.md#requisitos-elicitados) |
    | RF29  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Atendimento e Internação | [OBS29](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF30  | O aplicativo deve exibir os registros de atendimentos ou internações do usuário            | [OBS30](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF31  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Contatos | [OBS31](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF32  | O aplicativo deve exibir contatos de profissionais de saúde                               | [OBS32](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF33  | O aplicativo deve permitir que o usuário adicione o contato de um profissional de saúde em casos de emergência | [OBS33](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF34  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Diário de Saúde | [OBS34](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF35  | O aplicativo deve exibir todos os registros de saúde do usuário                           | [OBS35](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF36  | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Pressão         | [OBS36](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF37  | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Pressão | [OBS37](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF38  | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Glicose         | [OBS38](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF39  | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Glicose | [OBS39](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF40  | O aplicativo deve exibir os registros de saúde do usuário referentes ao seu IMC            | [OBS40](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF41  | O aplicativo deve permitir que o usuário adicione um registro de saúde referente ao seu IMC | [OBS41](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF42  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Alergias | [OBS42](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF43  | O aplicativo deve exibir as alergias que usuário possui                                   | [OBS43](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF44  | O aplicativo deve permitir que o usuário adicione uma alergia                            | [OBS44](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RF45  | O sistema deverá apresentar o termo de consentimento.                                    | [AD01](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF46  | O sistema deverá informar quais dados serão coletados.                                   | [AD02](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF47  | O sistema deverá permitir que o paciente escolha entre aceitar ou recusar a coleta de seus dados pessoais. | [AD03](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF48  | O sistema deverá registrar a escolha do paciente em relação à coleta de seus dados pessoais. | [AD04](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF49  | O sistema deverá pedir permissão de acesso à câmera do dispositivo.                      | [AD07](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF50  | O sistema deverá permitir ao paciente tirar sua foto utilizando a câmera do dispositivo. | [AD08](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF51  | O sistema deverá buscar no CADSUS os dados do paciente (Nome, data de nascimento, sexo, filiação, nacionalidade, e-mail, endereço e telefone) utilizando o CPF associado à conta Gov.br informada no login. | [AD10](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF52  | O sistema deverá buscar na RNDS os dados do paciente (Histórico clínico, dados de vacinação e resultados de exames) utilizando o CPF associado à conta Gov.br informada no login. | [AD11](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF53  | O sistema deverá permitir que o paciente solicite a remoção de seus dados pessoais do aplicativo. | [AD12](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF54  | O sistema deverá apresentar o *status* e posição do usuário na lista de espera para transplante de órgão e tecido. | [AD18](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF55  | O aplicativo deve permitir que o usuário exporte ou realize o download do documento referente ao Certificado de vacinação nacional de Covid-19. | [AD25](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados), [OBS45](../elicitacao/tecnicas/observacao.md#OBS45) |
    | RF56  | O sistema deverá permitir que o paciente preencha informações de autodeclaração com nome social, raça/cor e endereço. | [AD26](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF57  | O sistema deverá notificar o paciente sobre consultas agendadas, informando o tipo de consulta, a data, o horário e o local da consulta. | [AD30](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RF58  | A aplicação permite agendar exames                                                | [EN03](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RF59  | A aplicação permite ao servidor solicitar licença saúde                           | [EN04](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RF60  | A aplicação permite acompanhar o andamento de solicitações (licença, medicamentos) | [EN05](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RF61  | A aplicação permite acompanhar a vacinação                                        | [EN06](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RF62  | A aplicação permite consultar pedidos de medicamento                              | [EN07](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RF63  | A aplicação permite consultar recebimentos de medicamento                         | [EN08](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RF64  | A aplicação permite consultar os agendamentos de exames                           | [EN09](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RF65  | A aplicação permite consultar os resultados de exames                             | [EN10](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RF66  | A aplicação notifica o cancelamento de agendamentos                               | [EN11](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RF67  | A aplicação permite realizar pedidos de medicamento                               | [EN12](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RF68  | A aplicação permite ao paciente aplicar filtro de pesquisa ("Em processamento", "A caminho", "Entregue") para a consulta de pedidos de medicamento | [EN13](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RF69  | O aplicativo mostra o histórico de vacinação pré-pandemia                         | [GF01](../elicitacao/tecnicas/grupo-de-foco.md#requisitos-elicitados) |
    | RF70  | O aplicativo permite validação médica de declarações de alergia, mediante laudo. Essa validação deve ser visivelmente sinalizada ao paciente | [GF03](../elicitacao/tecnicas/grupo-de-foco.md#requisitos-elicitados) |
    | RF71  | O aplicativo permite consultar receitas médicas                                   | [GF04](../elicitacao/tecnicas/grupo-de-foco.md#requisitos-elicitados) |
    | RF72  | O aplicativo notifica aos usuários atualizações em conteúdos relacionados a patologias que eles venham a ter | [GF05](../elicitacao/tecnicas/grupo-de-foco.md#requisitos-elicitados) |
    | RF73  | O aplicativo pode destacar conteúdos pertinentes a um estado para usuários desse estado | [GF06](../elicitacao/tecnicas/grupo-de-foco.md#requisitos-elicitados) |
    | RF74  | O aplicativo deve permitir que o paciente exporte/baixe as receitas médicas       | [GF07](../elicitacao/tecnicas/grupo-de-foco.md#requisitos-elicitados) |
    | RF75  | O aplicativo deve oferece agendamento de consultas e exames                      | [GF02](../elicitacao/tecnicas/grupo-de-foco.md#requisitos-elicitados) |

    </center>

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>


## Rastreabilidade Retrospectiva dos Requisitos Não Funcionais

??? note "Tabela 3"

    <div align="center">
        <p><strong>Tabela 3 – Rastreabilidade retrospectiva dos requisitos não funcionais elicitados</strong></p>
    </div>

    <center>

    | ID     | Descrição | Rastreabilidade |
    | :----  | --------- | --------------- |
    | RNF1   | O sistema deve garantir que o login por meio da conta Gov.br seja realizado com autenticação segura (OAuth 2.0) | [OBS45](../elicitacao/tecnicas/observacao.md#requisitos-elicitados), [AD22](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RNF2   | O aplicativo deve exibir informações de ajuda de maneira acessível e compreensível para todos os usuários, incluindo pessoas com deficiência visual ou auditiva | [OBS46](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF3   | O histórico de vacinação deve ser carregado em menos de 3 segundos em dispositivos com conexão 4G | [OBS47](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF4   | O aplicativo deve oferecer suporte a pelo menos três idiomas (português, inglês e espanhol) para os certificados de vacinação | [OBS48](../elicitacao/tecnicas/observacao.md#requisitos-elicitados), [AD29](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RNF5   | O certificado de vacinação deve ser exportado em formato PDF de alta qualidade, com tamanho máximo de 2 MB | [OBS49](../elicitacao/tecnicas/observacao.md#requisitos-elicitados), [AD32](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RNF6   | O histórico de vacinas deve ser armazenado em servidores seguros, em conformidade com a LGPD | [OBS50](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF7   | O acesso aos detalhes de cada vacina deve ser protegido por criptografia ponta a ponta | [OBS51](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF8   | As informações de ajuda relacionadas a exames devem ser exibidas em uma interface amigável, seguindo padrões de usabilidade | [OBS52](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF9   | Os resultados de exames laboratoriais devem ser apresentados em formato padronizado e visualmente acessível | [OBS53](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF10  | Os dados sobre exames laboratoriais devem ser carregados de maneira otimizada, mesmo em conexões lentas | [OBS54](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF11  | Os documentos de resultados de exames laboratoriais devem ser exportados em formatos amplamente compatíveis, como PDF ou JPEG | [OBS55](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF12  | O aplicativo deve exibir informações sobre medicamentos em uma interface responsiva e acessível | [OBS56](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF13  | O histórico de medicamentos deve ser armazenado em servidores redundantes para garantir alta disponibilidade | [OBS57](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF14  | A busca por medicamentos deve apresentar resultados relevantes em menos de 2 segundos | [OBS58](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF15  | A busca de medicamentos por nome e dosagem deve ser sensível a erros de digitação | [OBS59](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF16  | A autorização para retirada de medicamentos deve ser confirmada com autenticação segura do usuário | [OBS60](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF17  | Os medicamentos recebidos pelo Programa Farmácia Popular devem ser exibidos em ordem cronológica | [OBS61](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF18  | A seção de ajuda do Programa Dignidade Menstrual deve seguir diretrizes de acessibilidade (WCAG 2.1) | [OBS62](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF19  | As autorizações para participação no Programa Dignidade Menstrual devem ser processadas em menos de 5 segundos | [OBS63](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF20  | O documento referente à autorização do Programa Dignidade Menstrual deve ser exportado em formato PDF com validação digital | [OBS64](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF21  | A localização do dispositivo do usuário deve ser acessada apenas com consentimento explícito e armazenada temporariamente | [OBS65](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF22  | O aplicativo deve usar APIs de geolocalização eficientes e de baixo consumo de bateria | [OBS66](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF23  | As opções de estabelecimentos de saúde devem ser carregadas em menos de 2 segundos | [OBS67](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF24  | A lista de estabelecimentos de saúde recentes deve ser atualizada automaticamente sem comprometer o desempenho | [OBS68](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF25  | O agendamento de consultas deve ser sincronizado em tempo real com os sistemas do SUS | [OBS69](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF26  | As informações sobre consultas médicas ou exames devem ser exibidas com visualização amigável e intuitiva | [OBS70](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF27  | O registro de atendimentos ou internações deve ser armazenado de forma segura em servidores certificados | [OBS71](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF28  | Os contatos de profissionais de saúde devem ser exibidos em uma lista organizada, de fácil navegação | [OBS72](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF29  | As informações de emergência devem ser acessíveis rapidamente, com opção de busca por nome ou especialidade | [OBS73](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF30  | Os registros de saúde do usuário devem ser apresentados em gráficos interativos e de fácil interpretação | [OBS74](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF31  | As informações sobre Pressão, Glicose e IMC devem ser armazenadas de forma criptografada para garantir a privacidade | [OBS75](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF32  | O aplicativo deve garantir alta disponibilidade, com no mínimo 99,5% de uptime | [OBS76](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF33  | Os dados relacionados a alergias devem ser carregados rapidamente e protegidos contra acesso não autorizado | [OBS77](../elicitacao/tecnicas/observacao.md#requisitos-elicitados) |
    | RNF34  | Os dados pessoais dos pacientes devem ser protegidos por criptografia AES-256. | [AD14](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RNF35  | O sistema deverá ser compatível com dispositivos Android e iOS. | [AD15](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RNF36  | O armazenamento e processamento dos dados pessoais deverão estar em conformidade com a LGPD. | [AD16](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RNF37  | O termo de consentimento deverá ser exibido em até 5 segundos após a solicitação, em dispositivos com conexão 4G. | [AD19](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RNF38  | O design do termo de consentimento deverá ser responsivo, adaptando-se a diferentes tamanhos de tela. | [AD20](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RNF39  | As informações sobre os dados coletados deverão ser apresentadas em linguagem acessível, seguindo o padrão de leitura de nível intermediário. | [AD21](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RNF40  | O sistema deverá usar conexões criptografadas (TLS 1.2 ou superior) para comunicação com os servidores do CADSUS. | [AD23](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RNF41  | O sistema deverá atualizar as informações presentes no cartão de vacinação em até 10 dias após o registro dos dados no sistema do Ministério da Saúde. | [AD28](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RNF42  | A notificação de consultas agendadas deverá ser feita com pelo menos 12 horas de antecedência. | [AD31](../elicitacao/tecnicas/analise-de-documentos.md#requisitos-elicitados) |
    | RNF43  | A aplicação pode receber informações do usuário através de biosensores | [EN01](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RNF44  | O fluxo para solicitar medicamentos deve ser concluído em até 5 cliques/telas | [EN14](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RNF45  | A aplicação deve processar a solicitação de medicamentos e fornecer uma resposta em até 5 segundos | [EN15](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RNF46  | O resultado da consulta de pedidos de medicamento deve ser exibido em ordem cronológica | [EN16](../elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
    | RNF47  | A receita médica deve ser exportada em formato PDF de alta qualidade, com tamanho máximo de 2 MB | [GF08](../elicitacao/tecnicas/grupo-de-foco.md#requisitos-elicitados) |
    | RNF48  | O resultado da consulta de receitas médicas deve ser exibido em ordem cronológica | [GF09](../elicitacao/tecnicas/grupo-de-foco.md#requisitos-elicitados) |

    </center>

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>


## Elos de Rastreabilidade

Elos de rastreabilidade representam as relações entre os elementos de um sistema (requisitos, artefatos, casos de uso, testes etc.) para garantir coerência e controle durante o ciclo de vida do projeto. Eles são fundamentais para rastrear:

- A origem de um requisito (elicitado a partir de stakeholders ou documentos).
- Como ele é implementado e testado.
- Quais dependências ele possui (em relação a recursos, subsistemas ou responsabilidades).

### Tipos de Elos de Rastreabilidade

<div align="center">
    <p><strong>Tabela 4 – Tipos de Elos de Rastreabiliadade</strong></p>
</div>

<center>

| Tipo de Elo      | Descrição                                                                        |
| :--------------- | -------------------------------------------------------------------------------- |
| Satisfação       | Indica que um requisito é atendido por um artefato ou funcionalidade específica. |
| Recurso          | Relaciona um requisito à necessidade de um recurso, como hardware ou software.   |
| Responsabilidade | Associa pessoas ou equipes a tarefas específicas ligadas aos requisitos.         |
| Representação    | Liga os requisitos a modelos que os detalham, como diagramas ou tabelas.         |
| Alocado          | Conecta requisitos a subsistemas ou componentes designados.                      |
| Agregação        | Indica que um requisito ou artefato é composto por outros elementos menores.     |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>


### Elos Funcionais de Rastreabilidade

??? note "Tabela 5"

    <div align="center">
        <p><strong>Tabela 5 – Elos (ou vínculos) funcionais de rastreabilidade</strong></p>
    </div>

    <center>

    | ID   | Requisito Funcional | Tipo de Elo | Nível de Elo       | Descrição |
    | :--- | :------------------ | :---------- | :----------------- | --------- |
    | EF1  | [RF1](../elicitacao/requisitos-elicitados.md#RF1) | Representação | Desenvolvimento    | O requisito é representado no diagrama de contexto que descreve o login via Gov.br. |
    | EF2  | [RF2](../elicitacao/requisitos-elicitados.md#RF2) | Satisfação    | Organizacional     | O requisito é atendido pela funcionalidade de ajuda informativa na seção de Vacinas. |
    | EF3  | [RF3](../elicitacao/requisitos-elicitados.md#RF3) | Agregação     | Gerencial          | A funcionalidade de acesso à Carteira Nacional de Vacinação Digital compõe o módulo de histórico de vacinação. |
    | EF4  | [RF4](../elicitacao/requisitos-elicitados.md#RF4) | Recurso       | Desenvolvimento    | Requer a funcionalidade de seleção de idioma para o certificado de vacinação. |
    | EF5  | [RF5](../elicitacao/requisitos-elicitados.md#RF5) | Representação | Desenvolvimento    | Exportação da Carteira de Vacinação Digital está vinculada ao modelo de geração de PDFs. |
    | EF6  | [RF6](../elicitacao/requisitos-elicitados.md#RF6) | Satisfação    | Ambiental          | O histórico de vacinas atende à necessidade de rastreamento de imunizações anteriores. |
    | EF7  | [RF7](../elicitacao/requisitos-elicitados.md#RF7) | Alocado       | Desenvolvimento    | Detalhes de cada vacina estão alocados no módulo de consultas detalhadas. |
    | EF8  | [RF8](../elicitacao/requisitos-elicitados.md#RF8) | Recurso       | Organizacional     | O recurso de ajuda informativa está integrado à seção de Exames. |
    | EF9  | [RF9](../elicitacao/requisitos-elicitados.md#RF9) | Representação | Desenvolvimento    | Exames laboratoriais realizados são exibidos no histórico médico do usuário. |
    | EF10 | [RF10](../elicitacao/requisitos-elicitados.md#RF10) | Satisfação    | Gerencial          | Os resultados de exames atendem à necessidade de informações detalhadas para o paciente. |
    | EF11 | [RF11](../elicitacao/requisitos-elicitados.md#RF11) | Recurso       | Desenvolvimento    | O recurso de exportação de exames utiliza o gerador de relatórios em PDF e JPEG. |
    | EF12 | [RF12](../elicitacao/requisitos-elicitados.md#RF12) | Satisfação    | Organizacional     | A ajuda informativa na seção de Medicamentos é satisfatória às necessidades do usuário. |
    | EF13 | [RF13](../elicitacao/requisitos-elicitados.md#RF13) | Alocado       | Desenvolvimento    | O histórico de medicamentos é alocado no módulo de gerenciamento de medicamentos. |
    | EF14 | [RF14](../elicitacao/requisitos-elicitados.md#RF14) | Recurso       | Desenvolvimento    | A busca por medicamentos utiliza uma interface de pesquisa integrada. |
    | EF15 | [RF15](../elicitacao/requisitos-elicitados.md#RF15) | Representação | Gerencial          | A funcionalidade de busca por nome e dosagem está representada no fluxo de busca rápida. |
    | EF16 | [RF16](../elicitacao/requisitos-elicitados.md#RF16) | Satisfação    | Organizacional     | A autorização de retirada de medicamentos satisfaz os critérios de segurança definidos. |
    | EF17 | [RF17](../elicitacao/requisitos-elicitados.md#RF17) | Agregação     | Organizacional     | Medicamentos recebidos pelo Farmácia Popular compõem o histórico farmacológico. |
    | EF18 | [RF18](../elicitacao/requisitos-elicitados.md#RF18) | Satisfação    | Ambiental          | Ajuda informativa sobre Dignidade Menstrual atende a critérios de acessibilidade. |
    | EF19 | [RF19](../elicitacao/requisitos-elicitados.md#RF19) | Alocado       | Gerencial          | A emissão de autorizações para o Programa Dignidade Menstrual está alocada no módulo de autorizações. |
    | EF20 | [RF20](../elicitacao/requisitos-elicitados.md#RF20) | Recurso       | Desenvolvimento    | Exportação do documento do Programa Dignidade Menstrual utiliza o gerador de PDFs. |
    | EF21 | [RF21](../elicitacao/requisitos-elicitados.md#RF21) | Representação | Desenvolvimento    | Ajuda informativa da Rede de Saúde está representada na interface de navegação. |
    | EF22 | [RF22](../elicitacao/requisitos-elicitados.md#RF22) | Recurso       | Organizacional     | A funcionalidade de permissão de localização é vinculada ao acesso aos serviços locais. |
    | EF23 | [RF23](../elicitacao/requisitos-elicitados.md#RF23) | Alocado       | Desenvolvimento    | Armazenamento da localização é alocado em servidores seguros. |
    | EF24 | [RF24](../elicitacao/requisitos-elicitados.md#RF24) | Satisfação    | Organizacional     | Oferecer estabelecimentos de saúde próximos satisfaz necessidades geográficas do usuário. |
    | EF25 | [RF25](../elicitacao/requisitos-elicitados.md#RF25) | Representação | Desenvolvimento    | Estabelecimentos recentes vinculados ao usuário estão representados no histórico local. |
    | EF26 | [RF26](../elicitacao/requisitos-elicitados.md#RF26) | Satisfação    | Gerencial          | Ajuda informativa sobre agendamentos atende à necessidade de orientação do usuário. |
    | EF27 | [RF27](../elicitacao/requisitos-elicitados.md#RF27) | Representação | Desenvolvimento    | Consultas e exames estão representados no calendário interativo do aplicativo. |
    | EF28 | [RF28](../elicitacao/requisitos-elicitados.md#RF28) | Alocado       | Gerencial          | Agendamentos estão alocados no módulo de gestão de consultas. |
    | EF29 | [RF29](../elicitacao/requisitos-elicitados.md#RF29) | Recurso       | Organizacional     | Ajuda informativa sobre atendimento e internação utiliza a base de dados de orientações. |
    | EF30 | [RF30](../elicitacao/requisitos-elicitados.md#RF30) | Satisfação    | Ambiental          | Exibição dos registros de internação atende aos requisitos de transparência médica. |
    | EF31 | [RF31](../elicitacao/requisitos-elicitados.md#RF31) | Representação | Desenvolvimento    | Ajuda informativa sobre contatos está representada no diretório de contatos. |
    | EF32 | [RF32](../elicitacao/requisitos-elicitados.md#RF32) | Satisfação    | Gerencial          | Exibição de contatos atende às necessidades de conexão do usuário com profissionais. |
    | EF33 | [RF33](../elicitacao/requisitos-elicitados.md#RF33) | Alocado       | Desenvolvimento    | Adicionar contato de emergência está alocado no módulo de gerenciamento de contatos. |
    | EF34 | [RF34](../elicitacao/requisitos-elicitados.md#RF34) | Representação | Organizacional     | Ajuda informativa sobre Diário de Saúde está no fluxo de introdução do módulo. |
    | EF35 | [RF35](../elicitacao/requisitos-elicitados.md#RF35) | Satisfação    | Ambiental          | Exibição de registros de saúde atende ao monitoramento contínuo do paciente. |
    | EF36 | [RF36](../elicitacao/requisitos-elicitados.md#RF36) | Representação | Desenvolvimento    | Registros de pressão são representados em gráficos no diário de saúde. |
    | EF37 | [RF37](../elicitacao/requisitos-elicitados.md#RF37) | Alocado       | Desenvolvimento    | Adição de registros de pressão é alocada no módulo de monitoramento de saúde. |
    | EF38 | [RF38](../elicitacao/requisitos-elicitados.md#RF38) | Representação | Gerencial          | Registros de glicose estão representados na interface de gráficos interativos. |
    | EF39 | [RF39](../elicitacao/requisitos-elicitados.md#RF39) | Recurso       | Desenvolvimento    | Adição de registros de glicose utiliza o formulário de entrada padrão. |
    | EF40 | [RF40](../elicitacao/requisitos-elicitados.md#RF40) | Representação | Organizacional     | Registros de IMC estão representados no painel de saúde integrado. |
    | EF41 | [RF41](../elicitacao/requisitos-elicitados.md#RF41) | Alocado       | Desenvolvimento    | Adição de registros de IMC está alocada no formulário de acompanhamento de saúde. |
    | EF42 | [RF42](../elicitacao/requisitos-elicitados.md#RF42) | Satisfação    | Ambiental          | Ajuda informativa sobre alergias atende aos requisitos de orientação médica. |
    | EF43 | [RF43](../elicitacao/requisitos-elicitados.md#RF43) | Representação | Desenvolvimento    | Exibição de alergias está representada no histórico médico do paciente. |
    | EF44 | [RF44](../elicitacao/requisitos-elicitados.md#RF44) | Alocado       | Desenvolvimento    | Adicionar alergia está alocada no módulo de atualização do histórico médico. |
    | EF45 | [RF45](../elicitacao/requisitos-elicitados.md#RF45) | Satisfação    | Organizacional     | Apresentação do termo de consentimento atende aos critérios de transparência do sistema. |
    | EF46 | [RF46](../elicitacao/requisitos-elicitados.md#RF46) | Representação | Gerencial          | Informações sobre coleta de dados estão representadas no painel de políticas de privacidade. |
    | EF47 | [RF47](../elicitacao/requisitos-elicitados.md#RF47) | Recurso       | Desenvolvimento    | Escolha sobre coleta de dados utiliza o sistema de notificações do aplicativo. |
    | EF48 | [RF48](../elicitacao/requisitos-elicitados.md#RF48) | Alocado       | Desenvolvimento    | Registro da escolha do paciente está alocado no módulo de consentimento. |
    | EF49 | [RF49](../elicitacao/requisitos-elicitados.md#RF49) | Representação | Desenvolvimento    | Permissão de acesso à câmera está representada no fluxo de configuração de permissões. |
    | EF50 | [RF50](../elicitacao/requisitos-elicitados.md#RF50) | Recurso       | Organizacional     | Foto tirada pelo paciente é vinculada ao sistema de reconhecimento facial. |
    | EF51 | [RF51](../elicitacao/requisitos-elicitados.md#RF51) | Alocado       | Desenvolvimento    | Busca no CADSUS está alocada no módulo de integração com bases de dados governamentais. |
    | EF52 | [RF52](../elicitacao/requisitos-elicitados.md#RF52) | Recurso       | Desenvolvimento    | Dados buscados na RNDS utilizam o sistema de sincronização em tempo real. |
    | EF53 | [RF53](../elicitacao/requisitos-elicitados.md#RF53) | Representação | Gerencial          | Solicitação de remoção de dados está representada no painel de configurações do usuário. |
    | EF54 | [RF54](../elicitacao/requisitos-elicitados.md#RF54) | Satisfação    | Ambiental          | Exibição do status na lista de espera para transplantes atende a requisitos de transparência. |
    | EF55 | [RF55](../elicitacao/requisitos-elicitados.md#RF55) | Recurso       | Desenvolvimento    | Exportação do certificado de vacinação utiliza o gerador de documentos PDF. |
    | EF56 | [RF56](../elicitacao/requisitos-elicitados.md#RF56) | Representação | Organizacional     | Preenchimento de autodeclaração está representado no formulário de dados pessoais. |
    | EF57 | [RF57](../elicitacao/requisitos-elicitados.md#RF57) | Satisfação    | Gerencial          | Notificação sobre consultas agendadas atende aos requisitos de comunicação do sistema. |
    | EF58 | [RF58](../elicitacao/requisitos-elicitados.md#RF58) | Alocado       | Desenvolvimento    | Agendamento de exames está alocado no módulo de gestão de exames. |
    | EF59 | [RF59](../elicitacao/requisitos-elicitados.md#RF59) | Representação | Organizacional     | Solicitação de licença saúde está representada no painel de funcionalidades do servidor. |
    | EF60 | [RF60](../elicitacao/requisitos-elicitados.md#RF60) | Satisfação    | Gerencial          | Acompanhamento de solicitações atende aos critérios de transparência do usuário. |
    | EF61 | [RF61](../elicitacao/requisitos-elicitados.md#RF61) | Representação | Desenvolvimento    | Acompanhamento de vacinação está representado no painel de saúde. |
    | EF62 | [RF62](../elicitacao/requisitos-elicitados.md#RF62) | Recurso       | Organizacional     | Consulta de pedidos de medicamentos utiliza o sistema de busca integrada. |
    | EF63 | [RF63](../elicitacao/requisitos-elicitados.md#RF63) | Representação | Desenvolvimento    | Consulta de recebimentos de medicamentos está no histórico farmacológico. |
    | EF64 | [RF64](../elicitacao/requisitos-elicitados.md#RF64) | Alocado       | Desenvolvimento    | Consulta de agendamentos de exames está alocada no módulo de gestão de consultas. |
    | EF65 | [RF65](../elicitacao/requisitos-elicitados.md#RF65) | Satisfação    | Gerencial          | Consulta de resultados de exames atende aos critérios de acesso rápido a informações. |
    | EF66 | [RF66](../elicitacao/requisitos-elicitados.md#RF66) | Representação | Organizacional     | Notificação de cancelamento de agendamentos está representada no painel de alertas. |
    | EF67 | [RF67](../elicitacao/requisitos-elicitados.md#RF67) | Recurso       | Desenvolvimento    | Realização de pedidos de medicamentos utiliza o sistema de requisição automática. |
    | EF68 | [RF68](../elicitacao/requisitos-elicitados.md#RF68) | Representação | Organizacional     | Aplicação de filtros na consulta de medicamentos está no painel de gestão farmacológica. |
    | EF69 | [RF69](../elicitacao/requisitos-elicitados.md#RF69) | Representação | Gerencial          | Histórico de vacinação pré-pandemia está representado no registro consolidado. |
    | EF70 | [RF70](../elicitacao/requisitos-elicitados.md#RF70) | Satisfação    | Ambiental          | Validação médica de declarações de alergia atende aos critérios de conformidade médica. |
    | EF71 | [RF71](../elicitacao/requisitos-elicitados.md#RF71) | Representação | Desenvolvimento    | Consulta de receitas médicas está representada no histórico clínico do paciente. |
    | EF72 | [RF72](../elicitacao/requisitos-elicitados.md#RF72) | Alocado       | Desenvolvimento    | Notificação de atualizações está alocada no sistema de informações dinâmicas. |
    | EF73 | [RF73](../elicitacao/requisitos-elicitados.md#RF73) | Representação | Organizacional     | Destaque de conteúdos pertinentes está representado na interface de navegação. |
    | EF74 | [RF74](../elicitacao/requisitos-elicitados.md#RF74) | Recurso       | Desenvolvimento    | Exportação de receitas médicas utiliza o gerador de PDFs do sistema. |
    | EF75 | [RF75](../elicitacao/requisitos-elicitados.md#RF75) | Satisfação    | Gerencial          | Oferecimento de agendamento de consultas atende aos requisitos de acessibilidade. |

    </center>

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>


### Elos Não Funcionais de Rastreabilidade

??? note "Tabela 6"

    <div align="center">
        <p><strong>Tabela 6 – Elos (ou vínculos) não funcionais de rastreabilidade</strong></p>
    </div>

    <center>

    | ID   | Requisito Não Funcional | Tipo de Elo   | Nível de Elo       | Descrição |
    | :--- | :---------------------- | :------------ | :----------------- | --------- |
    | ENF1 | [RNF1](../elicitacao/requisitos-elicitados.md#RNF1) | Representação | Desenvolvimento    | O requisito de autenticação segura (OAuth 2.0) é representado no diagrama de login seguro. |
    | ENF2 | [RNF2](../elicitacao/requisitos-elicitados.md#RNF2) | Satisfação    | Ambiental          | A acessibilidade das informações de ajuda atende às diretrizes para usuários com deficiência. |
    | ENF3 | [RNF3](../elicitacao/requisitos-elicitados.md#RNF3) | Satisfação    | Gerencial          | O carregamento do histórico de vacinação em menos de 3 segundos atende às expectativas de performance. |
    | ENF4 | [RNF4](../elicitacao/requisitos-elicitados.md#RNF4) | Recurso       | Organizacional     | O suporte a três idiomas para certificados de vacinação depende da funcionalidade de tradução integrada. |
    | ENF5 | [RNF5](../elicitacao/requisitos-elicitados.md#RNF5) | Representação | Desenvolvimento    | O formato PDF de alta qualidade para certificados de vacinação está representado no módulo de exportação. |
    | ENF6 | [RNF6](../elicitacao/requisitos-elicitados.md#RNF6) | Alocado       | Organizacional     | O armazenamento do histórico de vacinas é alocado em servidores seguros, conforme a LGPD. |
    | ENF7 | [RNF7](../elicitacao/requisitos-elicitados.md#RNF7) | Representação | Desenvolvimento    | A criptografia ponta a ponta para acesso aos detalhes de vacinas está representada no fluxo de segurança. |
    | ENF8 | [RNF8](../elicitacao/requisitos-elicitados.md#RNF8) | Satisfação    | Organizacional     | As informações de ajuda relacionadas a exames atendem aos padrões de usabilidade definidos. |
    | ENF9 | [RNF9](../elicitacao/requisitos-elicitados.md#RNF9) | Representação | Desenvolvimento    | A apresentação de resultados de exames está representada no formato padronizado e acessível. |
    | ENF10 | [RNF10](../elicitacao/requisitos-elicitados.md#RNF10) | Satisfação   | Gerencial          | O carregamento otimizado dos dados de exames atende às necessidades de desempenho do sistema. |
    | ENF11 | [RNF11](../elicitacao/requisitos-elicitados.md#RNF11) | Recurso      | Desenvolvimento    | A exportação de documentos de exames utiliza os formatos amplamente compatíveis, como PDF e JPEG. |
    | ENF12 | [RNF12](../elicitacao/requisitos-elicitados.md#RNF12) | Representação | Organizacional     | A interface responsiva para exibição de informações sobre medicamentos está representada no design adaptativo. |
    | ENF13 | [RNF13](../elicitacao/requisitos-elicitados.md#RNF13) | Alocado      | Desenvolvimento    | O histórico de medicamentos está alocado em servidores redundantes para garantir alta disponibilidade. |
    | ENF14 | [RNF14](../elicitacao/requisitos-elicitados.md#RNF14) | Satisfação   | Ambiental          | A busca por medicamentos em menos de 2 segundos atende aos critérios de eficiência do sistema. |
    | ENF15 | [RNF15](../elicitacao/requisitos-elicitados.md#RNF15) | Representação | Gerencial          | A sensibilidade a erros de digitação na busca por medicamentos está representada no sistema de busca inteligente. |
    | ENF16 | [RNF16](../elicitacao/requisitos-elicitados.md#RNF16) | Recurso      | Organizacional     | A autenticação segura do usuário é utilizada para confirmar a autorização de retirada de medicamentos. |
    | ENF17 | [RNF17](../elicitacao/requisitos-elicitados.md#RNF17) | Representação | Desenvolvimento    | A exibição de medicamentos recebidos pelo Programa Farmácia Popular está organizada em ordem cronológica. |
    | ENF18 | [RNF18](../elicitacao/requisitos-elicitados.md#RNF18) | Satisfação   | Ambiental          | A seção de ajuda do Programa Dignidade Menstrual atende às diretrizes de acessibilidade WCAG 2.1. |
    | ENF19 | [RNF19](../elicitacao/requisitos-elicitados.md#RNF19) | Satisfação   | Gerencial          | O processamento das autorizações para o Programa Dignidade Menstrual em menos de 5 segundos atende às expectativas. |
    | ENF20 | [RNF20](../elicitacao/requisitos-elicitados.md#RNF20) | Representação | Desenvolvimento    | O documento do Programa Dignidade Menstrual em formato PDF com validação digital está representado no módulo de exportação. |
    | ENF21 | [RNF21](../elicitacao/requisitos-elicitados.md#RNF21) | Recurso      | Organizacional     | O acesso à localização do dispositivo do usuário utiliza consentimento explícito e armazenamento temporário. |
    | ENF22 | [RNF22](../elicitacao/requisitos-elicitados.md#RNF22) | Recurso      | Ambiental          | APIs de geolocalização eficientes e de baixo consumo de bateria são utilizadas para otimizar o desempenho. |
    | ENF23 | [RNF23](../elicitacao/requisitos-elicitados.md#RNF23) | Satisfação   | Gerencial          | O carregamento das opções de estabelecimentos de saúde em menos de 2 segundos atende aos critérios de performance. |
    | ENF24 | [RNF24](../elicitacao/requisitos-elicitados.md#RNF24) | Representação | Organizacional     | A atualização automática da lista de estabelecimentos recentes está representada no sistema de sincronização. |
    | ENF25 | [RNF25](../elicitacao/requisitos-elicitados.md#RNF25) | Alocado      | Desenvolvimento    | O agendamento de consultas está alocado no módulo de integração com os sistemas do SUS. |
    | ENF26 | [RNF26](../elicitacao/requisitos-elicitados.md#RNF26) | Representação | Organizacional     | A exibição intuitiva das informações sobre consultas médicas está representada no painel de usuário. |
    | ENF27 | [RNF27](../elicitacao/requisitos-elicitados.md#RNF27) | Alocado      | Desenvolvimento    | O armazenamento seguro de registros de internação está alocado em servidores certificados. |
    | ENF28 | [RNF28](../elicitacao/requisitos-elicitados.md#RNF28) | Representação | Gerencial          | A lista de contatos de profissionais de saúde está representada no diretório de navegação. |
    | ENF29 | [RNF29](../elicitacao/requisitos-elicitados.md#RNF29) | Satisfação   | Organizacional     | O acesso rápido às informações de emergência atende às expectativas de usabilidade do sistema. |
    | ENF30 | [RNF30](../elicitacao/requisitos-elicitados.md#RNF30) | Representação | Desenvolvimento    | Os registros de saúde do usuário apresentados em gráficos interativos estão representados no painel de visualização. |
    | ENF31 | [RNF31](../elicitacao/requisitos-elicitados.md#RNF31) | Alocado      | Desenvolvimento    | O armazenamento criptografado de informações sobre pressão, glicose e IMC está alocado no sistema seguro. |
    | ENF32 | [RNF32](../elicitacao/requisitos-elicitados.md#RNF32) | Recurso      | Organizacional     | A garantia de alta disponibilidade com uptime de 99,5% é gerenciada pelo sistema de monitoramento. |
    | ENF33 | [RNF33](../elicitacao/requisitos-elicitados.md#RNF33) | Representação | Desenvolvimento    | Os dados de alergias protegidos contra acesso não autorizado estão representados no módulo de segurança. |
    | ENF34 | [RNF34](../elicitacao/requisitos-elicitados.md#RNF34) | Recurso      | Ambiental          | A criptografia AES-256 é utilizada para proteger os dados pessoais dos pacientes. |
    | ENF35 | [RNF35](../elicitacao/requisitos-elicitados.md#RNF35) | Satisfação   | Organizacional     | A compatibilidade do sistema com dispositivos Android e iOS atende às expectativas de usabilidade. |
    | ENF36 | [RNF36](../elicitacao/requisitos-elicitados.md#RNF36) | Representação | Gerencial          | O armazenamento de dados em conformidade com a LGPD está representado nos fluxos de governança de dados. |
    | ENF37 | [RNF37](../elicitacao/requisitos-elicitados.md#RNF37) | Recurso      | Desenvolvimento    | O tempo de exibição do termo de consentimento em até 5 segundos é garantido pelo sistema de otimização. |
    | ENF38 | [RNF38](../elicitacao/requisitos-elicitados.md#RNF38) | Representação | Organizacional     | O design responsivo do termo de consentimento está representado no modelo adaptativo da interface. |
    | ENF39 | [RNF39](../elicitacao/requisitos-elicitados.md#RNF39) | Satisfação   | Ambiental          | A apresentação das informações de dados coletados em linguagem acessível atende às necessidades dos usuários. |
    | ENF40 | [RNF40](../elicitacao/requisitos-elicitados.md#RNF40) | Representação | Desenvolvimento    | O uso de conexões criptografadas (TLS 1.2 ou superior) está representado no fluxo de segurança de comunicação. |
    | ENF41 | [RNF41](../elicitacao/requisitos-elicitados.md#RNF41) | Satisfação   | Gerencial          | A atualização de informações no cartão de vacinação em até 10 dias atende aos requisitos de eficiência. |
    | ENF42 | [RNF42](../elicitacao/requisitos-elicitados.md#RNF42) | Representação | Organizacional     | A notificação de consultas agendadas com antecedência está representada no módulo de alertas. |
    | ENF43 | [RNF43](../elicitacao/requisitos-elicitados.md#RNF43) | Recurso      | Desenvolvimento    | A coleta de dados de biosensores é gerenciada pelo sistema de integração de dispositivos. |
    | ENF44 | [RNF44](../elicitacao/requisitos-elicitados.md#RNF44) | Satisfação   | Organizacional     | O fluxo para solicitação de medicamentos em até 5 cliques atende aos critérios de usabilidade. |
    | ENF45 | [RNF45](../elicitacao/requisitos-elicitados.md#RNF45) | Representação | Desenvolvimento    | O tempo de processamento de solicitações de medicamentos está representado no módulo de desempenho. |
    | ENF46 | [RNF46](../elicitacao/requisitos-elicitados.md#RNF46) | Satisfação   | Gerencial          | A exibição cronológica de pedidos de medicamentos atende às expectativas de organização do sistema. |
    | ENF47 | [RNF47](../elicitacao/requisitos-elicitados.md#RNF47) | Representação | Organizacional     | A exportação de receitas médicas em PDF está representada no módulo de documentação. |
    | ENF48 | [RNF48](../elicitacao/requisitos-elicitados.md#RNF48) | Representação | Desenvolvimento    | A exibição cronológica de receitas médicas está representada no histórico clínico do paciente. |

    </center>

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>


## 📚 Bibliografia

> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. _Engenharia de Requisitos: software orientado ao negócio_. Rio de Janeiro: Brasport, 2016.
>
> WIEGERS, Karl; BEATTY, Joy. _Software Requirements. Third Edition_. Redmond, WA: Microsoft Press, 2013.
>
> TORANZO, M.; CASTRO, J.; MELO, E. _Uma proposta para melhorar o rastreamento de requisitos_. In: WER – Workshop em Engenharia de Requisitos. Valencia, Espanha, 2002.

## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação da estrutura inicial do documento referente ao Backward From. | [Artur Ricardo](https://github.com/algorithmorphic) | 16/01/2025 | [Pedro Lopes](https://github.com/pLopess) | 19/01/2025 |
| `1.1`  | Atualização da bibliografia. | [Artur Ricardo](https://github.com/algorithmorphic) | 17/01/2025 |  |  |
| `1.2`  | Adição da tabela de rastreabilidade para trás referente aos requisitos funcionais elicitados e correção de título. | [Artur Ricardo](https://github.com/algorithmorphic) | 19/01/2025 | [Pedro Lopes](https://github.com/pLopess) | 19/01/2025 |
| `1.3`  | Adição da tabela de rastreabilidade para trás referente aos requisitos funcionais não elicitados. | [Artur Ricardo](https://github.com/algorithmorphic) | 19/01/2025 | [Pedro Lopes](https://github.com/pLopess) | 19/01/2025 |
| `1.4`  | Correção na tabela de rastreabilidade retrospectiva referente aos requisitos funcionais elicitados, atualização das legendas, reorganização das tabelas e criação das tabelas referentes aos elos funcionais e não funcionais. | [Artur Ricardo](https://github.com/algorithmorphic) | 19/01/2025 | [Pedro Lopes](https://github.com/pLopess) | 19/01/2025 |
| `1.5`  | Atualização das informações a respeito dos campos "Introdução" e "Metodologia". | [Artur Ricardo](https://github.com/algorithmorphic) | 19/01/2025 | [Pedro Lopes](https://github.com/pLopess) | 19/01/2025 |
| `1.6`  | Atualização das referências bibliográficas. | [Artur Ricardo](https://github.com/algorithmorphic) | 19/01/2025 | [Pedro Lopes](https://github.com/pLopess) | 19/01/2025 |
