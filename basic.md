## Conceptos

### Declarar una variable
```
let variable = value;
```

### Declarar una constante
```
const end = value;
```

### Imprimir en consola
```
console.log(variable);
```

### Declarar un array *vacio/datos*
```
let array = [];
let array = ["first", "second"];
```

### Agregar un elemento al final de un array
Retorna el nuevo tamaño del array
```
array.push(element);
```
### Agregar un elemento al inicio de un array
Retorna el nuevo tamaño del array
```
array.unshift(element);
```

### Eliminar el último elemento de un array 
```
let popped = array.pop();
```

### Eliminar el primer elemento de un array
```
const shifted = array.shift();
```

### For
```
for (iterator; condition; iteration) {
  logic;
}
```

### for ... of - For each
```
for (const <value> of <iterable>) {

}
```

### Declarar un método
```
function name(parameter) {

}
```

### if
```
if (condition) {
  // this code will run if condition is true
} else if (condition2) {
  // this code will run if the first condition is false
} else {
  // this code will run 
  // if the first and second conditions are false
}
```

### While
```
while (condition) {
  logic;
}
```

### Objetos
```
const object = {
  name: "Test"
  "age of": 10
};
```

### Acceder a los atributos de un objeto
```
object.name;
object["age of"];
```