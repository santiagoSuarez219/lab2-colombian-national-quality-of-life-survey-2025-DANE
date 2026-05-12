# Detalle de variables por módulo — ECV 2025
Diccionario completo de las **249 variables** distribuidas en los tres módulos temáticos cargados para el Laboratorio 2 (Capítulos D, G e I de la Encuesta Nacional de Calidad de Vida 2025 del DANE).

Cada tabla lista el código DANE de la variable, el tipo de dato declarado en el diccionario oficial, y la descripción extraída textualmente del cuestionario. Los códigos numéricos antes de cada descripción (p. ej. `1.`, `8A.`) corresponden a la numeración del formulario original.

**Total de variables:** 249 (78 + 82 + 89, contando llaves identificadoras repetidas en cada módulo).

**Estructura común a los tres módulos:** las cinco llaves `DIRECTORIO`, `SECUENCIA_ENCUESTA`, `SECUENCIA_P`, `ORDEN` y `FEX_C` aparecen en todos los módulos; permiten unirlos a nivel de persona.

---

## Módulo D — Características y composición del hogar
Aplica a **todas las personas del hogar**. Registro maestro de demografía y bienestar subjetivo.

**Total de variables en este módulo:** 78

### Llaves identificadoras y peso poblacional

| Código | Tipo | Descripción |
|---|---|---|
| `DIRECTORIO` | NUMBER | DIRECTORIO |
| `SECUENCIA_ENCUESTA` | NUMBER | Número de la persona dentro del hogar |
| `SECUENCIA_P` | NUMBER | Número del Hogar dentro de la vivienda |
| `ORDEN` | NUMBER | Número de la persona dentro del hogar |
| `FEX_C` | NUMBER | Factor de expansión |

### Variables temáticas del Capítulo D

