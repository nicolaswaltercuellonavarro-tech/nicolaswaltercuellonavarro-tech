# Análisis forense de memoria y correlación de evidencias

**Tipo:** evaluación académica individual de Herramientas de Seguridad Informática, abril de 2026.

**Autor:** Nicolás Cuello Navarro.

## Objetivo

Investigar evidencias de un incidente de laboratorio a partir de un volcado de memoria, una captura de red y artefactos del registro de Windows proporcionados para la evaluación.

## Trabajo documentado

- Identificación del sistema operativo y revisión de procesos con Volatility 3.
- Análisis de conexiones de red y procesos con características sospechosas.
- Consulta de variables, artefactos de archivos y registro de Windows.
- Correlación con tráfico HTTP y FTP en Wireshark.
- Uso de herramientas de hashing y extracción de cadenas.
- Elaboración de un informe con hipótesis y evidencia de laboratorio.

## Herramientas

Parrot OS · Volatility 3 · Wireshark · regipy · GNU coreutils · strings.

## Alcance y limitaciones

Resumen del informe académico, sin reejecutar el análisis ni validar de forma independiente sus conclusiones. Algunas secciones del informe conservan campos por completar y deben revisarse antes de reutilizarlo como evidencia técnica. No se incluyen volcados de memoria, PCAP, credenciales, rutas personales, URLs de evidencia ni direcciones IP.

## Procedencia

Síntesis del documento `Informe EVA1 Nicolas Cuello sec61 (pdf).pdf`, recuperado del correo institucional del autor. La atribución de actividad maliciosa requiere correlación de artefactos y no puede basarse únicamente en el nombre de un proceso.
