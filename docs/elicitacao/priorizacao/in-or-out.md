# Priorização de Requisitos - In or Out

## Introdução
A priorização de requisitos é uma etapa essencial na engenharia de requisitos, permitindo definir quais funcionalidades devem ser implementadas de acordo com o valor agregado ao usuário e às restrições do projeto. Neste documento, utilizamos a técnica **In or Out**, onde a cliente irá classificar cada requisito como essencial (**In**) ou descartável para o escopo inicial (**Out**). Essa priorização servirá como guia para as próximas etapas do desenvolvimento do **Meu SUS Digital**.

## Metodologia
A técnica **In or Out** permite uma priorização objetiva dos requisitos com base na percepção do usuário/cliente. Os requisitos elicitados foram organizados na **Tabela 1**, onde o usuário/cliente indicará "In" para aqueles que devem ser implementados e "Out" para os que podem ser deixados de fora nesta fase.

A tabela apresenta os seguintes campos:

- **Tipo**: Identificação do requisito como funcional (RF) ou não funcional (RNF).
- **Descrição**: Explicação do requisito.
- **Rastreabilidade**: Técnicas utilizadas para elicitação.
- **Implementado**: Indica se o requisito já está presente na versão atual do **Meu SUS Digital**.
- **Prioridade (In/Out)**: Campo a ser preenchido de acordo com a escolha do usuário/cliente.

## Aspectos Éticos

