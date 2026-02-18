---
type: leccion
curso: Unidad 1
fecha: 2026-02-15
estado: en-progreso
tags:
  - leccion
---
#  Lección 01 - Principios del diseño de Arquitectura
Unidad: [[Unidad 1]]

## Descripción general de la lección

> 

##  Objetivos de la lección

> ¿Qué deberías saber al terminar esta lección?

---

## Contenido

> Introducción a la Arquitectura de Software
> Géneros Arquitectónicos
> Estilos Arquitectónicos
> Diseño Arquitectónico
> Evaluación de los diseños Alternativos para la arquitectura.
> Mapeo de la arquitectura con el uso del flujo de datos

### Introducción a la Arquitectura de Software

Cuando hablamos de arquitectura de software nos referimos tanto a la parte de hardware y software.

La [Arquitectura de Software](https://youtu.be/NtTlN_wFbwY) se asemeja a lo que seria un plano de una casa, solo que este establece lo que seria:

- Estructura del sistema.
- Componentes.
- Propiedades del Hardware.

Para poder lograr una buena arquitectura de software es recomendable:

- Estudiar y analizar cada aspecto de la organización y los intereses de los involucrados en el proyecto para tomar las mejores decisiones.
- Averiguar todos los detalles para facilitar el desarrollo simultaneo de módulos o componentes y detectar errores antes de que su impacto sea mayor.
- Dedicar tiempo a la elaboración de modelos y esquemas que permiten visualizar de manera general el sistema y el funcionamiento de cada uno de sus componentes.
- Considerar el panorama actual que busca resolver el sistema, la visión a futuro de crecimiento y su mejora.
- Detallar el sistema de la arquitectura para resolver posibles discusiones y cuestionamientos del software durante la gestión para precisar el costo y el tiempo necesario para su implementación.

En la actualidad el proceso de desarrollo de software a aumentado progresivamente, teniendo como resultado la construcción de grandes y complejos sistemas que requieren la combinación de diferentes tecnologías y plataformas de software y hardware para alcanzar las funcionalidades requeridas.

En consecuencias el producto resultante deber ser **flexible y específico**, para la resolución de un problema.

Por esto los desarrolladores deben definir:

- Requisitos críticos
- Funcionales
- De rendimiento y/o de calidad

Y lo que deben lograr es:

- Solucionar sus objetivos
- Definir el conjunto de estructuras, clases y atributos principales del software y sus interfaces de comunicación

El problema radica en saber priorizar:

- Definición
- Diseño
- Implementación
- Evaluación

> [!info] Requeriemientos
> Cuando se habla de requerimientos, principalmente se refieren a los de la empresa, no a los del sistema.
> 
> 

> [!caution] Arquitectura de Software
> Esta se encarga de enseñarnos a como hacer un sistema, desviarnos de esto, siempre lleva al fracaso

hacer un despliegue con errores nunca es una opción, se tiene que hacer bien el trabajo, el código se congela al momento del despliegue, incluso hasta las pruebas hay que diseñar (las pruebas se diseñan desde el inicio).

Sistema de emisión critica:
Emergencia de un hospital, todo el tiempo tiene que producir resultados certeros, casi libre de fallas. en todo sistema hay que tener cuidado en que salga nítido.

Si no sale en tiempo un proyecto, seguramente sale con errores, cuesta tiempo y dinero, sistemas que puedan tener riesgos.

Orden de temas:

- Planos, de todo hay que hacer planos.
- Que conlleva la arquitectura:
	- Estructura del sistema
	- Componentes
	- Propiedades del hardware
- Estudiar y analizar los intereses de la organización.
- Esconder es un tapar un error, es una falta de ética intentar zafarse del error. 
- La obligación del sistema es trabajar para lo que se espera, no para lo que entendimos.
- Trabajar con tiempo es importante.
- DDA, Documento de Definición de Arquitectura.
- No se debe implementar nada, que no se haya modelado en la arquitectura.
- Visión a futuro, por muy pequeño que sea un sistema, nadie asegura que no vaya a crecer a futuro.
- Todos los sistemas tienen que estar alienados, al plan estratégico institucional. (Sistema apadrinado por la gerencia).
- Atributos de Calidad, (flexible y especifico escalable distribución eficiencia)
- Implementación
- Aplicación de Tecnologías

---

En la [Arquitectura de Software](https://youtu.be/RJsLcC3JeDY) tener un plan es esencial, es como tener un plano para poder construir una casa, este define como todas las partes del software interactúan entre si. La arquitectura indica como es que se conectan las partes para que funcione correctamente. 

Hay diferentes patrones de arquitectura de software, con lo que permite como estructurar el software, ejemplo vista controlador, MVC.

Elegir la arquitectura correcta es vital para el proyecto. ya que si no se alinea con las necesidades de la aplicación se tienen problemas de rendimiento. Es esencial considerar factores como tamaño, complejidad y experiencia del equipo.

Una arquitectura bien definida mejora la colaboración, trabajo en equipo mas eficiente, mayor  mantenibilidad, con lo que se pueden hacer cambios sin afectar a todo el sistema, escalabilidad, puede aumentar el trabajo de datos y mejor riesgos.

Diseñar es la primera parte fundamental, ya que no podemos construir sin un plano o guia para poder realizarlo.


---

### Arquitectura de Software

¿Qué es una arquitectura?

- IEEE 1471
	- El nivel conceptual más alto de un sistema en su ambiente
- Arquitectura es la organización fundamental de un sistema descrita en 
	- Sus componentes
	- Relación entre ellos con el ambiente.
	- Principios que guían su diseño y evolución.
- Software Architecture in parctice - Kazman
	- La estructura de estructuras de un sistema la cual abarca componentes de software, propiedades externas visibles de estos componentes y sus relaciones.
	- 


> [!info]
> Lo primero que hay que realizar  no es el patron arquitectonico (como implementar la arquitectura), patron de diseño (tiene que ver con el patron arquitectonico,)
> Son los principios que guian los dieños. (Estilo, todo el sistema o conjunto de sistemas en su totalidad, uno que es base o con mayor influencia.

### ¿Qué es?

El diseño arquitectónico representa la estructura de los datos y de los componentes del programa que se requieren para construir un sistema basado en computadora.

### Atributos

(Atributos de calidad)
Entre los atributos que debería tener un buen diseño son **durabilidad, utilidad y encanto**.

Aplicados al software estos atributos podrían verse como fácil de implementar, entendible, de confianza y fácil de evolucionar.


> [!important]
> Existen 3 tipos de drivers, ARF, Atributos de Calidad, De restricción> 

¿Qué es?
- La arquitectura de un sistema de software define un sistema en términos de componentes computacionales e interacciones entre componentes.
- La arquitectura del software en un sistema es la estructura o estructuras de un sistema en el cual se comprometen los elementos de un software, las propiedades externas visibles de esos elementos y las relaciones entre ellos.
- Se debe equilibrar los requisitos y la calidad.

> [!tip] Definición Básica
> La arquitectura de software de un programa o sistema de computación es la estructura o estructuras del sistema, las cuales comprometen elementos de software, las propiedades externamente visibles de esos elementos y las relaciones entre ellos.


### Otras definiciones

- Es la organización de un sistema en términos de sus componentes de software, incluyendo los subsistemas e interacciones entre ellos, y los principios que guían el diseño de ese sistema de software.
- Es una forma coherente de establecer los patrones y abstracciones para que los analistas y desarrolladores trabajen en una línea común hacia la implementación del sistema de información.
- Una arquitectura sigue un patrón o un conjunto de patrones que proporcionan un marco de referencia para lograr la funcionalidad requerida por el cliente, y otros objetivos como la mantenibilidad, auditabilidad, flexibilidad e interacción con otros sistemas de información
- Es un esquema de trabajo que determina la interacción de diferentes componentes del sistema
- Emerge como parte crucial del proceso de análisis -> Diseño de alto nivel
- Es el resulta de un conjunto de decisiones técnicas y de negocio
- Es la estructura general del sistema
- Es un conjunto de componentes, conectores y restricciones de un programa o sistema, sus interrelaciones y los principios que gobiernan su diseño.
- La arquitectura de software es una forma de representar sistemas complejo mediante el uso de la abstracción.
- Es la organización fundamental de un sistema incorporada en sus componentes en sus relaciones mutuas y el entorno y los principios que guían su diseño y evolución.
- Es importante como disciplina debido a que los ss crecen de tal forma que resulta muy complicado que sean diseñados y especificados solo por un individuo.
- Este campo es estudiado debido al factor humano, debido a las limitaciones de este.

---

### Evolución de las Arquitecturas

Dos factores primarios de la ingeniería de software que han incrementado la importancia de la arquitectura.


| Escala       | Complejidad |
| ------------ | ----------- |
| Distribución | Riesgos     |

> [!info]
> No confundir patrón y diseño arquitectonico

#### Aplicaciones Monolíticas

- Interfaces de usuario (GUI)
- Servicios de presentación, negocio y persistencia en la misma máquina, o en una misma unidad de código.
- Alto acoplamiento entre tiers.

#### Arquitectura Cliente-Servidor

- Clientes pesados, no estándar
- Conexiones dedicadas a DB
- Protocolos Pesados
- Ejecución remota de SQLs
- Alta administración
- Bajo Rendimiento
- Alto tráfico de red

#### Cliente-Servidor Mejorado

- Lógica de negocios en DB
- Clientes pesados, no estándar
- Conexiones dedicadas a la DB
- Mejora en rendimiento
- Alta administración
- Baja escalabilidad
- Baja flexibilidad
- Baja portabilidad

#### Arquitectura de 3 niveles

- Reutilización de lógica de negocio para diferentes clientes o sistemas.
- Mejora la escalabilidad.
- Mejora flexibilidad
- Independencia de la base de datos

#### Arquitectura de N - niveles

- Bajo costo de administración de clientes
- Alta accesibilidad
- Alta flexibilidad
- Alta disponibilidad y tolerancia a fallos
- Alta escalabilidad
- Independencia de DB

### visión de arquitectura orientada a servicios (SOA)

- Heterogeneidad
- Escalabilidad
- Disponibilidad
- Distribución
- Manejabilidad de procesos.
- Administración y monitoreo de procesos, servicios e infraestructura.

### ¿Quién lo hace?

Ingenieros de software/ especialistas

El diseñador de una db crea la arquitectura de los datos para un sistema.

El "arquitecto del sistema" selecciona un estilo arquitectónico apropiado a partir de los requerimientos obtenidos durante el análisis de los datos.


### ¿Qué es un arquitecto de software?

- Rational Unified Process
	- Arquitecto es un rol en un proyecto de desarrollo de software el cual es responsable de:
		- Liderar el proceso de la arquitectura
		- Producir los artefactos necesarios: Documento de descripción de arquitectura.
		- Modelos y prototipos de arquitectura.
	- El arquitecto:
		- Visualiza el comportamiento del sistema.
		- Crea los planos del sistema
		- Define la forma en la cual los elementos del sistema trabajan en conjunto.
		- Responsable de integrar los requerimientos no funcionales (NRFs) en el sistema.
		- Define herramientas, implementación, para requisitos funcionales y no funcionales.


### ¿Qué es la arquitectura de software?

Idea y construye los planos de las aplicaciones y canales digitales para que estos soporten todas las necesidades para los que fueron diseñados. Es la encargada de garantizar que funcione de manera óptima, entregando calidad, disponibilidad y seguridad, entre otros atributos.


### ¿Por qué es importante?

- Es importante comunicar los stakeholders
- Manifiesta el primer conjunto de necesidades de diseño
- Es un abstracción del sistema
- Antes de preocuparse por los detalles, necesitaría tener el panorama general.
- Eso es lo que hace el diseño arquitectónico, da el panorama y asegura que sea correcto.

### Terminología

- Arquitectura: La arquitectura es la organización fundamental de un sistema encarnado en sus componentes, su relación entre sí y con el medio ambiente y los principios que guían su diseño y evolución.
- Arquitecto. El arquitecto es el que obtiene los requisitos de los clientes, da soluciones a los desarrolladores y genera un diseño de la arquitectura.
- Arquitecting: Proceso de la arquitectura del software.
- Sistema: conjunto de componentes que cumplen una función o un conjunto de funciones específicas.
- Descripción de la arquitectura: Es un conjunto de productos que documentan la arquitectura.
- Perspectiva de la arquitectura: Es una representación desde una perspectiva específica de un determinado sistema o de una parte del mismo.
- Punto de vista arquitectónico: es una plantilla que describe la forma de crear y utilizar una perspectiva de la arquitectura. Un punto de vista incluye un nombre, socios, problema más abordados por el punto de vista y el modelado y las convenciones analíticas.

> [!info] Escenarios
> Cada escenario plantea retos condiciones y necesidades diferentes.
> Que herramientas, personas, presupuesto, conocimiento y tiempo necesitamos para cada escenario.
> 

### Beneficios de una Arquitectura de Software

#### Proporciona la comunicación entre Stakeholders (participantes del proyecto)

- Director de la organización de desarrollo
- Mercadeo
- Usuario Final
- Organización del mantenimiento
- Cliente

#### Triangulo de la triple restricción
Se puede hacer, rápido, barato y bueno, pero solo puedes elegir 2.
(la calidad es lo mas importante y no negociable)

- Costos y recursos
- Scope (alcance)
- Time/Schedule

##### Equilibrios detectados

- Alcance - costo tiempo
	- El triángulo esta equilibrado cuando el alcance es igual a la combinación de los costos y el tiempo.
	- Si se quiere aumentar el alcance aumentan las variables de la derecha, que puede ser el tiempo o costo.


### Diagrama de Kiviat - Diagrama de flexibilidad

- Features
- Qualitu
- Staff
- Schedule
- Cost

#### Dimensiones clave

- Funcionalidad
- Personas
- Valor
- Tiempo
- Herramientas
- Procesos 
- Calidad
- Dinero

### Beneficios de una Arquitectura de Software

- Requisitos de calidad
	- Stkaeholders
	- Organizaciones de desarrollo
- Ambiente técnico
- Experiencia del arquitecto

#### Manifiesta las decisiones de diseño tempranamente
- Define restricciones de implementación
- Soporta la estructura organizacional
- Inhibe o activa los atributos de calidad del sistema
- Exhibe los atributos de calidad requeridos
- Facilita el razonar acerca del manejo del cambio
- Ayuda en la evolución del prototipado
- Alcanza más exactitud en estimación de costos y agenda del proyecto.

#### Las arquitecturas como un modelo reusable y transferible
- Las líneas de productos de software comparten una arquitectura en común
- los sistemas se pueden construir usando grandes y extensos elementos de desarrollo
- Menos es más: vocabulario restringido de alternativas de diseño
- Una arquitectura permite desarrollo basado en plantillas
- Una arquitectura puede ser la base para el entrenamiento de nuevos miembros del equipo de desarrollo.

### ¿Dónde debe colocarse la arquitectura en el ciclo de vida del SW?

- Involucra requisitos funcionales y no funcionales
- Es un proceso iterativo a través de requisitos y calidad
- Involucra una gran variedad de stakeholders
- nos permite conocer el primer conjunto de decisiones de diseño, la estructura organizativa, restricciones en la implementación, atributos de calidad.
- Es la abstracción de un sistemas
- La arquitectura del software es el resultado de equilibrar requisitos funcionales y de calidad.
- Se ve afectada por la organización, el entorno y la experiencia.

### ¿Cuáles son los pasos?

- El diseño de la arquitectura comienza con el **diseño de los datos**.
- Continua con la obtención las representaciones de la estructura arquitectónica del sistema.
- Se analizan alternativas de estilos o patrones arquitectónicos.
- Seleccionada la alternativa, se elabora la arquitectura con el empleo de un **método de diseño**.

### ¿Cuál es el producto final?

- Un modelo de arquitectura que incluye datos y la estructura del software.
- Además, se describen las propiedades y relaciones (interacciones) que hay entre los componentes.

### ¿Qué permite?

- Analizar la efectividad del diseño para cumplir los requerimientos establecidos.
- Considerar alternativas arquitectónicas en una etapa en la que hacer cambios al diseño todavía es relativamente fácil.
- Reducir los riesgos asociados con la construcción del software.

### Estructuras arquitectónicas y vistas

Vista es la representación de la estructura.
Estructura es el conjunto de elementos en sí, como es que existen.
Se diseñan estructuras y se documentan vistas de esas estructuras

### Arquitectura 4+1 vistas

#### Vista de procesos
Representan los flujos de trabajo paso a paso del negocio y operacionales de los componentes que conforman el sistema. También va a mostrar algunos de los requisitos no funciónales, como son **ejecución, disponibilidad, tolerancia a fallas, integridad, seguridad, confiablidad entre otros**.

En esta vista vamos a completar con los diagramas de Actividad.

#### Vista 1 o Vista de escenarios
Esta vista es representadas por los casos de uso, que ayudarán a unir las otras cuatro vistas.

Desde un caso de uso podemos ver cómo se van ligando las otras cuatro vistas, con esto tenemos la trazabilidad de componentes, clases, equipo, paquetes, etc. para realización cada caso de uso.

En esta vista vamos a complementar con los diagramas de caso de Uso


#### Vista lógica
Requisitos funcionales del sistema y de lo que el sistema debe de hacer, las funciones y servicios que se han definido.

Enfocada a lo definido como dominio de la aplicación, lo que son las clases y objetos principales que formaran el corazón o "core" de la aplicación.

En esta vista vamos a complementar con los diagramas de caso de Clases, Paquetes

#### Vista de despliegue o Vista de desarrollo

Mostrar básicamente como está dividido nuestro sistema de software en componentes, y muestra las dependencias entre estos componentes.

Componentes físicos, archivos, cabeceras, bibliotecas compartidas, módulos, ejecutables o paquetes.

En esta vista vamos a complementar con los diagramas de caso de componentes, paquetes.

#### Vista física
Representan cómo están distribuidos los componentes entre los distintos equipos que conforman la solución incluyendo los servicios.

En esta vista vamos a complementar con los diagramas de caso de Deployment

### Pasos par ala definición de una Arquitectura de Software

El diseño de la arquitectura incluye:

- Estructura: Descripción de subsistemas como composición de componentes.
- Comportamiento: Descripción de la comunicación entre otros componentes
- Cualquier otra información que el arquitecto considere relevante:
	- Protocolos de comunicación, sincronización ya acceso a datos.
	- Distribución física.
	- Puntos de variabilidad y extensión.
- Puntos de variabilidad y extensión.

### Arquitectura de Software (Flujo de definición)

barras de sincronización, dividen flujos o unen flujos.
actividades se pueden dar de formas paralelas.

primero se definen los drivers 

### Resumen

- La arquitectura de software de un sistema es el conjunto de estructuras necesarias para razonar sobre el sistema, que comprende elementos de software, relaciones entre ellos y propiedades de ambos.
- Una estructura es un conjunto de elementos y las relaciones entre ellos.
- Una vista es una representación de un conjunto coherente de elementos arquitectónicos, según lo escrito y leído por los interesados del sistema, Una vista es una representación de una o más estructuras.

#### Categorías de Estructuras

- Las estructuras de los módulos muestran cómo se debe estructurar un sistema como un conjunto de unidades de código o de datos que se deben construir o adquirir.
- Las estructuras de componentes y conectores muestran cómo se debe estructurar el sistema como un conjunto de elementos que tienen un comportamiento en tiempo de ejecución (componentes) e interacciones (conectores).
- Las estructuras de asignación muestran cómo se relacionará el sistema con las estructuras que no son de software en su entorno (como CPU, sistemas de archivos, redes, equipo de desarrollo, etc.)

### Pasos para la definición de una arquitectura de software

- Creación del caso de negocio para el sistema
- Entendimiento de los requisitos
- Creación y selección de la arquitectura
- Documentación y comunicación de la arquitectura.
- Análisis o evaluación de la arquitectura.
- Implementación del sistema basado en la arquitectura.
- Aseguramiento de que la implementación esté acorde a la arquitectura.

- Requerimientos
- Diseño
- Documentación
- Evaluación
- Implementación



## Partes importantes

> Atributos de calidad importantes, durabilidad, utilidad y encanto.

---

## Conceptos clave

> Drivers RF (Requisitos Funcionales Críticos)

---

## Ejemplos / Práctica


---

## Conexiones con tu conocimiento

> Relaciónalo con cuadernos u otras lecciones

- [[ ]]
    
- [[ ]]
    

---

## Tareas


---

## Resumen final

> Léelo dentro de 1 año y debería bastar para recordar la lección
