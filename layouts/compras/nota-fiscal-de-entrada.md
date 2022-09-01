# Nota Fiscal de Entrada

## 🎯 Objetivo da tela

O objetivo principal da tela é de incluir e configurar uma Nota Fiscal de Entrada.&#x20;

## 📝 Documentação

**Protótipo navegável (Adobe XD)**\
****[https://xd.adobe.com/view/a52aee43-e8e8-472f-85ac-daae2b9db396-f079/](https://xd.adobe.com/view/a52aee43-e8e8-472f-85ac-daae2b9db396-f079/)

**Tela original Pirâmide (Loom)**\
****[https://www.loom.com/sha](https://www.loom.com/share/bc843f9cf8774958b462c20612aab07c)[re/bc843f9cf8774958b462c20612aab07c](https://www.loom.com/share/bc843f9cf8774958b462c20612aab07c)\
[https://www.loom.com/share/33af7600ef9e41ceb3b6f4a58a9df99b](https://www.loom.com/share/33af7600ef9e41ceb3b6f4a58a9df99b)\
[https://www.loom.com/share/514185360dc745dead5f45e744c835db](https://www.loom.com/share/514185360dc745dead5f45e744c835db)

## 🖥️ Anatomia

O fluxo de Inclusão de Nota Fiscal de Entrada é composto por uma tela inicial e uma tela principal.

## Tela inicial Inclusão de Nota Fiscal de Entrada

Esta primeira tela é composta pelo cabeçalho "Inclusão de Nota Fiscal de Entrada" seguida por um único accordion chamado Dados da Nota Fiscal de Entrada. Neste accordion estão os campos com os principais dados da nota, alguns deles já são carregados pela AF. A tela possui os botões "Salvar e Avançar", que só pode ser selecionado caso todos os campos obrigatórios sejam preenchidos, e "Voltar".&#x20;

![](<../../.gitbook/assets/image (8).png>)

## Tela principal Inclusão de Nota Fiscal de Entrada

A tela principal é composta por 12 elementos:&#x20;

1. Cabeçalho
2. Dados da Nota Fiscal de Entrada (Accordion)
3. Geral (Accordion)
4. Impostos (Accordion)
5. Itens (Accordion)
6. Observação (Accordion)
7. Título (Accordion)
8. Transporte (Accordion)
9. Outras Despesas (Accordion)
10. Orçamento (Accordion)
11. Campos Personalizados (Accordion)
12. Botões de ação da tela

![](<../../.gitbook/assets/image (226).png>)

## 1. Cabeçalho

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual, e qual os dados do título que está sendo manipulado.

Os elementos que compõem o cabeçalho são:

**1. Título da Tela (Inclusão de Nota Fiscal de Entrada)**\
****O título da tela deve ser o nome da operação principal da tela.

**2. Voltar e Consultar a Wiki**

## **2**. Dados da Nota Fiscal de Entrada

Este primeiro accordion é um resumo das informações que foram preenchidas na tela inicial, só deverão aparecer os campos que foram preenchidos. O accordion poderá ser minimizado.&#x20;

![](<../../.gitbook/assets/image (151).png>)

## 3. Geral

O Accordion Geral apresenta os campos presentes na aba de mesmo nome do Pirâmide. Os campos serão habilitados ou desabilitados de acordo com as informações já existentes da NFE. O usuário poderá favoritar campos. O accordion foi subdividido em sessões, utilizando subtítulos para isso (Nota Fiscal Eletrônica, Volume e Totais). O accordion poderá ser minimizado e também ter sua posição reordenada de acordo com a preferência do usuário.&#x20;

![](<../../.gitbook/assets/image (233).png>)

## 4. Impostos

Este accordion possui duas tabelas, sendo a primeira uma Table Edit e a segunda uma Data Table. As tabelas vem precedidas dos seus títulos "Total dos Impostos Impressos na Nota" e "Totais dos Impostos Calculados". A primeira poderá ser editada, de acordo com as permissões do usuário, a segunda é apenas para visualização. O accordion poderá ser minimizado e também ter sua posição reordenada de acordo com a preferência do usuário.&#x20;

![](<../../.gitbook/assets/image (39).png>)



## 5. Itens

Este accordion é constituído por uma Table Edit e os botões: Adicionar Novo Item, Alterar, Detalhar e Excluir. Quando clicados, os três primeiros botões, é aberto um sidebar de Inclusão/Detalhamento/Alteração de Item. O accordion poderá ser minimizado e também ter sua posição reordenada de acordo com a preferência do usuário.&#x20;

![](<../../.gitbook/assets/image (56).png>)

## 5.1 Sidebar Itens

O Sidebar de Itens possui número, código e descrição do item, assim como setas para mudar o item em questão. Nele estão todas as configurações referentes aos itens. É composto por 8 accordions: Dados Gerais, Almoxarifado, Impostos, Séries, Configurações, Rateio do ISS por Município, Rateio OSI e Campos Personalizados.&#x20;

![](<../../.gitbook/assets/image (205).png>)

## 5.1.1 Dados Gerais - Sidebar

Neste primeiro accordion estão os dados gerais do item, os principais são exibidos no topo e os demais serão exibidos quando for selecionado o "Ver Mais Campos".&#x20;

![](<../../.gitbook/assets/image (219).png>)

## 5.1.2 Almoxarifado - Sidebar

Estão os dados relativos ao almoxarifado do item. Alguns já são carregados automaticamente.&#x20;

![](<../../.gitbook/assets/image (174).png>)

## 5.1.3 Impostos - Sidebar

Exibe uma Data Table com os impostos relativos ao item.&#x20;

![](<../../.gitbook/assets/image (981).png>)

## 5.1.4 Série - Sidebar

Exibe dois campos com o intervalo de séries e uma Data Table.&#x20;

![](<../../.gitbook/assets/image (620).png>)

## 5.1.5 Configurações - Sidebar

Exibe as configurações do item, sendo um campo, duas Table Edits e uma Data Table. Poderão ser adicionadas novas linhas nas Table Edits.&#x20;

![](<../../.gitbook/assets/image (1012).png>)

## 5.1.6 Rateio do ISS por Município - Sidebar

Em caso de não ser um produto, e sim um serviço, será habilitado este accordion. É composto por um dropdown, dois campos de texto e uma Table Edit.&#x20;

![](<../../.gitbook/assets/image (599).png>)

## 5.1.7 Rateio OSI - Sidebar

Accordion já criado pelo time previamente.&#x20;

![](<../../.gitbook/assets/image (564).png>)

## 5.1.8 Campos Personalizados - Sidebar

Possibilita ao usuário criar campos para adicionar informações que não são contempladas em nenhum dos accordions.&#x20;

![](<../../.gitbook/assets/image (1007).png>)

## 6. Observação

Exibe as observações da Nota Fiscal de Entrada. Possui duas Table Edits, nas quais podem ser adicionadas novas linhas com novas observações. Em caso de Devolução, os campos Observação e Complemento estarão preenchidos. O accordion poderá ser minimizado e também ter sua posição reordenada de acordo com a preferência do usuário.&#x20;

![](<../../.gitbook/assets/image (558).png>)

## 7. Título

Exibe as informações referentes ao título. Os campos são subdivididos nas categorias Dados Bancários, Juros, Multa e Desconto Financeiro. Houve uma troca na ordem dos campos em relação ao Pirâmide Desktop visando uma melhor usabilidade. O accordion poderá ser minimizado e também ter sua posição reordenada de acordo com a preferência do usuário.&#x20;

![](<../../.gitbook/assets/image (581).png>)

## 8. Transporte

Accordion com as informações relativas ao transporte, já foi previamente feito pela equipe. O accordion poderá ser minimizado e também ter sua posição reordenada de acordo com a preferência do usuário.&#x20;

![](<../../.gitbook/assets/image (997).png>)

## 9. Outras Despesas

O accordion possui uma Table Edit com outras despesas, podendo ser adicionada uma nova despesa pelo botão + Adicionar Nova Linha. Possui ainda um campo totalizador. O accordion poderá ser minimizado e também ter sua posição reordenada de acordo com a preferência do usuário.

![](<../../.gitbook/assets/image (562).png>)

## 10. Orçamento

Este accordion só é exibido caso o Modo Construtora esteja habilitado. Não é possível adicionar uma nova linha, mas é possível alterar os campos de Rateio Percentual e Rateio Quantidade. O accordion poderá ser minimizado e também ter sua posição reordenada de acordo com a preferência do usuário.

![](<../../.gitbook/assets/image (593).png>)

## 11. Campos Personalizados

![](<../../.gitbook/assets/image (1009).png>)

## 12. Botões de Ação da Tela

![](<../../.gitbook/assets/image (555).png>)

