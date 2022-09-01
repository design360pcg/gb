---
description: Contas a pagar / cadastros / Vendedor
---

# Vendedor

## Objetivo da tela

O objetivo principal deste fluxo de telas é realizar a **cadastro** de um vendedor específico. Como objetivo secundário as telas permitem que o usuário realize **consulta**, **alteração**, **exclusão** e detalhamento do vendedor.

## Documentação

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/9cd1abab-55a1-4c3a-bd9d-18a26ede6cca-c982/](https://xd.adobe.com/view/9cd1abab-55a1-4c3a-bd9d-18a26ede6cca-c982/)

Vídeo: [https://www.loom.com/share/29a8b520437a4218830abbdb6886ec1b](https://www.loom.com/share/29a8b520437a4218830abbdb6886ec1b)

## Anatomia

A tela de Itens da solicitação é construída por 5 elementos principais:

1. **Cabeçalho (Header)**
2. **Filtros (Accordion)**
3. **Botão "Pesquisar" e "Limpar"**
4. **Tabela de itens - Resultado do filtro (Datatable)**
5. **Rodapé (Footer) Botões**
   1. Incluir **(Tela de Inclusão de Vendedor)**
   2. Alterar **(Tela de Alteração de Vendedor)**
   3. Detalhar **(Tela de Detalhes de Vendedor)**
   4. Excluir **(PopUp de confirmação da Exclusão de Vendedor)**

![](<../../../../.gitbook/assets/image (153).png>)

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual, e qual os dados do título que está sendo manipulado.

Os elementos que compõe o cabeçalho são:

![](<../../../../.gitbook/assets/image (76).png>)

**1. Título da Tela (Vendedores)**\
****O título da tela deve ser o nome da operação principal da tela.

### 2. Filtros (Accordion)

### **3**. Botões ''Pesquisar'' e ''Limpar''

No accordion Filtros,  está localizado os campos que o usuário pode utilizar para filtrar os itens que deseja ou que ele costuma usar para realizar o cadastro de novos vendedores. _Se atentar ao grid com três colunas_. Há também o botão de pesquisar e limpar.&#x20;

![](<../../../../.gitbook/assets/image (49).png>)

### 4. Tabela de itens (Datatable)

![](<../../../../.gitbook/assets/image (94).png>)

### 5. Footer

**Botões de ação da página:** São os botões de ação da página que permitem Incluir, Alterar, Detalhar e Excluir. &#x20;

![](<../../../../.gitbook/assets/image (197).png>)

### 5.1 Incluir (Tela de Inclusão de Vendedor)

**5.1.1** O Cabeçalho **(Header) **_**\[Item 1]**_:

* **Campo de Data**
* **Título da Tela (Inclusão de Vendedor)** O título da tela deve ser o nome da operação principal da tela.

**5.1.2** _**\[Item 2 - Dados Gerais]**_ Os campos de preenchimento se referem a novas informações válidas. No entanto o campo de **"Nome"** é **obrigatório**.&#x20;

**5.1.3** _**\[Item 3 - Associar Fornecedor]**_ Para ativar o _**dropdown Fornecedor o**_ usuário precisa informar de é um fornecedor.

**5.1.4** _**\[Item 4 - Revendedor]**_ Caso o usuário queira associar a um **Revendedor**, precisa informar sim ou não, caso informe sim, ativa os campos Cliente e o dropdown Subtipo de pedido de venda.

**5.1.5** _**\[Item 5 - Endereços e Informações de Contato]**_ Os campos de preenchimento se referem a novas informações válidas. No entanto o campo de **"Cep" e "Endereço"** "Cidade" "Bairro" "Estado" "Telefone" "Email" são **obrigatórios**.&#x20;

**5.1.6** _**\[Item 6 - Empresa]**_ Aqui o usuário pode adicionar uma empresa e fazer alterações e inclusão na tabela nos campos. _Escrever as colunas da seguinte forma, por extenso, sem abreviar a palavra:_  **"Empresa" " Supervisor" "Percentual de Ajuste de Preço da Comissão"  "Conceder Desconto até: (%) "Tipo de Vendedor" "Vendedor Ativo" "Conta Contábil"** A Abreviação foi feita no protótipo apenas para caber as palavras na tabela.

**5.1.7** _**\[Item 7 - Filiais]**_ Aqui o usuário pode adicionar uma empresa e fazer alterações e inclusão na tabela nos campos. _Escrever as colunas da seguinte forma, por extenso, sem abreviar a palavra:_  **"Empresa" " Comissão" "Percentual de Ajuste de Preço da Comissão"  "Conceder Desconto até: (%) "Conta Contábil"**&#x20;

**5.1.8 **_**\[Item 8]**_ O campo personalizado (Accordion) permite que o usuário utilize de outros campos para fazer o registro do novo vendedor. É um diferencial do 360, que oferta a oportunidade de moldar o cadastro com dados relevantes para a empresa em questão.

**5.1.9** Correspondem aos botões de ação de uma página de inclusão.

![](<../../../../.gitbook/assets/image (72).png>)

![](<../../../../.gitbook/assets/image (87).png>)

![](<../../../../.gitbook/assets/image (48).png>)

### Item 6 - Empresa

_**No item 6, o usuário pode adicionar uma empresa clicando nesse botão;**_

![](<../../../../.gitbook/assets/image (96).png>)

**Item 6.1 -** Ao adicionar empresa abre um sidebar.

**6.1.1** _**\[Item 2 - Título do Sidebar]**_ **(Adicionar Empresa)**&#x20;

**6.1.2** _**\[Item 2 - Empresa]**_ Nesse Accordion o usuário pode escolher a empresa, o supervisor, inserir o valor de comissão e o percentual de Ajuste de Preço de Comissão, além de escolher se o vendedor é interno ou terceirizado e se o vendedor está ativo ou não, também pode conceder desconto em porcentagem.

![](<../../../../.gitbook/assets/image (187).png>)

**6.1.3** _**\[Item 3 - Conta Contábil]**_ Aqui teremos uma Tableedit onde o usuário pode adicionar linha e fazer alterações na tabela.

![](<../../../../.gitbook/assets/image (235).png>)

**6.1.4** _**\[Item 4 - Base de Cálculo]**_ Através desse componente o usuário consegue realizar um cálculo utilizando variáveis.

**6.1.5** _**\[Item 5 - Botões de " + Nova Variável" " + Nova Operação" "Salvar Fórmula"]**_ Correspondem aos botões _**para incluir e salvar a fórmula ou realizar uma nova operação.**_

**6.1.6** _**\[Item 6 - Botões de ação]**_  Correspondem aos botões de ação.

![](<../../../../.gitbook/assets/image (25).png>)

![](<../../../../.gitbook/assets/image (55).png>)

### Item 7 - Filiais

_**No item 7, o usuário pode adicionar uma filial clicando nesse botão;**_

![](<../../../../.gitbook/assets/image (139).png>)

**Item **_**7**_**.1 -** Ao adicionar empresa abre um sidebar.

**7.1.1** _**\[Item 1 - Título do Sidebar]**_ **(Adicionar Filial)**&#x20;

**7.1.2** _**\[Item 2 - Filiais]**_ Nesse Accordion o usuário pode escolher a empresa, a filial, inserir o valor de comissão e o percentual de Ajuste de Preço de Comissão, também pode conceder desconto em porcentagem.



![](<../../../../.gitbook/assets/image (178).png>)

![](<../../../../.gitbook/assets/image (144).png>)

**7.1.3** _**\[Item 3 - Conta Contábil]**_ Aqui teremos uma Tableedit onde o usuário pode adicionar linha e fazer alterações na tabela.

**7.1.4** _**\[Item 4 - Base de Cálculo]**_ Através desse componente o usuário consegue realizar um cálculo utilizando variáveis.

**7.1.5** _**\[Item 5 - Botões de " + Nova Variável" " + Nova Operação" "Salvar Fórmula"]**_ Correspondem aos botões _**para incluir e salvar a fórmula ou realizar uma nova operação.**_

**7.1.6** _**\[Item 6 - Botões de ação]**_  Correspondem aos botões de ação.

### Alterar (Tela de Alteração de Vendedor) - Consiste em reaçizar alterações nos campos devidos e salvar

1.Header - Título da tela e Data

2\. Dados Gerais

3\. Associar a um fornecedor

4\. Revendedor

5\. Endereço e Informações de Contato

6\. Empresa

7\. Campos personalizados

**9 -**  Correspondem aos botões de ação de uma página de alteração.

![](<../../../../.gitbook/assets/image (183).png>)

![](<../../../../.gitbook/assets/image (232).png>)

### Detalhar (Tela de Detalhes de Vendedor)

**Por ser uma página de detalhamento, os campos ficam desabilitados e a única opção do usuário é visualizar as informações e voltar.**

![](<../../../../.gitbook/assets/image (111).png>)

![](<../../../../.gitbook/assets/image (6).png>)

### Excluir (PopUp de confirmação da Exclusão de Vendedor)

_**Item 1]**_ Texto de **"Tem certeza que deseja excluir vendedor?"**&#x20;

_**Item 2]**_ Correspondem aos botões de ação de um pop up de confirmação: **"Sim"** e **"Não"**.

![](<../../../../.gitbook/assets/image (193).png>)
