Trends in startups project

Contains: 
Aggregate function performs a calculation on a set of values, and returns a single value. Except for COUNT(*), aggregate functions ignore null values. Aggregate functions are often used with the GROUP BY clause of the SELECT statement.

All aggregate functions are deterministic. In other words, aggregate functions return the same value each time that they are called, when called with a specific set of input values. See Deterministic and Nondeterministic Functions for more information about function determinism. The OVER clause may follow all aggregate functions, except the STRING_AGG, GROUPING or GROUPING_ID functions.

Use aggregate functions as expressions only in the following situations:
  - The select list of a SELECT statement (either a subquery or an outer query).
  - A HAVING clause.
