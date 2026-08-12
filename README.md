# Optimización de renderizado en aplicación React

Una aplicación financiera requiere mejorar su rendimiento y experiencia de usuario al cargar páginas. El equipo de desarrollo ha identificado que la técnica actual de renderizado no es óptima para ciertos tipos de contenido. Es necesario evaluar y aplicar diferentes técnicas de renderizado web para mejorar la carga inicial y la interactividad de la página.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Renderizado web |
| **Nivel** | senior-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 4-6 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Node.js 18+, npm, VS Code o similar.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Ejecuta `npm install && npm run build` (o `npm start`). Si no hay errores, estás listo.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Evaluación de técnicas de renderizado

**Objetivo:** Comprender las diferencias entre CSR, SSR y pre-render y su impacto en el rendimiento y la experiencia de usuario.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Investiga y compara las técnicas de renderizado CSR, SSR y pre-render.
- Identifica las ventajas y desventajas de cada técnica en diferentes contextos de negocio.

**Entregable:** Un informe comparativo de las técnicas de renderizado.

<details>
<summary>Pistas de conocimiento</summary>

- Considera el tipo de contenido y la audiencia al evaluar cada técnica.
- Piensa en cómo cada técnica afecta la carga inicial y la interactividad de la página.

</details>

### Fase 2: Implementación de SSR en una página crítica

**Objetivo:** Aplicar SSR en una página de la aplicación que requiera carga rápida y SEO.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Selecciona una página de la aplicación que se beneficie de SSR.
- Implementa SSR en esa página y mide el impacto en el rendimiento.

**Entregable:** Una página con SSR implementado y un informe de rendimiento.

<details>
<summary>Pistas de conocimiento</summary>

- Utiliza herramientas de medición de rendimiento para evaluar el impacto de SSR.
- Considera la estructura de la página y cómo afecta la implementación de SSR.

</details>

### Fase 3: Evaluación y ajuste de la implementación

**Objetivo:** Evaluar el rendimiento y la experiencia de usuario después de implementar SSR y realizar ajustes necesarios.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Evalúa el rendimiento y la experiencia de usuario de la página con SSR.
- Realiza ajustes necesarios para optimizar el rendimiento y la experiencia de usuario.

**Entregable:** Un informe de evaluación y los ajustes realizados.

<details>
<summary>Pistas de conocimiento</summary>

- Considera el feedback de los usuarios al evaluar el rendimiento y la experiencia de usuario.
- Piensa en posibles mejoras para optimizar aún más el rendimiento.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es SSR y cómo difiere de CSR y pre-render?
- **paraQueSirve**: ¿En qué escenarios es más beneficioso usar SSR?
- **comoSeUsa**: ¿Cómo implementaste SSR en la página seleccionada?
- **erroresComunes**: ¿Qué errores comunes enfrentaste al implementar SSR y cómo los resolviste?
- **queDecisionesImplica**: ¿Qué decisiones tomaste al evaluar y ajustar la implementación de SSR?

## Criterios de Evaluacion

- Comparación de técnicas de renderizado.
- Implementación de SSR en una página crítica.
- Evaluación y ajuste de la implementación de SSR.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
