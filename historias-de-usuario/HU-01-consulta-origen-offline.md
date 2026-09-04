\# Historia de Usuario: HU-01 - Consulta de Proceso y Materiales en Redes de Baja Conectividad



\*\*Como:\*\* Comprador de artesanías que visita la región Mixteca.  

\*\*Quiero:\*\* Consultar las fotografías del proceso de elaboración, los materiales utilizados y el municipio de origen de la pieza de forma ligera y optimizada.  

\*\*Para:\*\* Conocer la procedencia y elaboración de la artesanía sin que la aplicación se trabe o dependa de una red de internet rápida.



\---



\### Criterios de Aceptación Verificables

\- \[ ] \*\*Dado que\*\* el comprador abre la ficha de información de una artesanía, \*\*cuando\*\* el sistema carga las fotografías del proceso, \*\*entonces\*\* las imágenes se sirven en formato comprimido (WebP/miniaturas) con un peso no mayor a 150 KB por imagen.

\- \[ ] \*\*Dado que\*\* el dispositivo se encuentra sin señal o con red intermitente, \*\*cuando\*\* el usuario solicita ver los detalles, \*\*entonces\*\* el sistema despliega la información técnica (materiales, localidad y técnica) guardada previamente en almacenamiento local/caché.

\- \[ ] \*\*Dado que\*\* la información es visualizada por el comprador, \*\*cuando\*\* lee la ficha del producto, \*\*entonces\*\* el sistema muestra explícitamente una leyenda que indica: \*"Información y evidencias recopiladas y declaradas directamente por el productor local"\*.

