# 🧠 Freud‑Server

**Conversación inteligente con IA local para evaluación psicológica indirecta.**

Este proyecto es un servidor de chat impulsado por modelos de lenguaje alojados localmente con [Ollama](https://ollama.com/), diseñado para evaluar a una persona psicológicamente durante una conversación natural de 5 minutos. Todo funciona sin conexión a internet, sin uso de APIs externas, 100% en tu máquina.

---

## 🎯 Objetivo

> Evaluar de forma indirecta el estado emocional y psicológico de una persona a través de una conversación guiada de 5 minutos con una IA.

Este sistema simula una conversación fluida y natural, capturando el contexto reciente y utilizando un **prompt psicológico especializado** para detectar rasgos emocionales, estados mentales y reacciones, sin preguntas invasivas.

---

## 🚀 Características

- ✅ **IA local (offline)** – Potenciada por Ollama y modelos como LLaMA3, Mistral, etc.
- 🧠 **Memoria de 5 minutos** – La IA solo recuerda lo conversado en los últimos 5 minutos, simulando enfoque clínico.
- 🧬 **Prompt psicológico** – Diseñado para generar respuestas que permiten evaluar personalidad y emociones indirectamente.
- 📦 **Modular y Extensible** – Puedes convertir este motor en una IA multipropósito.
- 📈 **TensorFlow ready** – Incluye espacio para añadir análisis de sentimiento y patrones psicológicos con Machine Learning.

---

## 🛠️ Tecnologías

- 🐍 Python 3.11+
- 🔁 Ollama (para ejecutar modelos LLM locales)
- 🧠 Modelos LLaMA3, Mistral o similares
- 🧮 TensorFlow (opcional, para análisis de respuestas)
- 🗃️ JSON (para el historial en memoria)

---

## 📦 Instalación

```bash
# Clona el repositorio
git clone https://github.com/tuusuario/freud-server.git
cd freud-server

# Instala dependencias de Python
pip install -r requirements.txt

# Descarga el modelo local (ejemplo con LLaMA3)
ollama pull llama3

# Inicia el servidor de Ollama
ollama serve
