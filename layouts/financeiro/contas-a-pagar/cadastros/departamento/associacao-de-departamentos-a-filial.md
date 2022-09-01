---
description: Fluxo de telas para associar departamentos à filial.
---

# Associação de Departamentos à Filial

## Objetivo da tela

O objetivo principal deste fluxo de telas é realizar a **associação** de uma filial aos departamentos já cadastrados. Como objetivo secundário as telas permitem que o usuário realize **consulta**, **alteração**, **exclusão** e **detalhamento** das associações.

## Documentação

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/3f8e4f34-1dd8-4350-a285-0b6009116d4b-6add/](https://xd.adobe.com/view/3f8e4f34-1dd8-4350-a285-0b6009116d4b-6add/)

## Anatomia

A tela de Itens da solicitação é construída por 5 elementos principais:

1. **Cabeçalho (Header)**
2. **Filtros (Accordion)**
3. **Tabela de itens - Resultado do filtro (Datatable)**
4. **Rodapé (Footer)**
   1. Associar **(Tela de Associar Departamentos à Filial)**
   2. Alterar **(Tela de Alterar Associação de Departamentos à Filial)**
   3. Detalhar **(Tela de Detalhar Associação de Departamentos à Filial)**
   4. Desvincular **(PopUp de confirmação da Exclusão de Associação)**

![](<../../../../../.gitbook/assets/image (92).png>)

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual, e qual os dados do título que está sendo manipulado.

Os elementos que compõe o cabeçalho são:

![](<../../../../../.gitbook/assets/image (785).png>)

**1. Botão "Dúvidas? Acesse a wiki"**\
Botão que direciona o usuário para a tela da wiki.

**2.Botão de "Voltar"**\
Botão que direciona o usuário para a tela anterior.

**2. Título da Tela (Departamentos Associados à Filiais)**\
****O título da tela deve ser o nome da operação principal da tela.

### 2. Filtros (Accordion)

No accordion **Filtros**,  está localizado os campos que o usuário pode utilizar para filtrar os itens que deseja: **Código**, **Filial** e **Descrição**. Há também o botão de pesquisar e limpar.&#x20;

![](<../../../../../.gitbook/assets/image (245).png>)

### 3. Tabela de itens (Datatable)

![](<../../../../../.gitbook/assets/image (943).png>)

### 4. Footer

**Botões de ação da página:** São os botões de ação da página que permitem Associar, Alterar, Detalhar e Desvincular. &#x20;

![](<../../../../../.gitbook/assets/image (913).png>)

### 4.1 Associar (Associar Departamentos à Filial)

**4.1.1** O Cabeçalho **(Header) **_**\[Item 1]**_:

* **Botão "Dúvidas? Acesse a wiki"** Botão que direciona o usuário para a tela da wiki.‌
* **Botão de "Voltar"** Botão que direciona o usuário para a tela anterior.‌
* **Título da Tela (Associar Departamentos à Filial)** O título da tela deve ser o nome da operação principal da tela.

**4.1.2** _**\[Item 2]**_ O dropdown para escolher a **Filial** que deseja fazer as associações.

**4.1.3 **_**\[Item 3]**_  A table edit vem como uma alternativa ao comportamento de realizar mais de uma associação de uma vez só. No entanto vale salientar que os campos **Departamento** e **Centro de Custo** são **autocomplete** (dropdown) e só deverá mostrar os departamentos que ainda não foram associados à filial.

Os demais campos a serem preenchidos são: **Prédio**, **Departamento Obrigatório** e **Status do Departamento**.

**4.1.4 **_**\[Item 4]**_ **** Correspondem aos botões de ação de uma página de inclusão.

![](<../../../../../.gitbook/assets/image (867).png>)

### 4.2 Alterar (Tela de Alterar Associação de Departamento à Filial)

**4.2.1** O Cabeçalho **(Header) **_**\[Item 1]**_:

* **Botão "Dúvidas? Acesse a wiki"** Botão que direciona o usuário para a tela da wiki.‌
* **Botão de "Voltar"** Botão que direciona o usuário para a tela anterior.‌
* **Título da Tela (Alterar Associação de Departamentos à Filial)** O título da tela deve ser o nome da operação principal da tela.

**4.2.2** _**\[Item 2]**_ O dropdown para escolher a **Filial** fica **desabilitado**.

**4.2.3 **_**\[Item 3]**_  A table edit vem com o campo de **Departamento** desabilitado.

**4.2.4 **_**\[Item 4]**_ **** Correspondem aos botões de ação de uma página de inclusão.

![](<../../../../../.gitbook/assets/image (924).png>)

**4.2.5** Quando o usuário clicar em "Salvar" deverá aparecer um PopUp de confirmação por ser uma ação sensível.&#x20;

![](<../../../../../.gitbook/assets/image (872).png>)

![](<../../../../../.gitbook/assets/image (907).png>)

**4.2.5.1** _**\[Item 1]**_ Texto de **"Tem certeza que deseja confirmar a alteração?"**&#x20;

**4.2.5.2 **_**\[Item 2]**_ Correspondem aos botões de ação de um popUp de confirmação: **"Sim"** e **"Não"**.

### 4.3 Detalhar (**Detalhar Associação de Departamentos à Filial**)

**4.3.1** O Cabeçalho **(Header) **_**\[Item 1]**_:

* **Botão "Dúvidas? Acesse a wiki"** Botão que direciona o usuário para a tela da wiki.‌
* **Botão de "Voltar"** Botão que direciona o usuário para a tela anterior.‌
* **Título da Tela (Detalhar Associação de Departamentos à Filial)** O título da tela deve ser o nome da operação principal da tela.

**4.2.2** _**\[Item 2]**_ O dropdown para escolher a **Filial** fica **desabilitado**.

**4.2.3 **_**\[Item 3]**_  A table edit vem com todos os campos desabilitados.

**4.2.4 **_**\[Item 4]**_ **** Correspondem aos botões de ação de uma página de inclusão.

![](<../../../../../.gitbook/assets/image (36).png>)

### 4.4 Excluir (PopUp de confirmação da Desvínculo de Associação)

**4.4.1** _**\[Item 1]**_ Texto de **"Tem certeza que deseja excluir associação?"**&#x20;

**4.4.2 **_**\[Item 2]**_ Correspondem aos botões de ação de um pop up de confirmação: **"Sim"** e **"Não"**.

![](<../../../../../.gitbook/assets/image (815).png>)

