# Talento Tech – Dashboard de Resultados Comerciales  
**Empresa ficticia:** Datawise Consulting

## Descripción del proyecto
Proyecto desarrollado en el marco del programa **Talento Tech**, orientado al
análisis de resultados comerciales y a la construcción de un dashboard
interactivo para apoyar la toma de decisiones.

El objetivo fue simular un escenario real de negocio, trabajando con múltiples
fuentes de datos, realizando un análisis exploratorio y presentando los
resultados de forma clara y visual mediante **Looker Studio**.

---

## Datos utilizados
El análisis se realizó a partir de un conjunto de tablas relacionadas,
representativas de un contexto comercial real:

- **ventas**: registros de transacciones, montos y fechas.
- **clientes**: información general y segmentación de clientes.
- **productos**: catálogo de productos.
- **categorias**: clasificación y jerarquía de productos.
- **metodos_pago**: medios de pago utilizados en las operaciones.

---

## Preparación y limpieza de datos
Previo al análisis, se llevó a cabo un proceso de revisión y depuración de los
datos, que incluyó:

- Validación de tipos de datos (fechas, montos y campos categóricos).
- Tratamiento de valores nulos y registros incompletos.
- Normalización de nombres y categorías para asegurar consistencia.
- Revisión de duplicados en tablas maestras.

Este proceso permitió trabajar con información confiable y consistente para el
análisis posterior.

---

## Integración y modelo de datos
Las tablas fueron integradas utilizando claves comunes, construyendo una vista
consolidada de la información:

- **ventas** como tabla central de hechos.
- Relación con **clientes**, **productos** y **metodos_pago** mediante
  identificadores.
- Vinculación de **productos** con **categorias** para análisis por jerarquía.

La integración de los datos permitió analizar los resultados desde múltiples
dimensiones de negocio.

---

## Análisis y métricas relevantes
A partir del modelo integrado se analizaron métricas clave, entre ellas:

- Ventas totales y su evolución en el tiempo.
- Distribución de ventas por categoría y producto.
- Comportamiento y segmentación de clientes.
- Participación de los distintos métodos de pago.
- Comparación de resultados entre distintos segmentos.

Los hallazgos se presentaron en un dashboard interactivo diseñado para facilitar
la exploración de la información y el seguimiento de indicadores.

---

## Storytelling y comunicación de resultados
Como parte del proyecto, se desarrolló una breve presentación en Google Slides
con el objetivo de comunicar los principales hallazgos del análisis a un
público no técnico.

La presentación se estructura en 4 slides, donde cada visualización es
acompañada por una interpretación clara del mensaje y sus implicancias para
el negocio.

🔗 **Presentación de resultados:**  
(https://docs.google.com/presentation/d/1H1sfvKairse23nyWkJ1Iy1GsVCxpJVRSdHsDNxQvOns/edit?slide=id.p#slide=id.p)

---

## Dashboard
El dashboard fue desarrollado en **Looker Studio** y permite interactuar con los
principales indicadores del negocio.

🔗 **Link al dashboard:**  
(https://lookerstudio.google.com/u/0/reporting/588d53dd-3bf4-43a7-92c2-f95b99ed1cc9/page/p_a33zxvdkud)

---

## Estructura del repositorio
```
├── data/
│   ├── categorias.csv
│   ├── clientes.csv
│   ├── metodos_pago.csv
│   ├── productos.csv
│   └── ventas.csv
├── visuals/
│   └── dashboard.png
└── README.md
```
