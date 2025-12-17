# Richie 'Rinehart' Club
We present our central data-driven argument and thus 'call to arms': the status-quo is completely broken and needs disrupting. We present some introductory Data Science learning below, hopefully the power of the internet allows it to get to those that are less fortunate to get such _highly valued_ education. 

> [!NOTE]
> If you have any issue doing the following steps, please [let us know about your issue](https://github.com/TessellateDataScience/RichieRinehartClub/issues).

## Get started
[Python](https://realpython.com/)-based environment leveraging computational & visualisation modules such as Scipy & Numpy, and Matplotlib. All wrapped-up and ready-to-roll using Docker:
1. [Install Docker](https://docs.docker.com/get-started/)
2. Download our [base notebook](https://github.com/TessellateDataScience/RichieRinehartClub/blob/main/rich.ipynb) into a directory where Docker will see it. On Windows use the Terminal app: `cd \Users\username\richie`
3. Download the functioning environment for current [JupyterLab](https://jupyterlab.readthedocs.io/en/latest/) notebook: `docker pull nchowlett/data-science:0.1`

## Run enviroment
1. Start computational environment: `docker run -it -v "$(pwd):/home/jovyan/work" -p 8888:8888 nchowlett/data-science:0.1`
2. Paste the 'localhost' URL into your web browser.
3. Navigate to notebook via clicking on 'work' directory in left side.
4. Shutdown environment: `Ctrl + c`
