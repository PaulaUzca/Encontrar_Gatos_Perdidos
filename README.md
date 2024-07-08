![Banner Image](banner.jpg)

**Titulo:** Modelo de inteligencia artificial para encontrar gatos perdidos

**Autor:** Paula Uzcátegui León

**Objetivo**: Emparejar la imagen de un gato con imágenes de gatos muy similares

**Dataset**: el dataset que cree lo subí a kaggle, [mi dataset](https://www.kaggle.com/datasets/paulauzcategui/proyecto-ia-gaticos/data) contienen en total 1416 gatos diferentes. Son imágenes de tamaño (224,224,3) prerpocesadas con una red yolov8 para recortar la cata del gato. Las fuentes son un formulario, web scrapping de esta [página](https://www.petfinder.com/) y de un [dataset de kaggle](https://www.kaggle.com/datasets/aleksandrdremov/cat-faces-detection). Las imágenes están en formato de byte spor lo que deben ser convertidas a array.

**Modelos**: contrastive learning, siamese network, EfficientNetB2, YoloV8, TripletLoss

[Video en youtube](https://www.youtube.com/watch?v=cl8D7Brlm2E)

[best_yolo_faces.pt](best_yolo_faces.pt) - Pesos del modelo yolov8 para recortar imagenes de los gatos

[modelo_siames_best1.h5](modelo_siames_best1.h5) - Pesos del modelo siames para identificación de gatos

[modelo_mininghard.h5](modelo_mininghard.h5) - Pesos del modelo siames con fining tuning con los negativos más difíciles

[proyecto_gaticos_yolo.ipynb](proyecto_gaticos_yolo.ipynb) - Notebook con entrenamiento de red yolov8 para detectar caras de gatos

[proyecto_gaticos_procesamiento.ipynb(proyecto_gaticos_procesamiento.ipynb) - Notebook de preprocesamiento de los datos para crear el dataset

[proyecto_gatos_final.ipynb](proyecto_gatos_final.ipynb) - Notebook sobre construcción del modelo siamés para identificación de gatos





