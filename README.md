# Proyecto Final — Econometría Financiera
**EGADE Business School | ITESM**  
**Alumno:** Héctor Guillermo Fuentes González | A01452149  
**Profesor:** Dr. Raymundo Díaz Robles  
**Fecha:** 20 de marzo de 2026  

---

## Descripción
Proyecto final del curso de Econometría Financiera. Análisis econométrico 
de un portafolio de 15 acciones (11,960 posiciones, $6.17M valor de mercado) 
utilizando modelos de regresión, series de tiempo, data panel y GARCH.

---

## Archivos del repositorio

| Archivo | Descripción |
|---------|-------------|
| `Proyecto_Final_Econometria_Financiera.ipynb` | Notebook completo en Google Colab |
| `Proyecto_Final_Econometria_Financiera.html` | Versión HTML del notebook |
| `Proyecto_Final_Econometria_Financiera.pdf` | Documento final del proyecto (PDF) |
| `AI_Prompts_Claude.md` | Prompts de IA utilizados en el desarrollo |
| `regresion_simple_nvda.png` | Regresión lineal simple — NVDA vs tiempo |
| `regresion_multiple_nvda.png` | Regresión múltiple — NVDA vs VOO + Volumen + META |
| `tsla_series_frecuencias.png` | Series de tiempo TSLA (horaria y 5 minutos) |
| `tsla_acf_pacf.png` | Funciones ACF y PACF — rendimientos horarios TSLA |
| `tsla_forecast_arima.png` | Forecast ARIMA(1,1,1) — próximas 24 horas |
| `data_panel_trimestral.png` | Data panel trimestral — 10 empresas |
| `garch_rendimientos.png` | Rendimientos diarios NVDA y TSLA |
| `garch_volatilidad.png` | Volatilidad condicional GARCH(1,1) |

---

## Modelos econométricos

- **Regresión lineal simple** — Precio NVDA vs tiempo (R²=0.927)
- **Regresión múltiple** — Rendimiento NVDA vs VOO + Volumen + META (R²adj=0.393, β_VOO=2.319)
- **Series de tiempo + ARIMA(1,1,1)** — Forecast 24h precio TSLA con IC 95%
- **Data panel trimestral** — 10 empresas × 5–7 trimestres (ingresos, EBITDA, utilidad neta)
- **GARCH(1,1)** — Volatilidad condicional NVDA (persistencia=0.717) y TSLA (persistencia=0.978) *(puntos extra)*

---

## Portafolio
15 acciones | 11,960 posiciones | $6,175,322.27 USD valor de mercado  
Outperformance vs SPY: ~+5% en febrero–marzo 2026