| Código | Tipo | Descripción |
|---|---|---|
| `P6016` | NUMBER | Número de orden de la persona que proporciona la información: |
| `P1894` | NUMBER | 1. Tipo de documento de identidad |
| `P6020` | NUMBER | 2. Sexo al nacer: |
| `P6034` | NUMBER | 3. ¿Cuál es la fecha de nacimiento de ...? |
| `P6040` | NUMBER | 4. ¿Cuántos años cumplidos tiene ...? |
| `P6051` | NUMBER | 5. ¿Cuál es el parentesco de ... con el jefe o la jefa de este hogar? |
| `P5502` | NUMBER | 6. Actualmente ...: |
| `P6071` | NUMBER | 7. El (la) cónyuge de ... ¿Vive en este hogar? |
| `P6071S1` | NUMBER | No. de orden |
| `P756` | NUMBER | 8. ¿Dónde nació ________? |
| `P756S1` | NUMBER | Departamento |
| `P756S2` | NUMBER | Municipio |
| `P756S3` | NUMBER | En otro país |
| `P3510` | NUMBER | 8A. ¿Qué nacionalidad tiene? |
| `P3510S1` | NUMBER | País o países de nacionalidad (además de colombiana) |
| `P3510S1A1` | NUMBER | 1. Estadounidense |
| `P3510S1A2` | NUMBER | 2. Española |
| `P3510S1A3` | NUMBER | 3. Venezolana |
| `P3510S1A4` | NUMBER | 4. Ecuatoriana |
| `P3510S1A5` | NUMBER | 5. Panameña |
| `P3510S1A6` | NUMBER | 6. Peruana |
| `P3510S1A7` | NUMBER | 7. Costarricense |
| `P3510S1A8` | NUMBER | 8. Argentina |
| `P3510S1A9` | NUMBER | 9. Francesa |
| `P3510S1A10` | NUMBER | 10. Italiana |
| `P3510S1A11` | NUMBER | 11. Otra |
| `P3510S2` | NUMBER | País o países de nacionalidad (sin colombiana) |
| `P3510S2A1` | NUMBER | 1. Estados Unidos |
| `P3510S2A2` | NUMBER | 2. España |
| `P3510S2A3` | NUMBER | 3. Venezuela |
| `P3510S2A4` | NUMBER | 4. Ecuador |
| `P3510S2A5` | NUMBER | 5. Panamá |
| `P3510S2A6` | NUMBER | 6. Perú |
| `P3510S2A7` | NUMBER | 7. Costa Rica |
| `P3510S2A8` | NUMBER | 8. Argentina |
| `P3510S2A9` | NUMBER | 9. Francia |
| `P3510S2A10` | NUMBER | 10. Italia |
| `P3510S2A11` | NUMBER | 11. Otro país |
| `P6074` | NUMBER | 9. ¿... siempre ha vivido aquí en este municipio? |
| `P755` | NUMBER | 10. ¿Dónde vivía ..., hace 5 años? |
| `P755S1` | VARCHAR2 | Departamento |
| `P755S2` | VARCHAR2 | Municipio |
| `P755S3` | VARCHAR2 | En otro país |
| `P754` | NUMBER | 11. El lugar donde vivía ... hace 5 años era: |
| `P753` | NUMBER | 12. ¿Dónde vivía ..., hace 12 meses? |
| `P753S1` | VARCHAR2 | Departamento |
| `P753S2` | VARCHAR2 | Municipio |
| `P753S3` | VARCHAR2 | En otro país |
| `P752` | NUMBER | 12A. El lugar donde vivía ... hace 12 meses era: |
| `P1662` | NUMBER | 13. ¿Cuál fue el principal motivo por el que ... Cambió el lugar donde residia hace 12 meses? |
| `P6081` | NUMBER | 14. El padre de ... ¿vive en este hogar? |
| `P6081S1` | NUMBER | No. de orden |
| `P6087` | NUMBER | 15. ¿Cuál es o fue el nivel de educación más alto alcanzado por el padre de ...? |
| `P6083` | NUMBER | 16. La madre de ... ¿vive en este hogar? |
| `P6083S1` | NUMBER | No. de orden |
| `P6088` | NUMBER | 17. ¿Cuál es o fue el nivel de educación más alto alcanzado por la madre de ...? |
| `P6080` | NUMBER | 18. De acuerdo con su cultura, pueblo o rasgos físicos, ... es o se reconoce comó: |
| `P2057` | NUMBER | 20. ¿Usted se considera campesino/a? |
| `P2059` | NUMBER | 21. ¿Usted considera que alguna vez fue campesino/a? |
| `P2061` | NUMBER | 22. ¿Usted considera que la comunidad en que vive es campesina? |
| `P1895` | NUMBER | 23. En general, ¿qué tan satisfecho/a se siente ... con su vida actualmente? |
| `P1896` | NUMBER | 24. En general, ¿qué tan satisfecho/a se siente ... con su ingreso actualmente? |
| `P1897` | NUMBER | 25. En general, ¿qué tan satisfecho/a se siente ... con su salud actualmente? |
| `P1898` | NUMBER | 26. En general, ¿qué tan satisfecho/a se siente ... con su nivel de seguridad actualmente? |
| `P1899` | NUMBER | 27. En general, ¿qué tan satisfecho/a se siente ... con su trabajo/actividad actualmente? |
| `P3175` | NUMBER | 28. En general, ¿qué tan satisfecho/a se siente _____ con su tiempo libre? |
| `P1901` | NUMBER | 29. ¿Qué tan feliz se sintió ... el día de ayer? |
| `P1903` | NUMBER | 30. ¿Qué tan preocupado/a se sintió ... el día de ayer? |
| `P1904` | NUMBER | 31. ¿Qué tan triste se sintió ... el día de ayer? |
| `P1905` | NUMBER | 32. ¿Qué tanto considera ... que las cosas que hace en su vida valen la pena? |
| `P1927` | NUMBER | 33. ¿En cuál escalón diría usted que se encuentra parado/a en este momento? |
| `P3038` | NUMBER | 34. ¿Usted siente atracción sexual o romántica por? |
| `P3039` | NUMBER | 35. ¿Usted se reconoce como? |

---

