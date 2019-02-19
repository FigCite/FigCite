# FigCite

Requirements:

python>=2.7 \\
matplotlib
lxml
numpy


Instructions:

To run barChartGen.py file:

filename = "BarCharts/bar_xml_8001_10000.xml" #Stores information of each bar chart in xml format. \\
outfile = open("barchart_json_8001_10000.json","w") #Also store it in json format \\
outfile_csv = csv.writer(open("barchart_csv_8001_10000.csv","w")) #Storing it in csv format
NumberOfBarPlot = 10001 #change this variable to set the number of plots you want to generate

To run lineChartGen.py file:

xml_file = "LineCharts/linechart_xml_15001_20000.xml"
outfile = open("linechart_json_15001_20000.json","w")
outfile_csv = csv.writer(open("linechart_csv_15001_20000.csv","w"))
noOfPlots=12000 #set the number of charts you want to generate

To run pieChartGen.py file:

xml_file = "pie_xml_5000_10000.xml"
outfile = open("piechart_json_5000_10000.json","w")
outfile_csv = csv.writer(open("piechart_csv_5000_10000.csv","w"))
noOfPlot=2000 #set the number of charts you want to generate
