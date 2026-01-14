# Tarea Evaluación Módulo 11 – Desarrollo de Interfaces

## Descripción del proyecto
Este repositorio corresponde a la **Tarea Evaluación del Módulo 11: Desarrollo de Interfaces**.  
El objetivo de la práctica es completar el ciclo real de distribución de una aplicación JavaFX, partiendo del desarrollo en IntelliJ y Maven hasta la creación de un instalador para Windows.

La aplicación utilizada es una **aplicación JavaFX básica**, creada únicamente con fines académicos para demostrar el proceso de empaquetado y distribución.

---

## Estructura del repositorio

El repositorio se divide en dos carpetas principales:

Entrega_Modulo_11
├─ aplicacion
└─ instalador


### 📁 Carpeta `aplicacion`
Contiene el **proyecto JavaFX completo desarrollado en IntelliJ** con Maven.

Dentro de esta carpeta se pueden encontrar:
- Código fuente (`src`)
- Archivo de configuración Maven (`pom.xml`)
- Recursos JavaFX (`.fxml`)
- Carpeta `target` generada por Maven

#### 🔹 JAR ejecutable
Para localizar el JAR generado:
1. Entrar en la carpeta `aplicacion`
2. Entrar en la carpeta `target`
3. En esta carpeta se encuentra el archivo:

aplicacionbasica-1.0-SNAPSHOT.jar


Este JAR ha sido generado mediante Maven.

🔹 Ejecutable (.exe)
Dentro de la carpeta target también se encuentra la carpeta dist, creada al usar la herramienta Launch4j.

En esta carpeta:

Se encuentra el archivo .exe generado a partir del JAR

Launch4j es la herramienta que convierte el JAR en un ejecutable de Windows

Launch4j es la aplicación que “tenía un 4 en el nombre” y se ha utilizado para crear el ejecutable .exe a partir del JAR.

📁 Carpeta instalador
Contiene todos los archivos relacionados con la creación del instalador para Windows mediante Inno Setup.

En esta carpeta se incluyen:

El script .iss generado por Inno Setup

El instalador final .exe

Archivos necesarios para el proceso de instalación

El instalador:

Copia la aplicación en el sistema

Crea accesos directos

Permite desinstalar correctamente la aplicación

Herramientas utilizadas
IntelliJ IDEA: desarrollo del proyecto JavaFX

JavaFX: interfaz gráfica

Maven: gestión del proyecto y generación del JAR

Launch4j: creación del ejecutable .exe

Inno Setup: creación del instalador para Windows

Git y GitHub: control de versiones y entrega del proyecto
