# Rejeitar Títulos de Borderô Liquidados

## Objetivo da tela

A tela tem o objetivo de rejeitar/reabrir títulos no borderô.

## Documentação

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/ee6f6693-2246-4810-5751-24bf7d02a334-985e/](https://xd.adobe.com/view/9d570b4e-d3b0-4e4f-aceb-1788adaccd09-c804/screen/738335f5-9797-4fa0-926a-018daec62137)

## Anatomia

A tela de consulta de borderô é construída por 5 elementos principais:

1. _**\[Item 1]**_** Título**
2. _**\[Item 2]**_** Accordion de Filtros**\
   Apenas os campos "**Agência**" e "**Conta Corrente**" aparecem indisponíveis para o preenchimento. A partir das informações deste accordion os dados da **datatble **_**\[Item 3]**_ e do accordion **Títulos do Borderô Selecionado** _**\[Item 4]**_ serão disponibilizados.&#x20;
3. _**\[Item 3]**_** Datatable** com a relação de borderôs identificados a partir da pesquisa do accordion de Filtro.
4.  **\[Item 4] Accordion Títulos do Borderô Selecionado**&#x20;

    &#x20;As informações neste accordion dependem da seleção do borderô na **datatble **_**\[Item 3]**_&#x20;



![](<../../../.gitbook/assets/image (771).png>)

## Rejeitar Título (sidebar)

O sidebar de rejeição de título é construída por 3 elementos principais:

1. **Título: Rejeitar Títulos de Borderô Liquidados**&#x20;
2. **Campos de Preenchimento** \
   Os campos "Borderô" e "Título" estão indisponíveis para preenchimento. Os campos **"Filial"**, **"Centro de Custo"** e **"Conta Auxiliar"** são dropdown.&#x20;
3. **Botões de ação Reabrir Título e Limpar**

![](<../../../.gitbook/assets/image (849).png>)



## PopUp de Confirmação

Por ser uma ação sensível, o popup serve para certificar o usuário de sua escolha.

1. **Mensagem de confirmação de ação**
2. **Botões de ação Reabrir Título e Limpar**

![](<../../../.gitbook/assets/image (949).png>)
