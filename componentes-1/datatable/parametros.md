---
description: Exemplificação do uso dos parâmetros do componente Datatable
---

# Parâmetros e Exemplos

{% hint style="info" %}
Campo de Consulta Geral acima do Datatable

**\[campoConsultaGeral]="true"**
{% endhint %}

{% tabs %}
{% tab title="Exemplo" %}
![](../../.gitbook/assets/consultaGeralDatatable.png)
{% endtab %}

{% tab title="HTML" %}
```markup
<div class="row">
    <div  class="col-lg-12">
        <procenge-datatable 
            id="dt-descricaoUnica"
            [colunas]="colunas"
            [dados]="dados"
            [tipo]="'consultar'"
            [desabilitar]="tipoOperacao == 'detalharitem'"
            (valor)="dadosSelecionadosContratoTerc=$event"
            (limpar)="limpar()"
            [(dadosSelecionados)]="dadosSelecionadosContratoTerc"
            esconderBotoesPesquisa="true"
            [campoConsultaGeral]="true"
            [codigoCadastro]="codigoParaTabela">
        </procenge-datatable>
    </div>
</div>
```
{% endtab %}

{% tab title="JS" %}
```javascript
import { Cadastro } from './../../../shared/sistema/enum/cadastro';

// Exemplo de codigoParaTabela, 
// os codigos tem que estarem cadastrados nesse arquivo de cadastro
codigoParaTabela: string = Cadastro.CADASTRO_DE_TITULOS_A_RECEBER;

// exemplos de declaração
colunas: any[] = [];
dados: any[] = [];
dadosSelecionados: any[] = [];

// exemplo de como setar dados na lista
this.colunas = [
  { header: 'TITULO_NDO', field: 'titulo', tamanho: 100 },   
  { header: 'NDO', field: 'ndo', tamanho: 150 }
];

 dados.push({
  'ndo':ndo.NDO,          
  'titulo':titulo.TITULO_NDO
});
```
{% endtab %}

{% tab title="CSS" %}
```
// não necessario
```
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Selecionar apenas 1 opção

**`[mostraRadioButton]="true"`**
{% endhint %}

{% tabs %}
{% tab title="Exemplo" %}
![](../../.gitbook/assets/radioButtonDatatable.png)
{% endtab %}

{% tab title="HTML" %}
```markup
<div class="row">
    <div class="col-lg-12">
        <procenge-datatable 
            id="dt-descricaoUnica"
            [colunas]="colunas"
            [dados]="dados"
            [tipo]="'consultar'"  
            (valor)="dadosSelecionados=($event)"
            [(dadosSelecionados)]="dadosSelecionados"
            [campoConsultaGeral]="true"
            [mostraRadioButton]="true"
            [codigoCadastro]="codigoParaTabela">
        </procenge-datatable>
    </div>
</div>
```
{% endtab %}

{% tab title="JS" %}
```javascript
import { Cadastro } from './../../../shared/sistema/enum/cadastro';

// Exemplo de codigoParaTabela, 
// os codigos tem que estarem cadastrados nesse arquivo de cadastro
codigoParaTabela: string = Cadastro.CADASTRO_DE_TITULOS_A_RECEBER;

// exemplos de declaração
colunas: any[] = [];
dados: any[] = [];
dadosSelecionados: any[] = [];

// exemplo de como setar dados na lista
this.colunas = [
  { header: 'TITULO_NDO', field: 'titulo', tamanho: 100 },   
  { header: 'NDO', field: 'ndo', tamanho: 150 }
];

 dados.push({
  'ndo':ndo.NDO,          
  'titulo':titulo.TITULO_NDO
});
```
{% endtab %}

{% tab title="CSS" %}
```
```
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Desabilitar botão de pesquisa, e habilita-lo dependendo da regra de negocio

**\[desabilitarBotãoPesquisa]="desabilitarBotãoPesquisa"**
{% endhint %}

{% tabs %}
{% tab title="Exemplo" %}
![](../../.gitbook/assets/Screenshot\_1.png)
{% endtab %}

{% tab title="HTML" %}
```markup
<div class="row">
  <div class="col-lg-12">
      <procenge-datatable
        id="dt-descricaoUnica"
        [colunas]="colunas"
        [dados]="dados"
        [(dadosSelecionados)]="dadosSelecionados"
        (valor)="dadosSelecionados=$event;"
        (pesquisar)="pesquisar($event)"
        [desabilitarBotaoPesquisa]="desabilitarBotaoPesquisa"
        (limpar)="limpar()" 
        (cliquelinha)="cliqueLinha($event)"
        [codigoCadastro]="codigoParaTabela">
      </procenge-datatable>
  </div>
</div>
```
{% endtab %}

