# **Portfolio**

[Python and SQL](#python-and-sql)|[Publications](#publications)|[Outreach](#outreach)

## Python and SQL

### [Predicting Popular Recipes](https://github.com/maja-kucharczyk/predicting-popular-recipes)

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/maja-kucharczyk/predicting-popular-recipes)

<kbd>pandas</kbd> <kbd>numpy</kbd> <kbd>scipy</kbd> <kbd>matplotlib</kbd> <kbd>seaborn</kbd> <kbd>scikit-learn</kbd> <kbd>statsmodels</kbd>

I performed **exploratory data analysis**, **data preparation**, and **binary classification** using **Python** to predict which recipes would lead to high traffic on the website of a company that sells meal planning and ingredient delivery services. **Repeated stratified k-fold cross-validation** and **grid search** were used for model selection and hyperparameter tuning. The **logistic regression** model achieved an accuracy of 81% and revealed which recipe attributes are associated with high and low website traffic.

![](https://maja-kucharczyk.github.io/assets/img/coefficients.png)

---

### [Predicting Car Prices](https://github.com/maja-kucharczyk/predicting-car-prices)

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/maja-kucharczyk/predicting-car-prices)

<kbd>pandas</kbd> <kbd>numpy</kbd> <kbd>scipy</kbd> <kbd>matplotlib</kbd> <kbd>seaborn</kbd> <kbd>scikit-learn</kbd> <kbd>statsmodels</kbd>

I performed **exploratory data analysis**, **data preparation**, and **regression** using **Python** to predict used car prices. **K-fold cross-validation** and **grid search** were used for model selection and hyperparameter tuning. The **random forest** model achieved a root-mean-squared error of 1210 GBP, R<sup>2</sup> of 0.96, and predicted 78% of prices within 10% of their actual values.

![](https://maja-kucharczyk.github.io/assets/img/algorithm_comparison.png)

---

### [Exploring the International Debt BigQuery Data](https://github.com/maja-kucharczyk/exploring-international-debt)

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/maja-kucharczyk/exploring-international-debt)

<kbd>pandas</kbd> <kbd>pandas-gbq</kbd> <kbd>matplotlib</kbd> <kbd>seaborn</kbd>

