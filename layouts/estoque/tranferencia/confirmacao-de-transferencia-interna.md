# Confirmação de Transferência Interna

## Objetivo da tela

O objetivo principal desta dela é de confirmar o recebimento de uma transferência interna, podendo ainda consultar transferências e excluir pendências. \


## Documentação

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/0084cfdf-d007-4f13-96ff-d0e950cf81c6-55d7/](https://xd.adobe.com/view/0084cfdf-d007-4f13-96ff-d0e950cf81c6-55d7/)

**Tela original Pirâmide (Loom)**\
****[ https://www.loom.com/share/90272799566047eaaaf855f296397d82](https://www.loom.com/share/90272799566047eaaaf855f296397d82)

## Anatomia

A tela de Itens da solicitação é construída por 6 elementos principais:\


1. **Cabeçalho (Header)**
2. **Dados da Transferência (Accordion)**
3. **Filtros (Accordion)**
4. **Tabela de Transferências - Resultado do filtro (Table Edit)**
5. **Tabela de Detalhes da Transferência (DataTable)**
6. **Botões de ação da tela**
   1. Confirmar recebimento **(PopUp de confirmação do recebimento)**
   2. Excluir Pendências **(PopUp de confirmação da exclusão de pendências)**
   3. Voltar&#x20;

![](<../../../.gitbook/assets/image (51).png>)

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual, e qual os dados do título que está sendo manipulado.

Os elementos que compõem o cabeçalho são:

**1. Título da Tela (Confirmação de Transferência Interna)**\
****O título da tela deve ser o nome da operação principal da tela.

### 2. Dados da Transferência (Accordion)

No Accordion Dados da Transferência,  estão os campos **Filial** e **Almoxarifado**, que o usuário pode utilizar para filtrar os itens que deseja. O item Almoxarifado é representado por um componente de **range**, se minimizado o usuário pode incluir qualquer nome/código de um almoxarifado, se expandido, o usuário pode definir qual o almoxarifado de origem e qual o almoxarifado de destino.&#x20;

![](<../../../.gitbook/assets/image (247).png>)

### 3. Filtros (Accordion)

No Accordion Filtros, estão os campos **Número de Cadastro**, **Produto** e D**ata de Cadastro**, os quais o usuário pode também utilizar para filtrar os itens que deseja, não sendo obrigatórios. A Data de Cadastro também é composta por um componente de range, onde o usuário pode colocar uma só data em sua versão minimizada ou uma data inicial e data final em sua versão expandida. Ainda apresenta os botões de **Pesquisar** e **Limpar**.

![](<../../../.gitbook/assets/image (162).png>)

### 4. Tabela de Transferência (Table Edit)

A Tabela de Transferências mostra o resultado obtido a partir da busca com os filtros apresentados anteriormente. Ela possui um checkbox para selecionar linhas e a coluna "Data de Confirmação" pode/deve ser editada e preenchida com uma data.&#x20;

![](<../../../.gitbook/assets/image (222).png>)

### 5. Tabela de Detalhes da Transferência (DataTable)

Ao selecionar uma das linhas da tabela de Transferência, será mostrado o seu detalhamento com algumas informações como produto, descrição de produto, lote, validade e quantidade transferida. A **tabela deverá vir acompanhada do título "Detalhes da Transferência"**, apresentado antes, como mostra o protótipo.

![](<../../../.gitbook/assets/image (108).png>)

### 6. Botões de ação da tela

![](<../../../.gitbook/assets/image (20).png>)

### 6.1 Confirmar recebimento (PopUp confirmação)

O botão de Confirmar Recebimento **só será habilitado quando o usuário preencher o campo "Data de Confirmação"** na Table Edit. Ao confirmar o recebimento, será aberto um **PopUp** com a mensagem "Confirmar o recebimento das transferências selecionadas?", e os botões de Sim e Não.

![](<../../../.gitbook/assets/image (209).png>)

### 6.2 Excluir Pendências (PopUp confirmação de exclusão)

O botão de Excluir Pendências **só será habilitado quando o usuário marcar um ou mais checkbox** na TableEdit. Ao excluir uma pendência, será aberto um **PopUp** com a mensagem "Tem certeza que deseja excluir as pendências selecionadas?", e os botões de Sim e Não.

![](<../../../.gitbook/assets/image (5).png>)

### 6.3 Voltar&#x20;

Voltar para a tela anterior.

****







