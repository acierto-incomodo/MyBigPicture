# MyBigPicture

MyBigPicture es un proyecto inspirado en la interfaz de Steam Big Picture, diseñado para proporcionar una experiencia fluida y accesible para usuarios con mandos en Windows. Este proyecto es una interfaz de usuario alternativa que permite a los usuarios interactuar con su PC de una manera optimizada para controladores, similar a la interfaz de consola de Steam.

## Características

- Interfaz optimizada para mandos (PS4, Xbox, etc.).
- Sistema de navegación fluido y atractivo.
- Acceso a las aplicaciones y juegos directamente desde la interfaz.
- Instalador configurable con soporte multi-idioma (Inglés y Español).
- Registro de protocolo y soporte de desinstalación.

## Requisitos

- **Sistema operativo**: Windows 7 o superior.
- **Lenguaje de programación**: C# y tecnologías asociadas.
- **Requisitos adicionales**: 
  - Microsoft .NET Framework 4.7.2 o superior.
  - Certificado de firma de código (si deseas firmar el instalador).

## Instalación

### Usando el instalador

1. Descarga el archivo `MyBigPictureInstaller.exe`.
2. Ejecuta el instalador y sigue las instrucciones en pantalla.
3. El instalador registrará los protocolos necesarios y creará los accesos directos.

### Manualmente

1. Descarga el código fuente.
2. Compílalo utilizando Visual Studio con .NET Framework 4.7.2 o superior.
3. Crea un archivo `setup.exe` utilizando Inno Setup.
4. Ejecuta el archivo resultante para instalar la aplicación.

## Idiomas

El instalador de MyBigPicture soporta los siguientes idiomas:
- **Inglés** (por defecto).
- **Español** (disponible como opción en la instalación).

El archivo de licencia se adapta al idioma seleccionado durante la instalación.

## Uso

Una vez instalado, MyBigPicture se lanzará automáticamente y podrás navegar por la interfaz utilizando un mando. Accede a tus aplicaciones y juegos con una experiencia adaptada para mandos.

## Contribuciones

Si deseas contribuir al proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama para tu nueva funcionalidad (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit de ellos (`git commit -am 'Añadir nueva funcionalidad'`).
4. Sube tus cambios a tu fork (`git push origin feature/nueva-funcionalidad`).
5. Abre un pull request para que tus cambios sean revisados.

## Licencia

Este proyecto está bajo la licencia [MIT License](LICENSE).

## Contacto

Si tienes preguntas o sugerencias, no dudes en contactar a [GitHub](https://github.com/acierto-incomodo).
