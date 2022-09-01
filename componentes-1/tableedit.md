# TableEdit

{% hint style="success" %}
Quando for necessária a **alteração de texto diretamente na tabela**. \
**Exemplo:** Cancelamento de Saldo, lançamento contábil.
{% endhint %}

{% tabs %}
{% tab title="Exemplo" %}
![](<../.gitbook/assets/tableedit (1).png>)
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
**Evitar** utilizar esse tipo de tabela se houver **muitos campos escondidos** a serem adicionados (nesse caso, usar o **datatable** de adicionar/alterar)
{% endhint %}

{% hint style="info" %}
Caso a Tableedit tenha mais de 12 campos (gerando dessa forma uma barra de rolagem grande) utilizar um datatable com Checkbox  que abra um sidebar com os campos detalhados.
{% endhint %}

{% hint style="info" %}
exemplo de utilização para exclusão do item da linha, com pesquisa e podendo adicionar mais registros para tabela
{% endhint %}

{% tabs %}
{% tab title="Exemplo" %}
![](<../.gitbook/assets/tableedit (1).png>)
{% endtab %}

{% tab title="Html" %}
```markup
<div class="row box-mg espacamentoTableEdit">
    <div class="col-lg-12">
        <procenge-tableedit
            id="te-exemplo"
            [colunas]="colunasExemplo"
            [(dados)]="dadosExemplo"
            (emitirDados)="emitirDadosExemplo($event)"
            (onchange)="onchangeExemplo($event)"
            (emitirDadoLinha)="dadoSelecionadoExemplo($event, true)" 
            labelAdicionar= "Adicionar Débito"
            [(dadosModificados)]="dadosModificadosExemplo"
            habilitarPesquisa="true"
            [codigoCadastro]="codigoCadastroExemplo">
        </procenge-tableedit>
    </div>
</div>  
```
{% endtab %}

{% tab title="JS" %}
```javascript
```
{% endtab %}

{% tab title="Css" %}
```css
```
{% endtab %}
{% endtabs %}

{% hint style="info" %}

{% endhint %}

{% tabs %}
{% tab title="Exemplo" %}

{% endtab %}

{% tab title="Html" %}
```markup
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