The [International Debt Statistics](https://datacatalog.worldbank.org/search/dataset/0038015) dataset by The World Bank has reported the external debt of low- and middle-income countries and regions each year since 1970. Google hosts the International Debt Statistics as a public **BigQuery** dataset called [International Debt](https://console.cloud.google.com/marketplace/product/the-world-bank/international-debt). After inspecting the international_debt table in the BigQuery dataset, **I found that all 3.28 million rows had null year values and 94% of the rows had null debt values**. In total, there were 138,152 rows with non-null and non-zero debt values, of which 2,467 were unique. The unique rows were grouped and joined with other tables in the dataset to determine the highest-debt countries, total debt owed by all countries, and debt per income group, region, and debt indicator. Due to the null debt and year values in the international_debt table, the BigQuery dataset currently appears limited in its use for exploring aggregate debt and temporal aspects. If the BigQuery dataset is fixed, the **SQL** queries can be rerun to derive accurate estimates.

![](https://maja-kucharczyk.github.io/assets/img/region_income_group_debt.png)

---

## Publications

### [Remote sensing of natural hazard-related disasters with small drones: Global trends, biases, and research opportunities](https://doi.org/10.1016/j.rse.2021.112577)

**Kucharczyk, M.**, & Hugenholtz, C. H. (2021). Remote Sensing of Environment, 264, 1–13.

<kbd>Web of Science</kbd> <kbd>Scopus</kbd> <kbd>Mendeley</kbd> <kbd>Esri ArcGIS</kbd>

**Cited 50+ times**, this is a comprehensive review of drone-based remote sensing for supporting disaster management. We performed a systematic literature search using the **Preferred Reporting Items for Systematic Reviews and Meta-Analyses** methodology, resulting in 635 relevant articles from which we derived trends and critical research needs relating to geography, disaster management application, drone hardware, and drone remote sensing data type and analysis method. Based on the research gaps we identified, we recommended that future studies focus on: (i) earthquakes, floods, and cyclones and other windstorms due to higher loss of life and economic impacts; (ii) larger and urban study areas in low, lower-middle, and upper-middle income countries and territories to support vulnerable populations; (iii) under-demonstrated (and especially response-related) disaster management activities, which generally require observations of built features from urban environments; and (iv) data standards for integrating drone-based remote sensing with international disaster management methodologies.

![](https://maja-kucharczyk.github.io/assets/img/rse.jpg)
[Kucharczyk & Hugenholtz (2021)](https://doi.org/10.1016/j.rse.2021.112577) [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

---

### [Weather constraints on global drone flyability](https://doi.org/10.1038/s41598-021-91325-w)

Gao, M., Hugenholtz, C. H., Fox, T. A., **Kucharczyk, M.**, Barchyn, T. E., & Nesbit, P. R. (2021). Scientific Reports, 11(1), 1–13.

<kbd>Python</kbd>

**Cited 50+ times**, this study globally mapped the proportion of time various drones can fly safely (termed “flyability”). Flyability was quantified by comparing historical wind speed, temperature, and precipitation data to manufacturer-reported thresholds of common commercial and weather-resistant drones with a **Python**-based computer simulation. Within this global dataset, we examined the 100 most populated cities where some on-demand drone services and applications such as delivery and emergency services may be applied commonly. Results indicated that global flyability is highest in warm and dry continental regions and lowest over oceans and at high latitudes. Median global flyability for common drones is low: 5.7 h/day or 2.0 h/day if restricted to daylight hours. Weather-resistant drones have higher flyability (20.4 and 12.3 h/day, respectively). An inverse analysis for major population centres showed the largest flyability gains for common drones can be achieved by increasing maximum wind speed and precipitation thresholds from 10 to 15 m/s and 0–1 mm/h, respectively.

![](https://maja-kucharczyk.github.io/assets/img/sr.JPG)
[Gao et al. (2021)](https://doi.org/10.1038/s41598-021-91325-w) [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

---

### [Geographic Object-Based Image Analysis: A Primer and Future Directions](https://doi.org/10.3390/rs12122012)

**Kucharczyk, M.**, Hay, G. J., Ghaffarian, S., & Hugenholtz, C. H. (2020). Remote Sensing, 12(12), 1–33.

<kbd>GRASS GIS</kbd> <kbd>Trimble eCognition</kbd> <kbd>ENVI FX</kbd> <kbd>Esri ArcGIS</kbd>

**Cited 50+ times**, this study described the theoretical foundations of **geographic object-based image analysis (GEOBIA)** and provided a comprehensive overview of the methodological workflow. Building on this foundation, we then reviewed recent research on the convergence of GEOBIA with deep **convolutional neural networks**, which we suggested is a new form of GEOBIA. Overall, this study described the past, present, and anticipated future of GEOBIA in a novice-accessible format, while providing innovation and depth to experienced practitioners.

![](https://maja-kucharczyk.github.io/assets/img/rs.png)
[Kucharczyk et al. (2020)](https://doi.org/10.3390/rs12122012) [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

---

### [Pre-disaster mapping with drones: An urban case study in Victoria, British Columbia, Canada](https://doi.org/10.5194/nhess-19-2039-2019)

**Kucharczyk, M.**, & Hugenholtz, C. H. (2019). Natural Hazards and Earth System Sciences, 19(9), 2039–2051.

<kbd>SenseFly eMotion</kbd> <kbd>Pix4Dmapper Pro</kbd> <kbd>CloudCompare</kbd> <kbd>Google Earth Pro</kbd> <kbd>Esri ArcGIS</kbd> 

This study represents the first drone mapping mission over an urban area approved by Canada's aviation authority. The goal was to assess the quality of the pre-disaster 3D data in the context of geospatial accuracy and building representation. The images were acquired with a **senseFly eBee Plus fixed-wing drone** with real-time kinematic/post-processed kinematic functionality. Image processing with **structure-from-motion photogrammetry** produced digital surface models (DSMs) and 3D models. DSM vertical accuracy was assessed using 47 ground-surveyed checkpoints and **hypothesis testing**, while building representation in the 3D model was evaluated using **CloudCompare** and **Google Earth Pro**. Results indicated that the spatial accuracies achieved with this drone would allow for sub-meter building collapse detection, but the non-gimbaled camera was insufficient for capturing building facades.

![](https://maja-kucharczyk.github.io/assets/img/nhess.png)
[Kucharczyk & Hugenholtz (2019)](https://doi.org/10.5194/nhess-19-2039-2019) [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

---

### [UAV-LiDAR accuracy in vegetated terrain](https://doi.org/10.1139/juvs-2017-0030)

**Kucharczyk, M.**, Hugenholtz, C.H., & Zou, X. (2018). Journal of Unmanned Vehicle Systems, 6(4), 212-234.

<kbd>Trimble R4 GNSS</kbd> <kbd>Nikon DTM-522 Total Station</kbd> <kbd>CSRS-PPP</kbd> <kbd>Trimble Business Center</kbd> <kbd>Minitab</kbd> <kbd>IBM SPSS Statistics</kbd> <kbd>Esri ArcGIS</kbd>

We examined the horizontal and vertical accuracy of **light detection and ranging (lidar)** data acquired from a drone at a field site with six vegetation types: coniferous trees, deciduous trees, short grass, tall grass, short shrubs, and tall shrubs. Accuracy was evaluated using 20 horizontal and 445 vertical checkpoints surveyed with **real-time kinematic GNSS** and a **total station**, followed by **precise point positioning** GNSS processing, **Hough Transform**, and **hypothesis testing**. Results showed that horizontal accuracy and vegetated vertical accuracy at the 95% confidence level were 0.05 and 0.24 m, respectively. Median vertical errors significantly differed among 10 of 15 vegetation type pairs, highlighting the need to account for variations of vegetation structure. According to the 2015 American Society for Photogrammetry and Remote Sensing standards, the reported errors fulfilled the requirements for mapping at the 2 and 8 cm horizontal and vertical class levels, respectively.

![](https://maja-kucharczyk.github.io/assets/img/juvs2.jpeg)
[Kucharczyk et al. (2018)](https://doi.org/10.1139/juvs-2017-0030) [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

---

### [3-D stratigraphic mapping using a digital outcrop model derived from UAV images and structure-from-motion photogrammetry](https://doi.org/10.1130/GES01688.1)

Nesbit, P.R., Durkin, P.R., Hugenholtz, C.H., Hubbard, S.M., & **Kucharczyk, M.** (2018). Geosphere, 14(6), 2469–2486.

<kbd>SenseFly eMotion</kbd> <kbd>Pix4Dmapper Pro</kbd>

**Cited 50+ times**, this study examined the use of drone-based photogrammetry (structure-from-motion) for geologic mapping. We used **structure-from-motion** to develop a 3D digital outcrop model (DOM) of an Upper Cretaceous channel-belt sequence in Dinosaur Provincial Park (southeastern Alberta, Canada). Using the 3D DOM, we delineated the lower contact of the channel-belt sequence, created digital sedimentary logs, and estimated facies with similar conviction to field-based estimations (±4.9%). Overall, we found that measurements and observations derived from the 3D DOM were commensurate with conventional ground-based mapping techniques, but they had the added advantage of lateral continuity, which aided interpretation of stratigraphic surfaces and facies.

![](https://maja-kucharczyk.github.io/assets/img/geosphere.jpeg)
[Nesbit et al. (2018)](https://doi.org/10.1130/GES01688.1) [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

---

### [Reported UAV incidents in Canada: analysis and potential solutions](http://doi.org/10.1139/juvs-2016-0033)

Nesbit, P. R., Barchyn, T. E., Hugenholtz, C. H., Cripps, S., & **Kucharczyk, M.** (2017). Journal of Unmanned Vehicle Systems, 5(2), 51-61.

<kbd>Transport Canada CADORS</kbd>

To gain insight into the types of incidents that were occurring with small drones in Canada, we analyzed data from **Transport Canada’s Civil Aviation Daily Occurrence Reporting System (CADORS)**. Collectively, the CADORS data indicated that the overwhelming majority of drone incidents reported in Canada were airspace violations. The number of sightings dramatically increased after 2013, suggesting the problem of airspace infractions was real and increasing in prevalence. These results can guide future risk mitigation measures, hardware and software solutions, and educational campaigns to increase airspace safety.

![](https://maja-kucharczyk.github.io/assets/img/juvs.jpeg)
[Nesbit et al. (2017)](http://doi.org/10.1139/juvs-2016-0033) [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

---

### [Spatial accuracy of UAV-derived orthoimagery and topography: comparing photogrammetric models processed with direct georeferencing and ground control points](https://doi.org/10.5623/cig2016-102)

Hugenholtz, C.H., Brown, O., Walker, J., Barchyn, T.E., Nesbit, P.R., **Kucharczyk, M.**, & Myshak, S. (2016). Geomatica, 70(1), 21-30.

<kbd>Trimble R6 GNSS</kbd> <kbd>SenseFly eMotion</kbd> <kbd>Postflight Terra 3D</kbd> <kbd>Esri ArcGIS</kbd>

**Cited 100+ times**, this study compared the spatial accuracy of two nearly identical drones with differing onboard GNSS equipment: one with a survey-grade real-time kinematic (RTK) GNSS receiver (RTK drone), and the other with a lower-grade GPS receiver (non-RTK drone). Spatial accuracy was quantified using 17 horizontal and 180 vertical checkpoints surveyed with **RTK GNSS**, followed by **hypothesis testing**. The horizontal and vertical accuracy improved substantially with the RTK drone, effectively reducing the horizontal and vertical root-mean-squared error values by 1 to 2 orders of magnitude compared to the non-RTK drone. Importantly, the horizontal accuracy of the RTK drone data processed via direct georeferencing was equivalent to the horizontal accuracy of the non-RTK drone data processed with ground control points (GCPs), but the vertical error of the RTK drone data was 2 to 3 times greater than the vertical error of the non-RTK drone data with GCPs. Overall, these results suggested that direct georeferencing with the RTK drone can achieve a horizontal accuracy comparable to that obtained with a network of GCPs, but for topographic (vertical) measurements requiring the highest achievable accuracy, researchers and practitioners should use GCPs.

![](https://maja-kucharczyk.github.io/assets/img/geomatica.JPG)
[Hugenholtz et al. (2016)](https://doi.org/10.5623/cig2016-102)

---

## Outreach

### [Season 3 | Episode 12: GeoAI for damage assessment in the wake of a disaster](https://resources.esri.ca/geographical-thinking-podcast/season-3-episode-12-geoai-for-damage-assessment-in-the-wake-of-a-disaster)

**Podcast Guest.** (2023). Esri Canada Geographical Thinking Podcast.

I had an opportunity to be a guest on Esri Canada’s Geographical Thinking podcast, where I spoke with Guan Yue about using deep learning for post-disaster damage assessment.

<iframe allow="autoplay *; encrypted-media *; fullscreen *; clipboard-write" frameborder="0" height="175" style="width:100%;max-width:660px;overflow:hidden;border-radius:10px;" sandbox="allow-forms allow-popups allow-same-origin allow-scripts allow-storage-access-by-user-activation allow-top-navigation-by-user-activation" src="https://embed.podcasts.apple.com/ca/podcast/geoai-for-damage-assessment-in-the-wake-of-a-disaster/id1540357358?i=1000604553886&theme=light"></iframe>

---

### [Automated mapping of hurricane roof damage: An end-to-end Esri ArcGIS Pro workflow using deep learning and drone imagery](https://storymaps.arcgis.com/stories/61c60c6e67b04f8fade16adfaad74075)

**Kucharczyk, M.** (2023). ArcGIS StoryMaps.

Winning two awards from the International Statistical Institute and Esri, this story map describes my research on applying deep learning for detecting and delineating post-storm roof damage.

![](https://maja-kucharczyk.github.io/assets/img/roofs.jpg)
[Mark Yokoyama](https://flickr.com/photos/theactionitems/37201455634/) [(CC BY-NC-ND 2.0)](https://creativecommons.org/licenses/by-nc-nd/2.0/)

---

### [Canada's Conservation Tracker](https://esricanada-ce.github.io/appchallenge/2023/teams/ucalgary/Bow_Gees/)
Falahatkar, H., Ogunleye, S., & **Kucharczyk, M.** (2023). Esri Canada Centres of Excellence App Challenge.

I participated in the 2023 Esri Canada Centres of Excellence App Challenge, which is an annual one-week competition that engages teams of students at each of the Esri Canada GIS Centers of Excellence in the creation of innovative GIS applications using Esri technology and open data to address a specific theme. The theme of 2023 was "Conservation and Protected Areas or Urban Ecology". My team and I built Canada’s Conservation Tracker: an app that provides information about protected and other conserved areas in Canada. Overall, Canada’s Conservation Tracker supports the monitoring of Canada’s progress towards its 2025 conservation targets and allows users to investigate trends in conservation with respect to factors such as time, geography, and governance. I created the video below to introduce the app.

<iframe width="500" height="282" src="https://www.youtube.com/embed/aZlWpVRDyDk?si=M1CeC2s6TeMUIdtL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

### [Apply to become a Student Assistant at the 2023 Esri User Conference in San Diego](https://ecce.esri.ca/ucalgary-blog/2023/01/16/become-a-student-assistant-2023-esri-uc/)

**Kucharczyk, M.** (2023). Esri Canada Centres of Excellence Blog.

I wrote a blog post detailing my experience at the 2022 Esri User Conference, where I received an Esri Young Scholar Award, presented my deep learning research, and served as a student assistant.

![](https://maja-kucharczyk.github.io/assets/img/esri.jpeg)

---

### [Disaster-mapping drones often neglect deadliest, costliest events and hardest-hit areas](https://theconversation.com/disaster-mapping-drones-often-neglect-deadliest-costliest-events-and-hardest-hit-areas-165412)

**Kucharczyk, M.**, & Hugenholtz, C. H. (2021). The Conversation.

Following our publication of [Remote sensing of natural hazard-related disasters with small drones](https://doi.org/10.1016/j.rse.2021.112577), we published a journalistic article in The Conversation to share our work with the public.

![](https://maja-kucharczyk.github.io/assets/img/drone_fire.jpg)
[Brad Strobel/USFWS](https://www.rawpixel.com/image/11072839/photo-image-cloud-plant-fire) [(CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/)

---

### [The weather’s effects on commercial drones may hinder their widespread use](https://theconversation.com/the-weathers-effects-on-commercial-drones-may-hinder-their-widespread-use-162581)

**Kucharczyk, M.**, Hugenholtz, C. H., Gao, M., Nesbit, P. R., Barchyn, T. E., & Fox, T. A. (2021). The Conversation.

Following our publication of [Weather constraints on global drone flyability](https://doi.org/10.1038/s41598-021-91325-w), we published a journalistic article in The Conversation to share our work with the public.

![](https://maja-kucharczyk.github.io/assets/img/drone_winter.jpg)
[Wikimedia Commons](https://www.rawpixel.com/image/3337446/free-photo-image-aircraft-airplane-animal) [(CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/)

---

[Back to top](#top)
