# programacion-uno_integrador_VarelaSosa

Trabajo práctico integrador sobre algoritmos de búsqueda y ordenamiento, de la materia Programación I (UTN Regional San Nicolás - Tecnicatura en Programación a Distancia 2025).

**Alumnos:**
- Santiago Octavio Varela (santiagov.linked@gmail.com) / [GitHub @santiagovOK](https://github.com/santiagovOK) 
- Ximena Maribel Sosa (ximenasosa44@gmail.com) / [GitHub @xms44](https://github.com/xms44) 

## Objetivo

El objetivo principal del trabajo es desarrollar un programa en Python que, mediante la combinación de técnicas de ordenamiento y búsqueda, evidencie la mejora en el rendimiento y la organización de la información.


## Video explicativo

- [Programación I Integrador | “Implementación y análisis de algoritmos de ordenamiento y búsqueda en Python”](https://youtu.be/F-snpfuKj84)
- [URL de la presentación](https://whimsical.com/presentacion-algoritmos-de-busqueda-y-ordenamiento-varelasosa-UgHSFeC8BqS2QsNA16AZZi)

## Contenido

- [Programa Completo en un solo .py](./programacion-uno_integrador.py) 
- [Programa Modularizado](./src/main.py) 
- [Informe General (PDF)](./informe_general/programacion-uno_integrador_informe_VarelaSosa.pdf)

---

## Demostración breve

![Demo](./assets/demo.GIF)

## Descripción del Proyecto

Este repositorio contiene un programa desarrollado como trabajo integrador de la materia **Programación I**. Su propósito principal es **validar el funcionamiento** de algoritmos de ordenamiento y búsqueda a través de su aplicación en listas generadas aleatoriamente, dando cuenta de la importancia del ordenamiento previo para optimizar el rendimiento de las búsquedas.

El usuario puede:

- Generar listas de números aleatorios.
- Ordenarlas utilizando **Bubble Sort** o elegir no ordenar la lista.
- Buscar elementos mediante **búsqueda lineal** o **binaria**.
- Medir los tiempos de ejecución de ambas operaciones.

## Estructura del proyecto

Este repositorio incluye dos versiones funcionales del mismo programa:

```
programacion-uno_integrador_VarelaSosa/
│
├── assets/                      # Archivos multimedia
│   └── demo.gif
│
├── informe_general/            # Documentación (en este caso, solo el informe)
│   └── programacion-uno_integrador_informe_VarelaSosa.pdf
│
├── src/                        # Código fuente del proyecto
│   ├
│   ├── main.py                 # Punto de entrada del programa
│   ├── generador.py            # Generación de listas aleatorias
│   ├── ordenamiento.py         # Función de Bubble Sort y ordenamiento de listas
│   └── busqueda.py             # Búsquedas lineal y binaria 
│
├── programacion-uno_integrador.py  # Versión en un solo .py
├── README.md                   # Descripción general del proyecto
├── LICENCE.txt                 # Licencia del proyecto
└── .gitignore                  # Archivos y carpetas ignoradas por Git
```
- `programacion-uno_integrador.py`: archivo único que contiene todo el código en un solo script.

- `src/main.py`: versión modular del mismo proyecto. Facilita la reutilización, mantenimiento y el test de componentes individuales.


## Resultados obtenidos y observaciones finales

- Durante las pruebas del programa se confirmó que cumple con los objetivos propuestos: permite generar listas, ordenarlas con Bubble Sort y realizar búsquedas con algoritmos lineal o binario. Se validó el funcionamiento correcto en listas pequeñas y medianas, y se compararon tiempos reales de ejecución.

- En listas cortas, la búsqueda lineal resultó más rápida que la binaria, principalmente porque no requiere condiciones previas. Además, se destacó la utilidad de mostrar paso a paso el ordenamiento, y las validaciones guiaron correctamente al usuario en cada interacción.

- El proyecto refuerza la importancia de elegir algoritmos según el contexto y muestra claramente cómo el orden previo de los datos impacta en el rendimiento de las búsquedas.

## Tecnologías utilizadas

- Python
- Visual Studio Code
- GitHub
- Google Docs (para el informe)
- YouTube (para la presentación)

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](./LICENSE) para más detalles.

La información sobre los diferentes tipos de licencia la hemos extraído de [Choose a License](https://choosealicense.com/).
