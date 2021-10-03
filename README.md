# EDA_Projects
Project Proposal 

Background :
Our dataset is from MTA Turnstile Data.
First, we need to load this data and convert it to a data frame. Convert dates and time into a string, if any, to make it easier to work with.
Second, we make sure that the data set is clean from missing data, duplicate data, or anomalies.
Third, in order to benefit from this work, we must conduct statistical operations and then the resulting perceptions of these operations.

To take advantage of this process to increase profits in marketing campaigns, distributing advertising screens, distributing machines, stores, etc..

Question : 
what is the source dataset come from?
Do we need to load the data from the source and convert it to a data frame?
Do time and date need to turn this into a time series?
Is there any missing data?
Is there any duplicate data?
Are there outliers?
What are the statistical operations that can be applied to the data?
After performing the statistical operations, can the data give us visualizations?

Data Description : 
MTA Dataset : 
Field Description
C/A: Control Area (A002)
UNIT: Remote Unit for a station (R051)
SCP: Subunit Channel Position represents an specific address for a device (02-00-00)
STATION: Represents the station name the device is located at
LINENAME: Represents all train lines that can be boarded at this station. Normally lines are represented by one character.  LINENAME 456NQR repersents train server for 4, 5, 6, N, Q, and R trains.
DIVISION: Represents the Line originally the station belonged to BMT, IRT, or IND.
DATE: Represents the date (MM-DD-YY).
TIME: Represents the time (hh:mm:ss) for a scheduled audit event.
DESc: Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours)
           1. Audits may occur more that 4 hours due to planning, or troubleshooting activities. 
           2. Additionally, there may be a "RECOVR AUD" entry: This refers to a missed audit that                                         was recovered.
ENTRIES:The comulative entry register value for a device.
EXIST: The cumulative exit register value for a device.

Tools : 
-	SQL
-	SQLITE
-	Python 
-	Jupyter notebook 


![image](https://user-images.githubusercontent.com/90608912/135745664-5c997168-7f51-4652-affc-fac9ec46dfbc.png)
