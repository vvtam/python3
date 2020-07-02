### Summary:

- Python sleep() function will pause or delay the execution of code for the number of seconds given as input to sleep(). The sleep() function is part of the **time** module.
- You can make use of sleep() function when you want to temporarily halt the execution of your code. For example, in case you are waiting for another process to complete, or a file upload, etc.
- There are many ways to add delay to code besides sleep, and they are using asyncio.sleep , Event().wait and Timer.
- Similar to sleep() method, there is asyncio.sleep() method with python version 3.4 and higher. To make use of the asyncio sleep method, you need to add async and await to the function
- The Event().wait method comes from the threading module. Event.wait() method will halt the execution of any process for the number of seconds it takes as an argument.
- The Timer is another method available with Threading, and it helps to get the same functionality as sleep