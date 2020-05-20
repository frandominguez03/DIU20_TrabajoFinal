# Trabajo Final de Diseño de Interfaces de Usuario
**Descripción:** En este repositorio se expone todo el contenido relativo a la realización del trabajo final de la asignatura Diseño de Interfaces de Usuario del grado en Ingeniería Informática de la Universidad de Granada (2020).

**Autor:** Francisco Domínguez Lorente

**Supuesto práctico:** Dentro de las dos opciones propuestas, he decidido seleccionar [erranT](https://www.errant.es/). Personalmente he identificado ciertos problemas que podría tratar en torno a esta plataforma. La idea es rediseñar o enfocar de manera diferente el diseño actual de una página de coworking.

-----

# 1. Fase de Análisis
## 1.1 Análisis Competitivo
Una manera inteligente de empezar el rediseño de ErranT es compararla directamente con la otra opción que se nos proporcionaba. Esta opción también es una página de coworking y se llama [Cubikate](https://cubikate.es/). Vamos a analizar cada página por separado y a listar las cosas buenas y malas de cada alternativa, para ver desde un punto de vista de ErranT qué podemos mejorar con respecto a uno de nuestros competidores directos.

Primeramente nada más entrar en cada una de las dos páginas nos encontramos lo siguiente:

* erranT nos redirige a la página en inglés, a pesar de que el dominio es *.es*. Si queremos cambiar de idioma al español, tenemos que pulsar sobre el botón de cambio de idioma
* erranT pese a soportar dos idiomas, las versiones de la página en ambos idiomas varía en la página pricipal y en algunos elementos de otras páginas
* erranT no ofrece una versión en inglés de su blog, sin embargo en la página principal en inglés hay un botón que redirige a una página, supuestamente el blog que no se encuentra
* erranT hace incómoda la navegación a diferencia de Cubikate. Cubikate mantiene el menú en la parte superior de la página, para evitar tener que subir hasta arriba de la página si queremos movernos por el sitio
* Cubikate no ofrece posibilidad de traducir la página a otro idioma
* erranT no ofrece información sobre qué es el coworking, mientras que Cubikate sí. Está asumiendo que todo el público que entra a su página sabe a cerca del coworking y de lo que implica
* Ambas páginas son responsive, se adaptan bien a cualquier dispositivo, aunque se podría mejorar el diseño

## 1.2 Personas
Para ilustrar las necesidades que suelen tener los consumidores de espacios de coworking he creado una persona ficticia, John Redstone.
John es un emprendedor autónomo que quiere comenzar a llevar a la realidad sus proyectos pero que aún no tiene la financiación ni la independencia suficiente como para tener empleados a su cargo, ni tener una oficina sólo para su negocio.

John se pone como un ejemplo de persona que podría estar interesada en estos servicios. Una persona de mediana edad, entre los 25 y 40 años de edad, con estudios en el sector tecnológico o administrativo y con grandes ideas para emprender.

Es importante destacar que esta persona no tiene por qué ser española, puede ser de cualquier nacionalidad, aunque preferiblemente debería tener conocimientos de inglés para poder comunicarse con el resto de compañeros de la oficina.

Él mismo se encarga de gestionar sus perfiles en las redes sociales por ahora, así como de todas las gestiones relacionadas con los proyectos que recibe. A continuación se puede ver una imagen de la persona.

![John_preview](https://github.com/frandominguez03/DIU20_TrabajoFinal/blob/master/img/John_preview.png)

Esta persona se ha diseñado utilizando la herramienta online [HubSpot](https://www.hubspot.es/).

El documento en formato PDF completo está disponibles pulsando [aquí](https://github.com/frandominguez03/DIU20_TrabajoFinal/blob/master/Documentos/John%20Redstone.pdf).

No queremos tampoco dejar de lado el perfil de las PYMES. Las pequeñas y medianas empresas también usan los espacios de coworking y están interesadas en esos servicios. A diferencia de los autónomos, en las PYMES normalmente ya suele haber algún empleado con cierto reparto de tareas y también cierta jerarquía en cuanto a toma de decisiones y gestión de los proyectos.

## 1.3 Metas y puntos a evitar de los usuarios
En la Práctica 2 de la asignatura tuvimos la ocasión de leer un análisis real, el análisis de [MuseMap](https://blog.prototypr.io/musemap-street-art-app-ux-case-study-9bec6a99823b). En este análisis se destacaban las metan y las debilidades de los usuarios *(obtenidas a través del punto anterior)* a la hora de querer usar una aplicación. Estimo oportuno hacer este análisis para tener en cuenta los puntos más relevantes a la hora de rediseñar la aplicación.

### Metas
* Los usuarios quieren obtener información sobre coworking. ¿Qué es? ¿Por qué lo necesito?
* Los usuarios quieren saber la localización precisa de las oficinas que se ofrecen y de cómo se puede llegar a ellas *(transporte público, parking en los alrededores)*
* Los usuarios quieren tener la posibilidad de alquilar un espacio independientemente del idioma
* Los usuarios quieren obtener información precisa sobre tarifas y precios
* Los usuarios quieren obtener información nformación precisa sobre las comodidades que se ofrecen en el espacio de coworking

### Puntos a evitar
* Los usuarios no quieren un ambiente de trabajo molesto, pretenden poder trabajar a gusto en las instalaciones
* Los usuarios quieren tener una conexión a internet estable y continua
* Los usuarios deben de poder disponer de espacios tranquilos y aislados para hacer reuniones con posibles clientes

## 1.4 Usability Review
* **Enlace al documento:** [PDF](https://github.com/frandominguez03/DIU20_TrabajoFinal/blob/master/Documentos/UsabilityReview_erranT.pdf)/[Excel](https://github.com/frandominguez03/DIU20_TrabajoFinal/blob/master/Documentos/UsabilityReview_erranT.xlsx)
* **Valoración final:** 74/100
* **Comentario sobre la valoración:** En general lo que le falla a erranT es tener una navegación más clara y accesible. El menú desaparece conforme bajas en la página y se hace poco dinámico alcanzarlo de nuevo tanto desde móvil como desde ordenador. El mapa que se muestra tampoco ayuda mucho, ya que es una imagen muy reducida, con algo de mala calidad y sin contexto. Las versiones en español e inglés tienen ciertas discrepancias e inconsistencias que deberían ser arregladas.
