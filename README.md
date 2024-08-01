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
