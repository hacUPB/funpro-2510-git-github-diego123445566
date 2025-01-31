Abrir la terminal y navegar al directorio donde se creará el repositorio:

bash
Copiar
Editar
cd ruta/del/proyecto
Inicializar el repositorio:

bash
Copiar
Editar
git init
Esto crea una carpeta oculta .git que almacena la configuración y el historial del repositorio.

Configurar el usuario (si es la primera vez):

bash
Copiar
Editar
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"
Agregar archivos al área de preparación:

bash
Copiar
Editar
git add nombre_del_archivo
Para agregar todos los archivos:

bash
Copiar
Editar
git add .
Guardar los cambios con un commit:

bash
Copiar
Editar
git commit -m "Mensaje descriptivo del cambio"
Verificar el estado y la configuración del repositorio:

bash
Copiar
Editar
git status
git log
git config --list
