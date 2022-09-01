# Solicitação / Itens

## Objetivo da tela

O objetivo principal desta tela é escolher itens para gerar Autorização de fornecimento (AF) sendo os itens pertencentes à qualquer solicitação. Como objetivo secundário a tela permite que o usuário realize algumas ações como Preencher NDO, Informar contrato, Gerar licitação, Gerar cotação, Informar previsão de entrega.

## Documentação

**Documentação para Desenvolvimento (Zeplin)**\
[https://app.zeplin.io/project/5bbe06f64859890a3efe0bdf?seid=5e14c96dca1fbf54bfb300a6](https://app.zeplin.io/project/5bbe06f64859890a3efe0bdf?seid=5e14c96dca1fbf54bfb300a6)

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/df9c261d-fb6d-4924-542a-efb4a4795023-a9ad/?fullscreen](https://xd.adobe.com/view/df9c261d-fb6d-4924-542a-efb4a4795023-a9ad/?fullscreen)

## Anatomia

A tela de Itens da solicitação é construída por 5 elementos principais:

1. **Cabeçalho (Header)**
2. **Filtros favoritos (Accordion)**
3. **Filtros (Accordion)**
4. **Tabela de itens - Resultado do filtro (Datatable)**
5. **Rodapé (Footer)**
   1. **Informar previsão de entrega** (Sidebar)

![](<../../.gitbook/assets/Grupo 1813 (1).png>)

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual, e qual os dados do título que está sendo manipulado.

Os elementos que compõe o cabeçalho são:

![](<../../.gitbook/assets/Grupo 1813.png>)

**1. Botão Dúvidas? Acesse a wiki**\
Botão que direciona o usuário para a tela da wiki.

**2. Título da Tela (Itens da solicitação de compra)**\
****O título da tela deve ser o nome da operação principal da tela.

### 2. Filtros favoritos (Accordion)

O conteúdo é formado pelo accordion com seus respectivos campos favoritados.&#x20;

![](<../../.gitbook/assets/Grupo 1814.png>)

### 3. Filtros (Accordion)

No accordion Filtros,  está localizado os campos que o usuário pode utilizar para filtrar os itens que deseja. Apenas o campo Filial é de preenchimento obrigatório.

![](<../../.gitbook/assets/Grupo 1815.png>)

### 4. Tabela de itens (Datatable)

![](<../../.gitbook/assets/Grupo 1816.png>)

### 5. Footer

**Botões de ação da página:** São os botões de ação da página que permitem Alterar, Preencher NDO, Informar contrato, Gerar licitação, Gerar cotação, Informar previsão de entrega.&#x20;

![](<../../.gitbook/assets/Grupo 1817.png>)

### 5.1 Informar previsão de entrega (Sidebar)

**5.1.1** Título da sidebar deve conter a ação do botão que antecedeu a abertura do sidebar

**5.1.2** Os campos Filial, Solicitação, Item e quantidade são referentes à informações já cadastradas anteriormente. Já, os campos Nova data prevista e Nova quantidade se referem as novas informações válidas.

**5.1.3** Em Total, o campo é contabilizado e atualizado de acordo com os dados informados nos campos anteriores (Nova data prevista e Nova Quantidade).

**5.1.4** Correspondem aos botões de ação do sidebar.

![](<../../.gitbook/assets/Grupo 1820.png>)

