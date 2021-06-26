# Plotly
Visualization using Plotly in python offline
<br/> Used plotly library to visualize geographical data 
* Links that can be helpful - 
    * about plotly usage - [click here](https://plotly.com/python/renderers/)
    * cheat sheet for data visualization - must see very useful [click here](https://images.plot.ly/plotly-documentation/images/python_cheat_sheet.pdf)
    * Info about color scales and how to create one - [click here](https://plotly.com/python/colorscales/)
   
# Dataset
Dataset was collected from random sources to download dataset either click on it copy paste to a new csv file <br/>
or clone this repository by first going to a specific path and then using <br/>
```
git clone https://github.com/amey16/Plotly.git
```

# Extra Info
To build a data dictionary easiest way to do this is to use the dict() function of the general form: <br/>

type = 'choropleth', <br/>
locations = list of states <br/>
locationmode = 'USA-states' <br/>
colorscale= Either a predefined string:<br/>
'pairs' | 'Greys' | 'Greens' | 'Bluered' | 'Hot' | 'Picnic' | 'Portland' | 'Jet' | 'RdBu' | 'Blackbody' | 'Earth' | 'Electric' | 'YIOrRd' | 'YIGnBu'
<br/>
text= list or array of text to display per point<br/>
z= array of values on z axis (color of state)<br/>
colorbar = {'title':'Colorbar Title'})
