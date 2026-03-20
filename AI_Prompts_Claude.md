# AI-Assisted Development — Prompts utilizados en el Proyecto Final

**Proyecto:** Econometría Financiera — Proyecto Final  
**Alumno:** Héctor Guillermo Fuentes González | A01452149  
**Institución:** EGADE Business School — ITESM  
**Fecha:** 20 de marzo de 2026  
**Herramienta:** Claude (Anthropic) — Asistente de IA conversacional  

---

## Descripción del uso de IA

Para el desarrollo del proyecto final se utilizó Claude (Anthropic) como 
asistente de IA a lo largo de todo el proceso de desarrollo. El asistente 
apoyó en la estructuración del código, interpretación de resultados 
econométricos, redacción del documento Word y justificación de las 
decisiones de inversión del portafolio.

---

## Prompts principales utilizados

### 1. Configuración del entorno
```
"Necesito hacer mi proyecto final de econometría financiera en Google Colab 
con Python. Ayúdame a instalar las librerías necesarias: yfinance, 
statsmodels, arch, pandas, numpy y matplotlib"
```

### 2. Descarga de datos del portafolio
```
"Descarga datos de mis 15 acciones (VOO, NVDA, ASML, AVGO, MSFT, BAC, WMT, 
TSLA, GM, PFE, INTC, V, CMCSA, COST, META) en tres frecuencias: diaria 
(2023-2025), horaria (60 días) y 5 minutos (5 días) usando yfinance"
```

### 3. Regresión lineal simple
```
"Genera el modelo de regresión lineal simple OLS para el precio de NVDA 
en función del tiempo usando statsmodels. Incluye gráfica del precio vs 
tendencia lineal y gráfica de residuales"
```

### 4. Regresión múltiple
```
"Genera el modelo de regresión múltiple para el rendimiento logarítmico 
diario de NVDA usando como variables independientes el rendimiento de VOO, 
el volumen normalizado de NVDA y el rendimiento de META. Incluye gráfica 
Real vs Ajustado, residuales en el tiempo y coeficientes beta"
```

### 5. Series de tiempo y prueba ADF
```
"Analiza la serie horaria de TSLA, aplica la prueba Augmented Dickey-Fuller 
para verificar estacionariedad, y genera las gráficas ACF y PACF de los 
rendimientos diferenciados para identificar los órdenes p y q del ARIMA"
```

### 6. Modelo ARIMA y forecast
```
"Estima un modelo ARIMA(1,1,1) sobre el precio horario de TSLA y genera 
un forecast de las próximas 24 horas con intervalo de confianza al 95%. 
Incluye tabla con los valores pronosticados hora por hora"
```

### 7. Data Panel trimestral
```
"Descarga los estados financieros trimestrales de 10 empresas del portafolio 
usando yfinance quarterly_financials. Extrae ingresos, EBITDA y utilidad 
neta para los últimos 8 trimestres y calcula el margen neto. Genera 4 
gráficas: ingresos, EBITDA, utilidad neta y margen neto"
```

### 8. Modelo GARCH (puntos extra)
```
"Aplica la prueba de efectos ARCH de Engle sobre los rendimientos diarios 
de NVDA y TSLA. Luego estima un modelo GARCH(1,1) para cada acción, 
genera el forecast de volatilidad para los próximos 10 días y visualiza 
la volatilidad condicional sigma_t con bandas ±2σ"
```

### 9. Justificación del portafolio
```
"Justifica las compras del portafolio combinando los hallazgos de los 
modelos econométricos (beta de mercado 2.319, R²=0.927, forecast ARIMA, 
persistencia GARCH) con el análisis fundamental del data panel trimestral"
```

---

## Impacto del uso de IA en el proyecto

El uso de Claude como asistente permitió acelerar significativamente el 
desarrollo del proyecto manteniendo el rigor econométrico. Todos los 
resultados, interpretaciones y decisiones de inversión fueron revisados 
y validados por el alumno. La IA actuó como herramienta de apoyo para 
la implementación técnica y la estructuración del análisis, mientras que 
el criterio económico y la interpretación de los modelos fue 
responsabilidad del alumno.

---

*Documento generado como evidencia del proceso de desarrollo asistido 
por IA para el Proyecto Final de Econometría Financiera — EGADE 2026*
