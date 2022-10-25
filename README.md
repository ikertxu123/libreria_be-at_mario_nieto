# libreria_beñat_mario_nieto
This library has 3 functions with which you can manage lists or columns of dataframes.
You can impute, operate and filter.


**1. impute**(list1,method="_zero_")
With this function all null values are found and imputed by the selected method.

****Parameters****:
  - **list1** : list-like
      A list or a column of a dataframe 
  - **method** : {"_zero_", "_mean_", "_median_"}, default "_zero_"

    - "_zero_"
        All null values are imputed by 0
    -"_mean_"
        All null values will be imputed by the average of the list
    -"_median_"
        All null values will be imputed by the median of the list.
      
****Returns****:
  Returns the original imputed list


**2. column_operation**(listas,method="_concat_")

****Parameters****:
  -listas
  -method
  
****Returns****:


**3. filtering**(dataf,list1,filter,method=="_equal_")

****Parameters****:
  -dataf
  -list1
  -filter
  -method

****Returns****:


