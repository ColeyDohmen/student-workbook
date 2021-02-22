2/22/2021
Read Asynchronous Code > Callback Hell and answer the following questions

What are some of the signs and causes of Callback Hell? 
A sign of Callback Hell is when you see all of the } and ) at the end of your code. This is caused when people write JS where execution happens from the top down.

What does the asynchronous mean and how are callbacks involved?
Asynchonous means 'takes some time' or 'happens in the future, not right now'. Callbacks are used to handle async functions so that your program doesn't stop while waiting for that function to finish whatever it needs to do.

Summarize the 3 ways to avoid / fix Callback Hell
You can keep your code shallow (ex. like naming functions), you can modularize (or create libraries), and lastly you could handle every error.