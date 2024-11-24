# Análise de Documentos



## Introdução

A Análise de Documentos é um importante método da Engenharia de Requisitos, empregado para obter informações pertinentes de fontes documentais que descrevem processos, normas, manuais, regulamentos ou qualquer outro tipo de documentação ligada ao domínio do sistema. De acordo com Vázquez e Simões (2016), essa abordagem é particularmente útil para reconhecer requisitos implícitos, tais como limitações de negócios, normas jurídicas e técnicas, ou requisitos já estabelecidos em projetos passados.

No contexto do desenvolvimento de software, a Análise de Documentos complementa outras técnicas de elicitação, como entrevistas e workshops, ao oferecer uma base sólida de informações já existentes. Por meio dela, é possível mitigar lacunas de conhecimento dos *stakeholders*, garantir a conformidade do sistema com requisitos regulatórios e alinhar o desenvolvimento às necessidades estratégicas da organização. Para sua aplicação, os autores destacam a importância de selecionar documentos confiáveis, interpretar corretamente o conteúdo e validar as descobertas com as partes interessadas.

Essa técnica é especialmente útil em projetos complexos, como no desenvolvimento de sistemas voltados à área da saúde pública, como o Meu SUS Digital. Nesse contexto, a análise de legislações, políticas de saúde e normas técnicas é imprescindível para garantir que o sistema esteja em conformidade com os requisitos legais e atenda às necessidades dos usuários. Assim, a Análise de Documentos contribui para um levantamento de requisitos mais robusto e consistente.

## Legenda

<div align="center">
    <p><strong>Tabela 1 – Legenda</strong></p>
</div>

<center>

| Termo | Significado |
| ----- | ----------- |
| Qx | Questão nºx |
| ML.x | Memória de levantamento nºx |
| RNDS | Rede Nacional de Dados em Saúde |
| SUS | Siatema Único de Saúde |
| CADSUS | Cadastro Nacional de Usuários do SUS |
| ANVISA | Agência Nacional de Vigilância Sanitária |
| CGU | Controladoria-Geral da União |
| TCU | Tribunal de Contas da união |
| RFx | Requisito Funcional nºx |
| RNFx | Requisito Não Funcional nºx |
| ADx | Requisito nºx elicitado pela Análise de Documentos |
| LGPD | Lei Geral de Proteção de Dados |
| IMC | Índice de Massa Corporal |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>



## Metodologia

A análise foi conduzida com base nas orientações descritas por Vazquez e Simões em seu livro *Engenharia de requisitos: software orientado ao negócio* (Rio de Janeiro: Brasport, 2016). Inicialmente, foi necessário compreender em que etapa do ciclo de vida de desenvolvimento o Meu SUS Digital se encontra. Como o aplicativo já está em sua fase de implantação e utilização, identificou-se que seria possível alcançar um nível de análise mais aprofundado, focando na revisão de documentos e funcionalidades existentes.

A partir disso, foram elaboradas perguntas norteadoras para a análise. Essas perguntas foram projetadas para explorar aspectos funcionais e não funcionais do sistema, considerando as necessidades dos *stakeholders* e o alinhamento com objetivos estratégicos.

Na execução, foram analisados os documentos relevantes, como especificações técnicas, requisitos originais e relatórios de desempenho do aplicativo. Os resultados da análise foram organizados em tabelas, utilizando o modelo apresentado por Vazquez e Simões, contendo as respostas às perguntas formuladas e as observações derivadas do exame dos documentos.

Por fim, o resultado dessa análise será apresentado aos *stakeholders* posteriormente, visando validar as conclusões e identificar possíveis ajustes ou oportunidades de melhoria no Meu SUS Digital.



## Perguntas para a Análise de Documentos

- Q01: Quais dados de saúde dos pacientes são coletados?
- Q02: Há políticas claras sobre a retenção e o descarte dos dados de saúde dos pacientes?
- Q03: Quem poderá ter acesso aos dados dos pacientes?
- Q04: Com quem os dados poderão ser compartilhados?
- Q05: Como é obtido o consentimento dos pacientes para a coleta e uso de seus dados pessoais?
- Q06: Como os dados são coletados?
- Q07: Quais medidas de segurança estão implementadas para proteger os dados pessoais dos pacientes?
- Q08: Por quanto tempo os dados pessoais dos pacientes são armazenados pela plataforma?



## Resumo da Análise

---

<div align="center">
    <p><strong>Tabela 2 – Resumo da Análise da Nota Informativa</strong></p>
</div>

<center>

