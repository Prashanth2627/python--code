# python--code

### Question 1:
Write a Python program which accepts a sequence of comma separated 4 digit
binary numbers as its input and then check whether they are divisible by 5 or not.
The numbers that are divisible by 5 are to be printed in a comma separated
sequence.
Example:
0100,0011,1010,1001
Then the output should be:
1010

### Program:
```
a=input().split(",")
res=[]
for i in a:
  if(int(i,2)%5==0):
    res.append(i)
print(",".join(res))

```
### Output:
<img width="1706" height="637" alt="image" src="https://github.com/user-attachments/assets/c4018ef5-bdee-4d78-9922-4d382a219617" />


### Question 2
Write a Python program that accepts a sentence and calculate the number of
letters and digits.
Suppose the following input is supplied to the program:
hello world! 123
Then, the output should be:
LETTERS 10
DIGITS 3

### Program
```
sen = "hello world! 123"
let=0;
dig=0;
for i in sen:
  if i.isdigit():
    dig+=1
  elif i.isalpha():
    let+=1
print("Letter :",let)
print("Digit :",dig)

```
### Output
<img width="1311" height="563" alt="image" src="https://github.com/user-attachments/assets/de4e2351-6933-4e8a-a72a-f4b69b9f11d9" />


### Question 3
Write a program which can compute the factorial of a given numbers.The
results should be printed in a comma-separated sequence on a single
line.Suppose the following input is supplied to the program:8
Then, the output should be:40320

### Program
```
a=int(input())
fact = 1
for i in range(1,a+1):
  fact=fact*i
print(fact)
```
### Output
<img width="1486" height="515" alt="image" src="https://github.com/user-attachments/assets/4ac48b7d-c81b-4024-b7f3-8bfc998e725f" />

