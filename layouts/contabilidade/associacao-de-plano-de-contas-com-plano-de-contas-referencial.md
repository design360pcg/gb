---
description: >-
  Nova atualização dia 11 de setembro de 2020.  Este fluxo de telas recebeu uma
  atualização dia 06 de agosto de 2020.
---

# Associação de Plano de Contas com Plano de Contas Referencial

## 🎯 Objetivo da tela

O objetivo da tela é consultar, incluir, detalhar, alterar, excluir e copiar Associações de plano de conta com plano de conta referencial. Bem como Ajustar Centro de Custo e Verificar Coerência.

## 📝 Documentação

**Documentação para Desenvolvimento (Zeplin)**\
[https://zpl.io/ademqpR](https://zpl.io/ademqpR)

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/b084b600-f780-4cf6-a131-a0e6d2c46c65-e5d7/](https://xd.adobe.com/view/b084b600-f780-4cf6-a131-a0e6d2c46c65-e5d7/)

**Atualização: Protótipo navegável (Adobe XD) (06 de agosto de 2020)**\
[https://xd.adobe.com/view/149327ea-bb08-4aa9-afa2-bcbeb333a7b7-41c0/](https://xd.adobe.com/view/149327ea-bb08-4aa9-afa2-bcbeb333a7b7-41c0/)

****[**Atualização**](https://procenge.gitbook.io/piramide-360/layouts/contabilidade/associacao-de-plano-de-contas-com-plano-de-contas-referencial#atualizacao-do-fluxo-11-09-2020)**: Protótipo navegável (Adobe XD) (11 de setembro de 2020)**\
[**https://xd.adobe.com/view/9dd161d9-29ed-41b6-9196-52805403151c-c882/**](https://xd.adobe.com/view/9dd161d9-29ed-41b6-9196-52805403151c-c882/)****

**Link da tela antiga do pirâmide:**\
[**https://www.loom.com/share/0e9a1971dd72435f92a50434997390c8**](https://www.loom.com/share/0e9a1971dd72435f92a50434997390c8)****

## 🖥️ Consulta

A tela de consulta de **Associação de Plano de Contas com Plano de Contas Referencial** é construída por 4 elementos principais:

1. **Título**\
   ****Associação de Plano de Contas com Plano de Contas Referencial
2. **Filtros (Accordion)**\
   ****Filtros para efetuar uma pesquisa.
3. **Usuários (DataTable)**\
   ****DataTable que exibe os usuários pesquisados pelos filtros inseridos.
4. **Botões de ação da tela**\
   **"**Incluir", "Alterar", "Detalhar", "Excluir", "Ativar/Inativar" e "Voltar".

![](<../../.gitbook/assets/image (772).png>)

## 🖥️ Inclusão

A tela de inclusão simplificada de **Associação de Plano de Contas com Plano de Contas Referencial** é construída por 5 elementos principais:

1. **Título**\
   ****Associação de Plano de Contas com Plano de Contas Referencial Simplificada
2. **Filtros Gerais (Accordion)**\
   ****Filtros gerais da associação.
3. **Filtros de Contas (Accordion)**\
   ****Filtros de Contas Contábeis e Filtros de Plano de Contas Referencial
4. **Tabelas de Contas (DataTables)**\
   DataTable de Conta Contábil e DataTable de Conta Referencial.
5. **Botões de ação da tela**\
   ****"Associar", "Desassociar" e "Voltar".

![](<../../.gitbook/assets/image (965).png>)

![](<../../.gitbook/assets/image (940).png>)

## 🖥 Copiar

A tela de cópia de **Associação de Plano de Contas com Plano de Contas Referencial** é construída por 4 elementos principais:

1. **Título**\
   ****Copiar Associação
2. **Campos informativos**\
   ****Campos informativos: Associação Origem
3. **Campos da operação**\
   ****Campos necessários para efetuar a operação
4. **Botões de ação da tela**\
   ****"Copiar" e "Voltar".

![](<../../.gitbook/assets/image (959).png>)

Ao clicar em **Copiar**, será exibido um popup de confirmação:

![](<../../.gitbook/assets/image (928).png>)

## 🖥 Verificar Consistência

A tela de verificação de consistência de **Associação de Plano de Contas com Plano de Contas Referencial** é construída por 6 elementos principais:

1. **Título**\
   ****Copiar Associação
2. **Campos informativos**\
   ****Campos informativos: Versão do Plano de Contas
3. **Campos Informativos**\
   ****Campos informativos: Plano de Contas Referencial
4. **Campos de Filtro**\
   ****Campos necessários para filtrar as inconsistências
5. **Conta Contábil (DataTable)**\
   Tabela com as contas contábeis com inconsistência
6. **Botões de ação da tela**\
   ****"Copiar" e "Voltar".

![](<../../.gitbook/assets/image (747).png>)

![](<../../.gitbook/assets/image (853).png>)

Ao clicar em uma **Conta Contábil**, um sidebar com os lançamentos com incoerência é exibido.

![](<../../.gitbook/assets/image (738).png>)

## Atualização do Fluxo (11/09/2020)

O fluxo sofreu alguns ajustes:\
\


1. **Alteração no título na tela de consulta**&#x20;

O código não permite um título muito extenso, devido a esse impedimento técnico, o título foi reformulado e adaptado.

![](<../../.gitbook/assets/image (18).png>)

**2.  Adição de um botão "Excluir as Associações das Contas Vencidas"**

![](<../../.gitbook/assets/image (231).png>)

![](<../../.gitbook/assets/image (149).png>)

Quando selecionar o botão, deve aparecer um popup de confirmação da ação de exclusão:

![](<../../.gitbook/assets/image (182).png>)

**3. Sidebar de Lançamentos**

* Houve alteração no título. O mesmo deixou de ser "**Lançamentos**" e passou a ser "**Visualizar Lançamentos**".
* Retirou-se todos os "checkbox" presentes na datatable.
* O botão tornou-se primário, portanto sua coloração deve ser azul.

![](<../../.gitbook/assets/image (176).png>)
