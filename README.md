# Código de la tesis de maestría

Este repositorio contiene el código utilizado para los experimentos de mi tesis de la Maestría en Ingeniería Matemática de la Facultad de Ingeniería, Universidad de la República (Uruguay).

Este trabajo estudia la distancia de Fermat aplicada a datos genómicos para representar la estructura poblacional en baja dimensión. Se caracteriza teóricamente cuándo la distancia introduce “atajos” que modifican las relaciones de proximidad y se evalúa su efecto en simulaciones y en datos humanos reales.

## Experimentos

1. **Simulación binomial controlada:** estudio de la aparición de atajos y comparación con las predicciones teóricas.
2. **Modelo stepping-stone:** análisis de caminos y representaciones de una población estructurada espacialmente.
3. **Datos genómicos reales:** análisis de poblaciones humanas y de diez individuos uruguayos de ancestría mezclada.

Cada experimento se implementa en un notebook de Python.

## Disponibilidad de los datos

Los datos de la simulación binomial se generan directamente mediante el código.

Los datos del modelo stepping-stone provienen de las simulaciones de Díaz-Papkovich et al. (2026), disponibles en Zenodo (https://zenodo.org/records/17545804).

Los datos genómicos reales no se incluyen en este repositorio debido a restricciones de acceso. El código correspondiente se proporciona para documentar los procedimientos utilizados en el análisis.

## Reproducibilidad

Los notebooks contienen los procedimientos de cálculo y generación de figuras. La ejecución del experimento con datos reales requiere acceso autorizado a los archivos de entrada.
