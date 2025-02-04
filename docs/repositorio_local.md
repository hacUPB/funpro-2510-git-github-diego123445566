1. Inicializar el repositorio: Abre tu terminal y navega al directorio donde deseas crear el repositorio. Si el directorio no existe, crea uno nuevo y accede a él. Luego, ejecuta el comando git init para inicializar un repositorio vacío en ese directorio. Este comando crea una carpeta oculta llamada .git, lo que convierte a tu proyecto en un repositorio de Git.

2. Añadir archivos al repositorio: Después de inicializar el repositorio, debes añadir los archivos que deseas que Git gestione. Para ello, utiliza el comando git add. Si quieres añadir un archivo específico, puedes escribir git add nombre_del_archivo, o si deseas añadir todos los archivos del directorio, usa git add .. Este comando coloca los archivos en el área de preparación (staging area), que es donde se almacenan antes de ser confirmados (commit).

3. Hacer un commit: Un commit guarda una instantánea de los archivos que has añadido al repositorio. Para hacer un commit, usa el comando git commit -m "mensaje", donde "mensaje" es una descripción del cambio realizado. Por ejemplo, puedes escribir git commit -m "Primer commit: añadir archivo inicial". El mensaje del commit es importante para tener un registro claro de los cambios realizados.

4. Verificar el estado del repositorio: Para saber qué archivos están listos para ser confirmados o si hay cambios que aún no se han añadido, puedes usar el comando git status. Este comando te proporciona información sobre los archivos modificados y los que están pendientes de commit.

5. Ver el historial de commits: Si deseas revisar el historial de cambios, puedes usar git log. Este comando muestra una lista de todos los commits realizados, incluyendo detalles como el mensaje del commit, la fecha y el autor
