> valid-phone-numbers 193
file.txt:
```
987-123-4567
123 456 7890
(123) 456-7890
```
awk '/^([0-9]{3}-|\([0-9]{3}\) )[0-9]{3}-[0-9]{4}$/' file.txt



> Tenth Line 195
file.txt:
```
Line 1
Line 2
Line 3
Line 4
Line 5
Line 6
Line 7
Line 8
Line 9
Line 10
```
sed -n "10 p" file.txt



> 
