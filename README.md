# Vanilla-2020

The most recent data used was collected in 2020. The 2021 notebooks are based on this data. There are totally only 2 years of data available, 2019 and 2020. Out of this the 2019 data does not fully cover the flowering season, and has much lesser data. The visualization notebooks are mainly to understand the dynamics of vanilla flowering. For example, in this data exploration, I have identified a relation between the number of locations and the number of new flowers. This is significant because if we incorporate this intelligence in the day to day pollination, we can greatly improve manual pollination efforts.

The technology that I envision involves having an automatic data collection on the field, which would give immediate intelligence to the manual pollinator, and also feed the data to a centra database for real time yield tracking and projection. This yield projection data can be very useful to distributors and other players further up the value chain.

2021 updated Bar chart race rendered here : https://nbviewer.jupyter.org/github/Appymp/Vanilla-2020/blob/master/Vanilla_2021_Barchart_Race.ipynb

2021 updated Visualizations season: https://nbviewer.jupyter.org/github/Appymp/Vanilla-2020/blob/master/Vanilla_2021_May.ipynb

YOLO model for identifying new_flowers from video. The model was trained on very few (about 130) images, which were augmented by a range of crops,saturation and exposure variations. So totally the model was trained on about 490 images. 
Pending work:
- Counting the flowers for a particular location.
- Localize the count to the individual vine locations. 
- 

Best path algorithm:
- Use a path optimization algo like TSP or Djikstra's. However, can make modifications so that it does not become an NP-hard problem (like in TSP).
