<h2><center>Proyecto Final Machine Learning IELE4014<br> Jonathan Steven Roncancio Pinzón <br>Universidad de los Andes <br>201617312 </center></h2>

## Introducción: 
<div align="justify"> En la actualidad, muchos de los problemas de procesamiento de imágenes tienen como obstaculo subsecuente la transformación de imágenes a imágenes, o lo que es lo mismo, de píxeles a píxeles. Si bien es cierto que ya existen herramientas especializadas para la transformación de imágenes a nuevas imágenes, estas herramientas han sido creadas para fines específicos y con poco margen de uso con respecto a otro tipo de problemáticas. <br> 
 
Es aquí donde entra el modelo pix2pix publicado en el año 2016 por los 
investigadores de la universidad de Berkeley Phillip Isola, Jun-Yan Zhu, Tinghui Zhou y Alexei A. Efros [1]. En dicho paper, los autores proponen el uso de una red generativa adversarial condicional (cGAN) con la cual crear un modelo de propósito general para el problema de traducción de imagen a imagen. <br>

Con esto en mente, el objetivo de este proyecto es replicar los resultados obtenidos por los investigadores creando la red neuronal completa utilizando como única referencia la metodología y arquitectura especificada en la referencia [1] y la librería de libre acceso tensorflow. Además, en caso de tener el tiempo suficiente, se espera probar el modelo pix2pix en bases de datos diferentes a las utilizadas en el paper guía