## Módulo G — Educación
Aplica a **todas las personas del hogar**. Alfabetización, asistencia escolar, nivel educativo, gastos educativos.

**Total de variables en este módulo:** 82

### Llaves identificadoras y peso poblacional

| Código | Tipo | Descripción |
|---|---|---|
| `DIRECTORIO` | NUMBER | DIRECTORIO |
| `SECUENCIA_ENCUESTA` | NUMBER | Número de persona dentro del hogar |
| `SECUENCIA_P` | NUMBER | Número de hogar dentro de la vivienda |
| `ORDEN` | NUMBER | Número de persona dentro del hogar |
| `FEX_C` | NUMBER | Factor de expansión |

### Variables temáticas del Capítulo G

| Código | Tipo | Descripción |
|---|---|---|
| `P6160` | NUMBER | 1. ¿Sabe leer y escribir? |
| `P8586` | NUMBER | 2. ¿... actualmente estudia? (asiste al preescolar, escuela, colegio o universidad) |
| `P6218` | NUMBER | 3. ¿Cuál es la razón principal para que ... no estudie? |
| `P8587` | NUMBER | 4. ¿Cuál es el nivel educativo más alto alcanzado por ... y el último año o grado aprobado en ese nivel? |
| `P8587S1` | NUMBER | Grado o año aprobado |
| `P6211` | NUMBER | 5. ¿Cuántos años de estudios superiores (técnicos, tecnológicos, universitarios, de posgrado, etc.) ha realizado y aprobado? |
| `P1088` | NUMBER | 6. ¿En que nivel está matriculado/a ... y qué grado o año cursa? |
| `P1088S1` | NUMBER | Grado o año que cursa |
| `P6216` | NUMBER | 7. ¿Cuántos años de estudios superiores (técnicos, tecnológicos, universitarios, de postgrado, etc.) ha realizado y aprobado? |
| `P5673` | NUMBER | 8. El establecimiento donde estudia ... es: |
| `P5674` | NUMBER | Subsidiado? |
| `P1101` | NUMBER | 9. ¿En qué jornada estudia ...? |
| `P3336` | NUMBER | 10. ¿En qué modalidad(es) o a través de qué medio(s) se encuentra estudiando ... actualmente? |
| `P3336S1` | NUMBER | 1. Presencial |
| `P3336S2` | NUMBER | 2. Virtual (a través de internet en computador de escritorio, portátil, tableta o celular) |
| `P3336S3` | NUMBER | 3. Alternancia entre presencial y virtual |
| `P3336S7` | NUMBER | 4. Otro |
| `P3514` | NUMBER | 11. El establecimiento educativo se localiza en: |
| `P3514S1` | NUMBER | Departamento |
| `P3514S2` | NUMBER | Municipio |
| `P6223` | NUMBER | 11A. Este establecimiento está ubicado en: |
| `P4693` | NUMBER | 12. ¿Qué medio de transporte utiliza principalmente ... para ir a la institución a la que asiste? |
| `P6167` | NUMBER | 13. ¿Cuántos minutos gasta para ir a la institución a la que asiste? |
| `P6180` | NUMBER | 14. ¿Recibe ... en el plantel educativo alimentos (desayunos, refrigerios, almuerzos) en forma gratuita o por un pago simbólico? |
| `P6180S1` | NUMBER | a. ¿Valor que paga DIARIO? |
| `P6180S2` | NUMBER | b. Si lo tuviera que comprar en otra parte, ¿cuánto pagaría al día por lo que recibe? |
| `P3337` | NUMBER | 15. ¿... tuvo comunicación con sus maestros la semana pasada? |
| `P3339` | NUMBER | 16. ¿Cuál(es) medio(s) utiliza ... para comunicarse con sus maestros? |
| `P3339S1` | NUMBER | 1. Mensaje de texto |
| `P3339S2` | NUMBER | 2. Correo electrónico |
| `P3339S3` | NUMBER | 3. Teléfono (llamadas de voz) |
| `P3339S4` | NUMBER | 4. Aplicaciones en línea (videoconferencias en Zoom, Microsoft Teams, Skype, Google Meet, WebEx, Classroom, Integra, Google for Education, Aprender Digital contenido para todos) |
| `P3339S5` | NUMBER | 5. Whatsapp |
| `P3339S7` | NUMBER | 6. Interacción personal |
| `P3339S6` | NUMBER | 7. Otro |
| `P3341` | NUMBER | 17. Durante este AÑO ESCOLAR el hogar pagó: ¿Matriculas para ...? |
| `P3341S1` | NUMBER | 17a. Valor |
| `P3342` | NUMBER | 18. Durante este AÑO ESCOLAR el hogar pagó: ¿Uniformes para ...? |
| `P3342S1` | NUMBER | 18a. Valor |
| `P3343` | NUMBER | 19. Durante este AÑO ESCOLAR el hogar pagó: ¿Lista de útiles escolares, compra o alquiler de textos para ...? |
| `P3343S1` | NUMBER | 19a. Valor |
| `P3344` | NUMBER | 20. El hogar paga por: ¿Pensión para ...? |
| `P3344S1` | NUMBER | 20a. Valor Mensual |
| `P3345` | NUMBER | 21. El hogar paga por: ¿Transporte escolar para ...? |
| `P3345S1` | NUMBER | 21a. Valor Mensual |
| `P3346` | NUMBER | 22. El hogar paga por: ¿Alimentación en el establecimiento educativo para ...? |
| `P3346S1` | NUMBER | 22a. Valor Mensual |
| `P3347` | NUMBER | 23. EL MES PASADO, ¿el hogar gastó en útiles (papel, lápices, cuadernos etc..) material escolar o fotocopias para ...? |
| `P3347S1` | NUMBER | 23a. Valor Mensual |
| `P3348` | NUMBER | 24. EL MES PASADO, el hogar realizó otros pagos como: bingos, salidas pedagógicas, etc. en el establecimiento educativo para ...? |
| `P3348S1` | NUMBER | 24a. Valor Mensual |
| `P8610` | NUMBER | 25. Durante este AÑO ESCOLAR, ¿... recibió beca en dinero o en especie para estudiar? |
| `P8610S1` | NUMBER | Valor $ |
| `P8610S2` | NUMBER | Frecuencia |
| `P6229` | NUMBER | 26. ¿De quién recibió la beca para estudiar? |
| `P8612` | NUMBER | 27. Durante este AÑO ESCOLAR, ¿ ... recibió subsidio en dinero o en especie para estudiar? |
| `P8612S1` | NUMBER | Valor ($) |
| `P8612S2` | NUMBER | Frecuencia |
| `P6238` | NUMBER | 28. ¿De quién recibió el subsidio para estudiar? |
| `P8614` | NUMBER | 29. Durante este AÑO ESCOLAR ,¿... ha recibido crédito educativo? |
| `P8614S1` | NUMBER | Valor ($) |
| `P8614S2` | NUMBER | Frecuencia |
| `P6202` | NUMBER | 30. ¿Quién le concedió el crédito educativo? |
| `P781` | NUMBER | 31. ¿Con quién permanece ... después de asistir al establecimiento educativo o durante la mayor parte del tiempo entre semana? |
| `P781S1` | VARCHAR2 | No. de orden |
| `P781S2` | NUMBER | Sexo: |
| `P782` | NUMBER | 32. ¿Cuántos años tiene esta persona? |
| `P783` | NUMBER | 33. ¿Cuál es el nivel educativo de esta persona? |
| `P3004` | NUMBER | 34. Cuáles de las siguientes actividades realiza _____ fuera de la jornada escolar: |
| `P3004S1` | NUMBER | 1. Participa en cursos, talleres o grupos artísticos (música, teatro, danza, pintura, etc.) |
| `P3004S2` | NUMBER | 2. Participa en cursos, talleres o gruposde ciencia y tecnología (computación, botánica, robótica, etc.) |
| `P3004S3` | NUMBER | 3. Asiste a cursos, prácticas o escuelas deportivas (futbol, gimnasia, natación, tenis, atletismo, etc.) |
| `P3004S4` | NUMBER | 4. Participa en grupos de estudio |
| `P3004S5` | NUMBER | 5.Sale al parque |
| `P3004S6` | NUMBER | 6.Lee libros |
| `P3004S7` | NUMBER | 7.Juega |
| `P3004S8` | NUMBER | 8.Ninguna de las anteriores |

