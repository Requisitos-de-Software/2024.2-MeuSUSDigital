# Observação



## Introdução

A técnica de observação (etnografia) é uma ferramenta essencial para compreender as necessidades reais dos usuários e identificar os requisitos de um software de maneira mais fidedigna. Originária da antropologia, essa abordagem é amplamente utilizada na análise de interações entre pessoas, sistemas e seus ambientes. Em projetos de software, a observação permite explorar aspectos implícitos que entrevistas ou outras técnicas de elicitação de requisitos nem sempre capturam. No entanto, é fundamental considerar a preparação cuidadosa para garantir que os objetivos sejam claros e que a execução não interfira de forma significativa na observação. Esta técnica foi empregada no presente projeto, com o objetivo de elicitar requisitos funcionais (encontrados na **Tabela 2**) e não funcionais (encontrados na **Tabela 3**) do aplicativo Meu SUS Digital, respeitando o que foi previamente estabelecido em cronograma.

Conforme pode ser observado na **Tabela 1**, a observação foi composta por [Artur Ricardo](https://github.com/algorithmorphic), um dos integrantes da equipe do Grupo 04, que fará o papel de observador, e por Stefany Paraíso, uma usuária do aplicativo e não pertencente à equipe, como pessoa observada.



## Metodologia

Para esta etapa e atividade do projeto, foi adotada a técnica de observação participativa com postura ativa (ou visível), onde o analista atuou como observador, dialogando com a participante (pessoa observada) sempre que necessário. A análise foi conduzida conforme o que foi definido em [cronograma](../planejamento/cronograma-tecnicas.md#cronograma), de acordo com as seguintes etapas:

### Planejamento

- **Definição do objetivo principal**: identificar requisitos funcionais e não funcionais para aprimorar o uso do aplicativo Meu SUS Digital.

- **Escolha do(a) participante**: será selecionada uma pessoa externa à equipe do Grupo 04 com experiência no uso do Meu SUS Digital, garantindo maior fidelidade às interações reais.

- **Agendamento da sessão**: a atividade será realizada no dia 24/11/2024, às 11:00 horas da manhã, com duração aproximada de 20 minutos, por meio da ferramenta Microsoft Teams.

### Execução

O analista se apresentará ao participante, explicando os objetivos da sessão e garantindo que sua atuação não será julgada ou criticada. Será enfatizado que o propósito é compreender melhor os processos envolvidos na utilização do aplicativo Meu SUS Digital a fim de seja realizada uma análise de seus requisitos por parte da equipe do Grupo 04.
Durante a sessão, o analista solicitará que o(a) participante realize uma série de tarefas típicas no app, incentivando-o(a) a "pensar alto" enquanto executa as atividades, para compartilhar suas intenções, desafios e percepções.
Sempre que surgir uma dúvida ou ponto de interesse, o analista interromperá o processo momentaneamente para fazer perguntas exploratórias sobre as razões das escolhas ou dificuldades observadas.

### Documentação

Todas as ações e interações do participante com o aplicativo serão anotadas detalhadamente pelo analista, bem como as respostas às questões levantadas durante a observação.
Com a técnica de observação (etnografia), serão levantados requisitos funcionais e não funcionais a respeito do Meu SUS Digital.

### Revisão

Após a sessão, o documento será compartilhado com o participante para revisão e validação das informações coletadas. Eventuais esclarecimentos serão incluídos no material final.

## Participantes

<div align="center">
    <p><strong>Tabela 1 – Participantes da observação</strong></p>
</div>

<center>

| Nome                                                | Função           |
| --------------------------------------------------- | ---------------- |
| [Artur Ricardo](https://github.com/algorithmorphic) | Observador       |
| Stefany Paraíso                                     | Pessoa observada |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>




## Gravação

Através deste [link](https://www.youtube.com/watch?v=lyMJnsWt9oI), você será redirecionado(a) para o YouTube, onde o vídeo da gravação da observação foi disponibilizado.



## Requisitos Elicitados

### Funcionais

<div align="center">
    <p><strong>Tabela 2 – Requisitos funcionais elicitados</strong></p>
</div>

<center>

| ID    | Descrição | Implementado |
| ----- | --------- | ------------ |
| OBS1  | O sistema deve permitir que o paciente realize login por meio de uma conta Gov.br | Sim |
| OBS2  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Vacinas | Sim |
| OBS3  | O aplicativo deve disponibilizar ao usuário o acesso à sua Carteira Nacional de Vacinação Digital | Sim |
| OBS4  | O aplicativo deve permitir que o usuário selecione o idioma do certificado referente à sua Carteira Nacional de Vacinação Digital | Sim |
| OBS5  | O aplicativo deve permitir que o usuário exporte/baixe o certificado referente à sua Carteira Nacional de Vacinação Digital | Sim |
| OBS6  | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de vacinas | Sim |
| OBS7  | O aplicativo deve disponibilizar ao usuário o acesso aos detalhes de cada vacina | Sim |
| OBS8  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Exames | Sim |
| OBS9  | O aplicativo deve permitir a visualização dos exames laboratoriais realizados | Sim |
| OBS10 | O aplicativo deve permitir a visualização dos resultados e demais informações a respeito dos exames laboratoriais realizados | Sim |
| OBS11 | O aplicativo deve permitir a exportação/download do documento contendo o resultado e demais informações a respeito de cada exame laboratorial realizado | Sim |
| OBS12 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Medicamentos | Sim |
| OBS13 | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de medicamentos recebidos | Sim |
| OBS14 | O aplicativo deve permitir que o usuário adicione um medicamento recebido por meio de programas de dispensação do Governo Federal através de um mecanismo de busca | Sim |
| OBS15 | O aplicativo deve permitir que o usuário possa realizar a busca por um medicamento através do nome e dosagem do mesmo | Sim |
| OBS16 | O aplicativo deve fornecer ao usuário, em adesão ao Programa Farmácia Popular, a opção de autorizar ou não a retirada de medicamentos em seu CPF | Sim |
| OBS17 | O aplicativo deve permitir que o usuário possa verificar os medicamentos recebidos pelo Programa Farmácia Popular | Sim |
| OBS18 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Dignidade Menstrual | Sim |
| OBS19 | Caso o usuário atenda aos critérios do Programa, o aplicativo deve permitir que o usuário emita uma autorização para participar do Programa Dignidade Menstrual | Sim |
| OBS20 | O aplicativo deve permitir que o usuário exporte/baixe o documento referente à autorização de participação no do Programa Dignidade Menstrual | Sim |
| OBS21 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Rede de Saúde | Sim |
| OBS22 | O aplicativo deve pedir permissão de acesso à localização do dispositivo do usuário | Sim |
| OBS23 | O aplicativo deve armazenar a localização do dispositivo do usuário | Sim |
| OBS24 | O aplicativo deve oferecer opções de estabelecimentos de saúde a fim de que o usuário possa identificar àqueles próximos à sua localização, de acordo com o tipo de serviço desejado | Sim |
| OBS25 | O aplicativo deve permitir que o usuário possa identificar os estabelecimentos de saúde recentes vinculados a ele | Sim |
| OBS26 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Agendamentos | Sim |
| OBS27 | O aplicativo deve exibir as consultas médicas ou exames de saúde do usuário | Sim |
| OBS28 | O aplicativo deve possibilitar o agendamento de consultas médicas ou exames de saúde | Sim |
| OBS29 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Atendimento e Internação | Sim |
| OBS30 | O aplicativo deve exibir os registros de atendimentos ou internações do usuário | Sim |
| OBS31 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Contatos | Sim |
| OBS32 | O aplicativo deve exibir contatos de profissionais de saúde | Sim |
| OBS33 | O aplicativo deve permitir que o usuário adicione o contato de um profissional de saúde em casos de emergência | Sim |
| OBS34 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Diário de Saúde | Sim |
| OBS35 | O aplicativo deve exibir todos os registros de saúde do usuário | Sim |
| OBS36 | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Pressão | Sim |
| OBS37 | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Pressão | Sim |
| OBS38 | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Glicose | Sim |
| OBS39 | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Glicose | Sim |
| OBS40 | O aplicativo deve exibir os registros de saúde do usuário referentes ao seu IMC | Sim |
| OBS41 | O aplicativo deve permitir que o usuário adicione um registro de saúde referente ao seu IMC | Sim |
| OBS42 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Alergias | Sim |
| OBS43 | O aplicativo deve exibir as alergias que usuário possui | Sim |
| OBS44 | O aplicativo deve permitir que o usuário adicione uma alergia | Sim |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>

### Não Funcionais

<div align="center">
    <p><strong>Tabela 3 – Requisitos não funcionais elicitados</strong></p>
</div>

<center>

| ID    | Descrição | Implementado | 
| ----- | --------- | ------------ |
| OBS45 | O sistema deve garantir que o login por meio da conta Gov.br seja realizado com autenticação segura (OAuth 2.0) | Sim |
| OBS46 | O aplicativo deve exibir informações de ajuda de maneira acessível e compreensível para todos os usuários, incluindo pessoas com deficiência visual ou auditiva | Sim |
| OBS47 | O histórico de vacinação deve ser carregado em menos de 3 segundos em dispositivos com conexão 4G | Sim |
| OBS48 | O aplicativo deve oferecer suporte a pelo menos três idiomas (português, inglês e espanhol) para os certificados de vacinação | Sim |
| OBS49 | O certificado de vacinação deve ser exportado em formato PDF de alta qualidade, com tamanho máximo de 2 MB | Sim |
| OBS50 | O histórico de vacinas deve ser armazenado em servidores seguros, em conformidade com a LGPD | Sim |
| OBS51 | O acesso aos detalhes de cada vacina deve ser protegido por criptografia ponta a ponta | Sim |
| OBS52 | As informações de ajuda relacionadas a exames devem ser exibidas em uma interface amigável, seguindo padrões de usabilidade | Sim |
| OBS53 | Os resultados de exames laboratoriais devem ser apresentados em formato padronizado e visualmente acessível | Sim |
| OBS54 | Os dados sobre exames laboratoriais devem ser carregados de maneira otimizada, mesmo em conexões lentas | Sim |
| OBS55 | Os documentos de resultados de exames laboratoriais devem ser exportados em formatos amplamente compatíveis, como PDF ou JPEG | Sim |
| OBS56 | O aplicativo deve exibir informações sobre medicamentos em uma interface responsiva e acessível | Sim |
| OBS57 | O histórico de medicamentos deve ser armazenado em servidores redundantes para garantir alta disponibilidade | Sim |
| OBS58 | A busca por medicamentos deve apresentar resultados relevantes em menos de 2 segundos | Sim |
| OBS59 | A busca de medicamentos por nome e dosagem deve ser sensível a erros de digitação | Não |
| OBS60 | A autorização para retirada de medicamentos deve ser confirmada com autenticação segura do usuário | Sim |
| OBS61 | Os medicamentos recebidos pelo Programa Farmácia Popular devem ser exibidos em ordem cronológica | Sim |
| OBS62 | A seção de ajuda do Programa Dignidade Menstrual deve seguir diretrizes de acessibilidade (WCAG 2.1) | Não |
| OBS63 | As autorizações para participação no Programa Dignidade Menstrual devem ser processadas em menos de 5 segundos | Não |
| OBS64 | O documento referente à autorização do Programa Dignidade Menstrual deve ser exportado em formato PDF com validação digital | Sim |
| OBS65 | A localização do dispositivo do usuário deve ser acessada apenas com consentimento explícito e armazenada temporariamente | Sim |
| OBS66 | O aplicativo deve usar APIs de geolocalização eficientes e de baixo consumo de bateria | Sim |
| OBS67 | As opções de estabelecimentos de saúde devem ser carregadas em menos de 2 segundos | Não |
| OBS68 | A lista de estabelecimentos de saúde recentes deve ser atualizada automaticamente sem comprometer o desempenho | Sim |
| OBS69 | O agendamento de consultas deve ser sincronizado em tempo real com os sistemas do SUS | Sim |
| OBS70 | As informações sobre consultas médicas ou exames devem ser exibidas com visualização amigável e intuitiva | Sim |
| OBS71 | O registro de atendimentos ou internações deve ser armazenado de forma segura em servidores certificados | Sim |
| OBS72 | Os contatos de profissionais de saúde devem ser exibidos em uma lista organizada, de fácil navegação | Sim |
| OBS73 | As informações de emergência devem ser acessíveis rapidamente, com opção de busca por nome ou especialidade | Não |
| OBS74 | Os registros de saúde do usuário devem ser apresentados em gráficos interativos e de fácil interpretação | Sim |
| OBS75 | As informações sobre Pressão, Glicose e IMC devem ser armazenadas de forma criptografada para garantir a privacidade | Sim |
| OBS76 | O aplicativo deve garantir alta disponibilidade, com no mínimo 99,5% de uptime | Sim |
| OBS77 | Os dados relacionados a alergias devem ser carregados rapidamente e protegidos contra acesso não autorizado | Sim |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>



## 📚 Bibliografia

> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.



## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação inicial da estrutura do documento referente à técnica de observação (etnografia). | [Artur Ricardo](https://github.com/algorithmorphic) | 20/11/2024 | [Pedro Lopes](https://github.com/pLopess) | 24/11/2024 |
| `1.1`  | Adição dos requisitos (funcionais e não funcionais) elicitados através da técnica de observação (etnografia). | [Artur Ricardo](https://github.com/algorithmorphic) | 24/11/2024 | [Pedro Lopes](https://github.com/pLopess) | 24/11/2024 |
