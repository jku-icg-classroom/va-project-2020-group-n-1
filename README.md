# Visual Analytics Lab Project 2020/21
Submission template for the Visual Analytics lab project at the Johannes Kepler University Linz.

**Explanation:**
This `README.md` needs to be updated and pushed to github for the first and the final deadline.
Change/extend the corresponding sections by replacing the [TODO] markers.
*In order to meet the deadlines make sure you push everything to your Github repository.*
For more details see Visual Analytics [Moodle page Assignment 4](https://moodle.jku.at/jku/course/view.php?id=11328#section-7).

**Tip:** Make yourself familiar with [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## General Information
*Due on 07.12.2020.*

### Group Members

| Student ID    | First Name  | Last Name      |
| --------------|-------------|----------------|
| K11938626     | Vangel      | Paronov        |
| k0151789      | Paula       | Lun            |
| k11707630        | Johannes      | Kröpfl         |
| k1018852      | Hendrik     | Schlieper      |

### Dataset

## Our dataset is a combination of several [Gapminder](https://www.gapminder.org/data/) datasets

* Economy -> Incomes and growth -> GDP total, yearly growth
* Education -> Gender equality -> Gender ratio of mean years in school
* Environment -> Emission -> CO2 emissions per person
* Health -> New Born & Infants -> Babies per woman (total fertility)

proposal additional dataset:
* Economy -> Economic Situation -> Hourly compensation
* Economy -> Economic Situation -> Working hours per week
* Economy -> Incomes and growth -> Income
* Health -> Mental Health -> Suicide/100k people 
* Health -> Nutrition -> Food Supply
* Economy -> Poverty & Inequality -> average age of dollar billionaires
* Economy -> Poverty & Inequality -> dollar billionaires


## Usage

* descriptive statistics
* correlations between attributes
* cluster similar items

### Locally
Checkout this repo and change into the folder:

```shell
git clone https://github.com/jku-icg-classroom/va-project-2020-<GROUP_NAME>.git
cd va-project-2020-<GROUP_NAME>
```

Load the conda environment from the `environment.yml` file, if you haven't already in previous assignments:

```sh
conda env create -f environment.yml
```

Activate the loaded conda environment:

```sh
conda activate python-tutorial
```

Install Jupyter Lab extension to use *ipywidgets* in JupyterLab:

```sh
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

Launch Jupyter :

```shell
jupyter lab
```

Jupyter should open a new tab with url http://localhost:8888/ and display the tutorial files.

### MyBinder
Go to: https://mybinder.org/ and paste your repository url to work online.
MyBinder installs the dependencies specified inside of the `environment.yml` for you.

By default, it will launch to Jupyter Notebook, but you can switch to Jupyter Lab by simply appending `?urlpath=lab` to the URL.

Note: MyBinder can not save to your repository, you need to download the notebooks and update the repository yourself!

## Final Submission
*Due on 11.01.2021.*

* Make sure that you pushed your GitHub repository and not just committed it locally.
* Sending us an email with the code is not necessary.
* Please update the *environment.yml* file if you need additional libraries, otherwise the code is not executeable.
* Save your final executed notebooks as html and add them to your repository.  
  Select 'File' -> 'Export Notebook As...' -> 'Export Notebook to HTML'
