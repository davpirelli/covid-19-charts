# covid-19-charts
Jupyter Notebook and tools to generate charts and stats related to COVID-19 spread

This notebook generates a variety of charts starting from the latest daily data regarding COVID-19, made publicly available by Johns Hopkins University (see URL reference below).

Dataframes are created in both a cumulative and an incremental fashion starting from the original data. This allows to plot them revealing a few interesting insights.

A plotting function capable of presenting data in complex ways is the core of this notebook.

You can:

- Present data from 8 aggregated Dataframe sources: Cumulative Active cases, Daily Active (new cases), Cumulative Confirmed cases, Daily Confirmed (new cases), Cumulative Recoveries, Daily Recoveries (new cases), Cumulative Fatalities, Daily Fatalities (new cases)
- There are also 3 further aggregated Dataframe sources for drawing Pie Charts: Confirmed cases, Recoveries and Fatalities. Active Cases not present here because they can (correctly) have negative values at times, being a derived quantity
- Easily filter the Dataframe Sources specifying an initial date
- Easily filter the Dataframe Sources by Country at the same time
- Combine the above 2 points
- Draw multiple line charts on the same plot
- Draw multiple bar chart on the same plot
- Draw pie charts
- Specify linear or logarithmic scale for the Y axis
- Select single or multiple Coutries as the source of data for a particular plot
- Specify if you want to keep the Country data separated (e.g. for charts comparison) or aggregated (e.g. to check global trends)
- Generate Chart Images in PNG format inside a "charts" subdirectory, together with a simple "Index.html" page to directly show the images on a browser

### Contacts:
You can contact me here:
r.lombardelli@digitalgarage.it

### Data Source Reference:
2019 Novel Coronavirus COVID-19 (2019-nCoV) Data Repository by Johns Hopkins CSSE: https://github.com/CSSEGISandData/COVID-19

### Terms of use:
Please see the Terms of Use extensively described at the above link for reference

### Disclaimer:
This GitHub repo and its contents herein, including all data, mapping, and analysis is provided to the public strictly for educational and academic research purposes. It is hereby disclaimed any and all representations and warranties with respect to the Website, including accuracy, fitness for use, and merchantability. Reliance on the Website for medical guidance or use of the Website in commerce is strictly prohibited.

### View the live Site with the latest data:
https://r-lomba.github.io/covid-19-charts/charts
