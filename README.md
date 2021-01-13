# Euroleague-ML
The aim of this repository is to publish several Python Notebooks to see how Machine Learning (ML) can be applied to basketball-based European Datasets. Although the given examples are quite simple (build-in scikit-learn functions), I expect these models to provide coaches/analysts/GM's with concrete baseline examples. 
In particular, at the moment (January 12th 2020), three tutorials about ML gold-standards have been included:
1. **Clustering**, where K-Means is used to group similar types of shooters based on shotchart-based features. 
2. **Classification**, where SVM is used to build a model able to classify player positions. 
3. **Regression**, where linear models are used in order to predict several statistics, as well as suggesting potentially interesting players for a given lineup. 

I really hope you find it useful. If you have any questions / suggestions, feel free to send me an email (adria.arbues@upf.edu) or a Twitter DM (@arbues6).
Big shoutout also to Nacho Gámez (@ngamezj), who provided me with a notable dataset to get started. 

## Required Dependencies
All code has been written in Python (3.7); the following libraries should be installed (all of the are included in pip3):
```
pip3 install numpy
pip3 install opencv-python
pip3 install pandas
pip3 install matplotlib
pip3 install scikit-learn
```

## Other Interesting Links and Resources
- Andrew Patton's Repository "Basic NBA Tutorials": https://github.com/anpatton/basic-nba-tutorials
- Talk "Beyond the 4 Factors" with Seth Partnow, Todd Whitehead and Justin Jacobs: https://www.youtube.com/watch?v=DKv-1n5OHEc&&ab_channel=Adri%C3%A0Arbu%C3%A9s
- Some non-technical deep Euroleague reports: https://medium.com/@adria.arbues
