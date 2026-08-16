# Actividad Formativa: Modelamiento Inicial de Datos - BT&Airways

Este repositorio contiene la solución para el diseño del modelo entidad-relación de la aerolínea **BT&Airways**, desarrollado en **Oracle SQL Developer Data Modeler**.

## Integrantes
* **Javier Ignacio Rojas Pulgar**
* **María Victoria Ponce Blanco**

## Justificación Técnica de Diseño y Tipos de Datos

* **Identificador de Pasajero (`num_documento` / `VARCHAR(20)`):**  
  Dado el alcance internacional de la aerolínea (5 continentes), se seleccionó `VARCHAR` como identificador principal para admitir pasaportes alfanuméricos y documentos de identidad con prefijos o dígitos verificadores de diversos países.

* **Estructura de Nombres (`nombre_completo` / `VARCHAR(100)`):**  
  Se unificaron nombres y apellidos en un solo campo para alinearse con la pauta de la actividad y soportar la diversidad de estructuras de nombres internacionales.

* **Código de Vuelo (`numero_vuelo` / `VARCHAR(10)`):**  
  Se definió en formato alfanumérico para respetar los estándares de la industria aeronáutica (IATA/OACI), combinando código de aerolínea y número de ruta (ej. *LA801*).

## Contenido del Repositorio

* **Documento Word:** Incluye el análisis, justificación y capturas en **Notación Barker** y **Notación de Ingeniería de la Información / Bachman**.
* **Archivo Comprimido (.zip):** Contiene el archivo de diseño `.dmd` y su subcarpeta de metadatos generados por Oracle Data Modeler.
