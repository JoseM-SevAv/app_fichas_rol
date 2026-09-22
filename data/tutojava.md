# Tutorial de java

### 1. Instalación de java y visual studio code
### 2. Puesta a punto y primer "Hola, Mundo"

### 1. Instalación de java y visual studio code.

- Descarga el documento "https://download.oracle.com/java/27/latest/jdk-27_windows-x64_bin.exe" en la página web de [Oracle](https://www.oracle.com/java/technologies/downloads/#jdk27-windows), recuerda que buscamos la versión jdk27 para Windows 10 en nuestro caso.
- Una vez descargado procedemos a instalarlo, es el típico instalador de siguiente, siguiente, siguiente, finalizar, no tiene perdida.
- Para asegurarnos de que se ha instalado correctamente abriremos una consola de comandos como puede ser Windows PowerShell o el Símbolo de sistema, aquí escribiremos el comando "java -version" (sin comillas). Si ha funcionado debería aparecer una respuesta como esta: 

<div align="center">
    <img src="https://github.com/JoseM-SevAv/app_fichas_rol/blob/main/imagenes/powershell.png" height = "500 px"/>
</div>

- Como Entorno de desarrollo integrado podemos usar [Visual Studio Code](https://code.visualstudio.com/) para Windows, (aunque [intelliJ Idea](https://www.jetbrains.com/idea/download/other/) también es una opción).
- En el caso de Visual Studio Code necesitamos además instalar una extensión en el menú de extensiones, usaremos la extensión de Java de Oracle: 

<div align="center">
    <img src="https://github.com/JoseM-SevAv/app_fichas_rol/blob/main/imagenes/Visualstudio.png" height = "700 px"/>
</div>

- Una vez instalada la extensión crearemos una nueva carpeta con un archivo nuevo cuya nombre sea "holamundo.java" y escribiremos lo siguiente en dicho archivo:

public class holamundo {
    public static void main(String[] args) {
        System.err.println("Hola, Mundo");        
    }
}

- Para correr este archivo pulsaremos el botón de abajo de correr y debugear (ojo el propio Visual Studio debe reconocerlo como archivo java primero):

