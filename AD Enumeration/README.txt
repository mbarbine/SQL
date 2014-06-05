Using these two stored procedures build out a view that you can export to 
another source. Your tool of choice is up to you on how to interface with raw data.

I prefer Crystal Reports. 

I also execute these as SQL stored procedures, however, they can be converted to 
another querying or scripting language and output to a flat file or other.

____________________________


Intended use:


You SORT by Group 
and list all of the users WHERE that group is assigned.



The results look like this 



Domain Admins (group)

	Michael barbine
	John Doe
	Paula John

Exchange Admins (group)

	Michael barbine
	John Doe
	Paula John


Accounting (Group) 


	Michael barbine
	John Doe
	User #3
	User #4 
