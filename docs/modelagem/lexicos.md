# Lexicos

## Introdução

O Léxico é uma técnica que, por meio da descrição de termos, busca detalhar os elementos específicos de um determinado domínio. No contexto do site Meu SUS Digital, ele é utilizado para identificar palavras ou expressões características do ambiente de saúde digital, facilitando a compreensão do sistema e de suas funcionalidades. Cada termo descrito possui dois aspectos principais: a noção, que define o significado do termo no contexto do sistema, e o impacto, que representa o efeito prático ou a consequência gerada por sua aplicação ou execução dentro do ambiente analisado.


## Metodologia

Para a elaboração dos léxicos, utilizamos a notação do Léxico Ampliado da Linguagem (LAL)¹, com os conceitos detalhados na Tabela 1. O modelo utilizado pode ser consultado na Tabela 2.

<div align="center">
    <p><strong>Tabela 1 – Léxicos do tipo LAL</strong></p>
</div>

<center>

| Tipo do símbolo | Noção | Impacto |
| ----------------- | ------- | ------- |
| Sujeito | Quem é o sujeito | Ações que executa |
| Verbo | Quem realiza, quando acontece e quais os procedimentos | Quais os reflexos das ações no ambiente e novos estados decorrentes |
| Objeto | Definir o objeto e identificar outros objetos com os quais ele se relaciona | Ações que podem ser aplicadas ao objeto  |
| Estado | O que indica e ações que levaram a esse estado | Identificar outros estados que podem ocorrer a partir do estado que se descreve  |

</center>

<div align="center">
    <p>Fonte: SERRANO, Maurício e SERRANO, Milene<a id="anchor_1" href="#REF1"><sup>1</sup></a>.</p>
</div>



<div align="center">
    <p><strong>Tabela 2 – Template Léxicos</strong></p>
</div>

<center>

| ID | Descrição |
| ----------------- | ------- |
| Classificação | Objeto/Verbo/Estado |
| Impacto | Descrição de ações e de seus efeitos | 
| Noção | Símbolo |
| Dicionário | Sinônimos |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
</div>

---

## Léxicos

### L01: Histórico de Vacinação

<div align="center">
    <p><strong>Tabela 1 – Histórico de Vacinação</strong></p>
</div>

<center>

| **L01**              | **Descrição**                                                                                      |
|----------------------|----------------------------------------------------------------------------------------------------|
| **Classificação**   | Objeto                                                                                            |
| **Impacto**         | Ajuda o usuário a manter o controle sobre sua saúde, evitando doses duplicadas ou esquecimentos.   |
| **Noção**           | Registro sistemático das vacinas recebidas pelo paciente.                                          |
| **Dicionário**      | Vacina, Data, Local de vacinação, Lote, Fabricante, Dose. 

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
</div>

---

### L02: Carteira Nacional de Vacinação Digital

<div align="center">
    <p><strong>Tabela 2 – Carteira Nacional de Vacinação Digital</strong></p>
</div>

<center>

| **L02**              | **Descrição**                                                                                      |
|----------------------|----------------------------------------------------------------------------------------------------|
| **Classificação**   | Objeto                                                                                            |
| **Impacto**         | Serve como documento oficial, confirmando vacinações. Pode ter sua autenticidade <u>validada por QR Code</u> ou código alfanumérico. É gerada a partir de dados de vacinação contidos no <u>RNDS</u>. Se omite alguma vacina, precisa ser atualizada levando a caderneta física do paciente a um profissional da saúde em uma <u>Unidade Básica de Saúde</u> |
| **Noção**           | Documento digital que contém informações básicas do cidadão (como nome, data de nascimento, CPF, nome da mãe, nacionalidade e sexo), junto de informações de vacinação. A seção de vacinação Covid-19 é destacada das demais. Apresenta data e hora da sua emissão |
| **Dicionário**      | *Sinônimos*: Certidão Nacional de Vacinação. *Termos relacionados*: Valida QRCode, Valida Certidão, RNDS, Exportar documento, Padrão do Documento, Cartilha de Vacinas |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/JoosPerro">João Pedro</a>.</p>
</div>

---

### L03: Consulta

<div align="center">
    <p><strong>Tabela 3 – Consulta</strong></p>
</div>

<center>

