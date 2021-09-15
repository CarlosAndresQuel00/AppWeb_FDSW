# Jamafud

El siguiente proyecto muestra el desarrollo de una Aplicación Web que permite a usuarios generar un presupuesto y una lista de ingredientes en base a un menú semanal escogido.
<br/>**Video:** https://youtu.be/wxyQoMb3b8I
<br/>**Realizado por:**
<br/> - Alejandro Armas
<br/> - Carlos Quel

## 1. Herramientas de Desarrollo

### NODEJS
Su uso permite instalar los paquetes necesarios para React y obtener librerías específicas para el desarrollo de _front-end_.

### LARAVEL
Su implementación permite generar una API de manera sencilla, obteniendo los datos del lado del servidor y presentarlos al cliente de forma eficiente. También el manejo de los datos de las bases SQL a objetos de tipo JSON mediante el uso de recursos API.

### XAMPP
Su uso permite levantar un servidor local que ayuda a conectar herramientas como la base de datos con MySQL y la API, además de permitir mantener levantada la API para la conexión al front-end y manejar los datos.

### POSTMAN
Su uso permite dos partes importantes, la primera es hacer testings a los endpoints como el de autenticación y de ingreso de datos a la API y la segunda es ver como llegan o se reciben los datos al realizar una petición al API.

## 2. Estructura y arquitectura

### ° Arquitectura

La Arquitectura de la Aplicación web se meustra en la siguiente imagen.
![image](https://user-images.githubusercontent.com/66259796/133201557-723600cf-835c-4e6b-8b05-4151236103b6.png)

### ° Estructura
Los datos almacenados en Laravel con MySQL muestran la siguiente estructura.
![image](https://user-images.githubusercontent.com/66259796/133201645-a714a2f8-2292-48c2-9e7a-6bc20d612426.png)

## 3. Funcionalidades principales

Dentro del desarroLlo de la Aplicación Web se pudo recabar varios requerimientos y funcionalidades para la Aplicación Web, algunas de las más importantes son las siguientes:

### ° Iniciar sesión y registro de usuarios
El usuario puede iniciar sesión o registrase dentro de la aplicación usando un correo y una contraseña generada por el mismo usuario al momento de ingresar al formulario de registro, para esto fue necesario activar este método de autenticación en Laravel Authentication habilitando Email/Password.

![image](https://user-images.githubusercontent.com/66259796/133201835-b0b53975-3ab1-4f1a-acc3-3ecf01618b88.png)
![image](https://user-images.githubusercontent.com/66259796/133201864-75a6dbe7-f487-40a5-8421-eab68fa1405a.png)

### ° Visualización de la sección comida nacional
El usuario podrá ver todas las publicaciones de platillos en detalle de todos los usuarios que han regsitrado en la sección comida nacional.

![image](https://user-images.githubusercontent.com/66259796/133202204-790fb9f8-f592-4e21-8c1b-3c6e7e2d698f.png)

### ° Guardar nuevos ingredientes por parte de los usuarios
El usuario podrá guardar nuevos ingredientes en el caso de que no existan que posiblemente le serán útiles a otros usuarios, y así poder acceder a esta información de manera más fácil, por detrás del botón siguiente habrá una lista que encontraran todos los datos de los nuevos ingredientes añadidos, así como a que tipo de ingrediente pertenece.

![image](https://user-images.githubusercontent.com/66259796/133203336-a5b71aca-b8c7-4258-90c9-5e5ff9c6c855.png)

### ° Perfil de usuario
Los usuarios tendrán la posibilidad de tener su menú guardado en su propio perfil y compartirlo con los demás si quieren.

![image](https://user-images.githubusercontent.com/66259796/133203750-e72c89e1-4a4a-4a5b-92e8-e52b85263864.png)

### ° CRUD de datos
Los usuarios podrán crear, guardar sus creaciones de sus platillos u obtener platillos ya guardados.<br/>
![image](https://user-images.githubusercontent.com/66259796/133204162-0c4e3af3-22ce-411a-a6d2-4e78df2f06d3.png)
![image](https://user-images.githubusercontent.com/66259796/133204247-c9245e44-771c-4504-a519-96b50b628017.png)

### ° Detalle en especifico de un platillo
Muestra el detalle de un platillo a través de un modal dentro del aplicación web.
![image](https://user-images.githubusercontent.com/66259796/133204291-09060757-b50c-4908-abf4-b2491eb9125b.png)

## 4. Versión de Desarrollo

![image](https://user-images.githubusercontent.com/66259796/133205110-27ca9146-0ec8-4031-828f-2389b115022e.png)
![image](https://user-images.githubusercontent.com/66259796/133212606-c5461691-3b44-4789-b013-f8d80e3a1374.png)

## 5. Instalación

### 1. Clonar el Repositorio _front-end_

```bash
git clone https://github.com/DAW-ESFOT/frontend-jamafud-fronend.git
cd frontend-jamafud-fronend
```

### 2. Clonar el Repositorio _back-end_

```bash
git clone https://github.com/DAW-ESFOT/proyecto-semestre-backend-jamafud.git
cd proyecto-semestre-backend-jamafud
```

### 3. Instalar dependencias _front-end_

```bash
npm install
```

### 3. Instalar dependencias _back-end_

```bash
composer install
```

### 4. Levatar el servidor local

```bash
php artisan serve
```

## 6. Anexos

En el siguiente link se encuentra toda la documentacion como Manual Técnico, Manual de Usuarios, Informe Técnico y los diferentes anexos del proyecto. <a href="https://github.com/CarlosAndresQuel00/Documentacion_FDSW">Link</a>
