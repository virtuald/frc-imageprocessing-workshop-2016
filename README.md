Image Processing using OpenCV + Python
======================================

This is a repository with content from a presentation given at NE FIRST
University Day on September 10, 2016.

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/virtuald/frc-imageprocessing-workshop-2016)

To launch the interactive environment using a web browser, click the
'launch binder' button above. You can view the slides in that environment, just
click "File", "Open", and select "slides.ipynb" from the list.

If you just want to view the slides, download and open slides.pdf 


Running this locally
====================

Windows
-------

* Install Python 3.5 (http://www.python.org/downloads)
* Install jupyter, matplotlib, and OpenCV:

```sh
py -3 -m pip install jupyter matplotlib opencv-python
```

To actually launch the environment, run this command from inside the repository
directory:

```sh
py -3 -m jupyter notebook
```

OSX
---

* Install [Python 3.4](https://www.python.org/downloads/release/python-344/) (not 3.5!)
* Install jupyter, matplotlib, and OpenCV:

```sh
pip3 install jupyter matplotlib opencv-python 
```

To actually launch the environment, run this command from inside the repository
directory:

```sh
jupyter notebook
```


Slideshow
---------

To display the slideshow interactively, you'll need to install
[RISE](https://github.com/damianavila/RISE).

Author
======

Dustin Spicuzza (dustin@virtualroadside.com)