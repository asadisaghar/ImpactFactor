# Impact Factor and the power-low tail of citations

[![DOI](https://zenodo.org/badge/21629/hamed/ImpactFactor.svg)](https://zenodo.org/badge/latestdoi/21629/hamed/ImpactFactor)

I pulled the data of [A simple proposal for the publication of journal citation distributions](http://dx.doi.org/10.1101/062109) and produced probability density function using geometric bins. The result is:

![pdf](https://raw.githubusercontent.com/hamed/ImpactFactor/master/fig/pdf.png)

They have power-law tails, so I belive the suggestion of [Time to remodel the journal impact factor](http://www.nature.com/news/time-to-remodel-the-journal-impact-factor-1.20332) is a good quick fix. 
If we replace mean with median in the definition of impact factor, I think it has a better interpretation. If you publilsh an article in Nature, there is 50% chance that it get more than 24 citation in two years time. 

For more details about math and methods, please see the [source file](https://github.com/hamed/ImpactFactor/blob/master/src/ImpactFactor.ipynb).
