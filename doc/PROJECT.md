# Digimon World — Proyecto de mod

> Documento vivo para centralizar el diseño, el alcance y la coordinación del mod de **Digimon World (PS1)**. Completar y revisar en equipo; marcar las decisiones tentativas como tales.

## Estado del documento

- **Versión:** 0.1 — esqueleto inicial
- **Estado:** Borrador
- **Responsable:** Por definir
- **Última revisión:** 2026-10-15
- **Enlaces relacionados:** [Índice de documentación](README.md)

## 1. Resumen del proyecto

- **Nombre provisional del mod:** Por definir
- **Juego base:** Digimon World (PlayStation, PS1)
- **Plataforma/ejecución objetivo:** Por definir (incluido el port de PC mencionado en el README; especificar alcance y compatibilidad)
- **Tipo de proyecto:** Mod de juego
- **Elevator pitch:** En 2–3 frases, ¿qué experiencia ofrece este mod?
- **Pilares de diseño:**
  1. Por definir
  2. Por definir
  3. Por definir

## 2. Visión y objetivos

### Visión
¿Qué queremos que el jugador sienta y recuerde al terminar?

### Objetivos
- [ ] Definir la fantasía y el público objetivo.
- [ ] Acordar el alcance de la primera versión.
- [ ] Documentar sistemas y contenido antes de implementarlos.
- [ ] Mantener el diseño viable con las herramientas disponibles.

### No objetivos
¿Qué ideas quedan expresamente fuera del alcance inicial?

## 3. Público y experiencia

- **Público objetivo:** Por definir
- **Conocimientos previos esperados del juego:** Por definir
- **Experiencia deseada:** Por definir
- **Duración/ritmo objetivo:** Por definir
- **Accesibilidad y calidad de vida:** Por definir

## 4. Alcance y entregas

| Entrega | Contenido | Criterio de salida | Estado |
|---|---|---|---|
| Prototipo | Por definir | Por definir | Pendiente |
| Versión inicial | Por definir | Por definir | Pendiente |
| Actualizaciones | Por definir | Por definir | Pendiente |

### Límites conocidos
- La herramienta final de modding/decompilación aún está en desarrollo.
- Registrar aquí otras limitaciones técnicas, legales o de recursos que el equipo confirme.

## 5. Principios de diseño

- **Respeto por el juego base:** ¿Qué identidad y elementos deben conservarse?
- **Cambios deliberados:** Cada cambio debe apoyar un objetivo de diseño identificable.
- **Consistencia:** Nuevas mecánicas y contenido deben encajar con las reglas del mundo.
- **Pruebas y trazabilidad:** Relacionar cada cambio importante con su especificación y validación.

## 6. Diseño del juego

Describir el juego tal como lo modifica el proyecto. Para cada sistema, anotar el comportamiento actual relevante, el cambio propuesto, el motivo y las dependencias.

### 6.1 Bucle principal
- Bucle actual relevante:
- Bucle propuesto:
- Cambios y motivos:

### 6.2 Progresión y crianza
- Estadísticas, entrenamiento, disciplina y estado:
- Evolución, condiciones y rutas:
- Ciclo de vida y consecuencias:

### 6.3 Combate
- Reglas y flujo:
- Técnicas, atributos y balance:
- Cambios propuestos:

### 6.4 Mundo y exploración
- Áreas, accesos y navegación:
- Desbloqueos y progresión:
- Cambios propuestos:

### 6.5 Ciudad, personajes y eventos
- Digimon/personajes:
- Reclutamiento y servicios:
- Eventos, misiones y diálogos:

### 6.6 Economía e inventario
- Monedas, objetos y tiendas:
- Recompensas y fuentes:
- Cambios propuestos:

## 7. Contenido

| Elemento | Idea/función | Requisitos | Estado | Responsable |
|---|---|---|---|---|
| Digimon | Por definir | Por definir | Pendiente | Por asignar |
| Área | Por definir | Por definir | Pendiente | Por asignar |
| Evento | Por definir | Por definir | Pendiente | Por asignar |
| Objeto/técnica | Por definir | Por definir | Pendiente | Por asignar |

## 8. Narrativa, lore y dirección audiovisual

La biblia de lore vive en [`03_content/lore/README.md`](03_content/lore/README.md). Desarrollar personajes, cronología e historia en sus subcarpetas y enlazar cada dato importante con sus fuentes.

- **Premisa y tono:** Por definir
- **Temas:** Por definir
- **Canon y continuidad:** Aclarar relación con el juego base y otras referencias.
- **Dirección visual:** Por definir, respetando las limitaciones del arte original.
- **Música y sonido:** Por definir
- **Localización e idiomas:** Por definir

## 9. Diseño técnico y restricciones

- **Herramientas de decompilación/modding:** Por identificar y versionar
- **Formato de trabajo y parche de distribución:** Por definir
- **Compatibilidad objetivo:** Por definir
- **Datos/recursos que pueden modificarse:** Por confirmar
- **Limitaciones y riesgos técnicos:** Registrar con impacto y alternativa.
- **Reproducibilidad:** Documentar versiones, pasos y configuración necesarios para construir/probar.

No incluir ni distribuir archivos del juego original sin autorización. Documentar por separado qué insumos debe aportar cada colaborador y cómo se compartirán cambios propios.

## 10. Producción y colaboración

- **Coordinación y canales:** Por definir
- **Responsables por área:** Por definir
- **Flujo de propuesta y revisión:** Propuesta → revisión de diseño → aceptación → implementación → validación → documentación.
- **Convenciones de nombres y formatos:** Por definir
- **Cómo reportar cambios:** Resumir el cambio, propósito, archivos afectados y estado.

### Roles
| Área | Responsable | Apoyo | Notas |
|---|---|---|---|
| Diseño/GDD | Por asignar | Por asignar | |
| Investigación | Por asignar | Por asignar | |
| Ingeniería/herramientas | Por asignar | Por asignar | |
| Arte/audio | Por asignar | Por asignar | |
| Pruebas | Por asignar | Por asignar | |

## 11. Pruebas y calidad

- **Entorno y versiones a probar:** Por definir
- **Casos de prueba por sistema:** Por definir
- **Progresión completa y partidas guardadas:** Por definir
- **Compatibilidad y regresiones:** Por definir
- **Criterios de aceptación para cambios:** Por definir

## 12. Riesgos, preguntas y dependencias

| Tipo | Descripción | Impacto | Próximo paso | Responsable |
|---|---|---|---|---|
| Dependencia | La herramienta final de modding está pendiente | Puede limitar la implementación | Mantener diseños independientes de detalles no confirmados | Por asignar |
| Pregunta | ¿Cuál es la plataforma de distribución/ejecución objetivo? | Afecta compatibilidad y alcance | Acordar objetivo | Por asignar |

## 13. Decisiones

Registrar decisiones duraderas en `decisions/` usando la plantilla `templates/decision_record.md`. Resumir aquí las más importantes y enlazar su registro.

| Fecha | Decisión | Motivo | Registro |
|---|---|---|---|
| Por definir | Por definir | Por definir | Por enlazar |

## 14. Glosario

| Término | Definición |
|---|---|
| Por definir | |

## 15. Historial de cambios

| Fecha | Cambio | Autor |
|---|---|---|
| 2026-10-15 | Creación del esqueleto inicial | Equipo |



