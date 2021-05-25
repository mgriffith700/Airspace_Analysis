# Airspace_Analysis
I created a jupyter notebook using Python version 3.7.9 to download a csv dataset from Airspace's github repository.  
I used python to manipulate and analyze the data, creating several new tables and graphs to visualize important data points.  
The notebook shows the methods and skills I would use to analyze, enhance, and pull useful information from a dataset.  
At several places in the notebook I printed a subset (5-10 rows) of a dataframe to prevent the whole dataset from appearing in the notebook.  
To run the notebook and generate the full dataframes, simply remove .head() from the dataframe callout.  
Example: order_count.head(10).style.hide_index().set_precision(2) -> order_count.style.hide_index().set_precision(2)  
  
Github will render a static version of the jupyter notebook here in the repository.  
To run/test the notebook either download the file from this github repo or visit:  
https://mybinder.org/v2/gh/mgriffith700/Airspace_Analysis/9a42b4e0db9603f412c66f555f6d76e368a9b246  
and click on the Airspace_Analysis.ipynb file to run it online.  

Requirements.txt is a list of python packages used in the notebook and used by binder.com to render the notebook online.
