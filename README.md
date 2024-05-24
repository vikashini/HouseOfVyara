Friday, May 24, 2024
10:42 AM

Had a requirement to write a store procedure to add conditions based on the input's from JSON file.

	1. If we have values satisfying the join condition and where condition we need to execute a select query adding those values and move the selected values into temp table
	2. If at least one condition fails we need to select the values based on other satisfying conditions.
If no values are satisfying the we need select all the values(where 1=1).![image](https://github.com/vikashini/MySqlLearnings/assets/9973800/c1d30ad5-e7ab-4487-8998-d19be8360d59)
