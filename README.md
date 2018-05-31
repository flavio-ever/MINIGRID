**Folha simples de estilo para quem precisa ter mais liberdade na hora da codificação do Layout;**
 - 4Kb arquivo original / 2Kb arquivo minificado.
 - Não acompanha estilização de elementos;
 - Grid de 1360px; 
 - Com a classe .move--*, você consegue melhor posicionar a coluna dentro do Grid;
 - São 12 colunas;
 - Estrutura flexível;
 - A menos de 600px as colunas se empilham verticalmente;

**Classes**
```
.container (width 1360px)

.no--space (somente com .row)

.col--1
.col--2
.col--3
.col--4
.col--5
.col--6
.col--7
.col--8
.col--9
.col--10
.col--11
.col--12

.column-overlay (após uma .col--*, use como wrapper de conteúdo)

.move--1    (somente com .col--*)
.move--2    (somente com .col--*)
.move--3    (somente com .col--*)
.move--4    (somente com .col--*)
.move--5    (somente com .col--*)
.move--6    (somente com .col--*)
.move--7    (somente com .col--*)
.move--8    (somente com .col--*)
.move--9    (somente com .col--*)
.move--10   (somente com .col--*)
.move--11   (somente com .col--*)
.move--12   (somente com .col--*)
```
**Obs: Não deixe de usar a Classe: '.container'**

**Estrutura comum das colunas**
```
<div class="row">
    <div class="col--8 move--2">
        <div class="column--overlay">
            8 ( .move--2 )
        </div>
    </div>
    <div class="col--8">
        <div class="column--overlay">
            8
        </div>
    </div>
    <div class="col--3">
        <div class="column--overlay">
        4
        </div>
    </div>
</div>
<div class="row no--space">
    <div class="col--6">
        <div class="column--overlay">
            6 ( row .no-space )
        </div>
    </div>
    <div class="col--6">
        <div class="column--overlay">
            6 ( row .no-space )
        </div>
    </div>
</div>
```
