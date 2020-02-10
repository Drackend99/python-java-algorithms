# python-java-algorithms
A (soon to be) long set of algorithms useful to know as a software engineer

# Algorithms - Python

## Prime Number

Determine if a number is prime

### Concept

Using the "else" conidtional statement with for loops:
  - If the for loop is able to reach its end and terminate on its own, the ```else``` will be executed
  - If the for loop is terminated early with a ```break```, the ```else``` will not be executed

```
for i in range(1,4):
  print(i)
else:
  print("Made it to the end with no breaks")
```
### Code
```
is_prime = false
the_number = input()

if the_number > 1:
  for i in range(2, the_number):
    if the_number % i == 0:
      print("Number is not prime")
      break
  else:
    print("Number is prime")
else:
  print("Number is not prime")
```

# Algorithms - Java

## Prime Number
