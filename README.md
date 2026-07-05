# Sistema de Triaje Inteligente & Derivación Médica (MVP)

Este proyecto es parte de un proyecto personal. El sistema permite realizar un triaje clínico automatizado utilizando escalas de valoración (FAST, IAM, Glasgow) y geolocalización para derivar pacientes a casas de salud en Quito, Ecuador, según su cobertura y nivel de complejidad.

## 🚀 Características
- **Triaje clínico automatizado:** Clasificación de pacientes basada en signos vitales y escalas validadas.
- **Geolocalización:** Cálculo de distancia en tiempo real a centros hospitalarios cercanos.
- **Integración con Mapas:** Navegación asistida mediante Google Maps.

## 🛠️ Tecnologías
- **Python 3.12**
- **Streamlit** (Interfaz web)
- **Pandas & NumPy** (Procesamiento de datos)
- **Streamlit-geolocation** (Geolocalización)

## 📋 Requisitos previos
Para ejecutar esta aplicación, asegúrate de tener instalado Python y contar con el archivo de base de datos de hospitales en el mismo directorio.

## ⚙️ Instalación
1. Clona este repositorio:
   `git clone https://github.com/tu-usuario/tu-repositorio.git`
2. Instala las dependencias:
   `pip install -r requirements.txt`
3. Ejecuta la aplicación:
   `streamlit run triage_app.py`
