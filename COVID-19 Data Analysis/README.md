In this project, we analyzed a sample dataset of global COVID-19 cases using Python libraries like Pandas, Matplotlib, and Seaborn. The dataset included key fields such as Date, Country, Confirmed, Recovered, and Deaths. After parsing dates and cleaning the data (e.g., dropping missing values), the dataset was grouped by country and date to compute cumulative statistics.

To visualize the pandemic's progression globally, we first plotted cumulative line charts of confirmed, recovered, and death cases over time. This clearly illustrated the spread and eventual stabilization of cases. Next, an area chart was used to compare the three categories in a more layered view, emphasizing the difference in scale between them.

We then calculated daily new cases for each country and created a heatmap to show how these new cases varied across different dates and nations. This heatmap made it easy to spot surges or declines in specific regions. Lastly, to compare the situation in major countries, we filtered for India, United States, and Brazil, and plotted their confirmed case curves side by side—helping to highlight regional differences in the pandemic timeline.

Overall, the analysis provided a comprehensive and visual overview of COVID-19 trends both globally and by country.

