
# PARTE I: Mi Experiencia UX

## 1. Fundamentos Teóricos

El análisis y trabajo desarrollado durante esta asignatura de Diseño de Interfaces de Usuario (DIU) y Experiencia de Usuario (UX) ha supuesto un cambio estructural en mi forma de analizar y construir software. He llegado a comprender, a través de la experimentación práctica y el profundo análisis teórico, que una aplicación técnicamente impecable en su código o arquitectura backend carece de valor real en el mercado si el usuario final experimenta confusión o frustración al intentar interactuar con ella.

Mi evolución ha ido desde un enfoque de "diseño basado en suposiciones o intuición puramente estética" hacia una metodología de "diseño basado en evidencias, normativas y datos". Comprender la **historia de los sistemas interactivos y la evolución de los sistemas de manipulación persona-ordenador** durante los seminarios teóricos fue el primer paso para este cambio. A través de la conceptualización, el diseño arquitectónico, el prototipado de alta fidelidad y la evaluación de nuestro proyecto principal, **Cyber-Gourmet**, he adquirido un grado de madurez analítica que me permite evaluar interfaces de forma mucho más técnica.

## 2. Actividades de Clase y Seminarios Teóricos

El trabajo realizado en los seminarios y ejercicios de teoría sentó las bases de mis contribuciones.

* **Características del Diseño y UX:** En las actividades sobre la experiencia del usuario, aporté reflexiones sobre cómo la estética no debe comprometer la funcionalidad. Estudiar las características fundamentales del diseño me permitió defender que la inmersión temática debía tener límites claros para no salirse de los modelos mentales preexistentes de los usuarios.
* **Patrones y Tareas de Interacción:** Durante el análisis de elementos de diseño de IU y diseño web, me centré en la identificación de patrones de interacción estandarizados (como los carruseles, los menús hamburguesa o los *breadcrumbs*). Esto fue vital para justificar posteriormente por qué decidimos alterar algunos de estos patrones y mantener otros intactos.
* **Accesibilidad (Normativas, Pautas y Guías de Estilo):** Abordar las normativas y pautas (como las WCAG) en clase me proporcionó las herramientas y argumentos técnicos necesarios para implementar contrastes de color, tamaños de tipografía y jerarquías legibles.

## 3. Fase de Investigación y Definición: Empatía y UX Research

El primer desafío en mi experiencia práctica UX fue interiorizar lo siguiente: "el equipo de diseño no es el usuario". Tuve que realizar un esfuerzo analítico y empático consciente para alejarme de mis preferencias tecnológicas avanzadas y conectar verdaderamente con el público objetivo general.

### Análisis Competitivo

Para entender el entorno real de las aplicaciones del sector de mi proyecto práctico, comenzamos realizando un análisis competitivo exhaustivo. Esta fase fue imprescindible para identificar no solo las fortalezas operativas de los competidores directos, sino, de manera crítica, sus brechas de usabilidad. Detectamos patrones problemáticos recurrentes: procesos de *checkout* (pago) excesivamente largos que fomentaban el abandono del carrito, arquitecturas de la información confusas donde los alérgenos o las opciones de personalización eran confusos o poco visibles, y una importante falta de accesibilidad visual.

### Creación de Arquetipos: User Personas y Empathy Maps

Para materializar a nuestros usuarios, desarrollamos *User Personas* y *Empathy Maps* detallados. Definir arquetipos con necesidades, contextos de uso y niveles de competencia digital dispares me enseñó que el diseño debe ser inherentemente inclusivo y anticiparse al error humano. Entendí que no es lo mismo diseñar un flujo de navegación para un usuario joven, nativo digital e impulsivo, que para un perfil de mayor edad, con menor experiencia tecnológica, que necesita confirmaciones u otras adaptaciones constantes.

Además, la elaboración de los *User Journey Maps* me permitió trazar de forma visual y cronológica los puntos de contacto del usuario con nuestro servicio. Entendí que la Experiencia de Usuario no empieza cuando la pantalla se enciende, sino en la psicología del usuario, en la motivación que le lleva a buscar comida y en la satisfacción posterior al recibirla.

No solo he aprendido sobre diseño y usuarios sino también sobre documentación y trabajo colaborativo. Utilizamos diagramas estructurados y volcamos todo el progreso en repositorios de **GitHub**, manteniendo la la información organizada, versionada y colaborativa.

## 4. Ideación, Arquitectura de la Información y Prototipado UI

### Diseño Visual, Sistemas de Diseño y Accesibilidad

En esta fase constructiva, la herramienta principal de trabajo fue **Figma**. Mi dominio de Figma creció de manera exponencial al obligarme a aplicar buenas prácticas de diseño de interfaces modernas entrando en la verdadera maquetación digital.
Antes de comenzar a prototipar las pantallas finales, definimos de manera estricta una guía de estilos visuales (*Guidelines* y *Moodboard*). Establecimos una paleta de colores fundamentada en un "Modo Oscuro" permanente, utilizando fondos muy oscuros o negros puros, con alto contraste de colores. Aquí tuve que aplicar conocimientos de accesibilidad visual, iterando sobre los tonos exactos para asegurar que el contraste entre el texto luminoso y el fondo oscuro superara los ratios mínimos exigidos por las normativas de accesibilidad (WCAG).

### Prototipado de Alta Fidelidad y Diseño Responsivo

Utilizamos Figma no solo como herramienta de representación gráfica, sino como una plataforma de estructuración lógica. Aprendí y apliqué extensamente el uso de *Auto-layout* y la creación de Componentes y Variantes (metodología cercana al *Atomic Design*). Esto era fundamental para garantizar que el diseño fuera verdaderamente responsivo, permitiendo que las tarjetas de productos, los botones y los formularios se adaptaran de manera matemática y fluida a distintas resoluciones, manteniendo siempre la jerarquía visual sin importar el tamaño de la pantalla.


