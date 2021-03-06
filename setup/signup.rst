.. _signup:

Digital Earth Africa Sandbox
============================

The Sandbox is a learning and analysis environment for getting started with
Digital Earth Africa and the Open Data Cube. It includes sample data and
Jupyter notebooks that demonstrate the capability of the Open Data Cube.

Register
--------

The Sandbox is free to use. Visit https://sandbox.digitalearth.africa/ to sign up 
for a new account, or sign in if you have an existing account. 

If registering, you must provide a username, name, email address and password, as 
presented below. A verification code will be sent to the email address you register 
with, so ensure you have access to the email you provided.

.. image:: / _static/sandbox-register-form.png
   :align: center
   :width: 250px
   :alt: Digital Earth Africa Sanbox Register Form

Access
------

After signing in, the Sandbox will prepare a JupyterLab environment for you.
All necessary software is provided as part of this environment, so no additional
installation or configuration is required. 

When accessing the Sandbox you may be provided with some Server Options, as 
presented below. Click the Start button to proceed using default Sandbox 
environment.

.. image:: / _static/sandbox-server-options.png
   :align: center
   :width: 400px
   :alt: Digital Earth Africa Sandbox Server Options

Eventually, your Sandbox environment will be initialised. As the system prepares
the environment, you should see a loading screen similar to figure below.

.. image:: / _static/sandbox-server-loading.png
   :align: center
   :width: 500px
   :alt: Digital Earth Africa Sandbox Server Loading

Once signed in, the Jupyter Lab homepage should appear as below.

.. image:: / _static/sandbox-homescreen.png
   :align: center
   :width: 600px
   :alt: Digital Earth Africa Sandbox Homescreen

Learning Jupyter
================

Overview
--------
Jupyter is an interactive coding environment. The name ‘Jupyter’ comes from Julia, Python and R, which are all programming
languages that are used in scientific computing. Jupyter started as a purely Python-based environment, called iPython, but
there has been rapid progress over the last few years.

Navigating the Jupyter Lab Interface
------------------------------------
The Jupyter Lab interface consists of several sections that require explanation. These sections are presented and explained 
below.

.. image:: / _static/sandbox-homescreen-sections.png
   :align: center
   :width: 600px
   :alt: Digital Earth Africa Sandbox Homescreen Sections

The main work area (1) enables you to arrange documents (notebooks, text files, etc.) and other activities (terminals, code 
consoles, etc.) into panels of tabs that can be resized or subdivided. Most of you work will be done here. The left sidebar (2) 
contains a file browser, the list of running kernels and terminals, the command palette, the notebook cell tools inspector, 
and the tabs list. Finally, the menu bar (3) exposes actions available in Jupyter Lab including actions related to saving, 
editing, viewing and running notebooks.

Opening a Jupyter Notebook
--------------------------

After launching JupyterLab on the Sandbox, double-click on the Beginners_guide folder in the left sidebar to view existing 
notebooks (see figure below). The Jupyter notebook files are those with the file extension ``.ipynb``. Double-click a notebook 
to open in in the main work area.

.. image:: / _static/sandbox-notebook-folders.png
   :align: center
   :width: 500px
   :alt: Digital Earth Africa Sandbox Notebook Folders

Read more about opening files in the `JupyterLab Documentation`_.

.. _JupyterLab Documentation: https://jupyterlab.readthedocs.io/en/stable/user/files.html

Working with notebooks
----------------------

For an in-depth guide on running and editing notebooks, see the `introduction to Jupyter notebooks`_ section of the Beginner's 
guide.

.. _introduction to Jupyter notebooks: ../notebooks/Beginners_guide/01_Jupyter_notebooks.ipynb

Closing a notebook
------------------

Simply closing the notebook browser tab, will not shut down its "computational engine" (called the kernel). To shut down a kernel, 
go to the associated notebook and click on menu **File -> Close and Shutdown Notebook** (see figure below). Alternatively, the 
Notebook Dashboard has a tab named Running that shows all the running notebooks (i.e. kernels) and allows shutting them down (by 
clicking on a Shutdown button).

.. image:: / _static/sandbox-notebook-close.png
   :align: center
   :width: 500px
   :alt: Digital Earth Africa Sandbox Notebook Close and Shut Down

Shutting down the Jupyter Notebook App
--------------------------------------

Closing the browser (or the tab) will not close the Jupyter Notebook App. To completely shut it down you need to close the \
associated terminal. For more information about Jupyter Notebooks, see the official Jupyter Notebook `website`_.

.. _website: http://jupyter.org/
