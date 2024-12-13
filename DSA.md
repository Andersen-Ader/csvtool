The dataset currently analyzed is a hyperspecific csv with only three columns and a number of rows set by the user.  When finished the software will be able to tell the user the number of rows and columns in any given csv and what the fields are called in the header line. 

Eventually the interface will be in the form of `csvtool [options] <filename>` where options will be the various special options for output, such as tell me the number of lines or tell me the data format and filename will be the csv to be converted into a sqlite3 db.  

Currently the languages are just going to be C with sqlite3's inbuilt C function calls being used for the db construction.  

No teammates currently.   
