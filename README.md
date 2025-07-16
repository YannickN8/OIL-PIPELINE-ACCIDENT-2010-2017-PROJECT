
 <img width="1160" height="651" alt="01_COVER" src="https://github.com/user-attachments/assets/93713329-8712-4033-9fa0-390d9dcbcdfa" />


Summary/Problem Statement:
 In the United States, there have been numerous pipeline accidents in past years. According to data from the Pipeline and Hazardous Materials Safety Administration (PHMSA), there were 2,795 pipeline accidents in the United States from 2010 to 2017, resulting in 137 fatalities and 709 injuries. In addition ,there was a total Emergency cost of 735 million channeled to these accidents. Reducing this expense can help improve on other sectors of the oil industry.

KPIs:

<img width="1231" height="692" alt="02_KPIs" src="https://github.com/user-attachments/assets/36275a21-2a3c-4cab-9505-7845b7ebff74" />

 

DATA DICTIONARY:

<img width="1202" height="753" alt="03_DataDictionary" src="https://github.com/user-attachments/assets/52a17523-4066-429c-8d7d-7d03086a84a4" />

 

EXECUTIVE SUMMARY:

![04_EXECUTIVE SUMMARY Final](https://github.com/user-attachments/assets/764badb4-608c-47cb-89dd-3722203d8a1a)

 


Troubles that occurred during the project:

1. Some columns had Null values and gave me a hard time doing data conversion as they kept throwing errors. I had to use the ISNULL() and CAST() functions to replace the null values therefore ended up using SQL query in the source data flow task.
2. I had trouble with the script task locating the filepath for the Json file. To solve this issue, I had to change the location of the file in my folder and gave it a specific name with suffix ".json"
3. The dictionary tables had a lot of duplicate data . To get rid of this, I used the "Select Distinct" statement in the OLEDB source .

 <img width="1483" height="835" alt="05_Problems encountered" src="https://github.com/user-attachments/assets/5430d2c9-ad4a-4b12-956d-6f2e48ab9de4" />



Visual Key Insights:

 <img width="1537" height="736" alt="06_KeyVisualInsights" src="https://github.com/user-attachments/assets/0b593da7-170d-43e0-be75-225d446a63f5" />



 <img width="1276" height="742" alt="07_Positive Insights" src="https://github.com/user-attachments/assets/1f8c6c20-6c31-4503-860f-090dbfcfbdc5" />


•	Since 2014-2017, there has been a tremendous drop of -51.33% in number of oil pipeline accidents caused by incorrect valve position.
      
 <img width="1292" height="735" alt="08_Positive Insight 1" src="https://github.com/user-attachments/assets/84b87441-c98b-4800-860f-f7ef506076aa" />


•	With unknown causes of oil pipeline accidents , between 2016 and 2017, number of oil pipeline accidents has gone down to 29565 from 9238254. This is a -97% drop in number of accidents caused by unknown factors.
        
 <img width="1292" height="690" alt="09_Positive Insight2" src="https://github.com/user-attachments/assets/b1e52673-b8a5-4f23-81b4-e7ef22486839" />



 
<img width="1278" height="717" alt="10_Negative Insights" src="https://github.com/user-attachments/assets/367f0d95-28dd-474a-bf2e-3c2b37771940" />


 <img width="1198" height="715" alt="11_Negative Insights 1" src="https://github.com/user-attachments/assets/7881197c-4d43-49c1-82dc-1b97e2d7986b" />


•	The number of oil pipeline accidents caused by pump or pump related equipment is high across most of the years between 2010-2017. In 2016, there is an increase in number of accidents by 164.18% .
          
 <img width="1293" height="676" alt="12_Negative Insight 2" src="https://github.com/user-attachments/assets/7747c685-f411-4241-abf6-afaaf514bd66" />


•	The number of oil pipeline accidents caused by external corrosion of pipelines keeps flactuating and in 2015, there was a massive increase in these accidents by 6289% .
      
 <img width="1352" height="673" alt="13_negative Insight 3" src="https://github.com/user-attachments/assets/b0d48fd1-dda1-4d60-9230-1d7dcae6865c" />


Data Model:

 <img width="1306" height="791" alt="14 DataModel" src="https://github.com/user-attachments/assets/a789205d-ef4d-4693-bdce-3c06c929fe45" />



Suggestions:
1. The data shows that the highest number of Oil spillages which is 1792, are due to        corroded pipelines. Therefore, I recommend conduction of regular safety inspections and maintenance of oil rigs, pipelines, and storage facilities to ensure they are in good condition and identify potential hazards before they cause accidents.

2. According to the data, emergency response costs are high at 735 million within a period of 7 years. This could be lowered by upto 50% if there is proper training for employees on how to effectively approach emergencies and put in place guidelines for reporting and investigating accidents.

3. The data shows property damage costs are unpredictable and this could lead to unpreparedness. Therefore I suggest we develop and invest in new technologies and methods to improve oil spill prevention and response, such as leak detection systems and improved equipment for containing and cleaning up spills.

4. The data between 2010-2017 shows  that oil accidents are not predictable on when it will get better. There is a rise and fall in the numbers and I therefore suggest we  consider diversifying energy sources and reducing dependence on oil to reduce the risks of oil accidents and the impact of their consequences.

 <img width="1536" height="860" alt="15_Suggestions" src="https://github.com/user-attachments/assets/fff83945-fb73-4b9d-8641-61b049d4b9d0" />



