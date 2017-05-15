# taxiridesharing
An efficient way to merge taxi trips.


We developed a Taxi Ride-Sharing system for a part of New York City. This system accepts passengers’ real-time ride requests and schedules taxis to pick them up via ride-sharing keeping in mind constraints with respect to time, taxi capacity and money. The entire objective behind this project is to devise an efficient ride-sharing algorithm that will be beneficial to both the customer requesting for a ride and the Taxi company (or the driver of the Taxi). Post ride-sharing, the customer will not pay more compared to a ride without sharing and compensation due to lengthened travel time and money for short distances will be made up for. 
Our algorithm focuses on single source – multiple destination combinations. Our single source point is Barclay’s center in Brooklyn, NYC. 


Dependencies to run the project:
1. Python version 3.0 or higher.
2. Jupyter Notebook.

Install and Run instructions:
1. Clone the repository as zip.
2. Unzip the files in a folder.
3. Download all the files from google drive link:
    https://drive.google.com/drive/folders/0Bx-5mrdb_G2KZnJCdm1lVkNoRGs?usp=sharing
4. COpy the downloaed files and folders to Repository Folder
5. Open cmd and navigate to the project folder.
6. Run the following command:
    java -jar graphhopper-web-0.6.0-with-dep.jar jetty.resourcebase=webapp config=config-example.properties osmreader.osm=new-york-         latest.osm.pbf
7. Install Jupyter Notebook and open the project folder in localhost.
8. Run the project step by step using Jupyter on 2 files (in order):
    Import.ipynb
    Apply.ipynb
