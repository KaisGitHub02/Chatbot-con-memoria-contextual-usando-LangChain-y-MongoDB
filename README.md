# 🤖 Chatbot con Memoria Contextual

## 📚 Documentación del Proyecto

### 🎯 Objetivo

Crear un **chatbot con memoria contextual** que utiliza **LangChain** para el procesamiento de lenguaje natural y **MongoDB** para almacenar el historial de conversaciones.

---

### 🏗️ Arquitectura

1. **Config**: Gestión centralizada de configuraciones.
2. **MongoDBHandler**: Manejo de operaciones con la base de datos.
3. **ContextualChatbot**: Lógica principal del chatbot.
4. **Interfaz interactiva**: Modo demo para pruebas en consola o web.

---

### 🔧 Componentes Principales

- [LangChain](https://www.langchain.com/): Framework para aplicaciones con LLMs.
- [HuggingFace](https://huggingface.co/): Proveedor del modelo de lenguaje.
- [MongoDB](https://www.mongodb.com/): Base de datos NoSQL para persistencia.
- [PyMongo](https://pymongo.readthedocs.io/): Driver de Python para conectarse a MongoDB.

---

### 📝 Buenas Prácticas Implementadas

✅ Separación clara de responsabilidades  
✅ Configuración centralizada y reutilizable  
✅ Logging estructurado y detallado  
✅ Manejo robusto de errores  
✅ Documentación inline en el código  
✅ Estructura preparada para pruebas automatizadas  
✅ Código limpio, modular y legible  

---

### 🚀 Funcionalidades

- 📌 **Memoria contextual persistente** por usuario
- 👥 Soporte para **múltiples usuarios simultáneos**
- 📈 Estadísticas de uso por usuario
- 🔄 Gestión de sesiones por fecha
- 🛠️ Recuperación ante fallos y modo simulado

---

### 🧪 Ejemplo de Conversación

![Demo del Chatbot](assets/chat_demo.PNG)

![Demo del Chatbot2](assets/chat_demo2.PNG)

![Demo del Chatbot3](assets/chat_demo3.PNG)

![Demo del Chatbot4](assets/chat_demo4.PNG)

![Demo del Chatbot5](assets/chat_demo5.PNG)

![Demo del Chatbot6](assets/chat_demo6.PNG)

---

### 🔍 Testing

- ✅ Pruebas de conexión a MongoDB y HuggingFace
- ✅ Pruebas unitarias para componentes clave
- ✅ Validación de configuración antes de ejecutar
- ✅ Pruebas de integración entre módulos

---

### 📊 Métricas y Monitoring

- 🪵 Logging estructurado con timestamps y niveles
- 📊 Estadísticas por usuario (`total_conversations`, `last_interaction`)
- 🧪 Tracking de errores y excepciones
- ⏱️ Métricas de rendimiento observables por logs

---

### 📁 Estructura Recomendada
project/
├── config.py
├── mongodb_handler.py
├── chatbot.py
├── app.py
├── requirements.txt
└── README.md


---

### ✅ Requisitos

```bash
pip install langchain pymongo langchain-community langchain-huggingface
