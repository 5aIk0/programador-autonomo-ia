# Proyecto: Programador 100% Autómata con IA

## Estado inicial

- Usuario: Benjamín
- Plataforma base: Cursor AI Pro (entorno de desarrollo)
- IA principal: DevStral (descartado por recursos), se usará Phi-3 (liviano y compatible con Ollama)
- Sistema operativo: Windows (sin Docker pesado)
- Interfaz de uso: Cursor + Dashboard Visual
- Preferencia: ejecución 100% autónoma sin requerir confirmaciones
- Logs: avanzados, persistentes y visualizables

## Memoria persistente activada (Opción A)

Este documento será el núcleo de referencia de todo el proyecto. Aquí se documentarán:

- Tareas completadas
- Decisiones tomadas
- Diseño de arquitectura
- Módulos del sistema
- Comandos y configuraciones importantes

Será actualizado por ChatGPT en cada paso.

## Restricciones

- No se usará DevStral por limitaciones de hardware
- No se usará Docker pesado

## Modelos seleccionados

- Phi-3 Mini (4B) como modelo IA principal
  - Bajo consumo, alta velocidad
  - Comando: `ollama run phi3`

## Objetivo general

Desarrollar un sistema que pueda:

- Generar, modificar, mantener y probar código
- Ejecutar tareas sin intervención humana
- Aprender y adaptarse a estilos de programación
- Interactuar con el entorno (archivos, terminal, proyectos)
- Mostrar todo en un dashboard visual

## Próximo paso

Diseñar la arquitectura general del sistema con módulos independientes, orquestador, modelo IA, logs y dashboard.

Este documento se mantendrá siempre al día.
