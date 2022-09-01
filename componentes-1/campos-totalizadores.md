# Campos totalizadores

{% hint style="success" %}
**Status: Componente aguardando desenvolvimento.**

* [x] Componente definido e documentado pelos designers
* [x] Componente criado no backlog dos arquitetos
* [x] Componente priorizado na "sprint" dos arquitetos
* [x] Componente desenvolvido
{% endhint %}

{% hint style="success" %}
O campo totalizador deve ser utilizado para informar dados referentes a valor e data.
{% endhint %}

## Componente

### Estados

#### Valor normal

![Cor - #0A5096](<../.gitbook/assets/image (323).png>)

#### Valor positivo

![Cor - #006737](<../.gitbook/assets/image (380).png>)

#### Valor negativo

![Cor - #973937](<../.gitbook/assets/image (333).png>)

#### Data

![Cor - #0A5096](<../.gitbook/assets/image (356).png>)

## Exemplo de uso

Para utilizar este componente o desenvolvedor deve utilizar esta construção. Passando as variáveis de valor.

{% tabs %}
{% tab title="exemplo" %}
![](../.gitbook/assets/total.png)
{% endtab %}

{% tab title="HTML" %}
```markup
<div class="row box-total">
  <div class="espacamentoValores">
    <h6>Valor Líquido</h6>
    <h3>
      <span class="label label-default" [ngStyle]="{'color':ValorLiquido >= 0 ? '#0a5096' : '#973937' }">
        {{ ValorLiquido | number:'1.2' }}
      </span>
    </h3>
  </div>

  <div class="espacamentoValores">
    <h6>Valor Devido</h6>
     <h3>
      <span class="label label-default" [ngStyle]="{'color':ValorLiquido >= 0 ? '#0a5096' : '#973937' }">
        {{ ValorDevido | number:'1.2' }}
      </span>
    </h3>
  </div>
</div>
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

{% hint style="info" %}
&#x20;Totalizador **com** moeda visível
{% endhint %}

{% tabs %}
{% tab title="Exemplo" %}
![](<../.gitbook/assets/image (297).png>)
{% endtab %}

{% tab title="HTML" %}
```markup
 <div class="row box-total">
  <div class="espacamentoValores">
    <h6>Valor Líquido</h6>
    <h3>
      <span class="label label-default" [ngStyle]="{'color':ValorLiquido >= 0 ? '#0a5096' : '#973937' }">
        {{ ValorLiquido | currency:'BRL': 'symbol' }}
      </span>
    </h3>
  </div>

  <div class="espacamentoValores">
    <h6>Valor Devido</h6>
     <h3>
      <span class="label label-default" [ngStyle]="{'color':ValorLiquido >= 0 ? '#0a5096' : '#973937' }">
        {{ ValorDevido | currency:'BRL': 'symbol' }}
      </span>
    </h3>
  </div>
</div>
 
 | number:'1.2'
```
{% endtab %}

{% tab title="JS" %}

{% endtab %}

{% tab title="CSS" %}

{% endtab %}
{% endtabs %}
