# Dashboard 📊

## Dashboard

No Dashboard é possível o usuário fixar cards com diferentes componentes, a partir de uma lista de componentes previamente criados, apenas arrastando e soltando.

## Objetivo da tela <a href="#objetivo-da-tela" id="objetivo-da-tela"></a>

O objetivo do Dashboard é comportar os componentes (Gráficos, Indicadores, etc) que o usuário definir na tela.

## Documentação <a href="#documentacao" id="documentacao"></a>

**Documentação para Desenvolvimento (Zeplin):**\
****[https://zpl.io/2GR3kGE​](https://zpl.io/a3DOm8y)

**Protótipo navegável (Adobe XD):**\
****[https://xd.adobe.com/view/34151324-ff24-41c4-4ffa-3de4e0a05f23-4224/](https://xd.adobe.com/view/34151324-ff24-41c4-4ffa-3de4e0a05f23-4224/)

## Anatomia <a href="#anatomia" id="anatomia"></a>

A estrutura do Dashboard é dividida em 2 partes, sendo elas:

![](<../../.gitbook/assets/image (363).png>)

1. ****[**Área dos Cards**](./#1-cabecalho-header)****
2. ****[**Catálogo de Componentes**](./#2-conteudo-accordions)****

****

### 1. Área dos Cards <a href="#1-cabecalho-header" id="1-cabecalho-header"></a>

Esta é a área onde os cards serão alocados, arrastando e soltando da lista de cards.\
Esta área é dividida em um Grid dividido em 2 partes principais, sendo elas:

![](<../../.gitbook/assets/image (290).png>)

**1.1 Botão Adicionar Cards** \
Botão que permite abrir a lista de cards.

**1.2 Grid: Alocando Indicadores** \
Espaço do Grid dedicado a alocação dos indicadores (tipo de componente).

**1.3 Grid: Alocando Gráficos e outros Componentes**\
Espaço do Grid dedicado a alocação de gráficos e outros componentes de porte maior.

![](<../../.gitbook/assets/image (378).png>)

**1. Conteúdo** \
Conteúdo do componente

**2. Botões do componente** \
Botões para realizar diferentes ações

{% tabs %}
{% tab title="Filtrar" %}
![Botão para aplicar filtros dinâmicos no componente.](<../../.gitbook/assets/image (273).png>)

Ao ser clicado é exibido o modal de filtros dinâmicos.

![](<../../.gitbook/assets/image (294).png>)
{% endtab %}

{% tab title="Visualização" %}
![Botão para aplicar filtros dinâmicos no componente.](<../../.gitbook/assets/image (340).png>)

Ao ser clicado exibe as opções de visualização do componente, variando de acordo com o componente.

#### Gráfico

![](<../../.gitbook/assets/image (374).png>)

#### Indicador

![](<../../.gitbook/assets/image (371).png>)
{% endtab %}

{% tab title="Opções" %}
![Botão para exibir as opções do componente.](<../../.gitbook/assets/image (339).png>)

Ao ser clicado exibe as opções do componente.

![](<../../.gitbook/assets/image (390).png>)
{% endtab %}
{% endtabs %}

### 2. Catálogo de Componentes <a href="#2-conteudo-accordions" id="2-conteudo-accordions"></a>

A etapa de Configuração tem o objetivo de auxiliar o usuário na configuração do componente, e é composta por 2 blocos:

![](<../../.gitbook/assets/image (685).png>)

**2.1 Navegação em Abas**\
Possibilita navegar entre as opções: "Gráficos e Indicadores" e "Outros".

{% tabs %}
{% tab title="Gráficos e Indicadores" %}
Nesta aba são listados os componentes do tipo **"Gráfico"** e **"Indicador"**.
{% endtab %}

{% tab title="Outros" %}
Nesta aba são listado os **outros componentes**, que não são do tipo Gráfico ou Indicador.
{% endtab %}
{% endtabs %}

**2.2 Lista de Componentes**\
Área onde os componentes são listados, mudam de acordo com a aba selecionada.

**2.3 Botão de Criação de Componentes**\
Botão que chama a tela de Criação de Componentes.
