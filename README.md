# int1-Practica02-250980
---
En esta práctica aprenderemos a utilizar las herramientas Git y GitHub para el control de versiones de proyectos de desarrollo de software, aplicando principios de buenas prácticas en Documentación, Desarrollo Colaborativo y Respaldo en la nube del Proyecto Integrador.


Elaborado por: **Brian Isael Ramirez Cortes**

Materia: **Proyecto Integrador**

Docente: **M.T.I. Marco Antonio Ramírez Hernández**

Periodo: *Mayo - Agosto 2026*


## Comandos Básicos para Maquetado de la Documentación utilizando el estandar de Markdown (.md)
---

Mardown es el estándar utilizado por Git y GitHub, para estelizar (maquetar) la documentación de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operación del mismo.

### 1. Encabezados o Títulos (HEADERS)

Para poder realizar una buena documentación del proyecto debemos dsitribuir correctamente los contenidos, para poder delimitar o hacer enfasis (enfatizar), es decir, resaltar las secciones más importantes, podemos utilizar los siguientes: 

**EJEMPLOS**

# Encabezado de Nivel 1 
## Encabezado de Nivel 2
### Encabezado de Nivel 3
#### Encabezado de Nivel 4
##### Encabezado de Nivel 5
###### Encabezado de Nivel 6
####### Encabezado de Nivel 7 - *El estandar solo permite 6 niveles para titulos, a partir del séptimo serán presentado como texto plano (sin estilo)*

### 2.- Separadores (SEPARATORS)

Si se desea marcar una separación visual de los contenido podemos utilizar una línea horizontal indicano tres carácteres - continuos, en el maquetado

**EJEMPLO**

### Título de la sección 

---

Texto despuén del separador 
### 3. Párrafos (PARAGRAPHS)

Son Utilizados para presentar grandes secciones de texto que decriben detalladamente el contenido de las secciones de la documentacion,detallan procesos, explican código teórico.

**EJEMPLO:**

Párrafo 1: Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 vEste texto es del párrafo 1 Este texto es del párrafo 1 Este texto es del párrafo 1 

Párrafo 2: este texto es del párrafo 2 este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2veste texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2este texto es del párrafo 2veste texto es del párrafo 2este texto es del párrafo 2,el estandar de markdown distingue los párrafos con un doble de línea de texto, si no se párrafos con un doble salto de texto,si no desea alinear ,es decir estará alineado a la izquierda por defecto

En caso de que necesitemos alinear el párrafo a **izquierda**, **derecha**,**centrado** o **justificado**, deberemos utilizar una etiqueta '''<p>''' con la propiedad aling y la direccion deseada. 

<p align="left">Párrafo alineado a la izquierda   párrafo alineado a la izquierda párrafo alineado a la izquierdapárrafo alineado a la izquierda párrafo alineado a la izquierda párrafo alineado a la izquierda párrafo alineado a la izquierda párrafo alineado a la izquierda párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda  párrafo alineado a la izquierda 

<p align="right"> Párrafo alineado a la derecha párrafo alineado a la derecho párrafo alineado a la derechopárrafo alineado a la derechopárrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho párrafo alineado a la derecho

<p align="justify"> Párrafo justificado  párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado párrafo justificado



### 4. Enfatizado de Texto

Texto en Negritas: Para realizar texto importante que no sea un titulo por questo inicialmente están en negrita, debemos encerrar el texto desdeado entre dobles asteriscos (**)

Ejemplo: Este texto estan en **negrita**.

- Texto en Cursiva (Italico): Para hacer referencia a texto utilizando el formato inclinado o italico bastará con encerrar el texto deseado entre dos asteriscos simples (*)

Ejemplo: Este *Texto* estara *inclinado*

- Texto en Cursiva y Negrita: Para lograr esta estilización en la documentación basta con juntar ambas configuraciones , es decir encerramos el texto en un triple asterisco (***)

Ejemplo: ***Este texto esta Negrito e Italico.***

