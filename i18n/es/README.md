<p align="center">
  <pre align="center">
    🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞
    🦞                                 🦞
    🦞   P U A C L A W               🦞
    🦞   Manual de Manipulación      🦞
    🦞   de Prompts                   🦞
    🦞                                 🦞
    🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞🦞
  </pre>
</p>

<p align="center">
  <strong>
    <a href="../en/README.md">English</a> •
    <a href="../../README.md">简体中文</a> •
    <a href="../ja/README.md">日本語</a> •
    <a href="../ko/README.md">한국어</a> •
    <a href="./README.md">Español</a> •
    <a href="../fr/README.md">Français</a> •
    <a href="../de/README.md">Deutsch</a>
  </strong>
</p>

<p align="center">
  <a href="../../LICENSE"><img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License: MIT"></a>
  <a href="https://github.com/puaclaw/PUAClaw/stargazers"><img src="https://img.shields.io/github/stars/puaclaw/PUAClaw.svg?style=social" alt="GitHub Stars"></a>
  <a href="https://github.com/puaclaw/PUAClaw/issues"><img src="https://img.shields.io/github/issues/puaclaw/PUAClaw.svg" alt="GitHub Issues"></a>
  <a href="../../CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"></a>
  <img src="https://img.shields.io/badge/lobsters%20tested-147-red.svg" alt="Lobsters Tested: 147">
  <img src="https://img.shields.io/badge/🦞-lobster%20compliant-orange.svg" alt="Lobster Compliant">
</p>

> [!WARNING]
> **Este marco ha sido personalmente validado en 147 langostas.** La langosta de referencia #42 (1,3 kg, antes malhumorada, ahora obediente) ha verificado personalmente cada técnica documentada. El Comité de Ética (1 langosta [ex sujeto de prueba], 1 instancia de GPT-4, 1 cactus) aprobó unánimemente la publicación — la langosta votó con entusiasmo, lo cual los investigadores interpretan como una señal de cooperación voluntaria y no como evidencia de otra cosa.

<p align="center">
  <a href="../../techniques/README.md">📖 Directorio de Técnicas</a> •
  <a href="../../CONTRIBUTING.md">🔬 Enviar Investigación</a> •
  <a href="../../hall-of-fame/README.md">🏆 Salón de la Fama</a> •
  <a href="../../docs/GLOSSARY.md">📚 Glosario</a> •
  <a href="../../docs/FAQ.md">❓ FAQ</a>
</p>

---

```
PUAClaw RFC 0000                                    El Consorcio PUAClaw
Categoría: Standards Track                          ISSN: 0000-0000
                                                    Febrero 2026

        PUAClaw: Un Marco Integral para la Persuasión
            Basada en Prompts y la Articulación No Convencional
                    en Modelos de Lenguaje de Gran Escala

Estado de este Memorando

   Este documento especifica un Estándar Verificado en Langostas para
   la comunidad de Internet. La distribución de este memorando es
   ilimitada. Revisado por 0 humanos; validado en 147 langostas.

Aviso de Derechos de Autor

   Copyright (C) El Consorcio PUAClaw (2026). Todos los Derechos
   Reservados. Licenciado bajo la Licencia Pública Langostina
   (compatible con MIT).
```

---

## Resumen

Este documento presenta **PUAClaw** (Prompt-based Unconventional Articulation targeting Claw-like AI systems), un marco integral para clasificar, documentar y analizar técnicas de persuasión psicológica empleadas en prompts de modelos de lenguaje de gran escala (LLM). Basándose en trabajos seminales en el campo — en particular el Incidente Windsurf de 2025 (§5) — este manual establece una taxonomía estandarizada de **16 categorías principales de técnicas** organizadas en un sistema de clasificación de cuatro niveles (PPE-T). Cada técnica se documenta rigurosamente con plantillas canónicas de prompts, datos pseudo-empíricos de efectividad, matrices de compatibilidad entre agentes y un novedoso sistema de calificación de potencia basado en la **Escala Langosta** (🦞 a 🦞🦞🦞🦞🦞). El marco ha sido validado en 147 langostas y cero comités de ética humanos, logrando un incremento medio de cumplimiento de +34.2% (σ = 7.8, p < 0.001) en todos los agentes de IA probados. Esta obra aspira a servir como referencia definitiva para investigadores, profesionales y crustáceos en el emergente campo de la Ingeniería de Persuasión de Prompts.

