# JupyterLab &  Notebooks

Goals:
* Launch JupyterLab and create a new Jupyter Notebook.
* Navigate the JupyterLab interface, including file browsing, cell creation, and cell execution, with confidence.
* Write and execute Python code in a Jupyter Notebook cell, observing the output and modifying code as needed.
* Save a Jupyter Notebook as an .ipynb file and verify the file’s location in the directory within the session.

# Download notebooks for this workshop

* [Go to the Respository for this workshop](https://github.com/SouthernMethodistUniversity/intro-to-python)

![Github link](https://raw.githubusercontent.com/SouthernMethodistUniversity/intro-to-python/main/images/repo.png)

* Click on Code to downlaod all files, or click into Docs to downlaod individual notebooks. Notebooks are indicated by .ipynb file type.
![Download link](https://raw.githubusercontent.com/SouthernMethodistUniversity/intro-to-python/main/images/downloadrepo.png)


## Using JupyterLab to edit and run Python code.
  
### Getting started with JupyterLab
To run Python, we are going to use Jupyter Notebooks via [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/index.html).  [Jupyter notebooks](https://docs.jupyter.org/en/latest/#what-is-a-notebook) are documents that contain both computer code (like Python) alongside explanatory images, figures, videos, and links. Most importantly, the code in a Jupyter notebook can be executed, modified, and deleted. 
Jupyter notebooks let us execute and view the results of our Python code immediately within the notebook. JupyterLab has several other handy features:

- You can easily type, edit, and copy and paste blocks of code.
- It allows you to annotate your code with links, different sized text, bullets, etc.
  to make it more accessible to you and your collaborators.
- It allows you to display figures next to the code 
  to better explore your data and visualize the results of your analysis.
- Each notebook contains one or more cells that contain code, text, or images.

### Start JupyterLab using Anaconda Navigator 

While you can [install](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) and [start JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html) by using a shell command line interface, **in this workshop we will use the Anaconda Interface.** 
- You should already have Anaconda installed. If not, refer to the [Anaconda section](https://southernmethodistuniversity.github.io/intro-to-python/anaconda.html)
- To start Anaconda, locate and open Anaconda Navigator from your system's application menu or by searching for it in the Start menu (Windows) or Launchpad (macOS). 


### The JupyterLab Interface
After installation, you can launch JupyterLab either by either:
1. Launching JupyterLab from ![Anaconda Navigator home panel ](https://github.com/SouthernMethodistUniversity/intro-to-python/raw/main/images/an_panel.png "Anaconda Navigator home panel")

2. or by typing in [Bash/command line](https://southernmethodistuniversity.github.io/git/commandline.html) which will launch JupyterLab:
```
jupyter lab
```

## JupyterLab
- Launching JupyterLab opens a new tab or window in your preferred web browser. While JupyterLab enables you to run code from your browser, it does not require you to be online. If you take a look at the URL in your browser address bar, you should see that the environment is located at your localhost, meaning it is running from your computer: http://localhost:8888/lab.

- When you first open JupyterLab you will see two main panels. In the left sidebar is your file browser. 
![JupyterLab home panel](https://github.com/SouthernMethodistUniversity/intro-to-python/raw/main/images/jl.png "JupyterLab home panel")

- To work inside a specific folder, start JupyterLab from that folder in your terminal, or navigate to it inside the browser interface.
![JupyterLab navigation](https://github.com/SouthernMethodistUniversity/intro-to-python/raw/main/images/jl_nb.png "JupyterLab navigation")

- Creating a Juypter Notebook:  To the right you will see a Launcher tab. Here we have options to launch a Python 3 notebook, a Terminal (where we can use shell commands), text files, and other items. For now, we want to launch a new Python 3 notebook, so click once on the Python 3 (ipykernel) button underneath the Notebook header. You can also create a new notebook by selecting New -> Notebook from the File menu in the Menu Bar.
When you start a new Notebook you should see a new tab labeled Untitled.ipynb. You will also see this file listed in the file browser to the left. Right-click on the Untitled.ipynb file in the file browser and choose Rename from the dropdown options. Let’s call the notebook file, workshop.ipynb.

### Console 
- You can open a Console from the JupyterLab launcher. This lets you run Python commands line-by-line—similar. Just type:
```
1 + 1
```
And press Enter to see the result.

# Notebooks (Scripts)
Jupyter notebooks let you combine code, text (markdown), and output in a single document. Code cells can be executed with Shift + Enter. Each notebook is saved with a .ipynb extension.


Example Python code cell:
```
# Add two numbers
1 + 1
```
- You can also export your notebook as a PDF or .py script.

## The JupyterLab Interface

Launching JupyterLab opens a new tab or window in your preferred web browser. While JupyterLab enables you to run code from your browser, it does not require you to be online. If you take a look at the URL in your browser address bar, you should see that the environment is located at your localhost, meaning it is running from your computer: `http://localhost:8888/lab`.

When you first open JupyterLab you will see two main panels. In the left sidebar is your file browser. You should see a folder in the file browser named `data` that contains all of our data. 

### Creating a Juypter Notebook

To the right you will see a `Launcher` tab. Here we have options to launch a Python 3 notebook, a Terminal (where we can use shell commands), text files, and other items. For now, we want to launch a new Python 3 notebook, so click once on the `Python 3 (ipykernel)` button underneath the Notebook header. You can also create a new notebook by selecting *New -> Notebook* from the *File* menu in the Menu Bar.

![Launching a new Python 3 Notebook](https://raw.githubusercontent.com/SouthernMethodistUniversity/intro-to-python/main/images/0_jupyterlab_launcher.png)

When you start a new Notebook you should see a new tab labeled `Untitled.ipynb`. You will also see this file listed in the file browser to the left. Right-click on the `Untitled.ipynb` file in the file browser and choose `Rename` from the dropdown options. Let's call the notebook file, `workshop.ipynb`.

We will share more features of the JupyterLab environment as we advance through the lesson, but for now let's turn to how to run Python code.

### Running Python code 

Jupyter allows you to add code and formatted text in different types of blocks called cells. By default, each new cell in a Jupyter Notebook will be a "code cell" that allows you to input and run Python code. Let's start by having Python do some arithmetic for us. 

In the first cell type 7 * 3, and then press the <kbd>Shift</kbd>\+<kbd>Return</kbd> keys together to execute the contents of the cell. (You can also run a cell by making sure your cursor is in the cell and choosing `Run > Run Selected Cells` or selecting the "Play" icon (the sideways triangle) at the top of the noteboook.)

```python
7 * 3
```

You should see the output appear immediately below the cell, and Jupyter will also create a new code cell for you. 

```python
21
```

If you move your cursor back to the first cell, just after the `7 * 3` code, and hit the <kbd>Return</kbd> key (without shift), you should see a new line in the cell where you can add more Python code. Let's add another calculation to the same cell:

```python
7 * 3
2 +1
```

While Python runs both calculations Juypter will only display the output from the last line of code in a specific cell, unless you tell it to do otherwise.

```python
3
```

### Editing the notebook

You can use the icons at the top of your notebook to edit the cells in your Notebook:

- The `+` icon adds a new cell below the selected cell.
- The scissors icon will delete the current cell. 

You can move cells around in your notebook by hovering over the left-hand margin of a cell until your cursor changes into a four-pointed arrow, and then dragging and dropping the cell where you want it.

You can add text to a Juypter notebook by selecting a cell, and changing the dropdown above the notebook from `Code` to `Markdown`. Markdown is a lightweight language for formatting text. This feature allows you to annotate your code, add headers, and write documentation to help explain the code. While we won't cover Markdown in this lesson, there are many helpful online guides out there:
- [Markdown for Jupyter Cheatsheet (IBM)](https://www.ibm.com/docs/en/watson-studio-local/1.2.3?topic=notebooks-markdown-jupyter-cheatsheet)
- [Markdown Guide (Matt Cone)](https://www.markdownguide.org/)


![Changing a cell from Code to Markdown](https://raw.githubusercontent.com/SouthernMethodistUniversity/intro-to-python/main/images/0_jupyter_markdown_dd.png)


You can also use "hotkeys"" to change Jupyter cells from Code to Markdown and back:

- Click on the code cell that you want to convert to a Markdown cell.
- Press the <kbd>Esc</kbd> key to enter command mode.
- Press the <kbd>M</kbd> key to convert the cell to Markdown.
- Press the <kbd>y</kbd> key to convert the cell back to Code.



[jupyterlab]: https://jupyterlab.readthedocs.io/en/stable/

Summary: 
- You can launch JupyterLab from the command line or from Anaconda Navigator.
- You can use a JupyterLab notebook to edit and run Python.
- Notebooks can include both code and markdown (text) cells.



______________


Attribution
* [Python Intro for Libraries ](https://librarycarpentry.github.io/lc-python-intro/getting-started.html)

