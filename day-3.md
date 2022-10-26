# Readings

**Reading**

- Primitives vs. Objects

![2022-10-25 (8)](https://user-images.githubusercontent.com/108303424/197927436-493f9e32-5300-4eab-8f6f-4ff2a3a757c0.png)

- Exceptions in Java (read the first three sections on the left: What is an Exception, The Catch or Specify Requirement, Catching and Handling Exceptions)

When an error occurs within a method, the method creates an object and hands it off to the runtime system. The object, called an exception object, contains information about the error, including its type and the state of the program when the error occurred. Creating an exception object and handing it to the runtime system is called throwing an exception.After a method throws an exception, the runtime system attempts to find something to handle it. The set of possible "somethings" to handle the exception is the ordered list of methods that had been called to get to the method where the error occurred. 


![2022-10-25 (10)](https://user-images.githubusercontent.com/108303424/197928200-6601a0b7-6248-44b4-9fc0-78b124ae3b5a.png)
![2022-10-25 (11)](https://user-images.githubusercontent.com/108303424/197928217-ee6b7eb0-6f1e-4251-9068-3b47fa7cc0b4.png)

- Using Scanner to read in a file in Java

A simple text scanner which can parse primitive types and strings using regular expressions.
A Scanner breaks its input into tokens using a delimiter pattern, which by default matches whitespace. The resulting tokens may then be converted into values of different types using the various next methods.

## Things I want to know more about.

- Specificity involving return statements.


