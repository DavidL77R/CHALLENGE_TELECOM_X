# ✅ INFORME FINAL - Análisis de Evasión de Clientes (Churn)

## 1. 🧩 Introducción
El objetivo de este análisis es entender los factores que influyen en la **evasión de clientes (churn)** en una empresa de telecomunicaciones. Identificar patrones de cancelación permite **anticipar comportamientos** y aplicar estrategias para **reducir la pérdida de clientes**.

---

## 2. 🧹 Limpieza y Tratamiento de Datos

- Se importaron los datos desde un archivo JSON.
- Se estandarizaron columnas anidadas (`account`, `customer`, `internet`, etc.).
- Se transformaron columnas relevantes:
  - `Total_Gastado`, `Mensualidad`, `Meses_Contrato`: convertidas a numéricas.
  - `Cancelado`: convertido a 0 (no) y 1 (sí).
- Se eliminaron valores inválidos o vacíos.

---

## 3. 📊 Análisis Exploratorio de Datos

### 🔹 Distribución de Cancelaciones
Gráfico de barras que muestra la proporción de clientes que cancelaron o no.

### 🔹 Evasión según variables categóricas
Gráficos que muestran cómo cambia la evasión según:
- Tipo de contrato
- Método de pago
- Facturación electrónica

### 🔹 Evasión según variables numéricas
Boxplots que comparan:
- Total gastado
- Cuota mensual
- Tiempo de contrato
entre quienes cancelaron y quienes no.

---

## 4. 💡 Conclusiones e Insights

- La mayoría de los clientes **no cancelaron**, pero existe un porcentaje significativo que sí lo hizo.
- Clientes con **contratos mensuales** tienen mayor evasión que los de largo plazo.
- Quienes **gastan poco** o llevan **poco tiempo con la empresa** tienden a cancelar más.
- Los métodos de pago como **cheque por correo** están asociados a mayor evasión.
- Los clientes con **cargos mensuales más altos** muestran una mayor tasa de evasión, lo que puede indicar una relación entre el precio y la percepción del valor del servicio.

---

## 5. 🧠 Recomendaciones


- **Incentivar contratos anuales o bienales** mediante descuentos u ofertas exclusivas, promoviendo mayor compromiso del cliente.
- **Fomentar métodos de pago automáticos** como débito o tarjeta de crédito con beneficios (por ejemplo, puntos, descuentos).
- **Ofrecer paquetes combinados** (Internet + teléfono + TV) con precios preferenciales, para aumentar el valor percibido del servicio.
- **Monitorear a clientes con cargos altos**, brindando atención personalizada o beneficios extra para reducir el riesgo de evasión.
