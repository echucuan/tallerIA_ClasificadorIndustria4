# 🤖 Talleres de Inteligencia Artificial — Industria 4.0

> Talleres prácticos de IA para estudiantes de preparatoria.  
> Aprende haciendo: desde cero hasta tu primer modelo funcionando en ~60 minutos.

---

## 📋 Talleres disponibles

| # | Taller | Tema | Nivel | Notebook |
|---|--------|------|-------|----------|
| 01 | Clasificador de Imágenes | ¿Perro 🐶 o Gato 🐱? | Principiante | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/echucuan/tallerIA_ClasificadorIndustria4/blob/main/Taller_IA_Clasificador_V02.ipynb) |

> 🔜 Próximamente: Detección de objetos, NLP, Modelos generativos

---

## 🎯 ¿Qué aprenderás en el Taller 01?

- Qué es una **Red Neuronal Convolucional (CNN)**
- Cómo funciona el **Transfer Learning**
- Preparar y augmentar un **dataset** de imágenes
- **Entrenar** un clasificador con ~90% de precisión
- **Evaluar** y probar el modelo con fotos reales

---

## 🚀 ¿Cómo usar estos talleres?

### Opción A — Google Colab (recomendado, sin instalación)

1. Haz clic en el badge `Open in Colab` del taller que quieras
2. Ve a **Entorno de ejecución → Cambiar tipo de entorno → T4 GPU**
3. Ejecuta las celdas en orden de arriba hacia abajo
4. ¡Listo! No necesitas instalar nada en tu computadora.

### Opción B — Local (para usuarios avanzados)

```bash
# Clona el repositorio
git clone https://github.com/echucuan/tallerIA_ClasificadorIndustria4.git
cd TU_REPOSITORIO

# Instala dependencias
pip install -r requirements.txt

# Abre el notebook
jupyter notebook Taller_IA_Clasificador_V02.ipynb
```

---

## 🗂️ Estructura del repositorio

```
📦 talleres-ia/
├── 📓 Taller_IA_Clasificador_V02.ipynb   ← Taller 01 (este)
├── 🖼️  imagenes/                          ← Imágenes de prueba
│   ├── gato1.jpg
│   ├── gato2.jpg
│   ├── perro1.jpg
│   └── perro2.jpg
├── 📄 requirements.txt                    ← Dependencias (uso local)
└── 📄 README.md                           ← Este archivo
```

---

## 📦 Dependencias

```
tensorflow>=2.13
tensorflow-datasets
matplotlib
numpy
Pillow
requests
```

---

## 🧠 Tecnología que se usa

| Herramienta | ¿Para qué? |
|-------------|-----------|
| **TensorFlow / Keras** | Construir y entrenar redes neuronales |
| **MobileNetV2** | Modelo pre-entrenado (Transfer Learning) |
| **TF Datasets** | Dataset de perros y gatos (23,000+ imágenes) |
| **Google Colab** | Ejecutar en la nube con GPU gratis |
| **Matplotlib** | Visualizar imágenes y resultados |

---

## 📸 Imágenes de prueba

Puedes usar estas imágenes para probar tu modelo al final del taller:

| Imagen | Clase esperada |
|--------|---------------|
| `imagenes/gato1.jpg` | 🐱 Gato |
| `imagenes/gato2.jpg` | 🐱 Gato |
| `imagenes/perro1.jpg` | 🐶 Perro |
| `imagenes/perro2.jpg` | 🐶 Perro |

O bien puedes subir tus propias fotos directamente en el notebook.

---

## 🏭 Conexión con la Industria 4.0

Los clasificadores de imágenes que construyes en este taller son la base de:

- **Inspección de calidad automatizada** en líneas de manufactura
- **Diagnóstico médico asistido por IA** (rayos X, resonancias)
- **Vehículos autónomos** (detección de peatones, señales)
- **Seguridad y control de acceso** (reconocimiento facial)

La tecnología es la misma. ¡Tú ya sabes cómo funciona! 🔥

---

## 🙋 ¿Preguntas o problemas?

- **Error al ejecutar una celda:** Asegúrate de ejecutarlas en orden
- **Sin GPU:** Ve a *Entorno de ejecución → Cambiar tipo de entorno → T4 GPU*
- **Otra duda:** Abre un [Issue](https://github.com/echucuan/tallerIA_ClasificadorIndustria4/issues)

---

## 📄 Licencia

Este material es de uso libre con fines educativos.  
Si lo usas en tu escuela o taller, ¡cuéntanos! Nos encanta saber del impacto. 🌟

---

<div align="center">

Hecho con ❤️ para estudiantes curiosos

</div>
