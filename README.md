# StataTools
My user-written commands/packages for data analysis in Stata

The included packages are:
- `exampleobs` prints (randomly selected) example observations and optionally stores the values in a local macro. This is useful to explore possible values of a variable in your data set without being biased by the ordering of the data.
- `head` prints the head observations (first observations in data set) and mimics the `head()` function in R and `head` command in Linux.
- `randomselect` randomly selects observations and marks them with a dummy variable. It differs from `sample` in that it does not drop the non-selected observations from the data set, and that either individual observations or other units, defined by a variable in the data set, can be randomly selected.
- `tail` prints the tail observations (last observations in data set) and mimics the `tail()` function in R and `tail` command in Linux.

These packages can be downloaded directly through Stata using `ssc install <package_name>, replace`
