# Elxsi - Python Package
Elxsi is a python package for performing advanced mathematical operations, distributions and visualizations and is licensed under the GNU General Public License v3.0. It includes modules for calculating mean, standard deviation and probability distribution function of various statistical distributions. The latest released stable version of elxsi is 1.0.3.

The project was started in 2021 by [Ashwin Raj](https://www.github.com/ashwinraj-in) as an academic project. The resources for the package and the pull requests are maintained and reviewed by a team of volunteers. Learn more about elxsi [here](https://pypi.org/project/elxsi/)

# Subdirectories and Constraints
### Dependencies
- Python (>= 3.9.0)
- NumPy (>=1.20.3)

### Files and Folders
The files and folders used in the package are as follows:
- [dist](https://github.com/WorkspaceDevelopers/elxsi/tree/main/dist): This subdirectory contains the source distribution for the package that needs to be uploaded to Pypi.
- [elxsi.egg-info](https://github.com/WorkspaceDevelopers/elxsi/tree/main/elxsi.egg-info): This subdirectory contains the package's metadata including PKG-INGFO and the sources.
- [elxsi](https://github.com/WorkspaceDevelopers/elxsi/tree/main/elxsi): This folder contains the source code for performing operations and visualizing statistical distributions.

**Note:**
Elxsi runs on all operating systems, is quick to install and is available for free use. No version of elxsi support Python 2.7 and Python 3.4. Elxsi plotting capabiliies requires matplotlib (>= 2.1.1) and seaborn (>= 0.9.0) packages.

# User Installation and Source Code
The latest stable release of elxsi can be installed from Pypi, using the code:
```
pip install elxsi
```
Once the package is succesfully installed, a wide array of different statistical distributions can be imported from the package by specifying the name of the distribution (seprated by ',') with first letter of each word typed in uppercase.

### Package Development
Elxsi development takes place on [GitHub](https://github.com/WorkspaceDevelopers/elxsi). Please submit any bugs that you may encounter to the issue tracker with a reproducible example demonstrating the problem, in accordance with the issue template present in /.github folder.

# Contribution
New contributors of all experience levels are welcomed to contribute to this project. Some basic information about the project has been included in this README. For major changes, it is recommended that you open an issue first (in line with the issue template) to discuss what you would like to change. Learn more about elxsi [here](https://pypi.org/project/elxsi/)

### Clone the repository
To contribute to this project, clone the repository first using the following code:
```
git clone https://github.com/ashwinraj-in/Workspace/tree/main/PandoraNLPWebApp
```
### Installing Required Libraries
Install the dependencies, present in the requirements.txt file using the below mentioned code:
```
sudo pip3 install -r requirements.txt
```
### Testing the Package
After installation, you can launch the test suite from outside the source directory (requires pytest >= 3.3.0)
```
pytest elxsi
```
View statistics for elxsi via [Libraries.io](https://libraries.io/pypi/elxsi), or by using the [public dataset on Google BigQuery](https://packaging.python.org/guides/analyzing-pypi-package-downloads/).

### Submitting a Pull Request
Before opening a Pull Request, it is recommended to have a look at the full contributing page to make sure your code complies with our pull request guidelines. Please ensure that your PR satisfies the checklist before submitting.

Pull requests are reviewed by the team on a rolling basis. If we are slow to review, either the pull request needs some benchmarking, tinkering, convincing, etc. We ask for your understanding during the review process.

# License and Project Status
The package and other resources are distributed under GNU General Public License v3.0. The package is compatible with all operating systems. The latest released stable version of elxsi is v1.0.3, available to be installed on any local system for general use through pip install from [Pypi](https://pypi.org/project/elxsi/) (and other indexes) using requirement specifiers. Checkout pip documentation v21.1.1 [here](https://pip.pypa.io/en/stable/). All commit-level changes are logged in the changelog.
