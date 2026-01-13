# MetsuDevHeader

Proyecto colaborativo para crear y mantener una cabecera de comentarios estándar en scripts Python, optimizada para desarrollo asistido por IA.

El objetivo principal es garantizar 

*coherencia entre iteraciones** y **control estricto** sobre cambios no autorizados por parte de herramientas de IA o colaboradores, evitando que se modifiquen, eliminen o reorganizen elementos del código sin permiso explícito del propietario.

## ¿Por qué este proyecto?

En entornos donde se usa IA para generar, mejorar o depurar código, es común que las herramientas:
- Reorganicen código "por limpieza"
- Eliminen optimizaciones o cachés "innecesarios"
- Cambien arquitectura sin entender el contexto
- Ignoren comentarios o exigencias previas

**MetsuDevHeader** proporciona un template de cabecera que incluye:
- Registro claro de versiones, novedades y características
- Exigencias permanentes y obligatorias para IAs y colaboradores
- Reglas explícitas que prohíben cambios no autorizados

## Objetivos

- Crear un template de cabecera genérico y adaptable a cualquier script Python
- Incluir secciones para:
  - Propósito, versión y fecha
  - Novedades por release
  - Características principales
  - Exigencias obligatorias para mantener integridad del código
- Fomentar contribuciones colaborativas para refinar el template
- Servir como "contrato" visible entre el desarrollador y cualquier IA/colaborador

## Instalación y Uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/metsuke/MetsuDevHeader.git
   cd MetsuDevHeader

Incluyelo en el prompt para la IA para que ejecute las acciones indicadas, una vez hecho por primera vez los comentarios de cabecera ya contendrán las instrucciones necesarias.

No requiere dependencias; es solo texto para cabeceras.

## Contribución

¡Cualquier mejora es bienvenida! Ideas aceptadas:

- Variantes para otros lenguajes (JS, Go, Rust, etc.)
- Secciones adicionales (dependencias, advertencias, licencia inline)
- Mejoras visuales en la estructura de la cabecera
- Ejemplos reales de aplicación en proyectos grandes

