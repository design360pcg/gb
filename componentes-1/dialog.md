# Dialog

{% hint style="success" %}
Componente aguardando documentação.

* [x] Componente definido e documentado pelos designers
* [x] Componente criado no backlog dos arquitetos
* [x] Componente priorizado na "sprint" dos arquitetos
* [x] Componente desenvolvido
{% endhint %}

| nome Parâmetro | Input/Output | tipo    | descrição                             |
| -------------- | ------------ | ------- | ------------------------------------- |
| titulo         | **Input**    | string  |                                       |
| visivel        | **Input**    |         |                                       |
| modal          | **Input**    | boolean | tipo de visualização do fundo da tela |
| largura        | **Input**    | string  |                                       |
| larguraminima  | **Input**    | number  |                                       |
| altura         | **Input**    | string  |                                       |
| alturaminima   | **Input**    | number  |                                       |
| topo           | **Input**    | number  |                                       |
| responsivo     | **Input**    | boolean |                                       |
| carregando     | **Input**    | boolean |                                       |
| visivelChange  | **Output**   |         |                                       |

{% hint style="info" %}
&#x20;Modal = true deixa com o fundo acinzentado
{% endhint %}

{% tabs %}
{% tab title="exemplo" %}
![](../.gitbook/assets/Screenshot\_2.png)


{% endtab %}

{% tab title="html" %}
```markup
<procenge-dialog 
    titulo="tituloDialog"
    [(visivel)]="popupDialog"     
    [carregando]="carregandoDialog"
    [modal]="true">
    
    <!-- ... -->
    
</procenge-dialog> 
```
{% endtab %}

{% tab title="JS" %}
```javascript
tituloDialog: string = "Titulo do Dialog";
popupDialog: boolean = false;
carregandoDialog: boolean = false;
```
{% endtab %}

{% tab title="CSS" %}
```
```
{% endtab %}
{% endtabs %}

{% hint style="info" %}
&#x20;Modal = false deixa com o fundo transparente
{% endhint %}

{% tabs %}
{% tab title="exemplo" %}
![](../.gitbook/assets/Screenshot\_3.png)
{% endtab %}

{% tab title="html" %}
```markup
<procenge-dialog 
    titulo="tituloDialog"
    [(visivel)]="popupDialog"     
    [carregando]="carregandoDialog"
    [modal]="false">
    
    <!-- ... -->
    
</procenge-dialog> 
```
{% endtab %}

{% tab title="JS" %}
```javascript
tituloDialog: string = "Titulo do Dialog";
popupDialog: boolean = false;
carregandoDialog: boolean = false;
```
{% endtab %}

{% tab title="CSS" %}
```
```
{% endtab %}
{% endtabs %}
