
# Hello SSIS

SSIS es una plataforma para la creación de soluciones de integración de datos, como la migración de datos, la transformación de datos y la carga de datos (ETL - Extract, Transform, Load). Se utiliza principalmente en Visual Studio con SQL Server para diseñar y gestionar flujos de trabajo y tareas de integración de datos.


## Funciones y Usos Principales de SSIS

- **Extracción de Datos**: SSIS puede extraer datos desde una variedad de fuentes, incluyendo bases de datos SQL Server, archivos planos, archivos XML, bases de datos de otros sistemas, servicios web, y más.

- **Transformación de Datos**: SSIS proporciona una amplia gama de transformaciones para limpiar, modificar y preparar los datos antes de cargarlos en el destino. Esto incluye operaciones como agregaciones, conversiones de tipos de datos, fusiones, filtrado, ordenación y mucho más.

- **Carga de Datos**: SSIS puede cargar datos en múltiples destinos, como bases de datos SQL Server, archivos, bases de datos de otros sistemas, y más. Permite la configuración detallada de cómo se manejan los errores y la lógica de reintento.

- **Automatización de Tareas**: SSIS permite automatizar tareas rutinarias de administración de datos, como la copia de seguridad de bases de datos, la generación de informes y la sincronización de bases de datos.

- **Integración con Otros Sistemas**: SSIS puede integrarse con otros sistemas mediante componentes específicos para conectarse a diferentes tipos de datos y servicios.

## Requisitos previos

Para utlizar Hello SSIS, asegúrate de tener instalado lo siguiente:

- Visual studio 2022
- Almacenamiento y procesamiento de datos (Server Data Tools, Herramientas de desarrollo de .NET Framework 4.7.2)
- Extensión: SQL Server Integration Services Projects 2022
- SQL Server Management Studio 2019 (SSMS) y cambiar el estado de los protocolos Named Pipes and TCP/IP a Enabled 


## Instalación

Sigue estos pasos para instalar y configurar Hello SSIS en tu entorno local:

1. Clona el repositorio  desde GitHub:
```bash 
git clone https://github.com/SrDavidAntonio2003/SSIS.git
```

## Ejecución

- Crear base datos SSISIntro en SSMS
- Ejecutar primero el paquete llamado "createTableBD" y luego "ImportarXMLFile"