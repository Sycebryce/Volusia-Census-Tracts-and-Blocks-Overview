# Volusia-Census-Tracts-and-Blocks-Overview
Hey class! Here is my project. Before you get started, download the zipfile I provided for you with all the 2020 Census Tracts, Block Groups, and Tabblocks. Once you do that, review my presentation which will show you step by step how to use the shapefiles. I also provided links to where I got the shapefiles and documentation about Census and LSTAT. I go over them in great detail in my videos. 

Step by instructions from the videos

Go to census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html and click FTP Archive by State. The link will take to list of shapefiles for each state. 

![Screenshot (302)](https://user-images.githubusercontent.com/82833246/116909297-02b90200-ac12-11eb-9cce-934f9bef3229.png)

You are going to click: 12_Florida>12127, then you'll be given a list zipfiles to download. You're going to want to download tl_2020_12127_bg20.zip, tl_2020_12127_tabblock20.zip, and tl_2020_12127_tract20.zip

![image](https://user-images.githubusercontent.com/82833246/116910944-490f6080-ac14-11eb-9205-11530a9580ec.png)

Extract the files into your desired folder, then load the shapefiles into your qgis. Click Layer>Add Vector Layer>Click the three dot button and click your deisred shapefile 

![image](https://user-images.githubusercontent.com/82833246/116912344-149ca400-ac16-11eb-838b-2e5bc09d4448.png)

Once you have uploaded your shapefiles on qgis, click one of the layers on your layer pane and click the information button to view your tracts, blockgroups, and tabblocks

![image](https://user-images.githubusercontent.com/82833246/116934527-1759c200-ac33-11eb-9cac-b113dc44f209.png)

Tracts, blockgroups, and tabblocks are broken up into population sizes. Tracts being the largest, followed by blockgroups, and lastly tabblocks. 

Tracts are statistical subdivisions of a county or equivalent entity that are updated by local participants. According to the Census Bureau, tracts can generally have a population size between 1,200 and 8,000 people, with an optimum size 4,000 persons. 

Blockgroups are groups of blocks that can contain between 600 to 3000 persons.

Blocks are very small areas that are statistically bounded on all sides by visible features (e.g., streets, roads, streams, and railroad tracks), and by non-visible boundaries (e.g. city, town, township, county limits, and short line-of-sight extensions of streets and roads.

One thing you will notice is the size of each tract and a lot of it is due to the density of the population. Notice how large the tracts, blockgroups, and blocks based on the house prices. Areas with red house will be a lot larger than areas with blue houses. Low income housing will produce smaller areas, becasue they are densely populated with smaller houses compared to high income housing.

![image](https://user-images.githubusercontent.com/82833246/116937273-ff843d00-ac36-11eb-984e-2700dbdca2a0.png)

![image](https://user-images.githubusercontent.com/82833246/116937387-25a9dd00-ac37-11eb-8576-dc34dd3bbdc3.png)

Right click on the track and click attribute table and on the top left you will see the total of records for tract, blockgroups, and blocks. On the table you will be provided with fields of data like the state and county fip code, area of land and water, and a variety data. To find out what each row of data is specifically we can click on the row and the data will be highlighted yellow. So we can do this for any of the rows we can click 

![image](https://user-images.githubusercontent.com/82833246/116934675-453f0680-ac33-11eb-8f6b-5566194a74ab.png)

![image](https://user-images.githubusercontent.com/82833246/116935084-da41ff80-ac33-11eb-9c19-86febdbe6991.png)

Presentation on how to use shapefiles 
Pt1 https://www.youtube.com/watch?v=eFzXRphnlVQ

Pt2 https://www.youtube.com/watch?v=A2rJAjUjFZo

Pt3 https://www.youtube.com/watch?v=kDY9LIZ__Ow

Link to the Census Tiger/Line Shapefiles
https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html

Link to the Tiger/Line Shapefiles
https://www2.census.gov/geo/pdfs/maps-data/data/tiger/tgrshp2020/TGRSHP2020_TechDoc.pdf

Link to the Hedonic Housing Prices and the Demand for Clean Air documentation
http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.926.5532&rep=rep1&type=pdf

