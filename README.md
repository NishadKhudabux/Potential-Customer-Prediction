# Potential-Customer-Prediction
A critical problem in EdTech is converting potential customers into paid customers. Performed EDA to identify the key factors driving the lead conversion process and built an ML model (using Decision Trees and Random Forest) that identifies which leads are more likely to convert.

Three features where identified as major drivers of lead convertability:
* **time spent on website** - Where more time is spent on the website suggests a predict likelyhood.
* **first_interaction_website** - Where interacting with the website rather than the app predict a greater likelyhood.
* **profile_completed**  - Where profiles completed above the medium level suggest a predict a greater likelyhood. 

From testing five different models, the hyper tuned random forest model showed the highest efficacy with a recall rate of 85%.
