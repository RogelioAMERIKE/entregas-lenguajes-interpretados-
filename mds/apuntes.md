Comandos basicos de Terminal Git Bash

# **_Mis Apuntes_**

- pwd: Imprime la ruta del directorio actual (print working directory)
- ls: lista los directorios y archivos de la carpeta del directorio donde esta la Terminal
- ls - l: lista detalles de los directorios y archivos
- ls -a: lista todo tipo de directorio y archivos (incluye los ocultos)
- ls -la: combinacion de ambas flags
- clear: para limpiar la pantalla del Terminal
- cd nombre-directorio: cambiar de directorio
- cd /: nos ubica en la carpeta raiz del equipo de computo
- cd ../: sube al directorio padre
- cd ../../: submos dos directorios padres
- cd ~: regresamos al directorio del usuario {/Users/Lab108-02}
- mkdir: crea un directorio
- touch archivos.txt: crea un archivo del tipo que le indiquemos
- rm (nombre de archivo): permite eliminar archivos
- rm -r: eliminar directorios
- cp ruta-actual ruta-nueva: copiar archivos
- mv ruta-actual ruta-nueva: mover archivos

## **_Atajos de VS Code_**
  - ctrl + j -Abre la terminal en el editor
  - alt + shit + flecha arriba o flecha abajo 
  - alt + shift + letra A

Mis apuntes

# Encabezado nivel 1

## Encabezado nivel 2
### Encabezado nivel 3
#### Encabezado nivel 4
##### Encabezado nivel 5
###### Encabezado nivel 6

Primer Parrafo en Markdown se termina el parrafo con Enter

Segundo Parrafo en Markdown

Las palabras en **negrita** se hace con asteriscos

Las palabras en _cursivas_ se hace con guiones abajos

Las palabras en _**crusiva negritas**_ con guion bajo y dos asteriscos/ dos asteriscos guion bajo

## Comando de *_GIT_*

### Configuracion Inicial

Estos comandos los vas a ejecutar una sola vez, despues de tener instalado *_GIT_*

```bash
git --version
git config --global user.name "Jonathan MirCha"
git config --global user.email jonmircha@gmail.com
git config --global user.ui true
git config --global init.defaultBranch main
git config --list
# asignando visual studio code como editor de configuración de git
git config --global core.editor "code --wait"
git config --global -e
# para estandarizar los saltos de línea en windows
git config --global core.autocrlf true
# para estandarizar los saltos de línea en linux/mac
git config --global core.autocrlf input
# ver todas las opciones de la configuración en la terminal
git config -h
# ver todas las opciones de la configuración en el navegador
git help config
```
### Inicializando GIT

Cuando queremos inicializar GIT en alguna carpeta local de nuestra computadora debemos ejecutar el comando: 
```bash
git init
```

Este comando lo debemos ejecutar solo una vez para inidicarle que le de seguimiento al archivo

El siguiente comando nos ayuda a visualizar el estado de seguimiento de los archivos de nuestra carpeta

```bash
git status
```

### Flujo basico de *GIT* Y *GITHUB*

![fLUJO BASICO DE gIT Y gITHUB](https://jonmircha.com/img/blog/git-flow.png)

```bash
git add <nombre-archivo>
```

El siguiente comnado nos ayuda a ver el historial de cambio del repositorio

```bash
git log 
```

- Primavera
- Verano
- Otoño
- Invierno

1. Primavera
1. Verano
1. Otoño
1. Invierno

|Pais|Ciudad|Continente|
|-|-|-|
|Mexico|CDMX|América|
|Francia|Paris|Europa|
|Japon|Tokio|Asia|

[Visita Amerike](https://amerike.edu.mx/campus-cdmx/)

<!-- ![This is JavaScript](https://jonmircha.com/img/blog/this-is-javascript.jpg) -->

![This is JavaScript](https://jonmircha.com/img/blog/this-is-javascript.jpg)

```js
function sumar(a, b) {
  if (typeof a !== "number" || typeof b !== "number") {
    console.error(`Los valores ingresados NO son números.`);
    return false;
  }

  let c = a + b;
  return c;
}
```
<form>
  <label for="q">Buscar:</label>
  <input type="search" name="q" id="q" required />
  <input type="submit" value="🔍" />
</form>

