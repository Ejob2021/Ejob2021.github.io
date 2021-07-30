## [Projec 1:	Built Enterprise data warehouse to migrate data based in legacy tools and application to cloud based platform for a company which provides loan to house buyers. ](https://github.com/Ejob2021/Ejob2021.github.io/blob/main/Project%20Summary.docx)

### The benefit of cloud-based migration is to make:
  *	Make data private and more secure
  * Empower users (By making data accessible for all skill level users)
  * To achieve faster insights.

### Built data pipelines for optimal extraction, transformation, and loading of data from various data sources using Cloud and SQL technologies Tools.

###	Extracted data from heterogenous data source. All connection managers are parametrized at project level.

  * SharePoint ----------                      ODATA Connection 
  * Salesforce  ---------                      ODATA Connection 
  * JSON Source (REST API or File) -----       FTP Connection 
  * Back Up Folder     -------                 OLEDB Connection 
  * JSON Source (REST API or File)-----        AUTH Connection 
  * Data Base   ------                         OLED Connection 
  * Excel             -----                    EXCEL Connection 
  * Flat Files     ------                      Flat File Connection

###	Developed Data Transformation Workflow and converted data into desired and consistent format. 

 * Performed different transformation operations to aggregate, split, sort, filter, match…etc for modification and data cleaning purpose.
 

###	Loaded data to different targeted destination.

  *	OLEDB
  *	Flat File
  *	Excel Spreadsheet

###	Created ETL and Error Handling Log Tables with in different packages.

  * Created and Configured  SSIS control flow to update ETL and Error Handling Log tables when  any update occures(Insertion/Deletion). 

###	Configured Email Script task, inside event handler, by using C#

  * Configured Email Script Task to send email notification on occurance of errors while execution the package.
 
### Deployed SSIS Pakage to SQl Server Management Studio.

  * Entire Solution deployed at Integration Service Catalog.
  
### Scheduled SQL Server Agent to run Master Package.

 * Master Package scheduled to run on specifc time on daily basis to capture newly added data in source.
 
## [Designed Data Warehouse by consolidating data integrated from different source.](https://github.com/Ejob2021/Ejob2021.github.io/blob/main/Phase%20II%20Summary%20Report.docx)

 * For analytical reporting and decision making organized and consolidated data .
 * Developed  adaptable Data Warehouse enviroment and made decesion making process rapid based on alalysis of past,present and future data.
 * Star Schema dimensional modelling adopted and fact table liked with associated demension table via foriegn Key/Primary Key relationships.

## Designed Dashboard based on Business requirements using Business Intelligence Tools.
 
![](/images/Star%20Schema.PNG)
 
 

