# Criação de Componente

## Criação de componente

Essa documentação representa a interface e o funcionamento para a tela "Criação de Componentes", uma operação do Dashboard.

## Objetivo da tela <a href="#objetivo-da-tela" id="objetivo-da-tela"></a>

O objetivo desta tela é criar os componentes, a partir de consultas do pirâmide, para serem inseridos em cards nos dashboards.

## Documentação <a href="#documentacao" id="documentacao"></a>

**Documentação para Desenvolvimento (Zeplin):**\
****[https://zpl.io/2GR3kGE​](https://zpl.io/a3DOm8y)

**Protótipo navegável (Adobe XD):**\
****[https://xd.adobe.com/view/810549da-122d-487a-64d3-5b1bbd35dbe5-f734/](https://xd.adobe.com/view/810549da-122d-487a-64d3-5b1bbd35dbe5-f734/)

## Anatomia <a href="#anatomia" id="anatomia"></a>

A tela de Criação e Componentes é dividida em três partes:

![](<../../.gitbook/assets/image (405).png>)

1. **Modelo de Consulta**
2. **Configuração**
3. **Tipo de Visualização**

### 1. Modelo de Consulta <a href="#1-cabecalho-header" id="1-cabecalho-header"></a>

Esta etapa é onde o usuário informa o modelo de Consulta que deseja utilizar para puxar os dados que serão utilizados nos componentes.

Esta etapa é dividida em duas partes, sendo elas:

![](<../../.gitbook/assets/image (385).png>)

**1.1 Modelo de Consultas** \
Campo dropdown com a lista das consultas, sendo várias disponibilizadas por padrão. Aqui o usuário também pode editar uma consulta (se for uma consulta padrão, ela será duplicada, afim de manter a original intacta) e também pode adicionar uma nova consulta, inserindo uma query.

{% tabs %}
{% tab title="Adicionar Nova Consulta" %}
![](<../../.gitbook/assets/image (693).png>)
{% endtab %}

{% tab title="Adicionar Nova Consulta / Testar Query" %}
![](<../../.gitbook/assets/image (704).png>)
{% endtab %}
{% endtabs %}

**1.2 Dados** \
Neste bloco serão exibidos os dados da consulta selecionada. No caso as colunas da tabela resposta da query.

****

### 2. Configuração <a href="#2-conteudo-accordions" id="2-conteudo-accordions"></a>

A etapa de Configuração tem o objetivo de auxiliar o usuário na configuração do componente, e é composta por 2 blocos:

![](<../../.gitbook/assets/image (319).png>)

**2.1 Configuração**\
Área onde o usuário configura o componente arrastando os dados para os campos de configuração, que variam de acordo com o tipo de visualização.

**2.2 Filtros Dinâmicos**\
Aqui o usuário insere filtros dinâmicos onde, na visualização do componente, poderá mudar os valores dos filtros a qualquer momento.

{% tabs %}
{% tab title="Tipo do Filtro" %}
Seleção do tipo do filtro

![](<../../.gitbook/assets/image (321).png>)
{% endtab %}

{% tab title="Configuração" %}
Configurações do filtro. Varia de acordo com o tipo do filtro selecionado.

![](<../../.gitbook/assets/image (351).png>)
{% endtab %}
{% endtabs %}

### 3. Tipo de Visualização <a href="#3-rodape-footer" id="3-rodape-footer"></a>

Na etapa de Visualização, é onde o usuário configura como quer visualizar seu componente.

![](<../../.gitbook/assets/image (666).png>)

**3.1 Tipo de Visualização** \
Aqui o usuário seleciona o tipo de visualização para o seu componente, podendo ser Gráficos ou Indicadores.

**3.2 Visualização do Componente**\
Área onde o usuário visualiza o resultado final do componente.
