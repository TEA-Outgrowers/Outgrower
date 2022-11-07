# Outgrower
<p align="center">
<img width="500" align="center" src="https://github.com/TEA-Outgrowers/Outgrower/blob/main/TEA-Outgrowers.png">
</p>
 
Este proyecto gira en torno a la creación de un software determinar la temperatura óptima requerida para determinar la óptima temperatura para lograr la germinación máxima de una dada cantidad de semillas para los cultivos de trigo, frijol mungo y arroz. 

# Objetivos 
•	Uso del lenguaje de programación Python para crear un programa con aplicabilidad en la agricultura.

•	Uso del lenguaje de programación Python para desarrollar un software que determine las temperaturas óptimas para la germinación de mayor cantidad posible de semillas de diferentes cultivos.

•	Brindar al sector agrícola un programa que se pueda aplicar a los planes de siembra de diferentes cultivos con una idea más precisa de la temperatura óptima de germinación.

•	Proporcionar las informaciones necesarias para realizar un plan de siembra en base a las variaciones de temperaturas.

# Introducción 

La tecnología es cada vez más imprescindible para nosotros hoy en día, porque nos facilita el trabajo en todos los ámbitos.
El sector agrícola también es uno de los principales beneficiarios. Basándonos en esta observación, como futuros agrónomos, queríamos usarla para
desarrollar un programa que permitiera determinar con mayor precisión una temperatura media óptima para la germinación ideal de determinadas especies a partir de los datos recogidos tras varios experimentos.

# Definición del problema a resolver

La variación de temperatura en función del lugar donde se cultiva y de la temporada en que estamos influyen mucho en la tasa de germinación de las semillas. Esto puede desencadenar grandes pérdidas de las inversiones de los productores si no toma en cuenta estos factores para crear las condiciones necesarias para obtener un mayor rendimiento en germinación, crecimiento y por ende producción. 



# Importancia de un tal programa
Dados los continuos cambios del clima en la actualidad, diversos factores importantes para el sector agrícola están sometidos a variaciones importantes que deben ser consideradas. Dentro de ellas,está la temperatura que es un factor decisivo en el proceso de la germinación, que influye
sobre las enzimas que regulan la velocidad de las reacciones bioquímicas que ocurren en la
semilla después de la rehidratación.
La actividad de cada enzima tiene lugar entre un máximo y un mínimo de temperatura, existiendo un óptimo intermedio. Del mismo modo, en el proceso
de germinación pueden establecerse unos límites similares. Por ello, las semillas sólo germinan
dentro de un cierto margen de temperatura. Si la temperatura es muy alta o muy baja, la
geminación no tiene lugar, aunque las demás condiciones sean favorables. Al determinar la temperatura óptimma para que se ocurren estos procesos se puede optar a crear las condiciones necesarios para lograrlos .

# Métodos y herramientas utilizados 

El lenguaje de programación utilizado en la realización de este proyecto es **Python**. Mediante la plataforma Github hemos creado una organización con un repositorio para almacenar la fuente de datos, los códigos generados para obtener los resultados, la documentación y información relativa a los miembros.

