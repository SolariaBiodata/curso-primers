![alt text](https://solariabiodata.com.mx/images/solaria_banner.png "Soluciones de Siguiente Generación")
# Curso de Diseño de Primers y Sondas - Sesión 1
## 1. Diseño con Primer 3

### Preparación

#### NCBI

1. Ingresar al NCBI: https://www.ncbi.nlm.nih.gov/
2. Base de datos Nucleotide
3. Teclear ``Cycas necrotic stunt virus RNA 2``
4. Dar click en el número de acceso ``NC_003792.2``
5. Copiar la secuencia completa

#### Primer 3

1. Ingresar a Primer3 http://bioinfo.ut.ee/primer3-0.4.0/
2. Pegar la secuencia copiada anteriormente en el cuadro del programa


### 1.1 Diseño de Punto Final
1. Dar click en Pick primers
2. Resultado: Producto de ``188pb``
3. Discutir valores de ``Any y 3´``

### 1.1.1 Ajuste de Parámetros
1. Ajustar los siguientes parámetros
2. Seleccionar ``58, 60 y 63 °C (Min, Opt, Max) en Primer Tm``
3. Seleccionar ``45, 50 y 55 (Min, Opt, Max) para el Primer GC%``
4. Colocar ``dos (2)`` para Max self Complementarity y ``cero (0)`` para Max 3´self complementarity
5. Colocar `Max poly X en ``tres (3)``
6. Resultado: Producto de 541pb
7. Discutir valores de Any y 3´

### 1.1.2 Ajuste de Parámetros (Pt. 2)
1. Ajustar los siguientes parámetros
2. Seleccionar ``58, 60 y 60 °C (Min, Opt, Max) en Primer Tm``
3. Seleccionar ``45, 50 y 55 (Min, Opt, Max) para el Primer GC%``
4. Colocar ``dos (2)`` para Max self Complementarity y ``cero (0)`` para Max 3´self complementarity
5. Colocar Max poly X en ``tres (3)``
6. Resultado: Producto de 996pb
7. Discutir valores de Any y 3´

### 1.1.3 Ajuste de Parámetros (Pt. 3)
1. Ajustar los siguientes parámetros
2. Seleccionar ``59, 60 y 60 °C (Min, Opt, Max) en Primer Tm``
3. Seleccionar ``45, 50 y 55 (Min, Opt, Max) para el Primer GC%``
4. Colocar ``dos (2)`` para Max self Complementarity y ``cero (0)`` para Max 3´self complementarity
5. Colocar Max poly X en ``tres (3)``
6. Resultado: No se generan Primers
7. Discutir valores de Any y 3´

### 1.2 PCR cuantitativa (sin sondas)

### 1.2.1
1. Ajustar los siguientes parámetros
2. Colocar en Product Size Ranges ``80-120``
3. Seleccionar ``57, 60 y 60 °C (Min, Opt, Max) en Primer Tm``
4. Seleccionar ``45, 50 y 55 (Min, Opt, Max) para el Primer GC%``
5. Colocar ``tres (3)`` para Max self Complementarity y ``cero (0)`` para Max 3´self complementarity
6. Colocar Max poly X en ``tres (3)``
7. Resultado: Producto de 99pb
8. Discutir valores de Any y 3´

### 1.2.2
1. Ajustar los siguientes parámetros
2. Colocar en Product Size Ranges ``80-120``
3. Seleccionar ``57, 60 y 63 °C (Min, Opt, Max) en Primer Tm``
4. Seleccionar ``45, 50 y 55 (Min, Opt, Max) para el Primer GC%``
5. Colocar ``tres (3)`` para Max self Complementarity y ``cero (0)`` para Max 3´self complementarity
6. Colocar Max poly X en ``tres (3)``
7. Resultado: Producto de 115pb
8. Discutir valores de Any y 3´

### 1.2.3
1. Ajustar los siguientes parámetros
2. Colocar en Product Size Ranges ``80-120``
3. Seleccionar ``57, 60 y 63 °C (Min, Opt, Max) en Primer Tm``
4. Seleccionar ``45, 50 y 55 (Min, Opt, Max) para el Primer GC%``
5. Colocar ``dos (2)`` para Max self Complementarity y ``cero (0)`` para Max 3´self complementarity
6. Colocar Max poly X en ``tres (3)``
7. Resultado: No se generan primers
8. Discutir valores de Any y 3´

### 1.3 PCR Tiempo Real (con sondas)

### 1.3.1 Ejercicio 1
1. Ajustar los siguientes parámetros
2. Marcar el cuadro Pick hybridization probe (internal oligo), or use below y mantener las mismas condiciones del ejercicio 2 (PCR tiempo real sin sondas)
3. Colocar en Product Size Ranges ``80-120``
4. Seleccionar ``57, 60 y 63 °C (Min, Opt, Max) en Primer Tm``
5. Seleccionar ``45, 50 y 55 (Min, Opt, Max) para el Primer GC%``
6. Colocar ``tres (3)`` para Max self Complementarity y ``cero (0)`` para Max 3´self complementarity
7. Colocar Max poly X en ``tres (3)``
8. Dirigirse a ``Hyb Oligo (Internal Oligo) General conditions``
9. Seleccionar ``67, 70 y 73 °C (Min, Opt, Max) en Hyb Oligo Tm``
10. Ajustar Hyb Oligo Max poly-X a un valor ``menor a 5 (4)``
11. Ajustar el Hyb Oligo Self Complementarity y Max 3´Self Complementarity a ``doce (12)``
12. Resultado: Producto de 115pb
13. Discutir valores de Any y 3´

### 1.3.2 Ejercicio 2
1. Ajustar los siguientes parámetros
2. Marcar el cuadro Pick hybridization probe (internal oligo), or use below y mantener las mismas condiciones del ejercicio 2 (PCR tiempo real sin sondas)
3. Dirigirse a ``Hyb Oligo (Internal Oligo) General conditions``
4. Seleccionar ``67, 70 y 73 °C (Min, Opt, Max) en Hyb Oligo``
5. Ajustar Hyb Oligo Max poly-X a un valor ``menor a 5 (4)``
6. Ajustar el Hyb Oligo Self Complementarity a ``cinco (5)`` y Max 3´Self Complementarity a ``cero (0)``
7. Resultado: Producto de 99pb
8. Discutir valores de Any y 3

### 1.3.3 Ejercicio 3
1. Ajustar los siguientes parámetros
2. Marcar el cuadro Pick hybridization probe (internal oligo), or use below y mantener las mismas condiciones del ejercicio 2 (PCR tiempo real sin sondas)
3. Dirigirse a ``Hyb Oligo (Internal Oligo) General conditions``
4. Seleccionar ``67, 70 y 73 °C (Min, Opt, Max) en Hyb Oligo``
5. Ajustar Hyb Oligo Max poly-X a un valor ``menor a 5 (4)``
6. Ajustar el Hyb Oligo Self Complementarity a ``tres (3)`` y Max 3´Self Complementarity a ``cero (0)``
7. Resultado: Producto de 99pb
8. Discutir valores de Any y 3

## 2. Bases de datos: NCBI
### Descripción
En este ejercicio veremos cómo accesar a diferentes repositorios de NCBI, utilizando la interfaz gráfica de nuestro navegador.

### Requisitos

Para poder realizar este ejercicio, necesitaremos:
1. Ingresar a la página de NCBI: [https://www.ncbi.nlm.nih.gov/](https://www.ncbi.nlm.nih.gov/)
2. Dar click en `Resource List (A-Z)`
>  El paso anterior nos desplegó una lista de todos los repositorios en NCBI que están disponibles para su consulta.
3. Abrir la Base de datos `Nucleotide`
4. Teclear `Escherichia coli` en el campo de búsqueda

### Ejercicio 1
### 2.1 Búsqueda Avanzada

1. Dar click en ``Advanced``
2. En el Builder, seleccionar ``Organism`` en la primer pestaña
3. Realizar nuevamente la búsqueda de ``Escherichia coli``

###  2.2 Dirigir la búsqueda a una región (o gen) de interés

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

### 2.3 Descarga de secuencias
1. Dar click en ``send to`` 
2. Dar click en ``File`` --> ``Format`` --> ``FASTA``  --> ``Create file``
3. Guardar las secuencias en tu computadora

>Ya tienes tu propia base de datos

## 3. Información de secuencias y descarga de archivos fasta

###  3.1 Búsqueda de secuencias específicas - BLAST
1. En la base de datos nucleotide buscar ``SARS-COV-2 AND S AND complete`` 
> ¿Qué secuencias aparecen?

2. Acceder al primer registro y buscar la ``proteína "S"``
3. Dar click en la palabra ``gene`` al lado de la secuencia de la proteína
4. En la parte inferior, dar click en ``Display FASTA``
5. Copiar la secuencia
6. Ingresar a BLAST
7. Pegar la secuencia y en la parte inferior dar click en ``BLAST``

#### Discusión
>¿Qué resultados aparecen?

### 3.2 Descarga de secuencias (hits) desde BLAST
1. Selecciona (tick) 5 secuencias de tu interés
2. Da click en ``Download`` --> ``FASTA (aligned sequences)``
3. Guarda las secuencias en tu computadora

>Ya tienes otra base de datos ;)


## 4. BLAST a primers y sondas

1. Del archivo del protocolo de Berlín copia la secuencia de la sonda confirmatoria para SARS-COV-2
2. Ingresa a BLAST, pega la secuencia y da click en ``BLAST``

#### Discusión
>¿Qué hits aparecen?
>¿Qué valor de E-value aparecen?



## 5. Evaluación de Primers

### Parte 1

#### NCBI
1. Abrir el árticulo: ``Sánchez-Navarro JA, Aparicio F, Herranz MC, Minafra A, Myrta A, Pallás V (2005) Simultaneus detection and identification of eight Stone fruit viruses by one-step RT-PCR. European Journal of Plant Pathology 111:77-84.``
2. Ingresar al NCBI: https://www.ncbi.nlm.nih.gov/
3. Base de datos Nucleotide

### 5.1 Ejercicio 1
1. Teclear el número de acceso ``U15608``
2. Copiar la secuencia completa
3. Ingresar a Pimer3 http://bioinfo.ut.ee/primer3-0.4.0/
4. Pegar la secuencia copiada anteriormente en el cuadro del programa
5. Seleccionar la casilla Pick left primer, or use left primer below y colocar los primers del artículo para el virus ApMV
6. Dar click en Pick primers y discutir el resultado.
7. Con lo que has aprendido hasta ahora, intenta mejorar los parámetros obtenidos.

### 5.2 Ejercicio 2
1. Teclear el número de acceso ``NC003453``
2. Copiar la secuencia completa
3. Ingresar a Pimer3 http://bioinfo.ut.ee/primer3-0.4.0/
4. Pegar la secuencia copiada anteriormente en el cuadro del programa
5. Seleccionar la casilla Pick left primer, or use left primer below y colocar los primers del artículo para el virus APLPV
6. Dar click en Pick primers y discutir el resultado.
7. Con lo que has aprendido hasta ahora, intenta mejorar los parámetros obtenidos.
