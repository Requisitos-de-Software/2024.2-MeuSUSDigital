# Backlog

## Introdução

O Backlog do Produto é uma lista organizada e priorizada que reúne todas as tarefas, funcionalidades, melhorias e correções necessárias para o desenvolvimento de um produto. Esse artefato é gerenciado pelo Dono do Produto (Product Owner), que sugere e ajusta os itens de acordo com a visão e os objetivos do projeto. Dinâmico por natureza, o backlog é atualizado continuamente para refletir mudanças nas necessidades, requisitos ou prioridades, garantindo que o trabalho da equipe esteja sempre alinhado aos objetivos estratégicos do produto.

## Metodologia

Após a elicitação das histórias de usuário, foram definidos os critérios de aceitação e as prioridades de cada uma delas, classificadas pelo PO como baixa, média, alta ou muito alta. Em seguida, temas, épicos e features foram estabelecidos para organizar e categorizar as histórias de usuário. A Tabela X ilustra o backlog do produto, o restante deste documento aprofunda o processo de definição de temas, épicos e features, bem como o significado de cada um desses termos. Os detalhes de cada história de usuário podem ser encontrados pela rastreabilidade na tabela que levará ao artefato específico de Histórias de Usuários.

<center>

 Backlog do Produto.

</center>


<center>


<table>
  <thead>
    <tr>
      <th>Épico</th>
      <th>Feature</th>
      <th>História de usuário</th>
      <th>Priorização</th>
    </tr>
  </thead>
  <tbody>
    <!-- Épico 1 -->
    <tr>
      <td rowspan="6">Épico 1 - Acesso a Serviços</td>
      <td rowspan="2">Feature 1 - Login e Registro</td>
      <td>HU1 - Login via Gov.br</td>
      <td>Muito Alta</td>
    </tr>
    <tr>
      <td>HU41 - Autodeclaração de Informações Pessoais</td>
      <td>Baixa</td>
    </tr>
    <tr>
      <td rowspan="4">Feature 2 - Consulta de Medicamentos</td>
      <td>HU14 - Acesso ao Histórico de Medicamentos Recebidos</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>HU42 - Consultar Pedidos de Medicamentos</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>HU15 - Adicionar Medicamento Recebido via Programas do Governo Federal</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>HU44 - Realizar Pedidos de Medicamentos</td>
      <td>Alta</td>
    </tr>
    <!-- Épico 2 -->
    <tr>
      <td rowspan="5">Épico 2 - Notificações e Alertas</td>
      <td rowspan="3">Feature 3 - Notificações de Saúde</td>
      <td>HU23 - Permissão para acessar minha localização</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>HU24 - Armazena Localização Para Personalizar os Serviços Oferecidos</td>
      <td>Baixa</td>
    </tr>
    <tr>
      <td>HU25 - Visualizar opções de estabelecimentos de saúde próximos</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td rowspan="2">Feature 4 - Dicas de Saúde</td>
      <td>HU36 - Obter ajuda nas seções de contato e indicadores de saúde</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>HU37 - Obter Ajuda sobre Alergias</td>
      <td>Média</td>
    </tr>
    <!-- Épico 3 -->
    <tr>
      <td rowspan="6">Épico 3 - Acessibilidade</td>
      <td rowspan="2">Feature 5 - Acessibilidade Digital</td>
      <td>HU4 - Seleção de idioma da Carteira Nacional de Vacinação Digital</td>
      <td>Baixa</td>
    </tr>
    <tr>
      <td>HU30 - Ajuda Informativa a Respeito da Seção de Atendimento e Internação</td>
      <td>Baixa</td>
    </tr>
    <tr>
      <td rowspan="4">Feature 6 - Suporte ao Usuário</td>
      <td>HU2 - Ajuda informativa sobre a seção de Vacinas</td>
      <td>Baixo</td>
    </tr>
    <tr>
      <td>HU9 - Ajuda informativa sobre a seção de Exames</td>
      <td>Baixa</td>
    </tr>
    <tr>
      <td>HU13 - Ajuda Informativa sobre a Seção de Medicamentos</td>
      <td>Baixa</td>
    </tr>
    <tr>
      <td>HU19 - Obter Ajuda Informativa sobre a Seção de Dignidade Menstrual</td>
      <td>Baixa</td>
    </tr>
    <!-- Épico 4 -->
    <tr>
      <td rowspan="5">Épico 4 - Segurança e Privacidade</td>
      <td rowspan="3">Feature 7 - Proteção de Dados</td>
      <td>HU20 - Emissão de Autorização para Participar do Programa Dignidade Menstrual</td>
      <td>Muito Alta</td>
    </tr>
    <tr>
      <td>HU21 - Exportação/Download do Documento de Autorização para o Programa Dignidade Menstrual</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>HU17 - Autorizar Retirada de Medicamentos pelo CPF no Programa Farmácia Popular</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td rowspan="2">Feature 8 - Prevenção de Erros</td>
      <td>HU6 - Exportação do Certificado de Vacinação Nacional de Covid-19</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>HU12 - Exportação de Resultado de Exame</td>
      <td>Média</td>
    </tr>
    <!-- Épico 5 -->
    <tr>
      <td rowspan="21">Épico 5 - Padronização e Usabilidade</td>
      <td rowspan="5">Feature 9 - Interface Intuitiva</td>
      <td>HU3 - Acesso à Carteira Nacional de Vacinação Digital</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>HU5 - Download da Carteira Nacional de Vacinação Digital</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>HU28 - Visualizar Exames Já realizados</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>HU33 - Consultar e atualizar registros de pressão arterial</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>HU34 - Consultar e atualizar registros de glicose</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td rowspan="6">Feature 10 - Ferramentas Necessárias</td>
      <td>HU7 - Histórico de vacinas</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>HU8 - Detalhes de vacinas</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>HU10 - Visualização de exames</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>HU32 - Consultar e atualizar contatos de profissionais de saúde</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>HU35 - Atualizar registros de IMC</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>HU27 - Visualização de Consultas</td>
      <td>Média</td>
    </tr>
    <tr>
      <td rowspan="10">Feature 11 - Serviços Complementares</td>
      <td>HU29 - Agendar Consultas Médicas ou Exames</td>
      <td>Muito Alta</td>
    </tr>
    <tr>
      <td>HU40 - Visualizar Posição na Fila de Transplantes</td>
      <td>Muito Alta</td>
    </tr>
    <tr>
      <td>HU39 - Adicionar Alergias</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>HU45 - Visualizar Histórico de Vacinação Pré-Pandemia</td>
      <td>Baixa</td>
    </tr>
    <tr>
      <td>HU46 - Consultar Receitas Médicas</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>HU22 - Informativa a respeito da seção de Rede de Saúde</td>
      <td>Média</td>
    </tr>
    <tr>
      <td>HU18 - Verificar Medicamentos Recebidos pelo Programa Farmácia Popular</td>
      <td>Baixa</td>
    </tr>
    <tr>
      <td>HU38 - Visualizar Alergias</td>
      <td>Baixa</td>
    </tr>
    <tr>
      <td>HU31 - Gráficos de Registros de Saúde</td>
      <td>Baixa</td>
    </tr>
    <tr>
      <td>HU26 - Identificar os Estabelecimentos de Saúde Já Utilizados por mim</td>
      <td>Baixa</td>
    </tr>
  </tbody>
