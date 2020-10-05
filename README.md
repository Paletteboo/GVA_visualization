# 2013-2018美国枪支暴力事件信息可视化项目
2013-2018 US Gun Violence Incidents Visualisation

## Introduce
This project is in D3.js and leaflet.js which focuses on the US Gun Incidents data from 2013 to 2018 and depicts the trend, distribution and casualties involved in the gun violence incidents in USA in this period.
本项目采用D3.js和leaflet.js，主要研究美国2013年至2018年的枪支事件数据，描述了这一时期美国枪支暴力事件的趋势、分布和涉及的伤亡情况。

## Content
1. recoding.mp4 is the video presentation record for this project.
2. code folder has the web code of this project.
3. Data source folder has the data that used in this project and the origin data without data cleaning.
4. Report folder contains the final group report and the Preparation Report that wroted in the project's early-age.
5. Sketch folder includes the tableau sketch and the sketch in paper documents.
项目文档内容
1. recoding.mp4是本项目的展示视频。
2. code文件夹中有本项目的网页代码。
3. Data source文件夹中包含了本项目中使用的数据和未经数据清洗的原始数据。
4. Report文件夹中包含了本项目前期编写的最终小组报告和准备报告。
5. Sketch文件夹中包含了Tableau草图和纸质文档中的草图。

#### the code folder of this project includes five files:  
1. data_cleaned5044.csv : The data source. 数据源。
2. index.css: The css style sheet of index.html.
3. index.html: The html webpage of this visualizsation which includes javascript code.
4. map.js: The functions of the Choropleth Map.
5. us-states.js: The geojson of Us-states which used to draw the Choropleth Map.

#### 本项目code文件夹包括五个文件。
1. data_cleaned5044.csv：数据源。
2. index.css：index.html的css样式表。index.html的css样式表。
3. index.html。该可视化项目的html网页，包含javascript代码。
4. map.js：地图的功能。
5. us-states.js：用于绘制Choropleth Map的美国各州的geojson。

#### Requirement
1. Firefox broswer

2. For running webserver locally：
	MAMP : to open local webserver.
#### 项目运行要求
1. 火狐浏览器

2. 在本地运行webserver：MAMP：打开本地网络服务器。
#### How To Start
1. Serving WebContent from URL address： https://cd243.host.cs.st-andrews.ac.uk/P3/html_code/index.html
2. Run the web visualization locally
  1. Download and install MAMP
  2. Run MAMP
  3. Copy the folder html_code to the webfolder ”htdocs“(for mac）/ ”www“(for windows) on your computer, that MAMP has created.
  4. Open the visualisation files from the browser using the following address:
	localhost/html_code/index.html (for windows)
	localhost:8888/html_code/index.html (for Mac)
#### 如何访问项目网站
1. 从URL地址访问：https://cd243.host.cs.st-andrews.ac.uk/P3/html_code/index.html。
2. 在本地运行
  1. 下载并安装MAMP
  2. 运行MAMP
  3. 将html_code文件夹复制到你电脑上的web文件夹 "htdocs"(for mac)/"www"(for windows)中，MAMP已经创建了这个文件夹。
  4. 使用以下地址从浏览器打开可视化文件。
	本地主机/html_code/index.html (windows)。
	localhost:8888/html_code/index.html (for Mac)
