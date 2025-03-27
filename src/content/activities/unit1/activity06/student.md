#### Manejo básico de la memoria ####

- ¿Qué es el direccionamiento directo? ¿Cómo se usa en el lenguaje ensamblador Hack?
  Es cuando aquella instrucción accede a la dirección especial de la memoria Ram que se le pidió sin operaciones extras.

- ¿Qué significa M=D en lenguaje ensamblador Hack? ¿Y D=M?
  M = D Significa guardar el valor de D en la RAM, justo en la dirección actual de A.
  D = M Significa cargar el valor almacenado de D en la RAM, justo en la dirección actual de A.

- Puntero
  Se le llama así a una variable la cual almacena una dirección de memoria en otro dato en vez del mismo dato.

  ```
  @0      
  D = M
  @D     
  D = M
  @20
  M = D
  ```
- Explicación:
  Lo que hicimos fue apuntar a RAM[0] y luego cargar la D en la dirección. Después apuntar la dirección almacenada en D y cargar en D el valor almacenado en la dirección.
  Por ultimo apuntar a RAM y guardar ahí mismo el valor leído de RAM
  


  