A priorização seguiu os princípios éticos estabelecidos para estudos envolvendo o usuário/cliente. O consentimento de uso de imagem, voz e demais informações foi obtido em tempo real durante a videochamada pelo [Microsoft Teams](https://teams.microsoft.com/), durante a sessão de prirização de requisitos.

## Priorização

A prorização foi conduzida de maneira remota, em um ambiente controlado, onde os participantes utilizam uma [planilha](https://docs.google.com/spreadsheets/d/1Ch35-v9Kbp9aLsPEIEvWIf93MmTK04qt9Oxyv-p0uVM/edit?usp=sharing) contendo os requisitos elicitados, onde o cliente/usuário realiza a priorização de cada um dos requisitos definindo-os como essencial (**In**) ou descartável para o escopo inicial (**Out**). Segue, abaixo, o **Vídeo 1**, disponibilizado como vídeo não listado no YouTube, tratando da gravação da priorização dos requisitos elicitados:

<div align="center">
    <p><strong>Vídeo 1 – Priorização de Requisitos - In or Out - Meu SUS Digital</strong></p>
</div>

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/uYv6pL00_1U?si=SwDJARGrcXppsJV1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>

## Requisitos Priorizados

<div align="center">
    <p><strong>Tabela 1 – Requisitos priorizados</strong></p>
</div>

<center>

| Tipo  | Descrição | Rastreabilidade | Implementado | Prioridade (In/Out) |
| :---: | --------- | --------------- | :----------: | :-----------------: |
| RF1 | O sistema deve permitir que o paciente realize login por meio de uma conta Gov.br | OBS1, AD09 | Sim | In |
| RF2 | O aplicativo deve permitir que o paciente obtenha ajuda informativa a respeito da seção de Vacinas | OBS2 | Sim | In |
| RF3 | O aplicativo deve disponibilizar ao paciente o acesso a sua Carteira Nacional de Vacinação Digital | OBS3 | Sim | In |
| RF4 | O aplicativo deve permitir que o paciente selecione o idioma do certificado referente a sua Carteira Nacional de vacinação Digital | OBS4 | Sim | In |
| RF5 | O aplicativo deve permitir que o paciente exporte/baixe o certificado referente a sua Carteira Nacional de vacinação Digital | OBS5, AD24 | Sim | In |
| RF6 | O aplicativo deve disponibilizar ao paciente o acesso ao seu histórico de vacinas | OBS6 | Sim | In |
| RF7 | O aplicativo deve disponibilizar ao paciente o acesso aos detalhes de cada vacina | OBS7 | Sim | Out |
| RF8 | O aplicativo deve permitir que o paciente obtenha ajuda informativa a respeito da seção de Exames | OBS8 | Sim | In |
| RF9 | O aplicativo deve permitir a visualização dos exames laboratoriais realizados | OBS9 | Sim | In |
| RF10 | O aplicativo deve permitir a visualização dos resultados e demais informações a respeito dos exames laboratoriais realizados | OBS10 | Sim | In |
| RF11 | O aplicativo deve permitir a exportação/download do documento contendo o resultado e demais informações a respeito de cada exame laboratorial realizado | OBS11 | Sim | In |
| RF12 | O aplicativo deve permitir que o paciente obtenha ajuda informativa a respeito da seção de Medicamentos | OBS12 | Sim | In |
| RF13 | O aplicativo deve disponibilizar ao paciente o acesso ao seu histórico de medicamentos recebidos | OBS13 | Sim | In |
| RF14 | O aplicativo deve permitir que o paciente adicione um medicamento recebido por meio de programas de dispensação  do Governo Federal através de um mecanismo de busca | OBS14 | Sim | In |
| RF15 | O aplicativo deve permitir que o paciente possa realizar a busca por um medicamento através do nome e dosagem do mesmo | OBS15 | Sim | In |
| RF16 | O aplicativo deve fornecer ao paciente, em adesao ao Programa Farmácia Popular, a opcao de autorizar ou nao a retirada de medicamentos em seu CPF | OBS16 | Sim | Out |
| RF17 | O aplicativo deve permitir que o paciente possa verificar os medicamentos recebidos pelo Programa Farmácia Popular | OBS17 | Sim | In |
| RF18 | O aplicativo deve permitir que o paciente obtenha ajuda informativa a respeito da seção de Dignidade Menstrual | OBS18 | Sim | In |
| RF19 | Caso o paciente atenda aos critérios do Programa, o aplicativo deve permitir que o paciente emita uma autorização para participar do Programa Dignidade Menstrual | OBS19 | Sim | In |
| RF20 | O aplicativo deve permitir que o paciente exporte/baixe o documento referente a autorização de participação do Programa Dignidade Menstrual | OBS20 | Sim | In |
| RF21 | O aplicativo deve permitir que o paciente obtenha ajuda informativa a respeito da seção de Rede de saúde | OBS21 | Sim | In |
| RF22 | O aplicativo deve pedir permissão de acesso a localização do dispositivo do paciente | OBS22, AD05 | Sim | In |
| RF23 | O aplicativo deve armazenar a localização do dispositivo do paciente | OBS23, AD06 | Sim | In |
| RF24 | O aplicativo deve oferecer opcoes de estabelecimentos de saúde para que o paciente possa identificar aqueles próximos a sua localização, de acordo com o tipo de servico desejado | OBS24 | Sim | In |
| RF25 | O aplicativo deve permitir que o paciente possa identificar os estabelecimentos de saúde recentes vinculados a ele | OBS25 | Sim | In |
| RF26 | O aplicativo deve permitir que o paciente obtenha ajuda informativa a respeito da seção de Agendamentos | OBS26 | Sim | In |
| RF27 | O aplicativo deve exibir as consultas médicas ou exames de saúde do paciente | OBS27 | Sim | In |
| RF28 | O aplicativo deve possibilitar o agendamento de consultas médicas ou exames de saúde | OBS28, AD27, EN02, GF02 | Sim | In |
| RF29 | O aplicativo deve permitir que o paciente obtenha ajuda informativa a respeito da seção de Atendimento e internação | OBS29 | Sim | Out |
| RF30 | O aplicativo deve exibir os registros de atendimentos ou internações do paciente | OBS30 | Sim | In |
| RF31 | O aplicativo deve permitir que o paciente obtenha ajuda informativa a respeito da seção de Contatos | OBS31 | Sim | Out |
| RF32 | O aplicativo deve exibir contatos de profissionais de saúde | OBS32 | Sim | Out |
| RF33 | O aplicativo deve permitir que o paciente adicione o contato de um profissional de saúde em casos de emergência | OBS33 | Sim | Out |
| RF34 | O aplicativo deve permitir que o paciente obtenha ajuda informativa a respeito da seção de Diário de saúde | OBS34 | Sim | In |
| RF35 | O aplicativo deve exibir todos os registros de saúde do paciente | OBS35 | Sim | In |
| RF36 | O aplicativo deve exibir os registros de saúde do paciente referentes a sua Pressão | OBS36 | Sim | In |
| RF37 | O aplicativo deve permitir que o paciente adicione um registro de saúde referente a sua Pressão | OBS37 | Sim | In |
| RF38 | O aplicativo deve exibir os registros de saúde do paciente referentes a sua Glicose | OBS38 | Sim | In |
| RF39 | O aplicativo deve permitir que o paciente adicione um registro de saúde referente a sua Glicose | OBS39 | Sim | Out |
| RF40 | O aplicativo deve exibir os registros de saúde do paciente referentes ao seu IMC | OBS40 | Sim | In |
| RF41 | O aplicativo deve permitir que o paciente adicione um registro de saúde referente ao seu IMC | OBS41 | Sim | Out |
| RF42 | O aplicativo deve permitir que o paciente obtenha ajuda informativa a respeito da seção de Alergias | OBS42 | Sim | In |
| RF43 | O aplicativo deve exibir as alergias que paciente possui | OBS43 | Sim | In |
| RF44 | O aplicativo deve permitir que o paciente adicione uma alergia | OBS44 | Sim | In |
| RNF1 | O sistema deve garantir que o login por meio da conta Gov.br seja realizado com autenticação segura (OAuth 2.0) | OBS45, AD22 | Sim | In |
| RNF2 | O aplicativo deve exibir informações de ajuda de maneira acessível e compreensivel para todos os pacientes, incluindo pessoas com deficiência visual ou auditiva | OBS46 | Sim | In |
| RNF3 | O histórico de vacinação deve ser carregado em menos de 3 segundos em dispositivos com conexão 4G | OBS47 | Sim | In |
| RNF4 | O aplicativo deve oferecer suporte a pelo menos tres idiomas (português, inglês e espanhol) para os certificados de vacinação | OBS48, AD29 | Sim | In |
| RNF5 | O certificado de vacinação deve ser exportado em formato PDF de alta qualidade, com tamanho máximo de 2 MB | OBS49, AD32 | Sim | In |
| RNF6 | O histórico de vacinas deve ser armazenado em servidores seguros, em conformidade com a LGPD | OBS50 | Sim | In |
| RNF7 | O acesso aos detalhes de cada vacina deve ser protegido por criptografia ponta a ponta | OBS51 | Sim | In |
| RNF8 | As informações de ajuda relacionadas a exames devem ser exibidas em uma interface amigavel, seguindo padroes de usabilidade | OBS52 | Sim | In |
| RNF9 | Os resultados de exames laboratoriais devem ser apresentados em formato padronizado e visualmente acessível | OBS53 | Sim | In |
| RNF10 | Os dados sobre exames laboratoriais devem ser carregados de maneira otimizada, mesmo em conexoes lentas | OBS54 | Sim | In |
| RNF11 | Os documentos de resultados de exames laboratoriais devem ser exportados em formatos amplamente compativeis, como PDF ou JPEG | OBS55 | Sim | In |
| RNF12 | O aplicativo deve exibir informações sobre medicamentos em uma interface responsiva e acessível | OBS56 | Sim | In |
| RNF13 | O histórico de medicamentos deve ser armazenado em servidores redundantes para garantir alta disponibilidade | OBS57 | Sim | In |
| RNF14 | A busca por medicamentos deve apresentar resultados relevantes em menos de 2 segundos | OBS58 | Sim | In |
| RNF15 | A busca de medicamentos por nome e dosagem deve ser sensível a erros de digitação | OBS59 | Sim | Out |
| RNF16 | A autorização para retirada de medicamentos deve ser confirmada com autenticação segura do paciente | OBS60 | Sim | In |
| RNF17 | Os medicamentos recebidos pelo Programa Farmácia Popular devem ser exibidos em ordem cronológica | OBS61 | Sim | In |
| RNF18 | A seção de ajuda do Programa Dignidade Menstrual deve seguir diretrizes de acessibilidade (WCAG 2.1) | OBS62 | Sim | In |
| RNF19 | As autorizações para participação no Programa Dignidade Menstrual devem ser processadas em menos de 5 segundos | OBS63 | Sim | In |
| RNF20 | O documento referente à autorização do Programa Dignidade Menstrual deve ser exportado em formato PDF com validação digital | OBS64 | Sim | In |
| RNF21 | A localização do dispositivo do usuário deve ser acessada apenas com consentimento explícito e armazenada temporariamente | OBS65 | Sim | In |
| RNF22 | O aplicativo deve usar APIs de geolocalização eficientes e de baixo consumo de bateria | OBS66 | Sim | In |
| RNF23 | As opções de estabelecimentos de saúde devem ser carregadas em menos de 2 segundos | OBS67 | Sim | In |
| RNF24 | A lista de estabelecimentos de saúde recentes deve ser atualizada automaticamente sem comprometer o desempenho | OBS68 | Sim | In |
| RNF25 | O agendamento de consultas deve ser sincronizado em tempo real com os sistemas do SUS | OBS69 | Sim | In |
| RNF26 | As informações sobre consultas médicas ou exames devem ser exibidas com visualização amigável e intuitiva | OBS70 | Sim | In |
| RNF27 | O registro de atendimentos ou internações deve ser armazenado de forma segura em servidores certificados | OBS71 | Sim | In |
| RNF28 | Os contatos de profissionais de saúde devem ser exibidos em uma lista organizada, de fácil navegação | OBS72 | Sim | Out |
| RNF29 | As informações de emergência devem ser acessíveis rapidamente, com opção de busca por nome ou especialidade | OBS73 | Sim | In |
| RNF30 | Os registros de saúde do usuário devem ser apresentados em gráficos interativos e de fácil interpretação | OBS74 | Sim | In |
| RNF31 | As informações sobre Pressão, Glicose e IMC devem ser armazenadas de forma criptografada para garantir a privacidade | OBS75 | Sim | In |
| RNF32 | O aplicativo deve garantir alta disponibilidade, com no mínimo 99,5% de uptime | OBS76 | Sim | In |
| RNF33 | Os dados relacionados a alergias devem ser carregados rapidamente e protegidos contra acesso não autorizado | OBS77 | Sim | In |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>

## Considerações Finais
Este documento será utilizado para facilitar a tomada de decisão quanto às funcionalidades mais importantes a serem priorizadas no **Meu SUS Digital**. O preenchimento da coluna "Prioridade (In/Out)" será importante em etapas futuras do projeto como, por exemplo, em prototipações e/ou refinamento do escopo.

## 📚 Bibliografia
> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.
>
> REINEHR, Sheila. Engenharia de requisitos [recurso eletrônico]. Revisão técnica: Marco Antônio Paludo. Porto Alegre: SAGAH, 2020.


## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação inicial da estrutura do documento referente à técnica de priorização In or Out. | [Artur Ricardo](https://github.com/algorithmorphic) | 10/02/2024 |[Emivalto Júnior](https://github.com/EmivaltoJrr), [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 10/02/2025 |
| `1.1`  | Inserção do link da gravação da priorização, adição dos aspectos legais etc. | [Artur Ricardo](https://github.com/algorithmorphic) | 10/02/2024 | [Emivalto Júnior](https://github.com/EmivaltoJrr), [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 10/02/2025 |
| `1.2`  | Atualização da tabela contendo os requisitos priorizados. | [Artur Ricardo](https://github.com/algorithmorphic) | 10/02/2024 | [Emivalto Júnior](https://github.com/EmivaltoJrr), [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 10/02/2025 |
