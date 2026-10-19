# PLP Python Week 6: Error Handling

## Files Included
* safe_tools.py
  Functions: safe_divide, safe_number, 
  and get_field using try/except.
* safe_tools_output.png
  Screenshot showing execution results.

## Reflection
Question: Why can't an if check catch 
int("abc") on its own?

Answer: An if check evaluates conditions 
before execution, whereas converting "abc" 
to an integer raises a ValueError at 
runtime. A try / except block is necessary 
to catch and handle this runtime exception 
without causing the program to crash.