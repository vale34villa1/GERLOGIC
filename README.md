# 🚛 GERLOGIC
## Agente Inteligente para la Gestión Eficiente de Inventarios en Empresas Logísticas

> **"La inteligencia artificial que centraliza el conocimiento logístico de tu empresa."**

GERLOGIC es un agente inteligente basado en Inteligencia Artificial Generativa y la técnica **Retrieval-Augmented Generation (RAG)**, diseñado para asistir a los colaboradores de empresas logísticas en la consulta de información corporativa almacenada en diversos documentos internos.

El agente responde preguntas en lenguaje natural sobre procesos logísticos, gestión de inventarios, transporte, almacenes, recursos humanos, calidad, seguridad y tecnología, utilizando como fuente de conocimiento documentos empresariales en diferentes formatos.

---

# 📌 Objetivo

Desarrollar un asistente inteligente capaz de responder consultas de los colaboradores de una empresa logística utilizando documentación corporativa como fuente de información, mejorando el acceso al conocimiento, reduciendo tiempos de búsqueda y optimizando la toma de decisiones operativas.

---

# 🚀 Problema

En las empresas logísticas, la información suele encontrarse distribuida entre manuales, políticas, procedimientos operativos, reportes, hojas de cálculo y documentos técnicos, dificultando su acceso y consulta.

GERLOGIC centraliza toda esta información mediante Inteligencia Artificial, permitiendo que cualquier colaborador consulte información de forma rápida, precisa y contextual.

---

# 💡 Solución

GERLOGIC implementa una arquitectura basada en **RAG (Retrieval-Augmented Generation)**, donde el agente consulta documentos internos antes de generar una respuesta.

La solución permite:

- Consultar información mediante lenguaje natural.
- Buscar información en múltiples documentos simultáneamente.
- Comprender distintos formatos de archivos.
- Centralizar el conocimiento empresarial.
- Reducir tiempos de búsqueda de información.
- Mejorar la productividad del personal.

---

# 📂 Áreas de conocimiento

El agente puede responder preguntas relacionadas con:

## 📦 Gestión de Inventarios

- Inventarios físicos
- Inventarios digitales
- Inventarios temporales
- Inventarios en tránsito
- Conteos cíclicos
- Ajustes de inventario
- FIFO
- FEFO
- Control de stock
- Trazabilidad

---

## 🚚 Operaciones Logísticas

- Recepción de mercancías
- Picking
- Packing
- Cross Docking
- Despacho
- Distribución
- Última milla
- Gestión de almacenes

---

## 🚛 Transporte

- Gestión de rutas
- Asignación de vehículos
- GPS
- Incidentes
- Entregas
- Transporte terrestre

---

## 👷 Recursos Humanos

- Manual del colaborador
- Onboarding
- Reglamento interno
- Vacaciones
- Beneficios
- Código de ética

---

## 📊 Calidad

- ISO 9001
- KPIs Logísticos
- OTIF
- Exactitud del inventario
- Auditorías

---

## 💻 Tecnología

- ERP
- WMS
- TMS
- Sistemas internos

---

## 💰 Finanzas

- Viáticos
- Gastos
- Facturación
- Reembolsos

---

## ☎ Atención al Cliente

- Reclamos
- Devoluciones
- Garantías
- Preguntas frecuentes

---

# 📄 Formatos de documentos soportados

GERLOGIC puede consultar información proveniente de:

- PDF
- Word (.docx)
- Excel (.xlsx)
- CSV
- JSON
- HTML
- Markdown (.md)
- PowerPoint (.pptx)

---

# 🏗 Arquitectura de la solución

```
                        Usuario

                           │
                           ▼

               Interfaz Web (Streamlit)

                           │
                           ▼

               Agente Inteligente (LangChain)

                           │
                           ▼

            Oracle Cloud Infrastructure (OCI)

                           │
                           ▼

               Modelo Generativo (LLM OCI)

                           │
                           ▼

                 Embeddings de documentos

                           │
                           ▼

                  Base Vectorial (FAISS)

                           │
                           ▼

             Documentación Corporativa

 PDF | Word | Excel | CSV | HTML | JSON | Markdown
```

---

# 🛠 Tecnologías utilizadas

| Tecnología | Descripción |
|------------|-------------|
| Python | Lenguaje principal |
| Streamlit | Interfaz Web |
| LangChain | Framework para IA |
| Oracle Cloud Infrastructure (OCI) | Infraestructura Cloud |
| OCI Generative AI | Modelo de lenguaje |
| FAISS | Base de datos vectorial |
| Pandas | Procesamiento de datos |
| PyPDF | Lectura de PDF |
| python-docx | Lectura de Word |
| OpenPyXL | Lectura de Excel |
| BeautifulSoup | Lectura de HTML |
| GitHub | Control de versiones |

---

# 📁 Estructura del proyecto

