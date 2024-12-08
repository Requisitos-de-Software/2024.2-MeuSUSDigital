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
    <p><strong>Tabela 1 – Léxicos do tipo LAL</strong></p>
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

### L02: Carteira Nacional de Vacinação

<div align="center">
    <p><strong>Tabela 2 – Carteira Nacional de Vacinação</strong></p>
</div>

<center>

| **L02**              | **Descrição**                                                                                      |
|----------------------|----------------------------------------------------------------------------------------------------|
| **Classificação**   | Objeto                                                                                            |
| **Impacto**         | Serve como documento oficial, confirmando vacinações. Pode ter sua autenticidade validade através de QR Code ou código alfanumérico. Necessida de identificação de cidadão para ser gerada. É contruída com base nos dados de vacinação contidos no RNDS |
| **Noção**           | Documento digital que contém informações básicas do cidadão (como nome, data de nascimento, CPF, nome da mãe, nacionalidade e sexo), junto de informações de vacinação. A seção de vacinação Covid-19 é destacada das demais. Apresenta data e hora da sua emissão |
| **Dicionário**      | ─ |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/JoosPerro">João Pedro</a>.</p>
</div>



---

<div align="center">
    <p><strong>Tabela 3 – Consulta</strong></p>
</div>

<center>

| **L02**              | **Descrição**                                                                                      |
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





## Bibliografia

> <a id="REF1" href="#anchor_1">1.</a> SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 10. **Aprender 3**. Distrito Federal, 2016. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf>>. Acesso em: 08 de dezembro de 2024.
> 
> Bilheteria Digital - Léxicos. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/>. Acesso em 08 de dezembro de 2024
>



## 📑 Histórico de Versão

 Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  `1.0`  | Criação do Documento |[Emivalto Júnior](https://github.com/EmivaltoJrr)| 05/11/2024   | [Pedro Lopes](https://github.com/pLopess) | 08/12/2024 |
|  `1.1`  | Adicionando metodologia e bibliografia| [Pedro Lopes](https://github.com/pLopess)   | 08/12/2024 |  | |
|  `1.2`  | Adicionando Léxico 2 | [João Pedro](https://github.com/JoosPerro)   | 08/12/2024 |  |  |
|  `1.3`  | Adicionando Léxico 3 | [Emivalto Júnior](https://github.com/EmivaltoJrr)  | 08/12/2024 |  |  |

