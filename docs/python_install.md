# Installing Python
- In order to work though this workshop, we must first install Python on your computer. There are multiple ways to install Python.
- If you already have a Python setup that you are happy with, you can continue to use that [(make sure your Python version is current).](https://www.python.org/downloads/)

- [Installing conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html#installing-conda)
- More about [Anaconda Distribution](https://www.anaconda.com/docs/getting-started/getting-started#should-i-use-anaconda-distribution-or-miniconda%3F)

## Anaconda (One way to install Python)
- Rather then installing the components separately (Python and associated materials), for this workshop we will use [Anaconda Navigator,](https://www.anaconda.com/docs/tools/anaconda-navigator/getting-started) which is an all in one installer 

**Download & Setup**
- [Download Anaconda](https://www.anaconda.com/download). Choose the version for your operating system (Windows, macOS, Linux) and install it.

- [Anaconda Navigator](https://www.anaconda.com/docs/tools/anaconda-navigator/getting-started) provides a user-friendly graphical interface for installing and working with the Python programming language. It manages packages, environments, and launching applications like Jupyter Notebook.
- [Installing Anaconda Distribution](https://www.anaconda.com/docs/getting-started/anaconda/install)
    - [Follow the directions on this page for Windows or macOS/Linux installation](https://www.anaconda.com/docs/getting-started/anaconda/install)
 <!-- During Anaconda installation, the "Add Anaconda to my PATH environment variable" option is presented, and it is not recommended by Anaconda. hen You Might Choose to Add to PATH for Convenience for Command-Line Use: If you frequently use Python commands directly from a standard command prompt or terminal (not the Anaconda Prompt), adding Anaconda to the PATH makes it easier to execute Python scripts and commands without specifying the full path to the interpreter. https://www.anaconda.com/docs/tools/working-with-conda/reference/faq#should-i-add-anaconda-to-the-windows-path & https://www.sens.buffalo.edu/software/conda -->
- After installation, open Anaconda Navigator. To start Anaconda, locate and open Anaconda Navigator from your system’s application menu or by searching for it in the Start menu (Windows) or Launchpad (macOS).
- [Python Environment Setup (Anaconda)](https://s4.ad.brown.edu/python2020/software.html) with walkthrough and images.

-- *Note:* 
- you can also use the Anaconda Prompt (Windows) or Terminal (macOS/Linux) to interact with Anaconda through the command line
- [Python from the terminal](https://southernmethodistuniversity.github.io/intro-to-python/python_ref.html#python-from-the-terminal) 

## Miniforge (Another way to install Python)
- [Miniforge](https://conda-forge.org/download/) is the preferred conda-forge installer and includes conda, mamba, and their dependencies.
- [Download and install for your system](https://conda-forge.org/download/)
- [Detailed insitructions from conda](https://github.com/conda-forge/miniforge?tab=readme-ov-file#install)
- [Detailed insitructions from The Carpentries](https://carpentries.github.io/workshop-template/#python-1)
- Conda is a [command-line (CLI) tool.](https://southernmethodistuniversity.github.io/git/commandline.html)

<!---Introduction to Conda for (Data) Scientists: Getting Started with Conda](https://carpentries-incubator.github.io/introduction-to-conda-for-data-scientists/01-getting-started-with-conda/index.html) &
[Managing conda](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-conda.html) 
## miniconda 
https://www.anaconda.com/docs/getting-started/miniconda/main * https://dublog.net/blog/so-many-python-package-managers/  https://www.datacamp.com/blog/anaconda-alternatives  https://wiki.orc.gmu.edu/mkdocs/Conda_Environments_on_Hopper/   smu https://southernmethodistuniversity.github.io/hpc_docs/examples/conda/README.html#
--->


# Jupyter Lab & Notebooks
- Now, *after installing Python,* run or install & launch Jupyter Lab. Once Jupyter Lab is open, you can now run [Jupyter](https://jupyter.org/) notebooks are documents that contain both computer code (like Python) alongside explanatory images, figures, videos, and links. Most importantly, the code in a Jupyter notebook can be executed, modified, and deleted.
- Open Jupyter Lab from Anaconda Navigator
 <img src="https://raw.githubusercontent.com/SouthernMethodistUniversity/intro-to-python/main/images/launch_jl.png" alt="Open Jupyter Lab" width="200"/>
- Many tutorial sites use these notebooks, so becoming familiar with how to launch and use them is a useful skill.

-- *Note:* 
- [JupyterLab can be installed as a terminal-launched application accessible via a web browser (default), or as a desktop application which is running in its own window and can be opened by clicking on a desktop shortcut (JupyterLab Desktop).](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)
- This means you can install Jupyter Lab through [pip or conda commands](https://jupyter.org/install) *If you installed Python using minforge or any Anaconda distribution, use the conda command.* 
- [Understanding Conda and Pip](https://www.anaconda.com/blog/understanding-conda-and-pip)
