# retoEnClase_Desarrollo_Nube
Reto en clase para puntos extras en examen práctico.

# Lilia A. Padilla Hdez

# Preguntas:
¿Qué tecnología elegiste para el cómputo y por qué?
Yo los manejaria con Lambdas, puesto que quiero manejarlas de forma serverless, ya que es muy sencillo lo que queremos que haga,
y realmente no necesitamos una conexión más robusta, solamente que se creen las tareas, se actualicen o se elimine. 
Así la producción sería más barata y la ganancia podría ser mayor en caso de querer lanzarla al mercado.

¿Qué tecnología elegiste para almacenamiento y por qué?
Debido a que queremos lograr que nuestro sistema de Kanban sea barato y que va a ser usado solo para consultar el estado de las tareas y actualizarlas, 
más que estarlas creando en grandes volumenes, la tecnología de almacenamiento que elegiría sería un S3, son más baratas las consultas y nos cobraría por
el alamacenamiento, que no es mucho, entonces seguiríamos con esta para de mantener la producción barata para una mayos ganancia, y la información no es 
de vida o muerte, por lo que podíamos esperar un poco al recibir la información que necesitamos.

¿Qué tecnologías utilizarías para notificar al usuario que una tarea con estado backlog o doing está próxima a vencer (por ejemplo, al día siguiente)?
Utilizaría el servicio de AWS SNS de publicación-suscripción, de esta forma, programaríamos que a quién se le asigna la tarea se suscriba para que AWS 
le notifique que su tarea esta próxima a expirar, de esta forma, a quién no este suscrito a esa tarea, no se le molestará.
