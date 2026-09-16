# 1. Crea un archivo de texto llamado textos.txt:
## Ábrelo con un navegador. Cámbialo de nombre por textos.html. Vuélvelo a abrir con el navegador.
### ¿Qué conclusiones sacas de tu observación?

+ En el archivo con .txt enseña la información exactamente la he escrito, mientras que el .html reconoce que se han utilizado unas reglas de un lenguaje de marcas y adapta lo que he escrito para cumplir con sus normas.


# 2. Observa el siguiente fragmento de un texto:
```
<dam>
<modulo><titulo>Lenguaje de Marcas</titulo>
<contenido>
<unidad>Introducción</unidad>
<unidad>HTML</unidad>
<unidad>CSS</unidad>
…
</contenido>
</modulo>
…
</dam>
```
## Lo que vemos es una manera de estructurar la información sobre los módulos de DAM. Podemos distinguir:
### Vocabulario: dam, modulo, titulo, contenido, unidad
### Reglas: dam contiene varios modulos, un modulo tiene un titulo y un contenido, contenido tiene varias unidades, todas las unidades están en un contenido, las unidades son texto simple, detrás de una unidad solo puede ir otra unidad o fin contenido, detrás de uno modulo solo pu ede ir otro modulo o fin de dam
### Completa con al menos tres de los módulos de DAM en este archivo. Llámale DAM.sgml
```
<dam>
<modulo><titulo>Lenguaje de Marcas</titulo>
 <contenido>
  <unidad>Introducción</unidad>
  <unidad>HTML</unidad>
  <unidad>CSS</unidad>
 </contenido>
</modulo>
<modulo><titulo>Programacion</titulo>
 <contenido>
  <unidad>Condicionales y Bucles</unidad>
  <unidad>Estructuras de Datos</unidad>
  <unidad>Gestión de Excepciones</unidad>
 </contenido>
</modulo>
<modulo><titulo>Base de Datos</titulo>
 <contenido>
  <unidad>Modelo Relacional</unidad>
  <unidad>Paso a Tablas</unidad>
  <unidad>SQL</unidad>
 </contenido>
</modulo>
<modulo><titulo>Sistemas Informáticos</titulo>
 <contenido>
  <unidad>Elementos Funcionales de un ordenador</unidad>
  <unidad>Arquitectura de Von Neumann</unidad>
  <unidad>Ciclo de Instrucciones</unidad>
 </contenido>
</modulo>
</dam>
```

# 3. Crea tu propio documento SGML indicando vocabulario y reglas. Implementa los datos para PAISES DEL MUNDO.
+ Vocabulario: Paises-del-mundo, país, nombre, capital, continente, población
+ Reglas: Paises-del-mundo contiene varios paises, cada país tiene un nombre, una capital, un continente y un numero exacto de población todo en texto simple y con ese orden interno. Detrás de cada país solo puede ir otro país o fin de Paises-del-mundo.
```
<Paises-del-mundo>
 <país>
  <nombre>España</nombre>
  <capital>Madrid</capital>
  <continente>Europa</continente>
  <población>47450000</población>
 </país>
<país>
  <nombre>Japón</nombre>
  <capital>Tokio</capital>
  <continente>Asia</continente>
  <población>125700000</población>
 </país>
 <país>
  <nombre>Argentina</nombre>
  <capital>Buenos Aires</capital>
  <continente>América del sur</continente>
  <población>45810000</población>
 </país>
 <país>
  <nombre>Argelia</nombre>
  <capital>Argel</capital>
  <continente>África</continente>
  <población>46700000</población>
 </país>
</Paises-del-mundo>
```

# 4. Modifica con un lenguaje de marcas la siguiente información para darle estructura y significado semántico al documento. Indica vocabulario y reglas.
###### FALCO (En papel)
###### ISBN 9788420419688
###### ARTURO PEREZ REVERTE
###### 9788420419688
###### 296 págs
###### ALFAGUARA
###### CASTELLÀ
###### TODO ALATRISTE (EBOOK)
###### 9788420425528
###### ARTURO PEREZ REVERTE
###### ALFAGUARA
###### CASTELLÀ
###### HOMBRES BUENOS (En papel)
###### 9788466329804
###### ARTURO PEREZ REVERTE
###### PUNTO DE LECTURA, 2024
###### La heróica aventura de quienes se atrevieron a cambiar el mundo con libros. En tiempos de oscuridad siempre hubohombres buenos que lucharon para llevar las luces y el progreso. Y otros que procuraron impedirlo

+ Vocabulario: biblioteca, libro, titulo, formato, isbn, autor, editorial, idioma.
+ Reglas: La biblioteca contiene uno o mas libros, todo libro contiene obligatoriamente titulo, formato, isbn, autor, editorial e idioma en ese orden interno y todo esta escrito en texto simple.

```
<biblioteca>
  <libro>
    <titulo>Falcó</titulo>
    <formato>En papel</formato>
    <isbn>9788420419688</isbn>
    <autor>Arturo Pérez-Reverte</autor>
    <paginas>296</paginas>
    <editorial>Alfaguara</editorial>
    <idioma>Castellà</idioma>
  </libro>
  <libro>
    <titulo>Todo Alatriste</titulo>
    <formato>Ebook</formato>
    <isbn>9788420425528</isbn>
    <autor>Arturo Pérez-Reverte</autor>
    <paginas>296</paginas>
    <editorial>Alfaguara</editorial>
    <idioma>Castellà</idioma>
  </libro>
  <libro>
    <titulo>Hombres Buenos</titulo>
    <formato>En papel</formato>
    <isbn>9788466329804</isbn>
    <autor>Arturo Pérez-Reverte</autor>
    <paginas>296</paginas>
    <editorial>Punto de Lectura</editorial>
    <idioma></idioma> //no se dice cual es
  </libro>
</biblioteca>
```



### Adrián Martínez García








