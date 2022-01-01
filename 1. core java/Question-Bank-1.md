# Core Java Interview Questions
## Question Bank 1

1.  <strong>What is static initializer block?</strong> <br/>
    The static initializer is a static {} block of code inside java class, and run only one time before the constructor or main method is called.

2. <strong>Where the static blocks get stored in memory?</strong> <br/>
    Static methods are stored in the `Metaspace space of native heap` as they are associated to the class.

3. <strong>Externalization in Java</strong><br/>
    Externalization is used whenever we need to customize serialization mechanism. If a class implements Externalizable interface then, object serialization will be done using writeExternal() method. 


4. <strong>Heap memory in Java</strong><br/>
    Heap memory is the run time data area from which the memory for all java class instances and arrays is allocated. The heap is created when the Java Virtual Machine (JVM) starts up and may increase or decrease in size while the application runs. The size of the heap can be specified using -XmsVM option.

5. <strong>Garbage collection in Java</strong><br/>
    Garbage collection is process of reclaiming the runtime unused memory automatically. In other words, it is a way to destroy the unused objects.

6. <strong>System.gc()</strong><br/>
    The java.land.System.gc() method runs the garbage collector. Calling this suggests that the JVM expend effort toward recycling unused objects in order to make the memory they currently occupy available for quick reuse.

7. <strong>How to avoid deadlock?</strong><br/>
    We may try to avoid deadlock by the following ways: <br/>
    - <strong>Avoid unnecessary locks:</strong> We should use locks only for those members on which it is required. Unnecessary use of locks leads to a deadlock situation. We recommend you to use a lock-free data structure. If possible keep your code free from locks. For example, instead of using synchronised ArrayList, use the ConcurrentLinkedQueue.
    - <strong>Avoid nested locks</strong>: Another way to avoid deadlock is to avoid giving a lock to multiple threads if we have already provided a lock to one thread. Since we must avoid allocating a lock to multiple threads.
    - <strong>Using Thread.join() method</strong>: You can get a deadlock if 2 threads are waiting for each other to finish indefinitely using thread join. If your thread has to wait for another thread to finish, it's always best to use join with the mazimum wait time you want to wait for the thread to finish.
    - <strong>Use lock ordering</strong>: Always assign a numeric value to each lock. Before acquiring the lock with a higher numeric value, acquiring the locks with lower numeric value.
    - <strong>Lock time-out</strong>: We can also specify the time for a thread to acquire a lock. If a thread does not acquire a lock the thread must wait a specific time before retrying to acquire a lock.

8. <strong>Ways to create a thread</strong><br/>
    - Extending Thread class
    - Implementing Runnable interface

9. <strong>Can we synchorize process? (not threads)</strong><br/>

10. <strong>What is re-entrant lock?</strong><br/>
    ReentrantLock allows thread to enter into the lock on a resource more than once.

11. <strong>Use of generics in core java</strong><br/>
    Generics usually provide compile-time type safety that allows programmers to catch invalid types at compile time.

12. <strong>What is type erasure in generics?</strong><br/>
    Type erasure is a process in which compiler replaces a generic parameter with actual class or bridge method. In type erasure, compiler ensures that no extra classes are created and there is no runtime overhead.

13. <strong>What is functional interface and how is it related to lambda?</strong><br/>
    Lambdas simplify the use of interfaces that declare single abstract method.

14. <strong>What is obfuscation(making jar not to decompile) and how to do it?</strong><br/>