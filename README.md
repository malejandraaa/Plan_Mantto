# Plan_Mantto

En esta carpeta encontrarás todos los archivos necesarios para ejecutar directamente desde MATLAB la interfaz gráfica creada para un plan de mantenimiento preventivo de un simulador de vuelo.

El archivo madre o inicial que permite la correcta ejeución de los demás es llamado PAM22. Este archivo llama los demás archivos creados para cada mes e incluso el de análisis estadístico, según la necesidad.

Cada archivo contiene informción especifica para cada mes y podrá ser modificado según la necesidad.

Es indispensable descargar el software Ghostscript según su sistema operativo, ya que este será el encargado de unir los pdfs creados de manera individual del plan de mantenimiento en un solo pdf. Puede encontrarlo en https://www.ghostscript.com/releases/gsdnld.html

La carpeta append_pdfs debe ser descomprimida en la misma carpeta donde esten guardados todos los archivos. En caso de que al ejecutarse el código se presente algun error relacionado con esta función, se deben seguir los siguientes pasos.
1. En la ventana principal de MATLAB, en la pestaña de HOME, en el apartado ENVIRONMENT, seleccionar SET PATH.
2. Seleccionar ADD WITH SUBFOLDERS.
3. Seleccionar la carpeta append_pdfs (ya descomprimida).
4. Seleccionar SAVE.

