# (CLOUD COMPUTING) ACTIVIDAD DE EVALUACIÓN

Cecilia Paláu

Juan Carlos Sala

Rodrigo López

Ricardo Vargas

Donnet Hernandez

Yuu Ricardo Akachi #Traidor

Pablo Monzon

## Instrucciones de Uso

### Paso 1: Clonar el Repositorio
```bash
git clone https://github.com/cecypd2/computo_en_la_nube_2.git
cd computo_en_la_nube
```

### Paso 2: Ejecución de los Notebooks:
1. **Carga de Datos, Limpieza y Entrenamiento del Modelo:** Corre `model.ipynb` para cargar los datos.
2. **Limpieza de Datos:** Se identificaron las columnas con valores nulos y se eliminaron. Posteriormente, se convierte la columna de fecha *ModifiedDate* a formato ordinal (*ModifiedDateOrdinal*). Así mismo, se eliminan columnas irrelevantes como *rowguid*, *PasswordHash* y *PasswordSalt*. Finalmente se codifican las variables categóricas usando LabelEncoder.
3. **Entrenamiento del Modelo:** Se separan las variables predictoras *x* y la variable objetivo (*y=ModifiedDateOrdinal*). Posteriormente se divide el dataset en entrenamiento y prueba con *train_test_split*. Finalmente se genera el modelo de Machine Learning (Random Forest) y los datos de prueba y se evalúa con el .score().
5. **Despliegue del Modelo:** Ejecuta `despliegue.ipynb` para preparar el modelo para producción.
6. **Uso de la API:** Ejecuta `API.ipynb` para hacer inferencias con el modelo entrenado. Sustituye el archivo de prueba según sea necesario.

### Especificaciones Mínimas
- **Sistema Operativo:** Windows, macOS o Linux.
- **RAM:** 4GB mínimo (8GB recomendado).
- **Ancho de Banda:** Conexión estable a Internet recomendada.

