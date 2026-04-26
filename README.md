Análisis de Mantenimiento Predictivo: Optimización de Procesos Industriales ⚙️📊

##  Descripción del Proyecto
Este proyecto es un estudio de caso detallado sobre la aplicación de técnicas de **Data Analytics** para la prevención de fallas en entornos de manufactura. Utilizando un dataset de mantenimiento industrial, el análisis se enfoca en identificar los factores mecánicos y térmicos que preceden a las paradas no programadas de línea.

El objetivo principal es transformar una estrategia de mantenimiento reactiva en una **proactiva**, optimizando la vida útil de las herramientas y minimizando el tiempo de inactividad.

##  Tecnologías Utilizadas
* **Python**: Lenguaje principal de análisis.
* **Pandas & NumPy**: Procesamiento y limpieza de datos.
* **Matplotlib & Seaborn**: Visualización avanzada y detección de patrones.
* **Jupyter Notebooks**: Documentación del flujo de trabajo.

##  Estructura del Dataset
El análisis se basa en 10,000 registros con las siguientes variables clave:
* **Temperaturas**: Aire y Proceso (convertidas de Kelvin a Celsius para mejor interpretación).
* **Variables de Torque y RPM**: Relación de fuerza y velocidad del equipo.
* **Desgaste de Herramienta (Tool Wear)**: Tiempo acumulado de uso en minutos.
* **Tipo de Falla**: Categorización de errores (Heat Dissipation, Power Failure, Overstrain, etc.).
  
##  Hallazgos Clave (Insights)
* **Umbral de Reemplazo:** Se identificó que el riesgo de falla por desgaste se acelera drásticamente después de los **180-200 minutos** de uso continuo.
* **Anomalías Operativas:** Las fallas de potencia (*Power Failure*) están correlacionadas con caídas de RPM cuando el Torque supera los 60 Nm.
* **Sensibilidad Térmica:** Las máquinas operando con productos de tipo **L (Low)** mostraron una mayor vulnerabilidad a fallas por disipación de calor bajo condiciones de alta temperatura de proceso.

##  Propuesta de Valor (Business Impact)
Basado en los datos, se recomiendan las siguientes acciones estratégicas:
1. **Mantenimiento Preventivo:** Programar cambios de piezas al alcanzar los 180 minutos de uso para evitar paradas críticas.
2. **Alertas en Tiempo Real:** Implementar monitoreo sobre la relación Torque/RPM para detener el proceso ante anomalías antes de que ocurra una rotura física.
3. **Optimización de Calidad:** Revisar los estándares de carga para productos de tipo "L", reduciendo la tasa de scrap en un potencial 15%.

---
**Desarrollado por:** Geremías Lauman  
*Analista de Datos con enfoque en Calidad y Logística Industrial.*
