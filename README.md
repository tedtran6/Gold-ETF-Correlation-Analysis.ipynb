# Gold-ETF-Correlation-Analysis.ipynb
This is a python analysis of correlating gold ETFs in the stock market. An HTML file is provided for interactive charts.
The gold ETFs used were JNUG, JDST, NUGT, DUST, and GLD.

## Exchange Trade Funds
An Exchange Traded Fund (ETF) is a security that tracks a stock index. These securities are regularly traded like regular stock on the market. 

  **NUGT:** Direxion Daily Gold Miners Index Bull 3X Shares. This is a 3x leveraged bet on the Arca Gold Miners Index.
  
  **JNUG:** Direxion Daily Junior Gold Miners Index Bull 3X Shares This is a 3x leveraged bet on the Market Vectors Junior Gold Miners Index. 
  These are often more small cap firms.
  
  **NUGT:** Direxion Daily Gold Miners Index Bear 3X Shares. This is an inverse 3x leveraged bet on the Arca Gold Miners Index.
  
  **JNUG:** Direxion Daily Junior Gold Miners Index Bear 3X Shares. This is an inverse 3x leveraged bet on the Market Vectors Junior Gold Miners Index.
  These are often more small cap firms.

## Notes
This is not a trading strategy, it's just an analysis on the correlation between some stocks.

I used the plotly library to create my charts.

below are some photos of the charts created.

<img src = "images/image1.png" width = "900">

The following two charts show correlation information between all the ETFs on in the dataframe. Of course, when comparing to itself, correlation would be 1. Also, when comparing a stock to its corollary like JNUG and NUGT, as well as JDST and DUST, the correlation would be high too. A lot more of the analysis comes from seeing the correlation that these ETFs have with GLD.

<img src = "images/image2.png" width = "900">
<img src = "images/image3.png" width = "900">


<p float="left">
  <img src = "images/image4.png" width = "430">
  <img src = "images/image5.png" width = "430">
</p>

<img src = "images/image6.png" width = "500">
