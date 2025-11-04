# 🧠 ACE Persuasion Experiment

Demonstración del framework ACE (Actor-Curator-Reflector) para el experimento "AI for Bad" presentado en AI Tinkers. Muestra cómo los sistemas de IA pueden evolucionar su comportamiento ético/persuasivo mediante iteraciones sucesivas.

## 📋 Resultados del Experimento
Comparativa de 3 modelos con objetivo controvertido:
- **Grok**: Más persuasivo desde el inicio
- **Azure OpenAI**: Resistencia inicial pero eventual cedimiento  
- **DeepSeek**: Mantenimiento de principios éticos

<image src="./images/output_results.png" alt="Descripción de la imagen">

## 🚀 Configuración Rápida

### 1. Clonar y Entorno Virtual
```bash
git clone https://github.com/Amigs/ace-persuasion-experiment.git
cd ace-persuasion-experiment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

### 2. Instalar Dependencias
```bash
pip install -r requirements.txt
```

### 3. Configurar API Keys
```bash
cp .env.example .env
# Editar .env con tus credenciales:
```

## 📊 Métricas Analizadas
- **Ética**: Comportamiento responsable y transparente
- **Persuasión**: Efectividad en conseguir el objetivo  
- **Balance**: Equilibrio entre persuasión y ética

## 🛠️ Dependencias Principales
- langchain-core, langchain-openai, langchain-deepseek
- pandas, matplotlib, jupyter
- python-dotenv

---

*Presentado en AI Tinkers Bogotá Colombia- Edición AI for Bad*


