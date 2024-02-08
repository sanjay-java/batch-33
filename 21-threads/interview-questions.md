#### How do you create a thread in Java?
 - There are two main ways to create a thread in Java.
    - By extending the Thread class and overriding its run() method.
    - By implementing the Runnable interface and passing it to a Thread object.

#### Explain the synchronized keyword in Java.
- The synchronized keyword in Java is used to create synchronized blocks of code or methods to ensure that only one thread can execute them at a time. It prevents concurrent access to shared resources and maintains data integrity.

#### What are the Thread states in Java?
- The thread states in Java include:
    - New
    - Runnable
    - Blocked
    - Waiting
    - Terminated

#### What is deadlock in Java? How can it be avoided?
- Deadlock in Java occurs when two or more threads are blocked indefinitely, waiting for each other to release resources. Deadlocks can be avoided by ensuring a consistent ordering of resource acquisition, using timeout mechanisms, and avoiding nested locks.