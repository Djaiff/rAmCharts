## LOG CHANGE

### rAmCharts 2.1.5 (based on [amcharts][amcharts_url] version **3.20.18**)

  * ``amTimeSeries`` : fix bug passing subset on ``col_series``
  * ``amHist`` : fix label precision
  
### rAmCharts 2.1.4 (based on [amcharts][amcharts_url] version **3.20.18**)

  * fix bug and add arguments on ``amTimeSeries`` 
  * Add multiple grouping on ``amBoxplot`` 
  * fix using labelRotation + xlab
  
### rAmCharts 2.1.3 (based on [amcharts][amcharts_url] version **3.20.18**)

  * fix bug on ``amTimeSeries`` with ``groupToPeriods``
  * Add control and options to export shiny
  
### rAmCharts 2.1.2 (based on [amcharts][amcharts_url] version **3.20.18**)

  * fix bug with ``addListener``
  * Shiny module to export rAmCharts on server-side
  * improve amTimeSeries (synchronization)
  * fix bug related to the languages plugins for exportation and date
  
### rAmCharts 2.1.1 (based on [amcharts][amcharts_url] version **3.20.10**)

  * fix bad interactions with the base package ``graphics``. Methods ``title()`` and ``legend()`` have become ``amTitle()`` and ``amLegend()``.
  
### rAmCharts 2.0.4 (based on [amcharts][amcharts_url] version **3.20.3**)

  * fix some ``rmarkdown`` bugs
  
### rAmCharts 2.0.3 (based on [amcharts][amcharts_url] version **3.20.3**)

  * fix ``getAmChart()`` clean using markdown
  * fix bug on ``stockpanel``
  * fix use data.frame with no checked colnames
  * new outliers treatments on boxplot + precision + fix data.frame
  
### rAmCharts 2.0.2 (based on [amcharts][amcharts_url] version **3.20.3**)

  * add ``getAmChart()`` javascript function to use and update chart within shiny
  * fix ``runExamples()`` bug
  * add ``dataLoader`` control for stock
  
### rAmCharts 2.0.0 (based on [amcharts][amcharts_url] version **3.18.3**)

  * New version available on CRAN, 
  * New functions 'am'
  * New shiny application : ``runExamples()``
  * New API

### rAmCharts 1.1.3 (based on [amcharts][amcharts_url] version **3.18.3**)

  * fix bug in markdown : now a call to method 'plot' is optionnal
  * New functions 'am'
  * fix init and rendered event with shiny
  * fix class 'Label' to allow character for properties 'x' and 'y'
  * Improve `am___` functions (histogram, scatter plot, gauge, funnel, etc.)

### rAmCharts 1.1.2 (based on [amcharts][amcharts_url] version **3.17.2**)
  
  * argument type in `amChartsOutput` is required only when `type = drill`
  * call to `plot` in shiny no longer necessary
  * better management of dependencies (dynamic loading in __R__)
  
[amcharts_url]: http://www.amcharts.com

---

### rAmCharts 1.1.1
  
  * Create a generic method for renderAmCharts (shiny use)
  * Create a show method for class AmChart (now plot the object if type is set)
  * fix bug in dependencies for html_document
  * Clean import when creating widget (plot method)
  * fix bug using renderAmChart with input/reactive values
  * rename renderAmChart -> renderAmCharts
  * rename amChartOutput -> amChartsOutput
  * add listeners on legend
  * new function 'runShinyExamples'
  * access the documentation with the functions api() or api(class = [className])
  
---

