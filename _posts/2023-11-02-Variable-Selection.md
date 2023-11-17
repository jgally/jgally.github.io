## Variable Selection For Regression  

Regression modeling is no easy task, especially for beginners. Throughout the readings there was one quote that soothed my inexperienced anxiety of variable selection for regression modeling, "Statisticians build at-risk accurate and stable models, either unknowingly using these unconfirmed methods or knowingly, because they do not know what to do"<sup>[3](https://link.springer.com/content/pdf/10.1057/jt.2009.26.pdf)</sup>. Hopefully this quote can ease the minds of other budding staticians as they dive into modeling regressions. There are many aspects of the variables and the selection techniques that must be taken into account. In our last homework we worked with forward elimination, backward elimination, and subetting selection as well as criterion-based selection like Akaike Information Criterion (AIC) and the Bayes Information Criterion (BIC). Forward and backward selection is easy enough to code, but comes with many downfalls. One of those being with every addition or removal of a variable in a specified order can create an opportunity where the "best" fitting model could be missed<sup>[2](https://www.biostat.jhsph.edu/~iruczins/teaching/jf/ch10.pdf)</sup>. Another issue with these types of modeling is evaluating the p-value and what is causing the p-value to be what it is. I am not experienced enough to recognize how the values are changed with the addition or removal of variables so this seems like a big uncertainty with these techniques. With criterion selection the code is a little more difficult for me, but the red flags of AIC or BIC are not as red as those of forward and backward elimination. I prefer AIC and BIC because these techniques seem more efficient as they evaluate models that are most likely to be the "best" fit rather than going through each combination of variables<sup>[2](https://www.biostat.jhsph.edu/~iruczins/teaching/jf/ch10.pdf)</sup>. AIC is built for bigger models and BIC covers the smaller models. While The RSS still must be evaluated there seems to be less uncertainty than the forward and backwards elimination selections. With a good EDA to show collinearity and possible variable symmetry, criterion-based selection is my preferred technique of variable selection. 

Reading Resources: 

[1. National Library of Medicine](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5969114/)  
[2. Chapter 10](https://www.biostat.jhsph.edu/~iruczins/teaching/jf/ch10.pdf)  
[3. A Closer Look](https://link.springer.com/content/pdf/10.1057/jt.2009.26.pdf)