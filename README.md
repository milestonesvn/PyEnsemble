# Building Ensemble Models using Python

Workshop material for *Ensemble Models using Python*
by [Amit Kapoor](http://twitter.com/amitkaps), [Bargava Subramanian](http://twitter.com/bargava), [Nischal HP](http://twitter.com/nischalhp) and [Raghotham S](http://twitter.com/raghothams)

**Experience Level** : Intermediate

**Audience**: People with some background in Machine Learning, who want to improve model accuracy. 

**Outline**

If data is available and well-formatted (`tidy data`), it is easy to build a first-cut machine learning model. But what does it take to build a reasonably good model, or even a state-of-art model ?

Ensemble models. They are our best friends. They help us exploit the power of computing. Of course, ensemble methods aren't new. They form the basis for some extremely powerful machine learning algorithms like random forests and gradient boosting machines. The key point about ensemble is that consensus from diverse models are more reliable than a single source. This talk will cover how we can combine model outputs from various base models(logistic regression, support vector machines, decision trees, neural networks, etc) to create a stronger/better model output.

The primary goal of the workshop is to understand the answers to the following questions:

1. Why ensembles produce better output?
2. How ensembles produce better output?
3. When data scales, what's the impact? What are the trade-offs to consider? 
4. Can ensemble models eliminate expert domain knowledge?

This workshop covers various strategies to create ensemble models.

Using third-party Python libraries along with scikit-learn, this talk will demonstrate the following ensemble methodologies:

1. Bagging
2. Boosting
3. Blending
4. Stacking

Real-life examples from the enterprise world will be show-cased where ensemble models produced better results consistently when compared against single best-performing models.

There will also be emphasis on the following: Feature engineering, model selection, importance of bias-variance and generalization.

*Script to check if requisite libraries for the workshop is present*
Please execute the following command at the command prompt

    $ python check_env.py

If any library has a `FAIL` message, please install/upgrade that library.

Installation instructions can be found [here](https://github.com/rouseguy/PyEnsemble/blob/master/installation_instructions.md)

---
### Licensing

Building ensemble models using Python by <a href="https://twitter.com/amitkaps/">Amit Kapoor</a> and <a href="https://twitter.com/bargava/">Bargava Subramanian</a> is licensed under a <a rel="license" href="https://opensource.org/licenses/MIT">MIT License</a>.
