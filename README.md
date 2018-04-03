What the code does:
- take the newest txt file matching with the name put in argument
- save a new sorted file by values in 'Clicks' column (descending)
- combine sorted list by "Keyword Unique ID" (in all cases will return the same list beacuse in arguments puts only one enumerator)
- change values for columns "number of commissions", "Commission Value", "ACCOUNT - Commission Value", "CAMPAIGN - Commission Value", "BRAND - Commission Value", "BRAND+CATEGORY - Commission Value", "ADGROUP - Commission Value", "KEYWORD - Commission Value" depends on variables modification_factor and cancellaction_factor
- save list with the new values into new file (with max 120000 lines, if has more will create another file with incremented index)
------