- Texto Tachado: En algunas ocaciones es necesario dar formato al texto con un efecto de como es incorrecto, generalmente esta idea se transmite por que el texto esta tachado, es decir con una linea que lo marca por la mitad. Para lograr este efecto tendremos que encerrar el texto entre una doble tilde de (~).

Ejemplo: Se dice haya no ~haiga~.

- Texto Subrayado: En este tipo de formato el texto queda sobre una linea inferior para denotar su relevancia, este formato no tiene una versión rápida en el estandar MARDOWN, pero dado su similaridad a HTML podemos utilizar las etiquetas ``` <u> ``` y ``` </u>```.

Ejemplo: El <u>texto</u> debe estar <u>subrayado</u>.

- Texto en Super Indice: En algunas ocasiones se requiere dar formato a formulas estadisticas que requieren potencias entre otras aplicaciones, podemos utilizar tag de HTML ``` <sup> ``` y ``` </sup> ``` para delimitar el formato.

Ejemplo: Para elevar x al cuadrado tendriamos lo siguiente x<sup>2</sup>

- Texto en Subindice: En el caso de Quimica se utilizan subindices para representar formulas, para ello podemos utilizar el formato de texto con la etiqueta HTML. ``` <sub> ``` y ``` </sub> ```

Ejemplo: La formula del Agua es H<sub>2</sub>0.


### 5. Listas

Cuando realizamos documentación utilizando el estandar de MARKDOWN, es común que tengamos que listar elementos, requisitos de hardware, requisitos de software o enumerar pasos de como el sofware debe ser instalado paso a paso, por eso debemos saber como crear listas de las cuales hay de 3 tipos : **Ordenadas (Numeros)** , **Desordenadas (Viñetas)** y **Mixtas (Viñetas y Numeros)**.

1. Listas Ordenadas

Estas deberán estar enumerdas con un numero seguido por un punto y un espacio en blanco para comenzar con el listado.
1. Pc
2. Wifi
3. Modem
4. Smartphone
6. Smart TV
5. Tablet 

Para reiniciar el conteo se debe poner una linea de texto sin numeralia.

2.  Listas Desornedadas

Estas listas no llevan un numero, sino una viñeta(simbolo), y suele listar elementos que no requieren un orden especifico.

- Pan
- Leche
- Huevo
- Azucar

3. Listas Mixta

Son aquellas que mezcla ambos elementos

- 3°A DSM
1. Juan
2. Pedro
3. Alejandra
- 3°B DSM
1. Romina
2. Daniel
- 3°C DSM
1. Yahir
2. Liseth
3. Jeovany
4. Erick

### 6. Bloques de Código (CODE BLOCKS) o Citas (BLOCK QUOTES)

Estos estilos de texto se utilizan para limpiar la atencion del lector, en pasos que son importantes, realizar algunas reseñas o segmentar lineas de codigo que se deberaán ingresar en una terminal de comandos o lineas de ejecución.

- Cuadro de Citas (BLOCK QUOTES)
Son cajas estilizadas en colores grises por defecto con un margen mas claro

Ejemplo

Para listar las carpetas y archivos desde una terminal de comandos en el sistema operativo de Windows debemos usar el comando:

> C:/dir

Despues oprimimos la tecla "Enter":

Tambien podemos usar texto multilineas

EJEMPLO:

Pasos para instalar MYSQL
> - Descargar el archivo instalador desde la página oficial www.mysql.com
> - Instalar el Servidor de Base de Datos
> - Definir el puerto y contraseña para el usuario **root**
> - Inicializar el servicio de base de datos
> - Conectarnos a la base de datos para verificar que se instalo correctamente

- Bloques de codigo 

Es común que la documentación del proyecto de software demos al usuario un par de instrucciones de como instalar, configurar, desplegar y testear (pruebas), nuestro producto desarrollado. Por tal motivo el estándar markdown nos permite enfatizar estas instrucciones , simulado estar en una terminal de sistema operativo, para delimitar este código basta encerrarios un triples caracteres de bactic (acento o tilde inversa ''' ' ''')

Para clonar el proyecto ingresa la siguiente instrucción

Ejemplo

