## Notes  

*following our Feb 21, 2018 meeting*  

## Question:  
 
Can we predict groundwater quality (TDS) in the Tulare Basin?  

## Hypothesis:  

Machine learning approaches (boosted tree regression models & Neural Nets) are computationally efficient methods to predict groundwater quality.  

## Approach:  

Use:  

* geology (USGS - Rich)  
	+ or perhaps what is mined this summer from the DWR well completion reports  
* socioeconomic data, i.e.- county/tract level Median AGI ([tidycensus](https://walkerke.github.io/tidycensus/articles/spatial-data.html) - Rich)   
* land use  

* Satellite data (Aakash):  
	+ crop production/NDVI  
	+ precipitation  
		+ more precip might flush out contaminants from shallow gw

		
To Predict:  

* TDS data in Rich's shiny web app.  


## Limitations  

Machine learning approaches can adequately assess groundwater quality, but might fail to capture long-term trends in groundwater quality deterioration or improvement.  
