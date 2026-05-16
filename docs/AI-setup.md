# Configuración de herramientas IA

## Claude como asistente principal

He optado por usar VSCode como editor junto a Claude como asistente de IA
en lugar de Cursor, manteniendo así el flujo de trabajo que mejor me funciona.

### Configuración aplicada
Al inicio de cada sesión de trabajo proporciono a Claude el contexto
completo del proyecto mediante un documento PDF que incluye:
- Stack tecnológico y versiones
- Estructura de carpetas
- Convenciones de código
- Restricciones de arquitectura
- Estado actual del desarrollo

### Por qué esta configuración
Proporcionar el contexto completo al inicio de cada sesión equivale
funcionalmente a un archivo .cursorrules — Claude conoce las decisiones
de diseño del proyecto y no genera código que las contradiga.