---
description: É para que se perceba que o campo está desabilitado.
---

# (new) Campos Informativos

{% hint style="success" %}
Componente aguardando documentação.

* [x] Componente definido e documentado pelos designers
* [x] Componente criado no backlog dos arquitetos
* [x] Componente priorizado na "sprint" dos arquitetos
* [x] Componente desenvolvido
{% endhint %}

### Componente

Componente de campos informativos com objetivo de exibir dados que não são editáveis.

![](<../../.gitbook/assets/image (432).png>)

### Exemplo de uso

![](<../../.gitbook/assets/image (303).png>)

{% hint style="info" %}
Só funcionará se o parâmetro **desabilitar** for igual á **true**
{% endhint %}

{% tabs %}
{% tab title="HTML" %}
```markup
<procenge-inputtext
    identificador="inputCodigo"
    nome="Input Exemplo"
    tamanho=50           
    [desabilitar]="operacao=='detalhar' || operacao=='alterar' || true">
</procenge-inputtext>
```
{% endtab %}

{% tab title="JS" %}
```
```
{% endtab %}

{% tab title="CSS" %}
```
```
{% endtab %}
{% endtabs %}

| Nome do componente             | Descrição | Utilização |
| ------------------------------ | --------- | ---------- |
| procenge-inputcpf              |           | sim        |
| procenge-inputcnpj             |           | sim        |
| procenge-inputtext             |           | sim        |
| procenge-inputcep              |           | sim        |
| procenge-inputemail            |           | sim        |
| procenge-inputpassword         |           | sim        |
| procenge-inputtextarea         |           | sim        |
| procenge-inputtextmask         |           | sim        |
| procenge-inputtextmaskconta    |           | sim        |
| procenge-inputnumber           |           | sim        |
| procenge-inputtextrange        |           | sim        |
| procenge-inputnumberrange      |           | sim        |
| procenge-calendar              |           | sim        |
| procenge-calendarrange         |           | sim        |
| procenge-dropdown              |           | sim        |
| procenge-dropdownmultivalorado |           | sim        |
| procenge-dropdownpaginado      |           | sim        |
| procenge-dropdownload          |           | sim        |
| procenge-dropdownrange         |           | sim        |
| procenge-dropdownrangepaginado |           | sim        |
