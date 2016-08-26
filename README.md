# RSG-ISCB-Santiago - Taller sobre ensamblaje y anotación de genomas bacterianos
--------------------------------------

- **Autor**: [Eduardo Castro](http://castrolab.org)
- **Fecha**: 27 de agosto de 2016  
- **Lugar**: Sala zócalo 2 (o ZO5), Facultad de Ciencias Biológicas, Pontificia Universidad Católica de Chile. Portugal 49

### Introducción

En este taller vamos a presentar y discutir los aspectos básicos del ensamblaje de genomas bacterianos y la anotación de genes. Vamos a utilizar datos reales de Illumina para prácticar directamente en la línea de comandos.  

En resumen, vamos a movernos a través de los pasos canónicos desde que recibimos los archivos desde el secuenciador hasta que comenzamos a examinar los resultados de lo que llamamos un genoma ensamblado y anotado.  

1. Control de calidad y procesamiento de datos genómicos ([PrinSeq](http://prinseq.sourceforge.net), [PEAR](http://sco.h-its.org/exelixis/web/software/pear/))
2. Ensamblaje de genomas con múltiples parámetros ([SPAdes](http://bioinf.spbau.ru/spades), [A5-pipeline](https://sourceforge.net/projects/ngopt/), [QUAST](http://quast.bioinf.spbau.ru))
3. Anotación automática de genes ab initio y por homología ([Prokka](https://github.com/tseemann/prokka), [EggNOG-Mapper](https://github.com/jhcepas/eggnog-mapper))
4. Exploración de resultados en exploradores de genomas ([Artemis Comparison Tool] (http://www.sanger.ac.uk/science/tools/artemis-comparison-tool-act), [Geneious Basic](http://www.geneious.com))  

Por motivos de tiempo, estamos dejando un paso muy importante afuera que tiene relación con el control de calidad de los fragmentos de DNA secuenciados, i.e., revisar si lo que nos entrega el secuenciador está libre de secuencias contaminantes, e.g., secuencias de humanos, otras bacterias, virus, etc. Revisa los siguientes manuscritos si estás interesado en aprender más sobre contaminación --> [PMID: 21408061](http://www.ncbi.nlm.nih.gov/pubmed/21408061); [PMID: 25412476] (http://www.ncbi.nlm.nih.gov/pubmed/25412476)  

Otro paso muy importante que vamos a dejar afuera tiene que ver con orientar los fragmentos de DNA contiguos producto del ensamblaje, i.e., orientar los contigs. Esto es comúnmente llamado Scaffolding y en general se utilizan uno o más genomas de referencia y las reads originales para guiar la orientación de los contigs. Para los interesados, revisar: Ragout ([PMID: 24931998] (http://www.ncbi.nlm.nih.gov/pubmed/24931998))  


Hoy vamos a trabajar con dos genomas bacterianos, *Escherichia coli* y *Pseudomonas fluorescens*. El aislado de *E. coli* fue obtenido de una muestra de carne de pollo que se compró en un supermercado en Washington, DC. El aislado de *P. fluorescens* fue obtenido de una muestra de suelo antártico.  

Descargar [*Pseudomonas fluorescens*](http://tinyurl.com/jn7nukh)  
Descargar [*Escherichia coli*](http://tinyurl.com/zu32w3j)  
[Clase introducción](https://github.com/ecastron/RSG-ISCB-Santiago/raw/master/RSG-ISCB.pdf)  




