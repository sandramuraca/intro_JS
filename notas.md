# INTRODUCCION A JS:

Notas teóricas sobre JS de lo visto en clase de ADA ITW y en Courseit
___

- Lenguaje orientado a objetos
- Creado por la necesidad de generar ntereccion con el usuario

## CARACTERISTICAS:

- Debilmente tipado: puedo cambiar desde el codigo un tipo de dato (el tipo de dato se define en la variable -var-)
- Interpretado: el codigo se traduce en tiempo real (no necesita correrse un proceso que lo traduzca al lenguaje de maquina)
- Dinámico
Es secuencial, es decir que tiene un orden

Se puede programar con JS desde un index.html itilizando la etiqueta:
 `<script></script>`  

🚫NO SE PUEDEN ANIDAR!🚫
<script>
    <script></script>  
</script>  ---->NOOOO!

Tambien se puede linkear un archivo con extensión JS
Las intrucciones (funciones o comandos) de js se ven en la CONSOLA no en el borwser

### VARIABLES:  
**Se puede escribir escribe: const / let / var**
Espacios de memoria donde se almacenan DATOS, los datos son información
CONST: variable constante, el dato no puede modificar. Se utiliza generalmente para un nombre.

*VAR y LET*: variables que se pueden modificar. Ejemplo la edad, si yo defino una variable con mi edad actual luego le sumo 1 (el año proximo) y me va a dar mi nueva edad.
Por defecto siempre se usa CONST. 

### TIPOS DE DATOS:
*-STRINGS:* cadena de texto
*-NUNMBER:* enteros, decimales, positivo, negativo
*-BOOLEAN:* 0 / 1 - true / false
*-NULL:*nulo
*-UNDEFINED:* no esta definido 
*-OBJETOS:* conjunto de propiedades que habla de algo en particular

Ej:
const nombre = 'Sandra'
Aqui tenemos una VARIBLE CONSTANTE "const" a la que le asignamos un tipo de dato "STRING" = nombre

Para escribir el dato de una variable se puede usar los 3 tipos de comillas disponibles: "" - dobles-  o '' - simples-  o ``-backtics o invertidas-

Las comillas dobles en una oreación por ejemplo, sirven para "destacar".
Ej
constant sentence = 'Sandra "Sandrita" es programadora'

Para ver en la consola una variable que no tiene asociado un console.log, se escribe el nombre de la sentencia, si seguimos el ejemplo anterior, si en la consola escribo: sentence, me va a traer el dato: 'Sandra "Sandrita" es programadora'

### OBJETOS
Sirven para agrupar variables que no tienen una relacion entre si.
Se escribe con {} y dentro tiene PROPIEDADES: CLAVE-VALOR 


### ARRAIS: 
Listas de elementos se escribe con []
Es un TIPO DE OBJETO, una forma de agrupar elementos de cualquier tipo.
En la consola cuando vemos el resultado del array, vemos que los elemtos agrupados cada uno se encuentra identificado con un numero que se denomina INDICE, el cual indica la POSICION de cada elemento. La numeración del indice siempre aranca en 0.
Ese nro indice se pued eutilizar luego para llamar a uno solo de los elementos agrupados.
En los arrays importa el orden de los elementos, su potencial maximo esta junto con los METODOS preprogramados por JS que vienen por defecto con el lenguaje.
El array es ITERABLE.

