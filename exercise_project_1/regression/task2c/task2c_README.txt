HIGH CARDINALITY

ydata is useful in this one as well!

pandas df.value_counts() / nunique() are also useful, but you have to use 
it separately for each categorical variable!

Look for categorical variables that have many options
in the values (usually more than 10) => high cardinality

If you see a word cloud in the variable (in ydata), 
this also implies extremely high cardinality.