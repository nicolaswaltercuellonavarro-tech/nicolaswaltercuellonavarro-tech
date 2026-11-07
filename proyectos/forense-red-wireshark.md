# Análisis forense de red con Wireshark y TShark

**Tipo:** evaluación académica individual de Herramientas de Seguridad Informática, mayo de 2026.

**Autor:** Nicolás Cuello Navarro.

## Objetivo

Analizar una captura de red de laboratorio de más de 26.000 paquetes y documentar hallazgos trazables a partir del tráfico.

## Trabajo documentado

- Revisión de jerarquía de protocolos, conversaciones y endpoints.
- Análisis de autenticaciones FTP y transferencias de archivos.
- Identificación de credenciales transmitidas sin protección y autenticación codificada en Base64.
- Extracción de objetos mediante TShark y correlación de eventos.
- Revisión de archivos y hashes con herramientas de laboratorio.
- Elaboración de una línea de tiempo y un informe técnico.

## Herramientas

Wireshark · TShark · Parrot OS · Python · John the Ripper · Hashcat.

## Alcance y limitaciones

Este caso resume el informe académico, sin repetir ni validar de forma independiente sus experimentos. No se publica el PCAP, capturas, direcciones IP, usuarios, contraseñas ni configuraciones recuperadas. La identificación de herramientas en consultas DNS, por sí sola, no demuestra actividad maliciosa: las hipótesis requieren correlación con otras evidencias.

## Procedencia

Resumen editorial de `Informe EVA2-HSI-Nicolas.C.N.pdf`, recuperado del correo institucional del autor. El documento original y la evidencia de laboratorio no se incluyen en el repositorio público.
