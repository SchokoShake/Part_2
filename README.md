Add the datasets folder locally, as the files are big *-*


Changes in the assignment, these are in the "updated" versions:
- Q1 d-e)
	- The following changes were applied:
	- Figure 1 will be added as additional material.
	- Subtask 1d) and 1e) will be swapped in their ordering.
	- The phrasing of the former Question 1d) will be changed to: "In this task, we want to impute missing values based on their k-nearest neighbor. Therefore, as a first step, create a reduced dataframe that contains the column(s) with missing values and with columns that correlate with the missing value. To decide which features (weakly) correlate, consider the correlation matrix in the figure below that is taken from literature (Source: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10417090/). Consider all features that have an absolute value for the correlation coefficient of at least 0.1 with the missing value."
- Q2 Part 2 e): Added the following specification to the first sentence to make the question clearer: "based on the frequent itemsets with a support of at least 0.03 ('frequent_itemsets')."
- Q4) Fixed that Data Loading and Preprocessing gives 8 pts as planned and Set of Words give 6.5. All points of Q4 now sum up to 23 pts.
- Q4 f) [https://moodle.rwth-aachen.de/mod/forum/discuss.php?d=225759#p357488] Added additional hint: "Note: To keep the complexity low, we do not expect you to use POS tagging before lemmatizing. You can apply lemmatization only for the nouns. This is covered by using a lemmatizer without further arguments."
- Q4 m) [https://moodle.rwth-aachen.de/mod/forum/discuss.php?d=225497#p356825] Changed references: task a4) to d) and b3) to l).
- Q4 n) [https://moodle.rwth-aachen.de/mod/forum/discuss.php?d=225027#p356281] Specified again that the index comes from the swift_df.
- Q4 o) [https://moodle.rwth-aachen.de/mod/forum/discuss.php?d=226193#p357831] Added info to use epoch=100.
- Q4 q) [https://moodle.rwth-aachen.de/mod/forum/discuss.php?d=226193#p357831] Added info to use euclidean distance.
- Q4 r) [https://moodle.rwth-aachen.de/mod/forum/discuss.php?d=226193#p357831] Added: "Note: You do not have to find exactly two clusters. Having at least two clusters, you should show the lyrics from two distinct clusters."
- Q4 u) [https://moodle.rwth-aachen.de/mod/forum/discuss.php?d=225631#p357485] Added additional hint: "Reminder / Hints: A lyric generated by an n-gram starts with n-1 times the start token "\<s>" and ends with n-1 times the end token "\</s>". Further, the n value of an n-gram can be accessed using the `n-gram.order` variable of an `n-gram`. Additionally keep in mind that you can condition the generation of your n-gram on some preceding text."
- Q5 a): Extended the hint a bit to be even clearer that the function _reduces_ to the un-weighted moving average.
- Q5 c): Clarified that we do not consider event-time vs. processing time in batching calculation. The latter is intended as it is simpler in this context. Either is fine regarding grading.
