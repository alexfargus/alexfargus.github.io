Install the dependencies
========================

Poppler
-------

>  wget http://blog.alivate.com.au/wp-content/uploads/2017/01/poppler-0.51_x86.7z
>  7z x poppler-0.51_x86.7z -oC:\

Imagemagick
-----------

>  choco install imagemagick.tool

Python dependencies
-------------------

>  pip install docutils recommonmark 
>  pip install rinoh-typeface-texgyrecursor rinoh-typeface-texgyreheros rinoh-typeface-texgyrepagella rinoh-typeface-dejavuserif
>  pip install bump2version restview tox twine pytest pytest-assume pytest-console-scripts tox-gh-actions wheel pytest-xdist
>  pip install doc8


Clone the repository
====================

> git clone git@github.com:brechtm/rinohtype.git
> cd rinohtype
> git submodule update --quiet --init


Register rinoh with python
==========================

> cd rinohtype
> python -m pip install -e .