<table border="1" cellspacing="0" cellpadding="8" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr style="background-color: #d3d3d3; color: #000;">
      <th>Tipo</th>
      <th>Localização</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Nota</td>
      <td><a href=https://meususdigital.saude.gov.br/publico/perfil/nota-informativa>https://meususdigital.saude.gov.br/publico/perfil/nota-informativa</a></td>
    </tr>
    <tr style="background-color: #d3d3d3; color: #000;">
      <td colspan="2"><strong>Nome</strong></td>
    </tr>
    <tr>
      <td colspan="2">Nota Informativa do Meu SUS Digital</td>
    </tr>
    <tr style="background-color: #d3d3d3; color: #000;">
      <td colspan="2"><strong>Memória de levantamento<strong></td>
    </tr>
    <tr>
      <td colspan="2">ML.01 - Resumo da análise da Nota Informativa <br> Objetivo: Entender como os dados são acessados <br> Pergunta/Resposta: <br> - Q01: informações relativas a medicamentos distribuídos, internações hospitalares, atendimentos ambulatoriais, de vacinação e resultados de exames. <br> - Q03: O Profissional de Saúde que, no exercício regular de sua profissão, esteja diretamente envolvido nas ações e serviços de saúde prestados a você, e tenha acesso à RNDS, do Ministério da Saúde, por meio do Conecte SUS Profissional. <br> - Q08: Os Dados de Saúde estarão disponíveis por trinta minutos ao Profissional de Saúde que esteja prestando atendimento. Os dados ficarão armazenados até que o paciente solicite a exclusão dos mesmos.</td>
    </tr>
  </tbody>
</table>

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>

---

<div align="center">
    <p><strong>Tabela 3 – Resumo da Análise da Política de Privacidade</strong></p>
</div>

<center>

<table border="1" cellspacing="0" cellpadding="8" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr style="background-color: #d3d3d3;  color: #000;">
      <th>Tipo</th>
      <th>Localização</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Política de Privacidade</td>
      <td><a href=https://meususdigital.saude.gov.br/publico/perfil/politica-privacidade>https://meususdigital.saude.gov.br/publico/perfil/politica-privacidade</a></td>
    </tr>
    <tr style="background-color: #d3d3d3;  color: #000;">
      <td colspan="2"><strong>Nome</strong></td>
    </tr>
    <tr>
      <td colspan="2">Política de Privacidade do Meu SUS Digital</td>
    </tr>
    <tr style="background-color: #d3d3d3; color: #000;">
      <td colspan="2"><strong>Memória de levantamento</strong></td>
    </tr>
    <tr>
      <td colspan="2">ML.02 - Resumo da análise da Política de Privacidade <br> Objetivo: Entender como é feita a coleta de dados <br> Pergunta/Resposta: <br> - Q05: Ao utilizar os serviços, o usuário confirma que leu e compreendeu as Políticas aplicáveis ao serviço Meu SUS Digital e concorda em ficar vinculado a eles. <br> - Q06: Nome, data de nascimento, sexo, filiação, nacionalidade, e-mail, endereço e telefone são obtidos através do CADSUS; localização e foto do paciente são obtidos através do dispositivo do mesmo, após o seu consentimento; dados de Saúde e contatos de emergência são informados pelo paciente; vacinação de covid-19, resultado de exame de covid-19 e internações hospitalares são obtidos através do RNDS; Situação Cadastral no Sistema Nacional de Transplantes é obtida através do Sistema Nacional de Transplantes. <br> - Q07: O site utiliza criptografia para que os dados sejam transmitidos de forma segura e confidencial, de maneira que a transmissão dos dados entre o servidor e o usuário, e em retroalimentação, ocorra de maneira totalmente cifrada ou encriptada. <br> - Q04: profissionais de saúde com acesso ao Conecte SUS Profissional, Secretarias Estaduais e Municipais de Saúde, ANVISA, CGU, TCU, Operador que desenvolve o Meu SUS Digital e o serviço de nuvem que armazena os dados. <br> - Q02: Sim. O serviço possui leis e normativos que são aplicáveis, como a Lei nº 12.527: Lei de Acesso à Informação, de 18 de novembro de 2011, Lei nº 13.460, de 26 de junho de 2017 e a Lei nº 13.709, de 14 de agosto de 2018.</td>
    </tr>
  </tbody>
</table>

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>

---



## Requisitos Elicitados

---

<div align="center">
    <p><strong>Tabela 4 – Requisitos Funcionais</strong></p>
</div>

<center>

