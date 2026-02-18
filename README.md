# 🔄 Convertidor IA

> Convertí documentos de forma inteligente con el poder de Google Gemini AI.  
> Más preciso que las páginas web de conversión tradicionales.

---

## ✨ ¿Qué es Convertidor IA?

**Convertidor IA** es una aplicación de escritorio para Windows que usa inteligencia artificial (Google Gemini) para convertir documentos con alta precisión. A diferencia de las páginas web de conversión tradicionales, usa IA para entender el contenido real del documento, lo que resulta en conversiones mucho más precisas, especialmente para tablas y documentos escaneados.

---

## 🚀 Funciones

- 📄 **PDF** → Excel, Word, Imágenes
- 🖼️ **Imágenes** (JPG, PNG, TIFF, BMP, WEBP) → Excel, PDF, Word
- 📊 **Excel** → PDF, Word, Imágenes
- 📝 **Word** → PDF, Excel, Imágenes
- ✅ Procesamiento de **múltiples archivos** a la vez
- ✅ **Drag & Drop** — arrastrá archivos directo a la ventana
- ✅ Los archivos se guardan automáticamente en tu carpeta **Descargas**
- ✅ Interfaz moderna y simple

---

## 📥 Descarga

### Opción — Desde el código fuente
Desde el código Python, seguí las instrucciones de instalación más abajo.

---

## 🖥️ Cómo usar

1. Abrí **Convertidor IA**
2. Arrastrá un archivo a la ventana **o** hacé click para seleccionarlo
3. Elegí el formato de destino
4. Hacé click en **COMENZAR CONVERSIÓN**
5. El archivo convertido se guarda automáticamente en tu carpeta **Descargas**

---

## ⚙️ Instalación desde código fuente

### Requisitos
- Windows 10 o superior
- Python 3.8+
- Una API Key de Google Gemini (gratis en [aistudio.google.com](https://aistudio.google.com/apikey))

### Pasos

**1. Cloná el repositorio**
```bash
git clone https://github.com/TU_USUARIO/convertidor-ia.git
cd convertidor-ia
```

**2. Instalá las dependencias**
```bash
pip install pillow google-genai pandas openpyxl reportlab pymupdf python-docx
```

**3. Pegá tu API Key**

Abrí `CONVERTIDOR_IA.py` y reemplazá en la línea 6:
```python
GEMINI_API_KEY = "tu-api-key-aquí"
```

**4. Ejecutá el programa**
```bash
python CONVERTIDOR_IA.py
```

---

## 🔨 Crear el .exe vos mismo

Si querés generar tu propio ejecutable con tu API key:

```bash
pip install pyinstaller
pyinstaller --onefile --windowed --name "Convertidor IA" CONVERTIDOR_IA.py
```

El `.exe` va a estar en la carpeta `dist/`.

---

## 🤖 ¿Por qué es mejor que otras herramientas?

Las herramientas de conversión tradicionales usan OCR básico que a menudo pierde la estructura de tablas, mezcla columnas o pierde datos. **Convertidor IA** usa Google Gemini, un modelo de lenguaje avanzado que *entiende* el contenido del documento y reconstruye la estructura con alta fidelidad.

Ideal para:
- Documentos escaneados con tablas complejas
- PDFs generados desde imágenes
- Conversiones masivas de múltiples archivos

---

## 📋 Dependencias

| Librería | Uso |
|---|---|
| `google-genai` | API de Google Gemini (IA) |
| `pillow` | Procesamiento de imágenes |
| `pandas` + `openpyxl` | Generación de archivos Excel |
| `reportlab` | Generación de PDFs |
| `pymupdf` | Lectura de PDFs |
| `python-docx` | Lectura y escritura de Word |

---

## 📄 Licencia

MIT License — libre para usar, modificar y distribuir.

---

## 👤 Tomi

Desarrollado con ❤️ y mucha IA (soy todo menos un desarrollador) 
Si te fue útil, dejá una ⭐ en el repositorio.

