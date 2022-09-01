# Compensação

## Objetivo da tela

A tela tem o objetivo de executar as ações de "Compensar", "Consultar Compensações" e "Estornar Compensação".

## Documentação

**Documentação para Desenvolvimento (Zeplin)**\
[https://zpl.io/adGZLLl](https://zpl.io/adGZLLl)

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/c75d94af-8fb7-41e8-5b85-d2c0ae8fda4d-b16c/](https://xd.adobe.com/view/c75d94af-8fb7-41e8-5b85-d2c0ae8fda4d-b16c/)

## **Consulta**

A Compensação começa com a tela de consulta que é dividida da seguinte forma:

![](<../../../.gitbook/assets/image (391).png>)

1. **Filtros**
2. **Data Table com as movimentações**
3. **Botões de ação**

### 1. Filtros

São os filtros para a busca de movimentações.

![](<../../../.gitbook/assets/image (328).png>)

### 2. Data Table com as movimentações

Data Table onde serão exibidas os resultados da busca.

![](<../../../.gitbook/assets/image (366).png>)

### 3. Botões de ação

São os botões de ação da tela, neste caso: "Compensar", "Consultar Compensações" e "Voltar"

![](<../../../.gitbook/assets/image (329).png>)

## **Compensar**

Ao clicar no botão **"Compensar"** será exibido um modal, onde será informado o valor da movimentação e o valor já compensado. O usuário precisará preencher o valor que deseja compensar e a data de compensação (o campo já sugere a data atual)

![](<../../../.gitbook/assets/Screenshot\_1 (1).png>)

## **Estornar compensação**

Ao selecionar em uma compensação e clicar em **"Estornar compensação"**, o usuário é levado para a tela de estorno, cuja estrutura é descrita abaixo:

![](<../../../.gitbook/assets/image (274).png>)

1. **Campos informativos da movimentação**
2. **DataTable com as compensações**
3. **Campos totalizadores de valor**

### 1. Campos informativos da movimentação

São os campos informativos das movimentações.

![](<../../../.gitbook/assets/image (381).png>)

### 2. DataTable com as compensações

DataTable com as compensações da movimentação.

![](<../../../.gitbook/assets/image (401).png>)

### 3. Campos totalizadores de valor

Campos totalizadores de valor. Mostrando o **valor** ta movimentação, o **valor a ser estornado** (cumulativo de acordo com as compensações que são selecionadas na DataTable acima) e o **valor após estorno**.

![](<../../../.gitbook/assets/image (452).png>)

## **Consultar compensação**

Ao selecionar uma compensação e clicar no botão **"Consultar Compensações" o usuário** será levado para a tela de consulta da compensação, cuja estrutura é exibida abaixo: onde será informado o valor da movimentação, a data da movimentação e os dados bancários e logo em seguida terá um Data Table com as compensações já feitas. O usuário pode selecionar as compensações desejadas e estornar.

![](<../../../.gitbook/assets/image (343).png>)

1. **Campos informativos da movimentação**
2. **DataTable com as compensações**
3. **Campos totalizadores de valor**
