**Folha simples de estilo para quem precisa ter mais liberdade na hora da codificação do Layout;**
 - Não acompanha estilização de elementos;
 - Um grid de demonstração vem incluso (exceto no arquivo minificado);
 - Atualizado para a resolução mais usada no momento; 

**Estrutura**
1. .container
- .row
- .col

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
