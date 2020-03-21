# PyGLPK_task_scheduling
ILP formulation for solving scheduling problem for scheduling n tasks on m processors

## Install
`conda install glpk` does not work. 


The steps below does not work as well:
So instead of spending time there, run

1. `wget http://www.dcc.fc.up.pt/~jpp/code/python-glpk/python-glpk_0.4.43.orig.tar.gz`
2. `tar -xzf python-glpk_0.4.43.orig.tar.gz`
3. `cd python-glpk-0.4.43/src/`
4. `sudo make install`
5. `cd ../examples`
6. `python test.py`

from https://en.wikibooks.org/wiki/GLPK/Python
