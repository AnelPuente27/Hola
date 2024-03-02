#!/bin/bash

# Nombre del archivo CSV
archivo="Accidentes_ags_2021.csv"

# Calcular la suma de la columna "PASCAMION"
suma=$(awk -F',' '{suma+=$16} END {print suma}' "$archivo")

# Mostrar la suma
echo "La suma de los datos de PASCAMION es: $suma"
