# 1
Exercise1:: ![[Pasted image exercise1.png]]

# 2

Exercise2:: ![[Pasted image exercise2.png]]
# 3
```
bad_vector_new() error:
  size represents the size of vector so the the size of v.data should be equal to  malloc(sizeof(int) *v.size);
  
  also_bad_vector_new has the same error with the function bad_vector_new;

valgrind --tool=memcheck --leak-check=full --track-origins=yes [OS SPECIFIC ARGS] ./<executable>
--tool=memcheck:default tool for detecting memory-related errors
--leak-check=full:detail infomation about memory leaks
--track-origins=yes : track the uninitialized values.
```

Exercise3:: ![[Pasted image exercise3.png]]