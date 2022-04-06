# Flexbox
* Nos permite posicionar os elementos dentro da caixa
* Controle em uma dimensão (horizontal ou vertical)
* Alinhamento, direcionamento, ordenar e tamanhos
* 
``` css
div.parent {
	display: flex;
}
```

## Direção flex

* Qual a direção do flex: horizontal ou vertical
* roww | colunm
  
## Alinhamento
* justificar-conteúdo
* itens de alinhamento
  
HTML

``` html
<div class="container">
  <div class="box blue"></div>
  <div class="box red"></div>
  <div class="box green"></div>
</div>
```
CSS

```css

.container {
    display: flex;
    justify-content: space-between;
}
.box {
  width: 50px;
  height: 50px;
  margin-bottom: 8px;
}

.blue {
  background-color: blue;
}

.red {
    background-color: red;
}

.green {
    background-color: green;
}

```