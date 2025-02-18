# P_CD_Guia_2
Desarrollo de la Guía 2 para la Materia de Programación para Ciencia de Datos de la Maestría en Ciencia de Datos  - Universidad EAN
Grupo de Trabajo [Grupos Guía 2 2] conformado por: 

* DAVID STEVEN LINARES DIAZ
* EDWIN FERLEY SANCHEZ BUSTOS
* JAVIER ORLANDO RODRIGUEZ PINZON
* JUAN DIEGO MARIN HERRERA

## Objetivo de la Guía
Aplicación de los conceptos de la librería Pandas en la manipulación y análisis de datos estructurados. Se trabajará con Series y DataFrames, aplicando técnicas de acceso, selección, filtrado y agregación de datos.

## Navegación sobre el Notebook [Grupo2_Guia_2]
El notebook se encuentra Dividido de la Siguiente Forma: 
### **Sección0**: *Entendimiento del Set de Datos [telecom_churn]*
Se presenta el Contexto del Set de Datos y su contenido.

### **Sección1**: *Exploración y Limpieza de Datos*
En esta sección de cargará el Set de Datos por medio de la librería Pandas  y su función[***read_csv***] y se realizará un análisis exploratorio del Set de Datos [***telecom_churn.csv***] esta dado por:

1. Visualización de la conformación del Set de Datos 
2. Obtención de Cantidad de Registros y Variables que contiene el Set
2. Entendimiento de las columnas y su respectivo tipo de Dato
4. Verificación de valores ausentes en el Set

### **Sección2**: *Análisis de Churn y Factores Relacionados*
En esta sección presentarán los cálculos de la deserción (churn = 1) sobre el total de la poblacion en el Set y se revisará si el Tener Plan Internacional [international plan] o Plan de Mensajes de Voz [voice mail plan] puede llegar a ser un factor discriminante en la deserción. 

### **Sección3:** *Análisis de la Duración del Servicio y Deserción*
En esta sección presentarán la relación promedio de la cuenta (account length) entre clientes que desertaron. 

### **Sección4:** *Relación entre Deserción y Uso del Servicio*
En esta sección presentarán la comparación del uso del Servicio (en minutos y llamadas) en diferentes franjar horarias y total versus la deserción.

### **Sección5:** *Impacto de las Llamadas al Servicio al Cliente en la Deserción*

En esta sección presenta como deserción puede ir relacionada con las llamadas al servicio al cliente (customer service calls) validado entre dos grupos. 
- Grupo 1: Clientes que llamaron más de 3 veces al servicio al cliente.
- Grupo 2: Clientes que llamaron 3 veces o menos.
### **Sección6:** *Análisis del Costo de las Llamadas y Churn*

En esta sección presentarán la comparación del servicio separado en dos franjas  horarias (diurno, nocturno)  versus la deserción.

 
