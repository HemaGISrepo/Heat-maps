Heatmaps


To create a heatmap, we use folium.plugins.HeatMap(). This shows the density of crime in different areas of the city, where red areas have relatively more criminal incidents.

As we'd expect for a big city, most of the crime happens near the center.


Output:

![image](https://user-images.githubusercontent.com/118595650/202857178-57fa061b-ef89-46ed-833b-fcb56335e871.png)


As you can see in the code cell above, folium.plugins.HeatMap() takes a couple of arguments:

Data is a DataFrame containing the locations that we'd like to plot.
radius controls the smoothness of the heatmap. Higher values make the heatmap look smoother (i.e., with fewer gaps).