{% tab title="JS" %}
```javascript
 import { Cadastro } from './../../../shared/sistema/enum/cadastro';

// Exemplo de codigoParaTabela, 
// os codigos tem que estarem cadastrados nesse arquivo de cadastro
codigoParaTabela: string = Cadastro.CADASTRO_DE_TITULOS_A_RECEBER;

// exemplos de declaração
colunas: any[] = [];
dados: any[] = [];
dadosSelecionados: any[] = [];

// exemplo de como setar dados na lista
this.colunas = [
  { header: 'TITULO_NDO', field: 'titulo', tamanho: 100 },   
  { header: 'NDO', field: 'ndo', tamanho: 150 }
];

 dados.push({
  'ndo':ndo.NDO,          
  'titulo':titulo.TITULO_NDO
});

 // inicia o botão desabilitado
 desabilitarBotaoPesquisa: boolean =true;
 
 // muda para botão habilitado
 this.desabilitarBotaoPesquisa=false;
```
{% endtab %}

{% tab title="CSS" %}
```css
```
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Tabela **mostrando** o totalizador
{% endhint %}

{% tabs %}
{% tab title="Exemplo" %}
![](../../.gitbook/assets/COM\_TOTALIZADOR.png)
{% endtab %}

{% tab title="HTML" %}
```markup
<div class="row">
  <div class="col-lg-12">
      <procenge-datatable
        id="dt-descricaoUnica"
        [colunas]="colunas"
        [dados]="dados"
        [(dadosSelecionados)]="dadosSelecionados"
        (valor)="dadosSelecionados=$event;"
        (pesquisar)="pesquisar($event)" 
        (limpar)="limpar()"  
        [codigoCadastro]="codigoParaTabela">
      </procenge-datatable>
  </div>
</div>
```
{% endtab %}

{% tab title="JS" %}
```javascript
import { Cadastro } from './../../../shared/sistema/enum/cadastro';

// Exemplo de codigoParaTabela, 
// os codigos tem que estarem cadastrados nesse arquivo de cadastro
codigoParaTabela: string = Cadastro.CADASTRO_DE_TITULOS_A_RECEBER;

// exemplos de declaração
colunas: any[] = [];
dados: any[] = [];
dadosSelecionados: any[] = [];

// exemplo de como setar dados na lista
this.colunas = [
  { header: 'TITULO_NDO', field: 'titulo', tamanho: 100 },   
  { header: 'NDO', field: 'ndo', tamanho: 150 }
];

 dados.push({
  'ndo':ndo.NDO,          
  'titulo':titulo.TITULO_NDO
});
```
{% endtab %}

{% tab title="CSS" %}

{% endtab %}
{% endtabs %}

{% hint style="info" %}
Tabela **sem mostrar** o totalizador

**\[mostrarTotalizador]="false"**
{% endhint %}

{% tabs %}
{% tab title="Exemplo" %}
![](../../.gitbook/assets/SEM\_TOTALIZADOR.png)
{% endtab %}

{% tab title="HTML" %}
```markup
<div class="row">
  <div class="col-lg-12">
      <procenge-datatable
        id="dt-descricaoUnica"
        [colunas]="colunas"
        [dados]="dados" 
        (valor)="dadosSelecionados=$event;"
        (pesquisar)="pesquisar($event)" 
        (limpar)="limpar()"  
        [mostrarTotalizador]="false" 
        [codigoCadastro]="codigoParaTabela">
      </procenge-datatable>
  </div>
</div>
```


{% endtab %}

{% tab title="JS" %}
```javascript
import { Cadastro } from './../../../shared/sistema/enum/cadastro';

// Exemplo de codigoParaTabela, 
// os codigos tem que estarem cadastrados nesse arquivo de cadastro
codigoParaTabela: string = Cadastro.CADASTRO_DE_TITULOS_A_RECEBER;

// exemplos de declaração
colunas: any[] = [];
dados: any[] = [];
dadosSelecionados: any[] = [];

// exemplo de como setar dados na lista
this.colunas = [
  { header: 'TITULO_NDO', field: 'titulo', tamanho: 100 },   
  { header: 'NDO', field: 'ndo', tamanho: 150 }
];

 dados.push({
  'ndo':ndo.NDO,          
  'titulo':titulo.TITULO_NDO
});
```
{% endtab %}

{% tab title="CSS" %}

{% endtab %}
{% endtabs %}
