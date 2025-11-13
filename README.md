# Análisis de Grupo de WhatsApp con Anonimización Avanzada

Análisis exploratorio completo de un grupo de WhatsApp con **protección total de privacidad** mediante anonimización robusta.

## 🔒 Características Principales

- **Anonimización Completa**: Todos los nombres reales son reemplazados por personajes ficticios
- **Análisis Profundo**: Extracción de patrones, tendencias y características del grupo
- **Expresiones Regulares Avanzadas**: Uso extensivo de regex para parseo y limpieza de datos
- **Protección de Privacidad**: Exclusión configurable de nombres sensibles
- **Visualizaciones Profesionales**: Gráficos y nubes de palabras para insights

## 📊 Análisis Incluidos

1. **Estadísticas Descriptivas**: Resumen general del grupo y período de análisis
2. **Nube de Palabras**: Visualización de palabras más frecuentes
3. **Usuarios Más Activos**: Ranking de participantes por mensajes enviados
4. **Distribución Temporal**: Análisis por hora del día y día de la semana
5. **Análisis Texto vs Multimedia**: Perfiles de usuario según tipo de contenido
6. **Evolución del Grupo**: Tendencias a lo largo del tiempo
7. **Menciones**: Quiénes son el centro de atención
8. **Uso de Emojis**: Expresividad de cada usuario

## 📁 Estructura del Proyecto

```
Grupo_whatsapp/
├── analisis_whatsapp_proteccion_reforzada.ipynb  # Notebook principal
├── .env.example                                    # Plantilla de configuración
├── .gitignore                                      # Archivos a ignorar en git
├── README.md                                       # Este archivo
└── .github/
    └── instructions/
        └── copilot-instructions.md                # Instrucciones de desarrollo
```

## 🚀 Uso

### Requisitos

- Python 3.8+
- Jupyter Notebook
- Librerías: pandas, numpy, matplotlib, seaborn, wordcloud

### Instalación

1. Clona el repositorio
2. Instala las dependencias:
   ```bash
   pip install pandas numpy matplotlib seaborn wordcloud
   ```

3. Copia el archivo de chat de WhatsApp a la carpeta del proyecto:
   ```
   Chat de WhatsApp con [nombre].txt
   ```

4. Configura los nombres a excluir (opcional):
   - Copia `.env.example` a `.env`
   - Agrega los nombres/apodos que quieras excluir de la nube de palabras

### Ejecución

1. Abre el notebook en Jupyter:
   ```bash
   jupyter notebook analisis_whatsapp_proteccion_reforzada.ipynb
   ```

2. Ejecuta las celdas en orden desde el inicio

## 🔐 Privacidad y Seguridad

### Protecciones Implementadas

- ✅ Nombres reales reemplazados automáticamente
- ✅ Variantes de nombres (apodos, diminutivos) anonimizadas
- ✅ Números de teléfono enmascarados
- ✅ Menciones procesadas y anonimizadas
- ✅ Datos sensibles eliminados del DataFrame
- ✅ Archivo original nunca compartido

### Archivos Excluidos de Git

- `*.txt` - Archivo de chat original (contiene datos sensibles)
- `.env` - Nombres personalizados a excluir

## 🛠️ Funcionalidades Técnicas

### Anonimización Avanzada

- Generación de variaciones de nombres (completos, fragmentados, sin acentos)
- Patrones regex dinámicos para cada usuario
- Manejo de menciones en múltiples formatos
- Normalización unicodedata para capturar variantes con acentos

### Análisis de Texto

- Extracción de palabras y conteo
- Detección de emojis con regex Unicode
- Clasificación automática de tipos de mensaje
- Limpieza inteligente con stopwords

### Visualizaciones

- Gráficos de barras horizontales y verticales
- Nube de palabras personalizada
- Análisis de tendencias temporales
- Gráficos apilados para composición

## 📝 Notas Importantes

- El archivo de chat original (`*.txt`) **NO se incluye** en el repositorio
- El archivo `.env` con nombres personalizados **NO se incluye** en el repositorio
- Solo el notebook y el código son compartidos públicamente
- Los resultados del análisis pueden ser compartidos libremente

## 🤝 Contribuciones

Este proyecto está diseñado como plantilla reutilizable para análisis de grupos de WhatsApp con protección de privacidad.

## 📄 Licencia

Este proyecto respeta la privacidad de todos los participantes y no debe usarse para fines de vigilancia o distribución de información personal.

---

**Creado con Python, Pandas y amor por los datos privados** 🐺❤️
