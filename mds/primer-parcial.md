# Examen Primer Parcial

#### 1. ¿Qué es y para qué sirve Visual Studio Code?

Visual Studio Code es un editor de código que es una herramienta que está hecho para poder documentar, escribir y editar códigos en diferentes lenguajes de programación.

#### 2. ¿Qué es y para qué sirve la Terminal de Comandos?

La terminal de comandos es la que permite de poder controlar o interactuar con el sistema operativo por medio de comandos esto sirve para ejecutar programas, realizar tareas y administrar los archivos. 

#### 3. ¿Qué es y para qué sirve Markdown

El formato Markdown es un lenguaje de marcado ligero que nos permite escribir textos a través de ciertos caracteres dándole un formato más organizado.

#### 4. ¿Qué es y para qué sirve Git?

Git es un software que tiene o ofrece un control de versiones en el cual los desarrolladores podrán trabajar de manera colaborativa y permite registrar cambios de los proyectos

#### 5. ¿Qué es y para qué sirve GitHub?

Github es una plataforma donde se guardan los repositorios sirve para tener uan mejor gestión de trabajos, prácticas o proyectos que se hagan en equipo entre desarrolladores.

#### 6. ¿Para qué sirven los siguientes comandos: pwd, whoami, touch, mkdir, cp, mv, ls, clear, cd y rm?

- pwd: Imprime la ruta del directorio actual (print working directory)
- whoami: Imprime o muestra el nombre del usuario actualmente
- touch archivos.txt: crea un archivo del tipo que le indiquemos
- mkdir: crea un directorio
- cp ruta-actual ruta-nueva: copiar archivos
- mv ruta-actual ruta-nueva: mover archivos
- ls: lista los directorios y archivos de la carpeta del directorio donde está la Terminal
- clear: para limpiar la pantalla del Terminal
- cd nombre-directorio: cambiar de directorio
- rm (nombre de archivo): permite eliminar archivos

#### 7. Caracteres especiales en la terminal:

./ :  Es el directorio actual.

../ : Sube un nivel del directorio actual.

/ :La carpeta raíz del equipo de computo.

~ : Directorio del usuario.

#### 8. ¿Cómo se inicializa un repositorio en Git?

Se inicializa un repositorio en git con el comando.

```js
git init
```

#### 9. ¿Cómo crear un repositorio en GitHub?

Desde la página de Github en tu cuenta en el botón de “New” o “Nuevo”  te abrirá un nuevo panel donde tendrás que poner el nombre del repositorio, configurarlo y escribir una pequeña descripción.

#### 10. ¿Cómo vincular un repositorio local de Git con uno remoto en GitHub?

Para vincular el repositorio local de Git con un remoto en github son los siguientes comandos: 

```js
git remote add origin (link del repositorio) //es el que agrega el origen remoto de tu repositorio de GitHub.
git push -u origin master //se utiliza en la primera vez que vinculamos el repositorio remoto con el local.
```

#### 11. Flujo básico de trabajo en Git y GitHub:

El flujo básico consta de 4 estados que se ubican en 4 áreas estas son: 

La primera área es Working Directory que el estado para este es “modified” donde se almacenan los archivos del proyecto.

La segunda área es Staging Area que el estado para este es “staged” donde agrega los cambios que se realizan en los archivos antes de su registro.

La tercera área es Local Repository que el estado para este es “committed”, donde los cambios se registran en el repositorio.

La cuarta área es Remote Repository que el estado para este es “remote” y es donde se almacenan los archivos del proyecto como en Github.



#### 12. ¿Para qué sirve el archivo .gitignore?

El archivo .gitignore sirve para indicar que archivos, carpetas o ejecutables no deben ser rastreados por Git.

#### 13. ¿Cuál es el propósito de una rama?

El propósito que tiene una rama es el que nos permite trabajar, hacer cambios o correcciones donde no afecte la rama principal o el entorno.

#### 14. ¿Qué es una fusión?

La fusión es la unión de dos ramas o ramas donde se integran los cambios y contenido que se realizaron en las ramas que fusionamos.

#### 15. Tipos de fusión (merge):

Existen dos tipos de fusiones: 

Fast Forward:  Es la fusión que se hace sin conflictos de manera automática.

Manual Merge: Es la fusión que se hace de manera manual para resolver los conflictos del contenido.

#### 16. ¿Cómo puedes ver el historial de tu repositorio?

Para ver el historial del repositorio se utiliza el comando:

```js
 git log
```

#### 17. ¿Cuál es el propósito de una etiqueta (tag)?

El propósito de las etiquetas (tag) es tener un historial del repositorio sobre cambios que se han hecho a través de versiones para identificar de mejor manera los cambios.
