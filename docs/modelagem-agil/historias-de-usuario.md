# Histórias de Usuário

## Introdução

As histórias de usuário representam um dos pilares na modelagem ágil, oferecendo uma maneira prática e centrada no usuário para capturar os requisitos de um sistema.

Diferentemente de métodos tradicionais de levantamento de requisitos, as histórias de usuário priorizam a colaboração, a adaptabilidade e a entrega contínua de valor. Baseadas em uma estrutura simples – "Como [tipo de usuário], desejo [ação] para [objetivo]" –, elas permitem que os requisitos sejam compreendidos tanto por especialistas técnicos quanto por profissionais sem formação técnica.

Este documento organiza e apresenta as histórias de usuário elicitadas para o Meu SUS Digital, estruturando-as com base nos requisitos funcionais do aplicativo. Cada história busca refletir os objetivos e problemas reais enfrentados pelos usuários, considerando o impacto prático que o sistema deve oferecer, como o acesso facilitado a informações de saúde e a digitalização de documentos importantes.

## Metodologia

A metodologia adotada para a elaboração deste documento foi baseada na divisão colaborativa do trabalho entre os membros da equipe, de forma a assegurar o equilíbrio entre eficiência no desenvolvimento e o aprendizado individual de cada integrante.

#### Divisão de Requisitos
  
Os requisitos funcionais foram distribuídos entre os integrantes da equipe, com cada membro sendo responsável por desenvolver dez histórias de usuário. Esse modelo permitiu distribuir a carga de trabalho equitativamente e promover um entendimento mais profundo de diferentes aspectos do sistema por parte de cada integrante.

#### Definição de Critérios de Aceitação

Como forma de assegurar a qualidade das histórias de usuário sem comprometer o ritmo de trabalho, foi estipulado que ao menos cinco critérios de aceitação fossem definidos por integrante. Essa flexibilização visa atender ao cronograma de desenvolvimento enquanto mantém um padrão mínimo de detalhamento e clareza nas histórias de usuário.


#### Documentação das Histórias de Usuário

Na **Tabela 1**, podemos identificar a legenda para cada uma das siglas utilizadas por todo o documento, principalmente nas tabelas.

<div align="center">
    <p><strong>Tabela 1 – Legenda para cada sigla utilizada</strong></p>
</div>

<center>

| Sigla | Descrição                   |
| :---: | --------------------------- |
| HUn   | n-ésima História de Usuário |
| RFn   | n-ésimo Requisito Funcional |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>

Quanto ao formato das histórias de usuário, estas foram documentadas no formato disposto na **Tabela 2**. 

<div align="center">
    <p><strong>Tabela 2 – Modelo para Histórias de Usuário</strong></p>
</div>

<center>

