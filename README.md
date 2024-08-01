


# Project For Startup
## Description
It is a project based on the use of machine learning through the sklearn library, in order to be able to relate a certain number of tenants within the same studio apartment, this is done in order to improve coexistence between the occupants.

The code is based on analyzing an excel database which contains certain behaviors such as:

    • schedule: Indicates the time of day in which the person performs the mentioned activities. It can be categorized into different time slots such as morning, afternoon, night, etc.
    • biorhythm: Describes the physical, emotional or intellectual state of a person at a given time. It can be based on biorhythm cycles that measure variations in these aspects over time.
    • educational_level: Level of education achieved by the person. It can include categories such as primary, secondary, university, postgraduate, etc.
    • reading: Indicates whether the person has the habit of reading and how often they do so. It could be categorized into options such as never, occasionally, frequently, daily, etc.
    • animation: The person's preference for watching animated films or series. It can indicate whether they like it and how often they consume this type of content.
    • cinema: The person's preference for going to the cinema or watching films in general. It can reflect the frequency with which they do this activity.
    • pets: Information on whether the person has pets, and if so, what type of pets (dogs, cats, birds, etc.).
    • cooking: Indicates whether the person likes to cook and how often they do so. It could be categorized into options such as never, occasionally, frequently, daily, etc.
    • sport: The person's participation in sports activities. It can reflect how often they practice sports and the type of sports they prefer.
    • diet: Type of diet the person follows. It can include options such as omnivorous, vegetarian, vegan, among others.
    • smoker: Indicates whether the person smokes and how often. It can be categorized into options such as never, occasionally, regularly, daily, etc.
    • visits: Frequency with which the person receives visitors at home or visits others. It could be categorized into options such as never, occasionally, frequently, weekly, etc.
    • order: Level of order and organization that the person maintains in their daily life or in their environment. It can be a scale from messy to very organized.
    • music_type: Type of music that the person prefers. It can include genres such as pop, rock, classical, jazz, electronic, among others.
    • loud_music: Indicates whether the person likes to listen to loud music. It can be categorized into options such as never, occasionally, frequently, always, etc.
    • perfect_plan: Description of the ideal or perfect plan according to the person. It can be an open answer or be categorized into different types of activities.
    • instrument: Information on whether the person plays any musical instrument and, if so, which instrument(s).

The idea is that each of these columns is analyzed as vectors using a likelihood matrix, taking as a premise that each taste of each possible new tenant counts as a vector of its own, which can be more or less similar to the vectors (tastes) of other tenants.

<p style="color:red;"> Note: </p>   the data is in the attached excel

# Spanish version

# Proyecto Para Starup

## Descripción

Es un proyecto basado en el uso de machine learnign mediante la librería sklearn, con el fin de poder relacionar cierto numero de inquilinos dentro de un mismo aparta estudio, esto se hace con el fin de mejorar la convivencia  entre los ocupantes.

El código se fundamenta en analizar una base de datos en excel la cual contiene ciertos comportamientos como:

    • horario: Indica el momento del día en el que la persona realiza las actividades mencionadas. Puede estar categorizado en diferentes franjas horarias como mañana, tarde, noche, etc.
    • bioritmo: Describe el estado físico, emocional o intelectual de una persona en un momento determinado. Puede estar basado en ciclos de biorritmo que miden variaciones en estos aspectos a lo largo del tiempo.
    • nivel_educativo: Nivel de educación alcanzado por la persona. Puede incluir categorías como primaria, secundaria, universidad, posgrado, etc.
    • leer: Indica si la persona tiene el hábito de leer y con qué frecuencia lo hace. Podría estar categorizado en opciones como nunca, ocasionalmente, frecuentemente, diariamente, etc.
    • animacion: Preferencia de la persona por ver películas o series de animación. Puede indicar si le gusta y con qué frecuencia consume este tipo de contenido.
    • cine: Preferencia de la persona por ir al cine o ver películas en general. Puede reflejar la frecuencia con la que realiza esta actividad.
    • mascotas: Información sobre si la persona tiene mascotas, y en caso afirmativo, qué tipo de mascotas (perros, gatos, aves, etc.).
    • cocinar: Indica si a la persona le gusta cocinar y con qué frecuencia lo hace. Podría estar categorizado en opciones como nunca, ocasionalmente, frecuentemente, diariamente, etc.
    • deporte: Participación de la persona en actividades deportivas. Puede reflejar la frecuencia con la que practica deportes y el tipo de deportes que prefiere.
    • dieta: Tipo de dieta que sigue la persona. Puede incluir opciones como omnívora, vegetariana, vegana, entre otras.
    • fumador: Indica si la persona fuma y con qué frecuencia. Puede estar categorizado en opciones como nunca, ocasionalmente, regularmente, diariamente, etc.
    • visitas: Frecuencia con la que la persona recibe visitas en su casa o visita a otros. Podría estar categorizado en opciones como nunca, ocasionalmente, frecuentemente, semanalmente, etc.
    • orden: Nivel de orden y organización que la persona mantiene en su vida diaria o en su entorno. Puede ser una escala de desordenado a muy ordenado.
    • musica_tipo: Tipo de música que la persona prefiere. Puede incluir géneros como pop, rock, clásica, jazz, electrónica, entre otros.
    • musica_alta: Indica si a la persona le gusta escuchar música a alto volumen. Puede estar categorizado en opciones como nunca, ocasionalmente, frecuentemente, siempre, etc.
    • plan_perfecto: Descripción del plan ideal o perfecto según la persona. Puede ser una respuesta abierta o estar categorizado en diferentes tipos de actividades.
    • instrumento: Información sobre si la persona toca algún instrumento musical y, en caso afirmativo, qué instrumento(s).


La idea es que cada una de esas columnas sean analizadas como vectores mediante una matriz de verosimilitud, esto tomando como premisa de que cada gusto de cada posible nuevo inquilino cuenta como un vector propio, el cual puede ser mas o menos similar a los vectores (gustos) de otros inquilino.

<p style="color:red;"> Nota: </p>  los datos se encuentran en el excel adjunto
