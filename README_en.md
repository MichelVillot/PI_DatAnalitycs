# Project Presentation
Currently our client `Data MOOC Enterprise` wants to venture into the world of MOOCs, however, he buys information from other companies in order to have a clearer perspective of whether or not it will be profitable over time.

Our job as `Data Analyst` is to extract as much information as possible from our datasets, which have information from `Udemy`, `Coursera` and `Edx`.

# Analysis:

After extracting, visualizing and comparing these 3 big ones in the MOOC industry, it was possible to know the following information that could be a starting point for our client:
1) The Beginner difficulty level is a good starting point, it is in high demand as no prior knowledge is needed
2) The average price of a course is from $25 to $50 USD, therefore placing it at that amount would be an additional point
3) The predominant language is English in all categories and levels of difficulty.

#KIPs
* `Annual Total Levels`
   * `Objective`: Reach a minimum of 500 annual courses in the sum of all levels
   * `Operation`: In order to use said KPI you must use the `MOOC` and `Difficulty level` segmenters.
     
* `Total Annual Price Average`
   * `Target`: Have an average price of more than $500 per year in all difficulty levels.
   * `Operation`: In order to use said KPI you must use the `MOOC` and `Difficulty level` segmenters.
     ``
* `Annual Total Languages`
   * `Target`: Compare

* `Operation`: In order to use said KPI you must use the `MOOC` and `Difficulty level` segmenters.

* `Last Year vs Current Comparison` (Applies only to Coursera)
   * `Objective`: Compare the number of enrollees for the current year vs. the previous year with an increase of 20% over it.
   * `Operation`: In order to use said KPI, you must use the `MOOC` and `Year` segmenters.
 
# repository
`Directories`:
  * `Datasets_EDA` > Contains all transformed CSV files.
  * `Original_DataSets` > Contains all original files provided by Henry and additional files found on Kaggle
  * `Notebooks`:
      * coursera_v1.ipynb > notebook with all the transformations and graphs made to the "coursera" dataset
      * coursera_v2.ipynb > notebook with all the transformations performed on the "coursera_v1" dataset
      * eda_final > notebook with the final transformations of each dataset to obtain the same combinations
      * edx.ipynb > notebook with all the transformations and graphics made to the "edx" dataset
      * udemy.ipynb > notebook with all the transformations and graphs made to the "udemy" dataset
  * `Datasets_DB and Dashboard` > These files were uploaded to the cloud due to weight and the maximum supported by Github.
      * Link: https://drive.google.com/drive/folders/13f7NhO_3yTjFj9N4Tq2NO5PYHwtFaCFp?usp=sharing
