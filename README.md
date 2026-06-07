# Portafolio de Proyectos 
**Ingeniero Industrial | Analytics & Mejora Continua**

¡Hola! Como estas? Mi nombre es Nicolas Reyna  y soy Ingeniero Industrial con sólida trayectoria en el análisis de datos, visualización y optimización de procesos operativos. Mi enfoque principal es transformar KPIs en decisiones estratégicas que impulsen la eficiencia.

## Habilidades Técnicas
**Análisis y Visualización:** Power BI (Avanzado), Excel (Avanzado).
**Automatización:** Power Automate, N8N.
**Gestión:** SAP, WMS Cygnus, Microsoft Fabric.

## Proyectos Destacados

### 1) Optimización y Monitoreo de Performance de Picking

**Contexto del Problema:** La falta de visibilidad en tiempo real sobre la productividad operativa impedía identificar desvíos críticos entre la ejecución real y los tiempos estándar definidos. Esto dificultaba la toma de decisiones para balancear cargas de trabajo y optimizar los recursos en el depósito.

**Solución Técnica:**
Desarrollé un tablero de control en Power BI que centraliza la data operativa, permitiendo:

**Análisis Comparativo:** Cálculo automático de la Performance mediante la relación entre tiempos estándar (por tipo de recorrido: Pallet, Bolsita, Cubeta) vs. tiempos reales registrados por el WMS.

**Monitoreo por Turnos:** Visualización segmentada por Depósito y Turno para una rápida detección de cuellos de botella.

**Seguimiento Evolutivo:** Gráficos de tendencias temporales para evaluar la productividad individual y grupal a lo largo del tiempo.

![Performance Mensual de Picking](PBI%20-%20Performance%20Mensual%20de%20Picking.jpeg)
![Performance del Turno Mañana de Picking](PBI%20-%20Performance%20Turno%20Mañana.jpeg)
![Semaforo Operativo de Picking](PBI%20-%20Semaforo%20Operativo%20de%20PK.jpeg)
---
*Nota: Los datos expuestos han sido anonimizados por confidencialidad.*


### 2) Optimización de Slotting y Capacidad de Almacenamiento

**Contexto del Problema:**
La asignación ineficiente de mercadería en las posiciones de picking generaba cuellos de botella operativos y subutilización de la capacidad del depósito. No existía una visibilidad clara sobre la relación entre el volumen del artículo, la capacidad de la posición asignada y la demanda real.

**Solución Técnica:**
Desarrollé un tablero de control en **Power BI** para el monitoreo integral de *slotting*, integrando datos de inventario y demanda, permitiendo:

* **Clasificación por Estado:** Categorización automática de artículos en "OK", "A Revisar", "A Corregir" y "Sobredimensionado", facilitando la priorización de tareas.
![Control de Slotting](PBI%20-%20Control%20de%20Slotting.jpeg)
* **Análisis de Capacidad:** Evaluación del ajuste entre la capacidad de la unidad de picking (UPF en $cm^3$) y la demanda diaria, permitiendo identificar rápidamente desequilibrios antes de que impacten en la productividad.
* **Filtros de Gestión:** Implementación de segmentadores por política de abastecimiento y código de material para una gestión granular del depósito.

**Impacto Operativo:**
* **Proactividad:** Permite al supervisor detectar y corregir errores de ubicación antes de que afecten la producción.
* **Eficiencia del Espacio:** Optimización directa del uso del depósito al identificar posiciones sobredimensionadas o críticas.
* **Visibilidad:** Monitoreo en tiempo real de los niveles de servicio y cumplimiento del *slotting* planificado.

**Tecnologías:** Power BI, Modelado de Datos, DAX, Gestión de Inventarios, KPIs Logísticos.

## 3) Optimización de Olas de Reaprovisionamiento
**Objetivo:** Mitigar la carga laboral extra y los cuellos de botella operativos originados por configuraciones ineficientes en las ubicaciones de *picking*.

**Descripción Técnica:**
* **Análisis de Causa Raíz:** El tablero identifica artículos con configuraciones de reaprovisionamiento subóptimas, los cuales generaban múltiples reposiciones semanales innecesarias, impactando directamente en los tiempos de salida de pedidos.
* **Categorización de Prioridades:** Implementación de un sistema de semaforización (OK, A Revisar, A Corregir, Urgentes) que permite al equipo logístico priorizar la corrección de datos maestros sobre los artículos de mayor impacto negativo.
* **Impacto Operativo:** Reducción de la carga administrativa en el depósito mediante la visibilidad clara de desequilibrios entre la demanda real y la capacidad de las posiciones.

![Monitoreo de Olas de Reaprovisionamiento](PBI%20-%20Monitoreo%20de%20Olas%20de%20Reaprovisionamiento.jpeg)
