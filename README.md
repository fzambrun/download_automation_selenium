# download_automation_selenium

Descarga Automática con Selenium
 
Este es una script que descarga automáticamente las declaraciones juradas de producción de las operadoras petroleras en Argentina (CAPIV). Cada reporte tiene los datos de áreas, producción, inyección de agua, método de extracción, entre otros.
 
La descarga se realiza de la página de la secretaría de energía utilizando selenium como motor de automatización.
Como se descarga un archivo por empresa, por mes y en formato .xls, luego , en el mismo script, se unifican limpian y estructuran para almacenar la información en una única base de datos en formato .csv