```
GERLOGIC/

│
├── app.py
├── config.py
├── requirements.txt
├── README.md
├── .gitignore
├── .env
│
├── data/
│   ├── pdf/
│   ├── excel/
│   ├── csv/
│   ├── word/
│   ├── json/
│   ├── html/
│   ├── markdown/
│   └── ppt/
│
├── loaders/
│   ├── pdf_loader.py
│   ├── excel_loader.py
│   ├── csv_loader.py
│   ├── word_loader.py
│   ├── json_loader.py
│   └── html_loader.py
│
├── embeddings/
│
├── vectorstore/
│
├── prompts/
│
├── screenshots/
│
└── docs/
```

---

# 📚 Documentación utilizada

- Manual de Gestión de Inventarios
- Procedimiento de Recepción de Mercancías
- Procedimiento de Picking
- Procedimiento de Packing
- Manual de Transporte
- Manual WMS
- Manual ERP
- Manual TMS
- Reglamento Interno
- Política de Reclamos
- Política de Reembolsos
- Indicadores Logísticos
- Tarifario de Servicios
- FAQ Corporativo

---

# ❓ Ejemplos de preguntas

## Inventarios

- ¿Cómo registrar un inventario temporal?
- ¿Cuál es el procedimiento para realizar un conteo cíclico?
- ¿Qué significa FEFO?
- ¿Cómo se realiza un ajuste de inventario?
- ¿Cómo registrar un producto dañado?

## Operaciones

- ¿Cuál es el procedimiento de Picking?
- ¿Cómo registrar una recepción de mercancía?
- ¿Qué es Cross Docking?

## Transporte

- ¿Cómo reportar un retraso?
- ¿Cuál es el procedimiento ante una avería?

## Calidad

- ¿Qué significa OTIF?
- ¿Cuál es la meta de exactitud del inventario?

## Recursos Humanos

- ¿Cómo solicito vacaciones?
- ¿Cuál es el horario del almacén?

---

# 🤖 Ejemplos de respuestas

### Pregunta

> ¿Qué es un inventario temporal?

**Respuesta**

Un inventario temporal corresponde al registro provisional de mercancías almacenadas durante procesos de recepción, consolidación, cross-docking o inspección. Estos productos permanecen en ubicaciones temporales hasta ser validados y trasladados a su ubicación definitiva dentro del almacén mediante el sistema WMS.

---

### Pregunta

> ¿Qué significa FEFO?

**Respuesta**

FEFO (First Expired, First Out) es un método de gestión de inventarios que prioriza la salida de los productos con la fecha de vencimiento más próxima, reduciendo pérdidas por caducidad y garantizando la rotación adecuada del inventario.

---

### Pregunta

> ¿Cómo registrar una recepción de mercancía?

**Respuesta**

El colaborador debe verificar la orden de compra, inspeccionar físicamente la mercancía, registrar la recepción en el sistema WMS, generar el comprobante correspondiente y asignar la ubicación de almacenamiento según las políticas establecidas.

---

# ▶ Instalación

## Clonar el repositorio

```bash
git clone https://github.com/usuario/GERLOGIC.git
```

## Ingresar al proyecto

```bash
cd GERLOGIC
```

## Crear entorno virtual

```bash
python -m venv venv
```

## Activar entorno virtual

Windows

```bash
venv\Scripts\activate
```

Linux / MacOS

```bash
source venv/bin/activate
```

## Instalar dependencias

```bash
pip install -r requirements.txt
```

## Ejecutar la aplicación

```bash
streamlit run app.py
```

---

# ☁ Despliegue en Oracle Cloud Infrastructure (OCI)

GERLOGIC fue desplegado utilizando **Oracle Cloud Infrastructure (OCI)**, aprovechando servicios de computación en la nube y modelos de IA Generativa para ofrecer respuestas rápidas y contextualizadas.

**Evidencias del despliegue:**

- URL pública de la aplicación *(agregar enlace una vez desplegado)*.
- Captura de pantalla de la aplicación en ejecución *(agregar imagen en `/screenshots`)*.
- Evidencia del agente respondiendo consultas basadas en la documentación cargada.

---

# 📈 Resultados esperados

- Centralización del conocimiento organizacional.
- Reducción del tiempo de búsqueda de información.
- Mayor eficiencia en la gestión de inventarios.
- Respuestas consistentes y contextualizadas.
- Mejora en la productividad de los colaboradores.

---

# 📌 Cumplimiento del Challenge Alura Agentes

| Requisito | Estado |
|-----------|:------:|
| Repositorio público en GitHub | ✅ |
| Historial de commits | ✅ |
| README completo | ✅ |
| Arquitectura documentada | ✅ |
| Agente Inteligente funcional | ✅ |
| Lectura de documentos PDF y CSV | ✅ |
| Procesamiento de múltiples formatos | ✅ |
| Uso de Oracle Cloud Infrastructure (OCI) | ✅ |
| Evidencia del despliegue | ✅ |

---

# 👨‍💻 Autor

**Valeria Villacorta**  
Bachiller en Ingeniería Industrial | Analítica de Datos | Inteligencia Artificial | Optimización de Procesos Logísticos

Proyecto desarrollado como parte del **Challenge Alura Agentes**, aplicando Inteligencia Artificial Generativa, RAG y Oracle Cloud Infrastructure para resolver un problema real en el sector logístico.
