# Matriz GUT

## Introdução

A Matriz GUT é uma ferramenta de qualidade proposta por Charles H. Kepner e Benjamin B. Tregoe em 1981, utilizada para definir prioridades entre diversas alternativas de ação (SOTILLE, 2014). Seu objetivo é priorizar ações de forma racional, considerando três critérios principais:

- **Gravidade (G)**: Avalia a intensidade ou profundidade dos danos que um problema pode causar se não for tratado.
- **Urgência (U)**: Considera o tempo disponível ou necessário para resolver o problema, indicando a pressão temporal existente.
- **Tendência (T)**: Analisa o potencial de crescimento do problema, ou seja, a possibilidade de piora, redução ou desaparecimento ao longo do tempo.

Cada critério é pontuado em uma escala de 1 a 5, onde valores mais altos indicam maior gravidade, urgência ou tendência. A multiplicação dessas pontuações (G × U × T) resulta em um índice que auxilia na priorização dos itens analisados.

No contexto deste projeto, a Matriz GUT foi aplicada para avaliar e organizar os requisitos, permitindo uma tomada de decisão mais eficaz e alinhada às necessidades identificadas.

## Metodologia

### 1. Levantamento de Requisitos

Foram selecionados os requisitos que foram identificados pela técnica de **[análise de documentos](../tecnicas/analise-de-documentos.md)**. Após essa etapa, foi criada uma planilha contendo todos os requisitos levantados, com o objetivo de organizar as informações para análise posterior.

### 2. Reunião com o Cliente

Uma reunião foi realizada com o cliente para alinhar expectativas e detalhar a aplicação da técnica da Matriz GUT. Durante essa etapa:  

- Foi explicada a lógica da Matriz GUT, destacando os critérios de **Gravidade**, **Urgência** e **Tendência**.  
- Exemplos práticos foram fornecidos para facilitar o entendimento e demonstrar como as notas de cada critério influenciam a priorização.

### 3. Priorização dos Requisitos

Com base na explicação anterior, o cliente foi solicitado a atribuir notas de **1 a 5** para cada requisito nos critérios de:

- **Gravidade (G):** O impacto causado caso o requisito não seja atendido.

- **Urgência (U):** O quão rapidamente o requisito precisa ser implementado.

- **Tendência (T):** A probabilidade do problema ou da necessidade se agravar ao longo do tempo.

As notas foram registradas na planilha previamente criada.

### 4. Cálculo da Prioridade

Com as notas atribuídas, foi calculado o índice de priorização para cada requisito, utilizando a fórmula:  
<center>
`Prioridade = G × U × T`
</center>

### 5. Criação da Lista Final

Os requisitos foram ordenados em ordem decrescente com base no índice de prioridade calculado. Após a organização, a lista final foi apresentada ao cliente para validação.

### 6. Confirmação

Após a validação do cliente, a lista priorizada foi consolidada, servindo como base para as próximas etapas do projeto. Os requisitos foram classificados seguindo o seguinte critério:  

- **Alta prioridade**: Pontuação de 80 a 125. Requisitos essenciais que precisam ser tratados imediatamente.

- **Prioridade média**: Pontuação de 36 a 79. Requisitos importantes, mas que podem ser resolvidos após os de alta prioridade.

- **Baixa prioridade**: Pontuação de 1 a 35. Requisitos menos críticos, que podem ser resolvidos no futuro ou em fases posteriores.



<center>

## Gravação

<p>Vídeo 1 – Reunião de priorização - Matriz GUT</p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/zibTZaYq1c4?si=fuzzpDuCDkOzvRHS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<p>Autor: <a href="https://github.com/MatheusHenrickSantos">Matheus Henrick</a>.</p>

</center>



## Priorização

| ID   | Requisito | Gravidade<br>(G) | Urgência<br>(U) | Tendência<br>(T) | Pontuação | Prioridade |
| ---- | --------- | :--------------: | :-------------: | :--------------: | :-------: | :--------: |
| [AD01](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF01 | 5 | 5 | 5 | 125 | Alta  |
| [AD02](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF02 | 5 | 5 | 5 | 125 | Alta  |
| [AD03](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF03 | 5 | 5 | 5 | 125 | Alta  |
| [AD04](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF04 | 5 | 5 | 5 | 125 | Alta  |
| [AD05](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF05 | 5 | 5 | 3 | 45  | Média |
| [AD06](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF06 | 5 | 5 | 3 | 45  | Média |
| [AD07](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF07 | 5 | 5 | 5 | 125 | Alta  |
| [AD08](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF08 | 5 | 5 | 3 | 45  | Média |
| [AD09](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF09 | 5 | 5 | 5 | 125 | Alta  |
| [AD10](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF10 | 5 | 5 | 5 | 125 | Alta  |
| [AD11](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF11 | 5 | 5 | 5 | 125 | Alta  |
| [AD12](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF12 | 4 | 3 | 2 | 24  | Baixa |
| [AD13](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF13 | 5 | 5 | 5 | 125 | Alta  |
| [AD17](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF14 | 5 | 4 | 4 | 80  | Alta  |
| [AD18](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RF15 | 5 | 4 | 3 | 60  | Média |
| [AD14](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RNF01 | 5 | 5 | 5 | 125 | Alta  |
| [AD15](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RNF02 | 5 | 5 | 5 | 125 | Alta  |
| [AD16](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RNF03 | 5 | 5 | 5 | 125 | Alta  |
| [AD19](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RNF04 | 3 | 3 | 3 | 27  | Baixa |
| [AD20](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RNF05 | 5 | 5 | 5 | 125 | Alta  |
| [AD21](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RNF06 | 5 | 5 | 3 | 75  | Média |
| [AD22](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RNF07 | 5 | 5 | 5 | 125 | Alta  |
| [AD23](../tecnicas/analise-de-documentos.md#requisitos-elicitados) | RNF08 | 5 | 5 | 5 | 125 | Alta  |



## 📚 Bibliografia

> SOTILLE, Mauro Afonso. A Ferramenta GUT – Gravidade, Urgência e Tendência. Porto Alegre: PM Tech Capacitação em Projetos, 2014. Disponível em: [https://www.gov.br/transportes/pt-br/pt-br/centrais-de-conteudo/dicas-pmp-matriz-gut-pdf](https://www.gov.br/transportes/pt-br/pt-br/centrais-de-conteudo/dicas-pmp-matriz-gut-pdf). Acesso em: 23 nov. 2024.

## 📑 Histórico de Versões

| Versão | Descrição | Autor(es) | Data de Produção | Revisor(es) | Data de Revisão | 
| :----: | --------- | --------- | :--------------: | ----------- | :-------------: |
| `1.0`  | Criação do documento. | [Matheus Henrick](https://github.com/MatheusHenrickSantos) | 24/11/2024 | [Pedro Lopes](https://github.com/pLopess) | 24/11/2024 |
