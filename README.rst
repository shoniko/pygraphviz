PyGraphviz
----------

PyGraphviz is a Python interface to the Graphviz graph layout and
visualization package.

With PyGraphviz you can create, edit, read, write, and draw graphs using
Python to access the Graphviz graph data structure and layout algorithms.

PyGraphviz is distributed with a BSD license.

Copyright (C) 2006-2018 by 
Aric Hagberg <aric.hagberg@gmail.gov>
Dan Schult <dschult@colgate.edu>
Manos Renieris, http://www.cs.brown.edu/~er/
Distributed with BSD license.     
All rights reserved, see LICENSE.txt for details.

Windows 10 installation
-----------
Download [GraphViz](https://ci.appveyor.com/project/ellson/graphviz-pl238/build/job/5txdbqadymi94vra/artifacts).

Then run:

```
python setup.py install --user --include-path=C:\\...\\graphviz\\include --library-path=C:\\...\\graphviz\\lib
```