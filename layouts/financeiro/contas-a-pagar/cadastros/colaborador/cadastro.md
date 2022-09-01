# Cadastro

## Objetivo da tela

O objetivo principal deste fluxo de telas é realizar a **cadastro** de um colaborador específico. Como objetivo secundário as telas permitem que o usuário realize **consulta**, **alteração**, **exclusão** e **detalhamento** do colaborador.

## Documentação

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/5fa59b8e-2c5a-4d02-beac-2ad4c8dc351b-0af6/](https://xd.adobe.com/view/5fa59b8e-2c5a-4d02-beac-2ad4c8dc351b-0af6/)

## Anatomia

A tela de Itens da solicitação é construída por 5 elementos principais:

1. **Cabeçalho (Header)**
2. **Filtros (Accordion)**
3. **Tabela de itens - Resultado do filtro (Datatable)**
4. **Rodapé (Footer)**
   1. Incluir **(Tela de Inclusão de Colaborador)**
   2. Alterar **(Tela de Alteração de Colaborador)**
   3. Detalhar **(Tela de Detalhes de Colaborador)**
   4. Excluir **(PopUp de confirmação da Exclusão de Colaborador)**

![](<../../../../../.gitbook/assets/image (971).png>)

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual, e qual os dados do título que está sendo manipulado.

Os elementos que compõe o cabeçalho são:

![](<../../../../../.gitbook/assets/image (789).png>)

**1. Botão "Dúvidas? Acesse a wiki"**\
Botão que direciona o usuário para a tela da wiki.

**2.Botão de "Voltar"**\
Botão que direciona o usuário para a tela anterior.

**2. Título da Tela (Colaboradores)**\
****O título da tela deve ser o nome da operação principal da tela.

### 2. Filtros (Accordion)

No accordion **Filtros**,  está localizado os campos que o usuário pode utilizar para filtrar os itens que deseja ou que ele costuma usar para realizar o cadastro de novos colaboradores. Na hora do cadastro há três dados obrigatórios que é interessante priorizar: **Matrícula**, **Nome** e **Situação**. Há também o botão de pesquisar e limpar.&#x20;

![](<../../../../../.gitbook/assets/image (756).png>)

### 3. Tabela de itens (Datatable)

![](<../../../../../.gitbook/assets/image (828).png>)

### 5. Footer

**Botões de ação da página:** São os botões de ação da página que permitem Incluir, Alterar, Detalhar e Excluir. &#x20;

![](<../../../../../.gitbook/assets/image (820).png>)

### 5.1 Incluir (Tela de Inclusão de Colaborador)

**5.1.1** O Cabeçalho **(Header) **_**\[Item 1]**_:

* **Botão "Dúvidas? Acesse a wiki"** Botão que direciona o usuário para a tela da wiki.‌
* **Botão de "Voltar"** Botão que direciona o usuário para a tela anterior.‌
* **Título da Tela (Incluir Colaborador)** O título da tela deve ser o nome da operação principal da tela.

**5.1.2** _**\[Item 2]**_ Os campos de preenchimento se referem a novas informações válidas. No entanto o campo de **"Matrícula"**, **"Nome"** e **"Situação"** são **obrigatórios**. O campo **"Deparamento Sob Sua Responsabilidade"** consiste em um **dropdown multivalorado**. Fora os os campos obrigatórios, os demais campos são **filtros favoritos**.

**5.1.3 **_**\[Item 3]**_ Dados Bancários (Accordion) permite que o usuário utilize dos campos para fazer o registro dos dados bancários do colaborador.&#x20;

**5.1.4 **_**\[Item 4]**_ O campo personalizado (Accordion) permite que o usuário utilize de outros campos para fazer o registro do novo colaborador. É um diferencial do 360, que oferta a oportunidade de moldar o cadastro com dados relevantes para a empresa em questão.

**5.1.5** Correspondem aos botões de ação de uma página de inclusão.

**5.1.6 **_**\[Item 6]**_ O box para inserir data e código. O preenchimento da data é obrigatório.&#x20;

![](<../../../../../.gitbook/assets/image (878).png>)

### 5.2 Alterar (Tela de Alteração de Comprador)

**5.2.1** O Cabeçalho **(Header) **_**\[Item 1]**_:

* **Botão "Dúvidas? Acesse a wiki"** Botão que direciona o usuário para a tela da wiki.‌
* **Botão de "Voltar"** Botão que direciona o usuário para a tela anterior.‌
* **Título da Tela (Alteração de Colaborador)** O título da tela deve ser o nome da operação principal da tela.

**5.2.2** _**\[Item 2]**_ Os campos de preenchimento se referem a novas informações válidas. No entanto o campo de **"Matrícula"** não podem ser alterado**.** O campo **"Deparamento Sob Sua Responsabilidade"** consiste em um **dropdown multivalorado**. Fora os os campos obrigatórios, os demais campos são **filtros favoritos**. **Nesta tela aparece pela primeira vez no fluxo de telas o campo "Conta de Adiantamento" é um dropdown e aparecerá no detalhamento também.**&#x20;

**5.2.3 **_**\[Item 3]**_ Dados Bancários (Accordion) permite que o usuário utilize dos campos para fazer a alteração no registro dos dados bancários do colaborador.&#x20;

**5.2.4 **_**\[Item 4]**_ O campo personalizado (Accordion) permite que o usuário utilize de outros campos para fazer alteração no registro do novo colaborador. É um diferencial do 360, que oferta a oportunidade de moldar o cadastro com dados relevantes para a empresa em questão.

**5.2.5 **_**\[Item 5]**_ Correspondem aos botões de ação de uma página de inclusão.

**5.2.6 **_**\[Item 6]**_ O box contém a data e o código e não podem ser alterados.&#x20;

![](<../../../../../.gitbook/assets/image (819).png>)

**5.2.7** Quando o usuário clicar em "Salvar" deverá aparecer um PopUp de confirmação por ser uma ação sensível.&#x20;

![](<../../../../../.gitbook/assets/image (923).png>)

![](<../../../../../.gitbook/assets/image (735).png>)

**5.2.7.1** _**\[Item 1]**_ Texto de **"Tem certeza que deseja confirmar a alteração?"**&#x20;

**5.2.7.2 **_**\[Item 2]**_ Correspondem aos botões de ação de um popUp de confirmação: **"Sim"** e **"Não"**.

### 5.3 Detalhar (Tela de Detalhes de Colaborador)

**5.3.1** O Cabeçalho **(Header) **_**\[Item 1]**_:

* **Botão "Dúvidas? Acesse a wiki"** Botão que direciona o usuário para a tela da wiki.‌
* **Botão de "Voltar"** Botão que direciona o usuário para a tela anterior.‌
* **Título da Tela (Detalhes do Colaborado'r)** O título da tela deve ser o nome da operação principal da tela.

**5.3.2** _**\[Item 2]**_ Os campos de preenchimento se referem as informações já existentes e inalteráveis. O campo **"Departamento Sob Sua Responsabilidade"** consiste em um **dropdown multivalorado,** logo deverá mostrar as **opções selecionadas**.&#x20;

**5.3.3 **_**\[Item 3]**_  Dados Bancários(Accordion) mostra as informações registradas anteriormente sobre o novo colaborador.&#x20;

**5.3.4 **_**\[Item 4]**_ O campo personalizado (Accordion) mostrar as opções selecionadas anteriormente sobre o registro do novo colaborador.&#x20;

**5.3.5** Correspondem aos botões de ação de uma página de detalhamento.

**5.3.6  **_**\[Item 6]**_ Box com a data de cadastro e o código do colaborador (ambos inalteráveis).

![](<../../../../../.gitbook/assets/image (905).png>)

### 5.4 Excluir (PopUp de confirmação da Exclusão de Colaborador)

**5.4.1** _**\[Item 1]**_ Texto de **"Tem certeza que deseja excluir?"**&#x20;

**5.4.2 **_**\[Item 2]**_ Correspondem aos botões de ação de um pop up de confirmação: **"Sim"** e **"Não"**.

![](<../../../../../.gitbook/assets/image (909).png>)

