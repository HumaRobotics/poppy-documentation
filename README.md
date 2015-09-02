# poppy-documentation

INSTALLATIONS:
pip install sphinx sphinxjp.themes.basicstrap
sudo apt-get install -qq texlive texlive-latex-extra dvipng
pip install commonmark recommonmark

if problems with Pygments:
sudo apt-get remove python-pygments
pip install Pygments

Pour convertir les ipython notebooks en rst:
pip install ipython
pip install nbconvert
sudo apt-get install pandoc

Create simlinks (ln -s /pth/to/folder link_name):
pypot/doc -> doc_pypot
poppy-humanoid/hardware/doc -> doc_poppy_humanoid
pypot/samples/notebooks -> ex_pypot
poppy-humanoid/software/samples/notebooks -> ex_poppy_humanoid

USAGE

creation de l'HTML
>make html

creation du PDF
>make latexpdf

convertion des notebooks
>ipython nbconvert --to rst notebook_name.ipynb 

Modification du contenu: index.rst



