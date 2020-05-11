# multivariate_freq_dist

When you use the crossstab function in Python, you get a pivot table of two variables. 
The index of this pivot table consists of the index parameter in which you write the pivot table function. 
When we want these index values to be a frequency distribution range, the crosstab or pivot functions in Python cannot 
respond to this need. This function is written to meet this need and is a pivot table function where two variables can be 
indexed with statistically significant frequency distribution ranges.

# Use of:

The function takes 4 parameters: <br/>
**given_df** = dataframe <br/>
**given_series1**= column of dataframe where you want the pivot table to index <br/>
**given_series2**= the column you want the dataframe to come into the columns of the pivot table <br/>
**m**= how many intervals the frequency distribution will consist of; <br/>
    If m = None, it divides statistically significant frequency ranges by default. <br/>
    

multivariate_freq_dist(given_df, given_series1, given_series2, m)

# Example:
Please upload the data file in the files section.
df=pd.read_excel('data.xlsx')
Then write the following command:
multivariate_freq_dist(df, 'bioistatistik_notu', 'lise_basarisi', 5)


<img src="/images/multivariate_freq_dist_for_github.png" 
data-canonical-src="https://user-images.githubusercontent.com/28653377/75344783-65936880-58ac-11ea-97fd-ccd0f62b7c51.png" />



