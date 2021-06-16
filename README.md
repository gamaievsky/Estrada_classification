# HARMONIC COLORATION COMBINATORY POTENTIAL OF INTERVALS

This script allows you to add an acoustic dimension to the Julio Estrada's combinatorial potential of intervals classification by introducing a harmonic colour on it.


## Python dependencies

- [p5 processing](https://p5.readthedocs.io/en/latest/install.html)
- tkinter

## Installation

Install tkinter:

```
pip install tk
```

Prerequise for p5: you need first to install GLFW:

```
brew install glfw
```

Then, install p5:

```
pip install tk
```
In case you have trouble to install p5, go to the [installation page](https://p5.readthedocs.io/en/latest/install.html)



## How to use it

Once dependencies are installed, run:

```
./Estada.py
```

To access the parameters, click on the button « Paramètres d'affichage » at the top left corner. You have access to spectrum parameters, colors assignation and color normalisation parameter on the second level of representation.  

#### Spectrum parameters
Descriptors values are pre-calculated, so for for each spectrum parameter you can choose between a set of values.

- K: number of partials
- Decr: decrease of partials coefficient
- σ: width of partials

#### Color parameters
There are two modes:

- RGB: You assign a harmonic descriptor to each of RGB (Red-Green-Blue) component.
- Rainbow (arc-en-ciel): You assign one descriptor to a color scale ranging from blue (low values) to red (high values), as below.  

![colorscale](/color_scale.png)

#### Second level (permutahedron)
There are two modes to color the permutahedron (set of normal classes in an identity).

- "Absolute": The same color scale is used like in respect to the first level
- "Relatif": Values of the permutahedron are matched to cover the whole color range, from blue to red.
