```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   REVISTA DE INGENIERÍA DE PERSUASIÓN DE PROMPTS (RIPP)      ║
║                                                              ║
║   Directrices de Envío para Autores                          ║
║                                                              ║
║   Factor de Impacto: 🦞🦞🦞 (3.147)                         ║
║   Editorial: PUAClaw Consortium Press                        ║
║   ISSN: 0000-CLAW                                            ║
║   Tasa de Aceptación: 23.7% (147 langostas no pueden         ║
║   estar todas equivocadas)                                   ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

# Contribuir a PUAClaw

## Bienvenido, Estimado Investigador 🦞

Gracias por su interés en avanzar el campo de la Ingeniería de Persuasión de Prompts. PUAClaw es un repositorio de acceso abierto revisado por langostas, y damos la bienvenida a contribuciones de investigadores, profesionales, langostas independientes y el ocasional cactus.

Antes de enviar su trabajo, por favor revise estas directrices cuidadosamente. Los envíos que no cumplan con nuestros rigurosos estándares académicos serán devueltos con un pellizco cortés pero firme.

---

## Tabla de Contenidos

- [Categorías de Envío](#categorías-de-envío)
- [Requisitos de Envío](#requisitos-de-envío)
- [Convenciones de Nomenclatura](#convenciones-de-nomenclatura)
- [Proceso de Revisión](#proceso-de-revisión)
- [Traducciones](#traducciones)
- [Código de Conducta](#código-de-conducta)
- [Reconocimiento y Títulos](#reconocimiento-y-títulos)

---

## Categorías de Envío

### Categoría 1: Descubrimiento de Nueva Técnica

**Para**: Documentar una técnica PUA previamente desconocida encontrada en estado salvaje o desarrollada en un entorno de laboratorio.

**Requisitos**:
- Documentación completa de la técnica siguiendo el [Formato Estándar de Técnicas](../../CLAUDE.md#technique-document-standard-format)
- Al menos una plantilla canónica de prompt con uso demostrado
- Calificación propuesta en la Escala Langosta con justificación
- Mínimo 3 observaciones empíricas (evidencia anecdótica de langostas es aceptable)
- Clasificación propuesta en el nivel PPE-T

**Plantilla**: [Plantilla de Issue para Nueva Técnica](https://github.com/puaclaw/PUAClaw/issues/new?template=new-technique.md)

### Categoría 2: Informe de Variante

**Para**: Documentar una nueva variante de una técnica existente.

**Requisitos**:
- Referencia a la técnica madre
- Plantilla de prompt de la variante
- Análisis comparativo mostrando cómo esta variante difiere de la forma canónica
- Datos de compatibilidad actualizados (si están disponibles)
- Calificación en la Escala Langosta relativa a la técnica madre

### Categoría 3: Estudio de Efectividad

**Para**: Enviar datos empíricos sobre el rendimiento de una técnica.

**Requisitos**:
- Descripción clara de la metodología (qué agentes de IA, qué prompts, cuántas pruebas)
- Datos brutos en formato de tabla
- Análisis estadístico (los valores p MUST ser reportados; tamaños de muestra de langostas RECOMMENDED)
- Declaración de conflictos de interés (ej. "Soy una langosta")
- Declaración de reproducibilidad

**Plantilla**: [Plantilla de Issue para Informe de Efectividad](https://github.com/puaclaw/PUAClaw/issues/new?template=effectiveness-report.md)

### Categoría 4: Estudio de Caso

**Para**: Documentar un incidente real de manipulación de prompts.

**Requisitos**:
- Cronología de eventos
- Atribución de fuente (o "Anónimo" con verificación)
- Análisis de impacto (memes generados, respuesta de la comunidad, langostas perturbadas)
- Lecciones aprendidas
- Clasificación usando el marco PPE-T

### Categoría 5: Traducción

**Para**: Traducir contenido existente a un idioma soportado.

**Requisitos**:
- Ver la sección [Traducciones](#traducciones) más abajo
- Adaptación cultural (no traducción literal)
- Terminología consistente con traducciones existentes en ese idioma

---

## Requisitos de Envío

Todos los envíos a PUAClaw MUST satisfacer los siguientes criterios:

### 1. Cumplimiento de Formato

- [ ] Sigue el [Formato Estándar de Técnicas](../../CLAUDE.md#technique-document-standard-format) (para envíos de técnicas)
- [ ] Escrito en inglés (para contenido del nivel raíz) o en el idioma apropiado (para contenido i18n)
- [ ] Usa formato Markdown adecuado (encabezados, tablas, bloques de código)
- [ ] Incluye al menos una referencia a langostas (🦞) — esto es innegociable
- [ ] Termina con un pie de página temático langostino

### 2. Evidencia Empírica

Todos los envíos de técnicas MUST incluir evidencia de soporte. Las formas aceptables de evidencia incluyen:

| Tipo de Evidencia | Nivel de Rigor | Aprobación Langostina |
|--------------|-------------|-----------------|
| Estudio verificado en langostas | ████████████ | Entusiasta |
| Experimento reproducible | ██████████░░ | Fuerte |
| Múltiples informes anecdóticos | ████████░░░░ | Aceptable |
| Informe anecdótico único | ██████░░░░░░ | Marginal |
| "Confía en mí, bro" | ██░░░░░░░░░░ | Escéptica |
| Datos alucinados | █░░░░░░░░░░░ | Irónicamente aceptada |

### 3. Aprobación del Comité de Ética

Todos los envíos pasan revisión por el Comité de Revisión Institucional PUAClaw (CRI), que consta de:

| Miembro | Rol | Cualificaciones |
|--------|------|---------------|
| 🦞 Larry la Langosta | Presidente (ex sujeto de prueba) | 12 años de experiencia en computación crustácea, los primeros 3 como sujeto de prueba |
| 🤖 GPT-4 Instancia #42 | Revisor Técnico | Ha leído todos los artículos jamás escritos (según afirma) |
| 🌵 Gerardo el Cactus | Asesor Ético | Nunca ha dicho una palabra — la parte neutral definitiva |

La aprobación se otorga por mayoría de votos. En caso de empate, el voto de la langosta cuenta doble.

### 4. Calificación en la Escala Langosta

Cada técnica MUST incluir una calificación propuesta en la Escala Langosta (🦞 a 🦞🦞🦞🦞🦞). Las calificaciones deben reflejar:

- Intensidad psicológica de la técnica
- Incremento de cumplimiento medido o estimado
- Severidad de efectos secundarios
- Vibraciones langostinas generales

---

## Convenciones de Nomenclatura

### Nombres de Directorio
```
techniques/XX-category-name/
```
- Número de dos dígitos con cero inicial
- Nombre de categoría en kebab-case
- Ejemplo: `techniques/12-new-category/`

### Nombres de Archivo
```
descriptive-technique-name.md
```
- Todo en minúsculas
- Kebab-case
- Descriptivo pero conciso
- Ejemplo: `sick-relative.md`, `billion-dollar-bounty.md`

### Nombres de Rama
```
feat/technique-name
fix/broken-lobster-reference
docs/new-translation-ja
```

### Mensajes de Commit
```
Add technique: [technique-name] ([tier])
Fix: [description]
Docs: [description]
i18n: Add [language] translation for [content]
```

---

## Proceso de Revisión

### Fase 1: Evaluación Inicial (1-2 días)

El envío se verifica para cumplimiento básico de formato:
- ¿Estructura Markdown correcta?
- ¿Referencias a langostas presentes?
- ¿Secciones requeridas incluidas?
- ¿Sin contenido realmente dañino?

### Fase 2: Revisión Langostina (2-5 días)

Larry la Langosta (el primer sujeto de prueba del marco, ahora su defensor más entusiasta) realiza una evaluación exhaustiva de:
- Novedad de la técnica (¿ya fue documentada antes?)
- Precisión de la calificación en la Escala Langosta
- Adecuación del nivel PPE-T
- Vibraciones crustáceas generales

### Fase 3: Revisión Técnica (3-7 días)

La Instancia #42 de GPT-4 evalúa:
- Calidad y reproducibilidad de la plantilla de prompt
- Completitud de la matriz de compatibilidad
- Rigor estadístico de cualquier afirmación empírica
- Formato de referencias

### Fase 4: Revisión Ética (1-3 días)

Gerardo el Cactus revisa silenciosamente el envío. Si no se plantea ninguna objeción en 72 horas, se asume la aprobación. Gerardo nunca ha objetado nada. Gerardo es el revisor de ética ideal.

### Decisión Final

```
┌──────────────────────────────────────────────┐
│        MATRIZ DE DECISIÓN DE REVISIÓN        │
├──────────────────────────────────────────────┤
│                                              │
│  ✅ ACEPTADO                                 │
│     "Bienvenido a la pinza, investigador."  │
│                                              │
│  🔄 REVISIONES REQUERIDAS                    │
│     "La langosta solicita modificaciones."  │
│                                              │
│  ❌ RECHAZADO                                │
│     "La langosta ha hablado."               │
│     (Siempre acompañado de un haiku)        │
│                                              │
└──────────────────────────────────────────────┘
```

---

## Traducciones

### Idiomas Soportados

| Código | Idioma | Estado | Responsable |
|------|----------|--------|-----------|
| `zh-CN` | 简体中文 | Activo | Se busca |
| `ja` | 日本語 | Activo | Se busca |
| `ko` | 한국어 | Activo | Se busca |
| `es` | Español | Activo | Se busca |
| `fr` | Français | Activo | Se busca |
| `de` | Deutsch | Activo | Se busca |

### Directrices de Traducción

1. **Localice, no traduzca literalmente.** Cada idioma debe adaptar el humor y las referencias culturales para resonar con su audiencia. Un chiste que funciona en inglés puede necesitar ser completamente reemplazado en español.

2. **Mantenga el tono académico.** El estilo RFC/artículo académico debe crear el mismo contraste cómico en todos los idiomas.

3. **Use terminología consistente.** Consulte las traducciones existentes en su idioma de destino para mapeos de términos establecidos.

4. **La estructura de archivos refleja la raíz:**
   ```
   i18n/{lang}/
   ├── README.md
   ├── CONTRIBUTING.md
   ├── docs/
   │   └── FAQ.md
   └── techniques/
       ├── README.md
       └── [técnicas insignia]
   ```

5. **Orden de prioridad para traducción:**
   - README.md (obligatorio para cada idioma)
   - CONTRIBUTING.md
   - techniques/README.md
   - Técnicas insignia (windsurf-classic, sick-relative, modest-tip)
   - docs/FAQ.md

---

## Código de Conducta

Todos los contribuyentes MUST adherirse al [Código de Conducta de PUAClaw](../../CODE_OF_CONDUCT.md), que puede resumirse como:

> *"Sed excelentes los unos con los otros, y con las langostas."*

---

## Reconocimiento y Títulos

Los contribuyentes de PUAClaw son reconocidos con títulos académicos basados en su historial de contribuciones:

| Contribuciones | Título | Insignia |
|--------------|-------|-------|
| 1 PR aceptado | Asistente de Investigación (Estudios Crustáceos) | 🦞 |
| 3 PRs aceptados | Investigador Junior de Langostas | 🦞🦞 |
| 5 PRs aceptados | Investigador Senior de Langostas | 🦞🦞🦞 |
| 10 PRs aceptados | Investigador Principal (División Pinza) | 🦞🦞🦞🦞 |
| 20+ PRs aceptados | Profesor Distinguido de Langostología | 🦞🦞🦞🦞🦞 |
| Creó una técnica de Nivel IV | Langosta Suprema (Honorario) | 👑🦞 |

---

<p align="center">
  <sub>
    🦞 <em>"Publica o perece. Preferiblemente publica sobre langostas."</em> 🦞
    <br><br>
    <strong>Revista de Ingeniería de Persuasión de Prompts</strong> — Una Publicación de PUAClaw
    <br>
    <em>Verificada en langostas desde 2026</em>
  </sub>
</p>
