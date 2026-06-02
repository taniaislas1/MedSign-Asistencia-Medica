# MedSign-Asistencia-Medica

- [AsisMed: Asistencia Médica](#asismed-asistencia-médica)
  - [Descripción](#descripción)
  - [Funciones de la aplicación](#funciones-de-la-aplicación)


## Descripción
Su propósito es facilitar la comunicación preliminar entre pacientes con discapacidad auditiva y el personal médico. Por medio de la detección del alfabeto de señas en tiempo real, se determinan los síntomas que el paciente intenta comunicar a través de acrónimos clínicos.


## Funciones de la aplicación
El funcionamiento de la aplicación contiene 4 secciones principales:
1. **Detección de Señas en Tiempo Real:** Captura de video donde el sistema identifica letras individuales del alfabeto mediante el uso de cuadros delimitadores.
2. **Procesamiento de Acrónimos Médicos:** Una lógica de acumulación de caracteres que valida combinaciones de letras. El sistema solo reconoce y procesa combinaciones que existan en el diccionario médico predefinido (ej. "OL" para Dolor, "CB" para Cabeza).
3. **Diálogo e Historial Clínico:** Una interfaz que muestra el flujo de video y una sección de texto donde se registran exclusivamente los síntomas validados, filtrando detecciones erróneas para mantener un expediente limpio.
4. **Voz:** Síntesis de voz que anuncia auditivamente el síntoma detectado, permitiendo al médico recibir la información sin necesidad de observar permanentemente la pantalla.
