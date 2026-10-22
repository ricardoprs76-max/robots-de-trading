# Robots de trading

Tres sistemas de trading algorítmico para el oro (XAU/USD) que desarrollé de punta a punta: investigación, pruebas históricas, programación del robot y alertas automáticas al teléfono.

> 🔒 **El código y la lógica de las estrategias son privados.** Este repositorio solo describe los proyectos de forma general.
>
> ⚠️ Proyectos personales y educativos, probados en cuentas demo. El trading con apalancamiento implica alto riesgo de pérdida. No es asesoría financiera.

## Problema que resuelven
Operar a mano exige mirar gráficos durante horas y decidir bajo presión, lo que lleva a errores y a operar por emoción. Estos robots aplican reglas fijas y medibles, se validan antes con datos históricos y avisan o ejecutan sin necesidad de estar frente a la pantalla, incluso con el PC apagado.

## Los tres robots

### 1. Robot Final Trading
Estrategia de reglas sobre el oro en 15 minutos con un filtro de régimen de mercado.
- Indicador en **TradingView** (Pine Script) que dibuja las señales en el gráfico.
- Asesor experto (**EA**) para **MetaTrader 5** en **MQL5**, probado en el probador de estrategias.
- **Alertas gratuitas a Telegram** desde la nube (Google Apps Script), que funcionan con el PC apagado.

### 2. Agentes IA Trading
Un sistema de varios «agentes» de análisis técnico y un coordinador que combina sus opiniones.
- Programado como EA en **MQL5** para MetaTrader 5.
- Envía a **Telegram** recomendaciones legibles (entrada, stop loss y take profit) y hace seguimiento vela a vela. No coloca órdenes por sí mismo.

### 3. Trading Algorítmico
Investigación con **aprendizaje automático** y reglas cuantitativas.
- Modelos **XGBoost** entrenados con validación *walk-forward* en **Python** y exportados a **ONNX** para ejecutarse dentro de MetaTrader 5.
- Bot en la nube con estrategias de reglas y datos de mercado en tiempo real, con avisos por **Telegram**.

## Tecnologías
**MQL5** (MetaTrader 5) · **Pine Script** (TradingView) · **Python** (pandas, XGBoost, ONNX) · **Google Apps Script** · **API de Telegram** · API de datos de mercado (Twelve Data) · simulaciones propias de pruebas históricas

## Funcionalidades comunes
- Pruebas históricas y *walk-forward* antes de cualquier uso.
- Gestión de riesgo: tamaño de lote, stop loss, límite de operaciones y filtros de horario.
- Alertas en tiempo real al celular por Telegram.
- Integración con la app **[Trading Automático](https://github.com/ricardoprs76-max/trading-automatico)**, que convierte las señales de Telegram en órdenes en MetaTrader 5 móvil.

## Capturas de pantalla
No se publican capturas, para no revelar la lógica de las estrategias.

## Instalación y uso
El código no es público. Si te interesa conocer los proyectos en detalle, escríbeme.

## Contacto
**Ricardo Augusto Porras Díaz** — Desarrollador de software y abogado especialista en derecho administrativo
- Correo: [ricardoprs76@gmail.com](mailto:ricardoprs76@gmail.com)
- GitHub: [github.com/ricardoprs76-max](https://github.com/ricardoprs76-max)
