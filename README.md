Exercício com CSS Flexbox & Grid
Para la estructura principal de la página, use CSS Grid. Es cierto que la idea principal eran 3 columnas, pero por el tamaño dado de las imagenes, y por tanto de las cartoes, se podrucía un scroll horizontal. 
La solución para que fuese responsive fue reducir 20 px el tamaño de cartao e imagen en dispositivos menores de 768px (móbiles, tablets pequeñas...), y hacer una estructura de una sola columna. Para el resto de dispositivos el tamaño de la imagen es el acordado (460px), y la estructura presenta 2 columnas.
Relacionado también con el tamaño del cartao, he hecho 6 cartoes con descripciones y textos de diferentes tamaños, para que se pueda ver que se cumplen las medidas establecidas. Esto en el caso de las descripciones, lo he conseguido con un overflow:scroll.
Añadi también variables en CSS para que trabajar con los diferentes colores, tamaños... fuera más sencillo.
