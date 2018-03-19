# music21playground

Some Jupyter notebooks (http://jupyter.org/) to test basic music21 functionalities.

### Run notebook online
There are some possibilities to get an interactive online notebook running without the need to install the whole jNotebook environment (especially useful for classes, e-learning etc):

Google Notebooks (not used here):
https://colab.research.google.com

Binder:
https://mybinder.org/

To see this Repo running on Binder, click on the badge: 
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/musicEnfanthen/music21playground/master)

Basic functionalities are interactively working with the Binder image. But, using jupyter notebook inside a Binder image causes some issues with music21's ".show()"-method (see: https://github.com/cuthbertLab/music21/issues/260). Thanks to Tony Hirst ([@psychemedia](https://github.com/psychemedia)) there is a small workaround with a redefinition of the show()-method. Use the "Berg_Violin Concerto_interactiveImage.ipynb"-Notebook when you started this repo via Binder.