---

## Módulo I — Tecnologías de Información y Comunicación
Aplica a **personas de 5 años y más**. Uso de dispositivos, frecuencia de internet, habilidades digitales, usos en línea.

**Total de variables en este módulo:** 89

### Llaves identificadoras y peso poblacional

| Código | Tipo | Descripción |
|---|---|---|
| `DIRECTORIO` | NUMBER | DIRECTORIO |
| `SECUENCIA_ENCUESTA` | NUMBER | Número de persona dentro del hogar |
| `SECUENCIA_P` | NUMBER | Número de hogar dentro de la vivienda |
| `ORDEN` | NUMBER | Número de persona dentro del hogar |
| `FEX_C` | NUMBER | Factor de expansión |

### Variables temáticas del Capítulo I

| Código | Tipo | Descripción |
|---|---|---|
| `P1910` | NUMBER | 1A. ¿Con qué frecuencia utiliza ... computador de escritorio (en cualquier lugar)? |
| `P1911` | NUMBER | 1B. ¿Con qué frecuencia utiliza ... computador portátil (en cualquier lugar)? |
| `P1912` | NUMBER | 1C. ¿Con qué frecuencia utiliza ... tableta (en cualquier lugar)? |
| `P1084` | NUMBER | 2. ¿Con qué frecuencia utiliza _____ internet (en cualquier lugar y desde cualquier dispositivo)? |
| `P1710` | NUMBER | 3. ¿Cuáles de las siguientes actividades sabe hacer ______ en el computador de escritorio, portátil, tableta o cuando utiliza internet: |
| `P1710S1` | NUMBER | 1.Usar procesadores de texto (Word, Google Docs, etc.)? |
| `P1710S2` | NUMBER | 2.Usar las funciones de copiar y pegar para duplicar o mover información entre documentos, dispositivos o en el almacenamiento utilizado través de internet? |
| `P1710S3` | NUMBER | 3. Enviar correos electrónicos con archivos adjuntos (documentos, fotos, videos, etc.)? |
| `P1710S4` | NUMBER | 4. Conectar o instalar dispositivos adicionales (ej. impresora, módem, cámara, etc.)? |
| `P1710S5` | NUMBER | 5. Usar fórmulas matemáticas básicas en una hoja de cálculo (Excel, Open Office Calc, etc)? |
| `P1710S6` | NUMBER | 6. Crear presentaciones mediante un programa especializado para ello (Power Point,Prezi, otros)? |
| `P1710S7` | NUMBER | 7. Transferir archivos entre dispositivos o por internet (computador, USB, celular, etc.)? |
| `P1710S8` | NUMBER | 8. Buscar, descargar, instalar o configurar programas computacionales (software) o aplicaciones? |
| `P1710S9` | NUMBER | 9. Utilizar un lenguaje de programación especializado? |
| `P1710S10` | NUMBER | 10. Implementar medidas de seguridad efectivas para proteger dispositivos y cuentas de internet (contraseñas fuertes, notificación de intento de conexión, etc.)? |
| `P1710S11` | NUMBER | 11. Limitar la difusión de datos o información personal en dispositivos, cuentas o aplicaciones de internet (nombre, información de contacto, fotografías, etc.)? |
| `P1710S12` | NUMBER | 12. Comprobar que las noticias o información que consulta o recibe a través de internet son ciertas o verdaderas? |
| `P765` | NUMBER | 4. Cuáles de los siguientes dispositivos utiliza ... para acceder a Internet: |
| `P765S1` | NUMBER | 1. Computador de escritorio? |
| `P765S2` | NUMBER | 2. Computador portátil? |
| `P765S3` | NUMBER | 3. Tableta? |
| `P765S4` | NUMBER | 4. Teléfono celular? |
| `P765S5` | NUMBER | 5. Consolas para juegos electrónicos (Play Station, X-box, Wii, PSP, Nintendo, Gameboy, etc.)? |
| `P765S6` | NUMBER | 6. Televisor inteligente? |
| `P765S7` | NUMBER | 7. Reproductores digitales de música video e imagen (MP3, MP4, Ipod)? |
| `P765S8` | NUMBER | 8. Otro |
| `P1085` | NUMBER | 5. ¿En cuáles de los siguientes sitios accede ... a Internet: |
| `P1085S1` | NUMBER | 1. En el hogar? |
| `P1085S2` | NUMBER | 2. En el trabajo? |
| `P1085S3` | NUMBER | 3. En la institución educativa? |
| `P1085S4` | NUMBER | 4. En centros de acceso público gratis? |
| `P1085S5` | NUMBER | 5. En centros de acceso público con costo (Café Internet)? |
| `P1085S6` | NUMBER | 6. En la vivienda de otra persona (pariente, amigo/a, vecino/a)? |
| `P1085S7` | NUMBER | 7. En desplazamiento de un sitio a otro? |
| `P1085S8` | NUMBER | 8. Otro sitio? |
| `P1083` | NUMBER | 6. ¿Para cuáles de los siguientes servicios o actividades utiliza ... Internet: |
| `P1083S1` | NUMBER | 1. Obtener información? (Excluir la búsqueda de información con fines de educación y aprendizaje) |
| `P1083S2` | NUMBER | 2. Enviar o recibir correos electronicos? |
| `P1083S3` | NUMBER | 3. Redes sociales? |
| `P1083S4` | NUMBER | 4. Comprar/ordenar productos o servicios? |
| `P1083S5` | NUMBER | 5. Banca electrónica y otros servicios financieros? |
| `P1083S6` | NUMBER | 6. Educación y aprendizaje? |
| `P1083S7` | NUMBER | 7. Trámites con entidades del gobierno (nacional, departamental o municipal)? |
| `P1083S8` | NUMBER | 8. Descargar software, imágenes, juegos, música o jugar en línea |
| `P1083S9` | NUMBER | 9. Consulta de medios de comunicación (televisión, radio, periódicos, revistas, medios digitales, etc)? |
| `P1083S10` | NUMBER | 10. Ver televisión, videos, películas u otro contenido audiovisual para entretenimiento |
| `P1083S12` | NUMBER | 11. Buscar trabajo (inscribirse en una plataforma, aplicación o convocatoria de empleo)? |
| `P1083S13` | NUMBER | 12. Servicios en la nube (guardar información, editar archivos, etc.)? |
| `P1083S14` | NUMBER | 13. Vender productos o servicios? |
| `P1083S15` | NUMBER | 14. Trabajar como requisito dentro de su empleo o actividad económica de independiente? |
| `P1083S16` | NUMBER | 15. Realizar llamadas o video llamadas (telefonía por Internet)? |
| `P1083S17` | NUMBER | 16. Publicar o intercambiar opiniones sobre las características y calidad de un bien o servicio? |
| `P1083S18` | NUMBER | 17. Subir contenido propio a un sitio web para ser compartido (texto, imágenes, videos, música, audios, fotos, software, etc.)? |
| `P1083S19` | NUMBER | 18. Consulta de información con fines educativos (tareas, trabajos, investigaciones, enciclopedias en línea)? |
| `P1083S20` | NUMBER | 19. Gestiones médicas (pedir citas, recibir atención, otros trámites) |
| `P1083S21` | NUMBER | 20. Usar herramientas de Inteligencia Artificial (chatbot, diseño, escritura, video) |
| `P1083S11` | NUMBER | 21. Otro |
| `P1929` | NUMBER | 7. ¿Cuál es la principal razón por la que __________ no utiliza internet?: |
| `P1082` | NUMBER | 8. ¿... tiene teléfono celular? |
| `P1082S1` | NUMBER | 1. Teléfono celular convencional |
| `P1082S2` | NUMBER | 2. Teléfono celular inteligente (smartphone) |
| `P803` | NUMBER | 9. EL MES PASADO ¿_____ realizó pagos por el servicio de telefonía celular (pospago o prepago)? |
| `P803S1` | NUMBER | Valor pagado |
| `P5504` | NUMBER | 10. A pesar de no tener teléfono celular, ….. utiliza teléfono celular? |
| `P5504S1` | NUMBER | Teléfono celular convencional |
| `P5504S2` | NUMBER | Teléfono celular inteligente (smartphone) |
| `P5505` | NUMBER | 11. ¿Por qué medio(s)…. utiliza el teléfono celular?: |
| `P5505S1` | NUMBER | 1. Un vendedor de minutos |
| `P5505S2` | NUMBER | 2. Prestado ocasionalmente por otra persona |
| `P769` | NUMBER | 12. ¿Con que frecuencia utiliza ... teléfono celular? |
| `P1080` | NUMBER | 13. Para cuál de las siguientes actividades utiliza … el teléfono celular: |
| `P1080S1` | NUMBER | 1. Llamadas personales o familiares? |
| `P1080S2` | NUMBER | 2. Llamadas laborales ? |
| `P1080S3` | NUMBER | 3. Mensajes de texto (SMS, mensajería instantánea, chat, etc.)? |
| `P1080S4` | NUMBER | 4. Navegación en Internet? |
| `P1080S5` | NUMBER | 5. Venta de minutos? |
| `P1080S6` | NUMBER | 6. Otras actividades? |
| `P804` | NUMBER | 14.¿Con que frecuencia escucha ... la señal de radio dentro del hogar? |
| `P805` | NUMBER | 15. Para cuáles de los siguientes servicios o actividades escucha ... la señal de radio: |
| `P805S1` | NUMBER | 1. Entretenimiento (música, deportes, variedades, humor) |
| `P805S2` | NUMBER | 2. Noticias |
| `P805S3` | NUMBER | 3. Información de interés comunitario |
| `P805S4` | NUMBER | 4. Educación y aprendizaje |
| `P805S5` | NUMBER | 5. Otra |

