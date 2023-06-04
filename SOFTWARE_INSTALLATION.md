# Table on content

- [Recommendation for Python install](#python)
    - [Mac](#mac)
    - [Linux](#linux)
    - [Windows](#windows)
    - [Library requirements](#python-req) 
- [Jupyter](#jupyter) 
- [astroML installation](#astroML)



# Recommendation for Python install <a name="python"></a>

You must install Python 3.7 and a few Python libraries. The recommended way to do so is to use
[Anaconda](https://www.anaconda.com/distribution/). The procedures described bellow will help you install what is needed for the school.

## Mac <a name="mac"></a>
On Mac OS X, `X11/XQuartz` will have to be installed, in addition to the software mentioned above.

All instructions below assume that the bash shell is used, as it is the default shell on Mac OS X. (Adapt instructions accordingly if you changed your default shell.)

1. [Download](https://www.anaconda.com/distribution/) `Anaconda3-2019.07-MacOSX-x86_64.pkg` (or a very similar name, adapt instructions accordingly) the Mac `Anaconda` installer for Python 3.7.
For Mac OS X 10.7 (Lion), 10.8 (Mountain Lion), or 10.9 (Mavericks), pick "Mac OS X — 64-Bit Python 3.7 Graphical Installer".
If you have Mac OS X 10.6 (Snow Leopard), you may use an older version of anaconda.

2. Double-click to install, and be sure to leave the default "Modify PATH" option.
Most of the necessary python modules already come by default with Anaconda: `numpy`, `matplotlib`, `scipy`, `scikit-learn`.

3. See next section for extra Python libraries requirements (if any).

4. **Test the installation:**

  - Launch python:
  
  		python

   This should start python, and the version should mention Anaconda.
   Exit with Control-D.
   
  - Launch ipython:
  
  		ipython
   This should start ipython, and the version should mention Anaconda.
   Exit with Control-D.
   
  - Launch ipython notebook:
  
  		ipython notebook
   This should open your default browser, and present you with a .
   Exit by closing the page (in the browser) and with Control-C (in the terminal).
   Note: When the OS language is not English, ipython notebook may crash with the error *"ValueError: unknown locale: UTF-8"*.
   In that case, before launching ipython notebook, type:
   ```export LC_CTYPE=en_GB.UTF-8```

  - Launch python and test the different modules:
  
  		import numpy
  		print numpy.__version__
  		import matplotlib
  		print matplotlib.__version__
  		import scipy
  		print scipy.__version__
  		import sklearn
  		print sklearn.__version__
  		


## Linux <a name="linux"></a>
All instructions below assume that the bash shell is used; adapt instructions accordingly if you use a different shell.

1. [Download](https://www.anaconda.com/distribution/) `Anaconda3-4.3.1-Linux-x86_64.sh` (or a very similar name, adapt instructions accordingly) the Linux `Anaconda` installer for Python 3.7.

2. Run the following command line:

		bash Anaconda3-2019.07-Linux-x86_64.sh
3. Type yes and press enter to approve the license.

4. Press enter to approve the default location for the files.

5. Answer `yes` to the following question to prepend Anaconda to your PATH (this makes the Anaconda distribution the default Python).
	
		Do you wish the installer to prepend the Anaconda3 install location
		to PATH in your /home/chotard/.bashrc ? [yes|no]
	
 Most of the necessary python modules already come by default with Anaconda: numpy, matplotlib, scipy, scikit-learn.

6. See next section for extra Python libraries requirements (if any).
7. **Test the installation:** 

   - Launch python:

			python

   - This should start python, and the version should mention Anaconda.
     Exit with Control-D.
   - Launch ipython:

  			ipython

     This should start python, and the version should mention Anaconda.
     Exit with Control-D.
   - Launch ipython notebook:
		
  			ipython notebook
 		
     This should open your default browser, and present you with a .
     Exit by closing the page (in the browser) and with Control-C (in the terminal).
   - Launch python and test the different modules:

  		import numpy
  		print numpy.__version__
  		import matplotlib
  		print matplotlib.__version__
  		import scipy
 		print scipy.__version__
  		import sklearn
 		 print sklearn.__version__




## Windows <a name="windows"></a>

1. Download [here](https://www.anaconda.com/distribution/) `Anaconda3-2019.07-Windows-x86_64.exe` (or a very similar name, adapt instructions accordingly) for the installation of Anaconda. 

2. Install Anaconda following the wizard and accepting all the defaults.
Most of the necessary python modules already come by default with Anaconda: numpy, matplotlib, scipy, scikit-learn.

Once installed, you can run `Anaconda navigator`. To run Jupyter, on the main page of the Anaconda navigator, click on `Launch` on the Jupyter notebook box. This will open your favorite browser. From there, you can either load a notebook (e.g. from the Git folder) or create a new notebook by clicking `new -> Python 3`. 

You can also install a Git tool for Windows: [Git for Windows](https://git-for-windows.github.io/). Launch `Git GUI` or `Git bash` to get started. 


## Library requirements <a name="python-req"></a>

All the required libraries come with the `Anaconda` install described
above. If you have followed the previous steps to install Python, you
can skip this section.

If you choose an other way to install Python 3.6 than the one
recommended above, you must install manually the Python libraries
listed in the [requirements.txt](requirements.txt) file. To do so, we
recommend using `pip`.

	  pip install -r requirements.txt

# Jupyter <a name="jupyter"></a>

To launch a Jupyter notebook, simply run the following command:

`jupyter notebook`

On Windows, see in the [above](#windows).
 

# astroML installation <a name="astroML"></a>
 
[Follow this link for astroML installation](https://www.astroml.org/user_guide/installation.html) 

To test your astroML installation, execute testInstallation.ipynb (you can find it in the top directory) as
> 'jupyter notebook testInstallation.ipynb'

and run all cells.








