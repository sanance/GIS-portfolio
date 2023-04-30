**Final Project Proposal**

Client: Vital Strategies

Consultant: Sarah Nance

**Bid and Problem**

Vital Strategies is an international non-profit that focuses on improving public health systems and creating a more equitable and humane world for everyone. In particular they focus on evidence-based implementation for policies and projects. I worked for Vital Strategies last summer as an overdose prevention intern and used my GIS skills to create some static maps of overdose prevention resources and demographics. In the last week of my internship I was asked if I could create a web map of overdose prevention resources that automatically updates when they receive new data. When this was asked of me, I did not have the skills, experience or time left in the summer to produce the requested output, however, I am now confident that I am up to the challenge. 

The current problem facing Vital Strategies’ overdose prevention team and their state partners is how to effectively communicate to the public where overdose prevention resources are located. These resources can include syring service providers (needle exchanges), providers offering medication for opioid use disorder, and locations that offer naloxone, a drug that can reverse opioid overdoses. Each resource is critical in combating the overdose crisis and it’s important that the public can easily access information on them. Currently, many states and the Substance Abuse and Mental Health Administration have lists of resources on their websites, but this information is often not formatted well and it can be difficult to find which resources are located nearby. A good method of maintaining this is through a map where website visitors can easily view where resources are located in their area. The map will have a point for each resource and would include at least a phone number and address so an individual can contact and visit that location.  

Additionally, based on past experience, these resources change regularly with old locations shutting down or moving, and new locations being added. As a result, a static map will not work because it cannot be easily updated or maintained by the client. Instead, a dynamic map hosted online that can be automatically updated is necessary. Given time constraints, this project will focus on North Carolina as this is the state I was most active in and most familiar with, but if the organization likes the output, it would be easy to apply for other areas of the country.    

The final anticipated delivery for this project is an ArcGIS Online web map for North Carolina with a point feature class layer of overdose prevention resources that automatically updates at regular intervals based on data from other online websites.

**Basic Work Plan**

Of note, step 1 of the basic work plan (research on how to complete the project) was completed prior to creating the rest of the work plan. As a result, the rest of the plan is based on the findings of that research. 

1.	Research how to create a map that automatically updates
a.	Investigate different platforms to determine what works best for the client
2.	Find appropriate data online to use
3.	Create Python code in ArcGIS Online Notebooks to read in the data from online sources
4.	Add Python code to clean the data, and geocode it
a.	Cleaning includes filtering to only North Carolina locations for national datasets
5.	Output the data as point feature classes and symbolize appropriately
6.	Add all data to a hosted web layer on ArcGIS Online
7.	Add task automation to run steps 3-6 on a regular interval using ArcGIS Notebooks 
8.	If time allows, embed web layer into website

**Proposed Pricing Breakdown**

| Deliverables	| Estimated Hours |	Cost at $100 per hour | 
| ------------- | --------------- | --------------------- |
| Research how to create a map that automatically updates |	6 hours | 600 |
| Find data online | 1 hour	| 100 |
| Create python code to read in data sources	| 2 hours |	200 |
| Clean data in python | 3 hours |	300 |
| Geocode data in python |	3 hours |	300 |
| Create feature class in python |	2 hours |	200 |
| Symbolize map |	30 min |	50 |
| Export as web layer |	2 hours |	200 |
| Automate code at regular interval |	5 hours |	500 |
| Total | 24.5 Hours |	$2450 |

**Actual Pricing Breakdown**

| Deliverables | Estimated Hours | Actual hours | Estimated Cost at $100 per hour | Actual Cost at $100 per hour |
| ------------ | --------------- | ------------ | ------------------------------- | ---------------------------- |
| Research how to create a map that automatically updates | 6 hours | 6 hours | 600 | 600 |
| Find data online | 1 hour | 30 min | 100 | 50 |
| Create python code to read in data sources | 2 hours | 1.5 hour | 200 | 150 |
| Clean data in python | 3 hours | 1.5 hours | 300 | 150 |
| Geocode data in python | 3 hours | 1.15 hours | 300 | 125 |
| Create feature class in python | 2 hours | 3.5 hours | 200 | 350 |
| Symbolize map | 30 min | 3 hours | 50 | 300 |
| Export as web layer | 2 hours | 2.5 hours | 200 | 250 |
| Automate code at regular interval | 5 hours | 1 hour and 45 min | 500 | 175 |
| Total | 24.5 Hours | 21.5 Hours | $2450 | $2150 |


Overall, I was slightly under time and as a result slightly under budget. I took around 3 hours less to complete this project than I expected. However, for the individual tasks I was rarely accurate. For example, I thought the symbology would be a quick task and instead it took 3 hours to figure out. On the other hand, I thought automating the notebook to run at a regular interval would be tricky, and instead it was simple thanks to all the research I did at the beginning of the project. In general it seems like I took less time on the parts I already knew how to do (clean data, geocode data, etc.) whereas steps I didn’t know how to do such as creating a feature class in python took significantly longer. In the future I think I would add a little more time to the steps I have never done before in order to account for the learning curve, especially if using the ArcGIS API for Python because the documentation isn’t the best. 

