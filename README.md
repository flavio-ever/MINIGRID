**Folha simples de estilo para quem precisa ter mais liberdade na hora da codificação do Layout;**
 - Não acompanha estilização de elementos;
 - Um grid de demonstração vem incluso (exceto no arquivo minificado);
 - Atualizado para a resolução mais usada no momento; 

**Classes**
```
.no-space (somente com .row)

.col-1
.col-2
.col-3
.col-4
.col-5
.col-6
.col-7
.col-8
.col-9
.col-10

.column-overlay (após uma .col-* use como wrapper de conteúdo)

.move-left-1 (somente com .col-*)
.move-left-2 (somente com .col-*)
.move-left-3 (somente com .col-*)
.move-left-4 (somente com .col-*)
.move-left-5 (somente com .col-*)
.move-left-6 (somente com .col-*)
.move-left-7 (somente com .col-*)
.move-left-8 (somente com .col-*)
.move-left-9 (somente com .col-*)
.move-left-10 (somente com .col-*)
.move-left-11 (somente com .col-*)
.move-left-12 (somente com .col-*)

.move-right-1 (somente com .col-*)
.move-right-2 (somente com .col-*)
.move-right-3 (somente com .col-*)
.move-right-4 (somente com .col-*)
.move-right-5 (somente com .col-*)
.move-right-6 (somente com .col-*)
.move-right-7 (somente com .col-*)
.move-right-8 (somente com .col-*)
.move-right-9 (somente com .col-*)
.move-right-10 (somente com .col-*)
.move-right-11 (somente com .col-*)
.move-right-12 (somente com .col-*)
```

**Não deixe de usar a classe: '.container'**

**Grid de Overlay**
```
<div class="grid-overlay">
    <div class="row">
       <div class="col-1"><div class="column-overlay"></div></div>
       <div class="col-1"><div class="column-overlay"></div></div>
       <div class="col-1"><div class="column-overlay"></div></div>
       <div class="col-1"><div class="column-overlay"></div></div>
       <div class="col-1"><div class="column-overlay"></div></div>
       <div class="col-1"><div class="column-overlay"></div></div>
       <div class="col-1"><div class="column-overlay"></div></div>
       <div class="col-1"><div class="column-overlay"></div></div>
       <div class="col-1"><div class="column-overlay"></div></div>
       <div class="col-1"><div class="column-overlay"></div></div>
       <div class="col-1"><div class="column-overlay"></div></div>
       <div class="col-1"><div class="column-overlay"></div></div>
    </div>
</div>
```
**Estrutura comum das colunas**
```
<div class="row">
    <div class="col-8 move-right-2">
        <div class="column-overlay">
          8
        </div>
    </div>
    <div class="col-8">
        <div class="column-overlay">
          8
        </div>
    </div>
    <div class="col-4">
      <div class="column-overlay">
        4
      </div>
  </div>
</div>
<div class="row no-space">
    <div class="col-5">
        <div class="column-overlay">
          5
        </div>
    </div>
    <div class="col-7">
        <div class="column-overlay">
          7
        </div>
    </div>
</div>
```
