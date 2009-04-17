
SQL Store
=========

RESTFUL (like) SQL Lite Wrapper for Storing Data - Key Value Pair
-----------------------------------------------------------------

    sql.get(key, callback); // callback will return the elements value 
    sql.post(key, value);    
    sql.put(key, value);
    sql.del(key);
    sql.exists(key,callback); // callback will return true or false
    sql.cleat(); clears the db