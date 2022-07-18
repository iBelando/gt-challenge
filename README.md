# GT Challenge

### Challenge 1

```
let a = 1;
let b = a;
a = 10;
console.log(b);
```

### Challenge 2

```
let persona = {
  nombre: 'Nacho'
};
let persona2 = persona;
persona2.nombre = 'Axel';
console.log(persona)
```

### Challenge 3

```
let numeros = [1, 2, 3, 1, 2, 3, 2, 2, 1];
```

### Challenge 4

```
function main() {
  function a() {
    return 5;
  }
  return a();
  function a() {
    return 10;
  }
}

function main() {
  let a = () => 5;
  return a();
  a = () => 10;
}
```

### Challenge 5

```
const palabras = ['hacer', 'oso', 'con', 'radar'];

const isPalindromo = (palabra) => palabra.split('').reverse().join('') === palabra;

isPalindromo(palabras[1]);
```
