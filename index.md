Ken Furudate  2021-02-05

## Welcome to our analysis
Here's how we analyzed the data in the [manuscript](https://github.com/ktlab-project/mutation-order).

### Web appilication
We have created a web appilication(web app) so that you can easily adapt the results of our analysis to your own patients. We strongly believe that if we can predict the next mutation in patients, it will lead to the risk stratification and the treatment strategies of pre-acquisition mutations targeting.


- First, select the name of the gene you are interested in from the initial mutations in the upper left box. It will then display interactive table that when the selected initial gene is obtained.

- Second, select the desired order in left middle box.It will then display the bar chart and table of the joint probability of acquiring the genes in that order when the selected initial gene is acquired.

- Finally, when checked in left bottom box, the image of the initial gene is displayed when it is acquired. You can also download that image.

Here is the code and necessary files to use web app.

### Navigation
This contains the code that accompany the manuscript. This codes were written in notebook(.ipynb) using Python and R.

```markdown
numpy 1.19.5
matplotlib 3.2.2
pandas 1.1.5
python 3.6.9
R 3.6.2
seaborn 0.11.1
sklearn 0.22.2.post1
```

### Contact
Please contact Principal Investigator, <ktakahashi@mdanderson.org> with any questions or suggestions.

### Reference
- Lane, T., & DuMouchel, W. Simultaneous Confidence Intervals in Multiple Regression. The American Statistician 48, 315-321(1994).
