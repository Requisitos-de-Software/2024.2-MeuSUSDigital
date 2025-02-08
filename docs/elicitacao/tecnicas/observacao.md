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
| <a id="OBS1"></a>OBS1  | O sistema deve permitir que o paciente realize login por meio de uma conta Gov.br | Sim |
| <a id="OBS2"></a>OBS2  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Vacinas | Sim |
| <a id="OBS3"></a>OBS3  | O aplicativo deve disponibilizar ao usuário o acesso à sua Carteira Nacional de Vacinação Digital | Sim |
| <a id="OBS4"></a>OBS4  | O aplicativo deve permitir que o usuário selecione o idioma do certificado referente à sua Carteira Nacional de Vacinação Digital | Sim |
| <a id="OBS5"></a>OBS5  | O aplicativo deve permitir que o usuário exporte/baixe o certificado referente à sua Carteira Nacional de Vacinação Digital | Sim |
| <a id="OBS6"></a>OBS6  | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de vacinas | Sim |
| <a id="OBS7"></a>OBS7  | O aplicativo deve disponibilizar ao usuário o acesso aos detalhes de cada vacina | Sim |
| <a id="OBS8"></a>OBS8  | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Exames | Sim |
| <a id="OBS9"></a>OBS9  | O aplicativo deve permitir a visualização dos exames laboratoriais realizados | Sim |
| <a id="OBS10"></a>OBS10 | O aplicativo deve permitir a visualização dos resultados e demais informações a respeito dos exames laboratoriais realizados | Sim |
| <a id="OBS11"></a>OBS11 | O aplicativo deve permitir a exportação/download do documento contendo o resultado e demais informações a respeito de cada exame laboratorial realizado | Sim |
| <a id="OBS12"></a>OBS12 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Medicamentos | Sim |
| <a id="OBS13"></a>OBS13 | O aplicativo deve disponibilizar ao usuário o acesso ao seu histórico de medicamentos recebidos | Sim |
| <a id="OBS14"></a>OBS14 | O aplicativo deve permitir que o usuário adicione um medicamento recebido por meio de programas de dispensação do Governo Federal através de um mecanismo de busca | Sim |
| <a id="OBS15"></a>OBS15 | O aplicativo deve permitir que o usuário possa realizar a busca por um medicamento através do nome e dosagem do mesmo | Sim |
| <a id="OBS16"></a>OBS16 | O aplicativo deve fornecer ao usuário, em adesão ao Programa Farmácia Popular, a opção de autorizar ou não a retirada de medicamentos em seu CPF | Sim |
| <a id="OBS17"></a>OBS17 | O aplicativo deve permitir que o usuário possa verificar os medicamentos recebidos pelo Programa Farmácia Popular | Sim |
| <a id="OBS18"></a>OBS18 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Dignidade Menstrual | Sim |
| <a id="OBS19"></a>OBS19 | Caso o usuário atenda aos critérios do Programa, o aplicativo deve permitir que o usuário emita uma autorização para participar do Programa Dignidade Menstrual | Sim |
| <a id="OBS20"></a>OBS20 | O aplicativo deve permitir que o usuário exporte/baixe o documento referente à autorização de participação no do Programa Dignidade Menstrual | Sim |
| <a id="OBS21"></a>OBS21 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Rede de Saúde | Sim |
| <a id="OBS22"></a>OBS22 | O aplicativo deve pedir permissão de acesso à localização do dispositivo do usuário | Sim |
| <a id="OBS23"></a>OBS23 | O aplicativo deve armazenar a localização do dispositivo do usuário | Sim |
| <a id="OBS24"></a>OBS24 | O aplicativo deve oferecer opções de estabelecimentos de saúde a fim de que o usuário possa identificar àqueles próximos à sua localização, de acordo com o tipo de serviço desejado | Sim |
| <a id="OBS25"></a>OBS25 | O aplicativo deve permitir que o usuário possa identificar os estabelecimentos de saúde recentes vinculados a ele | Sim |
| <a id="OBS26"></a>OBS26 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Agendamentos | Sim |
| <a id="OBS27"></a>OBS27 | O aplicativo deve exibir as consultas médicas ou exames de saúde do usuário | Sim |
| <a id="OBS28"></a>OBS28 | O aplicativo deve possibilitar o agendamento de consultas médicas ou exames de saúde | Sim |
| <a id="OBS29"></a>OBS29 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Atendimento e Internação | Sim |
| <a id="OBS30"></a>OBS30 | O aplicativo deve exibir os registros de atendimentos ou internações do usuário | Sim |
| ID    | Descrição | Implementado |
| ----- | --------- | ------------ |
| <a id="OBS31"></a>OBS31 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Contatos | Sim |
| <a id="OBS32"></a>OBS32 | O aplicativo deve exibir contatos de profissionais de saúde | Sim |
| <a id="OBS33"></a>OBS33 | O aplicativo deve permitir que o usuário adicione o contato de um profissional de saúde em casos de emergência | Sim |
| <a id="OBS34"></a>OBS34 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Diário de Saúde | Sim |
| <a id="OBS35"></a>OBS35 | O aplicativo deve exibir todos os registros de saúde do usuário | Sim |
| <a id="OBS36"></a>OBS36 | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Pressão | Sim |
| <a id="OBS37"></a>OBS37 | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Pressão | Sim |
| <a id="OBS38"></a>OBS38 | O aplicativo deve exibir os registros de saúde do usuário referentes à sua Glicose | Sim |
| <a id="OBS39"></a>OBS39 | O aplicativo deve permitir que o usuário adicione um registro de saúde referente à sua Glicose | Sim |
| <a id="OBS40"></a>OBS40 | O aplicativo deve exibir os registros de saúde do usuário referentes ao seu IMC | Sim |
| <a id="OBS41"></a>OBS41 | O aplicativo deve permitir que o usuário adicione um registro de saúde referente ao seu IMC | Sim |
| <a id="OBS42"></a>OBS42 | O aplicativo deve permitir que o usuário obtenha ajuda informativa a respeito da seção de Alergias | Sim |
| <a id="OBS43"></a>OBS43 | O aplicativo deve exibir as alergias que usuário possui | Sim |
| <a id="OBS44"></a>OBS44 | O aplicativo deve permitir que o usuário adicione uma alergia | Sim |
| <a id="OBS45"></a>OBS45 | O aplicativo deve permitir que o usuário exporte ou realize o download do documento referente ao Certificado de vacinação nacional de Covid-19 | Sim |

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
| <a id="OBS45"></a>OBS45 | O sistema deve garantir que o login por meio da conta Gov.br seja realizado com autenticação segura (OAuth 2.0) | Sim |
| <a id="OBS46"></a>OBS46 | O aplicativo deve exibir informações de ajuda de maneira acessível e compreensível para todos os usuários, incluindo pessoas com deficiência visual ou auditiva | Sim |
| <a id="OBS47"></a>OBS47 | O histórico de vacinação deve ser carregado em menos de 3 segundos em dispositivos com conexão 4G | Sim |
| <a id="OBS48"></a>OBS48 | O aplicativo deve oferecer suporte a pelo menos três idiomas (português, inglês e espanhol) para os certificados de vacinação | Sim |
| <a id="OBS49"></a>OBS49 | O certificado de vacinação deve ser exportado em formato PDF de alta qualidade, com tamanho máximo de 2 MB | Sim |
| <a id="OBS50"></a>OBS50 | O histórico de vacinas deve ser armazenado em servidores seguros, em conformidade com a LGPD | Sim |
| <a id="OBS51"></a>OBS51 | O acesso aos detalhes de cada vacina deve ser protegido por criptografia ponta a ponta | Sim |
| <a id="OBS52"></a>OBS52 | As informações de ajuda relacionadas a exames devem ser exibidas em uma interface amigável, seguindo padrões de usabilidade | Sim |
| <a id="OBS53"></a>OBS53 | Os resultados de exames laboratoriais devem ser apresentados em formato padronizado e visualmente acessível | Sim |
| <a id="OBS54"></a>OBS54 | Os dados sobre exames laboratoriais devem ser carregados de maneira otimizada, mesmo em conexões lentas | Sim |
| <a id="OBS55"></a>OBS55 | Os documentos de resultados de exames laboratoriais devem ser exportados em formatos amplamente compatíveis, como PDF ou JPEG | Sim |
| <a id="OBS56"></a>OBS56 | O aplicativo deve exibir informações sobre medicamentos em uma interface responsiva e acessível | Sim |
| <a id="OBS57"></a>OBS57 | O histórico de medicamentos deve ser armazenado em servidores redundantes para garantir alta disponibilidade | Sim |
| <a id="OBS58"></a>OBS58 | A busca por medicamentos deve apresentar resultados relevantes em menos de 2 segundos | Sim |
| <a id="OBS59"></a>OBS59 | A busca de medicamentos por nome e dosagem deve ser sensível a erros de digitação | Não |
| <a id="OBS60"></a>OBS60 | A autorização para retirada de medicamentos deve ser confirmada com autenticação segura do usuário | Sim |
| <a id="OBS61"></a>OBS61 | Os medicamentos recebidos pelo Programa Farmácia Popular devem ser exibidos em ordem cronológica | Sim |
| <a id="OBS62"></a>OBS62 | A seção de ajuda do Programa Dignidade Menstrual deve seguir diretrizes de acessibilidade (WCAG 2.1) | Não |
| <a id="OBS63"></a>OBS63 | As autorizações para participação no Programa Dignidade Menstrual devem ser processadas em menos de 5 segundos | Não |
| <a id="OBS64"></a>OBS64 | O documento referente à autorização do Programa Dignidade Menstrual deve ser exportado em formato PDF com validação digital | Sim |
| <a id="OBS65"></a>OBS65 | A localização do dispositivo do usuário deve ser acessada apenas com consentimento explícito e armazenada temporariamente | Sim |
| <a id="OBS66"></a>OBS66 | O aplicativo deve usar APIs de geolocalização eficientes e de baixo consumo de bateria | Sim |
| <a id="OBS67"></a>OBS67 | As opções de estabelecimentos de saúde devem ser carregadas em menos de 2 segundos | Não |
| <a id="OBS68"></a>OBS68 | A lista de estabelecimentos de saúde recentes deve ser atualizada automaticamente sem comprometer o desempenho | Sim |
| <a id="OBS69"></a>OBS69 | O agendamento de consultas deve ser sincronizado em tempo real com os sistemas do SUS | Sim |
| <a id="OBS70"></a>OBS70 | As informações sobre consultas médicas ou exames devem ser exibidas com visualização amigável e intuitiva | Sim |
| <a id="OBS71"></a>OBS71 | O registro de atendimentos ou internações deve ser armazenado de forma segura em servidores certificados | Sim |
| <a id="OBS72"></a>OBS72 | Os contatos de profissionais de saúde devem ser exibidos em uma lista organizada, de fácil navegação | Sim |
| <a id="OBS73"></a>OBS73 | As informações de emergência devem ser acessíveis rapidamente, com opção de busca por nome ou especialidade | Não |
| <a id="OBS74"></a>OBS74 | Os registros de saúde do usuário devem ser apresentados em gráficos interativos e de fácil interpretação | Sim |
| <a id="OBS75"></a>OBS75 | As informações sobre Pressão, Glicose e IMC devem ser armazenadas de forma criptografada para garantir a privacidade | Sim |
| <a id="OBS76"></a>OBS76 | O aplicativo deve garantir alta disponibilidade, com no mínimo 99,5% de uptime | Sim |
| <a id="OBS77"></a>OBS77 | Os dados relacionados a alergias devem ser carregados rapidamente e protegidos contra acesso não autorizado | Sim |

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
| `1.2`  | Adição de âncoras para os IDs e de um novo requisito elicitado (OBS45) através da técnica de observação (etnografia). | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 | [Emivalto Júnior](https://github.com/EmivaltoJrr)| 08/02/2025 |
