# introduction

These project stages will enable you to learn how to build a database system. You will build a working single-user DBMS that can execute certain simple SQL queries. The objective is to learn how a DBMS is organized and what goes on inside it when queries are executed. We will help you out by supplying the topmost and lowermost DBMS layers. The topmost layer is a parser that parses SQL queries and calls appropriate functions in the lower layers to perform relational operations. The lowermost layer is the disk I/O layer which reads and writes pages from and to the disk. In your case, the disk will just be the UNIX file system.  

At the end of each stage we will take a checkpoint and evaluate your work.  In Stage 3 you will implement a buffer manager.

# project website

https://pages.cs.wisc.edu/~anhai/courses/564/minirel-project/
