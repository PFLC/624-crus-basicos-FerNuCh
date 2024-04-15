
# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

## Ejemplos de CRUD

Los formularios pueden ser de 4 tipos distintos, variando cada uno en funcionalidad y objetivo de los mismos.

El de creacion, por ejemplo, sirve para crear un registro nuevo en la base de datos. Un uso de este seria el formulario de resgistro a paginas como Facebook.
![image](https://github.com/PFLC/624-crus-basicos-FerNuCh/assets/113657453/b359f3c2-4da8-4be6-98d6-96b1b0a51302)
El formulario de lectura es un poco mas complicado de explicar pues no es un formulario como tal si no mas una consulta que hacemos de otro registro existente, como la barra de busqueda de perfiles en alguna red social.
![twitter-1](https://github.com/PFLC/624-crus-basicos-FerNuCh/assets/113657453/0fe6b432-fc60-4c57-8e50-72e6b8612e05)
El formulario de actualizacion o Update es el que veriamos al querer cambiar nuestro nombre de usuario en una plataforma digital, como en Twitter/X que te pide ciertos datos al querer cambiar de nombre de usuario, Nombre de cuenta o contraseña
![CAMBIAR-CONTRASENA-TWITTER-1024x567](https://github.com/PFLC/624-crus-basicos-FerNuCh/assets/113657453/24fe3764-e3e2-409b-b52b-c828e3edbb84)
Y por ultimo el de eliminacion, que realmente se puede ver usualmente como un boton sencillo que al presionarlo te preguntara si estas seguro de eliminar tu cuenta, aun que en algunos casos se puede ver otro formulario que te pregunta las razones de esta eliminacion.
![450_1000](https://github.com/PFLC/624-crus-basicos-FerNuCh/assets/113657453/4dd130b1-5080-4629-9798-208741be074e)
