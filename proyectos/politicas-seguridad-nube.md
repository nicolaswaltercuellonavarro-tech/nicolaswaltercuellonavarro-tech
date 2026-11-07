# Políticas de seguridad en la nube — Laboratorio académico

**Tipo:** evaluación práctica grupal.

**Integrantes del trabajo original:** Nicolás Cuello, Mauricio Aldea, Katherine Ramones y Rocío Flores.

**Fecha del envío:** enero de 2026.

## Objetivo

Documentar reglas de filtrado de dominios, categorías, puertos y descargas dentro de un laboratorio de seguridad en la nube.

## Escenarios documentados

| Categoría | Ejemplos del ejercicio |
| --- | --- |
| Dominio y DNS | Filtrado por sufijo `.xyz` y por dominio específico |
| Tráfico saliente | Bloqueo de SMTP en puerto 25 y RDP en puerto 3389 hacia Internet |
| Descargas | Restricción de archivos EXE, MSI, ZIP, RAR y 7z |
| Categorías web | Restricciones de cryptomining, acortadores/redirecciones, traducción y shareware |

## Resultado y alcance

El documento contiene diez escenarios con capturas de configuración y explicaciones breves. Este resumen describe el trabajo académico y no afirma que esas reglas sean apropiadas para todas las organizaciones ni que se hayan validado en producción.

El material textual recuperado no permite atribuir con certeza una plataforma concreta: por eso este caso no se presenta como una implementación de AWS ni como una arquitectura Zero Trust completa.

## Competencias aplicadas

Políticas de acceso · Filtrado web · Seguridad de red · Configuración de controles · Documentación técnica.

## Procedencia

Resumen editorial del informe `Evaluación 3 seguridad en la nube.pdf`, recuperado de un envío del autor. No se publican capturas de consolas, identificadores de cuenta ni el documento original.
