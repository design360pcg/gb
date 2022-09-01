# Rastreamento de Renegociação de Títulos a Receber

## Objetivo da tela

O objetivo desta tela é visualizar os Títulos gerados a partir de Renegociação em uma visão comparativa ao Título Original.

## Documentação

**Documentação para Desenvolvimento (Zeplin)**\
[https://zpl.io/2p7Oxel](https://zpl.io/2p7Oxel)

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/40765caa-2223-4efe-5218-40f53c3a161e-3647/](https://xd.adobe.com/view/40765caa-2223-4efe-5218-40f53c3a161e-3647/)

## **Anatomia**

A tela de Rastreamento é composta por um Modal (Pop Up), onde seu conteúdo é divido em:

![](<../../../.gitbook/assets/image (364).png>)

1. **Componentes padrões do Modal (Pop Up)**
2. **Informações da Renegociação**
3. **Títulos Originais (DataTable)**
4. **Títulos Resultantes (DataTable)**
5. **Campos de Valor**

### 1. Componentes padrões do Modal (Pop Up)

O título e o botão fechar (X), são componentes padrões do Modal (Pop Up)

### 2. Informações da Renegociação

É um componente de visualização, com os dados informativos da Renegociação

![](<../../../.gitbook/assets/image (342).png>)

**1. Campo de Código**\
Informa o código do processo (Renegociação).

**2. Campo de Data**\
****Informa a data do processo (Renegociação).

**3. Campo de Status**\
Informa o status do processo (Renegociação).

### 3. Títulos Originais (DataTable)

Um DataTable (Grid) contendo os dados dos títulos originais da Renegociação.

![](<../../../.gitbook/assets/image (427).png>)

**1. Título**\
Título da tabela (Títulos Originais).

**2. DataTable (Grid)**\
****Tabela com as informações dos títulos originais.

**3. Botão Detalhar**\
Botão para abir a tela de detalhamento do Título selecionado.

**4. Botão Negociação anterior**\
Quando o Título Original de uma renegociação já tiver vindo de uma outra renegociação, o botão "Negociação anterior" é habilitado e o modal é preenchido pelos dados dessa negociação.

### 4. Títulos Resultantes

Um DataTable (Grid) contendo os dados dos títulos resultantes da Renegociação.

![](<../../../.gitbook/assets/image (435).png>)

**1. Título**\
Título da tabela (Títulos Resultantes).

**2. DataTable (Grid)**\
****Tabela com as informações dos títulos resultantes.

**3. Botão Detalhar**\
Botão para abir a tela de detalhamento do Título selecionado.

**4. Botão Negociação posterior**\
Quando o Título Resultante de uma negociação também foi negociado e gerou outros títulos o botão "Negociação posterior" é habilitado e o modal é preenchido pelos dados dessa negociação.

### 5. Campos de Valor

Campos do tipo totalizador.

![](<../../../.gitbook/assets/image (713).png>)

**1. Valor do Processo**\
Corresponde ao valor do processo de renegociação, considerando a multa e mora.

**2. Valor Final**\
****Corresponde ao valor final do processo de renegociação, ou seja, o total dos títulos a receber resultantes.
