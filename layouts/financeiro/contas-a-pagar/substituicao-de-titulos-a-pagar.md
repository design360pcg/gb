# Substituição de títulos

## Objetivo da tela

A tela tem o objetivo de consultar e criar substituições de títulos e títulos de impostos.

## Documentação

**Documentação para Desenvolvimento (Zeplin)**\
[https://zpl.io/VO80448](https://zpl.io/VO80448)

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/2a37b198-18e5-4499-646e-d0209d2e7414-5c06/?fullscreen](https://xd.adobe.com/view/2a37b198-18e5-4499-646e-d0209d2e7414-5c06/?fullscreen)

## **Anatomia**

A tela de substituição de títulos a pagar é dividida da seguinte forma:

#### Consulta:

![Fazer download da imagem para visualização com melhor qualidade.](<../../../.gitbook/assets/image (267).png>)

1. Título da página;
2. Campos de filtro;
3. Datatable primária com resultado filtrado e selecionável;
4. Datatable selecionável com Títulos substituídos após seleção em datatable primária;
5. Datatable selecionável com Títulos substitutos após seleção em datatable primária;
6. Botões de ação "Nova substituição", "Detalhar", "Excluir" e "Voltar".

## **Nova Substituição**

{% tabs %}
{% tab title="Títulos a pagar" %}
### · **** Títulos a pagar - Consulta

Consulta para criação de nova substituição filtrada por Título.

![Fazer download da imagem para visualização com melhor qualidade.](<../../../.gitbook/assets/image (365).png>)

### · **** Substituição de título:

![Fazer download da imagem para visualização com melhor qualidade.](<../../../.gitbook/assets/image (263).png>)

1. Título da página com campos de Data e Data de referência
2. Accordion contendo dados sobre os títulos originais com totalizadores e Datatable exibindo títulos originais de forma selecionável
3. Accordion com dados de títulos de juros
4. Accordion de títulos substitutos, neste accordion é possível  definir quantidade e gerar títulos&#x20;
5. Accordion de configuração dos títulos substitutos
6. Botões de ação "Substituir" e "Voltar"
{% endtab %}

{% tab title="Títulos a pagar de Impostos" %}
### · **** Títulos a pagar de Impostos - Consulta

Consulta para criação de nova substituição filtrada por Título de imposto.

![Fazer download da imagem para visualização com melhor qualidade.](<../../../.gitbook/assets/image (348).png>)

1. Título da tela;
2. Campos de filtro para pesquisa;
3. Datatable com resultado da pesquisa selecionável;
4. Botões de ação "Substituir" e "Voltar"

### · **** Substituição de título de imposto:

![](<../../../.gitbook/assets/image (467).png>)

1. **Título da tela;**
2. **Navegação entre grupos de títulos do mesmo tipo de imposto;**
3. **Campos informativos gerais do agrupamento de títulos de imposto;**
4. **Campos de configurações de Dados bancários;**
5. **DataTable com títulos substitutos selecionáveis;**
6. **Totalizadores dinâmicos;**
7. **Botões de ação "Substituir" e "Voltar".**

**5. Títulos Substitutos**

O accordion de Títulos Substitutos é formado pela seguinte estrutura:

![](<../../../.gitbook/assets/image (463).png>)

1. **DataTable com títulos substitutos selecionáveis**
2. **DataTable com NDO do titulo selecionado.**

Ao selecionar um título, é exibido a(s) NDO(s) correspondente.

![](<../../../.gitbook/assets/image (461).png>)
{% endtab %}
{% endtabs %}





