### Summary:

- The yield keyword in python works like a return with the only difference is that instead of returning a value, it gives back a generator function to the caller.
- A generator is a special type of iterator that, once used, will not be available again. The values are not stored in memory and are only available when called.
- The values from the generator can be read using for-in, list() and next() method.
- The main difference between yield and return is that yield returns back a generator function to the caller and return gives a single value to the caller.
- Yield does not store any of the values in memory, and the advantage is that it is helpful when the data size is big, as none of the values are stored in memory.
- The performance is better if the yield keyword is used in comparison to return for large data size.