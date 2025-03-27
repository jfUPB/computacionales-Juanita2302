#### describe al menos dos errores que hayas cometido durante la fase APPLY (aplicación). ####
Durante la fase APPLY, cometí algunos errores que me ayudaron a entender mejor cómo funciona el ensamblador en Hack.
Uno de ellos fue no inicializar una variable antes de usarla en una operación, lo que provocaba que los resultados fueran incorrectos. 
Me di cuenta del problema revisando los valores en el simulador y lo corregí asegurándome de que todas las variables tuvieran un valor
antes de ser usadas.
Otro error fue en una instrucción de salto condicional, donde puse el comparador equivocado (JGT en lugar de JEQ), 
haciendo que el bucle no terminara cuando debía. Lo identifiqué al ver que el programa se quedaba atrapado en el ciclo y lo arreglé
cambiando la condición de salto

#### ¿Qué aprendiste de esos errores? ####
Gracias a estos errores, aprendí que es fundamental revisar cada instrucción y probar el código poco a poco. 
Para evitarlos en el futuro, puedo agregar comentarios en el código y hacer pruebas en partes pequeñas antes de ejecutarlo 
por completo.

El debugging es muy importante en el desarrollo de software porque ayuda a detectar y corregir fallos antes de que afecten
el funcionamiento del programa. En el simulador de NAND2Tetris, usé la ejecución paso a paso y revisé los valores de memoria y
registros para entender qué estaba fallando y hacer los cambios necesarios.
