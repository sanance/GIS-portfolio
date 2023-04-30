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

**Instructions on How to Use Final Assets**

