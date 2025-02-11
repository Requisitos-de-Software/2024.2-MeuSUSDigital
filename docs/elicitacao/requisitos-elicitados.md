# Requisitos Elicitados



## Introdução

Requisitos são condições ou capacidades que um sistema (como um aplicativo, por exemplo) deve atender para resolver problemas ou alcançar objetivos, documentando necessidades e restrições. Os requisitos funcionais definem as funcionalidades específicas do sistema, enquanto os não funcionais abrangem qualidades como desempenho, segurança e usabilidade. Implementá-los adequadamente, após sua elicitação por meio de uma ou mais técnicas, é crucial para alinhar o desenvolvimento às expectativas, reduzir custos e retrabalho, garantir qualidade e minimizar falhas, criando sistemas eficazes e alinhados às necessidades dos usuários.

Este documento reúne todos os requisitos, tanto funcionais quanto não funcionais, elicitados através das técnicas de [Análise de Documentos](tecnicas/analise-de-documentos.md), [Entrevista](tecnicas/entrevista.md), [Grupo de Foco](tecnicas/grupo-de-foco.md), [Introspecção](tecnicas/introspeccao.md), [Observação](tecnicas/observacao.md) e [Questionário](analise-perfil-usuario/questionario.md).



## Metodologia

Optamos por dispor todos os requisitos elicitados na **Tabela 2**. A tabela contém os campos "Tipo", que trata da sigla referente ao tipo de requisito elicitado, "Descrição", onde a funcionalidade do requisito é descrita, "Rastreabilidade", que contém a(s) sigla(s)* referente(s) a cada técnica utilizada durante cada elicitação, e o campo "Implementado", onde é possível identificar se o requisito equivalente foi ou não implementado no Meu SUS Digital.

Já na **Tabela 1**, optamos por disponibilizar uma legenda para cada uma das siglas utilizadas na **Tabela 2**.

\* Cada sigla contém um link que redireciona para o documento respectivo à técnica em questão. 

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
| GFn  | n-ésimo Requisito elicitado pela técnica de Grupo de Foco         |
| INTn | n-ésimo Requisito elicitado pela técnica de Introspecção          |
| OBSn | n-ésimo Requisito elicitado pela técnica de Observação            |
| QUEn | n-ésimo Requisito elicitado pela técnica de Questionário          |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>



## Requisitos

Na **Tabela 2**, temos a relação de requisitos elicitados para o Meu SUS Digital, bem como sua rastreabilidade (técnicas por meio das quais foram elicitados) e implementação (se foram ou não implementados no Meu SUS Digital). 

<div align="center">
    <p><strong>Tabela 2 – Requisitos elicitados</strong></p>
</div>

<center>

