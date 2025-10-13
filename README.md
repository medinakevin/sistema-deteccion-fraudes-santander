# 🚨 Sistema de Detección de Fraudes - Santander México

**Proyecto Integrador - 5to Semestre - Ciencia de Datos para Negocios**  
*Universidad Nacional Rosario Castellanos*

---

## 🎯 **Objetivo**
Desarrollar un sistema integral de detección de fraudes en transacciones digitales para **Santander México**, combinando técnicas avanzadas de machine learning, procesamiento de big data y estrategias de comunicación para optimizar la seguridad y experiencia del cliente.

---

## 👥 **Equipo**

| Rol | Integrante | Responsabilidades |
|-----|------------|-------------------|
| **🛠️ Arquitecto de Datos & Big Data** | Kevin Axel Medina Santander | Pipeline de datos, bases de datos, arquitectura escalable |
| **🤖 Científico de Datos / ML Engineer** | Axl Jim Sanchez Diaz | Modelos de ML, análisis predictivo, algoritmos de clasificación |
| **📊 Especialista en Operaciones & Analytics** | Citlali Itzell Saldivar Salas | Optimización, teoría de colas, visualizaciones, KPIs |
| **📝 Estratega de Comunicación & Documentador** | Angela Estefania Martinez Lara | Documentación, reportes, pitch, estrategia de comunicación |

---

## 📁 **Estructura del Proyecto**
sistema-deteccion-fraudes-santander/
├── 📊 data/ # Datasets y datos procesados
│ ├── raw/ # Datos originales
│ └── processed/ # Datos limpios y preparados
├── 📓 notebooks/ # Análisis y modelos en Jupyter
│ ├── 01_analisis_exploratorio.ipynb
│ ├── 02_modelo_machine_learning.ipynb
│ └── 03_demo_interactivo.ipynb
├── 🖥️ src/ # Código fuente del sistema
│ ├── database/ # Scripts de bases de datos
│ ├── models/ # Modelos de machine learning
│ └── utils/ # Utilidades y visualizaciones
├── 📚 docs/ # Documentación y reportes
│ ├── reporte_tecnico.md
│ ├── pitch_proyecto.md
│ └── presentacion/
└── 📄 README.md # Este archivo

text

---

## 🛠️ **Tecnologías Utilizadas**

### **💻 Lenguajes & Plataformas**
- **Python 3.8+** - Desarrollo principal
- **SQL** - Consultas estructuradas
- **MongoDB** - Datos no estructurados
- **Jupyter Notebook** - Análisis interactivo

### **🤖 Machine Learning**
- **Scikit-learn** - Algoritmos de clasificación
- **XGBoost** - Modelos avanzados
- **SMOTE** - Balanceo de datos
- **Random Forest** - Modelo principal

### **📊 Procesamiento de Datos**
- **Pandas** - Manipulación de datos
- **NumPy** - Cálculos numéricos
- **Matplotlib/Seaborn** - Visualizaciones

### **🔄 Control de Versiones**
- **Git** - Control de versiones
- **GitHub** - Colaboración en equipo

---

## 🚀 **Cómo Usar Este Proyecto**

### **Para Ejecutar el Demo Interactivo:**
```bash
# 1. Clonar el repositorio
git clone https://github.com/medinakevin/sistema-deteccion-fraudes-santander.git

# 2. Navegar al directorio
cd sistema-deteccion-fraudes-santander

# 3. Ejecutar el notebook principal
jupyter notebook notebooks/03_demo_interactivo.ipynb
Para Desarrolladores:
bash
# Instalar dependencias (próximamente)
pip install -r requirements.txt

# Ejecutar scripts específicos
python src/models/entrenamiento.py
📈 Metodología de Trabajo
🔬 Enfoque Multidisciplinario
Aprendizaje de Máquinas: Modelos predictivos para detección de patrones

Big Data: Arquitectura escalable para procesamiento en tiempo real

Operaciones: Optimización de recursos y procesos

Comunicación: Estrategias para gestión de crisis reputacional

🔄 Flujo de Desarrollo
Análisis Exploratorio - Entendimiento de datos

Preprocesamiento - Limpieza y transformación

Modelado - Entrenamiento de algoritmos

Validación - Evaluación de resultados

Implementación - Demo interactivo

Documentación - Reporte técnico y pitch

🎯 Entregables Principales
📋 Documentación
Reporte técnico completo

Pitch ejecutivo

Presentación final

Manual de usuario

💻 Demo Técnico
Sistema de detección en tiempo real

Modelo de ML entrenado

Visualizaciones interactivas

Análisis de resultados

📊 Métricas de Éxito
Recall > 85% - Detección efectiva de fraudes

Falsos positivos < 5% - Minimizar molestias a clientes

Tiempo respuesta < 3s - Procesamiento en tiempo real

Datasets:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
¿Qué son las columnas V1, V2, V3... V28?
PCA (Principal Component Analysis) Explicado Simple:
Imagina que tienes 100 características originales como:
-Ubicación de la transacción
-Hora del día
-Historial del cliente
-Tipo de comercio
-Dispositivo usado
-etc...
El PCA hace esto:
-Toma todas esas 100+ características originales
-Las combina matemáticamente
-Crea 28 nuevas características (V1-V28) que capturan la información más importante
-Mantiene la confidencialidad (no sabemos qué representa exactamente cada V)

https://www.kaggle.com/c/ieee-fraud-detection/data
Ventajas:
✅ Más reciente (2019 vs 2013)
✅ Características REALES (no anonimizadas con PCA)
✅ Datos de identidad (dispositivo, navegador, SO)
✅ Múltiples tipos de transacciones
✅ Competencia activa (más documentación)

https://fraud-detection-handbook.github.io/fraud-detection-handbook/Chapter_3_GettingStarted/SimulatedDataset.html
Ventajas:
✅ Datos sintéticos pero REALISTAS
✅ Explicación completa de cada variable
✅ Diseñado específicamente para detección de fraudes
✅ Incluye temporalidad y relaciones cliente-transacción

https://www.kaggle.com/datasets/ealaxi/paysim1
Ideal para: Demostrar capacidades de Big Data
✅ 6+ millones de transacciones
✅ Simula operaciones móviles (como app bancaria)
✅ Múltiples tipos: TRANSFER, CASH_IN, CASH_OUT, etc.
✅ Datos estructurados claros

📊 Comparativa Rápida
Dataset	              Ventajas                  	Desventajas	                  Recomendación
Kaggle Credit Card.   Simple, conocido, rápido.	  Datos anonimizados, antiguo.	Si quieren ir rápido
IEEE-CIS.	            Real, completo, reciente. 	Más complejo, más grande.	    Si quieren profundidad
Fraud Handbook.	      Bien documentado, realista. Sintético, menos volumen.	    Si quieren entender bien
PaySim.	              Gran volumen, móvil.      	Sintético, patrones simples.	Para demostrar Big Data
