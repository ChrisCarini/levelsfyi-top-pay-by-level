# levelsfyi-top-pay-by-level

This repository contains information about the "Top Pay by Level" based data from [Levels.fyi](https://levels.fyi)'s "End of Year Pay Reports".

## 📣 Background

The data from Levels.fyi is a great resource for understanding the compensation landscape in the tech industry. The data is crowdsourced, and is a great way to understand what the 'market rate' is for a given role.

This repository simply takes public data from Levels.fyi's "End of Year Pay Reports" and visualizes the data in a different way for easy comparison.

## 🤝 Contributing

This repository welcomes contributions. If you have an idea for a visualization, or a different way to present the data, feel free to open an issue to start the conversation, and if you wish, a PR with the respective code change.

## 🔄 Data

The data used in this repository is sourced from Levels.fyi's "End of Year Pay Reports". The data is publicly available, and can be found at the following links:
- [2024](https://www.levels.fyi/2024/)
- [2023](https://www.levels.fyi/2023/)
- [2022](https://www.levels.fyi/2022/)
- [2021](https://www.levels.fyi/2021/)
- [2020](https://www.levels.fyi/2020/)
- [2019](https://www.levels.fyi/2019/)
- [2018](https://www.levels.fyi/2018/)

Each year a `Top Pay by Software Engineering Level` section exists, and is broken down by level of engineer - starting in 2022, additional roles in 'tech' have started to be included as well.

To generate the graphs in this repository, @ChrisCarini has gone through and collected the data from each year into `data.csv` in this repository.

## 📋 TODO

- [ ] Create a script that scrapes the data from Levels.fyi

## 📚 Notes

Below are notes for my own consumption.

1. It was a pain to figure out the name of the chart I was looking for; below are some names I came across, but none seem to be the definitive name
   1. Bump Chart
   2. Rank Chart
   3. Ranking Plot
   4. Pareto chart
   5. Slopegraph
   6. Parallel coordinate plot


### 📖 Resources

_Below is mostly a laundry list of the tabs I have open. Lots of them might be 'useful-ish' tabs that were me capturing graphs/visuals that were _semi-close_ to what I was looking for._

- https://chartexpo.com/charts/slope-chart
- https://python-graph-gallery.com/parallel-plot/
- https://python-graph-gallery.com/501-parallel-plot-seaborn/
- https://www.juiceanalytics.com/writing/parallel-coordinates
- https://www.analyticsvidhya.com/blog/2021/11/visualize-data-using-parallel-coordinates-plot/
- https://www.data-to-viz.com/graph/parallel.html
- https://en.wikipedia.org/wiki/Parallel_coordinates
- https://stephanieevergreen.com/ranking-data-in-excel/
- https://www.quanthub.com/data-storytelling-charts-for-displaying-ranks/
- https://github.com/apache/echarts
  - https://echarts.apache.org/examples/en/editor.html?c=bump-chart
  - https://echarts.apache.org/examples/en/editor.html?c=parallel-simple
  - https://echarts.apache.org/examples/en/editor.html?c=parallel-aqi
  - https://echarts.apache.org/examples/en/editor.html?c=parallel-nutrients
  - https://echarts.apache.org/examples/en/editor.html?c=scatter-matrix

_Below are some of the useful links for getting the data from Levels.fyi - they contain the HTML pages, as well as the PDFs that Levels.fyi generated._

- **_example year:_** 2023
  - https://www.levels.fyi/2023/
  - https://www.levels.fyi/assets/pdfs/2023Report.pdf
  - https://www.levels.fyi/2023/download.html