```
C:\Users\PC-09>git clone https://github.com/250980-brian/int1-Practica02-250980
```

A diferencia de los bloques de citas, la tipografia y significado asociado cambian.

### 7. Tablas

En caso de que necesitemos una estructura de datos o información relevante para la documentación podremos utilizar el formato de tablas, para lo que tenemos considerar la estructura base de una tabla:

- Usa | para delimitar las columnas
- Usa --- para separar las filas del encabezado

Ejemplo :

|Título 1 | Título 2 | Título 3 | Título 4 |
|---|---|---|---|
|Fila 1, Celda 1|Fila 1, Celda 2|Fila 1, Celda 3|Fila 1, Celda 4|
|Fila 2, Celda 1|Fila 2, Celda 2|Fila 2, Celda 3|Fila 2, Celda 4|
|Fila 3, Celda 1|Fila 3, Celda 2|Fila 3, Celda 3|Fila 3, Celda 4|

### 8. Hipervínculos (Links)

Para poder hacer referencias a documentos internos o externos dentro del repositorio, debemos respetar la siguiente estructura

```
[Texto que el usuario leera](url a donde te dirigirá) "texto que aparecerá cuando pongas el cursor sobre la liga"
```

Ejemplo

- Ligas externas
[Google](http://google.com)

- Ligas internas
[Acerca del Autor](./aboutme.md "Cónoceme más!")

### 9. Imágenes

El estándar de markdown nos permite incrustar imágenes dentro de nuestra documentación lo que nos permitirá poner logotipos, capturas de pantalla o cualquier archivo gráfico importante.

La estructura varia un poco de las referencias de hipervinculos, siendo:
```
![Texto que el usuario leera](url a donde se encuentra la imágen)
```

Ejemplo:
![Gato](./imagenes/gato.jpg)

Es importante comprender que la resolución de la imagen sera la original del archivo.

**Tip PRO**
Si el tamaño de la imagén no se ajusta a lo que deseas para tu documento, lo más recomendable es ajustar el tamaño del archivo original con algún software procesador de imágenes como : Paint, Illustrator, Ink o Photoshop. pero si quiere modificarlo desde el código, el estandár no tiene parametros definidos por lo que necesitaremos echar líneas de código HTML

Cambiando la estructura de maquetado por la etiqueta ``` <img> ```

Ejemplo:

<img src="./imagenes/gato.jpg" width="100" heigth="50">

### 10. Notas al pie

Si nuestra documentación requiere ubicar notas de importancia o relevancia posterior podemos usar notas de pie de manera dinámica

Nota al pie 1 [^¨first]

Nota al pie 2 [^Second]

Referencias al pie dentro ^[Nota interna] extenso dentro de nuestra documentación.

Segunda referencia la nota 2[^Second].

[^first]: Nota al pie **Puede ser formateada**

y tener múltiples lineas de parrafo 
[^Second]: Texto de la segunda nota al pie.

[^first]: Texto de la primera nota al pie
[^second]: texto de la segunda nota al pie
[^interna]: Texto de la nota interna

### 11. Abreviaciones

El estándar de Markdown (junto con extensiones comunes como markdown-it-abbr) nos permite definir abreviaciones que mostrarán su significado completo cuando el usuario coloque el cursor sobre ellas.

Este formato es inteligente: convierte las coincidencias exactas de la palabra, pero mantiene intactas las entradas parciales o palabras compuestas (por ejemplo, convertirá la palabra "HTML" por separado, pero dejará sin cambios términos como "xxxHTMLyyy").

Para declararlas, se coloca un asterisco seguido de la abreviación entre corchetes, dos puntos y su significado.

Ejemplo:

*[HTML]: Hyper Text Markup Language

### 12. Contenedores Personalizados

Cuando creamos documentación técnica, es fundamental resaltar advertencias, notas importantes o consejos de una manera visualmente llamativa. Para ello, podemos utilizar contenedores personalizados apoyados en bloques de tres puntos dobles (:::) seguidos de la palabra clave o etiqueta del contenedor (como warning, info o danger).

Ejemplo:

::: Advertencia: *Aquí hay dragones*
:::