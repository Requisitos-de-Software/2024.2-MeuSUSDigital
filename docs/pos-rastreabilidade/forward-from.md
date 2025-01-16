# Forward From

## Introdução

Este documento explora a aplicação do método de rastreabilidade forward-from. A rastreabilidade de requisitos é uma prática essencial no desenvolvimento de sistemas, pois possibilita a conexão e o acompanhamento de requisitos ao longo de todas as fases do ciclo de vida do sistema. Essa abordagem promove uma visão abrangente sobre a origem e os impactos de cada requisito, contribuindo para uma gestão eficaz de mudanças, alinhamento às expectativas do cliente e garantia da qualidade do produto final. O método forward-from concentra-se em estabelecer relações claras e robustas entre os requisitos, o design do sistema e sua implementação, assegurando maior consistência e controle no processo de desenvolvimento[1].

## Metodologia

A metodologia adotada baseia-se na matriz de rastreabilidade com a utilização de referências cruzadas [1]. Essa abordagem será aplicada aos requisitos elicitados e aos artefatos desenvolvidos nas etapas subsequentes de modelagem de requisitos e metodologias ágeis. É importante destacar que a relação entre um requisito e um artefato não é, necessariamente, de um para um. Por exemplo, um único requisito pode estar associado a múltiplos casos de uso. Na Tabela 1, a matriz de rastreabilidade é apresentada, onde as linhas correspondem aos requisitos, e as colunas representam os artefatos derivados de cada requisito.

Os artefatos contemplados nessa matriz incluem épicos, temas, histórias do usuário, léxicos, casos de uso, cenários, especificação suplementar e o framework NFR. Cada coluna será preenchida com o identificador ou nome do respectivo artefato.

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

Para consolidar o meta-modelo de Toranzo, as Tabelas 1 e 2 apresentam os elementos que estruturam essa rastreabilidade, reforçando a sistematização das relações entre requisitos e artefatos.



## Matriz de rastreabilidade Forward-From

A tabela 1 representa a matriz de rastreabilidade em que as linhas representam os requisitos e cada coluna representa o artefato criado a partir do requisito.

<div align="center">
    <p><strong>Tabela 1 – Legenda para cada sigla utilizada</strong></p>
</div>

<center>

| Tipo | Descrição |
| :--: | --------- |
| RF   |  Requisito Funcional |
| RNF  |  Requisito Não Funcional |
| ADn  | n-ésimo Requisito elicitado pela técnica de Análise de Documentos |
| ENn  | n-ésimo Requisito elicitado pela técnica de Entrevista |
| GFn  | n-ésimo Requisito elicitado pela técnica de Grupo de Foco         |
| INTn | n-ésimo Requisito elicitado pela técnica de Introspecção          |
| OBSn | n-ésimo Requisito elicitado pela técnica de Observação            |
| QUEn | n-ésimo Requisito elicitado pela técnica de Questionário          |
| FFn  | n-ésimo item referente ao Foward From                             |

</center>

<div align="center">
    <p>Autor: <a href="https://github.com/pLopess">Pedro Lopes</a>.</p>
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
| `1.0`  | Criação do Documento |[Pedro Lopes](https://github.com/pLopess) | 16/01/2025 | | |