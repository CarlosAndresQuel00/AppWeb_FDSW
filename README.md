#Jamafud
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
El siguiente proyecto muestra el desarrollo una Aplicación Móvil que permite a usuarios compartir ideas de reutilización de materiales mediante videos, imagenes o guías.
</br>**Video demostrativo:** https://youtu.be/qtX4d4mzTR8
</br>**Realizado por:**
</br>\- Alejandro Armas
</br>\- Carlos Quel

#1. Herramientas de Desarrollo
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
##IONIC
La aplicación móvil será híbrida por lo que Ionic es una buen framework para este tipo de aplicaciones ya que integra tanto la capa de diseño con estilo css y recursos como íconos, estilos, etc.

##FIREBASE
Firebase es una plataforma cuya función es desarrollar y facilitar la creación de apps de elevada calidad de una forma rápida ya que contiene diversas funciones que se pueden adaptar a las herramientas o plataformas que se usará para el desarrollo. Además de que es muy intuitiva al ofrecer APIs integradas, por otro lado, tambien se utlizó Firebase para el para el hosting y alamcenamiento de datos, imagenes y documentos.

#2. Estructura y arquitectura
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
##° Arquitectura

La Arquitectura de la Aplicación móvil se meustra en la siguiente imagen.
https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/arquitectura.png

##° Estructura
Los datos almacenados en Firebase muestran las siguiente estructura.
https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/estructura.png

#3. Funcionalidades principales
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Dentro del desarroLlo de la Aplicación Móvil se pudo recabar varios requerimientos y funcionalidades para la Aplicación Móvil, algunas de las más importantes son las siguientes:

##° Iniciar sesión y registro de usuarios
El usuario puede iniciar sesión o registrase dentro de la aplicación usando un correo y una contraseña generada por el mismo usuario al momento de ingresar al formulario de registro, para esto fue necesario activar este método de autenticación en Firebase Authentication habilitando Email/Password.

https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/Screenshot_20210309-003454_MyApp.jpg

##° Visualización de la ventana principal
El usuario podrá ver todas las publicaciones de todos usuarios regsitrado en la ventana principal.

https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/Screenshot_20210316-000159_R-Utiliza.jpg

##° Guardar publicaciones de otros usuarios
El usuario podrá guardar las publicaciones que le parecieron más interesantes de otros usuarios y así poder acceder a esta información de manera más fácil, en esta lista se encontraran todos los datos de la publicación, así como los datos de la persona que lo publicó.

https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/Screenshot_20210309-003140_MyApp.jpg

##° Seguir entre usuarios
Los usuarios tendrán la posibilidad de seguir a otros usuarios y así poder acceder a todas las publicaciones de los mismos.

https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/Screenshot_20210316-001415_R-Utiliza.jpg https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/Screenshot_20210316-001419_R-Utiliza.jpg https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/Screenshot_20210316-001436_R-Utiliza.jpg

##° CRUD de publicaciones
Los usuarios podrán crear, editar, eliminar y visualizar sus publicaciones.
https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/Screenshot_20210309-003113_MyApp.jpg https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/Screenshot_20210316-001542_R-Utiliza.jpg

##° Categorias de publicaciones
Muestra las categorías de las publicaciones dentro del aplicación móvil.
https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/Screenshot_20210316-002453_R-Utiliza.jpg

##° Reportar publicaciones
Realizar un reporte de alguna publicación que vulnere la temática principal de la aplicación que es reutilizar.
https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/Screenshot_20210316-004047_R-Utiliza.jpg

##° Comentar publicaciones
Los usuarios podrán comentra cualquier publicacion publicada.
https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/Screenshot_20210316-002422_R-Utiliza.jpg

##° Compartir publicaciones
Los usuarios podrán compartir las publicaciones creadas por ellos mismos o por otros usuarios.
https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/Screenshot_20210316-002438_R-Utiliza.jpg

#4. Versiones de Desarrollo
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
https://github.com/Migueltorresp/App_Tesis/blob/dev/Captures/ionic-info.jpg

#5. Instalación
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
##1. Clonar el Repositorio

```
git clone https://github.com/Migueltorresp/App_Tesis.git
cd App_tesis
```

##2. Instalar dependencias

```
npm install
```

##3. Levatar el servidor local

```
ionic serve
```

#6. Anexos
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
En el siguiente link se encuentra toda la documentacion como Manual Técnico, Manual de Instalación, Informe Técnico y los diferentes anexos del proyecto. Link
