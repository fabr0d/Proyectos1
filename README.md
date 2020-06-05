# Proyectos 1

## Implementacion de 3D-R2N2 y Pix2Vox

### Datasets

Ambos metodos utilizan modelos de Shapenet : 

* Imagenes renderizadas: http://cvgl.stanford.edu/data2/ShapeNetRendering.tgz
* Modelos voxelizados: http://cvgl.stanford.edu/data2/ShapeNetVox32.tgz

Pix2Vox tambien utiliza imagenes y modelos voxelizados de Pix3D : http://pix3d.csail.mit.edu/data/pix3d.zip

3D-R2N2 utiliza los pesos del modelo preentrenado ResidualGRUNet : http://cvgl.stanford.edu/data2/ResidualGRUNet.npy

### Requerimientos

#### 3D-R2N2

1. python 3
2. conda: es un sistema de gestión de paquetes de código abierto y un sistema de gestión del entorno.
3. numpy: biblioteca de python que agrega soporte para matrices y matrices multidimensionales grandes, junto con una gran colección de funciones matemáticas de alto nivel para operar en estas matrices.
4. Theano>=0.8: biblioteca de python que permite definir, optimizar y evaluar expresiones matemáticas que involucran matrices multidimensionales de manera eficiente.
5. easydict: permite acceder a los valores del diccionario como atributos para los diccionarios de python.
6. Pillow: libreria de imagenes de python con soporte para abrir, manipular y guardar muchos formatos de archivo de imagen diferentes.
7. pyyaml: es un analizador y emisor de YAML para python, aplicable para una amplia gama de tareas, desde archivos de configuración complejos hasta serialización y persistencia de objetos.
8. sklearn: es una biblioteca de machine learning de software libre para el lenguaje de programación Python. 

#### Pix2Vox

1. python 
2. argparse: facilita la escritura de interfaces de línea de comando fáciles de usar, genera automáticamente mensajes de ayuda y de uso y emite errores cuando los usuarios dan al programa argumentos no válidos.
3. easydict
4. matplotlib: libreria de plotting para python
5. numpy
6. opencv-python: es un contenedor de python para la implementación original de OpenCV C ++.
7. pprint: proporciona la capacidad de una impresion amigable de estructuras arbitrarias de datos de python en una forma que puede ser utilizada como entrada para el intérprete.
8. scipy: proporciona muchas rutinas numéricas fáciles de usar y eficientes, como rutinas para integración numérica, interpolación, optimización, álgebra lineal y estadísticas.
9. pytorch: libreria de machine learning de codigo abierto.
9. torchvision: paquete que consta de conjuntos de datos populares, arquitecturas de modelos y transformaciones de imágenes comunes para en visión por computadora.
10. tensorboardX: permite una interfaz simple para registrar eventos dentro de PyTorch.