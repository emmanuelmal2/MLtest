# Clasificador de Planes Móviles — Megaline

Este proyecto de *Machine Learning* tiene como objetivo construir un modelo de clasificación que prediga qué plan móvil es mejor para un cliente: **Smart** o **Ultra**, con base en su comportamiento.

La empresa ficticia **Megaline** busca que sus clientes migren a estos nuevos planes, y desea automatizar las recomendaciones a través de modelos inteligentes.

---

## Tecnologías y herramientas

- Python
- Pandas, NumPy
- Scikit-learn
- Árboles de decisión
- Bosques aleatorios
- Regresión logística
- Validación cruzada
- Métricas de evaluación: accuracy

## 📌 Resultado

El árbol de decisión, con un **76.98 %** de exactitud en el conjunto de prueba y un comportamiento coherente en los escenarios de cordura, supera el umbral mínimo del 75 % exigido y demuestra una capacidad intuitiva para recomendar planes según el perfil de uso.

Aunque el bosque aleatorio logró una precisión ligeramente mayor (**78.38 %**), su tendencia a asignar **Ultra** en todos los casos triviales evidencia un sesgo que lo hace menos confiable para usuarios de bajo consumo.

Por otro lado, la regresión logística quedó por debajo del umbral (**67.81 %**), por lo que el **árbol de decisión resulta ser la opción óptima** para la recomendación de planes Smart o Ultra en Megaline.

---

## ✍️ Autor

- Emmanuel Octavio Maldonado Escobedo  
*(estudiante de Ingeniería en Computación — UNAM)*
