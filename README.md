Esta es la presentación que hice sobre el estado del diseño en FOSS para UX Spain 2015. La puedes ver en:

http://belenbarrospena.github.io/uxspain2015/

Y este es el guión que seguí:

Muy buenas a tod@s. Me llamo Belén, soy la diseñadora en una cosa que se llama Yocto Project, que es uno de los proyectos colaborativos de la Fundación Linux. 

Como todos los proyectos de la Fundación Linux, Yocto Project es FOSS. FOSS es un acrónimo, el acrónimo que voy a utilizar en esta ponencia de ahora en adelante. El acrónimo significa Free and Open Source Software, software libre y de código abierto. 

Aunque en teoría free y open source software son cosas distintas, lo que nos concierne hoy aquí no es realmente en qué se diferencian, sino lo que tienen en común, que es mucho. Esta es la definición de ‘open source’: “software cuyo código es público, y que cualquiera puede modificar y mejorar”. Y esta es la definición de ‘free software’: “cualquier usuario puede inspeccionar el código, modificarlo y compartirlo”. Como podéis ver, la historia es bastante parecida. 

La otra cosa fundamental en FOSS es ‘peer review’. La RAE tiene una cuenta en Twitter a la que puedes enviar consultas, así que les pregunté cómo traducir ‘peer review’ y me recomendaron: “revisión por pares”. Pues eso: la revisión por pares es la otra característica fundamental del FOSS. Cualquier aplicación FOSS está desarrollada por una comunidad de programadores, que contribuyen código en pequeñas unidades que se llaman ‘patches’. Esto es un patch. Los patches se hacen públicos, con frecuencia en una lista de correo. Todos los que están suscritos pueden revisar los patches, y hacer comentarios o sugerencias para mejorarlos. Así que tus pares revisan tu código. Los patches, una vez revisados, se aceptan y se incorporan al cuerpo del código de la aplicación: a esto lo llaman “merging upstream”. Esto va más allá de simplemente publicar el código: cuando una contribuye a un proyecto FOSS, se compromete además a escuchar las opiniones de otros, a tenerlas en cuenta, y a hacer cambios siguiendo las recomendaciones de tus “pares”.

Y ahora que os he contado lo que es FOSS, os voy a hacer una pregunta. Quién de aquí usa FOSS? Por favor, levantaros para que os veamos… Esto que veis aquí es la percepción que los diseñadores tenemos del mundo del FOSS: FOSS es un porcentaje minoritario del software que existe, usado por una minoría.

Dejadme que os haga otra pregunta: quién aquí usa Internet? Levantaros para que os veamos. 

Y esto que veis aquí es la realidad del FOSS. Cualquier persona que usa Internet usa FOSS. Y no me refiero a los protocolos estándares como TCP/IP o las tecnologías HTML, CSS y JavaScript. No, no: los navegadores que utilizáis, están basados en rendering engines que son FOSS. Las páginas web que visitáis, están servidas por servidores manejados con FOSS, que viven en data centers gestionados con FOSS, a los que os conectáis con routers cuyo sistema operativo está basado en FOSS. Es más: cada vez que cruzáis un semáforo, cada vez que cogéis un ascensor, cada vez que imprimís un documento, cada vez que pagáis un parking, estáis utilizando FOSS, porque un gran porcentaje de la informática embebida está basada en el kernel de Linux que es … FOSS.

Y éste es uno de los problemas que tiene el FOSS: que cualquier parecido entre la percepción que tenemos de él y la realidad es pura coincidencia. El FOSS está rodeado de mitos. Y si me lo permitís, hoy voy a intentar desbancar algunos de los otros mitos que rodean al FOSS. No todos: sólo cinco de ellos. Hay más, pero hoy sólo me da tiempo a hacer cinco. 

