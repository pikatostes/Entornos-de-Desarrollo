# Control de versiones

### 1. Además de Git, ¿que otros sistemas de control de versiones existen?

- CVS, Subversion o Mercurial

  

### 2. En Git, ¿qué tres áreas existen?

- El directorio de Git (Git directory), el directorio de trabajo (working directory), y el área de preparación (staging area).

  

### 5. En Git, ¿para qué sirve el comando `git config`?

- Para definir valores de configuración de Git a nivel de un proyecto global o local.

  

### 6. En Git, ¿para qué sirve el comando `git init`?

- Para crear un nuevo repositorio de Git.

  

### 7. En Git, ¿para qué sirve el comando `git clone`?

- Se utiliza principalmente para apuntar a un repositorio existente y clonar o copiar dicho repositorio en un nuevo directorio, en otra ubicación.

  

### 8. En Git, ¿para qué sirve el comando `git status`?

- Para mostrar el estado del directorio de trabajo y del área del entorno de ensayo.

  

### 9. En Git, ¿para qué sirve el comando `git add`?

- Para añadir un cambio del directorio de trabajo en el entorno de ensayo.

  

### 10. En Git, ¿para qué sirve el comando `git commit`?

- Para confirmar una instantánea del directorio del entorno de ensayo en el historial de confirmaciones de los repositorios.

  

### 11. En Git, ¿para qué sirve el comando `git log`?

- Para explorar el historial del repositorio.

  

### 12. En Git, ¿para qué sirve el comando `git reset HEAD nombrearchivo`?

- Para deshacer los cambios locales en el estado de un repositorio de Git. Actúa en el historial de confirmaciones (HEAD).

  

### 13. En Git, ¿para qué sirve el comando `git checkout -- nombrearchivo`?

- Te permite deshacer cambios en un archivo concreto.

  

### 15. En Git, ¿para qué sirve el comando `git branch`?

- Sirve para crear, enumerar y eliminar ramas, así como cambiar su nombre.

  

### 16. En Git, ¿para qué sirve el comando `git checkout`?

- Te permite desplazarte entre las ramas creadas por `git branch`.

  

### 17. En Git, ¿para qué sirve el comando `git merge`?

- Te permite tomar las líneas independientes de desarrollo creadas por git branch e integrarlas en una sola rama.

  

### 18. En Git, explica cómo funciona la fusión (merge) de tipo fast-forward.

- Lo que hace es acelerar el flujo de trabajo en el proceso del proyecto. Esto lo consigue mediante la armonización de la rama principal del proyecto, con las modificaciones resultantes de la creación de una rama *`feature`* con determinadas especificaciones de cambios. Destaca por su capacidad de cambiar el \*HEAD\* en el sistema.