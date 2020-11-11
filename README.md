# Digital Asset Management


This repository contains the **solution for Digital Asset Management** 
It holds the SAPUI5 project (built with mock data). Currentlty, mock data has been used along with JSON model (since no backend connectibity and Annotaions are present to use Fiori Elements), UI controls are used keeping user experience and SAP Fiori Guidelines in mind. However, in real time, For backend : CDS View (along with desired Annotaions) will be used to fetch the data from the backend (Pagination to handle more number of records along with the use of OData Model). For Frontend: List Report(along with Object Page) to display/edit the asset details will be designed to handle this scenario.

Please follow the setup instructions below to get started.

## Directions

In the `main` branch, you can find:

* `DigitalAssetManagement`: SAPUI5 Project zip file (built on MVC paradigm). 

## Setup

You can import this repository to SAP Web IDE or run it standalone. Choose the scenario that fits your needs:

### SAP Web IDE (recommended)

1. Download **DigitalAssetManagement.zip** from repository and save it locally in your system.

2. Run SAP Web IDE; either personal edition or cloud edition.

3. Right click on the workspace, **Go to Import -> From File System**. Select the zip file from your system and choose `extract archive`.

4. A folder `DigitalAssetManagement` is added to your workspace.

5. In the `webapp` folder , right-click on the `index.html`, and choose **Run > Run index.html** or **Run > Run Component.js** to run the Asset Management Solution.


## Contributions & Support

If you spot any issues with the code or if you find a bug, please create an issue or a pull request, and I will take care of it.

Thank you,
Parth
