#!/bin/bash

# Nombre del archivo CSV
archivo="Accidentes_ags_2021.csv"
echo "ID          AUTOMOVIL"
echo "-----------------------------"
# Filtrar los datos del archivo CSV por el lugar "abastos" y mostrar los campos ID y AUTOMOVIL en columnas
grep -i "ABASTOS" "$archivo" | awk -F ',' '{print $1 "," $13}' | column -s', ' -t
