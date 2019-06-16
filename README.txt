README file for Assignment 2 

Cache and Files are required for the .html. As they cache the knitr so that if the R Markdown needs to knit again then it will have cache in memory. 

Run the .html file not the .rmd. Both files will launch the code working. However, the html will run it better whereas when knitr the data is unreadable. This is how rmarkdown produces the data output

1. Animated Bar chart. Comes out small as a gif. Turned it into a ffmpeg. Ability to pause, rewind the videos. 

2. Plotly Graph, that is interactive, showing all the countries. Double click on one country to only display that country, then single click on others to add more to the view. 

3. Dygraph. Showing the average in Germany, allows to only show a sample of the year data

4. Heatmaps

4a. Regular ggplot2 heatmap just showing the blue/green/red. Blue being cold, green is 0 while red is hot.
 
4b. Interactive heatmap, allows the user to hover over certain months/year to show that specific temperature. Better overall, would use but caused other interactive plots to crash. 

5. Barplots in South Africa/Zimbabwe using ggplot2. Non-interactive. Easy to read and understand how the temperature is heating up. 