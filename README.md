# Filogenomica
## Analsis de los arboles obtenidos se encuentran al final del repositorio.



Árbol de OG000000
![imagen 1](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG000000.mafft.fas.treefile.png)

Árbol de OG000001

![imagen 2](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000001.mafft.fas.treefile.png)

Árbol de OG000002
![imagen 3](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000002.mafft.fas.treefile.png)

Árbol de OG000003

![imagen 4](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000003.mafft.fas.treefile.png)

Árbol de OG000004

![imagen 5](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000004.mafft.fas.treefile.png)

Árbol de OG000005
![imagen 6](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000005.mafft.fas.treefile.png)

Árbol de OG000006
![imagen 7](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000006.mafft.fas.treefile.png)

Árbol de OG000007
![imagen 8](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000007.mafft.fas.treefile.png)

Árbol de OG000008
![imagen 9](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000008.mafft.fas.treefile.png)

Árbol de OG000009
![imagen 10](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000009.mafft.fas.treefile.png)

Árbol de OG000010
![imagen 11](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000010.mafft.fas.treefile.png)

Árbol de OG000011
![imagen 12](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000011.mafft.fas.treefile.png)

Árbol de OG000012
![imagen 13](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000012.mafft.fas.treefile.png)

Árbol de OG000013
![imagen 14](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000013.mafft.fas.treefile.png)

Árbol de OG000014
![imagen 15](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000014.mafft.fas.treefile.png)

Árbol de OG000015
![imagen 16](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000015.mafft.fas.treefile.png)

Árbol de OG000016
![imagen 17](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000016.mafft.fas.treefile.png)

Árbol de OG000017
![imagen 18](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000017.mafft.fas.treefile.png)

Árbol de OG000018
![imagen 19](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000018.mafft.fas.treefile.png)

Árbol de OG000019
![imagen 20](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000019.mafft.fas.treefile.png)

Árbol de OG000020
![imagen 21](https://github.com/SofiaChavesR/Filogen-mica/blob/main/OG0000020.mafft.fas.treefile.png)

En el caso de los árboles de genes individuales OG000000- OG0000020 muestran topologías diferentes, especialmente en las posiciones relativas de grupos como _Homo sapiens_, _Mus musculus_, _Danio rerio_ y _Callithrix jacchus_, esto indica discordancia génica, probablemente por procesos como ILS (incomplete lineage sorting) o recombinación.Además, elgunos árboles conservan la monofilia de los primates (_Homo sapiens_, _Callithrix jacchus_), pero en otros esta agrupación se rompe, como bien se puede apreciar en OG0000004, _Homo sapiens_ aparece separado de otros primates, indicando parafilia para ese clado. 

Los valores en los nodos (posterior probabilities) son muy bajos en ramas internas profundas, lo que indica bajo soporte filogenético en esas divisiones, lo que refleja poca señal filogenética en las secuencias de ese gen, y se puede apreciar que en varios árboles, especies distantes filogenéticamente como _Danio rerio_ aparecen cerca de tetrápodos, lo que contradice el árbol de especies (ASTRAL), lo que indica artefactos de reconstrucción o posible contaminación o errores en la alineación. Mientras que por otro lado algunos árboles como OG0000001 y OG0000003 muestran una relación más coherente entre vertebrados, agrupando correctamente peces, aves, y mamíferos.

Árbol de My gene trees (ASTRAL)
![imagen 22](https://github.com/SofiaChavesR/Filogen-mica/blob/main/my_gene_trees.tre.png)

Esto representa una superposición de múltiples árboles génicos, lo cual es útil para observar discordancias topológicas entre genes individuales y contrastarlas con el árbol de especies, además muestra una gran cantidad de discordancia entre los árboles génicos. Esto se refleja en la multiplicidad de bifurcaciones para ciertas ramas y la ausencia de una topología dominante clara, lo que sugiere la acción de procesos evolutivos como: Incongruencia por ILS (Incomplete Lineage Sorting) que es frecuente cuando las divergencias entre linajes ocurren rápidamente en el tiempo evolutivo. Junto a esto, diferentes genes pueden tener historias evolutivas distintas, especialmente si son parálogos. Además, algunos grupos parecen monofiléticos en la mayoría de los árboles (los clados se repiten con consistencia), mientras que otros muestran parafilia o polifilia lo que indica poca resolución filogenética en esas zonas, y este patrón es típico cuando los genes analizados tienen poca señal filogenética o alta tasa de evolución.

Grácias a este árbol se puede ver como ASTRAL infiere un árbol de especies basado en la frecuencia de cuartetos compartidos entre árboles génicos, proporcionando una estimación más robusta frente a la incongruencia.

Árbol de Concatena particionado
![imagen 23](https://github.com/SofiaChavesR/Filogen-mica/blob/main/partitioned.treefile.png)

Es un árbol basado en una matriz concatenada de genes, pero con modelos separados por partición (gen o región). Suele ser más preciso que el no particionado, ya que permite heterogeneidad evolutiva.

Árbol de concatenado no particionado
![imagen 24](https://github.com/SofiaChavesR/Filogen-mica/blob/main/unpartitioned.treefile.png)

Este árbol usa una matriz concatenada sin considerar diferencias evolutivas entre genes. Puede inducir sesgos en la inferencia filogenética si hay mucha heterogeneidad.

Árbol de Especies de ASTRAL
![imagen 25](https://github.com/SofiaChavesR/Filogen-mica/blob/main/species_tree_ASTRAL.tre.png)

Este árbol se basa en la reconciliación de múltiples árboles génicos. Refleja la historia evolutiva de las especies utilizando métodos que tienen en cuenta incongruencias entre genes debido a eventos como incompleta linaje sorting (ILS).
