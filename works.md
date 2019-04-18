# How Data Streamer Works
Data Streamer connects to a data source which can be a serial device, such as the Arduino UNO microcontroller, or a Windows 10 app via a UWP App Service. The data source collects data and packages it into a CSV format and sends the data at a frequency to Data Streamer. Data Streamer displays the data into an Excel worksheet. Data can also be sent from Excel to the device or app.

![Flow Chart](https://raw.githubusercontent.com/Microsoft/DataStreamerDevPortal/master/docs/DataStreamerAddInDiagram2.jpg)

Once connected and the Start Data button is clicked the add-in will generate 3 worksheets: Data In, Data Out, and Settings.

## Data In
Streaming data is injected into a range in the Data In worksheet. This range is updated whenever a new data packet is received. 

## Data Out
Data that is entered into the active range in the Data Out worksheet is packaged in CSV format and sent to the connected device or app. 

## Settings
Sets the parameters for the Data In and Data Out ranges and user settings. For more information go here. 

## Advanced Window
Use the Advanced Window to manage device settings, view the serial data console, or to change global user settings. For more information go here.