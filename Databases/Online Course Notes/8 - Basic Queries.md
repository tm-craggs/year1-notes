
You can use SELECT to select which column you want to get data from

For example:

SELECT *
FROM student; 

This would return each entry in its entirety. However,

SELECT name
FROM student;

This would only return the names of all students. 

You can also prepend these with the name of the table
For example:

SELECT student.name, student.major
FROM student;

This can help with making queries clearer in large databases with multiple tables. 

Another command is ORDER BY

SELECT student.name, student.major
FROM student
ORDER BY name;

This will return the names and majors, in alphabetical order by name. 
DESC can make the list in reverse order. 