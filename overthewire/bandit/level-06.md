# Bandit Level 05-06

## Objective
-Find a password based on properties

## Approach
-Used man to find out out to use find further than before

## Commands / Tools

```bash
cd inhere
find -readable -size 1033c ! -executable
```
Reasoning 
- find looks for files
- readable looks for readable files
- size looks for size, 1033 is the value, c is bytes
- ! -executable means NOT executable
  
Result - Resolved level 6 password

What I learned
-How to find files via properties
