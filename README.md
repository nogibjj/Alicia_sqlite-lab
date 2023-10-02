## SQLite Lab

### Goal:

* Use Copilot to support me writing the code.
* ETL-Query:  [E] Extract a dataset from URL, [T] Transform, [L] Load into SQLite Database and [Q] Query
For the ETL-Query lab:
* [E] Extract a dataset from a URL on github 
* [T] Transform the data by cleaning, filtering, enriching, etc to get it ready for analysis.
* [L] Load the transformed data into a SQLite database table using Python's sqlite3 module.
* [Q] Write and execute SQL queries on the SQLite database to analyze and retrieve insights from the data.

#### Tasks:

* Fork this project and get it to run
* Make the query more useful and not a giant mess that prints to screen
* Convert the main.py into a command-line tool that lets you run each step independantly
* Fork this project and do the same thing for a new dataset you choose
* Make sure your project passes lint/tests and has a built badge
* Include an architectural diagram showing how the project works

#### Reflection Questions

* What challenges did you face when extracting, transforming, and loading the data? 
I need to not only write the SQL query but also learn how to write python code to pack SQL code.
* What insights or new knowledge did you gain from querying the SQLite database?
The Primary key is very important value which can be used to locate where I should update my data value.
* How can SQLite and SQL help make data analysis more efficient? What are the limitations?
For the fix process, it can be really fast and automatically deploy within a second, but if there is any change, the whole structure
will have to change for it, that will cost a lot of labor.
* What AI assistant did you use and how did it compare to others you've tried? What are its strengths and weaknesses?
I used copilot, I think the prompt code it generate is really helpful even I am in different document, it still can follow my thought,
that's really amazing.

#### Here is my .lib file

I seperate the action into 4 parts to help me do CRUD wth SQL

<img width="248" alt="Screenshot 2023-10-01 at 10 59 47 PM" src="https://github.com/nogibjj/IDS706_Alicia_miniproject2/assets/143651934/5d3cda63-d594-482e-be0e-f9c520be6f16">

#### Extract the file

<img width="685" alt="Screenshot 2023-10-01 at 11 16 34 PM" src="https://github.com/nogibjj/IDS706_Alicia_miniproject2/assets/143651934/fe33e81a-96b8-4847-86a5-820c8eda9ad2">

#### Create a function

`Create_Records` to create records in database
`Update_Records` to change the contents in each column
`Delete_Records` to delete the records in database
`Read_Data` to read the file into database
