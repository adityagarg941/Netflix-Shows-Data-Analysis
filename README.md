# Netflix-Shows-Data-Analysis

In this Dataset I have done Data cleaning, Data Processing and multiple techniques on the Dataset.
Indentified missing values and handled them in columns as follows:- 

director - 	2,634	(Filled with "Unknown" text.)
cast -	825	(Filled with "Not listed" text.)
country -	831	(Filled with mode (most frequent country) or "Unknown" if no strong preference.)
date_added -	10	(Filled with mode value)
rating - 4	(Filled with mode (e.g., most common rating).
duration - 3	Depends on type (Movie/TV Show); filled with mode per type.

After this I have removed duplicate rows using .drop_duplicates() 
Converted date formats to a consistent type (e.g., dd-mm-yyyy).
Renamed column headers to be clean and uniform (e.g., lowercase, no spaces).
