## Team DiamondHands 
### Welcome to our [team project website!](https://julioveracruz.github.io/testwebsite/)

This is a website to showcase our analysis of research directed at determining possible correlations between Bitcoin and a variety of other cryptocurrencies.
(In pursuit of our final project for FIN 377 - Data Science for Finance at Lehigh University)

To see the complete analysis file(s) click [here](https://github.com/julioveracruz/testwebsite/blob/main/notebooks/example.ipynb).

Maybe you want a different website them for the project? Consider `minimal-mistakes`:
1. [Go here](https://github.com/mmistakes/mm-github-pages-starter/generate).
2. In the resulting repo, click Settings, then Pages, then make sure the source is the main branch.
3. [The doc site is here](https://mmistakes.github.io/minimal-mistakes/docs/structure/) and will help you customize layouts and figure out how to use it.

## Table of contents
1. [Introduction](#introduction)
2. [Methodology](#meth)
3. [Section 2](#section2)
    1. [Subsection](#subsec2-1)
    2. [Subsection](#subsec2-2)
4. [Analysis Section](#section3)
5. [Summary](#summary)
6. [About Us](#AtT)

## Introduction  <a name="introduction"></a>

The main goal of this project is to explore potential price movement correlations between Bitcoin and a variety of other cryptocurrencies.
This research aimed to predict price movement using two primary indicators:
    1. Leading Indicators
    2. Lagging Indicators
    
## Methodology <a name="meth"></a>

Here is some code that we used to develop our analysis. Blah Blah. [More details are provided in the Appendix](page2).
 
Note that for the purposes of the website, you have to copy this code into the markdown file and  
put the code inside trip backticks with the keyword `python`.

```python
import seaborn as sns 
iris = sns.load_dataset('iris') 

print(iris.head(),  '\n---')
print(iris.tail(),  '\n---')
print(iris.columns, '\n---')
print("The shape is: ",iris.shape, '\n---')
print("Info:",iris.info(), '\n---') # memory usage, name, dtype, and # of non-null obs (--> # of missing obs) per variable
print(iris.describe(), '\n---') # summary stats, and you can customize the list!
print(iris['species'].value_counts()[:10], '\n---')
print(iris['species'].nunique(), '\n---')
```

Notice that the output does NOT show! **You have to copy in figures and tables from the notebooks.**

## Section <a name="section2"></a>
Blah blah

### Subsection 1 <a name="subsec2-1"></a>
This is a subsection, formatted in heading 3 style

### Subsection 2 <a name="subsec2-2"></a>
This is a subsection, formatted in heading 3 style

## Analysis Section <a name="section3"></a>

Here are some graphs that we created in our analysis. We saved them to the `pics/` subfolder and include them via the usual markdown syntax for pictures.

![](pics/plot1.png)
<br><br>
Some analysis here
<br><br>
![](pics/plot2.png)
<br><br>
More analysis here.
<br><br>
![](pics/plot3.png)
<br><br>
More analysis.

## Summary <a name="summary"></a>

Blah blah



## About the Team <a name="AtT"></a>
---
### Harrison Sneddon
#### [LinkedIn](https://www.linkedin.com/in/harrison-sneddon/)

<img src="pics/HTS_LKDIN.jpg" alt="Harrison" width="300"/>
<br>
Harrison is a senior at Lehigh University studying finance and international economic relations.

- Current Employer: Analyst, Raymond James & Associates
- Career Track: Investment Banking, M&A. Industrial Technologies and Tech Enabled Services.
---       
### Theo Faucher
#### [LinkedIn](https://www.linkedin.com/in/theo-faucher-b98581173/)

<img src="pics/Theo LKDIN.jpg" alt="Theo" width="300"/>
<br>
Theo is a senior at Lehigh University studying finance and economics.

- Current Employer: Analyst, Cadent Consulting Group
- Career Track: Strategy Consulting
---
### Ian Rosen
#### [LinkedIn](https://www.linkedin.com/in/ianrosenr/)

<img src="pics/IAN LKDIN.jpg" alt="Ian" width="300"/>
<br>
Ian is a junior at Lehigh University studying finance and computer science.

- Current Employer: Summer Analyst, Stifel Financial
- Career Track: Diversified Institutional Advisory Services
---





To view the GitHub repo for this website, click [here](https://github.com/donbowen/teamproject).