| *HUn*                 | *Título*                                                                                                   |
| --------------------- | ---------------------------------------------------------------------------------------------------------- |
| Declaração            | Eu, *como* (tipo de usuário), *desejo* (ação) *para* (objetivo/benefício).                                 |
| Critério de Aceitação | *Dado que* (contexto ou lista de condições), *Quando* (evento/ação/gatilho), *Então* (resultado esperado). |
| Prioridade            | (Muito Alta, Alta, Média, Baixa)                                                                           |
| Rastreabilidade       | [RFn](../elicitacao/requisitos-elicitados.md#requisitos/)                                                  |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>

Essa abordagem pragmática busca equilibrar qualidade, aprendizado e avanço contínuo do projeto.

## Histórias de Usuário

Abaixo, podemos identificar cada uma das histórias de usuário desenvolvidas por cada integrante da equipe:

### HU1 - Login via Gov.br

??? note "Tabela 3 - História de Usuário referente ao login via Gov.br"
    <div align="center">
        <p><strong>Tabela 3 – História de Usuário referente ao login via Gov.br</strong></p>
    </div>

    | **HU1**                   | Login via Gov.br |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, _como_ paciente, _desejo_ realizar login por meio de uma conta Gov.br _para_ acessar meus dados no aplicativo. |
    | **Critério de Aceitação** | _Dado que_ o paciente possui uma conta Gov.br, _quando_ acessar a página de login pelo aplicativo, _então_ será possível autenticar-se usando as credenciais Gov.br. |
    | **Prioridade**            | Muito Alta |
    | **Rastreabilidade**       | [RF1](../elicitacao/requisitos-elicitados.md#RF1) |

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>

### HU2 - Ajuda informativa sobre a seção de Vacinas

??? note "Tabela 4 - História de Usuário referente à ajuda informativa sobre a seção de Vacinas"
    <div align="center">
        <p><strong>Tabela 4 – História de Usuário referente à ajuda informativa sobre a seção de Vacinas</strong></p>
    </div>


    | **HU2**                   | Ajuda informativa sobre a seção de Vacinas |
    | ------------------------- | ------------------------------- |
    | **Declaração**            | Eu, _como_ usuário, _desejo_ obter ajuda informativa sobre a seção de vacinas _para_ esclarecer minhas dúvidas. |
    | **Critério de Aceitação** | _Dado que_ o usuário esteja na seção de Vacinas, _quando_ clicar no botão de ajuda, _então_ será exibida uma página com informações relevantes e úteis sobre vacinas. |
    | **Prioridade**            | Baixa |
    | **Rastreabilidade**       | [RF2](../elicitacao/requisitos-elicitados.md#RF2) |

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>

### HU3 - Acesso à Carteira Nacional de Vacinação Digital

??? note "Tabela 5 - História de Usuário referente ao acesso à Carteira Nacional de Vacinação Digital"
    <div align="center">
        <p><strong>Tabela 5 – História de Usuário referente ao acesso à Carteira Nacional de Vacinação Digital</strong></p>
    </div>

    | **HU3**                   | Acesso à Carteira Nacional de Vacinação Digital |
    | ------------------------- | ----------------------------------------------- |
    | **Declaração**            | Eu, _como_ usuário, _desejo_ acessar minha Carteira Nacional de Vacinação Digital _para_ visualizar minhas vacinas. |
    | **Critério de Aceitação** | _Dado que_ o usuário esteja autenticado, _quando_ acessar a seção de vacinação e clicar em "Acessar", _então_ será exibida sua Carteira Nacional de Vacinação Digital. |
    | **Prioridade**            | Alta |
    | **Rastreabilidade**       | [RF3](../elicitacao/requisitos-elicitados.md#RF3) |

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>

### HU4 - Seleção de idioma da Carteira Nacional de Vacinação Digital

??? note "Tabela 6 - História de Usuário referente à seleção de idioma da Carteira Nacional de Vacinação Digital"
    <div align="center">
        <p><strong>Tabela 6 – História de Usuário referente à seleção de idioma da Carteira Nacional de Vacinação Digital</strong></p>
    </div>

    | **HU4**                   | Seleção de idioma da Carteira Nacional de Vacinação Digital |
    | ------------------------- | ----------------------------------------------------------- |
    | **Declaração**            | Eu, _como_ usuário, _desejo_ selecionar o idioma da minha Carteira Nacional de Vacinação Digital _para_ facilitar sua compreensão em outros países. |
    | **Critério de Aceitação** | _Dado que_ o usuário esteja na seção referente à Carteira Nacional de Vacinação Digital, _quando_ escolher o idioma desejado, _então_ o documento será exibido no idioma selecionado. |
    | **Prioridade**            | Baixa |
    | **Rastreabilidade**       | [RF4](../elicitacao/requisitos-elicitados.md#RF4) |

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>

### HU5 - Download da Carteira Nacional de Vacinação Digital

??? note "Tabela 7 - História de Usuário referente ao download da Carteira Nacional de Vacinação Digital"
    <div align="center">
        <p><strong>Tabela 7 – História de Usuário referente ao download da Carteira Nacional de Vacinação Digital</strong></p>
    </div>

    | **HU5**                   | Download da Carteira Nacional de Vacinação Digital |
    | ------------------------- | -------------------------------------------------- |
    | **Declaração**            | Eu, _como_ usuário, _desejo_ realizar o download da minha Carteira Nacional de Vacinação Digital _para_ mantê-la armazenado no meu dispositivo celular. |
    | **Critério de Aceitação** | _Dado que_ o usuário esteja na seção referente à Carteira Nacional de Vacinação Digital, _quando_ clicar no botão de "Exportar documento", _então_ o documento será baixado no formato PDF. |
    | **Prioridade**            | Alta |
    | **Rastreabilidade**       | [RF5](../elicitacao/requisitos-elicitados.md#RF5) |

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>

### HU6 - Exportação do Certificado de Vacinação Nacional de Covid-19

??? note "Tabela 8 - História de Usuário referente à exportação do Certificado de Vacinação Nacional de Covid-19"
    <div align="center">
        <p><strong>Tabela 8 – História de Usuário referente à exportação do Certificado de Vacinação Nacional de Covid-19</strong></p>
    </div>

    | **HU6**                   | Exportação do Certificado de Vacinação Nacional de Covid-19 |
    | ------------------------- | ----------------------------------------------------------- |
    | **Declaração**            | Eu, _como_ usuário, _desejo_ exportar meu Certificado de Vacinação Nacional de Covid-19 _para_ mantê-lo armazenado no meu dispositivo celular. |
    | **Critério de Aceitação** | _Dado que_ o usuário esteja na seção de Certificado de Vacinação Nacional de Covid-19, _quando_ clicar no botão de exportação, _então_ o certificado será exportado no formato escolhido. |
    | **Prioridade**            | Média |
    | **Rastreabilidade**       | [RF75](../elicitacao/requisitos-elicitados.md#RF75) |

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>

### HU7 - Histórico de vacinas

??? note "Tabela 9 - História de Usuário referente ao histórico de vacinas"
    <div align="center">
        <p><strong>Tabela 9 – História de Usuário referente ao histórico de vacinas</strong></p>
    </div>

    | **HU7**                   | Histórico de vacinas |
    | ------------------------- | -------------------- |
    | **Declaração**            | Eu, _como_ usuário, _desejo_ acessar meu histórico de vacinas _para_ verificar quais já tomei. |
    | **Critério de Aceitação** | _Dado que_ o usuário esteja autenticado, _quando_ acessar a seção de Histórico de vacinas, _então_ será exibida a lista de vacinas recebidas. |
    | **Prioridade**            | Média |
    | **Rastreabilidade**       | [RF6](../elicitacao/requisitos-elicitados.md#RF6) |

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>

### HU8 - Detalhes de vacinas

??? note "Tabela 10 - História de Usuário referente aos detalhes de vacinas"
    <div align="center">
        <p><strong>Tabela 10 – História de Usuário referente aos detalhes de vacinas</strong></p>
    </div>

    | **HU8**                   | Detalhes de vacinas |
    | ------------------------- | ------------------- |
    | **Declaração**            | Eu, _como_ usuário, _desejo_ acessar os detalhes de cada vacina que tomei _para_ entender mais sobre elas. |
    | **Critério de Aceitação** | _Dado que_ o usuário esteja na seção de Histórico de vacinas, _quando_ clicar em uma vacina específica, _então_ os detalhes dessa vacina serão exibidos. |
    | **Prioridade**            | Média |
    | **Rastreabilidade**       | [RF7](../elicitacao/requisitos-elicitados.md#RF7) |

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>

### HU9 - Ajuda informativa sobre a seção de Exames

??? note "Tabela 11 - História de Usuário referente à ajuda informativa sobre a seção de Exames"
    <div align="center">
        <p><strong>Tabela 11 – História de Usuário referente à ajuda informativa sobre a seção de Exames</strong></p>
    </div>

    | **HU9**                   | Ajuda informativa sobre a seção de Exames |
    | ------------------------- | ----------------------------------------- |
    | **Declaração**            | Eu, _como_ usuário, _desejo_ obter ajuda informativa sobre a seção de Exames _para_ esclarecer dúvidas sobre meus exames. |
    | **Critério de Aceitação** | _Dado que_ o usuário esteja na seção de Exames, _quando_ clicar no botão de ajuda, _então_ será exibida uma página com informações relevantes e úteis sobre tal seção. |
    | **Prioridade**            | Baixa |
    | **Rastreabilidade**       | [RF8](../elicitacao/requisitos-elicitados.md#RF8) |

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>

### HU10 - Visualização de exames

??? note "Tabela 12- História de Usuário referente à visualização de exames"
    <div align="center">
        <p><strong>Tabela 12 – História de Usuário referente à visualização de exames</strong></p>
    </div>

    | **HU10**                  | Visualização de exames |
    | ------------------------- | ---------------------- |
    | **Declaração**            | Eu, _como_ usuário, _desejo_ visualizar meus exames laboratoriais realizados _para_ acompanhar os resultados. |
    | **Critério de Aceitação** | _Dado que_ o usuário esteja autenticado, _quando_ acessar a seção de Exames, _então_ será exibida a lista de exames realizados. |
    | **Prioridade**            | Média |
    | **Rastreabilidade**       | [RF9](../elicitacao/requisitos-elicitados.md#RF9) |

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>

### HU11 - Detalhes de exames

??? note "Tabela 13 - História de Usuário referente aos detalhes de exames"
    <div align="center">
        <p><strong>Tabela 13 – História de Usuário referente aos detalhes de exames</strong></p>
    </div>

    | **HU11**                  | Detalhes de exames |
    | ------------------------- | ------------------ |
    | **Declaração**            | Eu, _como_ usuário, _desejo_ visualizar os detalhes de cada exame _para_ entender os resultados e informações associadas. |
    | **Critério de Aceitação** | _Dado que_ o usuário esteja na lista de exames, _quando_ clicar em um exame específico, _então_ os detalhes desse exame serão exibidos. |
    | **Prioridade**            | Baixa |
    | **Rastreabilidade**       | [RF10](../elicitacao/requisitos-elicitados.md#RF10)                                                      |

    <div align="center">
        <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
    </div>

### HU12 - Exportação de Resultado de Exame

??? note "Tabela 14 - História de Usuário referente à Exportação de Resultado de Exame"
    <div align="center">
        <p><strong>Tabela 14 – História de Usuário referente à Exportação de Resultado de Exame</strong></p>
    </div>

    | **HU12**                   | Exportação de Resultado de Exame |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como usuário do aplicativo, desejo exportar/download do documento contendo o resultado e informações de cada exame laboratorial realizado para guardar ou compartilhar com outros profissionais de saúde. |
    | **Critério de Aceitação** | <ul> <li>Dado que o usuário tenha acessado os detalhes de um exame laboratorial</li> <li>E o documento com o resultado e informações do exame esteja disponível</li> <li>Quando o usuário clicar no botão "Exportar" ou "Fazer Download"</li> <li>Então o aplicativo deve:</li> <ul> <li>Gerar o documento no formato PDF,</li> <li>Iniciar o download automaticamente no dispositivo do usuário,</li> <li>Exibir uma mensagem de confirmação de sucesso.</li> </ul> </li> </ul> |
    | **Prioridade**            | Média |
    | **Rastreabilidade**       | [RF11](../elicitacao/requisitos-elicitados.md#RF11) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>

### HU13 - Ajuda Informativa sobre a Seção de Medicamentos

??? note "Tabela 15 - História de Usuário referente à Ajuda Informativa sobre a Seção de Medicamentos"
    <div align="center">
        <p><strong>Tabela 15 – História de Usuário referente à Ajuda Informativa sobre a Seção de Medicamentos</strong></p>
    </div>

    | **HU13**                   | Ajuda Informativa sobre a Seção de Medicamentos |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo obter ajuda informativa sobre a seção de Medicamentos para entender melhor as funcionalidades e informações disponíveis nessa seção. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja navegando na seção de Medicamentos</li> <li>E deseje mais informações ou orientações</li> <li>Quando o paciente clicar na opção "Ajuda" ou no ícone correspondente</li> <li>Então o aplicativo deve:</li> <ul> <li>Exibir um guia informativo ou FAQ relacionado à seção de Medicamentos,</li> <li>Permitir que o paciente visualize detalhes sobre as funcionalidades e o uso da seção,</li> <li>Oferecer exemplos ou links para mais informações, se aplicável.</li> </ul> </li> </ul> |
    | **Prioridade**            | Baixa |
    | **Rastreabilidade**       | [RF12](../elicitacao/requisitos-elicitados.md#RF12) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>


### HU14 - Acesso ao Histórico de Medicamentos Recebidos

??? note "Tabela 16 - História de Usuário referente ao Acesso ao Histórico de Medicamentos Recebidos"
    <div align="center">
        <p><strong>Tabela 16 – História de Usuário referente ao Acesso ao Histórico de Medicamentos Recebidos</strong></p>
    </div>

    | **HU14**                   | Acesso ao Histórico de Medicamentos Recebidos |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo acessar meu histórico de medicamentos recebidos para consultar informações sobre tratamentos realizados anteriormente. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja autenticado no aplicativo</li> <li>E tenha um histórico de medicamentos registrados</li> <li>Quando o paciente acessar a opção "Histórico de Medicamentos" no menu ou seção correspondente</li> <li>Então o aplicativo deve:</li> <ul> <li>Exibir uma lista detalhada com os medicamentos recebidos,</li> <li>Apresentar informações como nome do medicamento, data de recebimento e dosagem,</li> <li>Permitir a ordenação ou filtragem por data ou tipo de medicamento.</li> </ul> </li> </ul> |
    | **Prioridade**            | Média |
    | **Rastreabilidade**       | [RF13](../elicitacao/requisitos-elicitados.md#RF13) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>

### HU15 - Adicionar Medicamento Recebido via Programas do Governo Federal

??? note "Tabela 17 - História de Usuário referente à Adição de Medicamento Recebido via Programas do Governo Federal"
    <div align="center">
        <p><strong>Tabela 17 – História de Usuário referente à Adição de Medicamento Recebido via Programas do Governo Federal</strong></p>
    </div>

    | **HU15**                   | Adicionar Medicamento Recebido via Programas do Governo Federal |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo adicionar um medicamento recebido por meio de programas de dispensação do Governo Federal utilizando um mecanismo de busca para manter meu histórico de medicamentos atualizado de forma prática e precisa. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja autenticado no aplicativo</li> <li>E esteja na seção para adicionar medicamentos</li> <li>Quando o paciente acessar o mecanismo de busca</li> <li>E inserir o nome ou informações relacionadas ao medicamento</li> <li>Então o aplicativo deve:</li> <ul> <li>Apresentar sugestões de medicamentos com base na busca,</li> <li>Permitir que o usuário selecione o medicamento correto,</li> <li>Solicitar a confirmação das informações (como data de recebimento e quantidade),</li> <li>Registrar o medicamento no histórico do usuário após a confirmação.</li> </ul> </li> </ul> |
    | **Prioridade**            | Média |
    | **Rastreabilidade**       | [RF14](../elicitacao/requisitos-elicitados.md#RF14) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>


### HU16 - Buscar Medicamento por Nome e Dosagem

??? note "Tabela 18 - História de Usuário referente à Busca de Medicamento por Nome e Dosagem"
    <div align="center">
        <p><strong>Tabela 18 – História de Usuário referente à Busca de Medicamento por Nome e Dosagem</strong></p>
    </div>

    | **HU16**                   | Buscar Medicamento por Nome e Dosagem |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo realizar a busca por um medicamento utilizando seu nome e dosagem para localizar rapidamente as informações desejadas. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja na seção de busca de medicamentos</li> <li>Quando o paciente inserir o nome completo ou parcial do medicamento</li> <li>E a dosagem desejada</li> <li>Então o aplicativo deve:</li> <ul> <li>Retornar uma lista de medicamentos correspondentes à busca,</li> <li>Exibir informações relevantes, como nome completo, dosagem disponível e descrição,</li> <li>Permitir que o paciente selecione o medicamento para visualizar mais detalhes ou realizar ações adicionais.</li> </ul> </li> </ul> |
    | **Prioridade**            | Média |
    | **Rastreabilidade**       | [RF15](../elicitacao/requisitos-elicitados.md#RF15) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>

### HU17 - Autorizar Retirada de Medicamentos pelo CPF no Programa Farmácia Popular

??? note "Tabela 19 - História de Usuário referente à Autorização de Retirada de Medicamentos pelo CPF"
    <div align="center">
        <p><strong>Tabela 19 – História de Usuário referente à Autorização de Retirada de Medicamentos pelo CPF</strong></p>
    </div>

    | **HU17**                   | Autorizar Retirada de Medicamentos pelo CPF no Programa Farmácia Popular |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo ter a opção de autorizar ou não a retirada de medicamentos em meu CPF para garantir o controle sobre quem pode acessar meus benefícios do Programa Farmácia Popular. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja autenticado no aplicativo</li> <li>Quando o paciente acessar a opção relacionada ao Programa Farmácia Popular</li> <li>Então o aplicativo deve:</li> <ul> <li>Exibir uma opção clara para autorizar ou não a retirada de medicamentos pelo CPF,</li> <li>Permitir que o paciente altere sua escolha a qualquer momento,</li> <li>Registrar a autorização ou recusa de forma segura e acessível para futuras consultas.</li> </ul> </li> </ul> |
    | **Prioridade**            | Alta |
    | **Rastreabilidade**       | [RF16](../elicitacao/requisitos-elicitados.md#RF16) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>

### HU18 - Verificar Medicamentos Recebidos pelo Programa Farmácia Popular

??? note "Tabela 20 - História de Usuário referente à Verificação de Medicamentos Recebidos pelo Programa Farmácia Popular"
    <div align="center">
        <p><strong>Tabela 20 – História de Usuário referente à Verificação de Medicamentos Recebidos pelo Programa Farmácia Popular</strong></p>
    </div>

    | **HU18**                   | Verificar Medicamentos Recebidos pelo Programa Farmácia Popular |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo poder verificar os medicamentos recebidos pelo Programa Farmácia Popular para acompanhar meu histórico de utilização e garantir a organização do tratamento. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja autenticado no aplicativo</li> <li>Quando o paciente acessar a opção de histórico no Programa Farmácia Popular</li> <li>Então o aplicativo deve:</li> <ul> <li>Exibir uma lista com os medicamentos recebidos, incluindo a data e local da retirada,</li> <li>Organizar as informações de forma clara e ordenada por data,</li> <li>Permitir ao paciente filtrar os registros por período ou tipo de medicamento.</li> </ul> </li> </ul> |
    | **Prioridade**            | Baixa |
    | **Rastreabilidade**       | [RF17](../elicitacao/requisitos-elicitados.md#RF17) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>


### HU19 - Obter Ajuda Informativa sobre a Seção de Dignidade Menstrual

??? note "Tabela 21 - História de Usuário referente à Obtenção de Ajuda Informativa sobre a Seção de Dignidade Menstrual"
    <div align="center">
        <p><strong>Tabela 21 – História de Usuário referente à Obtenção de Ajuda Informativa sobre a Seção de Dignidade Menstrual</strong></p>
    </div>

    | **HU19**                   | Obter Ajuda Informativa sobre a Seção de Dignidade Menstrual |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo obter ajuda informativa sobre a seção de Dignidade Menstrual para compreender melhor os recursos e serviços disponíveis nessa seção. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja autenticado no aplicativo</li> <li>Quando o paciente acessar a opção de ajuda informativa na seção de Dignidade Menstrual</li> <li>Então o aplicativo deve:</li> <ul> <li>Exibir informações claras e relevantes sobre os recursos disponíveis,</li> <li>Incluir orientações sobre como acessar os serviços ou benefícios relacionados,</li> <li>Permitir ao paciente navegar para links ou documentos adicionais para mais detalhes.</li> </ul> </li> </ul> |
    | **Prioridade**            | Baixa |
    | **Rastreabilidade**       | [RF18](../elicitacao/requisitos-elicitados.md#RF18) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>

### HU20 - Emissão de Autorização para Participar do Programa Dignidade Menstrual

??? note "Tabela 22 - História de Usuário referente à Emissão de Autorização para Participar do Programa Dignidade Menstrual"
    <div align="center">
        <p><strong>Tabela 22 – História de Usuário referente à Emissão de Autorização para Participar do Programa Dignidade Menstrual</strong></p>
    </div>

    | **HU20**                   | Emissão de Autorização para Participar do Programa Dignidade Menstrual |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo emitir uma autorização para participar do Programa Dignidade Menstrual caso atenda aos critérios do programa, para garantir minha participação e acessar os benefícios oferecidos. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente esteja autenticado no aplicativo</li> <li>E atenda aos critérios do Programa Dignidade Menstrual</li> <li>Quando o paciente acessar a opção relacionada ao programa no aplicativo</li> <li>Então o aplicativo deve:</li> <ul> <li>Exibir uma opção para emitir a autorização de participação no programa,</li> <li>Confirmar a elegibilidade do paciente antes de permitir a emissão da autorização,</li> <li>Registrar a autorização emitida e fornecer um documento ou comprovante para o paciente.</li> </ul> </li> </ul> |
    | **Prioridade**            | Muito Alta |
    | **Rastreabilidade**       | [RF19](../elicitacao/requisitos-elicitados.md#RF19) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>


### HU21 - Exportação/Download do Documento de Autorização para o Programa Dignidade Menstrual

??? note "Tabela 23 - História de Usuário referente à Exportação/Download do Documento de Autorização para o Programa Dignidade Menstrual"
    <div align="center">
        <p><strong>Tabela 23 – História de Usuário referente à Exportação/Download do Documento de Autorização para o Programa Dignidade Menstrual</strong></p>
    </div>

    | **HU21**                   | Exportação/Download do Documento de Autorização para o Programa Dignidade Menstrual |
    | ------------------------- | ---------------- |
    | **Declaração**            | Eu, como paciente, desejo exportar ou baixar o documento referente à autorização de participação no Programa Dignidade Menstrual, para ter uma cópia em formato digital ou imprimir para meus registros. |
    | **Critério de Aceitação** | <ul> <li>Dado que o paciente tenha emitido a autorização para o Programa Dignidade Menstrual</li> <li>Quando o paciente acessar a opção de exportar ou baixar o documento</li> <li>Então o aplicativo deve:</li> <ul> <li>Gerar o documento no formato PDF ou outro formato apropriado,</li> <li>Iniciar o download automaticamente no dispositivo do paciente,</li> <li>Exibir uma mensagem de confirmação de sucesso ao concluir o processo de download.</li> </ul> </li> </ul> |
    | **Prioridade**            | Alta |
    | **Rastreabilidade**       | [RF20](../elicitacao/requisitos-elicitados.md#RF20) |

    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>



### HU22 - Informativa a Respeito da Seção de Rede de Saúde 

??? note "Tabela 24 - informativa a respeito da seção de Rede de Saúde  "
    <div align="center">
        <p><strong>Tabela 24 – História de Usuário referente à informativa a respeito da seção de Rede de Saúde  </strong></p>
    </div>

    | **HU22**               | informativa a respeito da seção de Rede de Saúde     |
    | ------------------------- | ---------------- |
    | **Declaração**         | Eu, como usuário, desejo obter ajuda informativa a respeito da seção de Rede de Saúde para entender melhor suas funções. |
    | **Critério de Aceitação** | <ul><li>Dado que o usuário esteja na seção de Rede de Saúde,</li><li>Quando ele solicitar ajuda,</li><li>Então o sistema deve exibir informações claras e objetivas sobre a funcionalidade dessa seção.</li></ul> |
    | **Prioridade**         | Média                                    |
     | **Rastreabilidade**       | [RF21](../elicitacao/requisitos-elicitados.md#RF21) |
    
    <div align="center">
        <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
    </div>


### HU23 - Permissão Para Acessar Minha Localização

??? note "Tabela 25 - Permissão para acessar minha localização "
    <div align="center">
        <p><strong>Tabela 25 – História de Usuário referente à permissão para acessar minha localização </strong></p>
    </div>

    | **HU23**               | Permissão para acessar minha localização |
    | ------------------------- | ---------------- |
    | **Declaração**         | Eu, como usuário, desejo que o aplicativo peça permissão para acessar minha localização para garantir segurança e privacidade. |
    | **Critério de Aceitação** | <ul><li>Dado que o aplicativo precise acessar a localização,</li><li>Quando o usuário abrir o app pela primeira vez ou acessar funcionalidades relacionadas,</li><li>Então o sistema deve solicitar permissão de acesso à localização.</li></ul>  |
    | **Prioridade**         | Média                                   |
     | **Rastreabilidade**       | [RF22](../elicitacao/requisitos-elicitados.md#RF22) |
   
    <div align="center">
        <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
    </div>


### HU24 - Armazena Localização Para Personalizar os Serviços Oferecidos

??? note "Tabela 26 - Armazena Localização Para Personalizar os Serviços Oferecidos "
    <div align="center">
        <p><strong>Tabela 26 – História de Usuário referente à Armazena Localização Para Personalizar os Serviços Oferecidos </strong></p>
    </div>

    | **HU24**               | Armazena Localização Para Personalizar os Serviços Oferecidos |
    | ------------------------- | ---------------- |
    | **Declaração**         | Eu, como usuário, desejo que o aplicativo armazene minha localização para personalizar os serviços oferecidos.  |
    | **Critério de Aceitação** |<ul><li>Dado que o aplicativo tenha permissão de localização,</li><li>Quando o usuário utilizar o app,</li><li>Então o sistema deve armazenar a localização de forma segura e em conformidade com as leis de privacidade.</li></ul>  |
    | **Prioridade**         | Baixa                      |
    | **Rastreabilidade**       | [RF23](../elicitacao/requisitos-elicitados.md#RF23) |
   
    <div align="center">
        <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
    </div>

### HU25 - Visualizar Opções de Estabelecimentos de Saúde Próximos

??? note "Tabela 27 - Visualizar opções de estabelecimentos de saúde próximos "
    <div align="center">
        <p><strong>Tabela 27 – História de Usuário referente à visualizar opções de estabelecimentos de saúde próximos </strong></p>
    </div>

    | **HU25**               | Visualizar opções de estabelecimentos de saúde próximos |
    | ------------------------- | ---------------- |
    | **Declaração**         | Eu, como usuário, desejo visualizar opções de estabelecimentos de saúde próximos à minha localização para facilitar o acesso. |
    | **Critério de Aceitação** | <ul><li>Dado que o aplicativo tenha acesso à localização,</li><li>Quando o usuário buscar por estabelecimentos,</li><li>Então o sistema deve exibir opções próximas com base no tipo de serviço desejado.</li></ul> |
    | **Prioridade**         | Alta                                   |
    | **Rastreabilidade**       | [RF24](../elicitacao/requisitos-elicitados.md#RF24) |

    <div align="center">
        <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
    </div>

### HU26 - Identificar os Estabelecimentos de Saúde Já Utilizados por mim 

??? note "Tabela 28 - Identificar os Estabelecimentos de Saúde Já Utilizados por mim  "
    <div align="center">
        <p><strong>Tabela 28 – Identificar os Estabelecimentos de Saúde Já Utilizados por mim   </strong></p>
    </div>

    | **HU26**               | Identificar os Estabelecimentos de Saúde Já Utilizados por mim     |
    | ------------------------- | ---------------- |
    | **Declaração**         | Eu, como usuário, desejo identificar os estabelecimentos de saúde recentes vinculados a mim para facilitar o acompanhamento. |
    | **Critério de Aceitação** | <ul><li>Dado que o usuário tenha histórico de estabelecimentos vinculados,</li><li>Quando ele acessar a seção de históricos,</li><li>Então o sistema deve exibir os estabelecimentos recentes de forma clara e organizada.</li></ul> |
    | **Prioridade**         | Baixa                             |
    | **Rastreabilidade**       | [RF25](../elicitacao/requisitos-elicitados.md#RF25) |
    
    <div align="center">
        <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
    </div>

### HU27 - Visualização de Consultas

??? note "Tabela 29 - Visualização de Consultas "
    <div align="center">
        <p><strong>Tabela 29 – História de Usuário referente à Visualização de Consultas </strong></p>
    </div>

    | **HU27**               | Visualização de Consultas      |
    | ------------------------- | ---------------- |
    | **Declaração**         | Eu, como usuário, desejo obter ajuda informativa a respeito da seção de Agendamentos para saber como utilizá-la.  |
    | **Critério de Aceitação** | <ul><li>Dado que o usuário esteja na seção de Agendamentos,</li><li>Quando ele solicitar ajuda,</li><li>Então o sistema deve exibir informações claras e objetivas sobre como agendar consultas ou exames.</li></ul> |
    | **Prioridade**         | Média          |
    | **Rastreabilidade**       | [RF29](../elicitacao/requisitos-elicitados.md#RF29) |
   
    <div align="center">
        <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
    </div>

### HU28 - Visualizar Exames Já realizados

??? note "Tabela 30 - Visualizar Exames Já realizados"
    <div align="center">
        <p><strong>Tabela 30 – Visualizar Exames Já realizados</strong></p>
    </div>

    | **HU28**               | Visualizar Exames Já realizados       |
    | ------------------------- | ---------------- |
    | **Declaração**         | Eu, como usuário, desejo visualizar exames já realizados de saúde para acompanhar meu histórico. |
    | **Critério de Aceitação** |<ul><li>Dado que o usuário tenha consultas ou exames registrados,</li><li>Quando ele acessar a seção de histórico,</li><li>Então o sistema deve exibir as consultas ou exames de forma clara e organizada.</li></ul>  |
    | **Prioridade**         | Alta                                    |
    | **Rastreabilidade**       | [RF30](../elicitacao/requisitos-elicitados.md#RF30) |
    
    
    <div align="center">
        <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
    </div>


### HU29 - Agendar Consultas Médicas ou Exames 

??? note "Tabela 31 - Agendar Consultas Médicas ou Exames "
    <div align="center">
        <p><strong>Tabela 31 – História de Usuário referente à Agendar Consultas Médicas ou Exames  </strong></p>
    </div>

    | **HU29**               | Agendar Consultas Médicas ou Exames              |
    | ------------------------- | ---------------- |
    | **Declaração**         | Eu, como usuário, desejo agendar consultas médicas ou exames de saúde para organizar meu cuidado médico.      |
    | **Critério de Aceitação** | < <ul><li>Dado que o usuário deseje agendar um atendimento,</li><li>Quando ele acessar a funcionalidade de agendamento,</li><li>Então o sistema deve permitir a escolha de datas, horários e serviços disponíveis.</li></ul>               |
    | **Prioridade**         | Muito Alta     |
    | **Rastreabilidade**       | [RF28](../elicitacao/requisitos-elicitados.md#RF28) |
    
    
    <div align="center">
        <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
    </div>



### HU30 - Ajuda Informativa a Respeito da Seção de Atendimento e Internação

??? note "Tabela 32 - Ajuda Informativa a Respeito da Seção de Atendimento e Internação "
    <div align="center">
        <p><strong>Tabela 32 – História de Usuário referente à ajuda informativa a respeito da seção de Atendimento e Internação </strong></p>
    </div>

    | **HU30**               |  Ajuda Informativa a Respeito da Seção de Atendimento e Internação |
    | ------------------------- | ---------------- |
    | **Declaração**         | Eu, como usuário, desejo obter ajuda informativa a respeito da seção de Atendimento e Internação para saber como usá-la.  |
    | **Critério de Aceitação** | <ul><li>Dado que o usuário esteja na seção de Atendimento e Internação,</li><li>Quando ele solicitar ajuda,</li><li>Então o sistema deve exibir informações claras e objetivas sobre a funcionalidade dessa seção.</li></ul>             |
    | **Prioridade**         | Baixa                        |
    | **Rastreabilidade**       | [RF30](../elicitacao/requisitos-elicitados.md#RF30) |
    
 
    <div align="center">
        <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
    </div>

### HU31 - Registros de Saúde

??? note "Tabela 33 -  Gráficos de Registros de Saúde "
    <div align="center">
        <p><strong>Tabela 33 – História de Usuário referente à Gráficos de Registros de Saúde </strong></p>
    </div>

    |   **HU31**               | Gráficos de Registros de Saúde |
    | ------------------------- | ---------------- |
    | **Declaração**         | Eu, como usuário, desejo que meus registros de saúde sejam apresentados em gráficos interativos para facilitar a interpretação das informações e o acompanhamento do meu histórico médico. |
    | **Critério de Aceitação** | <ul> <li>Dado que o usuário tenha registros de saúde armazenados,</li> <li>Quando ele acessar a funcionalidade de gráficos,</li> <li>Então os gráficos devem ser interativos, fáceis de interpretar e atualizados em tempo real.</li> </ul> |
    | **Prioridade**         | Baixa                      |
    | **Rastreabilidade**       | [RF30](../elicitacao/requisitos-elicitados.md#RF30) |
    
    
    <div align="center">
        <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
    </div>


### HU42 - Obter Ajuda sobre Alergias

??? note "Tabela 44 – História de Usuário Obter Ajuda sobre Alergias"
    <div align="center">
        <p><strong>Tabela 44 – História de Usuário Obter Ajuda sobre Alergias</strong></p>
    </div>

    | **HU42**                  | Obter Ajuda sobre Alergias |
    | ------------------------- | -------------------------- |
    | **Declaração**            | Eu, _como_ paciente, _desejo_ obter ajuda a respeito da seção de "Alergias" _para_ entender como utilizar essa funcionalidade. |
    | **Critério de Aceitação** | <ul><li>_Dado que_ o paciente esteja na seção de "Atendimento e Internação",</li><li>_Quando_ ele clicar em "Ajuda",</li><li>_Então_ o aplicativo deve exibir informações que expliquem a funcionalidade desta seção.</li></ul> |
    | **Prioridade**            | Média |
    | **Rastreabilidade**       | [RF42](../elicitacao/requisitos-elicitados.md/#RF42) |

    <div align="center">
        <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
    </div>

### HU43 - Visualizar Alergias

??? note "Tabela 45 – História de Usuário Visualizar Alergias"
    <div align="center">
        <p><strong>Tabela 45 – História de Usuário Visualizar Alergias</strong></p>
    </div>

    | **HU43**                  | Visualizar Alergias |
    | ------------------------- | ------------------- |
    | **Declaração**            | Eu, _como_ paciente, _desejo_ visualizar as alergias que eu declarei, _para_ garantir que eu evite substâncias ou medicamentos que possam causar reações alérgicas. |
    | **Critério de Aceitação** | <ul><li>_Dado que_ o paciente possua alergias cadastradas,</li><li>_Quando_ ele acessar a sessão "Alergias",</li><li>_Então_ o aplicativo deve oferecer a lista de alergias que o paciente declarou.</li></ul> |
    | **Prioridade**            | Baixa |
    | **Rastreabilidade**       | [RF43](../elicitacao/requisitos-elicitados.md/#RF43) |

    <div align="center">
      <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
    </div>

### HU44 - Adicionar Alergias

??? note "Tabela 46 – História de Usuário Adicionar Alergias"
    <div align="center">
        <p><strong>Tabela 46 – História de Usuário Adicionar Alergias</strong></p>
    </div>

    | **HU44**                  | Adicionar Alergias |
    | ------------------------- | ------------------ |
    | **Declaração**            | Eu, _como_ paciente, _desejo_ adicionar as alergias que eu possuo, _para_ que os profissionais de saúde tenham acesso à minha condição alérgica. |
    | **Critério de Aceitação** | <ul><li>_Dado que_ o paciente acessou a sessão de "Alergias",</li><li>_Quando_ o paciente clicar em "Adicionar Alergia",</li><li>_Então_ o aplicativo deve oferecer uma lista de alergias para o paciente escolher, dentre as quais poderão ser:<ul><li>Alimentar: leite e derivados, ovos, carne bovina, peixe, crustáceos.</li><li>Animais: gato, cachorro, insetos, animais peçonhentos.</li><li>Medicamentos: dipirona, AAS, Paracetamol.</li></ul></ul> |
    | **Prioridade**            | Alta |
    | **Rastreabilidade**       | [RF44](../elicitacao/requisitos-elicitados.md/#RF44) |

    <div align="center">
      <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
    </div>

### HU45 - Visualizar Posição na Fila de Transplantes

??? note "Tabela 47 – História de Usuário Visualizar Posição na Fila de Transplantes"
    <div align="center">
        <p><strong>Tabela 47 – História de Usuário Visualizar Posição na Fila de Transplantes</strong></p>
    </div>

    | **HU45**                  | Visualizar Posição na Fila de Transplantes |
    | ------------------------- | ------------------------------------------ |
    | **Declaração**            | Eu, _como_ paciente, _desejo_ visualizar a posição e a situação em que eu me encontro na fila de espera para transplante de órgãos e tecidos, _para_ que eu não perca a chamada quando chegar minha vez. |
    | **Critério de Aceitação** | - |
    | **Prioridade**            | Muito Alta |
    | **Rastreabilidade**       | [RF54](../elicitacao/requisitos-elicitados.md/#RF54) |

    <div align="center">
      <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
    </div>

### HU46 - Autodeclaração de Informações Pessoais

??? note "Tabela 48 – História de Usuário Autodeclaração de Informações Pessoais"
    <div align="center">
        <p><strong>Tabela 48 – História de Usuário Autodeclaração de Informações Pessoais</strong></p>
    </div>

    | **HU46**                  | Autodeclaração de Informações Pessoais |
    | ------------------------- | -------------------------------------- |
    | **Declaração**            | Eu, _como_ paciente, _desejo_ informar meu nome social, cor e endereço, _para_ que os profissionais de saúde me atendam de forma respeitosa e personalizada. |
    | **Critério de Aceitação** | - |
    | **Prioridade**            | Baixa |
    | **Rastreabilidade**       | [RF56](../elicitacao/requisitos-elicitados.md/#RF56) |

    <div align="center">
      <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
    </div>

### HU47 - Consultar Pedidos de Medicamentos

??? note "Tabela 49 – História de Usuário Consultar Pedidos de Medicamentos"
    <div align="center">
        <p><strong>Tabela 49 – História de Usuário Consultar Pedidos de Medicamentos</strong></p>
    </div>

    | **HU47**                  | Consultar Pedidos de Medicamentos |
    | ------------------------- | --------------------------------- |
    | **Declaração**            | Eu, _como_ paciente, _desejo_ visualizar meus pedidos de medicamentos, _para_ que eu possa acompanhar meu histórico de medicação e planejar melhor meu tratamento. |
    | **Critério de Aceitação** | <ul><li>_Dado que_ o paciente acessou a seção de "Medicamentos",</li><li>_Quando_ ele clicar em "Pedidos",</li><li>_Então_ o aplicativo deve exibir uma lista com os pedidos ativos de medicamentos feitos por esse paciente.</li></ul> |
    | **Prioridade**            | Média |
    | **Rastreabilidade**       | [RF62](../elicitacao/requisitos-elicitados.md/#RF62) |

    <div align="center">
      <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
    </div>

### HU48 - Aplicar Filtro de Pesquisa

??? note "Tabela 50 – História de Usuário Aplicar Filtro de Pesquisa"
    <div align="center">
        <p><strong>Tabela 50 – História de Usuário Aplicar Filtro de Pesquisa</strong></p>
    </div>

    | **HU48**                  | Aplicar Filtro de Pesquisa |
    | ------------------------- | -------------------------- |
    | **Declaração**            | Eu, _como_ paciente, _desejo_ filtrar meus pedidos de medicamentos, _para_ que eu tenha uma visualização melhor dos meus pedidos de medicamentos. |
    | **Critério de Aceitação** | <ul><li>_Dado que_ o paciente acessou a seção de "Medicamentos" e clicou em "Pedidos",</li><li>_Quando_ ele clicar em "Filtrar",</li><li>_Então_ o aplicativo deve exibir os filtros aplicáveis, dentre os quais poderão ser:<ul><li>"Em processamento".</li><li>"A caminho".</li></ul></ul></li></ul> |
    | **Prioridade**            | Média |
    | **Rastreabilidade**       | [RF68](../elicitacao/requisitos-elicitados.md/#RF68) |

    <div align="center">
      <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
    </div>

### HU49 - Realizar Pedidos de Medicamentos

??? note "Tabela 51 – História de Usuário Realizar Pedidos de Medicamentos"
    <div align="center">
        <p><strong>Tabela 51 – História de Usuário Realizar Pedidos de Medicamentos</strong></p>
    </div>

    | **HU49**                  | Realizar Pedidos de Medicamentos |
    | ------------------------- | -------------------------------- |
    | **Declaração**            | Eu, _como_ paciente, _desejo_ realizar pedidos de medicamentos, _para_ que eu possa garantir a continuidade do meu tratamento. |
    | **Critério de Aceitação** | <ul><li>_Dado que_ o paciente acessou a seção de "Medicamentos",</li><li>_Quando_ ele clicar em "Fazer Pedido",</li><li>_Então_ o aplicativo deve exibir um formulário para que o paciente possa realizar um novo pedido de medicamentos. O formulário deverá apresentar as seguintes opções:<ul><li>Um campo com uma lista de farmácias cadastradas.</li><li>Um campo com uma lista de medicamentos e a quantidade.</li><li>Um campo com a forma de entrega (retirar na farmácia ou entrega em domicílio).</li></ul></li></ul> |
    | **Prioridade**            | Alta |
    | **Rastreabilidade**       | [RF67](../elicitacao/requisitos-elicitados.md/#RF67) |

    <div align="center">
      <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
    </div>

### HU50 - Visualizar Histórico de Vacinação Pré-Pandemia

??? note "Tabela 52 – História de Usuário Visualizar Histórico de Vacinação Pré-Pandemia"
    <div align="center">
        <p><strong>Tabela 52 – História de Usuário Visualizar Histórico de Vacinação Pré-Pandemia</strong></p>
    </div>

    | **HU50**                  | Visualizar Histórico de Vacinação Pré-Pandemia |
    | ------------------------- | ---------------------------------------------- |
    | **Declaração**            | Eu, _como_ paciente, _desejo_ visualizar meu histórico de vacinação pré-pandemia, _para_ que eu possa ter um registro das vacinas que eu tomei antes desse período. |
    | **Critério de Aceitação** | - |
    | **Prioridade**            | Baixa |
    | **Rastreabilidade**       | [RF69](../elicitacao/requisitos-elicitados.md/#RF69) |

    <div align="center">
      <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
    </div>

### HU51 - Consultar Receitas Médicas

??? note "Tabela 53 – História de Usuário Consultar Receitas Médicas"
    <div align="center">
        <p><strong>Tabela 53 – História de Usuário Consultar Receitas Médicas</strong></p>
    </div>

    | **HU51**                  | Consultar Receitas Médicas |
    | ------------------------- | -------------------------- |
    | **Declaração**            | Eu, _como_ paciente, _desejo_ visualizar minhas receitas médicas, _para_ que eu possa verificar os detalhes da minha prescrição. |
    | **Critério de Aceitação** | - |
    | **Prioridade**            | Média |
    | **Rastreabilidade**       | [RF71](../elicitacao/requisitos-elicitados.md/#RF71) |

    <div align="center">
      <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
    </div>

## Validação/Priorização das Histórias de Usuário

<div align="center">
  <p><strong>Vídeo 1 – Validação e Priorização da História de Usuário 1 (HU1) até a História de Usuário 11 (HU11)</strong></p>
</div>

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/VZIy-lQZ9Gs?si=f8pAnfdA6hKfQMYT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

</center>

<div align="center">
  <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>

---

<div align="center">
  <p><strong>Vídeo 2 – Validação e Priorização da História de Usuário 12 (HU12) até a História de Usuário 21 (HU21)</strong></p>
</div>

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/YkfeefLbQT8?si=t7o-G2Qm5owHoMRS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

</center>

<div align="center">
  <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
</div>

---

<center>

**Vídeo 3** - Validação e Priorização da HU22 a HU31.

<iframe width="560" height="315" src="https://www.youtube.com/embed/_WqYGoLaDxo?si=onNtAER9uJqu-h_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Fonte: [Emivalto Júnior](https://github.com/EmivaltoJrr).

</center>

## 📚 Bibliografia

> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016.
>
> REINEHR, Sheila. Engenharia de requisitos [recurso eletrônico]. Revisão técnica: Marco Antônio Paludo. Porto Alegre: SAGAH, 2020.

## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0` | Criação do documento. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 12/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 14/12/2024 |
| `1.1` | Adição da metodologia. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 13/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 14/12/2024 |
| `1.2` | Correção de titulos das tabelas e novo modelo de tabela expansiva. | [Pedro Lopes](https://github.com/pLopess) | 14/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 15/12/2024 |
| `1.3` | Criando Histórias de Usuário. | [Pedro Lopes](https://github.com/pLopess) | 14/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 15/12/2024 |
| `1.4` | Atualização de siglas, títulos e formatação das tabelas. | [Artur Ricardo](https://github.com/algorithmorphic) | 15/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 15/12/2024 |
| `1.5` | Atualização na parte de documentação das histórias de usuário e demais alterações na ordem e conteúdo do documento. | [Artur Ricardo](https://github.com/algorithmorphic) | 15/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 15/12/2024 |
| `1.6` | Adição de história de usuário e adoção de padrão. | [Artur Ricardo](https://github.com/algorithmorphic) | 15/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 15/12/2024 |
| `1.7` | Adição de histórias de usuário. | [Pedro Lopes](https://github.com/pLopess) | 15/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 15/12/2024 |
| `1.8` | Adição de histórias de usuário e ajuste na ordem das HUs e tabelas. | [Artur Ricardo](https://github.com/algorithmorphic) | 15/12/2024 | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 15/12/2024 |
| `1.8` | Adição de histórias de usuário e ajuste |  [Emivalto Júnior](https://github.com/EmivaltoJrr) | 15/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 16/12/2024 |
| `1.9` | Validação, Priorização e adicionando video das HU 12 a 21. | [Pedro Lopes](https://github.com/pLopess) | 15/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 16/12/2024 |
| `2.0` | Adição de bibliografias utilizadas como base para confecção do documento. | [Artur Ricardo](https://github.com/algorithmorphic) | 16/12/2024 |  |  |
| `2.1` | Adição de breve introdução. | [Artur Ricardo](https://github.com/algorithmorphic) | 16/12/2024 |  |  |
| `2.2` | Coreções e ajuste de historias de usuarios |  [Emivalto Júnior](https://github.com/EmivaltoJrr) | 16/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 17/12/2024 |
| `2.3` | coreções, Validação, Priorização e adicionando video das HU 22 a 31. | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 16/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 17/12/2024 |
| `2.4` | Adição das histórias de usuário 42 a 51. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 16/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 17/12/2024 |
| `2.5` | Priorização das histórias de usuário 42 a 51. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 16/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 17/12/2024 |
| `2.6` | Priorização das histórias de usuário de 1 a 11. | [Artur Ricardo](https://github.com/algorithmorphic) | 17/12/2024 |  |  |
| `2.7` | Criação da seção referente à validação/priorização das histórias de usuário. | [Artur Ricardo](https://github.com/algorithmorphic) | 17/12/2024 |  |  |

