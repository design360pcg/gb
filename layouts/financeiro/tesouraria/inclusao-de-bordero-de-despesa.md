---
description: >-
  O objetivo principal da tela é de incluir um Borderô de Despesa, assim como
  incluir e configurar NDOs.
---

# Inclusão de Borderô de Despesa

## Documentação

**Protótipo navegável (Adobe XD)**\
****[https://xd.adobe.com/view/09d218a8-c0e3-426d-b8e9-674d920a87d8-5c81/ **** ](https://xd.adobe.com/view/09d218a8-c0e3-426d-b8e9-674d920a87d8-5c81/)****

**Tela original Pirâmide (Loom)**\
****[https://www.loom.com/share/874c7bc5ac81411284e89633d99](https://www.loom.com/share/874c7bc5ac81411284e89633d990ed67)[0ed67](https://www.loom.com/share/874c7bc5ac81411284e89633d990ed67)



## Anatomia

A tela de Itens da solicitação é construída por 7 elementos principais:

1. **Cabeçalho (Header)**
2. **Dados Gerais (Accordion)**
3. **Botão Adicionar NDO (Botão)**&#x20;
4. **Tabela NDOs (DataTable)**
5. **Observação (Accordion)**
6. **Total (Campo totalizador)**
7.  **Botões de ação da tela**

    1. Salvar&#x20;
    2. Cancelar&#x20;
    3. Voltar





![](<../../../.gitbook/assets/image (130).png>)

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual, e qual os dados do título que está sendo manipulado.

Os elementos que compõem o cabeçalho são:

**1. Título da Tela (Inclusão de Borderô de Despesa)**\
****O título da tela deve ser o nome da operação principal da tela.

**2. Data do Borderô**&#x20;

**3. Número do Borderô**\
****Número do borderô que está sendo criado, definido automaticamente.&#x20;

![](<../../../.gitbook/assets/image (112).png>)

### 2. Dados Gerais (Accordion)

No Accordion Dados Gerais, estão os campos **Filial, Banco** e **Item de Fluxo de Caixa**, que o usuário deve preencher para incluir o borderô. O accordion ainda possui os campos de **Portador**, **Agência**, **Conta Corrente** e **Unidade de Origem**, estes são preenchidos automaticamente de acordo com os preenchimento dos campos mencionados anteriormente. Por fim, há o campo **Data de Pagamento**, que pode ser editado, além dos botões de **Incluir** e **Limpar**.

![](<../../../.gitbook/assets/image (172).png>)

### 3. Botão Adicionar NDO (Botão)&#x20;

Antes da tabela, encontra-se o botão Adicionar NDO, que deverá abrir uma Sidebar.&#x20;

![](<../../../.gitbook/assets/image (68).png>)

### &#x20;        3.1 Adicionar NDO (Sidebar)

Quando clicado, o Botão de Adicionar NDO deverá abrir uma Sidebar, na qual serão inseridas as informações que aparecerão na tabela de NDOs. No primeiro Accordion, o usuário deverá informar o tipo de **NDO**; se deseja informar por **Valor** ou **Porcentagem**, o campo seguinte deverá ser com a opção selecionada (Valor ou Porcentagem); **Código de Pagamento**; **Banco**; **Agência** e **Conta Corrente**, que tem sua obrigatoriedade relacionada ao Código de Pagamento; **CPF/CNPJ do Favorecido**, que não é obrigatório; **Complemento**, obrigatório.&#x20;

A sidebar ainda possui um outro accordion, inicialmente minimizado, de **Configurações**, um **campo totalizador** com o valor da NDO e os botões de **Adicionar**; **Adicionar e Criar Novo**; e **Cancelar**. &#x20;

![](<../../../.gitbook/assets/image (213).png>)

### &#x20;        3.1.1 Configurações NDO (Sidebar)

Na mesma sidebar de Adicionar NDO,  o usuário pode maximizar o Accordion de Configurações. Nele está uma Datatable, precedida do título "**Selecione na tabela a linha que deseja configurar.**", a tabela possui **radiobuttons** para a seleção de linhas. Uma linha deverá ser selecionada para ser configurada. As informações **Unidade de Negócio**, **Valor/Porcentagem** (a depender do que o usuário escolheu informar), **Centro de Custo** e **Conta Auxiliar** já vem preenchidos automaticamente, de acordo com informações da NDO, mas podem ser editados. **Centro de Custo** e **Conta Auxiliar** são dropdowns, com a opção de pesquisa. Já **Complemento** é um dropdown multivalorado, no qual o usuário pode escolher uma ou mais variáveis de complemento, também possui o campo de busca. &#x20;



### 4. Tabela NDOs (DataTable)&#x20;

A Tabela de NDOs mostra as informações que foram incluídas pelo botão "Adicionar NDO".&#x20;

![](<../../../.gitbook/assets/image (210).png>)



### 5. Observação (Accordion)&#x20;

Este accordion possui apenas um input de texto para serem escritas as observações que o usuário desejar informar.&#x20;

![](<../../../.gitbook/assets/image (170).png>)

### 6. Total (Campo Totalizador)&#x20;

Exibe o valor total do Borderô, ou seja, a soma de todas as NDOs.&#x20;

![](<../../../.gitbook/assets/image (175).png>)

### 6. Botões de ação

![](<../../../.gitbook/assets/image (137).png>)



