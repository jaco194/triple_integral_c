Este proyecto implementa un programa en lenguaje C para calcular:

✔ La masa total

✔ El centro de masa (x̄, ȳ, z̄)

de un cuerpo tridimensional con densidad variable, utilizando métodos numéricos de integración triple.
Densidades implementadas

Constante → ρ(x,y,z) = 1

Lineal → ρ(x,y,z) = a·x + b·y + c·z

Gaussiana → ρ(x,y,z) = exp(−(x² + y² + z²))

🔹 Métodos numéricos disponibles

Riemann tridimensional
Divide la región en Nx·Ny·Nz subceldas y evalúa en los centros.

Monte Carlo
Genera puntos aleatorios y estima la integral mediante promedios.

🔹 El programa permite:

✔ Ingresar límites de integración en x, y, z
✔ Elegir densidad
✔ Elegir método (Riemann o Monte Carlo)
✔ Elegir número de subdivisiones o muestras
✔ Calcular masa y centro de masa
✔ Medir el tiempo de ejecución
