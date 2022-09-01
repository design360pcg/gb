# RadioButton



{% hint style="success" %}
Componente aguardando documentação.

* [x] Componente definido e documentado pelos designers
* [x] Componente criado no backlog dos arquitetos
* [x] Componente priorizado na "sprint" dos arquitetos
* [x] Componente desenvolvido
{% endhint %}

![](<../.gitbook/assets/image (445).png>)

{% tabs %}
{% tab title="HTML" %}
```markup
 <div id="tipoPessoa" class="col-lg-4 col-md-6 col-sm-12 box-comp box-checkboxes-opts opts2 no-overflow">
   <procenge-radiobutton
     identificador="tipoPessoa"
     nome="Tipo de Fornecedor" 
     [(opcoes)]="listaTipoPessoa"
     [(selecaoInicial)]="fornecedor.PESSOA"
     (opcaoSelecionada)="fornecedor.PESSOA=$event; selecionarPessoa($event)"
     obrigatorio="true"
     [desabilitar]="operacao=='detalhar'||operacao=='alterar'">
    </procenge-radiobutton>
</div>
```
{% endtab %}

{% tab title="JS" %}
```javascript
```
{% endtab %}

{% tab title="CSS" %}
```css
```
{% endtab %}
{% endtabs %}

![exemplo de utilização do componente](<../.gitbook/assets/image (457).png>)