## 5. Evaluación, Métricas y Pruebas Reales con Usuarios (User Testing)

La asimilación de la teoría de **Evaluación y User Testing** me proporcionó una lección: un diseño nunca está verdaderamente terminado, hasta que sobrevive de forma exitosa al contacto no guiado con usuarios reales en un entorno de pruebas.

### Diseño del Plan de Pruebas y Estrategia de Reclutamiento

Para evaluar empíricamente la viabilidad de mi proyecto y compararla de manera objetiva frente a la propuesta desarrollada por otros compañeros, diseñamos un estudio de usabilidad comparativo entre-sujetos. Seleccionamos cuidadosamente a perfiles muy variados: desde usuarios jóvenes con experiencia TIC y perfiles visuales, hasta usuarios de mayor edad con baja competencia digital, impacientes o cautelosos.


### El Cuestionario SUS y herramientas

Tras la finalización de las pruebas prácticas de navegación, administramos el **System Usability Scale (SUS)**.

Nos permitió identificar que nuestro caso, a pesar de ser innegablemente más llamativo e impactante a nivel visual, obtuvo puntuaciones considerablemente más bajas. Las pruebas de campo evidenciaron que la terminología temática ("Hackear Pedido") y la alta densidad de estímulos visuales simultáneos generaban una fricción peligrosa justo en el momento más crítico: el pago. Usuarios orientados a la tarea rápida se sentían abrumados o confundidos por las etiquetas poco convencionales.

### Aproximación a Herramientas Biométricas: Eye Tracking

Investigé y preparé la aplicación de Eye Tracking. El objetivo teórico era obtener mapas de calor (*Heatmaps*) precisos sobre nuestros CTAs principales. El simple ejercicio de diseñar la interfaz y las tareas asumiendo cómo el ojo humano escanea instintivamente una pantalla ha reprogramado por completo mi concepción sobre cómo estructurar la jerarquía visual de cualquier proyecto futuro.

## 6. Autovaloración Justificada del Grado de Experiencia Adquirido

Al concluir este recorrido formativo, mi autovaloración respecto al grado de experiencia adquirido en las áreas de UI/UX y Usabilidad es positiva y se sitúa en un nivel **intermedio-avanzado**.

Me baso en los siguientes elementos logrados a lo largo del curso:

1. **Conociiento estético:** He superado la barrera inicial del desarrollador/diseñador novato que asume que "si funciona y se ve bien, es correcto". He interiorizado que la verdadera calidad reside en la métrica y en la respuesta del usuario, no en mi propia percepción de la interfaz. Mi capacidad para aceptar que "Cyber-Gourmet" fallaba en usabilidad frente a un diseño más simple demuestra madurez analítica.
2. **Dominio técnico:** No solo conozco la teoría, sino que he demostrado capacidad para implementarla. Sé cómo levantar un sistema de diseño estructurado en Figma, y tengo destreza en el uso de repositorios (GitHub) para documentar el proceso de UX Research, acercándome a los estándares reales de la industria.
3. **Capacidad de auditoría:** Me considero plenamente capaz de enfrentarme a un producto digital existente, auditarlo bajo los 10 principios heurísticos de Nielsen, someterlo a pruebas de *A/B testing* o administrar un formulario SUS, e interpretar esos datos estadísticos para redactar un informe de mejoras accionables y justificadas.

## 7. Competencias Adquiridas

A lo largo del desarrollo de este caso de estudio y de las prácticas asociadas, he consolidado una serie de competencias fundamentales:

* **Gestión y planificación de proyectos de diseño:** Capacidad para planificar y desarrollar proyectos interactivos siguiendo una metodología estricta centrada en el usuario, estructurando la información de manera lógica y gestionando de forma incremental cada fase del ciclo de vida del producto.
* **Diseño y aseguramiento de la usabilidad y accesibilidad:** Habilidad técnica y creativa para diseñar, prototipar y evaluar interfaces de usuario, aplicando sistemas de diseño, patrones de interacción y directrices de adaptación en base a normativas reales.
* **Evaluación científica de interfaces y analítica de datos:** Destreza en la realización de estudios, mediciones y valoraciones de la experiencia de usuario (*User Testing*), planificando pruebas con usuarios reales a través de guiones de tareas y analizando métricas de satisfacción y datos demográficos mediante herramientas estandarizadas (SUS).
* **Toma de decisiones objetivas basada en evidencias:** Capacidad analítica para tomar decisiones arquitectónicas y de interfaz fundamentadas en criterios y datos empíricos extraídos de las pruebas de usabilidad, sabiendo interpretar las métricas objetivas frente a las suposiciones iniciales.
* **Dominio de herramientas profesionales:** Fluidez en el uso y aplicación práctica de las tecnologías orientadas al prototipado interactivo de alta fidelidad (Figma), la recolección de datos y el control de versiones, buscando siempre el rigor técnico y la mejora continua de la calidad del software.
* **Resolución de problemas con iniciativa y creatividad:** Autonomía para resolver problemas complejos de interacción, logrando comprender la frontera entre plantear una propuesta de valor de fuerte identidad visual y la obligación ética y técnica de mantener una interfaz clara, intuitiva y libre de retos cognitivos para el usuario final.
* **Comunicación técnica e informes de experto:** Aptitud madurada para elaborar informes de usabilidad objetivos, estructurar análisis y comunicar de forma técnica las conclusiones de diseño, traduciendo las debilidades detectadas en la capa de presentación en recomendaciones de mejora e ingeniería accionables.
