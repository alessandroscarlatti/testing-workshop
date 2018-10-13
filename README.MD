# Testing

## The data flow
We start with a "book".
Break it into words.

All words turned into uppercase.
Each compound word (word more than 5 characters) is 
broken apart and stored separately.

How would I test this?

If I want to reassure myself that the software actually works
what will I actually do?

I would want to run a "bootRun" sort of task just to see that it works.

For this to work I would need "book" data.
I would then be able to run the "bootRun" sort of task.
Then I would inspect the results (console output)
to see if the data I expect is there.
Even more inconvenient, I might have to check file locations
or query a database.

After I've been away from the software for a long time checking a database
is something that I won't believe still works.  I will want to confirm
that is actually working.

I can automate bootRun with a @SpringBootTest.  Not a problem.