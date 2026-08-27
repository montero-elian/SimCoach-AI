

# Sim-Coach AI Pro para Assetto Corsa 

Sim-Coach AI es una herramienta de telemetría avanzada que funciona como tu **Driver Coach** y tu **Ingeniero de Pista** personal, analizando tu manejo en tiempo real mediante Inteligencia Artificial (Google Gemini) y comunicándose con vos por radio de voz.

## Características Principales

* **Telemetría en Vivo:** Captura de datos a ~50Hz (velocidad, pedales, fuerzas G, suspensión, wheel slip, etc.).
* **Driver Coach Dinámico:** Analiza tus vueltas y te avisa por voz sobre errores graves y accionables (frenadas tardías, trail-braking incorrecto, etc.) justo antes de llegar a la curva problemática.
* **Ingeniero de Setup:** Al entrar a boxes tras dar al menos 3 vueltas, la IA lee tu setup local y te sugiere cambios mecánicos basados en el comportamiento del auto.
* **Dashboard Visual:** Gráficos en tiempo real de tus inputs (acelerador/freno) y mapa de la trazada con zonas de frenado.

## 📥 Instalación y Uso

1. Descargá la última versión desde la pestaña **[Releases](https://github.com/montero-elian/SimCoach-AI/releases)**.
2. Descomprimí el archivo `.zip` en cualquier carpeta de tu PC.
3. Ejecutá `SimCoach_AI.exe`.
4. Ingresá tu **API Key de Gemini** (Podés obtener una gratuita en [Google AI Studio](https://aistudio.google.com/app/apikey)).
5. Hacé clic en **CONECTAR**.
6. Abrí Assetto Corsa, salí a pista y completá al menos **3 vueltas válidas** seguidas.

## ⚠️ Notas Importantes

* **Windows Defender:** Al ser un ejecutable empaquetado con PyInstaller sin firma digital comercial, es posible que Windows Defender muestre una advertencia (SmartScreen). Hacé clic en *Más información -> Ejecutar de todas formas*.
* **Vueltas Válidas:** El sistema descarta automáticamente las vueltas donde detecta choques o incidentes graves (Fuerzas G extremas combinadas con derrape) para no contaminar el análisis de la IA.
* **Audio:** Asegurate de tener el volumen del juego balanceado para poder escuchar los mensajes de radio generados por TTS.
