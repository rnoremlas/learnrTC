# learnrTC

> Aprendizaje activo de R para el Análisis de Datos en las Ciencias Sociales

Con el objetivo de generar conocimiento a partir de información, en este proyecto se persigue desarrollar recursos docentes que permitan el aprendizaje activo del análisis de datos en Ciencias Sociales por parte de los alumnos de las asignaturas que impartimos. De esta forma, por un lado, se mejorarían/facilitarían las técnicas de aprendizaje actuales del estudiantado y, por otro, se fomenta la participación del estudiantado en su propio proceso formativo.

Concretamente, se desarrollan recursos y materiales docentes que permitan al estudiante adquirir conocimientos de forma autónoma/virtual sobre el análisis de datos con el lenguaje de programación R (entorno de software libre para la computación de datos ampliamente usado en el ámbito académico y empresarial). 

La propuesta anterior se alcanza usando el paquete learnr de R, el cual permite (ver https://cran.r-project.org/web/packages/learnr/index.html) crear tutoriales interactivos usando una combinación de texto, figuras, videos, ejercicios o cuestionarios de forma que cada estudiante pueda aprender R a su propio ritmo. 

Para instalar el paquete que contiene los test desde GitHub hay que usar el paquete *remotes*:

> install.packages("remotes") # solo es necesario instalarlo la primera vez
>
> library(remotes)
>
> remotes::install_github("rnoremlas/learnrTC")

Para la asignatura Técnicas Cuantitativas 1 se han creado diez tutoriales que puedes ejecutar usando los siguientes comandos:

> learnr::run_tutorial("01 tablas y representaciones", package= "learnrTC") # creado por Román Salmerón Gómez
> 
> learnr::run_tutorial("02 medidas posicion", package= "learnrTC") # creado por Beatriz Cobo Rodríguez
> 
> learnr::run_tutorial("03 mediadas dispersion", package= "learnrTC") # creado por Teresa García Muñoz
> 
> learnr::run_tutorial("04 medidas de forma", package= "learnrTC") # creado por Rosaura Fernández Pascual
> 
> learnr::run_tutorial("05 medidas concentracion", package= "learnrTC") # creado por Irene García Garrido
> 
> learnr::run_tutorial("06 condicionadas", package= "learnrTC") # creado por Román Salmerón Gómez
> 
> learnr::run_tutorial("07 covarianza correlacion", package= "learnrTC") # creado por Alessio Gaggero
> 
> learnr::run_tutorial("08 recta regresion", package= "learnrTC") # creado por Víctor Blanco Izquierdo
> 
> learnr::run_tutorial("08bis recta regresion (no lineal)", package= "learnrTC") # creado por Román Salmerón Gómez
> 
> learnr::run_tutorial("09 distribucines discretas de probabilidad", package= "learnrTC") # creado por Catalina García García

¡¡Esperamos que este paquete sea de tu interés!!