Mito número uno: FOSS no usa interfaces gráficas. Circula por ahí esta idea de que todo el FOSS es software que nunca interactúa directamente con los usuarios: librerías, compiladores y cosas como el kernel que forman parte de la infraestructura de la tecnología, las cañerías de la informática; las cosas que usan los programadores con terminales de texto. Igual esto fue cierto en algún momento, pero realmente ya no lo es. Los programadores jovenzuelos (y no tan jovenzuelos) están acostumbrados a interfaces gráficas, y demandan el mismo tipo de interacción para sus herramientas. Prácticamente todo lo que os podáis imaginar, incluso las cosas más técnicas y que nos parecen más esotéricas, tienden a presentar una interfaz gráfica. Aquí os pongo un ejemplo: los build systems, que son herramientas para automatizar el proceso de compilación, y que son con lo que construimos nuestros sistemas operativos, tienen interfaces gráficas. No sólo eso: los tiempos del FOSS ocupándose sólo de las “cañerías” están llegando a su fin. Para muestra un botón. Ésta es la lista de los 8 sistemas operativos móviles en el mercado ahora mismo. De esos 8, nada menos que 5 se autodeclaran “Open Source”, entre ellos el que tiene prácticamente todo el mercado (Android), y los 4 más recientes: FirefoxOS, Sailfish, Tizen y Ubuntu Touch. Por supuesto, todos ellos tienen una interfaz gráfica, y todos ellos interactúan directamente con el usuario de a pie. 

Así que la idea de que FOSS no usa interfaces gráficas no es cierta: las interfaces gráficas son un componente fundamental y juegan un papel importantísimo en todo el software, incluido el FOSS. 

Mito número dos: todo el FOSS es feo e imposible de utilizar. Como los antropólogos os pueden explicar, los mitos tienen cierta conexión con la realidad. Y en el caso de este mito, pues es cierto. Hay mucho feísmo en FOSS. Más que feísmo, a mí me gusta llamarlo ‘brutalismo’. El brutalismo es un estilo arquitectónico super abundante en el Reino Unido. Aquí en Salamanca no hay mucho, pero en Inglaterra… brutalismo a punta pala! Ésta es la estación de autobuses de Preston, uno de los ejemplos más famosos de brutalismo. Para mí, las interfaces del FOSS son al software lo que el brutalismo es a la arquitectura, porque aunque la fachada nos pueda gustar o no, la realidad es que el edificio es sólido, es práctico, y está bien construido. Y esto es lo que le pasa al FOSS también: que aunque la interfaz sea fea como un demonio, el software que está detrás de ella es sólido, está bien diseñado desde el punto de vista técnico, y además es la mar de útil. Pero dejadme que os muestre algunos ejemplos de brutalismo en FOSS. 

Bugzilla, para la gestión de defectos: feo como el sólo. Cortesía de Mozilla, los mismos que hacen el navegador Firefox. 

Gerrit, una interfaz web para la revisión de código, patrocinado por Google, sí, sí, el mismo Google que hace vuestro precioso teléfono Android. 

Y mi favorito últimamente: menuconfig, la herramienta para configurar el kernel de Linux. Los que configuran el kernel son unos santos.

Pero deducir de estos ejemplos que TODO el FOSS es feo es una exageración. Firefox, el navegador de Mozilla, no sólo no es feo, sino que ha sido pionero en muchos de los patrones de diseño que ahora consideramos estándar en nuestros navegadores.

Sparkleshare, una alternativa a Dropbox.

MailPile, un aplicación segura de email que incorpora criptografía.

OwnCloud, otra alternativa a Dropbox.

Así que, aunque sí hay brutalismo en FOSS, no es cierto que todo el FOSS sea feo. Ni mucho menos. 

Mito número tres: los programadores involucrados en FOSS odian a los diseñadores. Si acordamos antes que los mitos tienen siempre algún tipo de conexión con la realidad, entonces esto no es un mito: es una mentira como una catedral. Lo programadores involucrados en FOSS *NO* odian a los diseñadores, que quede claro. Y no es que lo diga yo, es que lo dice la investigación científica. Esta gente de la Universidad de Oulu hizo un experimento con sus alumnos: como parte del trabajo práctico del curso, les pidieron que colaboraran con un estudio de usabilidad a un proyecto FOSS de su elección. El experimento concluyó lo siguiente (lo he puesto en versión original sin subtítulos, así que lo traduzco): “la comunidad aceptó a los expertos en usabilidad como a cualquier otro dispuesto a contribuir de alguna forma (…) Los programadores dijeron que agradecerían más ayuda en usabilidad y especialmente, la incorporación de un experto en usabilidad al equipo.” 

