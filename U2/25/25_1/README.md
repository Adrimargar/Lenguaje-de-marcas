# Base:
- Habrá un contenedor de 300px de ancho, y dentro 3 cuadrados en vertical a la izquierda.

# Static:
- No se moverá porque static deja por determinado su posición como un div que es.

# Relative:
- Tomando el 0,0 como su posición inicial despues del primer div, se alejará los 20px y luego se desplazará 50px de la izquierda

# Absolute:
- Primero, toma el 0,0 de la pantalla, entonces ser irá a la esquina derecha superior de la pantalla, al darle el relative a su padre, tomará como maximo lo que mida su padre, haciendo que se vaya simplemente al final del .contenedor.

# Z-index:
- Si le aplicas el Z-index en negativo, se pondra detras de cualquier objeto en default, ya que tiene el relative y una posición cambiada si que podriamos aplicarlo en el .c2
