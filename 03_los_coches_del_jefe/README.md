## README


### Los coches del jefe

##### PARTE 1
El archivo `TTERRENO.SAV` contiene información acerca de 125 vehículos de todo terreno clásicos. Tan clásicos, que sus precios vienen expresados en pesetas, que era la moneda oficial del Reino de España antes de la entrada en vigor del euro. En su afán como coleccionista, el dueño del family office en el que ud. trabaja los ha comprado todos y ha recogido, además, información relevante de ellos, expresada en las variables de las que tiene información en el documento `TTERRENO-VARIABLES.PDF` (ubicado en la carpeta references).

El dueño del family office, al que ud. reporta, quiere dividir los todo-terreno en las distintas propiedades que tiene. Dado que cuenta con hasta 10 lugares en los que podría conservar los vehículos, su trabajo consiste en asignar de la forma más eficiente y consistente los distintos vehículos, agrupándolos en virtud de las características que ud. considere oportunas. Debe por tanto informarse acerca de qué características pueden ser relevantes y cuáles no para el trabajo a realizar. Ser la persona de confianza del dueño tiene esas cosas, a veces no hay más remedio que entrar a estudiar cosas para las que ud. no se ha formado.

Una vez conocidas y justificadas cuáles son las características sobre las que va a trabajar, deberá explorar a qué datos se enfrenta, siempre con la mente puesta en la segmentación que deberá llevar a cabo más adelante.

Así pues, prepare un informe de 5 páginas justificando qué características ha considerado relevantes, por qué ha rechazado, si acaso, algunas otras (esto le llevará no más de una página) y describa, asimismo, en un máximo de 4 páginas adicionales y sin perder la perspectiva de la segmentación que más adelante llevará a cabo, las características de los vehículos que su jefe ha comprado.

***

##### PARTE 2

Su jefe tiene una semana complicada y le ha pedido que le haga una propuesta de cómo repartir la colección en las distintas residencias. Como ud. bien sabe, podría repartirlos como máximo en las diez que posee en la actualidad (precisamente está, durante esta semana, cerrando la venta de alguna de ellas, que quizá sustituya por alguna otra), pero, siendo una opción conservadora, quizá no sea la más adecuada, atendiendo a las caracerísticas que ud. ya conoce de los vehículos.

Así pues, su tarea es relativamente sencilla: estudiar el número adecuado de grupos en los que dividir la colección. El número máximo que puede alojar cualquier residencia es de 15 coches, pero eso no significa que los grupos sean de máximo 15 coches; en caso de proponer grupos con más coches, deberá escoger las residencias en las que guardarlos, atendiendo a un criterio de distancia.

El criterio de reparto debe ser consistente, y debe justificar su decisión en un máximo de 4 páginas.

![Map](./references/map.png)

***

##### PARTE 3
Finalmente, después de haber solucionado los problemas de selección de variables y tratamiento de valores perdidos, debe proceder a asignar los coches a las viviendas de su jefe. En un máximo de cuatro páginas, indique de qué forma va a proceder y cuáles son las características tanto de los grupos que ha creado como de los vehículos que asigna a cada vivenda.

***

### Structure

- README.md <- The top-level README for developers.

- data

	- 01_raw <- Immutable input data


- pdf <- pdf of the rmd.

- references <- additional information

- rmd <- r markdowns.

- solution <- html with the solution of the exercise.