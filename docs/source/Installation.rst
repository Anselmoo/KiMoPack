Installation
=============

The basis of the program is a module called "plot_func.py" that contains all the necessary functions and classes. 
We provide a series of jupyter based work flow packages that guide the user through a series of typical tasks 
during the analysis of optical transient absorption data and that we strongly recommend.
The files can be downloaded from the github directory https://github.com/erdzeichen/KiMoPack and manually installed (added to the path).
Alternatively we recommend the usage of the usual python install commands "pip" or if the distribution is using the Anaconda
package manager, The conda type installation. For both please open a command line (e.g. using "cmd" in windows) and execute the following commands. 
The Jupyter notebooks are copied during the install process. The notebooks can also be downloaded from the github server https://github.com/erdzeichen/KiMoPack.

Install using "pip":

.. code-block:: text

    $ pip install KiMoPack 

Upgrade if already installed:

    $ pip install KiMoPack -U

Install and update using "conda" from the channel erdzeichen:

.. code-block:: text

    $ conda install -c erdzeichen kimopack

Best usage
-----------
While KiMoPack is a python library, we facilitate its use with Jupyter notebooks. For the typical analysis tasks we have developed a series of Notebooks that guide through the tasks.\n These notebooks can be found in the installation folder under "Workflowtools" or can be downloaded from https://github.com/erdzeichen/KiMoPack/tree/main/Workflow_tools. Please copy one of these notebooks into your data analysis folder and rename them to create a analysis log of your session. For more information please see the publication https://doi.org/10.1021/acs.jpca.2c00907, the tutorial videos, or the tutorial notebooks under https://github.com/erdzeichen/KiMoPack/tree/main/Tutorial_Notebooks_for_local_use. 

Convenient use and documentation
------------------------------------
The notebooks mentioned above are also excellent analysis protocolls, if they are copied for each new analysis. The recommended use is, copy you favourite notebook close to your data, rename it  and then open it for you analysis. This goes most comfortable by using the module nbopen, that can be integrated into the file manager following the instructions on this webpage: https://pypi.org/project/nbopen/

Under windows this would be:

.. code-block:: text

    $ pip install nbopen
	$ python -m nbopen.install_win

Links
-----

	* Documentation: https://kimopack.readthedocs.io/
	* PyPI Releases: https://pypi.org/project/KiMoPack/
	* Source Code: https://github.com/erdzeichen/KiMoPack
	* Issue Tracker: https://github.com/erdzeichen/KiMoPack/issues
	* Website: https://www.chemphys.lu.se/research/projects/kimopack/
	* Publication: https://pubs.acs.org/doi/10.1021/acs.jpca.2c00907
	* Zenodo: https://doi.org/10.5281/zenodo.5720587

