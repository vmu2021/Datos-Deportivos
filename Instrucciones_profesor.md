# Instrucciones Profesor
## Referencia de proyecto:
### [TIZONA](https://git.institutomilitar.com/proyectos-finales/tizona/-/blob/master/README.md)
> NO SE IMPLEMENTA, es documentarlo

## Plataformas (todo en .md)
**Documentacion:** se usa la [**WIKI**](https://git.institutomilitar.com/aGir18/datosdeportivosdim44/-/wikis/2.%20EVS/2.1.%20Requisitos),  
**Código** se usa **GITHUB** para subirlo
**Despliegue API:** lo veremos
**Despliegue aplicación:**  
**Base de datos:** habrá una base de datos gratuita en **Firebase**  
**Transparencias** [SLIDES](https://slides.com/)
**Serialización** JSON XML (posible uso cbor???)

## Sprints
sprint 1  
sprint 2

## Estructura código
+ carpeta raiz para hacer el proyecto  
+   estara la api  
+   el build gradle  
+   frontend(ya no es angular)  


# Entrevista Juan
Alternativas tienen que ser coherentes, sin que las estimaciones se desvien demasiado en **PRESUPUESTO** y **TIEMPO** 

# Obtención Datos

## Fuentes
+ football-data.co.uk  
+ bet365  
+ casas de apuestas  

## Eventos
+ Futbol  
+ NBA  
+ Carreras Galgos 

## Sucesos
goles, tarjetas, expulsiones, descalificaciones, retiradas, averiás, lesiones, etc.

## Eventos
de dos contrincantes o más 
+ fecha
+ hora
+ nombre
+ id único
+ resultado

## Persistencia
GRATUITO (sera Firebase) en principio
POSIOBILIDAD DE PAGO si empiezan a realizarse numerosas consultas

## Usuarios
un solo usuario

# Explotación datos

## Estadísticas
 de los datos goles, corner, tarjetas  
+ histórico de racha de eventos (2 últimas temporadas )
+ de los eventos (liga, compteción, medias anuales, etc)
+ patrón sucesos que se repiten en cada jornada (ej: en cada jornada hubo 1 empate, 1 roja, etc)
+ de cada participante en una competición (ACTUALIZA antes, durante, antes de que finalice)
+ cuotas con una diferencia significativa (Ej: 1-4)

## Consultas
ver los resultados de un evento  
> ordenar según criterio usuario  
  filtrar resultados para un determinado participante*
  
  
### Predefinidas
DOS COSAS IMORTANTES ANTES DE LOS PARTIDOS
 + diferencia de goles, puntos
 + empates entre equipos  

### Personalizadas
+ seleccionadndo conjuntos de datos del sistema

# Difusión Datos

## Exportación
+ CSV
+ JSON
+ XML
+ **etc PENDIENTE DEL PRIMO CBOR??**

## Interfaz
Fácil e intuitiva

## Plataformas
+ movil
+ ordenador

## Alternativas
+ gratuitas
+ pago
+ gratuitas con posibilidad de pago

## Fechas (por confirmar)
**22 FEBRERO** nos juntamos y tenemos que tener unificado el MindMap de todos los grupos  
**3 MARZO** reunion cliente  
**FINALES MARZO** exposicion Especificación Requisitos Software (ERS) y Producto Minimo Viable (MVP) 
**SEMANA ANTERIOR SSANTA** (4-8 ABRIL) **ERS y MVP** 
**DESPUES SSANTA** EVS EVR del proyecto individual

## Reuniones pendientes
+ 22FEB asuntos pendientes anterior reunión, MindMap y definir MVP
+ Final del Estudio de Viabilidad del Sistema
+ reunion pte Estudio Requisitis Software y definir Producto minimo Viable


# Requisitos funcionales 
| **Requisito** | **Prioridad** | **Descripción** |
| :-------: | :-------: | :-----------------------------: |
| RF1 | ALTA | Importar datos externos desde ficheros de texto plano |
| RF2 | ALTA | Almacenar datos de eventos deportivos: texto plano y BBDD SQL |
| RF3 | ALTA | Control de suscesos |
| RF4 | ALTA | Exportar datos en CSV, JSON, XML |
| RF5 | ALTA | Realizar consultas sobre los datos |
| RF6 | ALTA | Obtener estadísticas de los eventos |
| RF7 | ALTA | Obtener estadísticas de sucesos y participantes |
| RNF1| ALTA | Accesible desde múltiples dispositivos |

## Entrada de datos

### Eventos
De dos contrincantes...o mas
Fecha
Hora
Nombre
ID unico
resultado

### Deportes
futbol, baloncesto, carreras de galgos

### Sucesos
goles, tarjetas, expulsiones, descalificaciones, retiradas, averiás, lesiones, etc.

### Fuentes
+ football-data.co.uk  
+ bet365  
+ casas de apuestas  

## Procesamiento de datos

### Consultas
+ ver los resultados de un determinado evento
+ diferencia de puntos
+ empates
+ rachas
+ apuestas con una cuota elevada (Ej: 1-4)
+ Datos que se repiten en cada jornada
+ filtrar resultados para un determinado participante.
+ Ordenar acorde con distintos criterios establecidos por el usuario. 
Predefinidas 
+ usuarios podrán configurar sus propias consultas seleccionando datos concretos de entre los almacenados en el sistema.

### Estadisticas
de los eventos, los cuales podrán estar agrupados de una forma concreta 
(Ej., una jornada de liga, una competición completa, medias anuales, etc.).
Patrón de sucesos que se repita en cada jornada, como una roja, una expulsión, etc
Estadisticas por cada participante en una competicion.
ANTES, MITAD, FINAL partido


## Salida de datos

### Persistencia/ Almacenamiento
Servidor gratutito Firebase
ficheros de texto plano xml json csv etc
bases de datos relacionales

### Exportación
eventos
participantes
sucesos
etc.
CSV, JSON, XML, etc. (PENDIENTE DEL PRIMO) CBOR??

### Acceso
web y movil

## Carga

## Explotacion

## Interfaz
Fácil e intuitiva para los usuarios que permita orientar la apuesta.



2. Identificar los requisitos funcionales y especificar cada requisito con la estructura propuesta en el estándar IEEE 830: entradas, procesamiento y salidas.
3. Identificar dos requisitos no funcionales que describan restricciones que considera necesarias para el sistema a construir