</table>


<div align="center">
    <p><strong>Apresentação Entrega 2</strong></p>
    <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
</div>

</center>


## Temas

Após analisar as Historias de Usuário identificamos os seguintes temas:
- **Funcionalidades**: Refere-se aos recursos que o sistema precisa oferecer para que o usuário possa desempenhar suas atividades de forma eficiente.  
- **Perfil**: Trata das características voltadas à adaptação do sistema às preferências e demandas específicas de cada usuário.

## Épicos

Com o objetivo de reduzir a abstração, exemplificamos melhor os temas dentro dos épicos. Os épicos são blocos de trabalho  que representam  objetivos ou funcionalidades do projeto, servindo como base para detalhamentos posteriores.

### Épico 1 - Acesso a Serviços


"Eu, como usuário, desejo acessar serviços e informações de saúde de forma simples e segura para gerenciar minha saúde com facilidade."

Este épico abrange funcionalidades que permitem ao usuário registrar-se, fazer login e consultar medicamentos, garantindo acesso rápido e eficiente aos serviços de saúde.

### Épico 2 - Notificações e Alertas

"Eu, como usuário, desejo receber notificações e alertas sobre minha saúde para me manter informado e não perder prazos importantes."

Esse épico inclui o envio de notificações sobre vacinas, exames e dicas de saúde, ajudando o usuário a estar sempre atualizado com informações relevantes.

### Épico 3 - Acessibilidade

"Eu, como usuário com necessidades específicas, desejo contar com uma interface acessível para utilizar o sistema sem barreiras."

Este épico foca na inclusão, garantindo que pessoas com deficiência visual ou dificuldades de navegação possam acessar o sistema de maneira intuitiva e eficiente.

### Épico 4 - Segurança e Privacidade


"Eu, como usuário, desejo que meus dados estejam protegidos e sejam usados de forma segura para garantir minha privacidade."

Este épico prioriza a proteção de dados, autenticação segura e prevenção de erros, assegurando que o usuário confie no sistema.


### Épico 5 - Padronização e Usabilidade


"Eu, como usuário, desejo acessar uma interface intuitiva e organizada para encontrar facilmente os serviços que preciso."

Esse épico visa melhorar a usabilidade do sistema, com ferramentas e funcionalidades que tornam a navegação mais simples e eficiente, além de oferecer histórico de ações e opções práticas.



## Features 

As features são divisões mais específicas dos épicos, representando funcionalidades ou capacidades menores que ajudam a atingir os objetivos gerais definidos nos épicos. No contexto de desenvolvimento ágil, as features facilitam o planejamento, a priorização e a entrega incremental de valor, permitindo que as equipes tenham uma compreensão clara das funcionalidades específicas que precisam ser implementadas.


## 📚 Bibliografia

> Patton, J. (2014). *User Story Mapping: Discover the Whole Story, Build the Right Product*. O'Reilly Media.

> Backlog. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: [https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/). Acesso em: 14 dez. 2024.

## 📑 Histórico de Versão

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão |  
| :----: | :-------: | :-------: | :--------------: | :---------: | :-------------: |
| `1.0`  | Criação do Documento. | [Pedro Lopes](https://github.com/pLopess) | 14/12/2024 |  [Emivalto Júnior](https://github.com/EmivaltoJrr) | 15/12/2024 |
| `1.1`  | Adição de tabelas e epicos. | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 15/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 17/12/2024 |
| `1.2`  | Adição de HUs na tabelaba de Backlog. | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 17/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 17/12/2024 |
| `1.3`  | Correção da tabela de Backlog. | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 17/12/2024 | [Pedro Lopes](https://github.com/pLopess) | 17/12/2024 |
| `1.4`  | Criação de Temas. | [Pedro Lopes](https://github.com/pLopess) | 17/12/2024 |  |  |
