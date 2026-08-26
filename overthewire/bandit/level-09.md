# Bandit Level 08-09

## Objective
-Find the only unique string in a text file

## Approach
-use man on sort and uniq
-use piping
## Commands / Tools

```bash
man sort
man uniq
sort data.txt | uniq -u
```
Reasoning 
-sort orders strings alphabetically so duplicate strings are adjacent, | joins to commands, uniq -u looks for unique strings

Result - Resolved level 9 password

What I learned
-How to sort text files
-How to find unique strings
