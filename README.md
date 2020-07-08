# PyHEP 2020: A new PyROOT for ROOT 6.22

This talk will present a major revision of the ROOT Python bindings (PyROOT), previously in experimental mode, which has become the default in ROOT 6.22. PyROOT is HEP's entrance to all C++ from Python, e.g. for frameworks and their steering code. The new PyROOT bindings are still automatic and dynamic, but now they now operate on top of the cppyy libraries, which provide extensive support for modern C++. Together with the automatic bindings, PyROOT provides many pythonizations: lazily-injected custom behaviour that makes it easier / more pythonic to use ROOT classes from Python; in addition, users have the possibility to add their own pythonizations.

Furthermore, PyROOT has advanced interoperability features with the Python data science ecosystem, introduced during the experimental phase and now included by default. An example is the ability to read/write data from/to ROOT files with NumPy arrays as interface, which is crucial for today's data analysis and provides simple integration of physics data with the SciPy software stack and popular machine learning libraries.

Regarding the way PyROOT is built, 6.22 introduces the possibility to create a multi-Python ROOT build with PyROOT libraries for both Python2 and Python3, which will be selectively loaded when importing ROOT from one Python version or another.

Last but not least, the new PyROOT comes with new documentation! A PyROOT manual is being added to the new ROOT website, and the ROOT reference guide will contain information about the pythonizations for ROOT classes.

Try it on Binder!

[![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/stwunsch/root-dataframe-basic/master)
