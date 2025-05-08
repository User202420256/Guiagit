# Guia basica del usode Git
### Que es git?
  Git es un sistema de control de versiones distribuido de código abierto que se utiliza para rastrear los cambios en los archivos de un proyecto a lo largo del tiempo. 
  
### Que es  github?
  Git es un sistema de control de versiones que permite gestionar el historial de cambios en un proyecto, mientras que GitHub es una plataforma web para alojar y colaborar en proyectos de código fuente que utilizan Git.
  
### ¿Qué necesitamos para usar Github en nuestro proyecto 
  Para usar GitHub en tu proyecto, necesitarás una cuenta de GitHub y una instalación de Git en tu computadora. Puedes usar la línea de comandos o un cliente gráfico como GitHub Desktop para interactuar con Git. 
  
### Alta Github, Gitbash (terminal), carpeta en disco local
1. Crea una carpeta local
2. Inicializa el repositorio Git
3. Crea archivos o añade contenido a la carpeta
4. Conecta el repositorio local con GitLab
5. Sincroniza con GitLab

### Comandos habituales para trabajar con un repositorio remoto
1. git remote add	----- Añade una conexión de repositorio remoto.
2. git push	------------- Empuja los cambios confir#mados a un repositorio remoto.
3. git pull	-------------- Obtener y fusionar cambios de un repositorio remoto.
4. git fetch ------------- Obtener cambios de un repositorio remoto sin fusionar.
  
### Git init, status, remote, add, commit, push
1. **El comando git init** Crea un nuevo repositorio Git. Permite convertir un proyecto existente sin versionar en un repositorio Git o inicializar un nuevo repositorio 
   vacío.
2. **El comando git status**Muestra el estado del directorio de trabajo y del área de staging. Permite ver qué cambios se han almacenado, cuáles no y qué archivos no están siendo rastreados por Git. La salida de estado no muestra información sobre el historial de proyectos confirmados.
3. **Un repositorio remoto en Git** Es un repositorio común que todos los miembros del equipo usan para intercambiar sus cambios. En la mayoría de los casos, este repositorio remoto se 
   almacena en un servicio de alojamiento de código como GitHub o en un servidor interno.
4. **El comando git add** El comando git add añade un cambio en el directorio de trabajo al área de staging. Indica a Git que se desea incluir las actualizaciones de un archivo específico en la siguiente confirmación. Sin embargo, git add no afecta significativamente al repositorio; los cambios no se registran hasta que se ejecuta git commit.
5. **it commit -a**. Confirma una instantánea de todos los cambios en el directorio de trabajo. Esto solo incluye las modificaciones a los archivos rastreados (aquellos que se agregaron con 
6. **git commit -m "mensaje de confirmación"** Un comando de acceso directo que crea inmediatamente una confirmación con un mensaje de confirmación enviado.
7. **El comando git push** Se usa para subir el contenido de un repositorio local a un repositorio remoto. Subir confirmaciones es la forma de transferirlas desde el repositorio local a un repositorio remoto. Es la contraparte de git fetch, pero mientras que obtener importa confirmaciones a las ramas locales, subir las exporta a las ramas remotas.

### Clonar un repositorio
  Genera una copia completa de todos los datos del repositorio que GitHub.com tiene en ese momento, incluyendo todas las versiones de cada archivo y carpeta del proyecto .
  
### Hacer Fork de un repositorio existente
  Significa crear una copia completa y totalmente independiente de ese repositorio en tu propio espacio de trabajo.
