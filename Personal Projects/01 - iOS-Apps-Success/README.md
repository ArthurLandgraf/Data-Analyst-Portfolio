# Success Elements in Free Mobile Applications

## About the project

As of September 2018, there were approximately 2 million iOS apps available on the App Store. By looking at a sample of those, we'll ask the questions:

> Are there shared elements that contribute to **free** mobile application's *success*?

> Are there shared elements that contribute to **free** mobile application's *failure*?

### OBJECTIVE
By the end of this analysis we expect a graphical representation of the correlation between specific elements and the success/failure of the app. The **elements to be evaluated** are:
- App's name length & key words
- App's genre in comparision to other genres
- App's size in bytes

And the **success/failure** will be defined as a score considering:
- Absolute Rating Count
- Average Rating itself
- These measures considering both overall and grouped in genres

### FLOW STRUCTURE
Throughout this document the colors as well as title numbers (1, 2...) will indicate in which part of the flow we are. By the end you can find the summary of the findings.
1. <font color=red>**Data Cleaning**</font>: Making sure the data is properly displayed before analysis
2. <font color=purple>**Success Score**</font>: Generating the score and ranking the apps accordingly
3. <font color=orange>**Splitting Sample**</font>: Defining the borderline between Success & Failure
4. <font color=blue>**Element's Evaluation**</font>: Correlation analysis between each element and the Success score
5. <font color=green>**Conclusion**</font>: Summary of the findings


## Built With
- Jupyter Notebook
- Python

*Modules:*

- Pandas
- Numpy
- Matplotlib
- Scipy
## References

[App Store Dataset](https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps)

## Log
