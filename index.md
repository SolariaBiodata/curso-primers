![alt text](https://solariabiodata.com.mx/images/solaria_banner.png "Soluciones de Siguiente Generación")
# Curso de Diseño de Primers y Sondas - Sesión 1
## 1. Bases de datos: NCBI
### Descripción
En este ejercicio veremos cómo accesar a diferentes repositorios de NCBI, utilizando la interfaz gráfica de nuestro navegador.

### Requisitos

Para poder realizar este ejercicio, necesitaremos:
1. Ingresar a la página de NCBI: [https://www.ncbi.nlm.nih.gov/](https://www.ncbi.nlm.nih.gov/)
2. Dar click en `Resource List (A-Z)`
>  El paso anterior nos desplegó una lista de todos los repositorios en NCBI que están disponibles para su consulta.
3. Abrir la Base de datos `Nucleotide`
4. Teclear `Escherichia coli` en el campo de búsqueda

### 1.1 Búsqueda Avanzada

1. Dar click en ``Advanced``
2. En el Builder, seleccionar ``Organism`` en la primer pestaña
3. Realizar nuevamente la búsqueda de ``Escherichia coli``

###  1.2 Dirigir la búsqueda a una región (o gen) de interés

1. Teclear ``Escherichia coli[Organism] AND stx1``
> Esta sigue siendo una búsqueda muy general, vamos a hacerla más específica
2. Dar click en ``Advanced``
3. En el historial de búsquedas, aparecen las más recientes, dar click en add en el primer registro
4. En el Builder, seleccionar ``Organism`` en la primer pestaña
5. Seleccionar ``Gene name ``en la segunda pestaña y teclear `` stx1`` en su cuadro de diálogo
6. Realizar la búsqueda nuevamente
7. Por último, añadir a la búsqueda ``AND complete`` para que el término final sea ``(Escherichia coli[Organism]) AND stx1[Gene Name] AND complete``

#### Discusión
¿Cuantas secuencias resultaron al final de esta búsqueda específica?

## 2. Información de secuencias y descarga de archivos fasta

###  2.1 Visualización de Secuencia
1. En la búsqueda anterior, dar click en el primer registro ``Escherichia coli O157:H7 stx1 genes for shiga toxin 1 variant A subunit, shiga toxin 1 B subunit,complete cds, strain:AI2000/182 ``
> (No Acceso: ``AB083043.1``)

#### Discusión

¿Qué información relevante aparece? Ubica los siguientes datos:

- No. de Acceso
- Tamaño de la secuencia
- Organismo al que pertenece
- Autores
- Publicación relacionada
- Año de publicación o año de registro de la secuencia
- Regiones codificantes
- Además de la información ¿Qué otras herramientas aparecen en esta página?

### 2.2 Descarga de esta secuencia en formato fasta

1. Crea una carpeta en tu escritorio llamada ``Secuencias_NCBI``
2. Dar click en la pestaña Send to, se ubica en la parte superior derecha
3. Seleccionar la opción file
4. En la pestaña FORMAT, elegir la opción ``FASTA``
5. Dar click en ``Create file``
6. Guardar como ``AB083043.1.fasta``
7. Abrir el archivo con el programa Bloq de Notas o un editor de texto simple.

#### Discusión

- ¿Qué contiene el archivo descargado?
- ¿Es sencillo de visualizar?

### 2.3 Descarga de varias secuencias

1. Dar click en el botón de Regresar de tu navegador para volver a la búsqueda de NCBI
2. Dar click en la pestaña Send to, se ubica en la parte superior derecha
3. Seleccionar la opción file
4. En la pestaña FORMAT, elegir la opción FASTA
5. Dar click en Create file
6. Guardar como ``stx1_todas.fasta``
7. Abrir el archivo con el programa Bloq de Notas

#### Discusión

¿Qué contiene el archivo descargado?
¿Es sencillo de visualizar?


### 2.4 Edición de archivos multifasta

1. En el menú del Bloc de Notas, dar click en ``Edición`` y después ``Buscar``
2. En el cuadro de diálogo, colocar un símbolo de  ``>``
3. Dar Enter antes de cada ``>`` que encuentres
4. Editar los headers por nombres más sencillos (pero informativos)
5. Dar un enter (o salto de línea) para separar las secuencias nucleotídicas de los headers
6. Guarda el archivo editado ``(Ctrl+G)``

## 3. Herramienta de Alineamiento BLAST

1. De tu archivo ``stx1_todas.fasta``, copiar el No. de acceso de tu último registro ``AB012101.1``
2. Ingresar al NCBI, seleccionar la base de datos Nucleotide  y pegar el No. de Acceso en  el cuadro de diálogo
3. Ubicar los siguientes datos:
 - Publicación relacionada
 - Año de publicación o año de registro de la secuencia
4. En la parte superior izquierda, dar click en el link FASTA
5. Copiar en tu portapapeles el total de la secuencia
6. Ingresar en tu navegador a la página de BLAST https://blast.ncbi.nlm.nih.gov/Blast.cgi
7. Dar click en ``Nucleotide BLAST``
8. Pegar la secuencia en el cuadro de diálogo
9. Dar click en el botón BLAST (parte inferior de la página)

#### Discusión

- ¿Cuál es el primer Hit encontrado?
- ¿Con qué tipo de secuencias alínea nuestra búsqueda?

## 4. Ejercicio Final
En la base de datos PubMed del NCBI, busca el artículo con ID: ``PMC168144``, localiza los iniciadores llamados ``slt-I`` (diseñados para identificar la toxina Shiga-Like en _E. coli_ ) y realiza un BLAST para cada uno de ellos. Únicamente con los datos arrojados por BLAST, ¿Consideras confiables a estos iniciadores?
