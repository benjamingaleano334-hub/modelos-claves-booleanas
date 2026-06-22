
# Modelo de Claves Booleanas en Python

Este repositorio contiene una práctica de **búsquedas booleanas (AND, OR, NOT)** sobre dos conjuntos de documentos utilizando **NLTK**.  
El trabajo está dividido en **Consigna 1** y **Consigna 2**, cada una con su propio conjunto de documentos y ejemplos de consultas.

---

## 📂 Contenido
- `modelo_clave_booleana.ipynb`: notebook con la implementación paso a paso.
- `README.md`: este archivo con instrucciones y ejemplos.

---

## 🚀 Ejecución
1. Abrir Jupyter Notebook.
2. Cargar `BooleanSearch.ipynb`.
3. Ejecutar todas las celdas.
4. Ingresar consultas booleanas en la terminal/notebook.  
   Para salir, escribir `salir`.

---

## 📖 Consigna 1 – Inteligencia Artificial
Documentos relacionados con IA y aprendizaje automático.

### Ejemplos de consultas:
```text
Ingrese una consulta booleana (o 'salir' para terminar): inteligencia AND artificial
📄 Documentos encontrados: {'doc1', 'doc2'}

Ingrese una consulta booleana (o 'salir' para terminar): redes OR aprendizaje
📄 Documentos encontrados: {'doc2', 'doc3', 'doc4', 'doc5'}

Ingrese una consulta booleana (o 'salir' para terminar): inteligencia NOT automatico
📄 Documentos encontrados: {'doc1'}
```

---

## 📖 Consigna 2 – Civilizaciones Antiguas
Documentos relacionados con civilizaciones antiguas.

### Ejemplos de consultas:
```text
Ingrese una consulta booleana (o 'salir' para terminar): egipcios AND pirámides
📄 Documentos encontrados: {'doc1'}

Ingrese una consulta booleana (o 'salir' para terminar): escritura OR astrónomos
📄 Documentos encontrados: {'doc1', 'doc3', 'doc5'}

Ingrese una consulta booleana (o 'salir' para terminar): romano NOT griegos
📄 Documentos encontrados: {'doc2'}
```

---

## ✅ Notas
- Los operadores booleanos (`AND`, `OR`, `NOT`) pueden escribirse en mayúsculas, minúsculas o mezclados (`and`, `And`, `AND`).
- Las palabras con acento también se reconocen aunque se escriban sin acento (`piramides` = `pirámides`).
- El sistema utiliza un **índice invertido** para asociar cada palabra con los documentos en los que aparece.

---

## 🛠️ Tecnologías utilizadas
- Python 
- NLTK (tokenización)
- Jupyter Notebook
```

