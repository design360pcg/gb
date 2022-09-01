---
description: O objetivo dessa tela é criar grupos de usuário.
---

# Grupo de Usuário

## Documentação <a href="#documentacao" id="documentacao"></a>

**Link do vídeo da tela antiga no Pirâmide** [**https://www.loom.com/share/012dec7678214369865de718707ab36c**](https://www.loom.com/share/012dec7678214369865de718707ab36c)****

**Protótipo navegável (Adobe XD)**\
****[**https://xd.adobe.com/view/344f82c5-c8db-4065-9730-e5bba5c46b5e-611c/**](https://xd.adobe.com/view/344f82c5-c8db-4065-9730-e5bba5c46b5e-611c/)****

## Anatomia <a href="#anatomia" id="anatomia"></a>

A tela de consulta de Grupos de Usuário é construída por 5 elementos principais:

1. **Cabeçalho (Header)**
2. **Filtros**
3. **Datatable**
4. **Rodapé (Footer)**
   1. Incluir
   2. Alterar
   3. Detalhar
   4. Excluir

**​**

![](<../../../.gitbook/assets/image (117).png>)

### 1. Cabeçalho (Header) <a href="#1-cabecalho-header" id="1-cabecalho-header"></a>

O cabeçalho tem o objetivo de manter o usuário informado sobre a tela atual. Houve uma mudança de **"Perfil"** para **"Grupo de Usuário"**.&#x20;

Obs.: Em todas as páginas que tiver **Perfil**, deverá ser substituída por "**Grupo de Usuário**".&#x20;

![](<../../../.gitbook/assets/image (19).png>)



Os elementos que compõe o cabeçalho são:

**1. Botão "Dúvidas? Acesse a wiki"** Botão que direciona o usuário para a tela da wiki.

**2. Título da Tela (Grupo de Usuário)** O título da tela deve ser o nome da operação principal da tela.

### 2. **Filtros** <a href="#2-configuracao-da-acao-a-ser-realizada" id="2-configuracao-da-acao-a-ser-realizada"></a>

Os filtros estão localizados dentro de um accordion e consiste em dois campos: **Código** (Campo de Range) e **Grupo de Usuário** (Dropdown).&#x20;

_Obs.: O **TimeOut não é um filtro** pois não é considerado uma informação pela qual alguém realizaria uma pesquisa. É um dado genérico._&#x20;

![](<../../../.gitbook/assets/image (238).png>)

### 3. Tabela de Objetos (Datatable) <a href="#3-tabela-de-objetos-datatable" id="3-tabela-de-objetos-datatable"></a>

A tabela reúne três dados: **Código**, **Grupo de Usuário** e **TimeOut de Sessão**

![](<../../../.gitbook/assets/image (200).png>)

### 4. Footer <a href="#4-tabela-de-tipo-de-permissao-datatable" id="4-tabela-de-tipo-de-permissao-datatable"></a>

**Botões de ação da página:** São os botões de ação da página que permitem **Incluir, Alterar, Detalhar e Excluir**. _O botão Incluir é primário (ou seja, tem coloração azul)_

![](<../../../.gitbook/assets/image (155).png>)



## Tela de Incluir

A tela possui quatro campos: **Nome do Grupo de Usuário**, **TimeOut da Sessão**, **Modelo de Grupo de Usuário** que servirá de referência nas configurações desse novo Grupo e **Código**.&#x20;

O campo **Código** é um box que é **preenchido automaticamente** pelo sistema e **não permite** a edição do usuário.&#x20;

![](<../../../.gitbook/assets/image (185).png>)

**A tela de incluir é igual a tela de alterar e detalhar.** No entanto, em **Detalhar** todos os campos aparecem **desabilitados** para a edição dos dados e em **Alterar** o campo **Código** também aparece **desabilitado.**

&#x20;****&#x20;

![Tela de Alterar](<../../../.gitbook/assets/image (211).png>)

![Tela de Detalhar](<../../../.gitbook/assets/image (82).png>)

Para as ações de **Excluir** e **Alterar**, tem um **popUp de confirmação**, pois são ações sensíveis:

&#x20;

![Confirmação de Alteração](<../../../.gitbook/assets/image (157).png>)

![Confirmação de Exclusão](<../../../.gitbook/assets/image (58).png>)
