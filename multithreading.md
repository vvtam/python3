#### Summary

- Python supports 2 modules for multithreading:
  1. **__thread** module: It provides a low-level implementation for threading and is obsolete.
  2. **threading module**: It provides a high-level implementation for multithreading and is the current standard.
- To create a thread using the threading module, you must do the following:
  1. Create a class which extends the **Thread** class.
  2. Override its constructor (__init__).
  3. Override its **run()** method.
  4. Create an object of this class.
- A thread can be executed by calling the **start()** method.
- The **join()** method can be used to block other threads until this thread (the one on which join was called) finishes execution.
- A race condition occurs when multiple threads access or modify a shared resource at the same time.
- It can be avoided by Synchronizing threads.
- Python supports 6 ways to synchronize threads:
  1. Locks
  2. RLocks
  3. Semaphores
  4. Conditions
  5. Events, and
  6. Barriers
- Locks allow only a particular thread which has acquired the lock to enter the critical section.
- A Lock has 2 primary methods:
  1. **acquire()**: It sets the lock state to **locked.** If called on a locked object, it blocks until the resource is free.
  2. **release()**: It sets the lock state to **unlocked** and returns. If called on an unlocked object, it returns false.
- The global interpreter lock is a mechanism through which only 1 CPython interpreter process can execute at a time.
- It was used to facilitate the reference counting functionality of CPythons's garbage collector.
- To make Python apps with heavy CPU-bound operations, you should use the multiprocessing module.