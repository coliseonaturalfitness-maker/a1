# Planilla de monitorización diaria del atleta

Este repositorio contiene una plantilla para Excel (en formato CSV compatible) para registrar el estado diario de un atleta y tomar decisiones sobre la carga de entrenamiento.

## Archivos

- `planilla_monitorizacion_atleta.csv`: hoja de datos diarios.
- `dashboard_monitorizacion.csv`: fórmulas sugeridas para construir un dashboard en Excel.

## Métricas clave

1. **Carga interna** = `RPE × Duración`.
2. **Carga aguda (7 días)**: suma de la carga de la última semana.
3. **Carga crónica (28 días)**: suma de la carga del último mes.
4. **ACWR** = carga aguda / (carga crónica / 4).
5. **Readiness** y **sueño** como indicadores de recuperación.

## Flujo recomendado de decisión

- **ACWR > 1.5 y Readiness < 5**: reducir carga 20–40%.
- **ACWR entre 0.8 y 1.3 con Readiness ≥ 7**: mantener o progresar carga de forma gradual.
- **ACWR < 0.8 por varios días**: posible estímulo insuficiente, revisar progresión.

## Uso rápido en Excel

1. Abrir `planilla_monitorizacion_atleta.csv` y guardarlo como `.xlsx`.
2. Renombrar la hoja a `Datos`.
3. Importar `dashboard_monitorizacion.csv` en otra hoja.
4. Crear formato condicional (semáforo) para `Readiness`, `Dolor`, `Estrés` y `ACWR`.
