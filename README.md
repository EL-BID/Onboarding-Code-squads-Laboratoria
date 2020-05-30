[![Analytics](https://gabeacon.irvinlim.com/UA-168064518-1/ga-beacon/onboarding)](https://github.com/EL-BID/Onboarding-Code-squads-Laboratoria)
# Onboarding: Piloto de colaboración en publicación de herramientas con Laboratoria 

 

## ¿Qué es Código para el Desarrollo? 

Desde el BID promovemos la idea que el software es un producto de conocimiento, y como tal debe ser compartido. Por eso lanzamos Código para el Desarrollo, una iniciativa que sirve como plataforma para compartir recursos y software de código abierto y también conectar las diversas comunidades que apoyan la visión que el software es un bien público. 

 

## ¿Cuál es el objetivo del piloto? 

El objetivo principal es descentralizar el proceso de evaluación de herramientas que se suman al catálogo de la web code.iadb.org.  

Esto con el fin de mejorar la eficiencia en el proceso de publicación y recibir finalmente retroalimentación, reflexiones e ideas del proceso con una perspectiva nueva y fresca.  

Creemos que mientras más abramos nuestro proceso podremos aprender más colaborativamente. 

A su vez, esperamos que para las laboratorians la experiencia de coordinar en interactuar con los equipos dueños de las herramientas sea enriquecedor. 

Cabe señalar que en esta oportunidad solo nos centraremos en repos en español. 


## ¿Cuáles son las etapas o estructura de actividades del piloto? 

* Formación de equipos y repartición de herramientas 

* Interacción con equipos owners en Github 

* Generación de contenido sobre herramientas 

* Reflexiones e ideas. 

* Reconocimientos a laboratorians 

 

## ¿En qué consiste el proceso de publicación de herramientas? 

Las herramientas que se publican en code.iadb.org pasan por 3 etapas: 

* Identificación  

* Evaluación 

* Diseminación 


## ¿Cómo contribuirán las laboratorians en este proceso de publicación? 

A continuación, iremos explicando en qué partes del proceso publicación necesitamos apoyo y cómo abordar la coordinación de actividades de manera ordenada durante las etapas del piloto. 
 

### Formación de equipos y repartición de herramientas: 

Previa coordinación hemos identificado y contactado con los equipos de 10 herramientas candidatas a ser publicadas en code.iadb.org.   

Dependiendo de la cantidad de laboratorians que participen en la piloto haremos la distribución de las herramientas a los equipos que se formarán. 

Máxima cantidad de personas por equipo: 4 a 5 personas 

Mínima cantidad de personas por equipo: 2 personas 

Perfiles de las reviewers: 

###### Perfil Dev  

Contrastará los estándares de documentación y evaluación técnica de nuestra guía y levantarán issues respecto a lo que falte en los repos oficiales de las herramientas. 

https://el-bid.github.io/guia-de-publicacion/ 

###### Perfil UX – STORYTELLING  

Coordinará con el equipo de comunicación de la herramienta para la creación de la vitrina siguiendo el template que ya manejamos y posteriormente también coordinará con Michelle Marshall, editora del Blog Abierto al Público la creación de un blog sobre la herramienta, enfocándose en la historia, impacto y posible reutilización de la misma. 

https://blogs.iadb.org/conocimiento-abierto/es/ 

 

### Interacción con equipos owners en Github 

Para organizarnos en la etapa de evaluación de las herramientas usaremos como canal github, aquí las integrantes del equipo que tienen un perfil dev deberán efectuar tareas según la asignación que se hayan repartido. 

### ¿En qué consiste la evaluación de herramientas? 

En la iniciativa evaluamos a las herramientas bajo tres pilares: 

## Documentación:  

Aunque no existe un formato estándar para abordar la documentación de herramientas de código abierto, pero en nuestra plantilla de repositorio podrán encontrar las secciones necesarias más comunes para disponer de un README.md 

Opcionalmente, esta información puede ir en otros documentos o archivos, pero estos recursos deben estar siempre referenciados en el README.md 

https://github.com/EL-BID/Plantilla-de-repositorio/blob/master/README.md 

###### Lo que las laboratorian con perfil dev tendran que hacer es: 

Revisar que el readme.md del repo público tenga las secciones que detallamos en la guía de publicación. https://el-bid.github.io/guia-de-publicacion/documents/documentacion/ , contamos con una plantilla de README.md para que pueda ser más fácil hacer esta revisión. https://github.com/EL-BID/Plantilla-de-repositorio/blob/master/README.md 

Generar un issue tipo checklist en el repo oficial de la herramienta que está siendo revisada sobre la información faltante en el README.md. En este issue se mencionará también qué parte de lo faltante podrá ser resuelta por la laboratorian, siempre teniendo en cuenta su capacidad para hacerlo. Para que posteriormente se genere un pull request de los puntos que se ofrecieron a resolver. Esto último reafirmamos, NO es obligatorio, pero en caso de que se pueda hacer ya hemos dado aviso a los equipos owners para que estén atentos a las sugerencias. El issue estará clasificado por los owners por los tags help wanted y documentación. 

Si la documentación se encontrase en inglés, también se agregará como un punto en el checklist la traducción de este contenido al español.  

Usar este template de issue de documentación , esto ayudará a que veamos el evance ya que estará tageada la cuenta oficial del banco. 

Conforme vaya avanzando la interacción con los equipos se ira cerrando este issue de documentación, esto puede pasar durante la piloto o posteriomente a la piloto. 

## Evaluación técnica: 

Al igual que la documentación, para la evaluación técnica de herramientas de código abierto no existe un estándar definido, pero bajo la iniciativa hemos identificado factores clave para empezar a evaluar las herramientas que publicamos. Recordemos antes de iniciar que cada herramienta tiene sus propias particularidades y que nos encontramos muy abiertos a recibir retroalimentación en especial en esta parte del proceso de publicación. 

###### Lo que las laboratorian con perfil dev tendran que hacer es: 

Revisar la guía de publicación en la sección de evaluación técnica, allí encontrarán los puntos que consideramos solicitar a los equipos owners de las herramientas. 

https://el-bid.github.io/guia-de-publicacion/documents/evaluacion/ 

Para esta piloto, estamos considerando 1 criterio de evaluación obligatorio y 1 criterio opcional.  

Los cuales son: 

* Reporte de evaluación estática de código  

Será obligatorio que todas las herramientas de la piloto tengan un reporte de evaluación estática de código. Lo ideal en este punto es que el repositorio tenga vinculado un servicio que ofrezca esta opción, para esto, el equipo owner tendrá que registrarse y vincular su cuenta de github con este servicio. Para laboratorians que estén revisando herramientas del BID solo tendrán que contactar con Jesenia Rodríguez para generar el reporte de Sonarcloud ya que el BID ya cuenta con este servicio vinculado. 

Nosotros recomendamos SonarCloud por la baja brecha de aprendizaje que ofrece para empezar a usarlo, pero las dejamos decidir si quisieran recomendar otro servicio similar. 

A continuación, te explicamos como abordar este tema con los equipos owners: 

Generar un issue en el repo dedicado a este punto 

Habiendo observado el repo y haciendo las consultas o dudas que te hayan surgido revisándolo. 

Usar este template de issue de evaluación técnica, esto ayudará a que veamos el evance ya que estará tageada la cuenta oficial del BID. 

 

* Agregar el badge del resultado del reporte en el Readme.md 

La mayoría de los servicios que generan reportes estáticos de evaluación de código a su vez generan el markdown de badges para colocar en los repositorios de las herramientas. De esta forma cualquier persona puede ingresar a ver el reporte generado por el último commit de la herramienta. 

 

* Posibilidad de generar Pull Requests 

Una vez generado el reporte se podrán visualizar diversos problemas con el código, en este momento la laboratorian observará cual de esos problemas estará en capacidad de resolver generando pull requests, recalcamos que esto último no es obligatorio, pero de realizarse ya hemos dado aviso a los equipos owners de tener especial atención a estas contribuciones. 

 

* Herramienta de integración continua de código 

Será opcional que los equipos implementen una herramienta de integración continua de código. 

Recomendamos hacer uso de una herramienta de integración continua de código (recomendamos Travis CI) para visibilizar el estado del build (debe estar en estado passing) en el readme.md dando uso al badge generado por este microservicio. 

Pueden usar cualquier otro microservicio que tenga esa función, a su vez es ideal poder ver el estado del build de manera pública. 

https://docs.travis-ci.com/ 

 

## Licenciamiento: 
 

Si la herramienta fue creada bajo el financiamiento del BID, se presentará la opción de usar la Licencia AM-331-A3, la cual deberá ser agregada en formato markdown en el LICENCE.md 

https://github.com/EL-BID/guia-de-publicacion/blob/master/_documents/pages/licenciabid.markdown 

Si la herramienta fue creada fuera de un financimiento del BID, pueden usar cualquier licencia de código abierto.  

De no tenerla, recomendamos revisar https://choosealicense.com/ 

###### las laboratorian con perfil dev tendran que hacer es: 
* Revisar que el repo tenga una licencia de código abierto.
 


### Generación de contenido sobre herramientas 

En paralelo a la evaluación, las laboratorian con perfil UX interactuarán con los equipos owner, específicamente con personal que ellos hayan designado para la tarea de acompañamiento en generar contenido sobre la herramienta. 

 

* Vitrina en code.iadb.org 

Coordinará con el equipo de comunicación de la herramienta para la creación de la vitrina siguiendo el template que ya manejamos. 


###### Lo que las laboratorian con perfil UX tendrán que hacer es: 
* Gestionar con el equipo owner la creación de este contenido.
* Asegurarse que el contenido de la vitrina sea de utilidad para el público objetivo de la web, los funcionarios públicos de américa latina y el caribe.


Puedes descargarte el template aquí 


* Blog en Abierto Al Público. 

También coordinará con Michelle Marshall, editora del Blog Abierto al Público la creación de un blog sobre la herramienta, enfocándose en la historia, impacto y posible reutilización de la misma.  

https://blogs.iadb.org/conocimiento-abierto/es/ 

Lo que las laboratorian con perfil UX tendrán que hacer es: 
* Generar preguntas evocadoras relacionadas a la reutilización de la herramienta.
* Conversar con el equipo owner sobre el potencial de reutilización y apoyar en plasmar este contenido en el blog.
* Brindar apoyo en la edición del blog, resolviendo dudas con el equipo owner de presentarse el caso.

### Reflexiones e ideas. 

### Reconocimientos a laboratorians 

* Diploma de reconocimiento según expertise técnico para las jóvenes que participaron en el piloto 

* Post en el Blog del BID - Abierto al Público - para compartir la experiencia (grupal) 

* Recomendación en LinkedIn (Por el BID y los equipos de trabajo de las ciudades) 
