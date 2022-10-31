# Comandos que se pueden utilizar en powershell

## Cambiar nombre de una carpeta

`Renama-Item 'nombre de archivo' 'nuevo nombre de archivo' `

## Crear archivo

`New-Item 'nombre de archivo' `

`mkdir 'Nombre de carpeta' `

## Para abrir paneles en la terminal

`shift + {seleccionar terminal en opciones}`

## Redimensionar paneles

`alt + shift + tecla de direcion`

## Cerrar paneles

`ctr + shift + w`

## Duplicar paneles

`alt + shitf + d`

## Abrir paleta de comandos 

`ctl + shift + p`

## Ver servicios disponibles

`Get-Service` _Ver servicios disponibles_

`Get-Service {nombre inicial de sevicio}*` _Para buscar servicio por su nombre o iniciales_

## Iniciar un servicio

**Iniciar powershell como administrador para ejecutar estos comandos**

`Start-Service {nombre del servicio}`

## Para entrar a pantalla completa 

`{F11} o {fn +F11}`

## Comando para iniciar proyecto de _RestClinica_ con spring 

` & 'C:\Users\pc\.vscode\extensions\redhat.java-1.12.0-win32-x64\jre\17.0.4.1-win32-x86_64\bin\java.exe' '-XX:+ShowCodeDetailsInExceptionMessages' '@C:\Users\pc\AppData\Local\Temp\cp_6heiq38suka6qkdq14qrbyr9z.argfile' 'com.example.RestClinicaApplication'`

## Ejecutar todos los test de un proyecto (_Para ejecutar los test hay que ubicarse en la raiz del proyecto_)

`mvn test`

## Ejecutar todos los test de una clase de spring boot con mvn

`mvn test -Dtest=nombreClase test`
## Ejecutar test de un metodo de una clase de spring boot con maven  _Importante tener instalado maven_ 

`mvn test -Dtest=nombreClase#nombreMetodo test`
