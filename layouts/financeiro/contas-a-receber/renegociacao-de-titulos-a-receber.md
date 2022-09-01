# Renegociação de Títulos a Receber

## Objetivo da tela

Consultar e realizar Renegociações de títulos a receber e Títulos de Impostos.

## Documentação

**Documentação para Desenvolvimento (Zeplin)**\
[https://zpl.io/bApo69p](https://zpl.io/bApo69p)

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/39e9773e-78d2-496a-42e9-0f9da9e61a38-4fd8/](https://xd.adobe.com/view/39e9773e-78d2-496a-42e9-0f9da9e61a38-4fd8/)

## Consulta de Renegociação

O processo de Renegociação começa pela tela de consulta, onde é possível consultar renegociações e efetuar novas. Esta tela de consulta segue a estrutura abaixo:

![](<../../../.gitbook/assets/image (400).png>)

1. **Cabeçalho (Header)**
2. **Campos de Filtros e botões de ação**
3. **Resultado da pesquisa: Renegociações (DataTable)**
4. **Botões de ação da tela**

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de informar o usuário sobre qual a tela atual e permitir que ele retorne para a tela anterior.

![](<../../../.gitbook/assets/image (423).png>)

### 2. Campos de filtros e botões de ação

Campo para filtrar e pesquisar Renegociações.

![](<../../../.gitbook/assets/image (281).png>)

**2.1 Filial**\
**2.2 Título**\
**2.3 Data de vencimento atual**\
**2.4 Valor do título**

### 3. Resultado da pesquisa: Renegociações (DataTable)

DataTable com o resultado da pesquisa das renegociações.

![](<../../../.gitbook/assets/image (280).png>)

### 4. Botões de ação da tela

Os botões de ação da tela, neste caso "Nova renegociação", "Detalhar", "Excluir" e "Voltar".

![](<../../../.gitbook/assets/image (421).png>)

## Nova Renegociação

A inclusão de renegociação é dividida nos seguintes passos:

![](<../../../.gitbook/assets/image (346).png>)

1. **Cabeçalho (Header)**
2. **Dados da Renegociação**
3. **Etapas do processo (Accordions)**
4. **Botões de ação da tela**

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de informar o usuário sobre qual a tela atual e permitir que ele retorne para a tela anterior.

![](<../../../.gitbook/assets/image (359).png>)

### 2. Dados da Renegociação

Abaixo do cabeçalho vem os campos informativos sobre os dados da renegociação. No caso da inclusão, a maioria dos campos ainda não existem, como "Número de Processo", etc. Nesses casos esses campos não devem ser exibidos na inclusão.

![](<../../../.gitbook/assets/image (308).png>)

**São os campos:**\
1\. Número de Processo\
2\. Status\
3\. Data de Abertura\
4\. Data de Aprovação\
5\. Data de Encerramento\
6\. Data de Referência

### 3. Etapas do processo (Accordions)

O processo de inclusão de renegociação é dividida em processos, sendo eles detalhados abaixo:

{% tabs %}
{% tab title="Definir Abrangência" %}
Neste accordion é definido os filtros da pesquisa dos títulos que deseja selecionar como Títulos Originais.

![](<../../../.gitbook/assets/image (422).png>)
{% endtab %}

{% tab title="Títulos Originais" %}
Neste accordion é exibido o resultado (lista de títulos) da busca e o usuário seleciona um ou mais títulos para renegociar (títulos originais).

![](<../../../.gitbook/assets/image (420).png>)
{% endtab %}

{% tab title="Títulos Resultantes" %}
Neste accordion é selecionado a condição de pagamento ou a quantidade de parcelas (títulos) que serão gerados e logo abaixo são exibidos os títulos resultantes. É possível preencher os dados de recebimento.&#x20;

![](<../../../.gitbook/assets/image (307).png>)
{% endtab %}

{% tab title="Justificativa" %}
No último accordion é preenchido o motivo da renegociação e um complemento.

![](<../../../.gitbook/assets/image (377).png>)
{% endtab %}
{% endtabs %}

### 4. Botões de ação da tela

Os botões de ação da tela, neste caso "Salvar", "Salvar como template", "Detalhar",  "Excluir" e "Voltar".

![](<../../../.gitbook/assets/image (255).png>)
