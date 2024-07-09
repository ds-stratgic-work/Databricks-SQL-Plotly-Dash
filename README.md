# Databricks-SQL-Plotly-Dash
Dash is a python framework developed by plotly to build interactive web applications. It is built on top of Flask, Plotly.js, and React.js. With Dash, there is no need to master HTML, CSS, and Javascript to create interactive dashboards; only python is required. Dash is an open-source framework, and applications created using it can be accessed through a web browser.

### Requirements:
- A Databricks workspace with Databricks SQL enabled

### Building Blocks
Dash applications consist of two main components: 
-Layout and 
- Callbacks.

## Install some required packages
! pip install dash   
! pip install dash-html-components                                         
! pip install dash-core-components                                     
! pip install plotly
!pip install databricks-sql-connector
!pip install sqlalchemy       ### A demonstration of how to extract information from Databricks using the SQLAlchemy engine and save it into Parquet files.


## Conclusion
While working with large-scale time-series data visualization, the Plotly Resampler's functionalities truly work out, especially when paired with Databricks ecosystems. It's not just the capacity to manage extensive datasets that sets it apart, but also its distinctive interactive features. These, combined with extensive customization choices and significantly improved performance, establish it as an essential tool for individuals working with expansive time-series data.

Although Datashader is praiseworthy, particularly for its innovative rasterization methods and integration with Bokeh, it may not offer the same level of user-friendly interactivity as the Plotly Resampler. This distinction makes the latter the preferred option for industrial IoT time-series scenarios.

Moreover, the incorporation of Polars into the Resampler's workflow enhances the rapid advancement and flexibility of the data science toolkit.




### Technologies and Libraries
Python 3.9
Jupyter Notebook


