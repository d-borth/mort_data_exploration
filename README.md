# Exploratory Analysis of 2018 National Vital Statistics Mortality Data
This repo is comprised of the parsing and initial exploratory analysis of all US mortality data from 2018.

* First, use the **2018_mort_to_csv** notebook to parse the 2018 mortality data.

* Once in (parsed) csv format, the data can then be read-in using the **mort_data_ml_exploration** notebook.

NOTE:

This repo represents the initial phase of my dissertation work towards employing machine learning methods that aid in identifying the underlying causes of suicides. Herein is demonstrated a method for training a (Random Forest) classifier model to distinguish between 6 different classes (causes of death) using 77 unique features for each of the +/-1.7M deaths identified with a known cause of death. It is proposed that this model, trained on national data, could then be evaluated for differences in performance when used to predict suicide cases at the state level and below. For example, a lower model performance would indicate that each state and region are merely peaces of the whole and not individually representative of the overall average. Each sub-population will have distinguishable characteristics that would require specific policy and approaches specific to that locality to be effective at that level. This is the first step towards that premise.

LIMITATIONS:

Regardless of the technique, we are only limited to the data that is available, and the results and analysis should be viewed as such. It is also not expected that a machine learning model will make crystal clear all cases and causes for suicide, but instead potentially illuminate previously unknown factors, while also opening the discussion to what we think we know and how we approach developing effective public health policy and solutions.
