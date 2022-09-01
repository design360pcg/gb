# Substituição de Títulos a Receber

## Objetivo da tela

Substituir títulos por novos.

## Documentação

**Documentação para Desenvolvimento (Zeplin)**\
[https://zpl.io/259PGwn](https://zpl.io/259PGwn)

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/b492b89b-8c3d-4000-45c5-d13c200aebf6-c2a3/](https://xd.adobe.com/view/b492b89b-8c3d-4000-45c5-d13c200aebf6-c2a3/)

## Anatomia

A tela de Atualização Massiva de Títulos é construída por três elementos principais:

![](<../../../.gitbook/assets/image (572).png>)

1. **Cabeçalho (Header)**
2. **Títulos Originais (Accordion)**
3. **Títulos Substitutos (Accordion)**
4. **Dados do(s) Título(s) (Accordion)**
5. **Rodapé (Footer)**

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de informar o usuário sobre qual a tela atual e permitir que ele retorne para a tela anterior.

![](<../../../.gitbook/assets/image (636).png>)

**1.1 Título e botão "Voltar"**\
Área onde fica o título da página e o botão de retornar.

**1.2 Campos de Destaque**\
****Área dedicada aos campos de destaque na tela, neste caso a "Data de Emissão",

### 2. Títulos Originais (Accordion)

Accordion contendo o(s) título(s) originai(s).

![](<../../../.gitbook/assets/image (698).png>)

**2.1 Títulos Originais**\
DataTable com o(s) título(s) originai(s), que serão substituídos.

### 3. Títulos Substitutos (Accordion)

DataTable com o(s) título(s) substituto(s), que irão substituir o(s) originai(s).

![](<../../../.gitbook/assets/image (711).png>)

**3.1 Quantidade de títulos**\
Seleciona a quantidade de títulos que deseja substituir o(s) originai(s).

**3.2 Títulos substitutos**\
****DataTable com os títulos substitutos.

**3.3 Campos personalizados**\
****Botão para preencher os campos personalizados do título substituto selecionado.

### 4. Dados do(s) Título(s)

Accordion com os campos referente a dados do título. Que serão usados em todos os títulos gerados.

![](<../../../.gitbook/assets/image (650).png>)

**4.1 Campos informativos**\
Os primeiros campos do accordion são os campos não editáveis, ou seja, apenas informativos.

**4.2 Campos gerais do título**\
****São os campos gerais do título.

**4.3 Dados bancários**\
****Os campos referentes aos dados bancários do título.

### 5. Rodapé (Footer)

No rodapé da tela, existirá um campo informativo do tipo totalizador. Informando o valor líquido da soma dos títulos, e os botões de ação da tela.

![](<../../../.gitbook/assets/image (686).png>)

**5.1 Campo informativo totalizador**\
Um campo do tipo totalizador informando o valor líquido da soma dos títulos.

**5.2 Botões de ação**\
****Os botões de ação da tela, neste caso: "Substituir" e "Voltar".
