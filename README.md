# music21playground

Some Jupyter notebooks (http://jupyter.org/) to test basic music21 functionalities.

### Run notebook online
There are some possibilities to get an interactive online notebook running without the need to install the whole jNotebook environment. Especially useful for classes, e-learning etc.

Binder:
https://mybinder.org/

Google Notebooks:
https://colab.research.google.com

To see this Repo running on Binder, click on the badge: 
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/musicEnfanthen/music21playground/master)

Basic functionalities are interactively working with the Binder image. But, using jupyter notebook inside a Binder image causes some issues with music21's ".show()"-method (see: https://github.com/cuthbertLab/music21/issues/260). Thanks to Tony Hirst ([@psychemedia](https://github.com/psychemedia)) there is a small workaround with a redefinition of the method.
