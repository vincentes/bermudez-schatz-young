# Proyecto Verdulista
  
## Abstract 
Reserved.

## Introducción
Es sabido que la tecnología cambia la forma por la cual interactuamos con el mundo, pero estos cambios pueden ser abruptos y algunas personas simplemente no se pueden acostumbrar a ello. De hecho, es de conocimiento que en varios países existe un notorio envejecimiento de la población, y además, un exponencial desarrollo tecnológico. En otras palabras: los ancianos están siendo aislados del mundo debido a su poca capacidad de incorporar nuevas tecnologías en sus vidas.

El nuevo coronavirus denominado SARS-CoV-2 (COVID-19) funcionó como un catalizador para la tecnología en todos los aspectos de nuestra vida diaria, incluso llegó a modernizar el delivery de mercadería de supermercado. Es sabido que este virus es significativamente más dañino para las personas de mayor edad (60+). Los ancianos no pueden exponerse a la posibilidad de fallecer por un mandado. La data nos muestra que unos de los más importantes culpables son los supermercados. Como ejemplo, en Riverside, California, hubo alrededor de 48 brotes relacionados a supermercados el verano pasado. Actualmente el grupo social mencionado puede pedir comida online, si es que llega a tener un asistente humano para realizar dicha orden, ya que gran parte de ellos no tienen la suficiente alfabetización informática.

En este contexto, tomamos la iniciativa de cerrar la grieta entre la vejez y la tecnología, al menos en lo que tiene que ver con los supermercados.

Tomaremos como base de la solución imitar la experiencia de usuario que los ancianos tuvieron en épocas menos arraigadas al riesgo de contagio, y evitar la dificultad de enseñarles a nuestros clientes cómo funciona la tecnología, pero a la vez mejorando su flexibilidad de compra.

La idea es que nuestros clientes puedan comunicarse con el equipo a través del celular y pedir los productos que necesitase. Compramos la mercadería al menor precio pero cuando la relación de calidad-precio, para posteriormente enviarle al cliente su pedido.

Nuestros clientes pagarán vía tarjeta de débito o crédito para reducir el contacto y el riesgo de contagio. Sin embargo, podrán pagar en efectivo si así lo desean.


## Presentación del cliente

### Mayores de edad (60+)

#### Distribución etaria uruguaya

La tendencia en la distribución etaria uruguaya es el envejecimiento general. El porcentaje de personas en la franja etaria de 60+ es cada vez más alto, siendo un 23% de la población total.

