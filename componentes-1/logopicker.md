# Logopicker

{% hint style="success" %}
Componente aguardando documentação.

* [x] Componente definido e documentado pelos designers
* [x] Componente criado no backlog dos arquitetos
* [x] Componente priorizado na "sprint" dos arquitetos
* [x] Componente desenvolvido
{% endhint %}

![](<../.gitbook/assets/image (399).png>)

{% tabs %}
{% tab title="HTML" %}
```markup
<div class="box-body-info">
  <app-logopicker 
    [limpar]='limparLogo'
    (limpar)='limparLogo = $event'
    [logo]="cliente.LOGOTIPO" 
    (novaLogo)="inserirLogo($event)"
    (nomeLogo)="inserirNomeLogo($event)"
    [operacao]="operacao" >
  </app-logopicker>
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

![Exemplo com a utilização do componente](<../.gitbook/assets/image (304).png>)

