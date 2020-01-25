# ProjectOne

# Link to the source of the data: https://www.bjs.gov/developer/ncvs/index.cfm

# Link to the index of terms: https://www.bjs.gov/developer/ncvs/personalFields.cfm
# Please note that while it is not listed in the index, the Hispanic origin, Marital status, and Region columns do contain "Unknown" variables as this will affect any data that you pull from those columns. 

# An additional note ragarding the clean_data. The amounts in the Household income column display oddly when in a dataframe due to the way that Python reads the dollar signs in the text fields. When dealing with that column, enter the row values as they appear in the index of terms and not as they are displayed in the dataframe. 