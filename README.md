# TelecomX: Segundo challenge del curso Data Science con Python del programa Alura Latam y Oracle Next Education.  

## Objetivos:
* El caso de estudio se centra en la pérdida de clientes de una empresa de telecomunicaciones llamada Telecom X.
* El análisis final debe indicar las razones que hacen que, los clientes abandonen la contratación de servicios de esta empresa.
* Aplicación práctica del conocimiento adquirido en un escenario real, mediante el uso de métodos y técnicas de:
    * La limpieza y tratamiento de datos. La manipulación de grandes volúmenes de información exige la capacidad de identificar y corregir inconsistencias en los datos, como valores nulos, duplicados y datos fuera de estándar. Garantizar que los datos estén listos para el análisis es un paso esencial para obtener resultados precisos y confiables.
    * El análisis exploratorio de datos (EDA). La capacidad de aplicar estadísticas descriptivas y generar visualizaciones permite identificar patrones, tendencias y relaciones entre las variables. Esto ayuda a formular hipótesis y generar insights que pueden influir en decisiones estratégicas dentro de la empresa.
    * Aplicar conocimientos esenciales para el análisis de grandes volúmenes de datos en un contexto real, donde tus hallazgos podrán impactar directamente en las estrategias de la empresa para mejorar el principal problema que están enfrentando.
    * Entender cómo la ciencia de datos puede aplicarse para resolver problemas reales que enfrentan las empresas en el mercado.

## Catracterísticas:
* El conjunto de datos a tratar se encuentra en formato JSON y disponible a través de el enlace https://raw.githubusercontent.com/alura-cursos/challenge2-data-science-LATAM/main/TelecomX_Data.json
* El desafío se dividió en 4 fases:
  * Extracción: Extraer y pasar los datos a un data frame de Pandas. Las columnas con datos anidados deben expandirse para poder tener la visión completa del set de datos.
  La limpieza de los datos inicia con la comprobación de incoherencias, valores nulos, identificación de valores únicos, verificación de patrones en los datos que puedan aportar más información.
  * Transformación: Para corregir las inconsistencias encontradas y obtener un data frame lo más limpio posible, se aplican métodos como: 
    * Renombrar columnas para mejorar la lectura, consistencia en los nombres y evitar errores en la lectura y procesamiento de modelos estadísticos avanzados.
    * Eliminación de filas o columnas que no aporten valor al análisis.
    * Sustitución de caracteres especiales, espacios en blanco o, que sean producto del formato del archivo.
    * Transformación de columnas con valores 'Si', 'No' en binarias.
    * Sustitución de total o parcial de datos, de valores faltantes o redundantes, previa justificación.
    * Cambio del tipo de dato de la columna para una correcta aplicación de funciones y comparaciones, según el tipo de dato.
    * Creación de columnas como medio para comprobar la información recibida, en otras columnas.
  * Carga y análisis: Se aplican critérios que permitan estudiar la información corregida y que den información sobre el porque la empresa, tiene una tasa alta de pérdida de clientes.
    En esta fase se aplican:
      * Análisis de las discrepancias encontradas.
      * Inclusión de las columnas que validen la información.
      * Aplicación de un análisis descriptivo con la función .describe()
      * Distribución de la evasión de clientes en torno a la variable churn.
      * Recuento de la evasión de clientes por variables categóricas y númericas.
      * Análisis de la correlación de variables entorno a la variable churn.
      * Visualizar los resultados de los análisis realizados.
  * Informe final: Contiene el detalle de los resultados obtenidos, conclusiones y recomendaciones.

## Tecnologías utilizadas
  * Google Colaboratory
    * Código Python 
  * JSON: Formato de archivo
  * Librerías
    * Pandas: Procesamiento y análisis de datos.
    * Numpy: Cálculo científico.
    * Matplotlib, Seaborn: Visualización de resultados
    
## Instalación y uso
   * Descarga el archivo .ipynb de este repositorio:
   * Abre en un nuevo Notebook en google Colaboratory y selecciona el archivo .ipynb descargado.

## Licencia
   * Este desarrollo está amparado por la licencia MIT, por lo que puede ser obtenido, modificado y distribuido libremente.

     * Condiciones
       * El aviso de copyright original y el texto de la licencia deben conservarse en el software redistribuido. 
       * El software se proporciona "tal cual", sin garantía de ningún tipo. 
       * Los autores o titulares de los derechos de autor no serán responsables de ningún reclamo, daños u otra responsabilidad 

     * Uso 
       * Para aplicar la licencia MIT, puedes: 
         * Crear un archivo de texto (normalmente llamado LICENSE o LICENSE.txt) en la raíz de tu código fuente.
         * Copiar el texto de la licencia en el archivo
         * Reemplazar [year] con el año actual y [fullname] con el nombre (o nombres) de los titulares de los derechos de autor.
