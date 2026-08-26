# Bandit Level 06-07

## Objective
-Find a password based on properties

## Approach
-Used man to find out out to use find further
-Used -user and -group

## Commands / Tools

```bash
find / -type f -user bandit7 -group bandit6 -size 33c 2>dev/null
```
Reasoning 
- find looks for files
- -user sorts by owner/user
- -group sorts by group
- -size filters by size
- 2>dev/null removes all failed outputs

Result - Resolved level 7 password

What I learned
- How to use find properties to find a more hidden file
