
##Despliege de apps Spring Boot en Heroku
Crear archivo `system.properties` en el proyecto con el contenido:
```
java.runtime.version=17
```

1. Crear cuenta en Heroku.com y github.com
2. Tener configurado git en el ordenador:
   1. `git config --global user.name "salvascript"`
   2. `git config --global user.email salvascript@gmail.com`
3. Subir el proyecto a Github desde Intellij IDEA desde la opción VCS > Share proyect in Github
4. Desde Heroku, crear la app y elegir método Github y buscar el repositorio subido.
5. Habilitar despliege automático y ejecutar el Deploy.
