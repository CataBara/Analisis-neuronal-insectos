# Bitácora de prompts — lab 1

## Prompt 1
Tengo el diguiente diccionario en Google Collab de Phyton  : 
(pegue mi codigo para crear el diccionario)
Luego, hice la siguiente filtración 

(pegue mi codigo que filtra el diccionario)

Ahora, necesito que me des un codigo que haga un histograma de la columna n_spikes para las filas con estímulo viento, con labels en los ejes y colores pálidos.

**Qué me devolvió:**  import matplotlib.pyplot as plt viento = datos[datos["estimulo"] == "viento"] plt.figure(figsize=(8, 5)) plt.hist(viento["n_spikes"], bins=10, color="#AEC6CF", edgecolor="white") plt.xlabel("Número de spikes") plt.ylabel("Frecuencia") plt.title("Distribución de n_spikes para estímulo 'viento'")

