# Proyecto: Implementación de Plataforma de Comercio Electrónico
# Cliente: Mercaderías El Detal
# Fecha: Abril 2025

---

# 📋 PLAN OPERATIVO - Implementación Encuesta "Mercaderías El Detal"

## 1. Proceso Detallado de Aplicación

**Fase 1: Preparación**
- Crear versiones de la encuesta en Google Forms y Typeform.
- Imprimir 250 copias de la encuesta en formato papel.
- Generar códigos QR para acceso rápido a la versión digital.
- Capacitar brevemente a personal de tienda sobre invitación a participar.

**Fase 2: Difusión**
- Envío masivo de link por WhatsApp y correo electrónico a base de datos actual.
- Exhibición de pósters en tienda con el QR de la encuesta.
- Publicación en redes sociales oficiales.

**Fase 3: Aplicación**
- Aplicación activa durante 2 semanas.
- Recordatorios a clientes frecuentes y visitantes de tienda.

**Fase 4: Cierre**
- Cerrar formularios digitales tras cumplir el periodo o alcanzar 200 respuestas.
- Recolectar todos los formularios físicos.

**Fase 5: Exportación**
- Descargar resultados digitales en `.csv`.
- Crear resumen de resultados en `.md` (resumen estructurado por secciones).
- Digitalizar las respuestas en papel a formato `.csv`.

---

## 2. Recomendaciones para Aumentar la Tasa de Respuesta

- Incentivo: sorteo de un vale de compra de $50 entre quienes respondan.
- Recordatorio semanal durante el periodo de aplicación.
- Mensajes cortos, amigables y con llamado a la acción claro.
- Resaltar que es una encuesta breve (6-8 minutos) y anónima.
- Brindar asistencia en tienda para quienes necesiten ayuda para llenar la encuesta.

---

## 3. Esquema de Almacenamiento y Clasificación de Datos

**Estructura de Archivos:**
```plaintext
/encuesta_el_detal/
    ├── respuestas/
    │   ├── respuestas_digital.csv
    │   └── respuestas_papel.csv
    ├── informes/
    │   ├── resumen_datos.md
    │   └── resultados_graficos.pdf
    └── backups/
        ├── respuestas_digital_bk.csv
        └── respuestas_papel_bk.csv
```

**Clasificación:**
- Respuestas separadas por canal (digital / papel).
- Codificación uniforme de datos abiertos.
- Campos obligatorios validados.

---

## 4. Procedimiento para Auditar y Limpiar Datos

**Paso 1: Auditoría Inicial**
- Verificar número total de respuestas recibidas vs. respuestas esperadas.
- Detectar encuestas incompletas o inconsistentes.

**Paso 2: Criterios de limpieza**
- Eliminar respuestas que:
  - Se completaron en menos de 2 minutos.
  - Tienen respuestas idénticas en todas las preguntas.
  - Contienen información ilógica.

**Paso 3: Normalización**
- Homogeneizar formatos de entrada.

**Paso 4: Consolidación**
- Unir archivos `.csv` en uno final.
- Exportar backup actualizado.

**Paso 5: Documentación**
- Registrar cambios en un documento `.md`.

---

# ✅ CHECKLIST DE EJECUCIÓN

| Tarea | Responsable | Fecha límite | Estado |
|:---|:---|:---|:---|
| Crear formularios digitales | Equipo de Marketing | Día 1 | ⬜ |
| Imprimir encuestas físicas | Coordinador de tienda | Día 2 | ⬜ |
| Capacitar personal de tienda | RRHH | Día 3 | ⬜ |
| Difundir encuesta (email, WhatsApp) | Marketing Digital | Día 4 | ⬜ |
| Aplicar encuesta en tienda | Personal de tienda | Día 5-19 | ⬜ |
| Descargar respuestas digitales (.csv) | Analista de Datos | Día 20 | ⬜ |
| Digitalizar respuestas físicas (.csv) | Auxiliar de Datos | Día 21 | ⬜ |
| Crear resumen de resultados (.md) | Coordinador de Proyecto | Día 22 | ⬜ |
| Auditar y limpiar datos | Analista de Datos | Día 23 | ⬜ |
| Backup de archivos (.csv, .md) | TI | Día 24 | ⬜ |
