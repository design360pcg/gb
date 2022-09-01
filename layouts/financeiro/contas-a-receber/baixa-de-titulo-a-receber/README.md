---
description: >-
  Essa documentação representa a interface e o funcionamento para a tela "Baixa
  de Títulos a Receber", uma operação de recebimento de título.
---

# Baixa de Título a Receber

## Objetivo da tela

O objetivo desta tela é fazer a baixa dos títulos de forma intuitiva e rápida. Podendo selecionar o tipo de baixa (integral, parcial, etc), inserir o valor da baixa, conferir valor total e os cálculos de imposto e mora, além de poder configurar NDOs.

## Documentação

**Documentação para Desenvolvimento (Zeplin)**\
[https://zpl.io/2GR3kGE](https://zpl.io/2GR3kGE)

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/624a83df-b7c2-41c1-47fe-46f3e06a6c64-147b/?fullscreen](https://xd.adobe.com/view/624a83df-b7c2-41c1-47fe-46f3e06a6c64-147b/?fullscreen)

## Anatomia

A tela de Baixa de Títulos é construída por três elementos principais:

![](<../../../../.gitbook/assets/image (635).png>)

1. **Cabeçalho (Header)**
2. **Conteúdo (Accordions)**
3. **Rodapé (Footer)**

### 1. Cabeçalho (Header)

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual, e qual os dados do título que está sendo manipulado.

Os elementos que compõe o cabeçalho são:

![](<../../../../.gitbook/assets/image (690).png>)

**1. Botão Voltar**\
Botão que retorna o usuário para a tela anterior.

**2. Título da Tela (Baixa de Título a Receber)**\
****O título da tela deve ser o nome da operação principal da tela.

**3. Título a ser recebido (título da baixa)**\
Código do Título a ser recebido.

**4. Botões para navegação entre os títulos**\
Navega entre os títulos selecionados na tela de consulta.

**5. Dados em destaque (Data de Emissão e Data de Vencimento)**\
Campo utilizado para destacar informações de Data e Códigos. No caso da Baixa de Títulos a Receber, destacar os campos de data principais (Data de Emissão e Data de Vencimento)

**6. Dados sobre o Título a Receber**\
Todos os dados contidos no título a receber.

### 2. Conteúdo (Accordions)

O conteúdo é formado pelos accordions e seus respectivos campos de formulário.&#x20;

![](<../../../../.gitbook/assets/image (688).png>)

**1. Título Accordion**\
O título refere-se a categoria dos dados do formulário.

**2. DataTable Adicionar Recebimento**\
****DataTable que permite adição de dados, abrindo um sidebar com os dados pra a inclusão de Recebimentos.

**Sidebar Adicionar Recebimento**\
****Ao clicar em "+ Recebimentos" o sidebar será aberto com os campos da inclusão de recebimento.

![](<../../../../.gitbook/assets/image (665).png>)

**3. Outras accordions**\
Cada accordion é uma categoria da operação (Baixa de Título a Receber).

### 3. Rodapé (Footer)

No rodapé fica localizado os campos de valores que foram afetados pelos campos preenchidos anteriormente e os botões de ação da página.

![](<../../../../.gitbook/assets/image (648).png>)

**1. Campos de visualização**\
No componente de campos de visualização do rodapé fica localizado os campos de valores e outros que são influenciados pelos campos previamente preenchidos.

**2. Botões de ação da página**\
****São os botões de ação da página, geralmente "Salva", "Salvar e Criar Novo" e "Voltar".