| Tipo | Descrição | Rastreabilidade | Implementado |
| :--: | --------- | --------------- | :----------: |
| <a id="RF1"></a>RF1 | O sistema deve permitir que o paciente realize login por meio de uma conta Gov.br | [OBS1](tecnicas/observacao.md#requisitos-elicitados), [AD09](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF2"></a>RF2 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Vacinas | [OBS2](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF3"></a>RF3 | O aplicativo deve disponibilizar ao usuário o acesso à sua Carteira Nacional de Vacinação Digital | [OBS3](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF4"></a>RF4 | O aplicativo deve permitir que o usuário selecione o idioma do certificado referente à sua Carteira Nacional de Vacinação Digital | [OBS4](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF5"></a>RF5 | O aplicativo deve permitir que o usuário exporte ou realize o download do documento referente à sua Carteira Nacional de Vacinação Digital | [OBS5](tecnicas/observacao.md#requisitos-elicitados), [AD24](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF6"></a>RF6 | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de vacinas | [OBS6](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF7"></a>RF7 | O aplicativo deve disponibilizar ao usuário o acesso aos detalhes de cada vacina | [OBS7](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF8"></a>RF8 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Exames | [OBS8](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF9"></a>RF9 | O aplicativo deve permitir a visualização dos exames laboratoriais realizados | [OBS9](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF10"></a>RF10 | O aplicativo deve permitir a visualização dos resultados e demais informações a respeito dos exames laboratoriais realizados | [OBS10](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF11"></a>RF11 | O aplicativo deve permitir a exportação/download do documento contendo o resultado e demais informações a respeito de cada exame laboratorial realizado | [OBS11](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF12"></a>RF12 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Medicamentos | [OBS12](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF13"></a>RF13 | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de medicamentos recebidos | [OBS13](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF14"></a>RF14 | O aplicativo deve permitir que o usuário adicione um medicamento recebido por meio de programas de dispensação do Governo Federal através de um mecanismo de busca | [OBS14](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF15"></a>RF15 | O aplicativo deve permitir que o usuário possa realizar a busca por um medicamento através do nome e dosagem do mesmo | [OBS15](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF16"></a>RF16 | O aplicativo deve fornecer ao usuário, em adesão ao Programa Farmácia Popular, a opção de autorizar ou não a retirada de medicamentos em seu CPF | [OBS16](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF17"></a>RF17 | O aplicativo deve permitir que o usuário possa verificar os medicamentos recebidos pelo Programa Farmácia Popular | [OBS17](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF18"></a>RF18 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Dignidade Menstrual | [OBS18](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF19"></a>RF19 | Caso o usuário atenda aos critérios do Programa, o aplicativo deve permitir que o usuário emita uma autorização para participar do Programa Dignidade Menstrual | [OBS19](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF20"></a>RF20 | O aplicativo deve permitir que o usuário exporte/baixe o documento referente à autorização de participação do Programa Dignidade Menstrual | [OBS20](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF21"></a>RF21 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Rede de Saúde | [OBS21](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF22"></a>RF22 | O aplicativo deve pedir permissão de acesso à localização do dispositivo do usuário | [OBS22](tecnicas/observacao.md#requisitos-elicitados), [AD05](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF23"></a>RF23 | O aplicativo deve armazenar a localização do dispositivo do usuário | [OBS23](tecnicas/observacao.md#requisitos-elicitados), [AD06](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF24"></a>RF24 | O aplicativo deve oferecer opções de estabelecimentos de saúde a fim de que o usuário possa identificar àqueles próximos à sua localização, de acordo com o tipo de serviço desejado | [OBS24](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF25"></a>RF25 | O aplicativo deve permitir que o usuário possa identificar os estabelecimentos de saúde recentes vinculados a ele | [OBS25](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF26"></a>RF26 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Agendamentos | [OBS26](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF27"></a>RF27 | O aplicativo deve exibir as consultas médicas ou exames de saúde do usuário | [OBS27](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF28"></a>RF28 | O aplicativo deve possibilitar o agendamento de consultas médicas ou exames de saúde | [OBS28](tecnicas/observacao.md#requisitos-elicitados), [AD27](tecnicas/analise-de-documentos.md#requisitos-elicitados), [EN02](tecnicas/entrevista.md#requisitos-elicitados), [GF02](tecnicas/grupo-de-foco.md#requisitos-elicitados) | Sim |
| <a id="RF29"></a>RF29 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Atendimento e Internação | [OBS29](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF30"></a>RF30 | O aplicativo deve exibir os registros de atendimentos ou internações do usuário | [OBS30](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF31"></a>RF31 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Contatos | [OBS31](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF32"></a>RF32 | O aplicativo deve exibir contatos de profissionais de saúde | [OBS32](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF33"></a>RF33 | O aplicativo deve permitir que o usuário adicione o contato de um profissional de saúde em casos de emergência | [OBS33](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF34"></a>RF34 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Diário de Saúde | [OBS34](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF35"></a>RF35 | O aplicativo deve exibir todos os registros de saúde do usuário | [OBS35](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF36"></a>RF36 | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Pressão | [OBS36](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF37"></a>RF37 | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Pressão | [OBS37](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF38"></a>RF38 | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Glicose | [OBS38](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF39"></a>RF39 | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Glicose | [OBS39](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF40"></a>RF40 | O aplicativo deve exibir os registros de saúde do usuário referentes ao seu IMC | [OBS40](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF41"></a>RF41 | O aplicativo deve permitir que o usuário adicione um registro de saúde referente ao seu IMC | [OBS41](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF42"></a>RF42 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Alergias | [OBS42](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF43"></a>RF43 | O aplicativo deve exibir as alergias que usuário possui | [OBS43](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF44"></a>RF44 | O aplicativo deve permitir que o usuário adicione uma alergia | [OBS44](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RF45"></a>RF45 | O sistema deverá apresentar o termo de consentimento. | [AD01](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF46"></a>RF46 | O sistema deverá informar quais dados serão coletados. | [AD02](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF47"></a>RF47 | O sistema deverá permitir que o paciente escolha entre aceitar ou recusar a coleta de seus dados pessoais. | [AD03](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF48"></a>RF48 | O sistema deverá registrar a escolha do paciente em relação à coleta de seus dados pessoais. | [AD04](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF49"></a>RF49 | O sistema deverá pedir permissão de acesso à câmera do dispositivo. | [AD07](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF50"></a>RF50 | O sistema deverá permitir ao paciente tirar sua foto utilizando a câmera do dispositivo. | [AD08](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF51"></a>RF51 | O sistema deverá buscar no CADSUS os dados do paciente (Nome, data de nascimento, sexo, filiação, nacionalidade, e-mail, endereço e telefone) utilizando o CPF associado à conta Gov.br informada no login. | [AD10](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF52"></a>RF52 | O sistema deverá buscar na RNDS os dados do paciente (Histórico clínico, dados de vacinação e resultados de exames) utilizando o CPF associado à conta Gov.br informada no login. | [AD11](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF53"></a>RF53 | O sistema deverá permitir que o paciente solicite a remoção de seus dados pessoais do aplicativo. | [AD12](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF54"></a>RF54 | O sistema deverá apresentar o *status* e posição do usuário na lista de espera para transplante de órgão e tecido. | [AD18](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF55"></a>RF55 | O aplicativo deve permitir que o usuário exporte ou realize o download do documento referente ao Certificado de vacinação nacional de Covid-19. | [AD25](tecnicas/analise-de-documentos.md#requisitos-elicitados), [OBS45](tecnicas/observacao.md#OBS45) | Sim |
| <a id="RF56"></a>RF56 | O sistema deverá permitir que o paciente preencha informações de autodeclaração com nome social, raça/cor e endereço. | [AD26](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF57"></a>RF57 | O sistema deverá notificar o paciente sobre consultas agendadas, informando o tipo de consulta, a data, o horário e o local da consulta. | [AD30](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RF58"></a>RF58 | A aplicação permite agendar exames | [EN03](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| <a id="RF59"></a>RF59 | A aplicação permite ao servidor solicitar licença saúde | [EN04](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| <a id="RF60"></a>RF60 | A aplicação permite acompanhar o andamento de solicitações de medicamentos | [EN05](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| <a id="RF61"></a>RF61 | A aplicação permite acompanhar a vacinação | [EN 06](tecnicas/entrevista.md#requisitos-elicitados) | Sim |
| <a id="RF62"></a>RF62 | A aplicação permite consultar pedidos/solicitações de medicamentos | [EN 07](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| <a id="RF63"></a>RF63 | A aplicação permite consultar recebimentos de medicamento | [EN 08](tecnicas/entrevista.md#requisitos-elicitados) | Sim |
| <a id="RF64"></a>RF64 | A aplicação permite consultar os agendamentos de exames | [EN 09](tecnicas/entrevista.md#requisitos-elicitados) | Sim |
| <a id="RF65"></a>RF65 | A aplicação permite consultar os resultados de exames | [EN10](tecnicas/entrevista.md#requisitos-elicitados) | Sim |
| <a id="RF66"></a>RF66 | A aplicação notifica o cancelamento de agendamentos | [EN11](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| <a id="RF67"></a>RF67 | A aplicação permite realizar pedidos/solicitações de medicamentos | [EN12](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| <a id="RF68"></a>RF68 | A aplicação permite ao paciente aplicar filtro de pesquisa ("Em processamento", "A caminho", "Entregue") para a consulta de pedidos/solicitações de medicamentos | [EN13](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| <a id="RF69"></a>RF69 | O aplicativo mostra o histórico de vacinação pré-pandemia | [GF01](tecnicas/grupo-de-foco.md#requisitos-elicitados) | Não |
| <a id="RF70"></a>RF70 | O aplicativo permite validação médica de declarações de alergia, mediante laudo. Essa validação deve ser visivelmente sinalizada ao paciente | [GF03](tecnicas/grupo-de-foco.md#requisitos-elicitados) | Não |
| <a id="RF71"></a>RF71 | O aplicativo permite consultar receitas médicas | [GF04](tecnicas/grupo-de-foco.md#requisitos-elicitados) | Não |
| <a id="RF72"></a>RF72 | O aplicativo notifica aos usuários atualizações em conteúdos relacionados a patologias que eles venham a ter | [GF05](tecnicas/grupo-de-foco.md#requisitos-elicitados) | Não |
| <a id="RF73"></a>RF73 | O aplicativo pode destacar conteúdos pertinentes a um estado para usuários desse estado | [GF06](tecnicas/grupo-de-foco.md#requisitos-elicitados) | Não |
| <a id="RF74"></a>RF74 | O aplicativo deve permitir que o paciente exporte/baixe as receitas médicas | [GF07](tecnicas/grupo-de-foco.md#requisitos-elicitados) | Não |
| <a id="RF75"></a>RF75 | O aplicativo deve oferece agendamento de consultas e exames| [GF02](tecnicas/grupo-de-foco.md#requisitos-elicitados) | Não |
| <a id="RNF1"></a>RNF1 | O sistema deve garantir que o login por meio da conta Gov.br seja realizado com autenticação segura (OAuth 2.0) | [OBS45](tecnicas/observacao.md#requisitos-elicitados), [AD22](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RNF2"></a>RNF2 | O aplicativo deve exibir informações de ajuda de maneira acessível e compreensível para todos os usuários, incluindo pessoas com deficiência visual ou auditiva | [OBS46](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF3"></a>RNF3 | O histórico de vacinação deve ser carregado em menos de 3 segundos em dispositivos com conexão 4G | [OBS47](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF4"></a>RNF4 | O aplicativo deve oferecer suporte a pelo menos três idiomas (português, inglês e espanhol) para os certificados de vacinação | [OBS48](tecnicas/observacao.md#requisitos-elicitados), [AD29](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RNF5"></a>RNF5 | O certificado de vacinação deve ser exportado em formato PDF de alta qualidade, com tamanho máximo de 2 MB | [OBS49](tecnicas/observacao.md#requisitos-elicitados), [AD32](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RNF6"></a>RNF6 | O histórico de vacinas deve ser armazenado em servidores seguros, em conformidade com a LGPD | [OBS50](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF7"></a>RNF7 | O acesso aos detalhes de cada vacina deve ser protegido por criptografia ponta a ponta | [OBS51](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF8"></a>RNF8 | As informações de ajuda relacionadas a exames devem ser exibidas em uma interface amigável, seguindo padrões de usabilidade | [OBS52](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF9"></a>RNF9 | Os resultados de exames laboratoriais devem ser apresentados em formato padronizado e visualmente acessível | [OBS53](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF10"></a>RNF10 | Os dados sobre exames laboratoriais devem ser carregados de maneira otimizada, mesmo em conexões lentas | [OBS54](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF11"></a>RNF11 | Os documentos de resultados de exames laboratoriais devem ser exportados em formatos amplamente compatíveis, como PDF ou JPEG | [OBS55](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF12"></a>RNF12 | O aplicativo deve exibir informações sobre medicamentos em uma interface responsiva e acessível | [OBS56](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF13"></a>RNF13 | O histórico de medicamentos deve ser armazenado em servidores redundantes para garantir alta disponibilidade | [OBS57](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF14"></a>RNF14 | A busca por medicamentos deve apresentar resultados relevantes em menos de 2 segundos | [OBS58](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF15"></a>RNF15 | A busca de medicamentos por nome e dosagem deve ser sensível a erros de digitação | [OBS59](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF16"></a>RNF16 | A autorização para retirada de medicamentos deve ser confirmada com autenticação segura do usuário | [OBS60](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF17"></a>RNF17 | Os medicamentos recebidos pelo Programa Farmácia Popular devem ser exibidos em ordem cronológica | [OBS61](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF18"></a>RNF18 | A seção de ajuda do Programa Dignidade Menstrual deve seguir diretrizes de acessibilidade (WCAG 2.1) | [OBS62](tecnicas/observacao.md#requisitos-elicitados) | Não |
| <a id="RNF19"></a>RNF19 | As autorizações para participação no Programa Dignidade Menstrual devem ser processadas em menos de 5 segundos | [OBS63](tecnicas/observacao.md#requisitos-elicitados) | Não |
| <a id="RNF20"></a>RNF20 | O documento referente à autorização do Programa Dignidade Menstrual deve ser exportado em formato PDF com validação digital | [OBS64](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF21"></a>RNF21 | A localização do dispositivo do usuário deve ser acessada apenas com consentimento explícito e armazenada temporariamente | [OBS65](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF22"></a>RNF22 | O aplicativo deve usar APIs de geolocalização eficientes e de baixo consumo de bateria | [OBS66](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF23"></a>RNF23 | As opções de estabelecimentos de saúde devem ser carregadas em menos de 2 segundos | [OBS67](tecnicas/observacao.md#requisitos-elicitados) | Não |
| <a id="RNF24"></a>RNF24 | A lista de estabelecimentos de saúde recentes deve ser atualizada automaticamente sem comprometer o desempenho | [OBS68](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF25"></a>RNF25 | O agendamento de consultas deve ser sincronizado em tempo real com os sistemas do SUS | [OBS69](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF26"></a>RNF26 | As informações sobre consultas médicas ou exames devem ser exibidas com visualização amigável e intuitiva | [OBS70](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF27"></a>RNF27 | O registro de atendimentos ou internações deve ser armazenado de forma segura em servidores certificados | [OBS71](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF28"></a>RNF28 | Os contatos de profissionais de saúde devem ser exibidos em uma lista organizada, de fácil navegação | [OBS72](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF29"></a>RNF29 | As informações de emergência devem ser acessíveis rapidamente, com opção de busca por nome ou especialidade | [OBS73](tecnicas/observacao.md#requisitos-elicitados) | Não |
| <a id="RNF30"></a>RNF30 | Os registros de saúde do usuário devem ser apresentados em gráficos interativos e de fácil interpretação | [OBS74](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF31"></a>RNF31 | As informações sobre Pressão, Glicose e IMC devem ser armazenadas de forma criptografada para garantir a privacidade | [OBS75](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF32"></a>RNF32 | O aplicativo deve garantir alta disponibilidade, com no mínimo 99,5% de uptime | [OBS76](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF33"></a>RNF33 | Os dados relacionados a alergias devem ser carregados rapidamente e protegidos contra acesso não autorizado | [OBS77](tecnicas/observacao.md#requisitos-elicitados) | Sim |
| <a id="RNF34"></a>RNF34 | Os dados pessoais dos pacientes devem ser protegidos por criptografia AES-256. | [AD14](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RNF35"></a>RNF35 | O sistema deverá ser compatível com dispositivos Android e iOS. | [AD15](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RNF36"></a>RNF36 | O armazenamento e processamento dos dados pessoais deverão estar em conformidade com a LGPD. | [AD16](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RNF37"></a>RNF37 | O termo de consentimento deverá ser exibido em até 5 segundos após a solicitação, em dispositivos com conexão 4G. | [AD19](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RNF38"></a>RNF38 | O design do termo de consentimento deverá ser responsivo, adaptando-se a diferentes tamanhos de tela. | [AD20](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RNF39"></a>RNF39 | As informações sobre os dados coletados deverão ser apresentadas em linguagem acessível, seguindo o padrão de leitura de nível intermediário. | [AD21](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RNF40"></a>RNF40 | O sistema deverá usar conexões criptografadas (TLS 1.2 ou superior) para comunicação com os servidores do CADSUS. | [AD23](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RNF41"></a>RNF41 | O sistema deverá atualizar as informações presentes no cartão de vacinação em até 10 dias após o registro dos dados no sistema do Ministério da Saúde. | [AD28](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RNF42"></a>RNF42 | A notificação de consultas agendadas deverá ser feita com pelo menos 12 horas de antecedência. | [AD31](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| <a id="RNF43"></a>RNF43 | A aplicação pode receber informações do usuário através de biosensores | [EN01](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| <a id="RNF44"></a>RNF44 | O fluxo para solicitar medicamentos deve ser concluído em até 5 cliques/telas | [EN14](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| <a id="RNF45"></a>RNF45 | A aplicação deve processar a solicitação de medicamentos e fornecer uma resposta em até 5 segundos | [EN15](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| <a id="RNF46"></a>RNF46 | O resultado da consulta de pedidos de medicamento deve ser exibido em ordem cronológica | [EN16](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| <a id="RNF47"></a>RNF47 | A receita médica deve ser exportada em formato PDF de alta qualidade, com tamanho máximo de 2 MB | [GF08](tecnicas/grupo-de-foco.md#requisitos-elicitados) | Não |
| <a id="RNF48"></a>RNF48 | O resultado da consulta de receitas médicas deve ser exibido em ordem cronológica | [GF09](tecnicas/grupo-de-foco.md#requisitos-elicitados) | Não |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a> e <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>



## 📚 Bibliografia

> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.



## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação inicial da estrutura do documento referente aos requisitos elicitados. | [Artur Ricardo](https://github.com/algorithmorphic) | 23/11/2024 | [Pedro Lopes](https://github.com/pLopess) | 24/11/2024 |
| `1.1`  | Adição de parte dos requisitos elicitados. | [Artur Ricardo](https://github.com/algorithmorphic) | 23/11/2024 | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 01/12/2024 |
| `1.2`  | Adição dos requisitos da Análise de Documentos | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 01/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 07/12/2024 |
| `1.3`  | Adição dos requisitos da Entrevista | [João Pedro](https://github.com/JoosPerro) | 05/12/2024 | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 07/12/2024 |
| `1.4`  | Adição dos requisitos do Grupo de Foco | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 07/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 07/12/2024 |
| `1.5`  | Inserção das âncoras nos tipos dos requisitos elicitados. | [Artur Ricardo](https://github.com/algorithmorphic) | 07/12/2024 | - | - |
| `1.6`  | Correção da descrição referente ao requisito de tipo RF5 elicitado e inserção de novo requisito (de tipo RF75) elicitado. | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 | - | - |
| `1.7`  | Correção de conflito entre requisitos. | [Artur Ricardo](https://github.com/algorithmorphic) | 19/01/2025 | - | - |
| `1.8`  | Atualização da descrição dos requisitos RF60, RF62, RF67 e RF68. | [Artur Ricardo](https://github.com/algorithmorphic) | 03/02/2025 | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 09/02/2025  |
