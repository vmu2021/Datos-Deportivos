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




