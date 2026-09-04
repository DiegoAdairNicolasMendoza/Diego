\# Auditoría con IA y Corrección de Historias de Usuario



\## 1. Prompt Utilizado para la Auditoría

> \*"Actúa como un Agile Coach y Auditor de Software experto. Analiza las siguientes Historias de Usuario desarrolladas para un sistema de información artesanal en la región Mixteca de Oaxaca. Evalúa si cumplen con la estructura 'Como/Quiero/Para', si los Criterios de Aceptación son verificables y no ambiguos, y si consideran restricciones de conectividad y dispositivos de gama baja. Identifica riesgos de alcance (especialmente sobre el concepto de 'autenticidad') y sugiere correcciones."\*



\---



\## 2. Hallazgos Identificados por la IA

1\. \*\*Ambigüedad en el alcance de "Autenticidad":\*\* La versión inicial de la HU-01 utilzaba la palabra \*"para verificar la autenticidad real de la artesanía"\*. La IA indicó que un sistema no puede prometer "autenticidad" por sí mismo.

2\. \*\*Criterios no verificables:\*\* Se incluían frases como \*"la imagen debe cargar rápido"\*, lo cual es ambiguo.

3\. \*\*Omisión de limitaciones técnicas:\*\* No se especificaban límites de peso de imagen ni comportamientos fuera de línea (\*offline\*).



\---



\## 3. Matriz de Decisiones del Equipo (Aceptaciones y Rechazos)



| Sugerencia de la IA | Decisión del Equipo | Argumentación y Justificación de la Decisión |

| :--- | :---: | :--- |

| Cambiar el término "Autenticidad" por "Trazabilidad de origen y evidencias proporcionadas por el productor". | \*\*ACEPTADO\*\* | \*\*Correcto.\*\* No podemos garantizar legal o automáticamente la autenticidad. El sistema únicamente presenta la evidencia registrada. |

| Definir métricas cuantitativas en criterios de aceptación (máx. 150 KB por foto, respuesta < 2s). | \*\*ACEPTADO\*\* | \*\*Correcto.\*\* Otorga verificabilidad a los criterios de aceptación durante la fase de pruebas. |

| Agregar verificación mediante firma digital criptográfica / Blockchain en cada fotografía capturada. | \*\*RECHAZADO\*\* | \*\*Argumento:\*\* La complejidad técnica y el procesamiento requerido para firmas criptográficas en vivo sobrecargaría los dispositivos de gama baja y complicaría el uso a artesanos con poca experiencia digital. Se prioriza el almacenamiento ligero local. |



\---



\## 4. Historias Corregidas

\*(Las versiones corregidas correspondientes fueron integradas en la carpeta `/historias-de-usuario/`)\*

