## Comando de Git 

Cuando hablamos de controlar la versión de sistemas hay muy pocos que hagan el estupendo trabajo que hace GIT, tanto en rendimiento como en predominio. GIT fue desarrollado por Linus Torvalds en el 2005 y hoy en día, millones de compañías lo usan como un eficiente administrador de código y control de versiones en sus proyectos.

Este software de código abierto se puede descargar tanto para Linux, Windows, Mac y Solaris, y en este tutorial aprenderás los comandos básicos de GIT para sacarle el mejor provecho.

###¿Qué necesitas?

Tener GIT instalado en tu sistema.

####Comandos básicos de GIT

# git config
Uno de los comandos más usados en git es git config, que puede ser usado para establecer una configuración específica de usuario, como sería el caso del email, un algoritmo preferido para diff, nombre de usuario y tipo de formato, etc… Por ejemplo, el siguiente comando se usa para establecer un email:

    git config --global user.email sam@google.com

# git init
Este comando se usa para crear un nuevo repertorio GIT:
    git init

#git add
Este comando puede ser usado para agregar archivos al index. Por ejemplo, el siguiente comando agrega un nombre de archivo temp.txt en el directorio local del index:

    git add temp.txt

#git clone
Este comando se usa con el propósito de revisar repertorios. Si el repertorio está en un servidor remoto se tiene que usar el siguiente comando:

    git clone alex@93.188.160.58:/path/to/repository
Pero si estás por crear una copia local funcional del repertorio, usa el comando:

     git clone /path/to/repository