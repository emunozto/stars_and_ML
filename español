Este trabajo se inspiró en el proyecto de investigación que realicé durante mis estudios de posgrado. El enfoque está en las estrellas de tipo **Be** y la aplicación de técnicas de aprendizaje automático para extraer información significativa sobre sus propiedades espectrales y la dinámica de sus discos. El conjunto de datos principal se obtuvo en el Observatorio de Kitt Peak, mientras que datos adicionales de acceso público pueden consultarse en la base de datos Be Star Spectra (BeSOS).

## Estrellas Be

**Introducción**  

Las estrellas **Be** son una clase peculiar de estrellas de tipo B que rotan rápidamente y están rodeadas por un disco de decreción circunestelar concentrado a lo largo del ecuador estelar. El mecanismo que impulsa la eyección de material desde la superficie estelar hacia este disco aún es incierto, aunque se cree que la rotación rápida desempeña un papel clave. El disco produce líneas de emisión prominentes, en particular de la serie de Balmer del hidrógeno. Además, numerosas líneas de emisión de Fe II se originan en la misma región. Entre las líneas de Balmer, H-alfa es la característica más brillante en el espectro visible. La forma y propiedades de estos perfiles de línea brindan información directa sobre la estructura, la geometría y la dinámica del disco.

Los espectros pueden clasificarse en dos grandes grupos: estrellas con disco y estrellas sin disco. Para las estrellas con disco, los espectros se subdividieron de acuerdo con el ángulo de inclinación relativo al observador, clasificándose como vistos desde el polo, de canto (edge-on) o en posición intermedia.

Este proyecto aplicó algoritmos de aprendizaje automático para analizar las líneas espectrales de estrellas *Be*, con el doble objetivo de caracterizar la dinámica del disco e identificar las regiones responsables de generar diferentes perfiles de línea. Un primer paso fue categorizar los espectros en dos grandes grupos: estrellas con disco y estrellas sin disco.

**Metodología**  

Se aplicó un agrupamiento no supervisado mediante Clustering Jerárquico Aglomerativo por Enlace Completo, un enfoque ascendente que construye árboles jerárquicos de clusters (dendrogramas). Para determinar el número óptimo de clusters, se utilizaron como métricas de evaluación tanto el método del codo (Elbow method) como el coeficiente de Silhouette.

**Conclusión**  

El análisis de agrupamiento reveló agrupaciones naturales consistentes con las expectativas físicas de la geometría del disco. Los perfiles de emisión H-α de doble pico surgieron como una firma característica de los discos circunestelares. Se encontró que la separación entre los dos picos se correlaciona fuertemente con la inclinación del disco: separaciones menores en sistemas casi vistos desde el polo y mayores en sistemas observados de canto. Estos resultados demuestran que los métodos no supervisados pueden recuperar distinciones físicas significativas directamente de los datos espectrales. Las líneas H-alfa producidas por el disco presentan doble pico, y la separación entre estos está estrechamente relacionada con la inclinación del disco respecto al plano de observación.

**Apéndice**  

Las estrellas de tipo B son estrellas calientes, masivas y luminosas que pertenecen al tipo espectral B. Sus temperaturas efectivas oscilan entre 10,000–30,000 K, significativamente mayores que el valor solar (~5,800 K), y por ello exhiben un color azul o azul blanquecino. Estas estrellas suelen tener masas entre 2–16 M☉ y radios varias veces el del Sol. Sus luminosidades bolométricas abarcan un rango amplio, desde 10² hasta 3×10⁴ L☉, situándolas entre las más radiantes de la secuencia principal y de las estrellas evolucionadas.

Ejemplos representativos:

Rigel (β Orionis, B8 Ia): una supergigante azul.

Spica (α Virginis, B1 III–IV): un sistema gigante/subgigante.

Achernar (α Eridani, B6 Vep): una estrella Be que exhibe líneas de emisión originadas en un disco de decreción circunestelar.

Importancia astrofísica:
Las estrellas de tipo B ejercen una fuerte influencia en su entorno mediante intensa radiación ultravioleta y vientos estelares de alta velocidad, que moldean el medio interestelar circundante. Sus vidas en la secuencia principal son relativamente cortas (~10–100 Myr), reflejando sus altas masas y rápido consumo de combustible. Las estrellas B más masivas evolucionan hacia supernovas de colapso del núcleo, contribuyendo al enriquecimiento químico y a la formación de objetos compactos. Entre sus subclases se encuentran las estrellas Be, caracterizadas por su rápida rotación y las emisiones asociadas a discos, y las variables β Cephei, que presentan inestabilidades pulsacionales impulsadas por el mecanismo κ.
