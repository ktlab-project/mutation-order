# Mutation order probabilities for predicting clonal heterogeneity and treatment response by single-cell analysis
The landscape of mutation order probabilities in AML by single-cell DNA-sequencing. Please refer to our publication for details.


### OVERVIEW
This dipository includes codes for processing dataset into the probabilities of mutation order that clonal hematopoiesis acquire mutations to contribute leukemogenesis, as described in our original paper. In addition, the Web Application is provided.


### WEBAPP
We have created a web appilication(web app) so that you can easily adapt the results of our analysis to your own patients. This map provides the novel perspectives firstly for risk stratification, secondly for treatment strategies of pre-acquisition mutations targeting, and thirdly would for predicting treatment response. We strongly believe that if we can predict the next mutation in patients, it will lead to the risk stratification and the treatment strategies of pre-acquisition mutations targeting.

First, select the name of the gene you are interested in from the initial mutations in the upper left box. It will then display interactive table that when the selected initial gene is obtained.

Second, select the desired order in left middle box.It will then display the bar chart and table of the joint probability of acquiring the genes in that order when the selected initial gene is acquired.

Finally, when checked in left bottom box, the image of the initial gene is displayed when it is acquired. You can also download that image.

Here is the code and necessary files to use web app.


### NAVIGATION
The documentation and source code can be found at [https://github.com/ktlab-project/mutation-order](https://ktlab-project.github.io/mutation-order/)

```markdown
arviz 0.9.0
numpy 1.19.5
matplotlib 3.2.2
pandas 1.1.5
python 3.6.9
pymc3 3.10.0
R 3.6.2
seaborn 0.11.1
sklearn 0.22.2.post1
theano-pymc 1.0.11
```


### CONTACT
Please contact Principal Investigator, <ktakahashi@mdanderson.org> with any questions or suggestions.


### LICENCE
This project is under the MIT license - see the [LICENSE](https://github.com/ktlab-project/mutation-order/blob/main/LICENSE) in details.

