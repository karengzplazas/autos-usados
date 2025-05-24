🧠 Análisis de Autos Usados para Inversión en Colombia 🚗💰

📌 # 📊 Resumen Ejecutivo: Análisis de Autos Usados

## 🧩 Contexto del Proyecto

Una empresa de compra y venta de autos usados está planeando expandirse en el mercado colombiano. Para tomar decisiones acertadas sobre qué vehículos adquirir, necesita comprender qué marcas, modelos y características de los autos representan mejores oportunidades de inversión, considerando variables como precio, kilometraje, tipo de transmisión y eficiencia del motor.

Como analista de datos, se te ha contratado para explorar una base de datos de autos usados y extraer conclusiones que sirvan como guía estratégica.

---

## 🎯 Objetivo

Identificar qué tipo de autos usados (marca, modelo, transmisión, combustible, etc.) son más convenientes para la empresa, maximizando la rentabilidad y reduciendo los riesgos de inversión.

---

## 📁 Datos Utilizados

- **Archivo fuente**: `cars.csv`
- **Número total de autos**: 38,531
- **Columnas disponibles**: 32 (como `manufacturer_name`, `model_name`, `transmission`, `price_usd`, `odometer_value`, `engine_capacity`, `year_produced`, `engine_fuel`, etc.)

**Estadísticas descriptivas**:
- Años de producción: 1942 - 2019 (mediana: 2003)
- Precio promedio: $6,639 USD
- Kilometraje promedio: 248,865 km
- Cilindraje promedio: 2.05 litros

---

## 🔍 Metodología

- Análisis exploratorio de datos (EDA)
- Limpieza y preprocesamiento de los datos
- Visualización de relaciones clave entre variables
- Construcción de un índice de conveniencia con criterios como:
  - Precio competitivo
  - Bajo kilometraje
  - Año reciente
  - Eficiencia de combustible
  - Garantía

---

## ✅ Hallazgos Clave

- **Marcas recomendadas**: Renault, Volkswagen, Ford, Hyundai, Nissan
- **Años ideales para invertir**: entre 2011 y 2019
- **Transmisión más conveniente**: Mecánica (mayor disponibilidad y menor costo)
- **Tipos de combustible más eficientes**: Gasolina y diésel (mejor rendimiento en mpg)
- **Variables más influyentes en el precio**: Año, kilometraje, tipo de transmisión, tipo de motor

---

## ❌ Autos a Evitar

- Vehículos con precios extremadamente bajos (< $500 USD)
- Con motores muy pequeños sin soporte híbrido o eléctrico (< 0.9 L)
- Demasiado antiguos o con muy alto kilometraje y sin garantía

---

## 📈 Visualizaciones Incluidas

- Barras y boxplots de precios por marca y transmisión
- Dispersión entre precio y kilometraje
- Evolución del índice de conveniencia por año
- Heatmaps de correlaciones

---

## 💡 Recomendaciones

Invertir en autos de gama media entre 2011 y 2019, con buena eficiencia y preferiblemente de transmisión mecánica. Favorecer las marcas más confiables y evitar modelos poco demandados o con características extremas en kilometraje o edad.
