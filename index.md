## When you would use a SQL UDF
A **User Defined Function (UDF)** is a customized function, which are often best used when there is a specific repetitive task to complete within SQL code. A UDF can be used to return a table, essentially as a SELECT statement, but is commonly used when used to compute or transform incoming variable data. 

## Differences between Scalar, Inline, and Multi-Statement Functions
A **Scalar function** returns a single value.

An **Inline function** is similar to a view in that an inline function can only contain a single SELECT statement and the columns of that statement carry into the returned data.

A **Multi-Statement function** does what it says on the tin: the function stores a more than one statements and executes them in a defined order. A multi-statement function might aggregate data, clean strings, and then alter a view to add the newly transformed data.
