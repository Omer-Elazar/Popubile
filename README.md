<center> Popubile </center>

<br><br>
<font size="5"> <center> HIT<br>
“Introduction to data science” final project<br><br>
By Omer Elazar

Full implementation:
https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb


## Tabel of contents

### <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#abstract">Abstract</a>


### <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#ImportingLibraries">Importing Libraries</a>


### <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#dataAcquisition">Data Acquisition</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#ScrapingGSMArena">Scraping GSMArena</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#Gettingbrandcountries">Getting brand countries</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#GettingUSDexchangerates">Getting USD exchange rates</a>

### <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#DataCleaning">Data Cleaning</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#Extractingnumericdata">Extracting numeric data</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#Addingcountrycolumn">Adding country column</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#Handlingmissingvalues">Handling missing values</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#Dealingwithoutliers">Dealing with outliers</a>


### <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#Eda">EDA</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#CatagoricalPlots">Catagorical Plots</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#Maps">Maps</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#CorrelationMatrix">Correlation Matrix</a>


### <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#MachineLearning">Machine Learning</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#PreparingTheData">Preparing The Data</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#ComparingTheModels">Comparing The Models</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#HyperparameterTuning">Hyperparameter Tuning</a>
 - <a href="https://nbviewer.org/github/Omer-Elazar/Popubile/blob/main/Popubile.ipynb#FinalEvaluation">Final Evaluation</a>




## Abstract

Can you predict the popularity (hits and fans on GSMArena) of a phone knowing its brand and technical specification ?
What makes one phone gain more attention than others? Is the brand and technical specification enough to know how popular a phone will be?

In this project I try to ansewr these questions by scraping data on 11,000 phones from GSMArena and implementing machine learning methods to try and predict the number of hits and fans a phone will get.