![Image of dog](https://i.imgur.com/DJgzPMJ.png)

| Edad | Hombres | Mujeres |
| :------- | ----: | :---: |
| 0-4 | 120998 | 115658 |
| 5-9 | 120696 | 115718 |
| 10-14 | 119355 | 113959 |
| 15-19 | 125373 | 120242 |
| 20-24 | 129196 | 124869 |
| 25-29 | 130680 | 126815 |
| 30-34 | 120774 | 118842 |
| 35-39 | 110535 | 110995 |
| 40-44 | 116131 | 118233 |
| 45-49 | 108977 | 111679 |
| 50-54 | 94801 | 101540 |
| 55-59 | 92752 | 101984 |
| 60-64 | 83283 | 95541 |
| 65-69 | 68057 | 81040 |
| 70-74 | 53325 | 70486 |
| 75-79 | 38711 | 57744 |
| 80-84 | 24278 | 46053 |
| 85-89 | 13862 | 34361 |
| 90-94 | 5155 | 20077 |
| 95-99 | 1192 | 7617 |
| 100 | 205 | 1938 |


##### Franja de edad objetiva

| Edad | Hombres | Mujeres |
| :------- | ----: | :---: |
| 60-64 | 83283 | 95541 |
| 65-69 | 68057 | 81040 |
| 70-74 | 53325 | 70486 |
| 75-79 | 38711 | 57744 |
| 80-84 | 24278 | 46053 |
| 85-89 | 13862 | 34361 |
| 90-94 | 5155 | 20077 |
| 95-99 | 1192 | 7617 |
| 100 | 205 | 1938 |

Total de población: 702.926 (23%)

### Cuestiones sanitarias
Los mayores sienten un riesgo sanitario al ir supermercado. Se realizó una encuesta a 53 personas para investigar acerca de este sentimiento en nuestro grupo foco. El 73% de los mayores de edad reportaron temor ante la posibilidad de contagiarse en un supermercado o verdulería. El 81% de este grupo foco estuvo de acuerdo en que se debían disponer de mejores soluciones tecnológicas para el delivery de frutas y verduras. 

## Alternativas
### PedidosYa (igual que Rappi, UberEats)
PedidosYa es una compañía uruguaya de delivery que reúne los restaurantes locales y los depliesga en una interfaz amigable para el usuario, dandole la opción de elegir de una variedad de comidas.

Diferencias con el Proyecto Verdulista:
* Requiere una tarjeta internacional
* Requiere saber usar el celular
* No es de uso diario
* Caro

### Snap Kitchen (igual que Daily Harvest, Splendid Spoon, Hungryroot)
SnapKitchen es una plataforma de delivery de comida para personas que tienen tiempo limitado para cocinar o comprar comida. El usuario puede registrarse en la página, introduciendo su dirección y una tarjeta de crédito para pagar.

Diferencias con el Proyecto Verdulista:
* Solo funciona en los EEUU
* Requiere que el usuario sepa usar una computadora
* No se pueden pedir ingredientes, es comida lista

## Tecnologías a utilizar

| Categoría | Tecnología | Razón |
| :-------: | :----: | :---: |
| Control de Versiones| Git con GitHub | Requerido |
| Documentación | Markdown | Requerido |
| Backend | NodeJS | Requerido |
| Frontend | Markdown | Requerido |
| Frontend | AngularJS | Conocimiento del equipo, facil de usar, responsive |
| Diseño | Material Design (ng-material) | Requerido |
| IDE | Visual Studio Code | Requerido |
| Test unitarios | Jest | Conocimiento del equipo, facil de usar |

### Cuestiones sanitarias

## Requerimientos
##  Requerimientos funcionales
Existen diferentes especificaciones que el sistema debe cumplir para su uso e implementacion, tambien en este momento vamos a especificar el funcionamiento del sistema en un momento especifico. Ademas de como se procesa la informacion (entrada y salida). 

1.En caso de un evento en el que la compra llegue al destino dalerta se debe notificar al usuario. 

2. En caso de ocurrir un evento que no era esperado se debe de notificar al estudiante. 

3. Se le debe proporcionar a todos los usuarios, una lista de preferencias de listas de alimentos en oferta.

4. Se le debe proporcionar a todos los usuarios una lista de comercios preferentes.

5. Se le debe permitir a los empleados asignar a los usuarios una zna limite de pedidos.

6. Permitir a los empleados realizar encuestas de calidad de servicio a todos los usuarios  

7. Permitir a los empleados su notificacion por alertas metereológicas de grado anaranjado o rojo.

8. Permitir a  los empleados el acceso a diferentes rutas (y se le dara la mas optimizada) 

9. Mostrar al usuario la ubicación actual del empleado.

10. Dada la ubicacion del empleado, su ubicación guiar al empleadohacia la siguiente verduleria que quiera que vaya.

11.Permitir el alta y baja del sistema

12.Ecriptar la contraseña de los usuarios

# Requerimientos no funcionales

A continuacion  se muestran las restricciones  provistas por el sistema, en aspectos mas tecnicos e interoperaciones con sisteas externos.

1.El sistema debe soportar 2000 usuarios haciendo un evento sin superar el tiempo de realizacion maxima siendo este 3 segundos 
2. Los usuarios tienen disponibles aplicaciones son móviles compatibles con iOS 10 o superior y con Android 8 Oreo o superior
3. El sistmea debe ser amigables e intuitivos para usuarios y empleadaos.
4. El sistema debe estar disponible las veinticuatro horas del día sin percances. 
5. En la aplicación móvil debe correr de manera fluida, incluso con dispositivos relativamente antiguos.
6. El sistema debe ser compatible con Android 4.1 en adelante.

8. El diseño de los programas a desarrollar, deberán cumplir con la ley N°18.331 de protección de datos personales.
9.  La aplicación móvil no debe pesar más de 20MB, y la aplicación web no debe pesar más de 500MB.
10. Todo el codigo debe estar escrito en JavaScript. 

## Actores involucrados
El proyecto afecta a varios actores directa e indirectamente: 
Los actores directos son:
1- Los ancianos: son el eje central en la creacion de este servicio que propone facilitar la seguridad y practicidad con la que hacen compras durante la era del COVID-19.
2- Los proveedores: supermercados, tiendas de conveniencia , puestos de feria , seran los encargados de proveer las frutas y verduras a los compradores.
3- Empresa de reparticion: encargados de transportar la fruta del proveedor al cliente, fundamentales en la cadena y ademas es clave su cuidado de la higiene.
Los actores indirectos son: 
1- Otros competidores con servicios similares: Rappi, UberEats, Pedidos Ya , etc. Estos ya tienen una solucion similar para este tipo de propuesta por lo que puede pasar que intenten imitar este modelo de negocio con mayor capacidad productiva debido a que son empresas mucho mas grandes.
2- Reguladores: Muchos de los vendedores de frutas y verduras realizan transacciones informales es decir, no pagan impuestos por lo que un aumento de la demanda de estos comerciantes puede impactar en entes reguladores y ademas puede afectar a otras verdulerias que compiten con desventaja debido a que pagan impuestos.

## Objetivos especificos

A continuacion detallaremos los objetivos especificos del proyecto: 

1- Reducir el riesgo de contagio en personas mayores que no tienen manejo fluido con aplicaciones: estas personas durante el tiempo que quede de COVID-19 deberan al menos tener la libertad de elegir cuando salir a comprar y cuando no, sin verse limitadas a depender de alguien mas para tener stock de alimentos.

2- Darle mas independencia a las personas mayores en el mundo moderno: estos tiempos dejaron relegados a muchas personas mayores que no tienen la capacidad de adaptarse a determinados cambios que propuso la mezcla de la pandemia y el avance de la tecnologia. Por lo que esta aplicacion puede ser una puerta de entrada gradual al mundo de la tecnologia para que estas personas puedan disfrutar de una vida mas independiente y con mas opciones.

##  Necesidades 

Las necesidades que se presentan en este desarrollo son las siguientes: 

1- Desarrollar una aplicacion que permita organizar los pedidos: agregar, leer , modificar y eliminar estos de la manera mas organizada posible por el administrador del sistema.

2- Una base de datos para almacenar la aplicacion de la aplicacion del punto 1 y que esos datos sean persistentes.

3- Un adminsitrador del sistema: Una persona que cuente con las habilidades para manipular un telefono y responder las llamadas de las personas y agendar esos pedidos en nuestra plataforma(desarrollada en el punto 1).

4- Un servicio de transporte que permita coordinar los envios lo mas rapido posible ajustandose al horario de los clientes.



Fundamentos de Ingenieria de Software, Proyecto Universidad ORT 2021
