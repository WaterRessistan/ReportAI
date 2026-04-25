# 🛡️ ReportAI v1.0: AI-Powered Security Auditing

ReportAI es una herramienta avanzada de auditoría de seguridad que utiliza Visión Artificial y Modelos de Lenguaje de Gran Escala (LLMs) para transformar capturas de pantalla de vulnerabilidades en informes técnicos detallados y alineados con marcos normativos internacionales.

## 🚀 Características Principales

- **Análisis Multimodal**: Procesamiento simultáneo de texto e imágenes (capturas de pantalla de terminales, exploits o configuraciones).
- **Cumplimiento Normativo**: Mapeo automático de hallazgos contra marcos como ISO 27001, NIST SP 800-53, ENS España y GDPR.
- **Motor de IA de Última Generación**: Implementación nativa con el SDK google-genai (2026) utilizando Gemini 2.5 Flash.
- **Exportación Profesional**: Generación instantánea de reportes en formato .docx listos para entrega final.

## 🛠️ Stack Tecnológico

- **Core**: Python 3.10+
- **Interface**: Streamlit
- **AI SDK**: Google GenAI (Gemini API)
- **Document Engine**: python-docx
- **Image Processing**: Pillow (PIL)

## 📋 Instalación y Configuración

Sigue estos pasos para desplegar el entorno localmente:

### Clonar el repositorio:

```bash
git clone https://github.com/tu-usuario/reportai.git
cd reportai
```

### Crear y activar un entorno virtual:

```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
```

### Instalar dependencias:

```bash
pip install -r requirements.txt
```

### Ejecutar la aplicación:

```bash
streamlit run app.py
```

## 🔑 Configuración de la API

Para utilizar esta herramienta, necesitas una API Key de Google Gemini:

- Ve a [Google AI Studio](https://aistudio.google.com/).
- Genera tu clave de API.
- Introdúcela en la barra lateral de la aplicación al iniciar.

## 📖 Flujo de Trabajo

1. **Evidencia**: Sube una o varias capturas de pantalla del hallazgo (ej. salida de Nmap, consola de AWS, vulnerabilidad XSS).
2. **Contexto**: Describe brevemente el hallazgo y selecciona el marco normativo.
3. **Auditoría IA**: El sistema valida la integridad de la información. Si es suficiente, redacta el informe profesional.
4. **Reporte**: Descarga el documento .docx generado automáticamente.

## ⚠️ Aviso Legal (Disclaimer)

Esta herramienta ha sido diseñada exclusivamente para fines de auditoría ética y seguridad informática. El uso de ReportAI para analizar activos sin autorización previa es estrictamente ilegal. El autor no se hace responsable del mal uso de esta herramienta.

## 🤝 Contribuciones

Si deseas mejorar el motor de análisis o añadir nuevos marcos normativos, ¡los Pull Requests son bienvenidos!

Desarrollado con ❤️ para la comunidad de Ciberseguridad.
