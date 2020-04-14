#  Database normalization
 
 is a process used to organize a database into tables and columns.  The main idea with this is that a table should be about a specific topic and only supporting topics included.

# Reasons for Database Normalization
-eliminate redundant data (storing the same data in more than one table) 
-ensure data dependencies make sense (only storing related data in a table).

# Insert Anomaly
An Insert Anomaly occurs when certain attributes cannot be inserted into the database without the presence of other attributes. For example this is the converse of delete anomaly - we can't add a new course unless we have at least one student enrolled on the course.

# Update Anomaly
 is a data inconsistency that results from data redundancy and a partial update. For example, each employee in a company has a department associated with them as well as the student group they participate in.


 # Deletion Anomaly
  A deletion anomaly occurs when you delete a record that may contain attributes that shouldn't be deleted. For instance, if we remove information about the last account
