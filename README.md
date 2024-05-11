### Práctica integradora. REST API + SQL DB

Tutora: Laura Acuña

- Objetivo: Crear una REST API que permita realizar operaciones CRUD sobre una base de datos SQL. El proyecto será desarrollado en NodeJs con typescript y express. Como base de datos se utilizará PostgreSQL en la nube (ElephantSQL). Como ORM se utilizará Sequelize.

### Paso a paso:

1. Crear un repositorio público en GitHub llamado "pizzeria-ada".
2. Clonar el repositorio en la computadora local.
3. Crear un proyecto de NodeJs con typescript. Levantar un servidor express en el puerto 3000. Instalar todas las dependencias necesarias.
4. Crear una base de datos en PostgreSQL en la nube (ElephantSQL).
5. Establecer una conexión a la base de datos creada desde el proyecto de NodeJs.
6. Organizar la estructura de carpetas del proyecto. Crear una carpeta "src" y dentro de ella crear las carpetas "config", "routes", "controllers", "services", "repositories", "models" y nuestro archivo de entrada de la aplicación: app.ts.
7. Agregar el archivo .env con las variables de entorno necesarias para la conexión a la base de datos.

### Requerimientos:

1. Crear los modelos correspondientes a las tablas de la base de datos.
   <img src="">
2. Respecto a las pizzas debemos poder:
   - Crear una pizza
   - Listar todas las pizzas
   - Obtener una pizza por id
   - Actualizar una pizza
   - Eliminar una pizza
3. Respecto a las Ordenes debemos poder:

   - Crear una orden
   - Listar todas las ordenes
   - Obtener una orden por id
   - Actualizar una orden
   - Eliminar una orden

4. Funcionalidades extra - Opcionales:

   - Buscar una pizza por su nombre
   - Listar las pizzas de la más cara a la más barata
   - Listar solo las pizzas vegetarianas
   - Listar solo las pizzas que tengan un ingrediente específico (Pej: "Peperoni")
   - Listar las ordenes de un cliente específico
   - Listar las ordenes creadas hoy
   - Listar las ordenes de este ultimo mes.

### Autoevaluación

Al final de la práctica, cada estudiante deberá autoevaluarse en los siguientes ítems:

1. ¿Logré ver todas las clases de la semana?
2. ¿Logré completar la práctica?
3. ¿Qué dificultades tuve?
4. ¿Pude traer preguntas para la clase de consultas?
5. Del 1 al 10 cuanto es mi compromiso con la cursada ésta semana? ¿Por qué?
6. Del 1 al 10 cuanto es mi compromiso con la cursada en general? ¿Por qué?
7. ¿Qué puedo hacer para mejorar mi compromiso con la cursada?
8. Del 1 al 10 qué tan útil fue la clase de consultas para mi aprendizaje? ¿Cómo podría mejorar la experiencia?

Por otro lado, cada estudiante podrá responder a las siguientes preguntas:

1. ¿Cuál es el punto de entrada de mi aplicación?
2. ¿A que se refiere el término Capas en el desarrollo de software?
3. ¿Qué es un ORM?
4. ¿Qué es un modelo? ¿Para qué sirve?
5. ¿Qué es un servicio? ¿Para qué sirve?
6. ¿Qué es un controlador? ¿Para qué sirve?
7. ¿Qué es un repositorio? ¿Para qué sirve?
8. ¿Qué es una ruta? ¿Para qué sirve?
9. ¿Qué son las relaciones en una base de datos? ¿Qué tipos de relaciones existen?
10. ¿Qué es una migración? ¿Para qué sirve? ¿Cómo sabe sequazile que una migración ya fue ejecutada?
11. ¿Cómo se define una relación uno a muchos en un modelo de Sequelize? ¿Y una relación muchos a muchos?
12. ¿Qué es una Primary Key? ¿Y una Foreign Key?
13. ¿Siempre es necesario definir una relación en ambos modelos? ¿Por qué?
14. ¿Qués son los status code? ¿Cuál es la diferencia entre los códigos 200, 201 y 204? ¿Y entre 400 y 404?
15. ¿Qué significa que una DB sea relacional?
16. ¿Qué es una API REST? ¿Qué significa que sea stateless?
17. ¿Qué significa CRUD? ¿Qué métodos HTTP se utilizan para cada operación CRUD?
18. ¿Cómo se definen las rutas en HTTP? ¿Cuales son las buenas prácticas sugeridas?
19. ¿Qué es un query param? ¿Para qué sirve? ¿y un path param? ¿y un body? ¿y un header?
