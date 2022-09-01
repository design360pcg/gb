---
description: >-
  Este fluxo prevê o cadastramento de departamento e associação dos
  departamentos à filiais.
---

# Departamento

## Objetivo da tela

O objetivo principal deste fluxo de telas é realizar a **cadastro de departamentos**. Como o objetivo secundário as telas permitem que o usuário realize **consulta**, **alteração**, **exclusão, associação com filiais** e **detalhamento** do departamento.

## Documentação

**Protótipo navegável (Adobe XD)**

****[https://xd.adobe.com/view/78efc292-5844-4e6b-9ba5-781314ff8722-2dbc/](https://xd.adobe.com/view/78efc292-5844-4e6b-9ba5-781314ff8722-2dbc/)

## Anatomia

A tela de Itens da solicitação é construída por 5 elementos principais:

1. **Cabeçalho (Header)**
2. **Filtros (Accordion)**
3. **Tabela de itens - Resultado do filtro (Datatable)**
4. **Rodapé (Footer)**
   1. Incluir **(Tela de Inclusão de Departamento)**
   2. Alterar **(Tela de Alteração de Departamento)**
   3. Detalhar **(Tela de Detalhes de Departamento)**
   4. [Associação de Departamento à Filial **(Fluxo de telas)**](https://app.gitbook.com/@procenge/s/piramide-360/layouts/financeiro/contas-a-pagar/cadastros/departamento/associacao-de-departamentos-a-filial)****
   5. Excluir **(PopUp de confirmação da Exclusão de Departamento)**

![](<../../../../../.gitbook/assets/image (951).png>)

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual, e qual os dados do título que está sendo manipulado.

Os elementos que compõe o cabeçalho são:

![](<../../../../../.gitbook/assets/image (900).png>)

**1. Botão "Dúvidas? Acesse a wiki"**\
Botão que direciona o usuário para a tela da wiki.

**2.Botão de "Voltar"**\
Botão que direciona o usuário para a tela anterior.

**2. Título da Tela (Departamentos)**\
****O título da tela deve ser o nome da operação principal da tela.

### 2. Filtros (Accordion)

No accordion **Filtros**,  está localizado os campos que o usuário pode utilizar para filtrar os itens que deseja ou que ele costuma usar para realizar o cadastro de **novos departamentos**. Na hora do cadastro há três dados que são interessantes priorizar: **Código**, **Sigla** e **Declaração**. Há também o botão de pesquisar e limpar.&#x20;

![](<../../../../../.gitbook/assets/image (895).png>)

### 3. Tabela de itens (Datatable)

![](<../../../../../.gitbook/assets/image (787).png>)

### 5. Footer

**Botões de ação da página:** São os botões de ação da página que permitem Incluir, Alterar, Detalhar e Excluir. &#x20;

![](<../../../../../.gitbook/assets/image (944).png>)

### 5.1 Incluir (Tela de Inclusão de Departamento)

**5.1.1** O Cabeçalho **(Header) **_**\[Item 1]**_:

* **Botão "Dúvidas? Acesse a wiki"** Botão que direciona o usuário para a tela da wiki.‌
* **Botão de "Voltar"** Botão que direciona o usuário para a tela anterior.‌
* **Título da Tela (Incluir Departamento)** O título da tela deve ser o nome da operação principal da tela.

**5.1.2** _**\[Item 2]**_**  Dados Gerais: **_****_ Os campos de preenchimento se referem a novas informações válidas. O usuário deve poder preencher A **sigla, descrição e código.** O campo personalizado (Accordion) permite que o usuário utilize de outros campos para fazer o registro do novo colaborador. É um diferencial do 360, que oferta a oportunidade de moldar o cadastro com dados relevantes para a empresa em questão.

**5.1.3** Correspondem aos botões de ação de uma página de inclusão.

**5.1.4 **_**\[Item 6]**_ O box para inserir data e código. O preenchimento da **Código** é realizado pelo usuário.&#x20;

![](<../../../../../.gitbook/assets/image (832).png>)

### 5.2 Alterar (Tela de Alteração de Departamento)

**5.2.1** O Cabeçalho **(Header) **_**\[Item 1]**_:

* **Botão "Dúvidas? Acesse a wiki"** Botão que direciona o usuário para a tela da wiki.‌
* **Botão de "Voltar"** Botão que direciona o usuário para a tela anterior.‌
* **Título da Tela (Alteração de Departamento)** O título da tela deve ser o nome da operação principal da tela.

**5.2.2** _**\[Item 2]**_ Os campos de preenchimento se referem a novas informações válidas.&#x20;

**5.2.3 **_**\[Item 3]**_ Correspondem aos botões de ação de uma página de **Alteração**.

**5.2.4 **_**\[Item 4]**_ O box contém a data e o código e não podem ser alterados.&#x20;

![](<../../../../../.gitbook/assets/image (892).png>)

**5.2.5** Quando o usuário clicar em "Salvar" deverá aparecer um PopUp de confirmação por ser uma ação sensível.&#x20;

![](<../../../../../.gitbook/assets/image (941).png>)

![](<../../../../../.gitbook/assets/image (735).png>)

**5.2.6.1** _**\[Item 1]**_ Texto de **"Tem certeza que deseja confirmar a alteração?"**&#x20;

**5.2.6.2 **_**\[Item 2]**_ Correspondem aos botões de ação de um popUp de confirmação: **"Sim"** e **"Não"**.

### 5.3 Detalhar (Tela de Detalhes do Departamento)

**5.3.1** O Cabeçalho **(Header) **_**\[Item 1]**_:

* **Botão "Dúvidas? Acesse a wiki"** Botão que direciona o usuário para a tela da wiki.‌
* **Botão de "Voltar"** Botão que direciona o usuário para a tela anterior.‌
* **Título da Tela (Detalhes do Departamento)** O título da tela deve ser o nome da operação principal da tela.

**5.3.2** _**\[Item 2]**_ Os campos de preenchimento se referem as informações já existentes e inalteráveis. &#x20;

**5.3.3 **_**\[Item 3]**_** ** Correspondem aos botões de ação de uma página de detalhamento.

**5.3.4  **_**\[Item 4]**_ Box com a data de cadastro e o código do departamento (ambos inalteráveis).

![](<../../../../../.gitbook/assets/image (858).png>)

### 5.4 [Associação de Departamento à Filial (Fluxo de telas)](https://app.gitbook.com/@procenge/s/piramide-360/\~/drafts/-MCIV5bNCnSelo6HMYF5/layouts/financeiro/contas-a-pagar/cadastros/departamento/associacao-de-departamentos-a-filial)

### 5.**5** Excluir (PopUp de confirmação da Exclusão de Departamento)

**5.5.1** _**\[Item 1]**_ Texto de **"Tem certeza que deseja excluir?"**&#x20;

**5.5.2 **_**\[Item 2]**_ Correspondem aos botões de ação de um pop up de confirmação: **"Sim"** e **"Não"**.

![](<../../../../../.gitbook/assets/image (909).png>)

