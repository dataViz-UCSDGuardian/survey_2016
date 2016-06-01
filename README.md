# survey_2016

###Visualizations for the UCSD Guardian Survey - UCSD Budget and Tuition Awareness

#####Files
1. `google_charts` - google pie charts with single colors
2. `google_charts_default_piechart` - google pie charts with default colors
3. `guardian_survey.ipynb` - Ipython notebook for processing data and dumping JSON
4. `output.json` - Output JSON to be consumed by Google Charts
5. `piechart_default.html` - piecharts in default colors
6. `piechart.html` - piecharts in single color
7. `processed_data.csv` - processed data for visualizing
8. `wordcloud` - generated wordcloud png

Make sure that you have matplotlib and wordcloud installed.
#####wordcloud installation
1. Use ```pip install wordcloud```
2. Or follow the instructions from their [Github Repository](https://github.com/amueller/word_cloud/) to install

#####Ipython Notebook
The JSON for the google charts is prepared from the Ipython notebook.

The piecharts from matplotlib can also be seen in the notebook to compare against the Google Charts.

#####Google Charts

```piechart.html``` contains the piecharts in a single color with the correct answer highlighted in a darker shade of the same color.

```piechart_default.html``` contains the piecharts in the default color shades as got from Google Charts.