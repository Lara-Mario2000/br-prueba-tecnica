# Prueba Técnica:

## Objetivo
El objetivo principal de esta prueba es validar tus conocimientos en **Python**, tu capacidad analítica para identificar patrones de riesgo y tu habilidad para traducirlos en **reglas de negocio efectivas y medibles**.

---

## 1. Contexto y Lógica de Negocio

Imagina que formas parte del equipo de analítica operativa de una importante cadena de supermercados. Recientemente, se ha detectado un incremento en los niveles de **devoluciones anómalas y reclamos injustificados de productos**, lo cual está afectando directamente la rentabilidad del negocio.

Tu misión principal es **diseñar una regla (o un set de reglas)** que logre identificar y alertar la mayor cantidad de solicitudes de devolución abusivas, minimizando al máximo la afectación sobre las compras y garantías legítimas de nuestros clientes regulares.

> **Reto clave:** Como parte del ejercicio, deberás definir y justificar estadísticamente bajo qué umbrales o métricas consideramos que el desempeño de tu regla es aceptable para implementarse en producción sin dañar la experiencia de compra de los consumidores honestos.

---

## 2. Obtención de Datos

Para comenzar la prueba, se te proporcionarán dos conjuntos de datos que servirán como base para tu análisis exploratorio y la construcción de tu script en Python:

* **Fuente Normal (Buenos):** Registro histórico de compras y devoluciones operadas de forma regular, exitosa y legítima.
* **Fuente Anómala (Malos):** Registro de transacciones tipificadas y confirmadas como devoluciones abusivas, violaciones de política o pérdidas directas para la tienda.

---

## 3. Entregables

Al finalizar la prueba, deberás compartirnos los siguientes dos archivos:

### A) Archivo de Código
Tu script en formato `.py` o un Jupyter Notebook (`.ipynb`) con el desarrollo completo de tu análisis.

### B) Reporte de Reglas (Excel)
Un documento que resuma los resultados de tu estrategia, el cual debe contener estrictamente la siguiente estructura de columnas:

| Columna | Descripción / Ejemplo |
| :--- | :--- |
| **Nombre de la regla** | Ej. `Regla_Monto_Canal_01` |
| **Descripción de la regla** | Explicada en lenguaje sencillo de negocio (Ej. *"Compras con montos entre $5,000 y $8,000 realizadas en..."*) |
| **Casos totales** | Volumen total evaluado por la regla. |
| **Casos malos** | Transacciones de fraude correctamente detenidas (Verdaderos Positivos). |
| **Casos buenos** | Transacciones legítimas afectadas por error (Falsos Positivos). |
| **Exactitud** | *Accuracy* |
| **Precisión** | *Precision* |
| **Sensibilidad** | *Recall* |
| **Especificidad** | *Specificity* |

---

## ¿Qué evaluaremos?

* **Racional analítico:** El proceso, la exploración de datos y la lógica de negocio que utilizaste para encontrar el patrón y definir la regla.
* **Calidad técnica:** La estructura, limpieza y eficiencia de tu código en Python.
* **Visión de negocio:** Tu capacidad para encontrar el punto de equilibrio óptimo entre frenar el riesgo y no afectar la venta legítima.

---

## Tiempo de entrega

**No tenemos un tiempo estimado o límite estricto para la entrega.** Queremos priorizar la calidad y profundidad de tu análisis sobre la velocidad, así que siéntete con total libertad de tomarte el tiempo que consideres necesario para desarrollar tu mejor propuesta.
