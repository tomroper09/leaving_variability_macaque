Code for analysing the leaving variability in Macaques performing a foraging task.

All analysis is within the jupyter notebook.

To download the data required you need to head to this url:
`https://figshare.com/articles/dataset/Data_zip/11839281?backTo=%2Fcollections%2FOverstaying_in_patchy_foraging_can_be_explained_by_behavioral_variability_Cash-Padgett_Hayden_2020_%2F4852557&file=21682743`


Note: In this task technically the patches in the task are identical, because the inital yield of reward is identical every single time. However, the travel time between patches varies, which might influence how the monkeys are behaving. For example, a longer travel time might be associated with the monkey spending longer in the next patch. In the data provided on the figshare link there is no field to track the travel time. This means we can't investigate whether the travel time is associated with different patch residency time (leading us to something like different patch types), so for the purposes of these analyses I have just lumped together all patches into one. Also, I have focused on monkey C as this monkey has the most sessions and data is in raw format for analysis.