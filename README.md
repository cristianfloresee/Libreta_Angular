<h1 align=center>
    Angular-CLI
</h1>

# Versión

Versión del CLI:
```
ng --version
```

Actualizar:
+ Desintalar la versión actual:
npm uninstall -g @angular/cli cache clean
+ Instalar la última versión:
npm install -g @angular/cli@latest

# Ayuda
Ayuda general:
ng help
Ayuda para un comando específico (generate en este caso):
ng help generate

# Nuevo proyecto

+ Generar un nuevo Proyecto:
ng new my-app

Algunos indicadores que puede utilizar son:

+ --dry-run:
Simula que archivos se crearían con el comando, pero no genera nada.

+ --skip-install:
No instala las dependencias o no ejecuta el npm install (útil cuando esta desconectado de internet o con conexión lenta).

+ --skip-tests : 
No crea los archivos de especificaciones (extensión .spec).

+ --skip-git: 
No inicializa un git repo.

+ --routing : 
Genera el modulo de enrutamiento de la aplicación.

+ --prefix : 
Especifica el prefijo que se usará para los selectores/directivas de los componentes (útil para evitar conflictos cuando tenga que integrar modulos externos). 

+ --style : 
Tiene el valor predeterminado de css, pero se puede establecer en scss.
 Un ejemplo sería --style=scss

--inline-style : 
utiliza estilos en línea para componentes en lugar de archivos separados.

--inline-template : utiliza plantillas en línea para los componentes en lugar de archivos separados.

+ --verbose: 
??

--source-dir :
Nombre del directorio fuente??

# Referencias
<https://alligator.io/angular/angular-cli-reference/>