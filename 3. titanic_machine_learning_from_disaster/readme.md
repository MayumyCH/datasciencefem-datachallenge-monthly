<img src="https://i.ibb.co/DWSqtc1/Encabezado.png" alt="descargar" border="0" width=800px>

# **RETO: "Titanic - Machine Learning from Disaster"**

<img src="https://storage.googleapis.com/kaggle-competitions/kaggle/3136/logos/header.png" alt="descargar" border="0" height=200px>

## 🔥 **Reto**
> **¿Cuál es la tasa de supervivencia por GÉNERO, CLASE Y EMBARQUE?**
>
> **Extras:**
> - Análisis de las variables PADRESHIJOS y HERMESP.
> - ¿Cuál es la tasa de supervivencia en intervalos de EDAD Y PRECIO?

## 🔗 Link importantes
1. [Link del Reto (Kaggle)](https://www.kaggle.com/c/titanic/data)
2. [Solución del Reto (Notebook)](https://github.com/MayumyCH/datasciencefem-datachallenge-monthly/blob/main/titanic_machine_learning_from_disaster/titanic_machine_learning_from_disaster.ipynb)

```
#RetoFem
#datachallenge365fem
#ParSel
#Titanic - Machine Learning from Disaster
#RetoIII
```

## 🔎 **Comprensión del Negocio** 

El hundimiento del Titanic 🛳️ es uno de los naufragios más infames de la historia.

El 15 de abril de 1912, durante su viaje inaugural, el RMS Titanic, ampliamente considerado "insumergible", se hundió después de chocar con un iceberg. Desafortunadamente, no había suficientes botes salvavidas para todos a bordo, lo que resultó en la muerte de 1502 de los 2224 pasajeros y la tripulación.

Si bien hubo algún elemento de suerte involucrado en sobrevivir, parece que algunos grupos de personas tenían más probabilidades de sobrevivir que otros.

### 📌 **Datos**
Este proyecto la data nos entregan dividida en 2 grupos: 
- Conjunto de entrenamiento (train.csv)
- Conjunto de prueba (test.csv)

Pero para este reto usaremos solo el conjunto de entrenamiento (train.csv).
A continuacion se detalla las 12 variables que nos trae la data


|Variable|Variable Es| Definicion  | Llave |
|--|--|--|--|
| **PassengerId**|**IdPasajero**|	Id asignado a cada pasajero	|
| **Survived**|**Sobrevivio**|	Sobrevivencia	| 0 = No Sobrevivió, 1 = Sobrevivió
| **Pclass**|**Clase**|	La clase en la que estaba el pasajero	| 1 = Alto, 2 = Medio, 3 = Bajo
| **Name**|**Nombre**|	Nombre del pasajero	|
| **Sex**|**Genero**|	Genero del pasajero	|
| **Age**|**Edad**|	Edad del pasajero | 
| **SibSp**|**HermEsp**|	# de hermanos / cónyuges a bordo del Titanic	|
| **Parch**|**PadresHijos**|	# de padres / hijos a bordo del Titanic	|
| **Ticket**|**Tiquete**|	# del tiquete del pasajero	|
| **Fare**|**Precio**|	Precio del tiquete	|
| **Cabin**|**Cabina**|	Número de cabina en qué estaba ubicado el pasajero	|
| **Embarked**|**Embarque**|	Puerto de embarque (lugar) |	C = Cherburgo, Q = Queenstown, S = Southampton


---