| ID | Descrição | Código | Implementado |
| -- | --------- | ------ | ------------ |
| AD01 | O sistema deverá apresentar o termo de consentimento. | RF01 | Sim |
| AD02 | O sistema deverá informar quais dados serão coletados. | RF02 | Sim |
| AD03 | O sistema deverá permitir que o paciente escolha entre aceitar ou recusar a coleta de seus dados pessoais. | RF03 | Sim |
| AD04 | O sistema deverá registrar a escolha do paciente em relação à coleta de seus dados pessoais. | RF04 | Sim |
| AD05 | O sistema deverá pedir permissão de acesso à localização do dispositivo. | RF05 | Sim |
| AD06 | O sistema deverá armazenar a localização do dispositivo. | RF06 | Sim |
| AD07 | O sistema deverá pedir permissão de acesso à câmera do dispositivo. | RF07 | Sim |
| AD08 | O sistema deverá permitir ao paciente tirar sua foto utilizando a câmera do dispositivo. | RF08 | Sim |
| AD09 | O sistema deverá permitir que o paciente realize login por meio de uma conta Gov.br. | RF09 | Sim |
| AD10 | O sistema deverá buscar no CADSUS os dados do paciente (Nome, data de nascimento, sexo, filiação, nacionalidade, e-mail, endereço e telefone) utilizando o CPF associado à conta Gov.br informada no login. | RF10 | Sim |
| AD11 | O sistema deverá buscar no RNDS os dados do paciente (Histórico clínico, dados de vacinação e resultados de exames) utilizando o CPF associado à conta Gov.br informada no login. | RF11 | Sim |
| AD12 | O sistema deverá permitir que o paciente solicite a remoção de seus dados pessoais do aplicativo. | RF12 | Sim |
| AD13 | O sistema deverá permitir que o paciente altere os seus dados. | RF13 | Sim |
| AD17 | O sistema deverá permitir que o paciente informe dados pessoais adicionais, dentre os quais poderão ser: dados de saúde (alergias, IMC, pressão, glicose, doações de sangue) e contatos de emergência e de profissionais de saúde. | RF14 | Sim |
| AD18 | O sistema deverá apresentar o *status* e posição do usuário na lista de espera para transplante de órgão e tecido. | RF15 | Sim |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>

---

<div align="center">
    <p><strong>Tabela 4 – Requisitos Não Funcionais</strong></p>
</div>

<center>

| ID | Descrição | Código | Implementado |
| -- | --------- | ------ | ------------ |
| AD14 | Os dados pessoais dos pacientes devem ser protegidos por criptografia AES-256. | RNF01 | Sim |
| AD15 | O sistema deverá ser compatível com dispositivos Android e iOS. | RNF02 | Sim |
| AD16 | O armazenamento e processamento dos dados pessoais deverão estar em conformidade com a LGPD. | RNF03 | Sim |
| AD19 | O termo de consentimento deverá ser exibido em até 2 segundos após a solicitação, em dispositivos com conexão padrão. | RNF04 | Não |
| AD20 | O design do termo de consentimento deverá ser responsivo, adaptando-se a diferentes tamanhos de tela. | RNF05 | Sim |
| AD21 | As informações sobre os dados coletados deverão ser apresentadas em linguagem acessível, seguindo o padrão de leitura de nível intermediário. | RNF06 | Sim |
| AD22 | O sistema deverá garantir autenticação segura por meio do protocolo OAuth 2.0, usado pelo Gov.br. | RNF07 | Sim |
| AD23 | O sistema deverá usar conexões criptografadas (TLS 1.2 ou superior) para comunicação com os servidores do CADSUS. | RNF08 | Sim |


</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>

---

Os requisitos RNF01 e RNF08 estão implementados, porém não foi possível confirmar qual criptografia está sendo utilizada pelo aplicativo Meu SUS Digital. Portanto foram escolhidas as criptografias mais comuns para cada caso. No requisito RNF04 não foi possível estimar o tempo de resposta.

## 📚 Bibliografia

> VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira. Engenharia de requisitos: software orientado ao negócio. Rio de Janeiro: Brasport, 2016. 419 p.
>
> UNIVERSIDADE FEDERAL DE SANTA CATARINA. Técnicas de elicitação de requisitos: análise de documentos. Retraining. Disponível em: [https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-analise-de-documentos](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-analise-de-documentos). Acesso em: 20 nov. 2024.
>
> BRASIL. Ministério da Saúde. Nota informativa. Meu SUS Digital. Disponível em: [https://meususdigital.saude.gov.br/publico/perfil/nota-informativa](https://meususdigital.saude.gov.br/publico/perfil/nota-informativa). Acesso em: 21 nov. 2024.
>
> BRASIL. Ministério da Saúde. Política de privacidade. Meu SUS Digital. Disponível em: [https://meususdigital.saude.gov.br/publico/perfil/politica-privacidade](https://meususdigital.saude.gov.br/publico/perfil/politica-privacidade). Acesso em: 21 nov. 2024.



## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação do documento. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 21/11/2024 | - | - |
| `1.1`  | Correção dos títulos das tabelas. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 21/11/2024 | - | - |
| `1.2`  | Adição dos requisitos elicitados. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 22/11/2024 | - | - |
| `1.3`  | Complementando a Tabela 4. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 22/11/2024 | - | - |
| `1.4`  | Correção dos requisitos. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 23/11/2024 |  |  |
