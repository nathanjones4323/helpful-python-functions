# helpful-python-functions
These are a collection of python functions that I created and found helpful as I came across generalizable problems.

File Structure
* `functions` contains all the python code for defining each function. They are of the format `{function_name}.py`
* Each function contains all the required dependencies. They are of the format `{function_name}_requirements.txt`

## Interactive Folium Choropleth
`interactive_choropleth()`
* Function to create more interactive choropleths in Folium (Actually `folium.GeoJson`)
* `folium.Choropleth` has limited customizations and tooltips are not friendly.
* We can step around these problems by implementing a custom function to interact with `folium.GeoJson` and create the same effect as `folium.Choropleth` with more interactivity and better tooltips.

### [Example Usage](https://nbviewer.org/github/nathanjones4323/helpful-python-functions/blob/main/functions/folium/choropleth/interactive_choropleth_notebook.ipynb)

### TODO
* Submit a PR to the `python-visualization/folium` repository
