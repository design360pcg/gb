---
description: >-
  O objetivo principal da tela é de detalhar um Borderô de Despesa já existente,
  sendo sua função apenas a visualização.
---

# Detalhamento de Borderô de Despesa

## Documentação

**Protótipo navegável (Adobe XD)**\
****[https://xd.adobe.com/view/66381431-185f-450e-943f-813b5291a348-336b/](https://xd.adobe.com/view/66381431-185f-450e-943f-813b5291a348-336b/)

**Tela original Pirâmide (Loom)**\
****[https://www.loom.com/share/d8cca5f201d54b7bbb6b1f819faf5ab4](https://www.loom.com/share/d8cca5f201d54b7bbb6b1f819faf5ab4)

## Anatomia

A tela de Itens da solicitação é construída por 7 elementos principais:

1. **Cabeçalho (Header)**
2. **Dados Gerais (Accordion)**
3. **NDOs do Borderô (DataTable)**&#x20;
4. **Detalhamento de Lançamentos da NDO (Accordion)**&#x20;
   1. DataTable Débite
   2. DataTable Crédite
5. **Observação**&#x20;
6. **Total (Campo totalizador)**
7. **Botão de Voltar**

![](<../../../.gitbook/assets/image (70).png>)

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual, e qual os dados do título que está sendo manipulado.

Os elementos que compõem o cabeçalho são:

**1. Voltar e Wiki**\
****Links de Voltar para a tela anterior e para consultar a Wiki

**2. Título da Tela (Detalhamento de Borderô de Despesa)**\
****O título da tela deve ser o nome da operação principal da tela.

**3. Data e Número do Borderô**\
****Data e **** Número do borderô que está sendo detalhado.&#x20;

![](<../../../.gitbook/assets/image (62).png>)

### 2. Dados Gerais (Accordion)

No Accordion Dados Gerais, estão os campos **Filial**, **Banco**, **Portador**, **Agência**, **Conta Corrente**, **Item de Fluxo de Caixa**, **Unidade de Origem e Data de Pagamento**. **** Nenhum dos itens é editável, todos são apenas para visualização.

![](<../../../.gitbook/assets/image (246).png>)

### 3. NDOs do Borderô (DataTable)

Esta tabela vem acompanhada pelo seu **título "NDOs do Borderô"**, não pode ser editada, mas cada linha possui um **Radio Button** que, **quando apertado, abre a o accordion de Detalhamento de Lançamentos**.

![](<../../../.gitbook/assets/image (142).png>)

### 4. Detalhamento de Lançamentos da NDO (Accordion)

O accordion de Detalhamento de Lançamentos da NDO **deverá ter seu título alterado de acordo com a linha selecionada** na tabela, seguindo o padrão "Detalhamento de lançamento da NDO: Nome do NDO". Ex.: "Detalhamento de Lançamentos da NDO: 0932 - Alugueis e arrendamentos".

O accordion posui ainda os itens Filial, Data, Versão, Documento, Tipo, Diferença e um Check Box de Expurgo RTT. Nenhum deles pode ser alterado ou selecionado, são apenas de visualização.

Ainda dentro do accordion, estão as tabelas "Debite" e "Credite", ambas com as colunas "Código de Lançamento, Conta, Valor, Unidades, Hierarquia, Histórico e Complemento. São **Data Tables**, apenas para visualização.

![](<../../../.gitbook/assets/image (116).png>)

### 5. Observação

Já fora do accordion, há um input de texto desabilitado com o título "Observações". Também não pode ser editado, apenas para visualização.

![](<../../../.gitbook/assets/image (81).png>)

### 6. Total (Campo Totalizador)

Totalizador com a soma de todas as NDOs.

![](<../../../.gitbook/assets/image (44).png>)

### 7. Voltar

Botão de voltar para a página anterior

![](<../../../.gitbook/assets/image (161).png>)





