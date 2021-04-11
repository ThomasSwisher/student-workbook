# Read Asynchronous Code > JavaScript Promises and answer the following questions
1. What are the three states of a Promise?

Pending: Initial State, before the Promise succeeds or fails
Resolved: Completed Promise
Rejected: Failed Promise

2. How do promises seek to resolve the issues of "callback hell"?

If we have multiple async operations  we can use promises to them to wait for the return rather than passing them. This way we can move on to other operations as we wait for the callback to return its response. And it is easier to read.

3. What is the difference between .then() and .catch()?

.then() is if the promise is resolved and them is used to decide what will happen after it is resolved.
.cathc() is used when the promise fails then we need get catch the failure so we can further evaluate our next steps to address how we want to proceed.

https://thomasswisher.github.io/spring21-gregslist-mvc/