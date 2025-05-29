## Descripción del Dataset

**Nombre de archivo**: "Tierra_Del_Fuego_Delitos", ubicado en "data/raw/Tierra_Del_Fuego_Delitos.xlsx" 

**Instancias**: 49 filas

- Sólo 37 de estas 49 filas serán útiles.

- Existen 12 filas irrelevantes que incluyen metadatos y espacios en blanco que no se tendrán en cuenta a futuro.

**Características (columnas)**: 126 columnas


- La primera columna "Delitos con intervención policial por mes, según tipo de delito" describe el tipo de delito y mes/año, desde el año 2014 hasta el año 2023.

- Las columnas 2–126 corresponden a los conteos mensuales de cada delito (Enero 2014 hasta Agosto 2023).  

- Sólo 117 de estas 126 columnas serán útiles. La primera columna descriptiva que especifica los delitos junto con las 116 columnas con datos mensuales desde enero 2014 hasta agosto 2023. Las 9 columnas vacías posteriormente se eliminarán.

**Tipos de datos**:  

- Todas las columnas importan actualmente como "object" (texto), por el formato original de Excel.  

- En los próximos pasos conviene convertir las fechas y los conteos a "datetime" e "int".  

## Origen y fecha de adquisición

- **Fuente**: Instituto Provincial de Análisis e Investigación, Estadística y Censos (AeIAS), con datos de la Dirección de Análisis Criminal, Policía TDF.  

- **Fecha de adquisición**: 12 de mayo de 2025 (fecha de descarga del dataset).  

- **Licencia / Dominio público**: Público, provisto por el organismo oficial.  

## Preprocesamiento realizado

- Por el momento solo se identificaron las filas (37 de 49) y columnas útiles (117 de 126). No se modificó el archivo original. El dataset permanece crudo y listo para limpieza.