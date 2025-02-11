# Forward From

## Introdução

Este documento explora a aplicação do método de rastreabilidade forward-from. A rastreabilidade de requisitos é uma prática essencial no desenvolvimento de sistemas, pois possibilita a conexão e o acompanhamento de requisitos ao longo de todas as fases do ciclo de vida do sistema. Essa abordagem promove uma visão abrangente sobre a origem e os impactos de cada requisito, contribuindo para uma gestão eficaz de mudanças, alinhamento às expectativas do cliente e garantia da qualidade do produto final. O método forward-from concentra-se em estabelecer relações claras e robustas entre os requisitos, o design do sistema e sua implementação, assegurando maior consistência e controle no processo de desenvolvimento[1].

## Metodologia

A metodologia adotada baseia-se na matriz de rastreabilidade com a utilização de referências cruzadas [1]. Essa abordagem será aplicada aos requisitos elicitados e aos artefatos desenvolvidos nas etapas subsequentes de modelagem de requisitos e metodologias ágeis. É importante destacar que a relação entre um requisito e um artefato não é, necessariamente, de um para um. Por exemplo, um único requisito pode estar associado a múltiplos casos de uso. Na Tabela 2, a matriz de rastreabilidade é apresentada, onde as linhas correspondem aos requisitos, e as colunas representam os artefatos derivados de cada requisito.

Os artefatos contemplados nessa matriz incluem épicos, histórias do usuário, casos de uso, cenários e especificação suplementar. Cada coluna será preenchida com o identificador ou nome do respectivo artefato.

Para realizar a rastreabilidade dos elos, utilizaremos o meta-modelo proposto por Toranzo, que classifica os requisitos elicitados em níveis e elos. De acordo com o slide 19 da aula 26 da professora Milene Serrano [2], os níveis abrangem:  

- **_Ambiental_**: Essas informações provêm do ambiente e contexto nos quais a organização está inserida.
- **_Organizacional_**: São dados relacionados à própria organização.
- **_Gerencial_**: Engloba informações que auxiliam na gestão do projeto.
- **_Desenvolvimento_**: Refere-se às informações associadas aos diversos artefatos gerados durante o processo de desenvolvimento.  

Já os principais elos de rastreabilidade, conforme o slide 21 da mesma aula, são:  

1. **Satisfação**: Indica que a classe de origem depende da satisfação proporcionada pela classe de destino.
2. **Recurso**: Reflete a dependência de recursos da classe de origem em relação à classe de destino.
3. **Responsabilidade**: Registra a participação, responsabilidade e ação de pessoas sobre os artefatos.
4. **Representação**: Captura a forma como os requisitos são representados ou modelados em outras linguagens.
5. **Alocado**: Relaciona a classe de origem a uma classe de destino que representa um subsistema.
6. **Agregação**: Indica a "composição" de elementos.  

Para consolidar o meta-modelo de Toranzo, as Tabelas 2 e 3 apresentam os elementos que estruturam essa rastreabilidade, reforçando a sistematização das relações entre requisitos e artefatos.



## Matriz de rastreabilidade Forward-From

A tabela 1 representa a legenda para as siglas que serão utilizadas.


<div align="center">
    <p><strong>Tabela 1 – Legenda para cada sigla utilizada nas tabelas 2 e 3.</strong></p>
</div>

<center>

| Tipo | Descrição |
| :--: | --------- |
| RFn   | n-ésimo Requisito Funcional |
| RNFn  | n-ésimo Requisito Não Funcional |
| EPn | n-ésimo Épico |
| FTn | n-ésima Feature |
| HSn | n-ésima História de usuário |
| Ln | n-ésimo Léxico |
| UCn | n-ésimo Caso de Uso |
| CENn | n-ésimo Cenário |
| F, U, R, AD | Tipos de Especificação de Uso |
| FFn  | n-ésimo item referente ao Foward From                             |
| ELOFn | n-ésimo item referente ao elo do Foward From                     |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
</div>



A tabela 2 representa a matriz de rastreabilidade em que as linhas representam os requisitos e cada coluna representa o artefato criado a partir do requisito.

