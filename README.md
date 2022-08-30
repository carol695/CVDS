### Escuela Colombiana de Ingeniería 
### Ciclos de vida de desarrollo de software 
### Laboratorio 2

### **LA HERRAMIENTA MAVEN** 
* **Cuál es su mayor utilidad**

    La mayor utilidad de esta herramienta es que permite a los desarrolladores comprender el estado completo 
    del proyecto en el menor tiempo posible. 

* **Fases de maven**
    1. Process-resources
    2. Compile 
    3. Process-test-resources
    4. test-compile 
    5. Test
    6. Package 
    7. Install
    8. Deploy 
   
* **Ciclo de vida de la construcción**

    1. **compile**: Genera los ficheros .class compilando los fuentes .java
    2. **test**: Ejecuta los test automáticos de JUnit existentes, abortando el proceso si alguno de ellos falla.
    3. **package**: Genera el fichero .jar con los .class compilados
    4. **install**: Copia el fichero .jar a un directorio de nuestro ordenador donde maven deja todos los .jar. 
         De esta forma esos .jar pueden utilizarse en otros proyectos maven en el mismo ordenador.
    5. **deploy**: Copia el fichero .jar a un servidor remoto, poniéndolo disponible para cualquier proyecto maven con acceso a ese servidor remoto.


* **Para qué sirven los plugins**

    Fragmento o componente de codigo hecho para ampliar las funciones de un programa o una herramienta.

* **Qué es y para qué sirve el repositorio central de maven**

    El repositorio central de Maven son una serie de librerias que sirven para el desarrollo y construccion de software. 
    Esto sirve para permitir que el proyecto tenga artefactos implementados en el repositorio central.
    
### *PARA QUE SIRVE Y COMO SE USA "gitignore"*

 Gitignore sirve basicamente para configurar un respositorio y hacer que archivos que no queremos que sean 
  agregados automaticamente no se agreguen al momento de subir o
  actualizar archivos en nuestro repositorio. 
