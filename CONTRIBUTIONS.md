# ⚜ Primeras Contribuciones

Es complicado. Resulta difícil la primera vez que haces algo, especialmente cuando colaboras con otros, pues cometer errores no es nada agradable.

- Nuestro objetivo es simplificar la forma en la que los nuevos contribuidores de codigo abierto aprenden y contribuyen por primera vez.

- Leer artículos y ver tutoriales puede ayudar, pero, ¿Qué mejor que hacer las cosas en un entorno de prácticas?

- Este proyecto se enfoca en ser una guía y en simplificar la forma en la que los principiantes hacen su primera contribución.

- Si quieres hacer tu primera contribución, sigue los pasos que se muestran a continuación.

## ⚜ Si no estás familiarizado con la línea de comandos

Aquí hay tutoriales usando herramientas con Interfaz Gráfica (GUI) / (Tutoriales con otras herramientas)

- Si no tienes git en tu equipo, puedes encontrar instrucciones para instalarlo en [este enlace](https://docs.github.com/es/get-started/quickstart/set-up-git)

## ⚜ Bifurca (Fork) este repositorio

Haz un *fork* de este repositorio haciendo click en el botón " *Fork*" en la parte superior derecha en esta página.
![fork de este repositorio](https://firstcontributions.github.io/assets/Readme/fork.png)

Si no tienes git en tu equipo, puedes encontrar instrucciones para instalarlo en [este enlace]( https://docs.github.com/es/get-started/quickstart/set-up-git).

- Esto creará una copia de este repositorio en tu cuenta.

## ⚜ Clona (*Clone*) el repositorio bifurcado ![clonar este repositorio](https://firstcontributions.github.io/assets/Readme/clone.png)

- Ahora clona este repositorio en tu equipo. Dirígete a tu cuenta de GitHub, haz click en el botón " *clone or download*" y luego haz click en el icono para *copiar al portapapeles*.

- Abre tu consola o terminal y ejecuta el siguiente comando de git: `git clone "url que acabas de copiar"`

- Donde pone "url que acabas de copiar" (sin las comillas dobles) es la *url* a este repositorio (tu *fork* a este proyecto).

Mira los pasos previos para obtener la *url*. ![copiar URL al portapapeles](https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png)

La parte de `este-eres-tu` la reemplazarás con tu usuario de GitHub.

Aquí estás copiando los contenidos del repositorio *first-contributions* en GitHub a tu equipo.

## ⚜ Crea una rama (*Branch*)

- Cambia al directorio del repositorio en tu equipo (si es que no estás ahí ya). `cd first-contributions`

- Ahora crea una rama (*branch*) usando el comando `git checkout`: `git checkout -b` Por ejemplo: `git checkout -b add-alonzo-church`

- El nombre de la rama no tiene por qué contener la palabra *add*, pero es razonable que lo tenga porque el objetivo de esta rama es añadir tu nombre a la lista.

## ⚜ Haz los cambios necesarios y confirma (*Commit*) esos cambios

- Abre el archivo `Contributors.md` en un editor de texto y añade tu nombre

- No lo añadas ni al principio ni al final del archivo, hazlo en cualquier otro sitio. Guarda el archivo. ![git status](https://firstcontributions.github.io/assets/Readme/git-status.png)

- Si vas al directorio del proyecto y ejecutas el comando `git status`, verás que hay cambios.

- Agrega esos cambios a la rama (*branch*) que creaste anteriormente usando el comando `git add`:`git add Contributors.md`

Ahora haz un *commit* sobre estos cambios ejecutando el comando `git commit`:`git commit -m "Add to Contributors list"` cambiando con tu nombre.

## ⚜ Sube (*Push*) tus cambios a GitHub

- Haz *push* de tus cambios usando el comando `git push`:`git push origin` `Reemplaza` con el nombre de la rama que creaste anteriormente

## ⚜ Envía (*Submit*) tus cambios para ser revisados

- Si vas a tu repositorio en GitHub, verás un botón `Compare & pull request`

Haz click sobre este botón. ![crea una pull request](https://firstcontributions.github.io/assets/Readme/compare-and-pull.png)

Ahora envía la *pull request*. ![enviar la pull request](https://firstcontributions.github.io/assets/Readme/submit-pull-request.png)

Pronto estaré fusionando tus cambios (haciendo *merge*) con la rama master de este proyecto. Recibirás una notificación por correo electrónico cuando los cambios hayan sido fusionados.

## ⚜ ¿Cuáles son los siguientes pasos?

- ¡Enhorabuena! ¡Has completado el flujo de trabajo fork -> clone -> edit -> PR que encontrarás habitualmente como contribuidor!

- Celebra tu contribución y compártela con tus amigos y seguidores.

Copyright (c) 2023 Andres Antonio Cardoso
