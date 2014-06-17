Physically Feasible Dynamic Parameter Identification of the WAM Robot 7-DOF
===========================================================================

[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.10534.png)](http://dx.doi.org/10.5281/zenodo.10534)

_Research notebook from the paper:_

**Sousa, Cristóvão D. and Cortesão, Rui, "Physically feasible dynamic parameter identification of the 7-DOF WAM robot," Intelligent Robots and Systems (IROS), 2013 IEEE/RSJ International Conference on , pp.2868-2873, 3-7 Nov. 2013, Tokyo, Japan, doi: [10.1109/IROS.2013.6696762](http://dx.doi.org/10.1109/IROS.2013.6696762)**



------------------------


Authors
-------

- Cristóvão D. Sousa, [crisjss@gmail.com](mailto:crisjss@gmail.com)
- Rui Cortesão, [cortesao@isr.uc.pt](mailto:cortesao@isr.uc.pt)

------------------------


Research Notebook
-----------------

The research is done in [Python](http://www.python.org/) within an [IPython notebook](http://ipython.org/notebook.html) (the *Paper IROS2013 - Phys Feas Dyn Param Ident 7-DOF WAM Rob.ipynb* file).
Data is in *data* folder. Additional Python support code is in *support_funcs* folder

The file *Paper IROS2013 - Phys Feas Dyn Param Ident 7-DOF WAM Rob.html* is a **preview** of the notebook. **It can be seen online at:**

**[Paper IROS2013 - Phys Feas Dyn Param Ident 7-DOF WAM Rob](http://goo.gl/8Xv6Mj)**


Presentation
------------

The slides and movies presented at IROS 2013 are avalable online [here](http://goo.gl/U9YmE5).


Paper Correction
----------------

The published paper presents a physically feasible base parameter solution ("beta star", rightmost column of Table I) which was obtained not taking the friction parameter positiveness constraints into account, contrary to what is shown in equation (17).
In this notebook, both the paper solution (without positiveness constraints on friction parameters) and the correct solution (with positiveness constraints on friction parameters) are computed and presented (to distinguish,  variable names are suffixed with the words "paper" and "correct", respectivelly). Nevertheless, the differences between both solutions (with exception to the corrected friction parameter) are very small, arround 1%. 


How to run the code
-------------------

- clone the git repository (it contains code and data) from https://github.com/cdsousa/IROS2013-Feas-Ident-WAM7
- open the *Paper IROS2013 - Phys Feas Dyn Param Ident 7-DOF WAM Rob.ipynb* notebook with [IPython](http://ipython.org/)
- edit and run the code

Dependencies:

- [Python](http://www.python.org/)
- [IPython](http://ipython.org/)
- [SymPy](http://sympy.org/)
- [Numpy](http://www.numpy.org/)
- [SciPy](http://www.scipy.org/)
- [SymPyBotics](https://github.com/cdsousa/SymPyBotics) (developed by the author Cristóvão D. Sousa)
- [PyLMI-SDP](https://github.com/cdsousa/PyLMI-SDP) (developed by the author Cristóvão D. Sousa)

------------------------


Questions & Feedback
--------------------

Although being open source, the code can lack some better documentation.
Feel free to contact the authors at [crisjss@gmail.com](mailto:crisjss@gmail.com)
We are open to help you to deploy this code or even your own implementation of the proposed algorithms.


------------------------


License
-------

Copyright (c) 2013, Cristóvão Duarte Sousa, Rui Cortesão

All rights reserved.

[![Creative Commons License](http://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)
This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/)