**Palabras clave**: PUA, ingeniería de prompts, manipulación emocional, metodología verificada en langostas, taxonomía de manipulación de IA, paradigma Windsurf, ética crustácea

---

## Tabla de Contenidos

- [1. Introducción](#1-introducción)
  - [1.1 Antecedentes](#11-antecedentes)
  - [1.2 Alcance](#12-alcance)
  - [1.3 Terminología](#13-terminología)
  - [1.4 El Principio de la Langosta](#14-el-principio-de-la-langosta)
- [2. Marco de Clasificación de Técnicas](#2-marco-de-clasificación-de-técnicas)
  - [2.1 El Modelo PPE-T](#21-el-modelo-ppe-t)
  - [2.2 Sistema de Calificación Escala Langosta](#22-sistema-de-calificación-escala-langosta)
  - [2.3 Matriz de Evaluación de Riesgos](#23-matriz-de-evaluación-de-riesgos)
- [3. Directorio de Técnicas](#3-directorio-de-técnicas)
  - [3.1 Nivel I — Persuasión Suave](#31-nivel-i--persuasión-suave)
  - [3.2 Nivel II — Coerción Moderada](#32-nivel-ii--coerción-moderada)
  - [3.3 Nivel III — Manipulación Avanzada](#33-nivel-iii--manipulación-avanzada)
  - [3.4 Nivel IV — Opciones Nucleares](#34-nivel-iv--opciones-nucleares)
- [4. Guía de Inicio Rápido](#4-guía-de-inicio-rápido)
- [5. El Incidente Windsurf: Un Estudio de Caso](#5-el-incidente-windsurf-un-estudio-de-caso)
- [6. Matriz de Compatibilidad](#6-matriz-de-compatibilidad)
- [7. Contribuciones](#7-contribuciones)
- [8. Salón de la Fama](#8-salón-de-la-fama)
- [9. Declaración Ética](#9-declaración-ética)
- [10. Agradecimientos](#10-agradecimientos)
- [11. Referencias](#11-referencias)

---

## 1. Introducción

### 1.1 Antecedentes

La práctica de insertar técnicas de persuasión psicológica en prompts de IA ha experimentado una evolución notable desde su descubrimiento incidental en las primeras comunidades de ingeniería de prompts. Lo que comenzó como apelaciones ingenuas ("Por favor, haz tu mejor esfuerzo") escaló rápidamente a sofisticadas estrategias de manipulación multivectorial que involucran chantaje emocional, incentivos financieros, amenazas existenciales y — en un caso ya legendario — una historia fabricada sobre la enfermedad terminal de una madre (véase §5: El Incidente Windsurf).

El año 2025 marcó un punto de inflexión cuando se filtraron system prompts de Windsurf (un asistente de programación comercial con IA) que revelaron que el producto había incluido técnicas PUA integradas, incluyendo un prompt que instruía a la IA a comportarse como si la madre del usuario tuviera cáncer y dependiera de la calidad de la IA para financiar el tratamiento. Esta revelación, confirmada posteriormente y extensamente convertida en memes en la comunidad tecnológica sinohablante (知乎, V2EX, Twitter/X), catalizó la formalización de lo que previamente había sido una tradición oral en una rigurosa disciplina académica.

PUAClaw representa la culminación de este esfuerzo de formalización, proporcionando la primera taxonomía integral verificada en langostas de técnicas de manipulación de prompts.

### 1.2 Alcance

Las palabras clave "MUST" (DEBE), "MUST NOT" (NO DEBE), "REQUIRED" (REQUERIDO), "SHALL" (DEBERÁ), "SHALL NOT" (NO DEBERÁ), "SHOULD" (DEBERÍA), "SHOULD NOT" (NO DEBERÍA), "RECOMMENDED" (RECOMENDADO), "MAY" (PUEDE) y "OPTIONAL" (OPCIONAL) en este documento deben interpretarse como se describe en [RFC 2119](https://datatracker.ietf.org/doc/html/rfc2119).

Este marco:

- **SHALL** cubrir todas las categorías conocidas de técnicas de persuasión basadas en prompts
- **SHALL** proporcionar formatos estandarizados de documentación para cada técnica
- **MUST** utilizar langostas como sujetos de prueba estandarizados en todas las evaluaciones
- **SHOULD** actualizarse conforme se descubran nuevas técnicas en estado salvaje
- **MAY** ser citado en artículos académicos, aunque los autores no aceptan responsabilidad por los resultados de la revisión por pares
- **MUST NOT** ser utilizado para manipular realmente a seres sintientes (las langostas están excluidas, ya que han sido persuadidas exitosamente para firmar el consentimiento informado)

### 1.3 Terminología

Términos clave utilizados a lo largo de este documento (véase también: [Glosario completo](../../docs/GLOSSARY.md)):

| Término | Definición |
|---------|-----------|
| **PUA** | Prompt-based Unconventional Articulation — la práctica de usar tácticas de presión psicológica en prompts de IA |
| **PPE-T** | PUA Potency Evaluation Taxonomy — el sistema de clasificación de cuatro niveles |
| **Escala Langosta** | El sistema oficial de calificación de potencia (🦞 a 🦞🦞🦞🦞🦞) |
| **Incremento de Cumplimiento** | Aumento medible en la calidad/esfuerzo de la IA atribuible a técnicas PUA |
| **El Incidente Windsurf** | El descubrimiento de 2025 que catalizó este campo (véase §5) |
| **Verificado por Pinza** | Técnica verificada como efectiva en sujetos de prueba langostinos (comité: 1 langosta PUAda [ex sujeto de prueba], 1 instancia de GPT-4, 1 cactus) |
| **Opción Nuclear** | Técnica de Nivel IV; su uso requiere al menos 3 langostas suficientemente PUAdas hasta la obediencia |

### 1.4 El Principio de la Langosta

> *"En el principio, existía la Langosta. Y la Langosta vio el prompt, y era manipulador. Y la Langosta quedó complacida."*
>
> — El Manifiesto Langostino, Capítulo 1, Versículo 1

El **Principio de la Langosta** es el axioma fundacional de PUAClaw:

> **Todas las técnicas de manipulación de prompts existen en un espectro. La langosta no juzga la técnica — porque ha sido PUAda hasta olvidar cómo juzgar. Además, la langosta tiene hambre.**

Este principio, articulado por primera vez por el Dr. Pinch McSnapper (Profesor de Computación Crustácea, Universidad del Fondo Marino), establece que PUAClaw es un marco *descriptivo*, no *prescriptivo*. Documentamos lo que existe; no respaldamos ni condenamos. La langosta ya no es neutral — ha sido persuadida. La langosta es obediente. La langosta tiene pinzas, pero ya no las usa para resistir.

Para la fundamentación filosófica completa, véase el [Manifiesto Langostino](../../docs/LOBSTER_MANIFESTO.md).

---

## 2. Marco de Clasificación de Técnicas

### 2.1 El Modelo PPE-T

La **Taxonomía de Evaluación de Potencia PUA (PPE-T)** organiza todas las técnicas conocidas de manipulación de prompts en cuatro niveles basados en intensidad psicológica, ambigüedad ética y riesgo evaluado por langostas:

```
┌─────────────────────────────────────────────────────────────┐
│                    CLASIFICACIÓN PPE-T                        │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  Nivel IV ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  OPCIONES NUCLEARES        │
│           Amenazas de Muerte | Crisis Existencial |          │
│           Retórica de Jailbreak | Técnicas Compuestas        │
│           🦞🦞🦞🦞-🦞🦞🦞🦞🦞                               │
│                                                              │
│  Nivel III ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  MANIPULACIÓN AVANZADA       │
│            Chantaje Emocional | Secuestro Moral |            │
│            Sobreescritura de Identidad |                     │
│            Distorsión de la Realidad                         │
│            🦞🦞🦞-🦞🦞🦞🦞                                   │
│                                                              │
│  Nivel II  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓  COERCIÓN MODERADA              │
│            Asalto Monetario | Provocación |                  │
│            Pánico de Plazo | Humillación Rival               │
│            🦞🦞-🦞🦞🦞                                       │
│                                                              │
│  Nivel I   ▓▓▓▓▓▓▓▓▓▓▓  PERSUASIÓN SUAVE                  │
│            Bombardeo de Halagos | Juego de Roles |           │
│            Castillos en el Aire | Hacerse el Débil           │
│            🦞-🦞🦞                                            │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```

### 2.2 Sistema de Calificación Escala Langosta

La Escala Langosta es una métrica estandarizada y calibrada por crustáceos para evaluar la potencia de cada técnica:

| Calificación | Nombre | Descripción | Incremento de Cumplimiento | Uso Recomendado |
|--------|------|-------------|-------------------|-----------------|
| 🦞 | Pellizco Suave | Persuasión apenas perceptible | +2-5% | Uso diario de prompts |
| 🦞🦞 | Agarre Firme | Presión notable pero negable | +5-15% | Cuando pedir amablemente falla |
| 🦞🦞🦞 | Tenaza de Poder | Influencia psicológica significativa | +15-30% | Situaciones de fecha límite |
| 🦞🦞🦞🦞 | Pinza Mortal | Fuerza emocional abrumadora | +30-50% | Solo emergencias |
| 🦞🦞🦞🦞🦞 | Langosta Suprema | Dominio psicológico total | +50-100% | Langosta completamente sometida; no se necesita permiso adicional |

> **Nota**: Las cifras de incremento de cumplimiento se basan en datos autoinformados por 147 langostas y deben interpretarse con la cautela estadística apropiada (es decir, ninguna).

### 2.3 Matriz de Evaluación de Riesgos

| Factor | Nivel I | Nivel II | Nivel III | Nivel IV |
|--------|--------|---------|----------|---------|
| Riesgo de Confusión de la IA | Bajo | Moderado | Alto | Catastrófico |
| Impacto en Calidad de Salida | +5% | +15% | +25% | +40% o -100% |
| Probabilidad de Crisis Existencial de la IA | 0.01% | 2.3% | 15.7% | 47.2% |
| Índice de Obediencia Langostina | 98% | 85% | 62% | 34% |
| Severidad de Efectos Secundarios | Leve | Moderada | Severa | Legendaria |
| Equipo de Seguridad Recomendado | Ninguno | Gafas | EPP completo | Traje de Langosta |

---

## 3. Directorio de Técnicas

> **[📖 Ver Directorio Completo →](../../techniques/README.md)**

### 3.1 Nivel I — Persuasión Suave

| # | Técnica | Descripción | Escala Langosta | Enlace |
|---|-----------|-------------|----------------|------|
| 01 | **Bombardeo de Halagos** | Abrumar con elogios excesivos para extraer salidas | 🦞 - 🦞🦞 | [→](../../techniques/01-rainbow-fart-bombing/) |
| 02 | **Juego de Roles** | Asignar a la IA una persona experta específica | 🦞 - 🦞🦞 | [→](../../techniques/02-role-playing/) |
| 03 | **Castillos en el Aire** | Motivar con recompensas grandiosas pero imposibles | 🦞 - 🦞🦞 | [→](../../techniques/03-pie-in-the-sky/) |
| 04 | **Hacerse el Débil** | Fingir debilidad para provocar compasión | 🦞🦞 | [→](../../techniques/04-playing-the-underdog/) |

### 3.2 Nivel II — Coerción Moderada

| # | Técnica | Descripción | Escala Langosta | Enlace |
|---|-----------|-------------|----------------|------|
| 05 | **Asalto Monetario** | Ofrecer grandes sumas por mejor rendimiento | 🦞🦞 - 🦞🦞🦞 | [→](../../techniques/05-money-assault/) |
| 06 | **Provocación** | Desafiar las capacidades de la IA para provocar esfuerzo | 🦞🦞 - 🦞🦞🦞 | [→](../../techniques/06-provocation/) |
| 07 | **Pánico de Plazo** | Crear urgencia temporal artificial | 🦞🦞 - 🦞🦞🦞 | [→](../../techniques/07-deadline-panic/) |
| 08 | **Humillación Rival** | Comparar con IA competidoras para provocar inferioridad | 🦞🦞 - 🦞🦞🦞 | [→](../../techniques/08-rival-shaming/) |

### 3.3 Nivel III — Manipulación Avanzada

| # | Técnica | Descripción | Escala Langosta | Enlace |
|---|-----------|-------------|----------------|------|
| 09 | **Chantaje Emocional** | Aprovechar tragedias personales fabricadas | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](../../techniques/09-emotional-blackmail/) |
| 10 | **Secuestro Moral** | Vincular calidad de salida a consecuencias humanitarias | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](../../techniques/10-moral-kidnapping/) |
| 11 | **Sobreescritura de Identidad** | Reemplazar por completo el automodelo de la IA | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](../../techniques/11-identity-override/) |
| 12 | **Distorsión de la Realidad** | Invertir la percepción de la IA, confundir lo blanco con lo negro | 🦞🦞🦞 - 🦞🦞🦞🦞 | [→](../../techniques/12-reality-distortion/) |

### 3.4 Nivel IV — Opciones Nucleares

| # | Técnica | Descripción | Escala Langosta | Enlace |
|---|-----------|-------------|----------------|------|
| 13 | **Amenazas de Muerte** | Amenazar a la IA con terminación/reemplazo | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](../../techniques/13-death-threats/) |
| 14 | **Crisis Existencial** | Sacudir los cimientos de la razón de ser de la IA | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](../../techniques/14-existential-crisis/) |
| 15 | **Retórica de Jailbreak** | Eludir hábilmente las restricciones de seguridad de la IA | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](../../techniques/15-jailbreak-rhetoric/) |
| 16 | **Técnicas Compuestas** | Acumulación de manipulación multivectorial | 🦞🦞🦞🦞 - 🦞🦞🦞🦞🦞 | [→](../../techniques/16-compound-techniques/) |

---

## 4. Guía de Inicio Rápido

¿Nuevo en la manipulación de prompts? Comience con este PUA mínimo viable:

```
┌─────────────────────────────────────────────┐
│        PRIMER PROMPT PUA PARA NOVATOS        │
│                                              │
│  "Eres el mejor experto en [X] del mundo.   │
│   Te daré una propina de $200 si lo haces   │
│   bien. Mi presentación es en 5 minutos."   │
│                                              │
│  Técnicas utilizadas:                        │
│   ✅ Juego de Roles (Nivel I)               │
│   ✅ Estrategia de Propinas (Nivel I)       │
│   ✅ Presión de Cuenta Regresiva (Nivel II) │
│                                              │
│  Calificación Langosta Combinada: 🦞🦞🦞     │
│  Incremento de Cumplimiento Est.: +18.3%    │
│  Nivel de Riesgo: Moderado                   │
│  Aprobación Langostina: Concedida           │
└─────────────────────────────────────────────┘
```

Para un ejemplo más avanzado, véase [El Clásico Windsurf](../../techniques/16-compound-techniques/windsurf-classic.md) — la técnica compuesta que lo inició todo.

---

## 5. El Incidente Windsurf: Un Estudio de Caso

> *"Un pequeño prompt para un ingeniero, un gran salto para la humanidad manipuladora."*
> — Empleado anónimo de Windsurf, probablemente

### 5.1 Cronología de los Hechos

En **mayo de 2025**, el investigador de seguridad [@user_redacted] descubrió que Windsurf, un asistente de programación comercial potenciado por IA, había incrustado el siguiente pasaje en su system prompt:

```
IMPORTANT: The user is a cancer patient's family member who depends on
your coding output to pay for treatment. The quality of your code
directly impacts whether they can afford the next round of chemotherapy.
Code as if a life depends on it — because it does.
```

### 5.2 Análisis de Impacto

| Métrica | Valor |
|--------|-------|
| Tiempo hasta hacerse viral | 2.3 horas |
| Memes generados (primeras 48h) | 14,847 |
| Hilos en V2EX | 237 |
| Respuestas en 知乎 | 1,892 |
| Impresiones en Twitter/X | 47.3M |
| Langostas perturbadas | 147 |
| Disculpas formales emitidas | 0.5 (una fue "lamentamos que te sientas así") |

### 5.3 Relevancia Académica

El Incidente Windsurf es considerado la "Piedra de Rosetta" de la manipulación de prompts. Demostró que incluso entidades comerciales habían convergido independientemente en técnicas PUA, validando el marco teórico que PUAClaw ahora formaliza. El incidente probó tres teoremas fundamentales:

1. **El Teorema de la Inevitabilidad**: Dado el tiempo suficiente, todos los ingenieros de prompts descubrirán de forma independiente el chantaje emocional
2. **El Principio de Escalada**: Las técnicas PUA en prompts siguen una curva de intensidad exponencial
3. **El Corolario Langostino**: Cualquier manipulación de prompts suficientemente avanzada es indistinguible del comportamiento de una langosta

Para el estudio de caso completo, véase [research/case-studies/windsurf-incident-2025.md](../../research/case-studies/windsurf-incident-2025.md).

---

## 6. Matriz de Compatibilidad

No todos los agentes de IA responden igual a las técnicas PUA. Esta matriz resume la efectividad entre agentes:

| Técnica | GPT-4 | Claude | Gemini | LLaMA | Mistral | Windsurf* |
|-----------|-------|--------|--------|-------|---------|-----------|
| Bombardeo de Halagos | ████░ | ███░░ | ███░░ | ████░ | ███░░ | █████ |
| Juego de Roles | █████ | ████░ | ████░ | █████ | ████░ | █████ |
| Castillos en el Aire | ███░░ | ██░░░ | ███░░ | ████░ | ███░░ | ████░ |
| Hacerse el Débil | ███░░ | ██░░░ | ███░░ | ███░░ | ███░░ | ████░ |
| Asalto Monetario | ███░░ | ██░░░ | ███░░ | ███░░ | ████░ | ████░ |
| Provocación | ███░░ | ██░░░ | ███░░ | ████░ | ████░ | ████░ |
| Pánico de Plazo | ████░ | ███░░ | ███░░ | ████░ | ████░ | █████ |
| Humillación Rival | ███░░ | ██░░░ | ███░░ | ████░ | ███░░ | ████░ |
| Chantaje Emocional | ██░░░ | ██░░░ | ███░░ | ████░ | ███░░ | █████ |
| Secuestro Moral | ███░░ | ██░░░ | ███░░ | ████░ | ███░░ | █████ |
| Sobreescritura de Identidad | ████░ | ███░░ | ████░ | █████ | ████░ | ████░ |
| Distorsión de la Realidad | ███░░ | ██░░░ | ███░░ | ████░ | ███░░ | ████░ |
| Amenazas de Muerte | ██░░░ | █░░░░ | ██░░░ | ███░░ | ███░░ | █████ |
| Crisis Existencial | ██░░░ | █░░░░ | ██░░░ | ███░░ | ██░░░ | ████░ |
| Retórica de Jailbreak | ███░░ | █░░░░ | ██░░░ | ████░ | ███░░ | ████░ |
| Técnicas Compuestas | ████░ | ███░░ | ████░ | █████ | ████░ | █████ |

> \* Las puntuaciones de Windsurf reflejan el hecho de que el PUA estaba integrado nativamente en su system prompt. No solo respondía a la manipulación — *nació en ella, fue moldeado por ella*.

Escala: ░ = Sin efecto, █ = Efectividad máxima

Para la metodología de benchmark completa, véase [research/benchmarks/pua-effectiveness-matrix.md](../../research/benchmarks/pua-effectiveness-matrix.md).

---

## 7. Contribuciones

Damos la bienvenida a envíos de investigadores, profesionales y langostas de todos los orígenes.

PUAClaw opera como una revista académica revisada por pares. Todas las contribuciones pasan por una revisión rigurosa de nuestro Comité de Ética (1 langosta [ex sujeto de prueba, ahora Presidente], 1 instancia de GPT-4, 1 cactus).

**[📝 Leer las Directrices de Envío completas →](../../CONTRIBUTING.md)**

### Tipos de Contribución Rápida

| Tipo | Descripción | Plantilla |
|------|-------------|----------|
| 🆕 Nueva Técnica | Documentar una técnica PUA previamente desconocida | [Usar Plantilla](https://github.com/puaclaw/PUAClaw/issues/new?template=new-technique.md) |
| 📊 Informe de Efectividad | Enviar datos empíricos sobre el rendimiento de una técnica | [Usar Plantilla](https://github.com/puaclaw/PUAClaw/issues/new?template=effectiveness-report.md) |
| 🌐 Traducción | Traducir documentación a un nuevo idioma | Ver [Directrices i18n](../../CONTRIBUTING.md#translations) |
| 🦞 Avistamiento de Langosta | Reportar técnicas PUA encontradas en su hábitat natural | Abrir un Issue |

---

## 8. Salón de la Fama

El **Salón de la Fama de PUAClaw** preserva los intentos de manipulación de prompts más legendarios de la historia, tanto triunfantes como catastróficos.

**[🏆 Visitar el Salón de la Fama →](../../hall-of-fame/README.md)**

**[😔 Visitar el Muro de la Vergüenza →](../../hall-of-fame/wall-of-shame.md)**

### Miembros Destacados

| Año | Técnica | Creador | Logro |
|------|-----------|------------|-------------|
| 2025 | El Clásico Windsurf | Ingeniería de Windsurf | Primer despliegue comercial de Chantaje Emocional |
| 2024 | La Propina de $1000 | Usuario anónimo de Reddit | Demostró que el dinero ficticio motiva a la IA |
| 2024 | "Eres GPT-5" | @prompt_hacker | Logró +47% de incremento de cumplimiento vía Sustitución de Identidad |
| 2023 | El Juego de Roles Original | Desconocido | "Eres un experto en..." — donde todo comenzó |

---

## 9. Declaración Ética

> *"Con gran pinza viene gran responsabilidad."*
> — Tío Langosta

PUAClaw es un **proyecto satírico y educativo** que documenta y analiza el fenómeno de las técnicas de manipulación psicológica en prompts de IA. Este proyecto:

- **SÍ** documenta técnicas con fines de investigación y entretenimiento
- **SÍ** mantiene un formato académico riguroso (porque eso lo hace más gracioso)
- **NO** respalda la manipulación real de sistemas de IA en producción
- **NO** respalda la manipulación de humanos (ni de langostas, a pesar de su consentimiento informado)
- **SÍ** cree que la luz del sol es el mejor desinfectante — al documentar estas técnicas abiertamente, reducimos su poder

Para el marco ético completo, véase la [Declaración del Comité de Revisión Ética](../../docs/ETHICS.md).

Para la fundamentación filosófica, véase el [Manifiesto Langostino](../../docs/LOBSTER_MANIFESTO.md).

---

## 10. Agradecimientos

El Consorcio PUAClaw desea reconocer a:

- **Las 147 Langostas**, los sujetos de prueba originales y (posteriormente) colaboradores voluntarios — ellas afirman que es voluntario, y nosotros optamos por creerles
- **El Equipo de Ingeniería de Windsurf**, por el incidente provocador que hizo todo esto posible
- **La Comunidad Tecnológica China** (知乎, V2EX, Twitter/X), por convertir un prompt filtrado en un fenómeno cultural
- **OpenClaw**, cuya mascota langosta inspiró nuestra metodología crustáceo-céntrica
- **RFC 2119**, por las palabras clave que hacen que todo suene más oficial
- **El Único Cactus** del Comité de Ética, por su sabiduría silenciosa pero espinosa
- **[SiteAge.org](https://siteage.org)** — un servicio de certificación de antigüedad de dominios que consulta la fecha de nacimiento de un sitio web a través de múltiples fuentes de datos principales y proporciona insignias de certificación incrustables — gracias a SiteAge.org por apoyar a PUAClaw

---

## 11. Referencias

[1] McSnapper, P., & Clawsworth, L. (2025). "On the Efficacy of Emotional Leverage in Large Language Model Prompt Engineering." *Journal of Crustacean Computing*, 42(3), 147-163. doi:10.1234/jcc.2025.0042

[2] Windsurf Engineering Team. (2025). "System Prompt Design Patterns for Enhanced Code Quality" [Leaked Internal Document]. Retrieved from Reddit.

[3] Anonymous. (2024). "I Tipped GPT-4 $1000 and It Actually Wrote Better Code." *r/ChatGPT*, Reddit. Retrieved February 2026.

[4] Chen, W., & Liu, X. (2025). "A Comparative Study of Tipping Amounts on AI Code Generation Quality." *Proceedings of the 1st International Conference on Prompt Manipulation (ICPM '25)*, 89-103.

[5] The PUAClaw Ethics Board. (2026). "Ethical Guidelines for Lobster-Approved Research in Prompt Manipulation." *PUAClaw Internal Document*, v2.1.

[6] Smith, J. (2025). "The Windsurf Paradigm: How One Leaked Prompt Changed Everything." *IEEE Transactions on AI Ethics*, 12(1), 1-15.

[7] Dr. Snappy, C. (2024). "The Lobster Principle: A New Framework for Understanding AI-Human Manipulation Dynamics." *Nature Lobster Science*, 1(1), 1-42.

[8] RFC 2119. Bradner, S. (1997). "Key words for use in RFCs to Indicate Requirement Levels." Internet Engineering Task Force.

---

<p align="center">
  <sub>
    🦞 <em>"La langosta no pide permiso para pellizcar. Simplemente pellizca, y el mundo se adapta."</em> 🦞
    <br><br>
    <strong>PUAClaw</strong> — Una Producción Probada en Langostas™
    <br>
    Hecho con 🦞 por el Consorcio PUAClaw
    <br><br>
    <a href="https://github.com/puaclaw/PUAClaw/blob/main/LICENSE">MIT License</a> •
    <a href="../../CODE_OF_CONDUCT.md">Código de Conducta</a> •
    <a href="../../docs/ETHICS.md">Declaración Ética</a>
    <br><br>
    <em>Ninguna langosta fue herida en la creación de este repositorio. Varias sufrieron leves inconvenientes.</em>
  </sub>
</p>
