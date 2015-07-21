ObjectJs
========

## Instalando com BOWER

```
bower install https://github.com/lcomino/ObjectJs.git
```
## Adicionando no html

```
<script src="bower_components/ObjectJs/object.js"></script>
```

## Utilizando

```
var object = {
  color : 'Red',
  value : 'Default value'
}

var newobject = {
  color : 'Blue'
}

Object.extend({}, object, newobject); // {color:'Blue', value: 'Default value'}
```

_Não afeta os objetos originais, ele retorna um novo objeto!_

Fique a vontate para contribuir com o projeto.
