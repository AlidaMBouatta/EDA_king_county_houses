# First DS-EDA prject : King County - Eric Robinson 
## <span style="color:black"> __What is the project about__ </span>
<span style="color:grey">
This EDA project is about finding the best houses for clients with specific needs and requirements. This is done by looking through a set of data given by DS- SPICED. 
My client is Eric Robinson, his requirements are:
* <span style="color:grey"> Investing in "Poor neighborhood".
* <span style="color:grey"> Buying for selling. 
* <span style="color:grey"> He would like a bit of profit. 

##  __In this repository:__
* <span style="color:grey"> Fetching the data.
* <span style="color:grey"> EDA project 
* <span style="color:grey"> README File. 

##  __How to analyze?__
<span style="color:black">
I fetch the data via SQL.

The raw data are:

df_king_county_house_sales.csv that shows all the houses available.

df_king_county_house_details.csv that shows details of each house.



Order of operation:

1_ : this file fetch data and saves raw csv and left joins to file: 


2_: this is the main analysis: Includes filtering, plots and results

To analyze the data, I started by looking at the price per square lot and square living, then a correlation matrix between the price and other parameters. From there I used boxplots to look at the spread of the data, and using it to determine the poor neighborhood by taking the zipcodes under the mode of the price per square lot. Having the location set, I filtered the data set to keep only houses between the grade 7 and 9. Those grades are still in a good price range. As the year where the houses were built do not have a strong impact on the price, I looked only for the houses that are in a perfect condition, which means that no renovations are needed, so Eric will not loose money. The top 3 houses give him a good profit. 


##  __Packages needed__
<span style="color:black">

| Package        | Version |
|----------------|---------:|
| folium         | 0.17.0  |
| geopy          | 2.4.1   |
| jupyter_client | 8.6.2   |
| jupyter_core   | 5.7.2   |
| kiwisolver     | 1.4.5   |
| MarkupSafe     | 2.1.5   |
| matplotlib     | 3.9.1   |
| missingno      | 0.5.2   |
| numpy          | 1.26.4  |
| pandas         | 2.2.2   |
| scipy          | 1.14.0  |
| seaborn        | 0.13.2  |
| SQLAlchemy     | 2.0.31  |
