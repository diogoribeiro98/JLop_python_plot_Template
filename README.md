# JLop Template

If you like to have full control over your plots, this is a good starting point. 

## Steps to have costumized plots

We will go step by step on how you can start to costumize your plots. In the code snipets bellow, `>`indicates the Unix like shell ( Linux or Powershell) and `>>>` denotes the python environment.

1.Install python from https://www.python.org/downloads/ and check version

```
> python --version
```

2. Install matplotlib from the command line

```
pip install matplotlib
```
3. See where the default parameters are located

```
>>> import matplotlib
>>> matplotlib.matplotlib_fname()
'C:\\Users\\your_user_name\\AppData\\Local\\Programs\\Python\\Python39\\lib\\site-packages\\matplotlib\\mpl-data\\matplotlibrc'
```
4. Go to filepath obtained and go to the folder '/stylelib'.

5. Place the file 'Jlop.mplstyle' inside this folder.

## Going further

With the knowledge above, you can start to develop more complicated styles to suit your needs. In case of doubts, always look back at the matplotlibrc file wich has all the default values of matplotlib.