Los datos utilizados se recopilaron a partir de un conjuntos de datos de los 
**[Proyectos de Github por Vincent Arel-Bundock](https://vincentarelbundock.github.io/Rdatasets/datasets.html)**. La fuente de datos seleccionada fue **Germination of three crops** en formato CSV dónde se evaluó diferentes respuestas de germinación de 3 especies: trigo, arroz y mungo frijol entre las temperaturas de 10 a 40 C.

La interfaz web **[Jupyter Notebook](https://jupyter.org/)** permitió realizar las diferentes codificaciones con el lenguaje python y generar un documento que descargamos para guardarlo en el repositorio Github.
Se ha utilizado el "open source" **[Pandas](https://pandas.pydata.org/)** para subir la fuente de datos a memoria, leerla para analizar y filtrar las informaciónes más relevantes. Y Las bibliotecas **[Matplotlib](https://matplotlib.org/)** y **[Numpy](https://numpy.org/)** fueron utilizadas para producir los diversos gráficos de manera a  interpretar los resultados. 

# Resultados y discusiones

<img height="400" src="https://github.com/TEA-Outgrowers/Outgrower/blob/main/graph_germinated_max.png" align="middle"> 

- A la temperatura de **10°C** de las 20 semillas: 

8 germinaron por la especie de trigo(**wheat**) 

9 germinaron por la especie de frijol mungo(**mungbean**)

No se hizó la experiencia con la especie de frijol(**rice**) 

- A la temperatura de **16°C** de las 20 semillas: 
 
10 germinaron por la especie de arroz(**rice**) 

8 germinaron por la especie de trigo(**wheat**) 

12 germinaron por la especie de frijol mungo(**mungbean**)
 
**Solo se hizó la experencia con el **mungbean** a las temperaturas de 10 y 16°C. La especie tuvó mayor germinación a la temperatura de 16°C.**

- A la temperatura de **22°C** de las 20 semillas: 
 
9 germinaron por la especie de arroz(**rice**) 

12 germinaron por la especie de trigo(**wheat**) 
  
- A la temperatura de **28°C** de las 20 semillas: 
 
17 germinaron por la especie de arroz(**rice**) 

8 germinaron por la especie de trigo(**wheat**) 

**Se obtuvó un mejor resultado para el arroz a 28°C.**
  
- A la temperatura de **34°C** de las 20 semillas: 
  
13 germinaron por la especie de arroz(**rice**) 

11 germinaron por la especie de trigo(**wheat**)
  
- A la temperatura de **40°C** de las 20 semillas: 

12 germinaron por la especie de arroz(**rice**) 

17 germinaron por la especie de trigo(**wheat**)   

**Se obtuvó un mejor resultado para el trigo a 40°C.**
  
 
# Conclusiones

1. El lenguaje de programación Python puede servir para llevar a cabo proyectos relacionados con la agricultura. 

2. Las librerías y open source de Python facilitan la filtración de datos para un análisis adecuado de informaciones 
   relevantes como la germinación máxima a las diferentes temperaturas de cada especie.  

3. El trigo(**wheat**) tuvó su germinación máxima a los 40°C, el arroz(**rice**) a los 28°C y el frijol mungo(**mungbean**) a los 16°C. 

4. El programa puede ser util en investigaciones sobre las relaciones que pueden existir entre las enzimas que participan en el proceso de germinación y la        
   temperatura.

5. El programa puede servir de guía para los diferentes agricultores en sus planes de siembra.  

# Proyección futuro 

Este programa es una herramienta bastante importante para el sector agrícola. Especialmente para los investigadores teniendo en cuenta que el experimento se realizó en  laboratorio.Tenemos la intención de recopilar aún más datos sobre más especies en el futuro sobretodo aquellas de gran importancia para las necesidades humanas. También, se espera una investigación en el campo de la bioquímica para analizar el comportamiento de las enzimas entre diferentes temperaturas.  

# Developers

Ana Murray          (ana.murray@est.zamorano.edu ; [anamurrayy](https://github.com/anamurrayy))   

Angie Palma         (angie.palma@est.zamorano.edu ; [Angiepalma24](https://github.com/Angiepalma24))

Ayleen Nuñez        (ayleen.nunez@est.zamorano.edu ; [ayleennunez](https://github.com/ayleennunez))

Daniela Cea         (daniela.cea@est.zamorano.edu ; [Dannncea05](https://github.com/Dannncea05))

Jorge Caballero     (jorge.a.caballero@est.zamorano.edu ; [jorge1a2caballero](https://github.com/jorge1a2caballero))

Madelyn Barrera     (madelyn.barrera@est.zamorano.edu ; [MadelynBarrera24](https://github.com/MadelynBarrera24)) 

María Aguirre       (mariajose.aguirre@est.zamorano.edu ; [mariajoseag77](https://github.com/mariajoseag77))

Mariela Flores      (mariela.g.flores@est.zamorano.edu ; [marielagissellef](https://github.com/marielagissellef))

Maryori Flores      (maryori.flores@est.zamorano.edu ; [maryori23](https://github.com/maryori23))

Widlyn Placide      (widlyn.placide@est.zamorano.edu ; [Widcrypt](https://github.com/Widcrypt)) 


# Fuente de datos: 
La base de datos de [Vincent Arel-Bundock](https://vincentarelbundock.github.io/Rdatasets/datasets.html) proporciona información estadística sobre diferentes temas y sobre diferentes países descargable en formato CSV o DOC.   

# Agradecimiento
Agradecemos enormemente al [Dr. Servio Palacios](https://github.com/maverick-zhn) y el ingeniero [Gonzalo Maradiaga](https://github.com/gonzalomaradiaga) por su apoyo en la realización de este proyecto.

# Referencias: 
Doria, J. (2010). Generalidades sobre las semillas: su producción, conservación y almacenamiento. Cultivos tropicales,31(1),0000. http://scielo.sld.cu/scielo.php?script=sci_arttext&pid=S0258-59362010000100011   

Ritz, C., Pipper, C. B., & Streibig, J. C. (2013). Analysis of germination data from agricultural experiments. European Journal of Agronomy, 45, 1-6.  

vincentarel-bundock/Rdatasets.(2020).Germiantion of three crops. Recuperado de  https://vincentarelbundock.github.io/Rdatasets/datasets.html 
 