**Final Web Map**
<style>.embed-container {position: relative; padding-bottom: 80%; height: 0; max-width: 100%;} .embed-container iframe, .embed-container object, .embed-container iframe{position: absolute; top: 0; left: 0; width: 100%; height: 100%;} small{position: absolute; z-index: 40; bottom: 0; margin-bottom: -15px;}</style><div class="embed-container"><iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" title="North Carolina Overdose Prevention Resources" src="//carnegiemellon.maps.arcgis.com/apps/Embed/index.html?webmap=b546af08ea0a4eee9839d6c2458a03c7&extent=-85.2504,33.0594,-74.4729,37.2523&home=true&zoom=true&previewImage=false&scale=true&legend=true&disable_scroll=true&theme=light"></iframe></div>


**Links to Final Notebooks**

[Starting Notebook](https://carnegiemellon.maps.arcgis.com/home/notebook/notebook.html?id=0f7bcf9d414247888a771a9873981078#)

[Automated Notebook](https://carnegiemellon.maps.arcgis.com/home/notebook/notebook.html?id=dfeddb8cf2744448888b99ec088cec20)

**Instructions on How to Use Final Products**

As explained in the proposal, the main final asset from this project is an ArcGIS Online web map for North Carolina with a point feature class layer of overdose prevention resources that automatically updates. Currently, the map shows buprenorphine providers according to the Substance Abuse and Mental Health Services Administration and health departments that have naloxone according to Naloxone Saves. Buprenorphine is used to treat opioid use disorders and naloxone can reverse an opioid overdose. This map also automatically updates at regular intervals based on data from the identified online websites. This process ensures that if the websites update their data, the map gets updated as well. Currently, the automated notebook that extracts the data from the aforementioned websites and creates the feature layers and web map is set to run every Sunday at 12am. This time was chosen so as to interfere with the fewest people possible, but can be changed if desired. 

The web map, North Carolina Overdose Prevention Resources, contains 2 separate point feature class layers: one for buprenorphine providers and one for health departments. The buprenorphine providers are colored orange and the health departments are dark blue. Each point has a pop-up with information that users can view in order to learn more about that location such as the phone number and address.

In order to automatically update the web map, two ArcGIS Online notebooks were created. The first, the ‘Starting Maps and Layers notebook’, creates the maps and feature layers for the first time. This notebook is entirely foundational and after it is run once it will never be run again. The second notebook is the automated one, that runs at a set time or interval and changes the contents of the web map. The only difference between the two notebooks is that the automated one contains additional code that deletes and replaces the previously created feature layers and web map. The notebooks are commented to make them easier to follow what each chunk is doing. 

**How to Use From Scratch**

1. Click the link to the ‘Starting notebook’ and in the upper right click ‘Open Notebook’ 
2. Run the notebook by clicking on the ‘Restart the Kernel and Rerun the Whole Notebook with Dialog” button, which looks like a fast forward button. This will create the web map and related features for the first time. 
3. Close the ‘Starting notebook’. You will not be using this ever again unless your ArcGIS Online account loses all of its contents or you change ArcGIS Online accounts. 
4. Click the link to the ‘Automated notebook’ and in the upper right click ‘Open Notebook’. Currently this notebook is set to run every Sunday at midnight in order to pull the most recent data from the websites and ensure the map always contains up to date information. You DO NOT need to do anything with this notebook as it is automatic.
5. Enjoy the web map! You can click the link to the Web Map in order to view it. The map is called “North Carolina Overdose Prevention Resources” when you view the contents of your ArcGIS Online account. 

If you decide that the map needs to be updated at a different interval or different time, there are two options. 

1. Manually run the notebook. This might be good for a one-time situation where the web map needs to be updated sooner than the usual scheduled time. Follow the same process as with the ‘Starting Notebook’. Run the notebook by clicking on the ‘Restart the Kernel and Rerun the Whole Notebook with Dialog” button, which looks like a fast forward button. This will recreate the web map and related features. 

2. Change the interval at which the notebook runs. This might be good if there is a repeated need to update the web map more or less often. On the ribbon at the top of the ‘Automated Notebook’, click ‘Tasks’. 

    - This will open a menu of all scheduled tasks. The currently scheduled task of running the code, entitled ‘Update Overdose Prevention Resources’ can be changed by clicking the three dots and selecting edit. 

    - Once you have selected to edit the task, hit next and go to ‘2. Set Task Schedule Details’. On this page you can change the interval, day, time, and end time of the task. 

   - Click ‘Save task’ to save any changes you have made. If you would like to check that the notebook is automatically updating and running properly, click on tasks     and the three dots next to the task. Instead of selecting ‘Edit’, choose ‘View Details’. 

   - This provides a pop-up that indicates the last time the task was run (Created) and if the notebook was modified to show the new output (Modified). These two     fields provide an idea of how long the notebook is taking to run. Importantly, ‘Status’ also indicates if the notebook was successful in running all the way through or not. If it says ‘Failed’, this indicates an error in the code that will need to be addressed by someone knowledgeable with the ArcGIS API for Python and this particular project/notebook. 

See [Client Walk-Through Document](https://github.com/sanance/GIS-portfolio/blob/main/Client%20Walk-Through.docx) for instructions with pictures
