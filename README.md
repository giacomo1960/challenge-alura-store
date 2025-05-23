
# ANALISIS VENTAS TIENDAS SR.JUAN

Este informe tiene la intención de ser una ayuda en la decisión de que tienda vender para iniciar un nuevo emprendimiento para el Sr.Juan. Para ello, se establece que este negocio es en Colombia y que tiene 4 tiendas de Alura Store, de las que se analizaron datos de ventas y comportamientos de la operación. 

##  Objetivos Del Proyecto 
Identificar la tienda menos eficiente para orientar las decisiones del Sr.Juan basada en los datos de ventas y comportamientos de sus tiendas.
## Tecnologías Utilizadas
## Instalación
## Uso
## Análisis de Datos
1. VALIDACION PERIODO DE ANALISIS
La operación de cada tienda se tiene que validar para hacer las comparaciones futuras, según muestra el CUADRO N° 1 adjunto, donde se indican las fechas de inicio y termino de de cada tienda.
CUADRO N° 1 PERIODO OPERACION
| Tienda  | Fecha inicio |Fecha término |
|---------|--------------|--------------|
|Tienda 1 | 2020-01-01   |2023-03-31    |
|Tienda 2 | 2020-01-01   |2023-03-31    |
|Tienda 3 | 2020-01-01   |2023-03-31    |
|Tienda 4 | 2020-01-01   |2023-03-30    |

Donde la Tienda 4 tiene 1 día menos.

ref: alura_store.ipynb/# 1. FECHAS ANALISIS BASE DATOS/

2. VENTAS TOTALES
El resultado de ventas totales se obtiene  por cada tienda sumando los valores de la columna 'Precio'. Estas se muestran en el CUADRO N° 2, con un detalle en pesos colombianos (COP).

CUADRO N° 2 VENTAS TOTALES POR TIENDA
| Tienda  |     Ventas Totales      |
|                    (COP)          |     
|---------|-------------------------|
|Tienda 1 |     1,150,880,400       |
|Tienda 2 |     1,116,343,500       |
|Tienda 3 |     1,098,019,600       |
|Tienda 4 |     1,038,375,700       |

![Gráfico de ventas](./assets/grafico.png)

Las ventas son lideradas por la Tienda 1  con el 26,13% y la de mas bajo rendimiento es Tienda 4 con 23.58%. La diferencia notable entre la tienda 1 y 4 se representa el 10.83% de menor rendimiento ( $112.504.700), con ello la posiciona como una candidata natural para ser vendida, si la prioridad es mantener los mayores ingresos posibles dentro del portafolio.

ref: alura_store.ipynb/#2. FACTURACION POR TIENDAS

3. VENTAS POR CATEGORIA (UNIDADES)
Las ventas por categoría se obtienen  por cada tienda sumando la cantidad de productos y que son agrupados por Categoría, como muestra el CUADRO N° 3, que ayuda a entender las preferencias de los clientes. Donde las categorías que concentran el 76.42% de las ventas son:
"Muebles"             :19.99% 
"Electrónicos"        :18.78%
"Juguetes"            :13.67% 
"Electrodomésticos"   :12.18%
"Deportes y diversión":11.80%

CUADRO N° 3 VENTAS POR CATEGORIA
|Categoría del Producto|Tienda 1|Tienda 2|Tienda 3|Tienda 4|Total|Porcentaje|
|---|---|---|---|---|---|---|
|Muebles|465|442|499|480|1886|19\.99|
|Electrónicos|448|422|451|451|1772|18\.78|
|Juguetes|324|313|315|338|1290|13\.67|
|Electrodomésticos|312|305|278|254|1149|12\.18|
|Deportes y diversión|284|275|277|277|1113|11\.8|
|Instrumentos musicales|182|224|177|170|753|7\.98|
|Libros|173|197|185|187|742|7\.86|
|Artículos para el hogar|171|181|177|201|730|7\.74|

Si bien es cierto que estas preferencias de los clientes se deben complementar con el valor total("Compras") por categorías y el valor del Ticket promedio como indicador de ventas especializado, como muestra el CUADRO N° 4. TICKET PROMEDIO VENTAS.

       480 |    1.92529e+08 |  401102           | Tienda 4 |


CUADRO N° 4. TICKET PROMEDIO VENTAS



4. Calificación prome
## Conclusiones
## Authors

- [@octokatherine](https://www.github.com/octokatherine)


## Tech Stack

**Client:** React, Redux, TailwindCSS

**Server:** Node, Express

