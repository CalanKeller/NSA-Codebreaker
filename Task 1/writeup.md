# Task 1 - Find the Unknown Object - (General programming, database retrieval)
```The US Coast Guard (USCG) recorded an unregistered signal over 30 nautical miles away from the continental US (OCONUS). NSA is contacted to see if we have a record of a similar signal in our databases. The Coast guard provides a copy of the signal data. Your job is to provide the USCG any colluding records from NSA databases that could hint at the object’s location. Per instructions from the USCG, to raise the likelihood of discovering the source of the signal, they need multiple corresponding entries from the NSA database whose geographic coordinates are within 1/100th of a degree. Additionally, record timestamps should be no greater than 10 minutes apart. ```

This task took me around 4 to 5 minutes start to finish. 
I downloaded the task files (USCG.log and database.db), which it was clear from what to do. 
I downloaded a database exploration tool (https://sqlitebrowser.org/) and from there looked for the entries that matched the description of "geographic coordinates are within 1/100th of a degree." 
Only database entries 414 and 754 matched that description.
