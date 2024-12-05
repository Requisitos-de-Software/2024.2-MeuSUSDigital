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
| RF1   | O sistema deve permitir que o paciente realize login por meio de uma conta Gov.br | OBS1, [AD09](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF2   | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Vacinas | OBS2 | Sim |
| RF3   | O aplicativo deve disponibilizar ao usuário o acesso à sua Carteira Nacional de Vacinação Digital | OBS3 | Sim |
| RF4   | O aplicativo deve permitir que o usuário selecione o idioma do certificado referente à sua Carteira Nacional de Vacinação Digital | OBS4 | Sim |
| RF5   | O aplicativo deve permitir que o usuário exporte/baixe o certificado referente à sua Carteira Nacional de Vacinação Digital | OBS5, [AD24](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF6   | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de vacinas | OBS6 | Sim |
| RF7   | O aplicativo deve disponibilizar ao usuário o acesso aos detalhes de cada vacina | OBS7 | Sim |
| RF8   | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Exames | OBS8 | Sim |
| RF9   | O aplicativo deve permitir a visualização dos exames laboratoriais realizados | OBS9 | Sim |
| RF10  | O aplicativo deve permitir a visualização dos resultados e demais informações a respeito dos exames laboratoriais realizados | OBS10 | Sim |
| RF11  | O aplicativo deve permitir a exportação/download do documento contendo o resultado e demais informações a respeito de cada exame laboratorial realizado | OBS11 | Sim |
| RF12  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Medicamentos | OBS12 | Sim |
| RF13  | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de medicamentos recebidos | OBS13 | Sim |
| RF14  | O aplicativo deve permitir que o usuário adicione um medicamento recebido por meio de programas de dispensação do Governo Federal através de um mecanismo de busca | OBS14 | Sim |
| RF15  | O aplicativo deve permitir que o usuário possa realizar a busca por um medicamento através do nome e dosagem do mesmo | OBS15 | Sim |
| RF16  | O aplicativo deve fornecer ao usuário, em adesão ao Programa Farmácia Popular, a opção de autorizar ou não a retirada de medicamentos em seu CPF | OBS16 | Sim |
| RF17  | O aplicativo deve permitir que o usuário possa verificar os medicamentos recebidos pelo Programa Farmácia Popular | OBS17 | Sim |
| RF18  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Dignidade Menstrual | OBS18 | Sim |
| RF19  | Caso o usuário atenda aos critérios do Programa, o aplicativo deve permitir que o usuário emita uma autorização para participar do Programa Dignidade Menstrual | OBS19 | Sim |
| RF20  | O aplicativo deve permitir que o usuário exporte/baixe o documento referente à autorização de participação do Programa Dignidade Menstrual | OBS20 | Sim |
| RF21  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Rede de Saúde | OBS21 | Sim |
| RF22  | O aplicativo deve pedir permissão de acesso à localização do dispositivo do usuário | OBS22, [AD05](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF23  | O aplicativo deve armazenar a localização do dispositivo do usuário | OBS23, [AD06](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF24  | O aplicativo deve oferecer opções de estabelecimentos de saúde a fim de que o usuário possa identificar àqueles próximos à sua localização, de acordo com o tipo de serviço desejado | OBS24 | Sim |
| RF25  | O aplicativo deve permitir que o usuário possa identificar os estabelecimentos de saúde recentes vinculados a ele | OBS25 | Sim |
| RF26  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Agendamentos | OBS26 | Sim |
| RF27  | O aplicativo deve exibir as consultas médicas ou exames de saúde do usuário | OBS27 | Sim |
| RF28  | O aplicativo deve possibilitar o agendamento de consultas médicas ou exames de saúde | OBS28, [AD27](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF29  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Atendimento e Internação | OBS29 | Sim |
| RF30  | O aplicativo deve exibir os registros de atendimentos ou internações do usuário | OBS30 | Sim |
| RF31  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Contatos | OBS31 | Sim |
| RF32  | O aplicativo deve exibir contatos de profissionais de saúde | OBS32 | Sim |
| RF33  | O aplicativo deve permitir que o usuário adicione o contato de um profissional de saúde em casos de emergência | OBS33 | Sim |
| RF34  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Diário de Saúde | OBS34 | Sim |
| RF35  | O aplicativo deve exibir todos os registros de saúde do usuário | OBS35 | Sim |
| RF36  | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Pressão | OBS36 | Sim |
| RF37  | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Pressão | OBS37 | Sim |
| RF38  | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Glicose | OBS38 | Sim |
| RF39  | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Glicose | OBS39 | Sim |
| RF40  | O aplicativo deve exibir os registros de saúde do usuário referentes ao seu IMC | OBS40 | Sim |
| RF41  | O aplicativo deve permitir que o usuário adicione um registro de saúde referente ao seu IMC | OBS41 | Sim |
| RF42  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Alergias | OBS42 | Sim |
| RF43  | O aplicativo deve exibir as alergias que usuário possui | OBS43 | Sim |
| RF44  | O aplicativo deve permitir que o usuário adicione uma alergia | OBS44 | Sim |
| RF45  | O sistema deverá apresentar o termo de consentimento. | [AD01](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF46  | O sistema deverá informar quais dados serão coletados. | [AD02](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF47  | O sistema deverá permitir que o paciente escolha entre aceitar ou recusar a coleta de seus dados pessoais. | [AD03](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF48  | O sistema deverá registrar a escolha do paciente em relação à coleta de seus dados pessoais. | [AD04](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF49  | O sistema deverá pedir permissão de acesso à câmera do dispositivo. | [AD07](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF50  | O sistema deverá permitir ao paciente tirar sua foto utilizando a câmera do dispositivo. | [AD08](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF51  | O sistema deverá buscar no CADSUS os dados do paciente (Nome, data de nascimento, sexo, filiação, nacionalidade, e-mail, endereço e telefone) utilizando o CPF associado à conta Gov.br informada no login. | [AD10](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF52  | O sistema deverá buscar na RNDS os dados do paciente (Histórico clínico, dados de vacinação e resultados de exames) utilizando o CPF associado à conta Gov.br informada no login. | [AD11](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF53  | O sistema deverá permitir que o paciente solicite a remoção de seus dados pessoais do aplicativo. | [AD12](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF54  | O sistema deverá apresentar o *status* e posição do usuário na lista de espera para transplante de órgão e tecido. | [AD18](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF55  | O sistema deverá permitir que o paciente baixe o Certificado de Vacinação Nacional de Covid-19 em seu dispositivo. | [AD25](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF56  | O sistema deverá permitir que o paciente preencha informações de autodeclaração com nome social, raça/cor e endereço. | [AD26](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RF57  | O sistema deverá notificar o paciente sobre consultas agendadas, informando o tipo de consulta, a data, o horário e o local da consulta. | [AD30](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RNF1  | O sistema deve garantir que o login por meio da conta Gov.br seja realizado com autenticação segura (OAuth 2.0) | OBS45, [AD22](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RNF2  | O aplicativo deve exibir informações de ajuda de maneira acessível e compreensível para todos os usuários, incluindo pessoas com deficiência visual ou auditiva | OBS46 | Sim |
| RNF3  | O histórico de vacinação deve ser carregado em menos de 3 segundos em dispositivos com conexão 4G | OBS47 | Sim |
| RNF4  | O aplicativo deve oferecer suporte a pelo menos três idiomas (português, inglês e espanhol) para os certificados de vacinação | OBS48, [AD29](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RNF5  | O certificado de vacinação deve ser exportado em formato PDF de alta qualidade, com tamanho máximo de 2 MB | OBS49, [AD32](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RNF6  | O histórico de vacinas deve ser armazenado em servidores seguros, em conformidade com a LGPD | OBS50 | Sim |
| RNF7  | O acesso aos detalhes de cada vacina deve ser protegido por criptografia ponta a ponta | OBS51 | Sim |
| RNF8  | As informações de ajuda relacionadas a exames devem ser exibidas em uma interface amigável, seguindo padrões de usabilidade | OBS52 | Sim |
| RNF9  | Os resultados de exames laboratoriais devem ser apresentados em formato padronizado e visualmente acessível | OBS53 | Sim |
| RNF10 | Os dados sobre exames laboratoriais devem ser carregados de maneira otimizada, mesmo em conexões lentas | OBS54 | Sim |
| RNF11 | Os documentos de resultados de exames laboratoriais devem ser exportados em formatos amplamente compatíveis, como PDF ou JPEG | OBS55 | Sim |
| RNF12 | O aplicativo deve exibir informações sobre medicamentos em uma interface responsiva e acessível | OBS56 | Sim |
| RNF13 | O histórico de medicamentos deve ser armazenado em servidores redundantes para garantir alta disponibilidade | OBS57 | Sim |
| RNF14 | A busca por medicamentos deve apresentar resultados relevantes em menos de 2 segundos | OBS58 | Sim |
| RNF15 | A busca de medicamentos por nome e dosagem deve ser sensível a erros de digitação | OBS59 | Sim |
| RNF16 | A autorização para retirada de medicamentos deve ser confirmada com autenticação segura do usuário | OBS60 | Sim |
| RNF17 | Os medicamentos recebidos pelo Programa Farmácia Popular devem ser exibidos em ordem cronológica | OBS61 | Sim |
| RNF18 | A seção de ajuda do Programa Dignidade Menstrual deve seguir diretrizes de acessibilidade (WCAG 2.1) | OBS62 | Não |
| RNF19 | As autorizações para participação no Programa Dignidade Menstrual devem ser processadas em menos de 5 segundos | OBS63 | Não |
| RNF20 | O documento referente à autorização do Programa Dignidade Menstrual deve ser exportado em formato PDF com validação digital | OBS64 | Sim |
| RNF21 | A localização do dispositivo do usuário deve ser acessada apenas com consentimento explícito e armazenada temporariamente | OBS65 | Sim |
| RNF22 | O aplicativo deve usar APIs de geolocalização eficientes e de baixo consumo de bateria | OBS66 | Sim |
| RNF23 | As opções de estabelecimentos de saúde devem ser carregadas em menos de 2 segundos | OBS67 | Não |
| RNF24 | A lista de estabelecimentos de saúde recentes deve ser atualizada automaticamente sem comprometer o desempenho | OBS68 | Sim |
| RNF25 | O agendamento de consultas deve ser sincronizado em tempo real com os sistemas do SUS | OBS69 | Sim |
| RNF26 | As informações sobre consultas médicas ou exames devem ser exibidas com visualização amigável e intuitiva | OBS70 | Sim |
| RNF27 | O registro de atendimentos ou internações deve ser armazenado de forma segura em servidores certificados | OBS71 | Sim |
| RNF28 | Os contatos de profissionais de saúde devem ser exibidos em uma lista organizada, de fácil navegação | OBS72 | Sim |
| RNF29 | As informações de emergência devem ser acessíveis rapidamente, com opção de busca por nome ou especialidade | OBS73 | Não |
| RNF30 | Os registros de saúde do usuário devem ser apresentados em gráficos interativos e de fácil interpretação | OBS74 | Sim |
| RNF31 | As informações sobre Pressão, Glicose e IMC devem ser armazenadas de forma criptografada para garantir a privacidade | OBS75 | Sim |
| RNF32 | O aplicativo deve garantir alta disponibilidade, com no mínimo 99,5% de uptime | OBS76 | Sim |
| RNF33 | Os dados relacionados a alergias devem ser carregados rapidamente e protegidos contra acesso não autorizado | OBS77 | Sim |
| RNF34 | Os dados pessoais dos pacientes devem ser protegidos por criptografia AES-256. | [AD14](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RNF35 | O sistema deverá ser compatível com dispositivos Android e iOS. | [AD15](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RNF36 | O armazenamento e processamento dos dados pessoais deverão estar em conformidade com a LGPD. | [AD16](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RNF37 | O termo de consentimento deverá ser exibido em até 5 segundos após a solicitação, em dispositivos com conexão 4G. | [AD19](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RNF38 | O design do termo de consentimento deverá ser responsivo, adaptando-se a diferentes tamanhos de tela. | [AD20](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RNF39 | As informações sobre os dados coletados deverão ser apresentadas em linguagem acessível, seguindo o padrão de leitura de nível intermediário. | [AD21](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RNF40 | O sistema deverá usar conexões criptografadas (TLS 1.2 ou superior) para comunicação com os servidores do CADSUS. | [AD23](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RNF41 | O sistema deverá atualizar as informações presentes no cartão de vacinação em até 10 dias após o registro dos dados no sistema do Ministério da Saúde. | [AD28](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RNF42 | A notificação de consultas agendadas deverá ser feita com pelo menos 12 horas de antecedência. | [AD31](tecnicas/analise-de-documentos.md#requisitos-elicitados) | Sim |
| RNF43 | A aplicação pode receber informações do usuário através de biosensores | [EN 01](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| RF44  | A aplicação permite agendar consultas | [EN 02](tecnicas/entrevista.md#requisitos-elicitados) |  Não |
| RF45  | A aplicação permite agendar exames | [EN 03](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| RF46  | a aplicação permite ao servidor solicitar licença saúde | [EN 04](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| RF47  | A aplicação permite acompanhar o andamento de solicitações (licensa, medicamentos) | [EN 05](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| RF48  | A aplicação permite acompanhar a vacinação | [EN 06](tecnicas/entrevista.md#requisitos-elicitados) | Sim |
| RF49  | A aplicação permite consultar pedidos de medicamento | [EN 07](tecnicas/entrevista.md#requisitos-elicitados) | Não |
| RF50  | A aplicação permite consultar recebimentos de medicamento | [EN 08](tecnicas/entrevista.md#requisitos-elicitados) | Sim |
| RF51  | A aplicação permite consultar os agendamentos de exames | [EN 09](tecnicas/entrevista.md#requisitos-elicitados) | Sim |
| RF52  | A aplicação permite consultar os resultados de exames | [EN 10](tecnicas/entrevista.md#requisitos-elicitados) | Sim |
| RF53  | A aplicação notifica o cancelamento de agentamentos | [EN 11](tecnicas/entrevista.md#requisitos-elicitados) | Não |



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
| `1.2`  | Adição dos requisitos da Análise de Documentos | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 01/12/2024 |  |  |
| `1.3`  | Adição dos requisitos da Entrevista | [João Pedro](https://github.com/JoosPerro) | 05/12/2024 |  |  |