De verdad de la buena que los programadores en FOSS no os odian: esta buena gente tiene cosas más importantes que hacer que ir por la vida odiando diseñadores.

Mito número cuatro: FOSS es todo super técnico, y yo de esas cosas no me entero. Pues sí, que le vamos a hacer: muchos proyectos FOSS son la mar de técnicos. Pero es que tiene sentido, porque muchas de las iniciativas consisten en desarrollar y mejorar herramientas de software. Yo lidio con cosas como ésta continuamente. 

Pero no TODOS los proyectos FOSS son técnicos o son herramientas para programadores. Algunos son juegos; otros son interfaces para sistemas operativos; otros son editores de documentos; o CMSs para democratizar la creación de contenido web. Los hay que son mercados de aplicaciones open source para Android, y servicios que te permiten comunicarte en privado con tu móvil. Entre los cientos y cientos y cientos de proyectos FOSS, hay cosas para todos los gustos. 

Y mito número cinco (que he dejado para el final, porque éste es mi favorito): no hay diseñadores en FOSS. Para desbancar éste, yo misma hice un experimento. En septiembre del año pasado mandé una propuesta a FOSDEM, que es un congreso muy grande que tiene lugar todos los años en Bruselas el primer fin de semana de febrero, y donde se reúne un mogollón de gente que contribuye a proyectos FOSS. La propuesta, que aceptaron, consistía en organizar un día entero de seminarios sobre diseño en FOSS. Con la ayuda de otros diseñadores que o bien trabajan en o contribuyen a FOSS, solicitamos propuestas para ponencias, elegimos las mejores, las pusimos en la página web de FOSDEM, y nos fuimos a Bruselas… a verlas venir. Era la primera vez en la historia de FOSDEM que había un día entero sobre diseño, así que no teníamos ni idea de lo que iba a pasar. 

Pues esto es lo que pasó: hasta la bandera. Tuvimos que dejar a gente fuera, porque había personas de pie, sentadas en la escaleras, en las esquinas, por todas partes. Yo creo que ninguno de los que organizamos esto nos esperábamos esta respuesta. Hay diseñadores en FOSS, Por supuesto que sí. Lo que pasa es que no se mueven en los mismos circuitos en los que nos movemos nosotros. 

Pero aunque los hay, los que somos no llegamos. Nos faltan manos, cabezas, pies, horas: nos falta de todo. Una de las cosas que me pasó durante FOSDEM es que vino muchísima gente a decirme: Belén, yo soy programador, tengo este proyecto que hace esto y esto, pero necesito a alguien que me ayude a diseñar la interfaz. Y el problema es que no encuentro a nadie. Dónde están los diseñadores dispuestos a contribuir? Dónde os juntáis? Hay algún sitio donde pueda publicar un anuncio?

En febrero, cuando me preguntaban esto, yo no tenía donde mandarles. Afortunadamente, las cosas han cambiado desde entonces. Un grupo de diseñadores y desarrolladores ha cogido el toro por los cuernos y ahora tenemos: un repositorio en GitHub, una página web (muy humilde por el momento, pero algo es algo), una cuenta en Twitter, un canal en IRC, y muchas, muchas ganas de llenar el vacío que los diseñadores hemos estado dejando hasta ahora en el mundo del FOSS.

Si os apetece subiros al carro, y ayudar a la comunidad FOSS a solucionar algunos de los problemas más peliagudos que existen en software hoy en día, como hacer la criptografía accesible a todo hijo de vecino; o ayudar a mantener la información sobre nuestras actividades privada y anónima; o ayudar a crear alternativas a los servicios comerciales, ya sabéis dónde estamos. 

Muchas gracias. 
