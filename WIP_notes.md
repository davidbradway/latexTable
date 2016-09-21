These are notes to resume adding multicolumn support to latexTables.

- I started looking at the number of data columns in each labeled header column
- To implement multicolumn (and multi-row?) one should analyze the data size then set the multi as needed
- This does not allow for nested cell arrays as Pete propsed. That would require recursion and ugliness
- I submitted a few Pull Requests to the developer, mostly for typos.
- If he accepts maybe I can submit the change from table2array to table2cell as a PR
