# Contenido

Este repositorio está orientado a servir como índice para los repositorios de las diferentes asignaturas del **Grado de Ingeniería Informática** de la **Universidad de Málaga**, donde cada asignatura tiene su propio repositorio en el que se encuentran sus apuntes, ejercicios, prácticas, exámenes resueltos...

La siguiente tabla contiene enlaces a los repositorios originales (en azul) y está clasificada por años y cuatrimestres; además, se ha utilizado el formato:
* **Negrita** para las asignaturas de mi mención (**Tecnologías de la Información**).
* _Cursiva_ para mis asignaturas optativas.

<table align="center">
    <thead align="center">
        <tr>
            <th></th>
            <th>Cuatrimestre I</th>
            <th>Cuatrimestre II</th>
        </tr>
    </thead>
    <tbody align="center">
        <tr>
            <td colspan="4"></td>
        </tr>
        <tr>
            <td rowspan="5">Año I</td>
            <td>Cálculo para la Computación</td>
            <td>Estructuras Algebráicas</td>
        </tr>
        <tr>
            <td>Fundamentos Físicos de la Informática</td>
            <td>Métodos Estadísticos para la Computación</td>
        </tr>
        <tr>
            <td>Fundamentos de Electrónica</td>
            <td>Organización Empresarial</td>
        </tr>
        <tr>
            <td>Fundamentos de Programación</td>
            <td><a href="https://github.com/15Galan/asignatura-109" target="_blank" rel="noopener noreferrer">Programación Orientada a Objetos</a></td>
        </tr>
        <tr>
            <td>Matemática Discreta</td>
            <td>Tecnología de Computadores</td>
        </tr>
        <tr>
            <td colspan="4"></td>
        </tr>
        <tr>
            <td rowspan="5">Año II</td>
            <td><a href="https://github.com/15Galan/asignatura-201" target="_blank" rel="noopener noreferrer">Análisis y Diseño de Algoritmos</a></td>
            <td>Introducción a la Ingeniería del Software</td>
        </tr>
        <tr>
            <td>Bases de Datos</td>
            <td><a href="https://github.com/15Galan/asignatura-207" target="_blank" rel="noopener noreferrer">Programación y Sistemas de Concurrencia</a></td>
        </tr>
        <tr>
            <td><a href="https://github.com/15Galan/asignatura-203" target="_blank" rel="noopener noreferrer">Estructura de Computadores</a></td>
            <td>Redes y Sistemas Distribuidos</td>
        </tr>
        <tr>
            <td><a href="https://github.com/15Galan/asignatura-204" target="_blank" rel="noopener noreferrer">Estructura de Datos</a></td>
            <td>Sistemas Inteligentes I</td>
        </tr>
        <tr>
            <td>Teoría de Autómatas y Lenguajes Formales</td>
            <td><a href="https://github.com/15Galan/asignatura-210" target="_blank" rel="noopener noreferrer">Sistemas Operativos</a></td>
        </tr>
        <tr>
            <td colspan="4"></td>
        </tr>
        <tr>
            <td rowspan="5">Año III</td>
            <td><a href="https://github.com/15Galan/asignatura-301" target="_blank" rel="noopener noreferrer">Introducción a los Sistemas de Información</a></td>
            <td><a href="https://github.com/15Galan/asignatura-305" target="_blank" rel="noopener noreferrer">Administración de Bases de Datos</a></td>
        </tr>
        <tr>
            <td><a href="https://github.com/15Galan/asignatura-302" target="_blank" rel="noopener noreferrer">Procesadores de Lenguajes</a></td>
            <td><a href="https://github.com/15Galan/asignatura-306" target="_blank" rel="noopener noreferrer">Sistemas de Información para Internet</a></td>
        </tr>
        <tr>
            <td><a href="https://github.com/15Galan/asignatura-303" target="_blank" rel="noopener noreferrer">Seguridad de la Información</a></td>
            <td>Sistemas Inteligentes II</td>
        </tr>
        <tr>
            <td><b><a href="https://github.com/15Galan/mencion-330" target="_blank" rel="noopener noreferrer">Desarrollo de Servicios Telemáticos</a></b></td>
            <td><b><a href="https://github.com/15Galan/mencion-331" target="_blank" rel="noopener noreferrer">Modelos Estadísticos y Simulación</a></b></td>
        </tr>
        <tr>
            <td><i>Redes Inalámbricas</i></td>
            <td><i>Procesamiento de Imágenes y Vídeo</i></td>
        </tr>
        <tr>
            <td colspan="4"></td>
        </tr>
        <tr>
            <td rowspan="4">Año IV</td>
            <td><b><a href="https://github.com/15Galan/mencion-430" target="_blank" rel="noopener noreferrer">Administración de Sistemas Operativos</a></b></td>
            <td><a href="https://github.com/15Galan/asignatura-401" target="_blank" rel="noopener noreferrer">Proyectos y Legislación</a></td>
        </tr>
        <tr>
            <td><b><a href="https://github.com/15Galan/mencion-431" target="_blank" rel="noopener noreferrer">Diseño y Evaluación de Infraestructuras Informáticas</a></b></td>
            <td><i>Arquitecturas Clúster</i></td>
        </tr>
        <tr>
            <td><b><a href="https://github.com/15Galan/mencion-432" target="_blank" rel="noopener noreferrer">Planificación de Proyectos y Análisis de Riesgos</a></b></td>
            <td><i>Prácticas Externas</i></td>
        </tr>
        <tr>
            <td><b>Tecnología de los Sistemas de Producción</b></td>
            <td>T.F.G</td>
        </tr>
    </tbody>
</table>

# Uso del repositorio

Se usan [submódulos de Git](https://www.git-scm.com/book/es/v2/Herramientas-de-Git-Subm%C3%B3dulos), por lo que puede obtenerse el contenido del repositorio original de cualquier asignatura de la siguiente forma:

Clonar este repositorio y todos los submódulos:
```bash
git clone --recursive
```

Actualizar todos los submódulos del repositorio:
```bash
git submodule update --init --recursive
```

Obtener el contenido de una asignatura en concreto:
```bash
git submodule update --init <carpeta de la asignatura>
```

Cualquiera de estos comandos es necesario al clonar el repositorio por primera vez o de lo contrario, los submódulos estáran vacíos, lo que podría llevar a confusión.
