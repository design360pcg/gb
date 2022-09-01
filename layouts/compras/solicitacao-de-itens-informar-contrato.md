# Solicitação de itens / Informar contrato

## Objetivo da tela <a href="#objetivo-da-tela" id="objetivo-da-tela"></a>

O objetivo deste fluxo é associar itens à contratos por meio do botão de ação "Informar contratos"‌

## Documentação <a href="#documentacao" id="documentacao"></a>

**Documentação para Desenvolvimento (Zeplin)**‌

**Protótipo navegável (Adobe XD)** [https://xd.adobe.com/view/a6f152e5-93c8-432c-6b2c-ee197fd90d8b-d0c0/?fullscreen](https://xd.adobe.com/view/5d75dca3-442c-4ad6-6468-91a13620b1db-2b44/)​

## Anatomia <a href="#anatomia" id="anatomia"></a>

A tela de Itens da solicitação é construída por 5 elementos principais:‌

1. **Cabeçalho (Header)**
2. **Filtros favoritos (Accordion)**
3. **Filtros (Accordion)**
4. **Tabela de itens agrupados por situação - Resultado do filtro (Treetable)**
5. **Rodapé (Footer)**
   1. **Informar contrato** (Sidebar)

‌

![](https://gblobscdn.gitbook.com/assets%2F-Lo0oO5fx3VNCGaUHqnJ%2F-Ly0IAb7-E044\_i-ESSw%2F-Ly0IRc7bIhFXKWSpBp4%2FGrupo%201813.png?alt=media\&token=129b0184-6d4d-40bb-be13-6f11d0fb0468)

### 1. Cabeçalho (Header) <a href="#1-cabecalho-header" id="1-cabecalho-header"></a>

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual, e qual os dados do título que está sendo manipulado.‌

Os elementos que compõe o cabeçalho são:![](https://gblobscdn.gitbook.com/assets%2F-Lo0oO5fx3VNCGaUHqnJ%2F-Ly0KNq7Amf2UfP3EMws%2F-Ly0Kv76D\_7nNcoCGuwK%2FGrupo%201813.png?alt=media\&token=36515767-9202-4c8a-955f-6e82ddc88205)‌

**1. Botão Dúvidas? Acesse a wiki** Botão que direciona o usuário para a tela da wiki.‌

**2. Título da Tela (Itens da solicitação de compra)** O título da tela deve ser o nome da operação principal da tela.‌

### 2. Filtros favoritos (Accordion) <a href="#2-filtros-favoritos-accordion" id="2-filtros-favoritos-accordion"></a>

O conteúdo é formado pelo accordion com seus respectivos campos favoritados.![](https://gblobscdn.gitbook.com/assets%2F-Lo0oO5fx3VNCGaUHqnJ%2F-Ly0KNq7Amf2UfP3EMws%2F-Ly0Lln-c-PdWPPDvbok%2FGrupo%201814.png?alt=media\&token=f8c85ea3-3299-4a8d-9db4-4ec24b17bd37)‌

### 3. Filtros (Accordion) <a href="#3-filtros-accordion" id="3-filtros-accordion"></a>

No accordion Filtros, está localizado os campos que o usuário pode utilizar para filtrar os itens que deseja. Apenas o campo Filial é de preenchimento obrigatório.

![](https://gblobscdn.gitbook.com/assets%2F-Lo0oO5fx3VNCGaUHqnJ%2F-Ly0KNq7Amf2UfP3EMws%2F-Ly0Lln3sFrGb8NT1cny%2FGrupo%201815.png?alt=media\&token=1499fa74-6d4b-4e56-b6fe-c724d441cf8d)

### 4. Tabela de itens (Treetable) <a href="#4-tabela-de-itens-treetable" id="4-tabela-de-itens-treetable"></a>

{% hint style="info" %}
Os itens são agrupados por solicitação, dessa forma o **usuário poderá selecionar item por item ou todos os itens da solicitação.**
{% endhint %}

![](https://gblobscdn.gitbook.com/assets%2F-Lo0oO5fx3VNCGaUHqnJ%2F-M2ZebJxPoOaj60an1yJ%2F-M2Zr6346yahDL27b7xQ%2Fimage.png?alt=media\&token=94fa2172-8cb9-4b2c-9d97-b0fd1a046ffd)

### 5. Footer <a href="#5-footer" id="5-footer"></a>

**Botões de ação da página:** São estes botões que permitem Alterar, Preencher NDO, Informar contrato, Gerar licitação, Gerar cotação, Informar previsão de entrega.

![](https://gblobscdn.gitbook.com/assets%2F-Lo0oO5fx3VNCGaUHqnJ%2F-Ly0KNq7Amf2UfP3EMws%2F-Ly0ZT-SB3TbfokQeSu8%2FGrupo%201817.png?alt=media\&token=d9656b63-69ba-4c76-897c-58a758e0d397)

### 5.1 Informar previsão contrato (Sidebar) <a href="#5-1-informar-previsao-contrato-sidebar" id="5-1-informar-previsao-contrato-sidebar"></a>

{% hint style="info" %}
A funcionalidade "Informar contrato" tem como objetivo informar e associar itens ao contrato, um item poderá ser associado à apenas um contrato.‌
{% endhint %}

o sidebar é construído por 4 elementos principais, são eles:‌

1. **Cabeçalho (Header)**
2. **Navegação com paginação e solicitação correspondente**
3. **Itens correspondentes a solicitação (Accordion)**
4. **Botões de ação com possibilidade de salvar grupo de itens atual ou todos selecionados no filtro anterior.**

![](https://gblobscdn.gitbook.com/assets%2F-Lo0oO5fx3VNCGaUHqnJ%2F-M2ZebJxPoOaj60an1yJ%2F-M2Zrz7VMt6AikJN7S4g%2Fimage.png?alt=media\&token=41b7c609-15e3-41fb-8f73-d78feb1c169c)
