# Python in neuroscience

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.345422.svg)](https://doi.org/10.5281/zenodo.345422)


"Python in neuroscience" is a collection of collaboratively-edited tutorials on computational neuroscience methods using Pythhon language. Each tutorial is presented as a [literate programming](https://en.wikipedia.org/wiki/Literate_programming) tutorial mixing text, code and figures. The tutorials offer introduction both to basic methods of computational neuroscience and scientific programming in Python. They are authored in the environment called [Jupyter notebook](https://jupyter.org/) -- you can even [try it](https://try.jupyter.org/) in your browser!

## Viewing the tutorials

The view the tutorials you can use the excellent [nbviewer](https://nbviewer.jupyter.org/). To go to the table of contents follow the [link](https://nbviewer.jupyter.org/github/btel/python-in-neuroscience-tutorials/blob/master/index.ipynb).

(You can also open them on Github, but nbviewer gives a nicer user experience).


## Running the tutorials

The easiest way to run the code in the tutorials and experiment with it (you are most encourage to do so!), is to run it on a server in your browser. To do this simply click on the button below:

 [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/btel/python-in-neuroscience-tutorials) 

## Running the tutorials locally

If you are more serious about the tutorials and want to keep the changes that you make in them (or even create new tutorials), you may want to run the Jupyter notebooks locally on your computer.

### Installation

To run the tutorials locally, you need to install the scientific Python ecosystem. We recommend the free Python distribution called [anaconda](https://www.continuum.io/downloads). Please download and install Python 3.x version of anaconda for your platform.

After having installed anaconda, download the [latest](https://github.com/btel/python-in-neuroscience-tutorials/releases/latest) release of the tutorials and unpack them. 

### Opening the tutorials

Then open your terminal (for example, using the builtin Terminal.app in MacOS, or command-line console in Windows) and change to the directory with the tutorials. Next run the command (which is provided by anaconda):

```
jupyter notebook
```

A web  page with the tutorials should open in your browser (don't close your terminal). The web page with the tutorials is served locally from the directory, where you started `jupyter notebook` and all changes you save in the notebook are directly visible in your local files. Please navigate to `index.ipynb` to open the table of contents.

## Contributing

The tutorials are created collaboratively by computational neuroscience community. You are most encourage to contribute your ideas, corrections or new tutorials! All development is done on Github, so you can suggest changes on the Github issues page for this project. To edit or add new tutorials we follow the Github "fork & pull request" model. 

## Citing

To cite us you can use Zenodo DOI:

    Bartosz Telenczuk, 2017. Python in neuroscience - tutorials. doi:10.5281/zenodo.345422
