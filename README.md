# Mute

### Goals
The goals of this project are entirely personal educational.  I want to examine how to architect a project as well as concepts like TDD (test-driven development).  This project is not for production use

### Concept
The concept is to create a library that can truncate sensitive data such as removing IP addresses from a log file.  There are two three main use-cases
1.  Removing data in an application
2.  Removing data after the fact, such as truncating entries in a file
3.  Removing data that is being passed in via stdin.  

Cases 1 will require a module.  Cases 2 and 3 will be done via a cli interface instead of a `npm run`.