* Eyob Portfolio website
# Projec 1:	Built Enterprise data warehouse to migrate data based in legacy tools and application to cloud based platform for a company which provides loan to house buyers. 

#### The benefit of cloud-based migration is to make:
  *	Make data private and more secure
  * Empower users (By making data accessible for all skill level users)
  * To achieve faster insights.

##	Extracted data from heterogenous data source. All connection managers are parametrized at project level.

  * SharePoint ----------                      ODATA Connection 
  * Salesforce  ---------                      ODATA Connection 
  * JSON Source (REST API or File) -----       FTP Connection 
  * Back Up Folder     -------                 OLEDB Connection 
  * JSON Source (REST API or File)-----        AUTH Connection 
  * Data Base   ------                         OLED Connection 
  * Excel             -----                    EXCEL Connection 
  * Flat Files     ------                      Flat File Connection

##	Transformed data into desired and consistent format. 
 * Performed different transformation operations to aggregate, split, sort, filter, match…etc for modification and data cleaning purpose.
 * 

##	Loaded data to different targeted destination.

  *	OLEDB
  *	Flat File
  *	Excel Spreadsheet

##	Created ETL and Error Handling Log Tables withing different packages.

  * Created and Configured  SSIS control flow to update ETL and Error Handling Log tables when  any update occures(Insertion/Deletion). 

##	Configured Email Script task, inside event handler, by using C#

  * Configured Email Script Task to send email notification on occurance of errors while execution the package.