| **L03**              | **Descrição**                                                                                      |
|----------------------|----------------------------------------------------------------------------------------------------|
| **Classificação**    | Objeto                                                                                            |
| **Impacto**          | Permite que o usuário visualize e gerencie suas consultas médicas agendadas, garantindo acesso rápido a informações como data, horário, local e especialidade. Facilita a organização da rotina de saúde do cidadão. |
| **Noção**            | Funcionalidade digital que apresenta ao usuário uma lista de consultas médicas previamente marcadas, com detalhes como data, horário, local, especialidade e profissional responsável. Pode incluir opções para reagendar ou cancelar. |
| **Dicionário**       | ─                                                                                                |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/EmivaltoJrr">Emivalto Júnior</a>.</p>
</div>

---

### L04: Certificado Nacional de Vacinação de Covid-19

<div align="center">
    <p><strong>Tabela 4 – Certificado Nacional de Vacinação de Covid-19</strong></p>
</div>

<center>

| **L04**           | **Descrição** |
| ----------------- | ------------- |
| **Classificação** | Objeto                                                                                            |
| **Impacto**       | Serve como documento oficial para comprovação da vacinação contra Covid-19, especialmente em contextos que exigem essa validação, como viagens internacionais ou acesso a eventos. Sua autenticidade pode ser validada por QR Code ou código alfanumérico. |
| **Noção**         | Documento digital gerado a partir dos dados de vacinação contra Covid-19 registrados no RNDS (Rede Nacional de Dados em Saúde). Contém informações como o nome do cidadão, doses recebidas, fabricantes das vacinas, datas de aplicação e autenticidade digital. |
| **Dicionário**    | Vacina, Covid-19, Data de vacinação, Lote, Fabricante, Dose, QR Code, Código Alfanumérico.          |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/algorithmorphic">Artur Ricardo</a>.</p>
</div>

---

### L05: Receita Médica

<div align="center">
    <p><strong>Tabela 5 – Receita Médica/strong></p>
</div>

<center>

| **L05**           | **Descrição** |
| ----------------- | ------------- |
| **Classificação** | Objeto                                                                                            |
| **Impacto**       | Serve como documento oficial para comprovação de consulta médica. Pode ter sua autenticidade validade através da assinatura digital ou carimbo do profissional de saúde. |
| **Noção**         | Documento digital que contém informações básicas do cidadão (como nome, CPF e endereço), junto de informações da receita (como nome do(s) medicamento(s), dosagem e posologia) e do profissional de saúde que a prescreveu. |
| **Dicionário**    | Receita médica, medicamento, dosagem, posologia. |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>
</div>

---



## Bibliografia

> <a id="REF1" href="#anchor_1">1.</a> SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 10. **Aprender 3**. Distrito Federal, 2016. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf>>. Acesso em: 08 de dezembro de 2024.
> 
> Bilheteria Digital - Léxicos. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/>. Acesso em 08 de dezembro de 2024.
> 
> SILVA, Lyrene Fernandes da; LEITE, Julio Cesar Sampaio do Prado; BREITMAN, Karin Koogan. C&L: uma ferramenta de apoio à engenharia de requisitos. PUC-Rio, Departamento de Informática. MCC25/04, Julho de 2004. Disponível em: [https://www.dbd.puc-rio.br/depto_informatica/04_25_silva.pdf](https://www.dbd.puc-rio.br/depto_informatica/04_25_silva.pdf). Acesso em: 7 dez. 2024.

## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação do Documento |[Emivalto Júnior](https://github.com/EmivaltoJrr) | 05/11/2024 | [Pedro Lopes](https://github.com/pLopess) | 08/12/2024 |
| `1.1`  | Adicionando metodologia e bibliografia| [Pedro Lopes](https://github.com/pLopess) | 08/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 |
| `1.2`  | Adicionando Léxico 2 | [João Pedro](https://github.com/JoosPerro) | 08/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 |
| `1.3`  | Adicionando Léxico 3 | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 08/12/2024 | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 |
| `1.4`  | Adição do Léxico 4. | [Artur Ricardo](https://github.com/algorithmorphic) | 08/12/2024 | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 08/12/2024 |
| `1.5`  | Adição do Léxico 5. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 08/12/2024 |  |  |

