# Código de Barras

{% hint style="danger" %}
**Status: Componente aguardando desenvolvimento.**

* [x] Componente definido e documentado pelos designers
* [x] Componente criado no backlog dos arquitetos
* [ ] Componente priorizado na "sprint" dos arquitetos
* [ ] Componente desenvolvido
{% endhint %}

{% hint style="success" %}
O componente código de barra deve ser utilizado para inputar códigos de barra e/ou de boletos bancários ou de concessionárias.
{% endhint %}

## Componente

O componente identifica se o código de barras é de um boleto bancário ou de concessionária e aplica a mascara correspondente.

![](<../../.gitbook/assets/image (584).png>)

### Estados

#### Normal

![](<../../.gitbook/assets/image (625).png>)

#### Preenchido / Boleto Bancário

![](<../../.gitbook/assets/image (624).png>)

#### Preenchido / Boleto Concessionária

![](<../../.gitbook/assets/image (634).png>)

### Validações

#### Erro no primeiro bloco

![](<../../.gitbook/assets/image (338).png>)

#### Erro no segundo bloco

![](<../../.gitbook/assets/image (419).png>)

#### Erro no terceiro bloco

![](<../../.gitbook/assets/image (415).png>)

#### Erro no último bloco

![](<../../.gitbook/assets/image (355).png>)
