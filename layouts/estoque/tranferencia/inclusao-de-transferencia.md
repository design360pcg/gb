---
description: >-
  O objetivo principal da tela é de incluir uma transferência, seja ela interna
  ou externa.
---

# Inclusão de Transferência

## Documentação

**Protótipo navegável (Adobe XD)**\
****[https://xd.adobe.com/view/fca1e1c6-f528-4641-be61-850097ab766c-a9f2/](https://xd.adobe.com/view/fca1e1c6-f528-4641-be61-850097ab766c-a9f2/)

**Tela original Pirâmide (Loom)**\
****Transferência Interna: [https://www.loom.com/share/a8aa9f8478ae419c838027f4f6ff082d](https://www.loom.com/share/a8aa9f8478ae419c838027f4f6ff082d)\
Transferência Externa: [https://www.loom.com/share/fe1c8f9ef9734b7c92edd94c97ac7ed3](https://www.loom.com/share/fe1c8f9ef9734b7c92edd94c97ac7ed3)

## Anatomia

A tela de Itens da solicitação é construída por 9 elementos principais:

1. **Cabeçalho (Header)**
2. **Origem (Accordion)**
3. **Destino (Accordion)**
4. **Geral (Accordion)**
5. **Configurar Transferência (Título + Accordion + DataTable)**\
   ****1. Inclusão de Produto (Sidebar)&#x20;
6. **Transporte da Transferência (Accordion) \***
7. **Volume da Transferência (Accordion)**
8. **Observação (Accordion + 2 Table Edit)**
9.  **Botões de ação da tela**

    1. Salvar&#x20;
    2. Remessas
    3. Voltar



\*O Accordion Transporte da Transferência só aparece em caso de Transferência Externa.

![](<../../../.gitbook/assets/image (57).png>)

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual, e qual os dados do título que está sendo manipulado.

Os elementos que compõem o cabeçalho são:

**1. Título da Tela (Incluir Transferência)**\
****O título da tela deve ser o nome da operação principal da tela.

**2. Voltar e Consultar a Wiki**

**3. Número da Transferência**\
****Número transferência que está sendo criada, definido automaticamente.&#x20;

![](<../../../.gitbook/assets/image (171).png>)

### 2. Origem (Accordion)

No Accordion de Origem estão os dados referentes à origem da transferência, são eles: **Filial** e **Almoxarifado**. Ambos dropdowns com a possibilidade de pesquisa pelo código ou pela descrição.

![](<../../../.gitbook/assets/image (80).png>)

### 3. Destino (Accordion)

No Accordion de Destino estão os dados referentes ao destino da transferência, são eles: **Empresa**, **Filial** e **Almoxarifado**. São todos dropdowns com a possibilidade de pesquisa pelo código ou pela descrição. Quando a empresa de destino selecionada é a mesma que está fazendo o cadastro, o sistema automaticamente entende a transferência como sendo **Interna**, sendo assim, oculta o Accordion de Transporte. Quando é **Externa**, o accordion de Transporte é habilitado e no accordion Geral é exibido um checkbox já marcado e desabilitado de "Transferencia Externa".&#x20;

![](<../../../.gitbook/assets/image (14).png>)

### 4. Geral (Accordion)

Os dados gerais referentes à transferência são a **Data da Transferência**, **Moeda**, **Solicitante**, em caso de transferência Externa também são exibidos os campos **Data da Entrega**, **Tipo da Transferência** e um checkbox marcado e desabilitado de "Transferência Externa". Moeda, Solicitante e Tipo da Transferência são dropwdowns com a possibilidade de busca.&#x20;

![](<../../../.gitbook/assets/image (12).png>)

### 5. Configurar Transferência (Título + Accordion + DataTable)

O accordion de Itens da Transferência vem precedido pelo **título "Configurar Transferência"** que fica fora do accordion. Já no accordion intitulado **Itens da Transferência** está uma **DataTable** com as colunas Código do Produto, Descrição, Complemento, Unidade de Medida, Estoque Atual, Lote e Validade. Antes da tabela possuímos o botão "**+ Adicionar Produto**" que leva para um sidebar de inclusão de produto.&#x20;

![](<../../../.gitbook/assets/image (23).png>)

### &#x20;        5.1 Inclusão de Produto (Sidebar)

Quando clicado, o botão "+ Adicionar Produto" leva para uma sidebar com os campos **Produto**, **Unidade de Medida**, **Estoque Atual**, **Lote**, **Validade**, **Quantidade Disponível no Lote**, **Quantidade Transferida**, **Custo da Transferência** e **Complemento**. Destes campos, somente Produto (dropdown), Quantidade Transferida (input de número) e Complemento (input de texto) podem ser preenchidos. Os demais já vem carregados de acordo com o Produto selecionado. A sidebar possui ainda os botões de Salvar; Salvar e Criar Novo; Voltar.&#x20;

![](<../../../.gitbook/assets/image (154).png>)

### 6. Transporte da Transferência (Accordion)

Este accordion **só é exibido caso a transferência seja externa**. É subdividido em **Frete Interno**, com os campos Transportadora, Placa do Veículo, Condutor, Tipo de Carga, Tipo de Frete e Via; **Transportadora 1**, com os campos Tipo de Carga, Tipo de Frete e Via; e **Transportadora 2**, também com os campos Tipo de Carga, Tipo de Frete e Via.

![](<../../../.gitbook/assets/image (243).png>)

### 7. Volume da Transferência (Accordion)

Este accordion é o volume referente ao volume da transferência, possui os campos **Nome**, **Espécie**, **Quantidade**, **Peso Bruto** e **Peso Líquido**. Estes dois últimos são campos apenas de visualização, a informação é carregada automaticamente.

![](<../../../.gitbook/assets/image (4).png>)

### 8. Observação (Accordion)

Neste accordion são encontradas duas Table Edits, uma de observação e a outra com detalhes da observação. Essa segunda depende da seleção de uma linha da primeira tabela. As tabelas são de observações da transferência, algumas informações podem já vir carregadas e outras podem ser inseridas manualmente. As colunas da tabela de Detalhes da Observação variam de acordo com a coluna de "Tipo de Observação" da primeira tabela. As duas tabelas são acompanhadas pelo botão "+ Adicionar Nova Linha"

![](<../../../.gitbook/assets/image (11).png>)

### 9. Botões de Ação da Tela&#x20;

![](<../../../.gitbook/assets/image (207).png>)

Ao salvar, o usuário recebe uma mensagem de confirmação que pode variar dependendo se é **Transferência Interna** ou **Transferência Externa**.&#x20;

### &#x20;        9.1 Pop Up confirmação Transferência Interna

![](<../../../.gitbook/assets/image (43).png>)

No caso de Transferência Interna, o pop up confirmando a geração informa apenas que a transferência foi gerada e o seu **número**.

### &#x20;        9.2 Pop Up confirmação Transferência Externa

![](<../../../.gitbook/assets/image (195).png>)

![](<../../../.gitbook/assets/image (189).png>)

No caso de Transferência Externa, **a depender das permissões do usuário**, antes da confirmação é solicitado **informar o Cliente**. O usuário poderá escolher pesquisar o cliente por Descrição ou pelo CNPJ. Após confirmar, é exibido um outro Pop Up contendo informações da transferência, Pedido de Venda, Nota Fiscal de Saída e Autorização de Fornecimento.&#x20;



\*No link do protótipo é possível ver uma tela para Inclusão de Transferência Externa (Que foi usada como modelo nessa documentação) e também a tela de Inclusão de Transferência Interna, com alguns campos a menos que a anterior.&#x20;
