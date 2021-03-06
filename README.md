# get_bus_info
Download bus line from the Internet

This repo show you how to download bus line and bus station based on map providers (such as amap, in this case). They can be used for bus operation analysis and many potential applications.

**Step 1**: Open the map website and the "Developer Mode" (Chrome recommended)

**Step 2**: Switch to `Network/All/Preview`,  then search for your expected bus line 

<img src="image/Step2.png" style="width:600px">

**Step 3**: Click the first item, then you will see the information under the keyword `data`. 

**Step 4**: Copy the information and paste it into your local scripts (See `shanghai_bus_line.py` for example) 

<img src="image/Step4.png" style="width:600px">

**Step 5**: Get the bus line information and bus station information (See `get_bus_geo_info_manually.ipynb`)

The following image shows 10 bus lines for demonstration

<img src="image/result_visualization.png" style="width:600px">

**Note**: 

1. Geopandas package is required.
2. The GPS coordinator converter is copied from [知名博主小旭学长](https://gitee.com/ni1o1/CoordinatesConverter)
3. This repo is used for academic purpose only.

