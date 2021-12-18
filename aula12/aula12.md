# JavaScript - Aula 12

## Condições em JS - Parte 2

## Condições aninhadas (else if)

```javascript
if (condiçãoUm) {
    blocoUm
} else {
    if (condiçãoDois) {
        blocoDois
    } else {
        blocoTrês
    }
}
```

## Condições múltiplas (Switch)

Serve para valores fixos.

```javascript
// Sintaxe do Switch:
switch(expressão) {
  case valor1:
    //
    break
  case valor2:
    //
    break
  case valor3:
  	//
    break
  default:
   	//
}
```

* O Switch só funciona com números inteiros e strings
* O **break** é imprescindível, senão a lógica do bloco quebra
