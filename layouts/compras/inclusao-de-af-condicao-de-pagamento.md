# Inclusão de AF / Condição de Pagamento

## Objetivo da tela

O objetivo desta tela é o usuário informar os **Títulos de Provisionamento** nas condições de pagamento do **Autorização de Fornecimento (AF)**.

## Documentação

**Documentação para Desenvolvimento (Zeplin)**\
[https://zpl.io/aNndXjZ](https://zpl.io/aNndXjZ)

**Protótipo navegável (Adobe XD)**\
[https://xd.adobe.com/view/25e56c14-ec66-48c6-4d9c-5fa3b7c81bef-53d4/?fullscreen](https://xd.adobe.com/view/25e56c14-ec66-48c6-4d9c-5fa3b7c81bef-53d4/?fullscreen)

## Anatomia

A tela de Itens da Cotação é construída por 3 elementos principais:

![](<../../.gitbook/assets/image (611).png>)

1. **Campos informativos**
2. **Títulos de Provisão (Table Edit)**
3. **Botões de ação da tela**

### 1. Campos informativos

São os campos que informam o valor total e o saldo restante a ser alocado.

![](<../../.gitbook/assets/image (579).png>)

### 2. Títulos de Provisão (Table Edit)

Um Table Edit onde o usuário preencherá com o vencimento e o valor dos Títulos de Provisão. A medida que os títulos são preenchidos, o campo informativo de Saldo é subtraído do valor do título até ser zerado.

{% tabs %}
{% tab title="Sem registros" %}
![](<../../.gitbook/assets/image (595).png>)
{% endtab %}

{% tab title="Um registro" %}
![](<../../.gitbook/assets/image (621).png>)
{% endtab %}

{% tab title="Dois registros" %}
![](<../../.gitbook/assets/image (576).png>)
{% endtab %}
{% endtabs %}

### 3. Botões de ação da tela

Os botões de ação da tela, neste caso "Salvar" e "Voltar".

![](<../../.gitbook/assets/image (607).png>)
