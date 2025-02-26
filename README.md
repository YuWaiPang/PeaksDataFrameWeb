## Web Pivot Table for Peaks DataFrame

The author created a .NET Web Pivot Table before using Golang. He is considering whether to re-implement this visual into Peaks DataFrame. The last bug fix was made on August 3rd, 2020. On April 30th, 2023, the author published this project again. 

If you want to use a ready to use version of the app, please download it from the "Releases" section of this page. How to use, please visit https://www.youtube.com/@accountingetl5158/videos

If you want to built the app from source code, please download it from https://github.com/hkpeaks/peaks-framework/tree/main/WebPivotTable.

Please note that you are authorized to amend the source code for your own use but not authorized to edit the download app.

Please read the license agreement before you use the app. Clicking the app which will start a websocket server and open your browser with default data. The app supports csv file only with maximum of 50 Million Rows given that your device has installed 32GB RAM. The websocket runs on local host “ws://127.0.0.1:5000/”. The websocket is an open source and can be downloaded from https://github.com/statianzo/Fleck.

Depend on whether there are a real demand, the Peaks project is considering developing a new version that supports billions of rows and is 5X to 10X faster.

### How-to Run the App

➾ Once you have downloaded the app, you can unzip it and read the readme file.

➾ After that, you can double click on the app and a folder named “uSpace” and a file named “uWeb” will be generated. Sample files are simulated automatically.

➾ Finally, double click on the “uWeb.html” file to open it in your browser. Or your browser may be opened automatically without clicking the file.

If it is not running properly, please check whether your machine has installed .net 4.72 or above. This is why the author moved to Go - no need to install .net to support an app.

![Web Pivot Table](https://github.com/hkpeaks/peaks-framework/blob/main/WebPivotTable/InstalledFolder.png)

https://youtu.be/yfJnYQBJ5ZY

[![Web Pivot Table](https://github.com/hkpeaks/peaks-framework/blob/main/WebPivotTable/WebPivotTable.png)](http://www.youtube.com/watch?v=yfJnYQBJ5ZY "Web Pivot Table")

➾ using C#, Vanilla JavaScript and W3.css for an integrated frontend to backend Web development, it do not implement any javascript framework or library 

➾  real-time web technology use Fleck websocket

➾  the project do not have dependency other than .net and fleck wedsocket, actually the web implementation did not use asp.net or asp.net core

➾  build-in a key-value NoSQL database for in-memory and disk versions

➾  building a set of algorithms to maximize parallel computing operating units which is extended to a big csv file and an in-memory table

➾  ultra-fast data import to web crosstab report with drag & drop and drill down capabilities 

➾  interactive pivot table that lets you move X and Y columns with real-time drilldown by simple mouse actions

➾  crosstab report supports multi-level of analysis account trial balance by period/currency/region

➾  1.3+ second youFast can process a million rows of a csv file to produce a web summary report and 0.13+ second youFast can filter data from 10 million rows to produce a web crosstab report (testing machine: Dell OptiPlex 7070 Micro Form Factor with Intel Core i9-9900 8 Cores 32G Ram Windows 10)

➾  developing pagination in X and Y direction, different levels of numeric precision

➾  clicking an app file with less than 500KB, user can enjoy zero installation and implementation 

➾  the app can run on a share drive and USB memory stick

➾  this project is maintained up to 100% C# source code
