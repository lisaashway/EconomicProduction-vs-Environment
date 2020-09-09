# EconomicProduction-vs-Environment


In this reposistory, you will find the pages of a website which uses data to visualize how pollution into the atmosphere changes based on economic producitivity in the United States. It can be found here! 
https://lisaashway.github.io/EconomicProduction-vs-Environment/

This website uses python's pandas and matplotlib libraries, jupyter lab notebooks, bootstrap, 
This site uses Bootstrap to display plots and dataframes created from python's pandas and matplotlib libraries. 

Below is a description of each folder and file in this repository:

        Index.html:
         The landing page of the website
    
        WebVisualizations folder:
            -assets folder:
                -styles.css: style sheet for custom visual effects on the site, including media queries to change the colors of the site depending on the window                       size
        
        comparisons.html:
            This is the webpage that displays all data visualizations side by side
            
        data.html:
            This is a webpage that displays the cleaned data used for the visualizations using a bootstrap table class
            
        plot1.html, plot2.html, plot3.html, plot4.html:
            These pages display each data visualization with a brief analysis of the plots

        Resources folder:
            -Pollution_2005_2016.csv: original cleaned pollutant data from EPA
            -stateemployment_monthly.csv: original unemployment data from US Bureau of Labor Statistics
            -CombinedData.csv: the cleaned csv that was used for the visualizations, which is created inside the Unemployment and Pollutant Charts python fole
            -Unemployment and Pollutant Charts.py: a python file that cleans and restructures the data, creates the visualizations, and exports the Combined csv                        using Pandas and Matplotlib Libraries
            -to_html.ipynb: a jupyter lab notebook that uses combineddata.csv to export the csv to an html table.
            -table.html: this table is created from to_html.ipynb and is pasted into the data.html page on the site
            
        visualizations:
            CO.png, NO2.png, O3.png, and SO2.png are the visualizations created in the Unemployment and Pollutant Charts python file using pandas and matplotlib                        libaries, and are displayed in the webpages of plot1, plot2, plot3, and plot4
        
