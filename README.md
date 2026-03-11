# Fundamentos de la Nube ☁️

Repositorio de apoyo para el curso **Fundamentos de la Nube**, desarrollado para Alura.

---

# Sobre el curso

Este curso presenta los **conceptos fundamentales de la computación en la nube** para científicos y científicas de datos, utilizando ejemplos prácticos con **datos reales del e-commerce brasileño**.

Durante el curso exploraremos las principales plataformas cloud del mercado. Sin embargo, el enfoque principal estará en **Google Cloud Platform (GCP)**.

---

# Contenido del curso

## Aula 1 — Introducción y datos

### Base de datos utilizada

- **[Olist Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)**  
  Conjunto de datos con aproximadamente **100 mil pedidos de la tienda Olist entre 2016 y 2018**.

### Datos complementarios

- **[Feriados nacionales de Brasil (JSON)](https://date.nager.at/api/v3/PublicHolidays/2016/BR)**

### Lecturas recomendadas

- **[¿Qué es la computación en la nube?](https://cloud.google.com/learn/what-is-cloud-computing?hl=es)**

- **[Modelos de servicios en la nube: PaaS vs IaaS vs SaaS](https://cloud.google.com/learn/paas-vs-iaas-vs-saas?hl=es)**

### Nota sobre Google Colab

Google Colab puede considerarse principalmente un **Software as a Service (SaaS)**, aunque algunas referencias lo describen como un **modelo híbrido entre SaaS y PaaS**.

- **[Google Colab para proyectos de datos](https://prof-frenzel.medium.com/kb-cloud-part-i-google-colab-for-data-projects-78fe3d079027)**

Se considera principalmente **SaaS**, porque ofrece un entorno listo para usar de **notebooks Jupyter directamente en el navegador**, sin necesidad de preocuparse por la infraestructura.

Sin embargo, también tiene características de **Platform as a Service (PaaS)**, ya que permite a los desarrolladores **crear y ejecutar su propio código** (modelos de machine learning, análisis de datos, entre otros) sobre una plataforma administrada por Google.

---

## Aula 2 — Primeros pasos en la nube

### Crear una cuenta gratuita en Google Cloud

- **[Google Cloud Free](https://cloud.google.com/free?hl=es)**

---

## Aula 3 — Almacenamiento de datos

### Documentación de los servicios utilizados

- **[Buckets en Google Cloud Storage](https://cloud.google.com/storage/docs/buckets?hl=es)**

- **[BigQuery](https://cloud.google.com/bigquery/docs?hl=es)**

---

## Aula 4 — Python y la nube

Notebook utilizado en la clase:

- **[`_Aula_4_Python_en_Nube`](https://github.com/YoannaHS/Alura_Fundamentos_Computacion_Nube/blob/main/_Aula_4_Python_en_Nube.ipynb)**

---

## Aula 5 — IAM y seguridad

Documentación recomendada:

- **[Principios de IAM](https://cloud.google.com/iam/docs/principals-overview?hl=es)**

- **[Cuentas de servicio](https://cloud.google.com/compute/docs/access/service-accounts?hl=es)**

- **[Permisos y roles de IAM](https://cloud.google.com/compute/docs/access/service-accounts?hl=es)**

---

# Estructura del repositorio

```
📓 _Aula_4_Python_en_Nube.ipynb
📁 datos_olist/
    ├── BR.json
    ├── olist_customers_dataset.csv
    ├── olist_geolocation_dataset.csv
    ├── olist_order_items_dataset.csv
    ├── olist_order_payments_dataset.csv
    ├── olist_order_reviews_dataset.csv
    ├── olist_orders_dataset.csv
    ├── olist_products_dataset.csv
    ├── olist_sellers_dataset.csv
    └── product_category_name_translation.csv
```

---

# Cómo usar este repositorio

1. Clona este repositorio.
2. Explora los notebooks y los datos dentro de la carpeta **`datos/`**.
3. Sigue las instrucciones de cada aula para acompañar el curso.