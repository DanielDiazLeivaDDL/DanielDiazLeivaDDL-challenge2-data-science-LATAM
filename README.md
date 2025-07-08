# 📉 Análisis de Evasión de Clientes (Churn) - TelecomX LATAM

Este proyecto analiza el comportamiento de los clientes de una empresa de telecomunicaciones ficticia, **TelecomX LATAM**, con el objetivo de identificar patrones asociados a la evasión de clientes (*churn*) mediante técnicas de análisis exploratorio de datos (EDA) y visualización.

---

## 🎯 Objetivos del proyecto

- Identificar qué características tienen los clientes que abandonan el servicio.
- Visualizar la proporción de evasión y su relación con variables como:
  - Género
  - Tipo de contrato
  - Método de pago
  - Cantidad de servicios contratados
  - Cargos mensuales y totales
- Calcular correlaciones para detectar las variables más influyentes.
- Generar un informe estructurado con conclusiones y recomendaciones.

---

## 🧰 Tecnologías y librerías

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ⚙️ Flujo de trabajo

1. **Carga y limpieza de datos**
   - Reemplazo de valores vacíos en `Churn`
   - Conversión de columnas categóricas a formato binario (0 y 1)
   - Conversión de `Charges.Total` a valor numérico
   - Creación de columna `ChargesDaily`

2. **Visualización**
   - Gráficos de barras, pastel y boxplots para explorar:
     - Distribución de churn
     - Género
     - Contrato
     - Método de pago
     - Gastos diarios y servicios
    
3. **Informe**
   - Conclusiones clave con base en visualizaciones y correlaciones
   - Recomendaciones estratégicas para retención de clientes

4. **Correlación**
   - Cálculo de la correlación entre variables numéricas y `Churn`
   - Identificación de factores con mayor relación al abandono



---

## 📈 Principales hallazgos

- Los clientes con **contratos mensuales** tienen mayor tasa de evasión.
- Los **clientes con más servicios contratados** (como seguridad en línea y soporte técnico) tienden a permanecer.
- La **duración como cliente** (`tenure`) está fuertemente asociada a la retención.
- El uso de **facturación electrónica** y el pago por **cheque electrónico** aparece frecuentemente en clientes que se dan de baja.

---

## 💡 Recomendaciones

- Implementar **programas de fidelización** para nuevos clientes.
- Promover **contratos anuales o bianuales** con beneficios exclusivos.
- Ofrecer **agrupación de servicios** para aumentar valor percibido.
- Aplicar un **modelo de predicción de churn** con las variables más correlacionadas.

---

## 👨‍💻 Autor

**Daniel Elías Díaz Leiva**  
📧 daniel.diazleiva.ingeco@gmail.com  


