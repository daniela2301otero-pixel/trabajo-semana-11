# trabajo-semana-11
TRABAJO SEMANA 11
preguntas-semana11
Pregunta 1:
Respuesta: Un sistema que permite almacenar y consultar información estructurada.
Pregunta 2:
Respuesta: Crear, leer, actualizar y eliminar datos.
Pregunta 3:
Respuesta: Identificar usuarios y controlar quién puede acceder a ciertas funciones.
Pregunta 4:
Respuesta: Para evitar riesgos de privacidad o uso indebido de la información.
modelo-datos.txt
Entidad: Causa
Campos principales:
- id
- titulo
- descripcion
- fecha
Propósito:
Guardar las causas comunitarias que serán publicadas en la plataforma para que los usuarios puedan conocerlas y apoyarlas.
Entidad: Apoyo
Campos principales:
- id
- causa_id
- usuario
- fecha
Propósito:
Registrar los apoyos realizados por los usuarios y llevar un control de la participación en cada causa comunitaria.
autenticacion.txt
El login permite identificar a un usuario antes de ingresar a la plataforma.
Gracias a la autenticación se puede controlar quién accede a determinadas funciones.
Las rutas protegidas evitan que personas no autorizadas modifiquen la información.
También ayudan a mantener la seguridad de los datos registrados.
No deben publicarse contraseñas, documentos de identidad, teléfonos ni direcciones.
Tampoco se deben compartir tokens, claves de API o archivos .env.
Proteger la información fortalece la confianza de la comunidad.
interfaz.txt
La plataforma tendría un formulario para crear una nueva causa comunitaria con título, descripción y fecha.
También mostraría una lista con todas las causas disponibles para que los usuarios puedan conocerlas.
Cada causa tendría un botón para brindar apoyo y un contador que indique cuántas personas la han apoyado.
La interfaz sería sencilla, organizada y fácil de usar, sin mostrar información privada de los usuarios.
reflexion-semana11
Una plataforma de participación ciudadana necesita una base de datos para almacenar la información de manera organizada. La autenticación permite que solo los usuarios autorizados puedan acceder a funciones importantes. Esto ayuda a proteger la información y evitar accesos no permitidos. También es importante cuidar los datos personales de la comunidad para mantener su privacidad. La protección de la información genera confianza entre los usuarios. Además, facilita el seguimiento de las actividades realizadas. Una plataforma segura es más confiable y útil para todos. Por eso, la base de datos, la autenticación y la seguridad son fundamentales para su buen funcionamiento
