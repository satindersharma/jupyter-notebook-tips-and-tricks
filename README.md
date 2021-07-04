# jupyter-notebook-tips-and-tricks
Here you can find some jupyter notebook customized tips and tricks




### 1. Measure Cell Execution Time
##### Use `%%time` to get the elapsed time of running a cell of code.

```python
%%time
nums = [i**2 for i in range(1,1_000_000)]

```


### 2. Extensions to Jupyter Notebooks
#### Jupyter Notebook is a great tool, but a bare notebook lacks useful features. This is where the extensions kick in.
##### 1. Run the following command in the command line to install the extensions:

```bash
pip install jupyter_contrib_nbextensions && jupyter contrib nbextension install
```

##### 2. Then start a Jupyter Notebook and go to the “Nbextensions” tab:

##### 3. Activate the extensions by clicking them. These are added as buttons to the notebook toolbar:
##### For instance, use the Code Prettify extension to make your code look structured and beautiful with one click of a button:
