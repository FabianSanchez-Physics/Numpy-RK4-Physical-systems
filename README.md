# RK4 Integrator — NumPy

Implementación del método de Runge-Kutta de orden 4 desde cero en NumPy,
aplicado a dos sistemas físicos clásicos.

## Sistemas resueltos

- **Oscilador armónico** — comparación con solución analítica, error máximo: ~1e-7
- **Péndulo no lineal** — ángulo inicial 0.9π, régimen de alta amplitud

## Resultados

El integrador reproduce la solución analítica del oscilador con error máximo
del orden de 1e-7 sobre un intervalo t ∈ [0, 10] con paso h = 0.01.
El péndulo no lineal muestra período notablemente mayor al lineal
debido a la no linealidad de sin(θ) para ángulos grandes.

## Tecnologías

Python · NumPy · Matplotlib

## Cómo ejecutar

Abrir `rk4_physics.ipynb` en Google Colab o Jupyter Notebook.
```
