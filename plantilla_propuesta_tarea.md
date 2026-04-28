# Práctica Temática: **Propuesta de Mini Proyecto Documentado**

## 1) Título de la práctica
**Diseño de una práctica temática pequeña en terminal**

> Ejemplos de enfoque (elige uno o propón otro similar):
> - **Mini Toolkit en ARM64**
> - **Asistente de Estudio en Terminal**
> - **Reporteador de Información del Sistema**
> - **Organizador de Archivos**
> - **Juego de Aprendizaje en Línea de Comandos**

---

## 2) Descripción general
En esta actividad **no vas a empezar programando “a lo loco”**. Primero vas a construir una **propuesta técnica breve y bien justificada** para un proyecto pequeño que se pueda desarrollar en pocas sesiones.

Tu objetivo es diseñar una idea viable para GitHub Classroom, con enfoque principal en:
- documentación técnica,
- planeación,
- estructura del repositorio,
- explicación clara del caso de uso.

### Lenguaje principal (elige uno)
- ARM64 Assembly
- C
- Python
- Bash

### Restricción importante de alcance
El proyecto debe ser **pequeño y realista**, considerando que puedes usar herramientas de IA con límite gratuito.

- Si eliges **ARM64 Assembly**, se recomienda únicamente para programas **muy pequeños** (por ejemplo: conversión simple, operación aritmética, lectura básica de argumentos, mini utilería).
- Evita proyectos grandes, frameworks complejos o infraestructura avanzada.

### Qué se evalúa primero
Se evalúa primero la **calidad de la propuesta y la documentación**. El código (si decides incluirlo) es secundario en esta etapa.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir **como mínimo** los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Opcionales:
- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio
Usa esta estructura mínima base:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> `<ext>` depende del lenguaje elegido: `s` (ASM), `c`, `py` o `sh`.

---

## 5) Contenido requerido por archivo

### `README.md`
Incluye:
1. Nombre del proyecto.
2. Descripción breve (3–6 líneas).
3. Lenguaje principal elegido y justificación corta.
4. Estado del proyecto: “Propuesta / En diseño”.
5. Índice con enlaces a los documentos en `docs/`.

---

### `docs/propuesta.md`
Estructura sugerida:
1. **Problema a resolver**
   - ¿Qué necesidad atiende?
   - ¿A quién le sirve?
2. **Objetivo general**
   - Una sola oración clara y medible.
3. **Objetivos específicos** (3 a 5)
4. **Alcance**
   - Qué sí incluye.
   - Qué no incluye.
5. **Lenguaje y herramientas mínimas**
   - Solo herramientas locales sencillas (compilador/intérprete/editor).
6. **Plan de implementación breve**
   - Fase 1: base funcional.
   - Fase 2: mejora pequeña opcional.

---

### `docs/caso_de_uso.md`
Incluye al menos:
1. **Usuario objetivo**
2. **Escenario de uso** (paso a paso)
3. **Entrada esperada**
4. **Salida esperada**
5. **Criterios de éxito**

Puedes agregar una tabla:

| Elemento | Descripción |
|---|---|
| Actor | Usuario de terminal |
| Precondición | Tener instalado el lenguaje elegido |
| Flujo principal | Ejecuta comando, ingresa datos, recibe resultado |
| Resultado | Solución útil y verificable |

---

### `docs/estructura_repositorio.md`
Incluye:
1. Árbol del repositorio actualizado.
2. Propósito de cada carpeta/archivo.
3. Convenciones de nombres (ej. `snake_case`, prefijos, etc.).
4. Estrategia mínima de versionado (commits pequeños y descriptivos).

---

### `docs/plan_de_pruebas.md`
Incluye:
1. Estrategia de pruebas manuales (mínimo 5 casos).
2. Casos normales, de borde y de error.
3. Formato sugerido:

| ID | Escenario | Entrada | Resultado esperado | Estado |
|---|---|---|---|---|
| P01 | Caso normal | ... | ... | Pendiente |
| P02 | Entrada vacía | ... | ... | Pendiente |

4. Criterios de aceptación mínimos.

---

## 6) Reglas técnicas de la práctica
- Proyecto **pequeño** (tiempo objetivo sugerido: 4 a 8 horas totales).
- Debe funcionar en terminal.
- Sin frameworks pesados.
- Sin APIs pagadas.
- Sin bases de datos.
- Sin nube.
- Sin contenedores.
- Sin dependencias complejas.

---

## 7) Ejemplos de alcance válido (mini)
- Script Bash que organiza archivos por extensión con reporte en texto.
- Programa en C que analiza conteo de palabras en archivos `.txt`.
- Script Python que genera un resumen de tareas desde un CSV local.
- Programa ARM64 Assembly (muy pequeño) que recibe dos números y muestra operaciones básicas.

---

## 8) Criterios de evaluación (rúbrica sugerida)
Total: **100 puntos**

1. **Claridad de la propuesta** (25 pts)
   - Problema, objetivo y alcance bien definidos.
2. **Calidad del caso de uso** (20 pts)
   - Flujo entendible, entradas/salidas correctas.
3. **Estructura de repositorio** (20 pts)
   - Organización limpia y coherente.
4. **Plan de pruebas** (20 pts)
   - Casos suficientes y medibles.
5. **Calidad de redacción técnica** (15 pts)
   - Precisión, ortografía, formato Markdown.

---

## 9) Instrucciones de entrega en GitHub Classroom
1. Acepta la asignación en GitHub Classroom.
2. Crea/edita los archivos requeridos en tu repositorio.
3. Realiza commits claros (ej. `docs: define caso de uso inicial`).
4. Verifica que todos los enlaces internos del `README.md` funcionen.
5. Entrega con tu rama principal actualizada.

---

## 10) Checklist rápido del estudiante
Marca con `x` al completar:

- [ ] Elegí lenguaje principal (ARM64 / C / Python / Bash).
- [ ] Definí un problema pequeño y realista.
- [ ] Redacté `docs/propuesta.md` con alcance claro.
- [ ] Documenté caso de uso completo.
- [ ] Definí estructura de repositorio y convenciones.
- [ ] Preparé plan de pruebas con mínimo 5 casos.
- [ ] Verifiqué ortografía, formato y enlaces.

---

## 11) Nota del instructor
La meta de esta práctica es que aprendas a **pensar como ingeniero/a**: delimitar, justificar, documentar y planear antes de implementar. Un proyecto pequeño, bien documentado y comprobable vale más que uno grande e incompleto.
