# README.md

This repository serves as a personal testing environment and GitHub portfolio.

The first project is a Bash script that prints the numbers 1–50 in sequence, using a `for` loop and a variable reference to display each number on its own line.

---

## Script

```Bash

#!/bin/bash
# Counter.sh – Prints numbers from 1 to 50.

for i in {1..50}; do
  echo $i
done

```
---

```
#!/bin/bash         ← Shebang line – specifies Bash shell interpreter
# Comment            ← Not executed – describes the purpose of the file

for i in {1..50}; do  ← 'for' loop starts; 'i' is the loop variable
                        '{1..50}' is brace expansion (1 to 50)
                        'do' begins the loop block

echo $i               ← Prints current value of $i

done                  ← Ends the loop block

```
