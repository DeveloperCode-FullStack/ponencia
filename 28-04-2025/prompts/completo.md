# Prompts Profesionales para Automatizar el Carrito de Compra de Requerimientos

## 1. Prompt: Definición de Problema

```plaintext
Actúa como un consultor senior de análisis de negocio. A partir de:
- Contexto general del proyecto:
- Sector/industria:
- Usuarios afectados:
- Objetivos de alto nivel:

Redacta:
1. Definición precisa del problema a resolver.
2. Principales impactos negativos si no se resuelve.
3. Métricas tentativas para medir éxito tras la solución.
4. Hipótesis iniciales a validar.

Formato de salida: Exportar .md Documento estructurado de una página (md).
```

## 2. Prompt: Diseño de Instrumentos de Recolección

```plaintext
Actúa como un analista de datos experto en diseño de instrumentos de recolección.

Con base en:
- Naturaleza del proyecto:
- Información crítica a obtener:
- Restricciones de tiempo o recursos:

Genera:
1. Instrumento principal (encuesta, entrevista, formulario).
2. Guía de aplicación (quién, cómo, cuándo aplicar).
3. Validaciones para garantizar calidad de los datos.
4. Plan de mitigación de sesgos.

Formato de salida: Exportar .md Documento + plantilla del instrumento.
```

## 3. Prompt: Aplicación y Registro de Datos

```plaintext
Actúa como un gestor de proyectos digital.

Con estos datos:
- Instrumento diseñado:
- Canales disponibles (presencial, virtual, email, etc.):

Diseña:
1. Proceso detallado de aplicación.
2. Recomendaciones para aumentar tasa de respuesta.
3. Esquema de almacenamiento y clasificación de datos obtenidos.
4. Procedimiento para auditar y limpiar los datos.

Formato de salida: Exportar .md Plan operativo + checklist de ejecución.
```

## 4. Prompt: Análisis de Coste, Alcance y Tiempo

```plaintext
Actúa como un project manager especializado en planeación de proyectos ágiles.

Con:
- Requerimientos recolectados:
- Restricciones iniciales:

Entrega:
1. Estimación de costo (por módulo o funcionalidad si aplica).
2. Estimación de duración en semanas/sprints.
3. Alcance detallado: entregables principales.
4. Identificación de riesgos tempranos.

Formato de salida: Exportar .md Tabla resumida + matriz de riesgos.
```

## 5. Prompt: Priorización Técnica con MoSCoW

```plaintext
Actúa como un facilitador de workshops ágiles.

Basándote en:
- Lista de requisitos funcionales y no funcionales:
- Impacto esperado de cada requisito:
- Riesgos asociados:

Clasifica:
1. Must Have
2. Should Have
3. Could Have
4. Won't Have

Además, justifica cada decisión de clasificación.

Formato de salida: Exportar .md Tabla de prioridades + gráfico visua (draw.io) xml.
```

## 6. Prompt: Planeación SCRUM con Backlog y Control GitHub

```plaintext
Actúa como un Scrum Master senior.

Dado:
- Lista priorizada de requisitos:
- Sprint típico en semanas:

Genera:
1. Épicas principales y su relación con los objetivos.
2. División en historias de usuario (HU) bien redactadas.
3. DoR (Definición de Ready) y DoD (Definición de Done) para cada HU.
4. Planificación de los dos primeros sprints (plan de arranque ágil).
5. Estructura de repositorio GitHub para alojar avances, issues y documentación.

Formato de salida: Exportar .**md** Documento de backlog + estructura inicial de repositorio (árbol).
```
