# Analyzing-Crime-in-Los-Angeles 

## Project Description 
Los Angeles, California 😎. The City of Angels. Tinseltown. The Entertainment Capital of the World! Known for its warm weather, palm trees, sprawling coastline, and Hollywood, along with producing some of the most iconic films and songs. However, as with any highly populated city, it isn't always glamorous and there can be a large volume of crime. 
This Data Analysis project aims to support the Los Angeles Police Department (LAPD) by analyzing crime data to identify patterns in criminal behavior. I need to find out the answers of several questions: 
  * Which hour has the highest frequency of crimes?
  * Which area has the largest frequency of night crimes (crimes committed between 10pm and 3:59am)?
  * Identify the number of crimes committed against victims of different age groups.

## The Data
They have provided a single dataset to use. A summary and preview are provided below.It is a modified version of the original data, which is publicly available from Los Angeles Open Data.
### Crimes.csv(original) [Download Here](https://data.lacity.org/api/views/2nrs-mtv8/rows.csv?accessType=DOWNLOAD)

| Column     | Description              |
|------------|--------------------------|
| `'DR_NO'` | Division of Records Number: Official file number made up of a 2-digit year, area ID, and 5 digits. |
| `'Date Rptd'` | Date reported - MM/DD/YYYY. |
| `'DATE OCC'` | Date of occurrence - MM/DD/YYYY. |
| `'TIME OCC'` | In 24-hour military time. |
| `'AREA NAME'` | The 21 Geographic Areas or Patrol Divisions are also given a name designation that references a landmark or the surrounding community that it is responsible for. For example, the 77th Street Division is located at the intersection of South Broadway and 77th Street, serving neighborhoods in South Los Angeles. |
| `'Crm Cd Desc'` | Indicates the crime committed. |
| `'Vict Age'` | Victim's age in years. |
| `'Vict Sex'` | Victim's sex: `F`: Female, `M`: Male, `X`: Unknown. |
| `'Vict Descent'` | Victim's descent:<ul><li>`A` - Other Asian</li><li>`B` - Black</li><li>`C` - Chinese</li><li>`D` - Cambodian</li><li>`F` - Filipino</li><li>`G` - Guamanian</li><li>`H` - Hispanic/Latin/Mexican</li><li>`I` - American Indian/Alaskan Native</li><li>`J` - Japanese</li><li>`K` - Korean</li><li>`L` - Laotian</li><li>`O` - Other</li><li>`P` - Pacific Islander</li><li>`S` - Samoan</li><li>`U` - Hawaiian</li><li>`V` - Vietnamese</li><li>`W` - White</li><li>`X` - Unknown</li><li>`Z` - Asian Indian</li> |
| `'Weapon Desc'` | Description of the weapon used (if applicable). |
| `'Status Desc'` | Crime status. |
| `'LOCATION'` | Street address of the crime. | 

## Prerequisites
  * Python 3.6 or higher [Download Here](https://www.python.org/downloads/)
  * Numpy
  * Pandas
  * Matplotlib
  * Seaborn

## Steps to complete 
  * Finding the frequencies of crimes by the hour of occurrence
  * Identifying the area with the most night crime
  * Crimes by age group 

## Results/ Findings
  * peak_crime_hour:  12
  * The area with the largest volume of night crime is Central
  * 26-34    47470
    35-44    42157
    45-54    28353
    18-25    28291
    55-64    20169
    65+      14747
    0-17      4528
