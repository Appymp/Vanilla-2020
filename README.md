# Vanilla-2020


"Flo counter" selected as one of the 10 finalists in Make it Agri Season 3! https://makeitagri.org/finalistes-saison-3/


For viewing the code notebooks, it is better to click on the corresponding nbviewer rendered links in the below document. 

The most recent data used was collected in 2020. The 2021 notebooks are based on this data. There are totally only 2 years of data available, 2019 and 2020. Out of this the 2019 data does not fully cover the flowering season, and has much lesser data. 
Check out the the preliminary research paper in the Vanilla-2019 repo: https://github.com/Appymp/Vanilla-2019.

Also, you can find a study I did on the data available on the FAO website on vanilla for the past 10 years: https://github.com/Appymp/Datamining_Vanilla_poster


In this Vanilla-2020 repo, the visualization notebooks are mainly to understand the dynamics of vanilla flowering. For example, in this data exploration, I have identified a relation between the number of locations and the number of new flowers. This is significant because if we incorporate this intelligence in the day to day pollination, we can greatly improve manual pollination efforts. If there are 100 unique flowering vanilla vines, on average less than 20% of the vines bear 80% of the flowers on any given day. So the pollinator can visit only 20% of the vines and still manage to pollinate 80% of the flowers. This can save time, effort, and worker shortage issues.

The technology I envision involves having an automatic data collection on the field, which would give immediate intelligence to the manual pollinator, and also feed the data to a central database for real time yield tracking and projection. This yield projection data can be very useful to distributors and other players further up the value chain. Its a Win-Win solution for all stakeholders.

2021 updated Bar chart race rendered here : https://nbviewer.jupyter.org/github/Appymp/Vanilla-2020/blob/master/Vanilla_2021_Barchart_Race.ipynb

2021 updated Visualizations season: https://nbviewer.jupyter.org/github/Appymp/Vanilla-2020/blob/master/Vanilla_2021_May.ipynb

YOLO model for identifying new_flowers from video. The model was trained on very few (about 130) images, which were augmented by a range of cropping,saturation and exposure variations. So totally the model was trained on just about 490 images. 
https://nbviewer.jupyter.org/github/Appymp/Vanilla-2020/blob/master/Vanilla_apps_Roboflow-Custom-YOLOv5.ipynb


Pending coding work:
- Counting the flowers for a particular location.
- Localize the count to the individual vine locations and map them. 
- Best path algorithm:
  - Use a path optimization algo like TSP or Djikstra's. However, we should make modifications so that it does not become an NP-hard computation problem (like in TSP).
  - Easy to read and implement output report for the pollinator. Example: report indicating column and row vlaue of vine location in the plantation grid, map top view of the locations and their number of flowers with a best path overlay.
https://nbviewer.jupyter.org/github/Appymp/Vanilla-2020/blob/master/Vanilla_2021_Best_path.ipynb
 

Business aspects:
- identify key large players and quantify the benefit of real time yield data. Dashboard for the distributors.
- dashoard for the vanilla farmers.
- data quality control and scope for quantifying dynamic labels like "organic" and "artisinal" etc.
