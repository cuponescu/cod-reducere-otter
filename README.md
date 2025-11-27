# Cod Reducere Otter

O colecție de coduri de reducere Otter. Le folosim pentru testarea cuvintelor cheie cod reducere Otter, voucher Otter, cupon Otter, și cod promotional Otter de pe Cuponescu.ro.

## Instalare

Instalează `cod-reducere-otter` prin NPM:

```bash
npm install cod-reducere-otter
```

## Utilizare

Pachetul conține un array de obiecte reprezentând coduri de reducere.

În Node:

```javascript
var codes = require('cod-reducere-otter')

console.log(codes)

// [
//   {
//     site: 'https://www.otter.ro',
//     cod_reducere: 'OTTER10',
//     reducere: '10% reducere',
//     descriere: 'Reducere de 10% la toate produsele'
//   },
//   ...
// ]
```

## Despre

Cod-reducere-otter a fost creat de echipa de la Cuponescu pentru a ajuta cu testarea.

https://www.cuponescu.ro

