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

| ID     | Tipo          | Descrição | Implementado | Rastreabilidade |
| :---:  | :-----------: | --------- | :----------: | --------------- |
| RNF1   | Não Funcional | O sistema deve garantir que o login por meio da conta Gov.br seja realizado com autenticação segura (OAuth 2.0) | Sim | [OBS45](tecnicas/observacao.md#requisitos-elicitados), [AD22](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RNF2   | Não Funcional | O aplicativo deve exibir informações de ajuda de maneira acessível e compreensível para todos os usuários, incluindo pessoas com deficiência visual ou auditiva | Sim | [OBS46](tecnicas/observacao.md#requisitos-elicitados) |
| RNF3   | Não Funcional | O histórico de vacinação deve ser carregado em menos de 3 segundos em dispositivos com conexão 4G | Sim | [OBS47](tecnicas/observacao.md#requisitos-elicitados) |
| RNF4   | Não Funcional | O aplicativo deve oferecer suporte a pelo menos três idiomas (português, inglês e espanhol) para os certificados de vacinação | Sim | [OBS48](tecnicas/observacao.md#requisitos-elicitados), [AD29](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RNF5   | Não Funcional | O certificado de vacinação deve ser exportado em formato PDF de alta qualidade, com tamanho máximo de 2 MB | Sim | [OBS49](tecnicas/observacao.md#requisitos-elicitados), [AD32](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RNF6   | Não Funcional | O histórico de vacinas deve ser armazenado em servidores seguros, em conformidade com a LGPD | Sim | [OBS50](tecnicas/observacao.md#requisitos-elicitados) |
| RNF7   | Não Funcional | O acesso aos detalhes de cada vacina deve ser protegido por criptografia ponta a ponta | Sim | [OBS51](tecnicas/observacao.md#requisitos-elicitados) |
| RNF8   | Não Funcional | As informações de ajuda relacionadas a exames devem ser exibidas em uma interface amigável, seguindo padrões de usabilidade | Sim | [OBS52](tecnicas/observacao.md#requisitos-elicitados) |
| RNF9   | Não Funcional | Os resultados de exames laboratoriais devem ser apresentados em formato padronizado e visualmente acessível | Sim | [OBS53](tecnicas/observacao.md#requisitos-elicitados) |
| RNF10  | Não Funcional | Os dados sobre exames laboratoriais devem ser carregados de maneira otimizada, mesmo em conexões lentas | Sim | [OBS54](tecnicas/observacao.md#requisitos-elicitados) |
| RNF11  | Não Funcional | Os documentos de resultados de exames laboratoriais devem ser exportados em formatos amplamente compatíveis, como PDF ou JPEG | Sim | [OBS55](tecnicas/observacao.md#requisitos-elicitados) |
| RNF12  | Não Funcional | O aplicativo deve exibir informações sobre medicamentos em uma interface responsiva e acessível | Sim | [OBS56](tecnicas/observacao.md#requisitos-elicitados) |
| RNF13  | Não Funcional | O histórico de medicamentos deve ser armazenado em servidores redundantes para garantir alta disponibilidade | Sim | [OBS57](tecnicas/observacao.md#requisitos-elicitados) |
| RNF14  | Não Funcional | A busca por medicamentos deve apresentar resultados relevantes em menos de 2 segundos | Sim | [OBS58](tecnicas/observacao.md#requisitos-elicitados) |
| RNF15  | Não Funcional | A busca de medicamentos por nome e dosagem deve ser sensível a erros de digitação | Sim | [OBS59](tecnicas/observacao.md#requisitos-elicitados) |
| RNF16  | Não Funcional | A autorização para retirada de medicamentos deve ser confirmada com autenticação segura do usuário | Sim | [OBS60](tecnicas/observacao.md#requisitos-elicitados) |
| RNF17  | Não Funcional | Os medicamentos recebidos pelo Programa Farmácia Popular devem ser exibidos em ordem cronológica | Sim | [OBS61](tecnicas/observacao.md#requisitos-elicitados) |
| RNF18  | Não Funcional | A seção de ajuda do Programa Dignidade Menstrual deve seguir diretrizes de acessibilidade (WCAG 2.1) | Não | [OBS62](tecnicas/observacao.md#requisitos-elicitados) |
| RNF19  | Não Funcional | As autorizações para participação no Programa Dignidade Menstrual devem ser processadas em menos de 5 segundos | Não | [OBS63](tecnicas/observacao.md#requisitos-elicitados) |
| RNF20  | Não Funcional | O documento referente à autorização do Programa Dignidade Menstrual deve ser exportado em formato PDF com validação digital | Sim | [OBS64](tecnicas/observacao.md#requisitos-elicitados) |
| RNF21  | Não Funcional | A localização do dispositivo do usuário deve ser acessada apenas com consentimento explícito e armazenada temporariamente | Sim | [OBS65](tecnicas/observacao.md#requisitos-elicitados) |
| RNF22  | Não Funcional | O aplicativo deve usar APIs de geolocalização eficientes e de baixo consumo de bateria | Sim | [OBS66](tecnicas/observacao.md#requisitos-elicitados) |
| RNF23  | Não Funcional | As opções de estabelecimentos de saúde devem ser carregadas em menos de 2 segundos | Não | [OBS67](tecnicas/observacao.md#requisitos-elicitados) |
| RNF24  | Não Funcional | A lista de estabelecimentos de saúde recentes deve ser atualizada automaticamente sem comprometer o desempenho | Sim | [OBS68](tecnicas/observacao.md#requisitos-elicitados) |
| RNF25  | Não Funcional | O agendamento de consultas deve ser sincronizado em tempo real com os sistemas do SUS | Sim | [OBS69](tecnicas/observacao.md#requisitos-elicitados) |
| RNF26  | Não Funcional | As informações sobre consultas médicas ou exames devem ser exibidas com visualização amigável e intuitiva | Sim | [OBS70](tecnicas/observacao.md#requisitos-elicitados) |
| RNF27  | Não Funcional | O registro de atendimentos ou internações deve ser armazenado de forma segura em servidores certificados | Sim | [OBS71](tecnicas/observacao.md#requisitos-elicitados) |
| RNF28  | Não Funcional | Os contatos de profissionais de saúde devem ser exibidos em uma lista organizada, de fácil navegação | Sim | [OBS72](tecnicas/observacao.md#requisitos-elicitados) |
| RNF29  | Não Funcional | As informações de emergência devem ser acessíveis rapidamente, com opção de busca por nome ou especialidade | Não | [OBS73](tecnicas/observacao.md#requisitos-elicitados) |
| RNF30  | Não Funcional | Os registros de saúde do usuário devem ser apresentados em gráficos interativos e de fácil interpretação | Sim | [OBS74](tecnicas/observacao.md#requisitos-elicitados) |
| RNF31  | Não Funcional | As informações sobre Pressão, Glicose e IMC devem ser armazenadas de forma criptografada para garantir a privacidade | Sim | [OBS75](tecnicas/observacao.md#requisitos-elicitados) |
| RNF32  | Não Funcional | O aplicativo deve garantir alta disponibilidade, com no mínimo 99,5% de uptime | Sim | [OBS76](tecnicas/observacao.md#requisitos-elicitados) |
| RNF33  | Não Funcional | Os dados relacionados a alergias devem ser carregados rapidamente e protegidos contra acesso não autorizado | Sim | [OBS77](tecnicas/observacao.md#requisitos-elicitados) |
| RNF34  | Não Funcional | Os dados pessoais dos pacientes devem ser protegidos por criptografia AES-256. | Sim | [AD14](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RNF35  | Não Funcional | O sistema deverá ser compatível com dispositivos Android e iOS. | Sim | [AD15](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RNF36  | Não Funcional | O armazenamento e processamento dos dados pessoais deverão estar em conformidade com a LGPD. | Sim | [AD16](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RNF37  | Não Funcional | O termo de consentimento deverá ser exibido em até 5 segundos após a solicitação, em dispositivos com conexão 4G. | Sim | [AD19](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RNF38  | Não Funcional | O design do termo de consentimento deverá ser responsivo, adaptando-se a diferentes tamanhos de tela. | Sim | [AD20](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RNF39  | Não Funcional | As informações sobre os dados coletados deverão ser apresentadas em linguagem acessível, seguindo o padrão de leitura de nível intermediário. | Sim | [AD21](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RNF40  | Não Funcional | O sistema deverá usar conexões criptografadas (TLS 1.2 ou superior) para comunicação com os servidores do CADSUS. | Sim | [AD23](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RNF41  | Não Funcional | O sistema deverá atualizar as informações presentes no cartão de vacinação em até 10 dias após o registro dos dados no sistema do Ministério da Saúde. | Sim | [AD28](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RNF42  | Não Funcional | A notificação de consultas agendadas deverá ser feita com pelo menos 12 horas de antecedência. | Sim | [AD31](tecnicas/analise-de-documentos.md#requisitos-elicitados) |
| RNF43  | Não Funcional | A aplicação pode receber informações do usuário através de biosensores | Não | [EN01](tecnicas/entrevista.md#requisitos-elicitados) |
| RNF44  | Não Funcional | O fluxo para solicitar medicamentos deve ser concluído em até 5 cliques/telas | Não | [EN14](tecnicas/entrevista.md#requisitos-elicitados) |
| RNF45  | Não Funcional | A aplicação deve processar a solicitação de medicamentos e fornecer uma resposta em até 5 segundos | Não | [EN15](tecnicas/entrevista.md#requisitos-elicitados) |
| RNF46  | Não Funcional | O resultado da consulta de pedidos de medicamento deve ser exibido em ordem cronológica | Não | [EN16](tecnicas/entrevista.md#requisitos-elicitados) |
| RNF47  | Não Funcional | A receita médica deve ser exportada em formato PDF de alta qualidade, com tamanho máximo de 2 MB | Não | [GF08](tecnicas/grupo-de-foco.md#requisitos-elicitados) |
| RNF48  | Não Funcional | O resultado da consulta de receitas médicas deve ser exibido em ordem cronológica | Não | [GF09](tecnicas/grupo-de-foco.md#requisitos-elicitados) |

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
| `1.3`  | Adição da tabela de rastreabilidade para trás referente aos requisitos funcionais não elicitados. | [Artur Ricardo](https://github.com/algorithmorphic) | 19/01/2025 |  |  |