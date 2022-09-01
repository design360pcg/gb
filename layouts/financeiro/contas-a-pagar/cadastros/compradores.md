---
description: >-
  A tela em questão foi produzida anteriormente e necessita de ajustes para o
  padrão estético pré-existente.
---

# Compradores

## Objetivo da tela

O objetivo principal deste fluxo de telas é realizar a **cadastro** de um comprador específico. Como objetivo secundário as telas permitem que o usuário realize **consulta**, **alteração**, **exclusão** e detalhamento do comprador.

## Documentação

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/e1d992dc-5529-453c-88c7-c475e7c77424-b48a/](https://xd.adobe.com/view/e1d992dc-5529-453c-88c7-c475e7c77424-b48a/)

## Anatomia

A tela de Itens da solicitação é construída por 5 elementos principais:

1. **Cabeçalho (Header)**
2. **Filtros (Accordion)**
3. **Tabela de itens - Resultado do filtro (Datatable)**
4. **Rodapé (Footer)**
   1. Incluir **(Tela de Inclusão de Comprador)**
   2. Alterar **(Tela de Alteração de Comprador)**
   3. Detalhar **(Tela de Detalhes de Comprador)**
   4. Excluir **(PopUp de confirmação da Exclusão de Comprador)**

![](<../../../../.gitbook/assets/image (931).png>)

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual, e qual os dados do título que está sendo manipulado.

Os elementos que compõe o cabeçalho são:

![](<../../../../.gitbook/assets/image (750).png>)

**1. Botão "Dúvidas? Acesse a wiki"**\
Botão que direciona o usuário para a tela da wiki.

**2.Botão de "Voltar"**\
Botão que direciona o usuário para a tela anterior.

**2. Título da Tela (Compradores)**\
****O título da tela deve ser o nome da operação principal da tela.

### 2. Filtros (Accordion)

No accordion Filtros,  está localizado os campos que o usuário pode utilizar para filtrar os itens que deseja ou que ele costuma usar para realizar o cadastro de novos compradores. _Se atentar ao grid com três colunas_. Há também o botão de pesquisar e limpar.&#x20;

![](<../../../../.gitbook/assets/image (766).png>)

### 3. Tabela de itens (Datatable)

![](<../../../../.gitbook/assets/image (974).png>)

### 5. Footer

**Botões de ação da página:** São os botões de ação da página que permitem Incluir, Alterar, Detalhar e Excluir. &#x20;

![](<../../../../.gitbook/assets/image (820).png>)

### 5.1 Incluir (Tela de Inclusão de Comprador)

**5.1.1** O Cabeçalho **(Header) **_**\[Item 1]**_:

* **Botão "Dúvidas? Acesse a wiki"** Botão que direciona o usuário para a tela da wiki.‌
* **Botão de "Voltar"** Botão que direciona o usuário para a tela anterior.‌
* **Título da Tela (Inclusão de Compradores)** O título da tela deve ser o nome da operação principal da tela.

**5.1.2** _**\[Item 2]**_ Os campos de preenchimento se referem a novas informações válidas. No entanto o campo de **"Código"** e **"Descrição"** são **obrigatórios**. O campo de **"Matrícula"** é um **dropdown** e o campo **"Empresa"** consiste em um **dropdown multivalorado**.&#x20;

**5.1.3 **_**\[Item 3]**_ O campo personalizado (Accordion) permite que o usuário utilize de outros campos para fazer o registro do novo comprador. É um diferencial do 360, que oferta a oportunidade de moldar o cadastro com dados relevantes para a empresa em questão.

**5.1.4** Correspondem aos botões de ação de uma página de inclusão.

![](<../../../../.gitbook/assets/image (768).png>)

### 5.2 Alterar (Tela de Alteração de Comprador)

**5.2.1** O Cabeçalho **(Header) **_**\[Item 1]**_:

* **Botão "Dúvidas? Acesse a wiki"** Botão que direciona o usuário para a tela da wiki.‌
* **Botão de "Voltar"** Botão que direciona o usuário para a tela anterior.‌
* **Título da Tela (Alteração de Comprador)** O título da tela deve ser o nome da operação principal da tela.

**5.2.2** _**\[Item 2]**_ Os campos de preenchimento se referem a novas informações válidas. No entanto o campo de **"Código"** consiste em informações já pré-existentes. O campo de **"Matrícula"** é um **dropdown** e o campo **"Empresa"** consiste em um **dropdown multivalorado**.&#x20;

**5.2.3 **_**\[Item 3]**_ O campo personalizado (Accordion) permite que o usuário utilize de outros campos para fazer a alteração no registro do comprador. _É um diferencial do 360 a oferta da oportunidade de moldar o cadastro com dados relevantes para a empresa em questão._

**5.2.4** Correspondem aos botões de ação de uma página de alteração.

![](<../../../../.gitbook/assets/image (866).png>)

### 5.3 Detalhar (Tela de Detalhes de Comprador)

**5.3.1** O Cabeçalho **(Header) **_**\[Item 1]**_:

* **Botão "Dúvidas? Acesse a wiki"** Botão que direciona o usuário para a tela da wiki.‌
* **Botão de "Voltar"** Botão que direciona o usuário para a tela anterior.‌
* **Título da Tela (Detalhes de Comprador)** O título da tela deve ser o nome da operação principal da tela.

**5.3.2** _**\[Item 2]**_ Os campos de preenchimento se referem a novas informações já existentes e inalteráveis. O campo **"Empresa"** consiste em um **dropdown multivalorado,** logo deverá mostrar as **opções selecionadas**.&#x20;

**5.3.3 **_**\[Item 3]**_ O campo personalizado (Accordion) mostrar as opções selecionadas anteriormente sobre o registro do novo comprador.&#x20;

**5.3.4** Correspondem aos botões de ação de uma página de detalhamento.

![](<../../../../.gitbook/assets/image (746).png>)

### 5.4 Excluir (PopUp de confirmação da Exclusão de Comprador)

**5.4.1** _**\[Item 1]**_ Texto de **"Tem certeza que deseja excluir?"**&#x20;

**5.4.2 **_**\[Item 2]**_ Correspondem aos botões de ação de um pop up de confirmação: **"Sim"** e **"Não"**.

![](<../../../../.gitbook/assets/image (909).png>)
