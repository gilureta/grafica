# Tópicos Avanzados de Gráfica Computacional

## Clases

1. Clase 01 - ¿Cómo modelamos un mundo digital?
    * 09/03 -  [Storyboard](clases/clase_01/index.html) - [Practical](practicals/practical_01/index.html)
    * Después de esta clase l@s estudiantes pueden **explicar** cuales son los elementos básicos de una escena 3D y cómo se relacionan entre ellos (mediante transformaciones jerárquicas)
    * Lecturas complementarias:
        * FCC - Ch 7 - Transformation Matrices
        * [ThreeJS Transformations](https://discoverthreejs.com/book/first-steps/transformations/)

1. Clase 02 - ¿Cómo modelamos objetos?
    * 11/03 - [Storyboard](clases/clase_02/index.html) - [Practical](practicals/practical_02/index.html)
    * Después de esta clase l@s estudiantes pueden **construir** una mesh a mano para las geometrías básicas (cubo, cilindro, esfera) y pueden explicar cuales son los componentes de un mesh. 
    * Lecturas complementarias:
        * FCC - Ch 12 - Data Structures for Graphics
        * [scratchapixel' polygon mesh intro](https://www.scratchapixel.com/lessons/3d-basic-rendering/introduction-polygon-mesh/introduction.html
        )

1. Clase 03 - Mallas Poligonales cómo datos
    * 16/03 - [Storyboard](clases/clase_03/index.html) - [Practical](practicals/practical_03/offline_processing.ipynb)
    * Después de esta clasel@s alumn@s  pueden leer una mesh desde un archivo, calcular estadísticas geométricas básicas (conteos, bounding box, duplicación de vértices) y visualizar los resultados en **python**.
    * Lecturas complementarias:
        * [scratchapixel' OBJ file format](https://www.scratchapixel.com/lessons/3d-basic-rendering/obj-file-format/obj-file-format.html)

1. Clase 04 - ¿Cómo agregamos imágenes a la geometría?
    * 18/03 - [Storyboard](clases/clase_04/index.html) -  [Practical](practicals/practical_04/index.html)
    * Después de esta clase los estudiantes pueden **inspeccionar y modificar coordenadas UV**, identificar distorsión y solapamientos, y explicar cómo mapas de normales y altura afectan la apariencia de una superficie sin cambiar su geometría.
    * Lecturas complementarias:
        * FCC - Ch 11 - Texture Mapping
        * ThreeJS - Texture Fundamentals https://threejs.org/manual/?q=tex#en/textures

1. Clase 05 - ¿Cómo coloreamos los objetos 3D?
    * 23/03 - [Storyboard](clases/clase_05/index.html) -  [Practical](practicals/practical_05/index.html)
    *  Después de esta clase los estudiantes pueden **explicar** el modelo de iluminación Lambertiano, **identificar** sus parámetros, y **razonar** cómo la interacción entre luz y material determina el color observado.
    * Lecturas complementarias:
        * FCC - Ch 5 - Surface Shading
        * Real-Time Rendering - Capitulo 5 - Visual Appearance

1. Clase 06 - Cámara. Del mundo 3D a la imagen 2D
    * 25/03 - [Storyboard](clases/clase_06/index.html) -  [Practical](practicals/practical_06/index.html)
    * Después de esta clase los estudiantes pueden **explicar** el modelo de cámara pinhole, **distinguir** entre parámetros intrínsecos y extrínsecos, y **calcular** una configuración de cámara que encuadre un objeto dentro del frustum.

    * Lecturas complementarias:
        * FCC - Ch 8 - Viewing
        * [The Pinhole Camera Model](https://www.scratchapixel.com/lessons/3d-basic-rendering/3d-viewing-pinhole-camera/how-pinhole-camera-works-part-1.html) by Scratch a Pixel 
    
1. Clase 07 - Ray Tracing
    * 25/03 - [Storyboard](clases/clase_07/index.html) -  [Practical](practicals/practical_07/RayTracing.ipynb)
    *  Después de esta clase los estudiantes pueden **generar rayos** desde una cámara para calcular una imagen, **identificar intersecciones** con la geometría de la escena y **explicar** cómo el color de cada píxel se determina a partir del primer objeto intersectado.
    * Lecturas complementarias:
        * FCC - Ch 4 - Ray Tracing
        * [Implementing the Ray Tracing Algorithm](https://www.scratchapixel.com/lessons/3d-basic-rendering/introduction-to-ray-tracing/implementing-the-raytracing-algorithm.html) by Scratch a Pixel 

## Bibliografia
* **[FCC]** Marschner, S., Shirley, P. (2021). Fundamentals of Computer Graphics: International Student Edition. United States: CRC Press. [[BiblioUC](https://buscador.bibliotecas.uc.cl/permalink/56PUC_INST/1mvmg85/alma990005791390203396)]
* Akenine-Möller, T., Haines, E., Hoffman, N. (2018). Real-Time Rendering, Fourth Edition. United Kingdom: CRC Press.
* Angel, E., Shreiner, D. (2015). Interactive Computer Graphics: A Top-down Approach with WebGL. United Kingdom: Pearson.
* Eck, D. J. (2016). Introduction to computer graphics., https://math.hws.edu/graphicsbook/ (free book)