??? note "Tabela 2"

    <div align="center">
        <p><strong>Tabela 2 – Matriz de Rastreabilidade Foward From</strong></p>
    </div>

    | ID  | Requisito | Implementado | Épico | Feature | História de usuário | Caso de Uso | Cenário | Especificação Suplementar |
    | :-: | :--: | ------------ | ----- | ------- | ------------------- | ----------- | ------- | ------------------------- |
    | FF1 | [RF11](../elicitacao/requisitos-elicitados.md#RF11) | Sim | [EP4](../modelagem-agil/backlog.md) | [FT8](../modelagem-agil/backlog.md) | [HU12](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF2 | [RF12](../elicitacao/requisitos-elicitados.md#RF12) | Sim | [EP3](../modelagem-agil/backlog.md) | [FT6](../modelagem-agil/backlog.md) | [HU13](../modelagem-agil/historias-de-usuario.md) | [UC5](../modelagem/caso-de-uso.md) | [CEN7](../modelagem/cenarios.md) | - |
    | FF3 | [RF13](../elicitacao/requisitos-elicitados.md#RF13) | Sim | [EP1](../modelagem-agil/backlog.md) | [FT2](../modelagem-agil/backlog.md) | [HU14](../modelagem-agil/historias-de-usuario.md) | [UC5](../modelagem/caso-de-uso.md) | - | - |
    | FF4 | [RF14](../elicitacao/requisitos-elicitados.md#RF14) | Sim | [EP1](../modelagem-agil/backlog.md) | [FT2](../modelagem-agil/backlog.md) | [HU15](../modelagem-agil/historias-de-usuario.md) | - | [CEN6](../modelagem/cenarios.md) | - |
    | FF5 | [RF15](../elicitacao/requisitos-elicitados.md#RF15) | Sim | - | - | [HU16](../modelagem-agil/historias-de-usuario.md) | [UC3](../modelagem/caso-de-uso.md) | [CEN6](../modelagem/cenarios.md) | - |
    | FF6 | [RF16](../elicitacao/requisitos-elicitados.md#RF16) | Sim | [EP4](../modelagem-agil/backlog.md) | [FT7](../modelagem-agil/backlog.md) | [HU17](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF7 | [RF17](../elicitacao/requisitos-elicitados.md#RF17) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT11](../modelagem-agil/backlog.md) | [HU18](../modelagem-agil/historias-de-usuario.md) | [UC5](../modelagem/caso-de-uso.md) | [CEN7](../modelagem/cenarios.md) | - |
    | FF8 | [RF18](../elicitacao/requisitos-elicitados.md#RF18) | Sim | [EP3](../modelagem-agil/backlog.md) | [FT6](../modelagem-agil/backlog.md) | [HU19](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF9 | [RF19](../elicitacao/requisitos-elicitados.md#RF19) | Sim | [EP4](../modelagem-agil/backlog.md) | [FT7](../modelagem-agil/backlog.md) | [HU20](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF10 | [RF20](../elicitacao/requisitos-elicitados.md#RF20) | Sim | [EP4](../modelagem-agil/backlog.md) | [FT7](../modelagem-agil/backlog.md) | [HU21](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF11 | [RF1](../elicitacao/requisitos-elicitados.md#RF1) | Sim | [EP1](../modelagem-agil/backlog.md) | [FT1](../modelagem-agil/backlog.md) | [HU1](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF12 | [RF2](../elicitacao/requisitos-elicitados.md#RF2) | Sim | [EP3](../modelagem-agil/backlog.md) | [FT6](../modelagem-agil/backlog.md) | [HU2](../modelagem-agil/historias-de-usuario.md) | [UC9](../modelagem/caso-de-uso.md) | [CEN3](../modelagem/cenarios.md) | - |
    | FF13 | [RF3](../elicitacao/requisitos-elicitados.md#RF3) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT9](../modelagem-agil/backlog.md) | [HU3](../modelagem-agil/historias-de-usuario.md) | [UC7](../modelagem/caso-de-uso.md) | [CEN2](../modelagem/cenarios.md) | - |
    | FF14 | [RF4](../elicitacao/requisitos-elicitados.md#RF4) | Sim | [EP3](../modelagem-agil/backlog.md) | [FT5](../modelagem-agil/backlog.md) | [HU4](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF15 | [RF5](../elicitacao/requisitos-elicitados.md#RF5) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT9](../modelagem-agil/backlog.md) | [HU5](../modelagem-agil/historias-de-usuario.md) | [UC7](../modelagem/caso-de-uso.md) | [CEN1](../modelagem/cenarios.md) | - |
    | FF16 | [RF6](../elicitacao/requisitos-elicitados.md#RF6) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT10](../modelagem-agil/backlog.md) | [HU7](../modelagem-agil/historias-de-usuario.md) | [UC9](../modelagem/caso-de-uso.md) | [CEN3](../modelagem/cenarios.md) | - |
    | FF17 | [RF7](../elicitacao/requisitos-elicitados.md#RF7) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT10](../modelagem-agil/backlog.md) | [HU8](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF18 | [RF8](../elicitacao/requisitos-elicitados.md#RF8) | Sim | [EP3](../modelagem-agil/backlog.md) | [FT6](../modelagem-agil/backlog.md) | [HU9](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF19 | [RF9](../elicitacao/requisitos-elicitados.md#RF5) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT10](../modelagem-agil/backlog.md) | [HU10](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF20 | [RF10](../elicitacao/requisitos-elicitados.md#RF10) | Sim | - | - | [HU11](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF21 | [RF21](../elicitacao/requisitos-elicitados.md#RF21) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT11](../modelagem-agil/backlog.md) | [HU22](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF22 | [RF22](../elicitacao/requisitos-elicitados.md#RF22) | Sim | [EP2](../modelagem-agil/backlog.md) | [FT3](../modelagem-agil/backlog.md) | [HU23](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF23 | [RF23](../elicitacao/requisitos-elicitados.md#RF23) | Sim | [EP2](../modelagem-agil/backlog.md) | [FT3](../modelagem-agil/backlog.md) | [HU24](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF24 | [RF24](../elicitacao/requisitos-elicitados.md#RF24) | Sim | [EP2](../modelagem-agil/backlog.md) | [FT3](../modelagem-agil/backlog.md) | [HU25](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF25 | [RF25](../elicitacao/requisitos-elicitados.md#RF25) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT11](../modelagem-agil/backlog.md) | [HU26](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF26 | [RF26](../elicitacao/requisitos-elicitados.md#RF26) | Sim | [EP2](../modelagem-agil/backlog.md) | [FT4](../modelagem-agil/backlog.md) | [HU36](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF27 | [RF28](../elicitacao/requisitos-elicitados.md#RF28) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT11](../modelagem-agil/backlog.md) | [HU29](../modelagem-agil/historias-de-usuario.md) | [UC6](../modelagem/caso-de-uso.md) | - | - |
    | FF28 | [RF29](../elicitacao/requisitos-elicitados.md#RF29) | Sim | [EP2](../modelagem-agil/backlog.md) | [FT4](../modelagem-agil/backlog.md) | [HU36](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF29 | [RF30](../elicitacao/requisitos-elicitados.md#RF30) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT9](../modelagem-agil/backlog.md) | [HU28](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF30 | [RF31](../elicitacao/requisitos-elicitados.md#RF31) | Sim | [EP2](../modelagem-agil/backlog.md) | [FT4](../modelagem-agil/backlog.md) | [HU36](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF31 | [RF32](../elicitacao/requisitos-elicitados.md#RF32) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT10](../modelagem-agil/backlog.md) | [HU32](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF32 | [RF33](../elicitacao/requisitos-elicitados.md#RF33) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT10](../modelagem-agil/backlog.md) | [HU32](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF33 | [RF35](../elicitacao/requisitos-elicitados.md#RF35) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT9](../modelagem-agil/backlog.md) | [HU33](../modelagem-agil/historias-de-usuario.md) | [UC2](../modelagem/caso-de-uso.md), [UC3](../modelagem/caso-de-uso.md), [UC9](../modelagem/caso-de-uso.md) | [CEN3](../modelagem/cenarios.md), [CEN8](../modelagem/cenarios.md) | - |
    | FF34 | [RF36](../elicitacao/requisitos-elicitados.md#RF36) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT9](../modelagem-agil/backlog.md) | [HU33](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF35 | [RF37](../elicitacao/requisitos-elicitados.md#RF37) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT9](../modelagem-agil/backlog.md) | [HU33](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF36 | [RF38](../elicitacao/requisitos-elicitados.md#RF38) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT9](../modelagem-agil/backlog.md) | [HU34](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF37 | [RF39](../elicitacao/requisitos-elicitados.md#RF39) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT9](../modelagem-agil/backlog.md) | [HU33](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF38 | [RF40](../elicitacao/requisitos-elicitados.md#RF40) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT10](../modelagem-agil/backlog.md) | [HU35](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF39 | [RF41](../elicitacao/requisitos-elicitados.md#RF41) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT10](../modelagem-agil/backlog.md) | [HU35](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF40 | [RF42](../elicitacao/requisitos-elicitados.md#RF42) | Sim | [EP2](../modelagem-agil/backlog.md) | [FT4](../modelagem-agil/backlog.md) | [HU37](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF41 | [RF43](../elicitacao/requisitos-elicitados.md#RF43) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT11](../modelagem-agil/backlog.md) | [HU38](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF42 | [RF44](../elicitacao/requisitos-elicitados.md#RF44) | Sim | [EP5](../modelagem-agil/backlog.md) | [FT11](../modelagem-agil/backlog.md) | [HU39](../modelagem-agil/historias-de-usuario.md) | - | - | - |
    | FF43 | [RF71](../elicitacao/requisitos-elicitados.md#RF71) | Não | [EP5](../modelagem-agil/backlog.md) | [FT11](../modelagem-agil/backlog.md) | [HU46](../modelagem-agil/historias-de-usuario.md) | [UC3](../modelagem/caso-de-uso.md) | [CEN5](../modelagem/cenarios.md) | - |
    | FF44 | [RF69](../elicitacao/requisitos-elicitados.md#RF69) | Não | [EP5](../modelagem-agil/backlog.md) | [FT11](../modelagem-agil/backlog.md) | [HU45](../modelagem-agil/historias-de-usuario.md) | [UC2](../modelagem/caso-de-uso.md) | - | - |
    | FF45 | [RF67](../elicitacao/requisitos-elicitados.md#RF67) | Não | [EP1](../modelagem-agil/backlog.md) | [FT2](../modelagem-agil/backlog.md) | [HU44](../modelagem-agil/historias-de-usuario.md) | [UC4](../modelagem/caso-de-uso.md) | [CEN6](../modelagem/cenarios.md) | - |
    | FF46 | [RF68](../elicitacao/requisitos-elicitados.md#RF68) | Não | - | - | [HU43](../modelagem-agil/historias-de-usuario.md) | [UC5](../modelagem/caso-de-uso.md) | [CEN7](../modelagem/cenarios.md) | - |
    | FF47 | [RF62](../elicitacao/requisitos-elicitados.md#RF62) | Não | [EP1](../modelagem-agil/backlog.md) | [FT2](../modelagem-agil/backlog.md) | [HU42](../modelagem-agil/historias-de-usuario.md) | [UC5](../modelagem/caso-de-uso.md) | [CEN7](../modelagem/cenarios.md) | - |
    | FF48 | [RNF1](../elicitacao/requisitos-elicitados.md#RNF1) | Sim | - | - | - | - | - | [R](../modelagem/especificacao-suplementar.md#restricao) |
    | FF49 | [RNF3](../elicitacao/requisitos-elicitados.md#RNF3) | Sim | - | - | - | [UC9](../modelagem/caso-de-uso.md) | [CEN3](../modelagem/cenarios.md) | [P](../modelagem/especificacao-suplementar.md#performance) |
    | FF50 | [RNF12](../elicitacao/requisitos-elicitados.md#RNF12) | Sim | - | - | - | [UC4](../modelagem/caso-de-uso.md) | [CEN6](../modelagem/cenarios.md) | [S](../modelagem/especificacao-suplementar.md#seguranca) |




    <div align="center">
        <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
    </div>




## Elos

A tabela 3 apresenta os elos entre os requisitos elicitados e os artefatos definidos nos forward-from.


??? note "Tabela 3"

    <div align="center">
        <p><strong>Tabela 3 – Elos de rastreabilidade Foward From</strong></p>
    </div>

    | Elo  | ID | Satisfação | Recurso | Representação | Alocado | Agregação |
    | :-: | :--:| ---------- | ------- | ------------- | ------- | --------- |
    | ELOF1 |  |  |  |  |  |  |

    <div align="center">
        <p>Autor: <a href="https://github.com/JoosPerro">João Pedro</a>.</p>
    </div>


## Referências Bibliográficas

> [1]SAYÃO, Miriam; DO PRADO LEITE, Julio Cesar Sampaio. Rastreabilidade de requisitos. RITA, v. 13, n. 1, p. 57-86, 2006.
>
> [2]Slides da Aula 26 da Professora Milene Serrano. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 15 nov. 2023.
>
>[3] - Economia DF: Foward From. Disponível em: <<https://requisitos-de-software.github.io/2023.2-Economia-DF/rastreabilidade/forward_from/>>. Acesso em: 16 jan. 2025.

## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação do Documento |[Pedro Lopes](https://github.com/pLopess) | 16/01/2025 |  [Emivalto Júnior](https://github.com/EmivaltoJrr) | 19/01/2025 |
| `1.1`  | Adicionando tabelas |[Pedro Lopes](https://github.com/pLopess) | 16/01/2025 | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 19/01/2025 |
| `1.2`  | Preenchendo tabela FF |[Pedro Lopes](https://github.com/pLopess) | 17/01/2025 | [Emivalto Júnior](https://github.com/EmivaltoJrr) | 19/01/2025 |
| `1.3`  | Correção tabela de Requisitos Foward From |[Pedro Lopes](https://github.com/pLopess) | 10/02/2025 |   |  |