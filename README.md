# Apuntes de Matemáticas Discretas para la Computación

Apunte del curso **CC3101 – Matemáticas Discretas para la Computación** del Departamento de Ciencias de la Computación (DCC) de la Universidad de Chile.

**Autor:** Andrés Abeliuk
**Año:** 2025

> Elaborado a partir de las diapositivas del curso impartido por Alejandro Hevia, Federico Olmedo y Jocelyn Simmonds.

## Contenidos

El apunte está organizado en cinco partes:

### Parte I – Fundamentos de la Lógica
- **Capítulo 1:** Lógica Proposicional — sintaxis, semántica, tautologías, equivalencia, consecuencia lógica, deducción natural, satisfactibilidad y aplicaciones
- **Capítulo 2:** Lógica de Predicados — cuantificadores, estructuras e interpretaciones, inferencia, robustez y completitud (Teorema de Gödel)

### Parte II – Técnicas de Demostración
- **Capítulo 3:** Inducción Matemática — demostración directa, contraposición, contradicción, principio de inducción, inducción fuerte, inducción estructural, definiciones recursivas

### Parte III – Relaciones y Funciones
- **Capítulo 4:** Relaciones — propiedades, relaciones de orden, relaciones de equivalencia, clases de equivalencia, particiones, relaciones n-arias
- **Capítulo 5:** Funciones — operaciones sobre relaciones, clausuras, funciones inyectivas/sobreyectivas/biyectivas, crecimiento de funciones y notación O

### Parte IV – Combinatoria
- Principios de conteo (producto y suma), inclusión-exclusión, principio del palomar
- Permutaciones y combinaciones (con y sin repetición)
- Pruebas combinatoriales
- Relaciones de recurrencia y recurrencias lineales
- Funciones generadoras, Teorema del Binomio Extendido, números de Catalán

### Parte V – Teoría de Grafos
- Definiciones y clasificación de grafos, representaciones (listas y matrices)
- Subgrafos, isomorfismo
- Conectividad, caminos, circuitos Eulerianos y Hamiltonianos
- Algoritmo de Dijkstra (caminos más cortos)
- Colorabilidad, grafos planares, Fórmula de Euler, Teorema de los Cuatro Colores
- Árboles, árboles generadores (DFS/BFS), árboles de costo mínimo (Prim y Kruskal)

## Compilar el apunte

El apunte está escrito en LaTeX. Para compilarlo necesitas una distribución LaTeX (e.g. TeX Live, MiKTeX) con los paquetes estándar.

```bash
pdflatex main_apunte.tex
```

El PDF compilado `main_apunte.pdf` también está disponible directamente en el repositorio.

## Estructura del repositorio

```
.
├── main_apunte.tex        # archivo principal LaTeX
├── main_apunte.pdf        # PDF compilado
├── clases/                # un archivo .tex por clase (clase01.tex … clase23.tex)
├── Figures/               # figuras e imágenes
└── dcc_2019_cuadrado_blanco.png
```

## Licencia

Ver archivo [LICENSE](LICENSE).
