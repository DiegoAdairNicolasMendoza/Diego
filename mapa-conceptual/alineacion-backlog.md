\# Concordancia Mapa Conceptual – Backlog del Sistema



\## 1. Alineación por Fases del Mapa Conceptual

\* \*\*Fase 1: Capta y Registro Local (Módulo Productor)\*\*

&#x20; \* `HU-02`: Registro de Evidencias de Elaboración por el Productor.

&#x20; \* `HU-03`: Selección asistida de materiales y técnicas regionales.

\* \*\*Fase 2: Optimización y Almacenamiento Adaptativo (Módulo Datos)\*\*

&#x20; \* `HU-04`: Compresión automática de medios en dispositivos de gama baja.

&#x20; \* `HU-05`: Sincronización en segundo plano al detectar red.

\* \*\*Fase 3: Consulta y Trazabilidad Transparente (Módulo Comprador)\*\*

&#x20; \* `HU-01`: Consulta de Proceso y Materiales en Redes de Baja Conectividad.

&#x20; \* `HU-06`: Visualización de ficha técnica con atribución clara al productor.



\---



\## 2. Ajustes Decididos durante la Alineación

\- \*\*Historias Divididas (\*Story Splitting\*):\*\* La historia original de "Registro del producto" se dividió en dos: una para la captura de datos/imágenes (`HU-02`) y otra exclusiva para el mecanismo de compresión y sincronización diferida (`HU-04`).

\- \*\*Historias Reescritas:\*\* Se reescribió la historia de visualización del comprador para forzar el uso de almacenamiento en caché (\*offline first\*).

\- \*\*Fase Adicionada al Mapa:\*\* Se detectó la falta de una fase intermedia de "Acondicionamiento de datos", la cual se añadió al mapa conceptual para representar el paso donde las imágenes se procesan para no saturar el ancho de banda.

