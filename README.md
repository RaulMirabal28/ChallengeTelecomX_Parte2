# 📊 Predicción de Cancelación de Clientes – Challenge Telecom X

Este proyecto busca predecir la cancelación de clientes de una empresa de telecomunicaciones, como parte del Challenge Telecom X de Oracle ONE - Alura Latam.

## ✅ Objetivos
- Analizar datos de clientes y sus servicios contratados.
- Identificar factores que influyen en la cancelación.
- Crear modelos predictivos para anticipar el churn.

## 🧾 Dataset
Incluye información sobre:
- Servicios contratados (Internet, soporte técnico, TV, etc.)
- Tipo de contrato y métodos de pago
- Variables de facturación
- Variable objetivo: `Cancelacion` (True/False)

## 🧹 Preparación de datos
- Se eliminaron columnas irrelevantes (`IDCliente`, `CargoTotal`, `CostoDiario`).
- Se aplicó codificación one-hot.
- Se balancearon las clases con SMOTE.

## 🤖 Modelos utilizados
- **Random Forest** (sin normalización)
- **Regresión Logística** (con normalización de variables numéricas)

## 📈 Evaluación
- Accuracy: ~77-78%
- Regresión Logística logró mejor recall (detecta más cancelaciones).
- Random Forest fue más equilibrado en rendimiento general.

## 🧠 Principales factores de cancelación
- Contrato mes a mes
- Pocos meses como cliente
- Uso de fibra óptica
- Bajo cargo mensual

## 🎯 Estrategias sugeridas
- Incentivar contratos anuales
- Mejorar experiencia de usuarios con fibra óptica
- Ofrecer beneficios a clientes nuevos o de bajo gasto

Desarrollado por **Raúl Mirabal** – Oracle ONE - Alura Latam
