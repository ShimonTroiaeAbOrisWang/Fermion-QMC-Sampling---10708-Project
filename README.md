# Nota bene (updated May 1 2022):

One important thing was missing from our final report. The "observable" we calculate is the average magnetization

<img src="https://render.githubusercontent.com/render/math?math=\mathcal{M}(\phi) =  \int \phi(x) d x.">

After discretization, it is approximated by

<img src="https://render.githubusercontent.com/render/math?math=\mathcal{M}(\phi) = \frac{1}{L \dotplus 1}\sum_{x=0}^L \phi(x).">


(We mentioned this in our midway report, but forgot to do so in the final report. We are sorry if this has caused some confusion when our project is being reviewed.)

-----
There is a typo in our final report. In Section 4.2, the "<img src="https://render.githubusercontent.com/render/math?math=S_{\mathrm{PF}}(\phi, \varepsilon)">" should be changed to "<img src="https://render.githubusercontent.com/render/math?math=S_{\mathrm{PF}}(\phi, \varphi)">".


# Fermion QMC Sampling (10708-Project)

This repository houses the codes of the course project for 10708 Probabilistic Graphical Models, Spring 2022 at Carnegie Mellon University.

The project is jointly done by Hongjian Wang and Andrew Smith.

To reproduce all the experiments in our final report, simply upload the file `10708_project.ipynb` into [Google Colab](https://colab.research.google.com/). Please see the code comments and the text blocks for detailed instruction.

If other environment, like the Jupyter Notebook, is used, simply remove all occurences of the following file IO scripts:
```
from google.colab import files
files.download("blahblahblah.pdf")
```
