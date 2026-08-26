# Bandit Level 11-12

## Objective
-Find password in Rot13 Encoded data

## Approach
-use man on tr
-use set 1 and set 2

## Commands / Tools

```bash
man tr
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```
Reasoning 
- cat prints data
- tr 'A-Za-z' 'N-ZA-Mn-za-m' sets up the rot13 encode/decoder
  
Result - Resolved level 12 password

What I learned
- How to decode rot13 encoded data
