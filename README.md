# 📚 Sistema de Retroalimentación - Matemáticas Discretas

Aplicación web para generar retroalimentación automatizada de ejercicios de Matemáticas Discretas.

## 🌟 Características

- **R3MD - Conjuntos**: Generador de retroalimentación por ejercicios de conjuntos
- **R4MD - Proposiciones Lógicas**: Calificador automático de foros
- **R7MD - Mensajes Predefinidos**: Mensajes personalizados para evaluaciones

## 🚀 Deployment en Streamlit Cloud

### Estructura de Archivos Necesaria

```
tu-repositorio/
│
├── final.py                    # Archivo principal
├── requirements.txt            # Dependencias
├── .streamlit/
│   └── config.toml            # Configuración (opcional)
└── README.md                  # Este archivo
```

### ⚠️ Nota Importante sobre el Historial

El historial de calificaciones (R4MD) se almacena temporalmente. En Streamlit Cloud, 
los archivos JSON se perderán cuando la aplicación se reinicie. Para uso persistente,
considera implementar una base de datos o almacenamiento en la nube.

## 📦 Instalación Local

```bash
pip install -r requirements.txt
streamlit run final.py
```

## 🔧 Tecnologías

- Python 3.8+
- Streamlit
- Pandas
- python-docx
- PyPDF2 / pdfplumber
- BeautifulSoup4

## 📝 Uso

1. Selecciona el módulo deseado en el menú lateral
2. Carga los archivos requeridos
3. Procesa y genera retroalimentación
4. Descarga o copia los resultados

## 👨‍💻 Desarrollo

Aplicación desarrollada para facilitar la evaluación de ejercicios de Matemáticas Discretas.

---
**Versión**: 1.0 | **Última actualización**: 2025
