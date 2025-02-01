##### Profundizando en las instrucciones del lenguaje ensamblador #####

##### ¿Cuál es la función de cada tipo de instrucción? #####
- De acuerdo a lo leido en el texto, he podido evidenciar que cada instrucción cumple una funcion para:
##### A-instructions: Se usan para cargar un valor en A el cual puede ser un numero constante o una dirección de memoria, su sintaxis es @ #####
##### C-instructions: Se usan para hacer operaciones aritméticas y lógicas. Son más complejas que las A y tienen tres partes (Comp, dest y jump) #####

##### ¿Cómo se representa cada tipo de instrucción en binario? #####
- En cuanto a la representación en binario es un poco más complejo pero de forma breve y clara:
- A-instructions: Su formato es 0 000000000XXXXXXX (espero no haberme pasado ceros ni x) son de 16 bits
- B-instructions: Su formato es 111 aaaaa bbbbb ccccc y es igual de 16 bits

##### Ejemplos: #####

1)

- @2 (Estamos cargando el número 2 en el registro A)
- D = M (Se encarga de guardar el valor en la dirección 2 dentro de la D)
- @3 (Estamos cargando la dirección 3 en el registro A)
- D = D + M (Se encarga de sumar el valor de 3 con D)
- @0 (Estamos cargando la dirección 0 en A)
- M = D (Guarda el resultado en 0)
- @END (Carga END en el registro A)
- 0;JMP

2)

- @5 (Estamos cargando el número 5 en el registro A)
- D = M (Se encarga de guardar el valor en la dirección 5 dentro de la D)
- @10 (Estamos cargando la dirección 10 en el registro A)
- M = D (Se encarga de guardar el valor de D en la dirección 10)
- @END (Mantiene)
- 0;JMP
