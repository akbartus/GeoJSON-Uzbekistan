<h1 align="center">GeoJSON file - Uzbekistan</h1>
<p align="center"><b>This GeoJSON file for Uzbekistan, which can be used for various data vizualizations based on maps. It contains geometric shapes for 14 administrative units of Uzbekistan as well as sample data, which match with geographic coordinates on the world map.</b><br><br>
<img width="500" src="https://raw.githubusercontent.com/akbartus/geojson-uzbekistan/main/img/Uzbekistan_map.jpg">
</p>

## Rationale
This file was compiled due to lack of GeoJSON for Uzbekistan on Internet. The few existing GeoJSON files for Uzbekistan are outdated and have some coordinate related errors (see for example: https://data.humdata.org/dataset/ubbekistan-update; although not originally in GeoJSON format, after  converting it, Tashkent city has wrong coordinates); or for a small fee. Present file was compiled based on OpenStreetMap, the project that creates and distributes free geographic data for the world (https://www.openstreetmap.org/) and it is completely free to use. I hope that this initiative will help to create interesting data vizualization projects for Uzbekistan in the future.   

## Features
:world_map: **Shapes and geocoordiates of 14 regions of Uzbekistan**: The file contains coordinates of the following regions and their respective shapes: Andijan Region, Bukhara Region, Fergana Region, Jizzakh Region, Khorezm Region, Namangan Region, Navoiy Region, Kashkadarya Region, Samarkand Region, Syrdarya Region, Surkhandarya Region, Tashkent Region, Republic of Karakalpakstan, Tashkent city.

:information_source: **Sample data for each region**: The file contains sample data (name of region) which corresponds to each given shape.

## Source
The GeoJSON was developed based on geodata and shapes for each of 14 regions of Uzbekistan available at OpenStreetMap (see: https://www.openstreetmap.org/changeset/104908077#map=6/41.523/64.574). 

## Usage
To use it:
1. Save the GeoJSON file (uzbekistan_regional.geojson) available in "geojson" folder to your local computer. 
2. Integrate with your own project(s).

To edit data in the GeoJSON file, follow the following steps:
1. Open GeoJSON editor available for free at https://geojson.io/.
<img width="500" src="https://raw.githubusercontent.com/akbartus/geojson-uzbekistan/main/img/instructions_0.jpg">

2. Click on "Open" > "File" and load uzbekistan_regional.geojson.
<img width="500" src="https://raw.githubusercontent.com/akbartus/geojson-uzbekistan/main/img/instructions_2.jpg">

3. Click on "Table" on the right side of the window and edit available rows.
<img width="500" src="https://raw.githubusercontent.com/akbartus/geojson-uzbekistan/main/img/instructions_3.jpg">

4. If there is a need for adding additional information, click on one of 14 regions displayed on the map on the right side of the screen.

5. In the popup window, click on "add row",  enter required data to the left and right columns and click "save". 
<img width="500" src="https://raw.githubusercontent.com/akbartus/geojson-uzbekistan/main/img/instructions_4.jpg">

6. Save and see the new column attached on the right of the screen.
<img width="500" src="https://raw.githubusercontent.com/akbartus/geojson-uzbekistan/main/img/instructions_5.jpg">

7. After doing required edits, click on "Save" > GeoJSON.
<img width="500" src="https://raw.githubusercontent.com/akbartus/geojson-uzbekistan/main/img/instructions_6.jpg">

### Examples
The file can be integrated for data vizualizations projects that utilize geographical data easily. Example (UNDP in Uzbekistan Project): https://i-map.o3.uz. 

### Future Steps
1. Compiling district based GeoJSON file for Uzbekistan.
2. Developing an online tool to combine geographical information available on OpenStreetMap and pre-compiled data. 