---

## Notas sobre la lectura del diccionario

- **Variables paraguas**: códigos como `P1083`, `P1710`, `P765`, `P3336` aparecen en el diccionario como preguntas únicas pero en los CSV vienen 100% NaN porque son **cabeceras de pregunta de respuesta múltiple**. La información real vive en sus sub-variables `Sx` (p. ej. `P1710S1`, `P1710S2`, ..., `P1710S12`). Ver Paso 2.3 del notebook para la detección automática de las 10 variables paraguas presentes.

- **Sub-variables anidadas**: `P3510S1` y `P3510S2` (rama de doble nacionalidad / nacionalidad extranjera) tienen sus propias hijas con patrón `P3510S1A1..A11` (banderas país por país).

- **Variables condicionadas por filtro**: muchas sub-preguntas (`P1710S*`, `P765S*`, `P1083S*`) solo se aplican a internautas frecuentes (`P1084 ∈ {1,2,3}`); fuera de ese universo el valor es NaN por diseño del cuestionario, no por omisión genuina.

- **Códigos numéricos vs etiquetas**: para las variables que se utilizan en la matriz consolidada de features (22 columnas), ver el [codebook detallado](codebook_matriz_features.md) que decodifica cada código numérico (p. ej. `educacion_max_padres_codigo` 1–10).

## Fuente original

- `Diccionario de datos ECV2025.xlsx` (DANE) — hoja *Plantilla Diccionario de Datos*.
- Capítulo D (`DBF_ENCV_592_1`), Capítulo G (`DBF_ENCV_592_4`), Capítulo I (`DBF_ENCV_592_6`).
- Formularios PDF originales adjuntos en cada subdirectorio de `data/`.
