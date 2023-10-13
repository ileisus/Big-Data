
1. About Spark [5 points] 
Answer each of these questions in no more than 2-3 sentences: 
1. [1 points] Why do operations such as count and collect sometimes take a long time whereas filter and join return almost instantaneously?

2. [2 points] Why would Scala have been preferred over more popular languages like Python for implementing Spark? 
- Scala is faster than Python, specifically because:
        - Scala uses static typing (variable types are explicitly declared and determined at compile time) while Python uses dynamic typing 
        - Scala is a functional programming language while Python supports OOP 
        - Scala is a compiled language while Python is interpreted
- Scala's concurrency support, which is crucial to parallelization when handling large datasets 


3. [1 point] “The DAG is a great fault tolerance mechanism but can occasionally result in long delays for fault recovery.” Why would this be true? 

4. [1 point] Checkpointing saves on the “long delays for fault recovery.” Why would this be true? 
