# css grid

## container

debe tener 
display :grid


- grid explicito 

grid-templat-rows
grid-template columns

grid-template : filas / columnas;
grid-template : 300px 150px  / 25% 200% 25%;

- grid implicito 

display: 
subgride: hereda la configuracion grid del padre
inline-grid: grid en linea , toma el tamaño de su contenido


    /*grid-template-rows: 80px  80px 60px;
     grid-template-columns: 25% 50% 25%;*/
    /* grid-gap: filas columnas;  */

espaciado
-contenido dinamico


<>
## nueva unidad de medida  fr

auto: designa el tamaño de acuerdo a su contenido

repeat(counter, size)
repite una mdida tantas veces como el counter lo indique
minmax(min,max)
define el ancho minimo y máximo de una columna o fila en grid




## emmet 

    <!-- .item{contenido #$}*100 -->
    <!-- .item{contenido #$}*100 -->


fr: designa una fraccion del grid
