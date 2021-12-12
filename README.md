# Exploratory Data Analysis (EDA) Projects of MTA Turnstile Data:

This repo contains MTA Turnstile data and solution at Istanbul Data Science Academy. This project is about Exploratory Data Analysis (EDA) of Metropolitan Transportation Authority (MTA) Turnstile Data.

## Exploratory Data Analysis (EDA):

Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns,to spot anomalies,to test hypothesis and to check assumptions with the help of summary statistics and graphical representations.

## Objective and Goal:
* BUSINESS NEED|Specifying usage of transportation frequency in pandemic
* OBJECTIVE | Finding the busiest subway stations, most crowded day and best time slot
* SOLUTION | Using MTA Turnstile and analyse to find best placement for comfort transportation. To show, visualize the data to users.

## MTA Turnstile Data:
Data obtained from http://web.mta.info/developers/turnstile.html.
 
## Field Description:

| Field Name | Description                                                                     |
|------------|---------------------------------------------------------------------------------|
| C/A        | Control Area (A002)                                                             |
| UNIT       | Remote Unit for a station (R051)                                                |
| SCP        | Subunit Channel Position represents an specific address for a device (02-00-00) |
| STATION    | Represents the station name the device is located at                            |
| LINENAME   | Represents all train lines that can be boarded at this station                  |
| DIVISION   | Represents the Line originally the station belonged to BMT, IRT, or IND         |
| DATE       | Represents the date (MM-DD-YY)                                                  |
| TIME       | Represents the time (hh:mm:ss) for a scheduled audit event                      |
| DESC       | Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours)   |
| ENTRIES    | The comulative entry register value for a device                                |
| EXITS      | The cumulative exit register value for a device                                 |


## Example:

The data below shows the entry/exit register values for one turnstile at control area (A002) from 03/28/2020 at 00:00 hours to 04/03/2020 at 00:00 hours
### C/A,UNIT,SCP,STATION,LINENAME,DIVISION,DATE,TIME,DESC,ENTRIES,EXITS.<br>
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/28/2020,00:00:00,REGULAR,0007412829,0002516511                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/28/2020,04:00:00,REGULAR,0007412831,0002516512                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/28/2020,08:00:00,REGULAR,0007412837,0002516526                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/28/2020,12:00:00,REGULAR,0007412849,0002516538                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/28/2020,16:00:00,REGULAR,0007412880,0002516555                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/28/2020,20:00:00,REGULAR,0007412899,0002516565                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/29/2020,00:00:00,REGULAR,0007412911,0002516573                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/29/2020,04:00:00,REGULAR,0007412912,0002516575                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/29/2020,08:00:00,REGULAR,0007412916,0002516578                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/29/2020,12:00:00,REGULAR,0007412931,0002516588                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/29/2020,16:00:00,REGULAR,0007412956,0002516603                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/29/2020,20:00:00,REGULAR,0007412977,0002516614                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/30/2020,00:00:00,REGULAR,0007413003,0002516618                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/30/2020,04:00:00,REGULAR,0007413004,0002516621                                            
A002,R051,02-00-00,59 ST,NQR456W,BMT,03/30/2020,08:00:00,REGULAR,0007413007,0002516633  
