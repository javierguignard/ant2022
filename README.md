# ITS - Programación
## Aplicación de Nuevas Tecnologías

---

# About us

Espacio destinado a subir los trabajos prácticos a realizar en la asignatura Aplicación de Nuevas Tecnologías, correspondiente al septimo año de la especialidad  Técnico en Programación del Instituto Técnico Salesiano Villada.  
Este documento está en constante desarrollo, por lo cuál, podrás ver que hay trabajos prácticos propuestos que aún no han sido elaborados (están tachados) 

---


# Tabla de contenidos

1. [Trabajo Práctico N° 1: Sistemas de control de versiones.](#trabajo-práctico-n-1-sistemas-de-control-de-versiones)
1. ~~Trabajo Práctico N° 2: Containers.~~
1. ~~Trabajo Práctico N° 3: Webservices.~~
1. ~~Trabajo Práctico N° 4: Arquitectura de Microservicios.~~

   
# Trabajo Práctico N° 1: Sistemas de control de versiones.

### 1- Objetivos de Aprendizaje
 - Utilizar herramientas de control de configuración de software, familiarizarse con la nomenclatura y conocer los comandos más utilizados.
 - Configurar el repositorio principal de cada alumno para la asignatura.

### 2- Consignas a desarrollar en el trabajo práctico:
  - Los ejercicios representan casos concretos y rutinarios en uso de este tipo de herramientas.
  - Documentar el proceso desarrollado utilizando las herramientas tecnológicas que creas necesarias.
  
### 3- Desarrollo:

#### 1- Instalar Git
Los pasos y referencias asumen el uso del sistema operativo Ubuntu, en caso otros SO seguir recomendaciones específicas.

  - Bajar e instalar el cliente git.  
  `$ sudo apt install git`
  - Bajar e instalar un cliente visual. 
  _Se puede utilizar el cliente del IDE que utiliza normalmente (vscode, por ejemplo)_. 
    - Lista completa: https://git-scm.com/downloads/guis/

#### 2- Crear un repositorio local y agregar archivos
  - Crear un repositorio local en un nuevo directorio.
  - Agregar un archivo Readme.md, que contenga tu nombre y un link a tu CV. Tu cv será otro archivo en el mismo formato, en la misma carpeta.
    - Aclaración: No pongas información personal como DNI, email o telefono en tu cv, puede tener información Falsa si lo prefieren.
  - Crear los commits de cada caso y proveer mensajes descriptivos.

#### 3- Crear un repositorio remoto
  - Crear una cuenta en https://github.com
  - Crear un nuevo repositorio en dicha página (vacío)
  - Asociar el repositorio local creado en el punto 2 al creado en github.
  - Subir los cambios locales a github.

#### 4- Familiarizarse con el concepto de Pull Request
Para algunos de los puntos proveer imágenes o videos.
  
  - Crear un branch local y agregar cambios a dicho branch. 
    - El cambio debe ser un archivo md donde se explique que es un pull request y un link a éste en el readme. 
  - Subir el cambio a dicho branch y crear un pull request.
  - Completar el proceso de revisión en github y mergear el PR al branch master.

#### 5- Mergear código con conflictos  
Para algunos de los puntos proveer imágenes o videos.
  
  - Instalar alguna herramienta de comparación
    - Ejemplos: SmartGit, GitEye, plugin para vscode. pycharm, etc   
  - Clonar en un segundo directorio de tu equipo el repositorio creado en github.
  - En el clon inicial, modificar el CV.md cambiando algunas lineas.
  - Hacer commit y subir el cambio a master a github.
  - En el segundo clon también realizar cambios en las mismas líneas que se modificaron en el otro directorio.
  - Intentar subir el cambio, haciendo un commit y push. Mostrar el error que se obtiene.
  - Hacer pull y mergear el código (solo texto por ahora), mostrar la herramienta de mergeo como luce.
  - Resolver los conflictos del código.
  - Explicar las versiones LOCAL, BASE y REMOTE.
  - Pushear el cambio mergeado.

#### 6- Algunos ejercicios online
  - Entrar a la página https://learngitbranching.js.org/
  - Completar los ejercicios **Introduction Sequence**
  - Opcional - Completar el resto de los ejercicios para ser un experto en Git :D !!!

#### 7- Crear Repositorio de la materia
  - Crear un repositorio para la materia en github. Por ejemplo **ANT** (Diferente al de este trabajo práctico)
  - Subir archivo(s) .md con los resultados, imágenes y/o videos de este trabajo práctico a ese repositorio. Puede ser en una subcarpeta **trabajo-practico-01**, con su propia rama, como mas le guste, pero en el README.md deberán explicar como encuentro el resultado.
  
