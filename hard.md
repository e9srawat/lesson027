# Problem No. 1

Perform inner join, left outer join and right outer join on two csv files.

```c
def files_innerjoin(filename1, filename2, **kwargs)
def files_leftouterjoin(filename1, filename2, **kwargs)
def files_rightouterjoin(filename1, filename2, **kwargs)
```


# Problem No. 2

Split a large csv file on values of one or more columns into multiple files.
```c
def split_file(filename, split_cols: list)
```

# Problem No. 3
Write a function to convert numbers into words;
```c
def num_to_words(num)
```



# Problem No. 4

write a function to find the value of d < 1000 for which 1/d contains the longest recurring cycle in its decimal fraction part. <br>
Example :
```
1/2 	=  	0.5
1/3 	=  	0.(3)
1/4 	=  	0.25
1/5 	=  	0.2
1/6 	=  	0.1(6)
1/7 	=  	0.(142857)
Where 0.1(6) means 0.166666..., and has a 1-digit recurring cycle. It can be seen that 1/7 has a 6-digit recurring cycle
```


# Problem No. 5

Create a Python function to convert a decimal to a hex. It must accept a string of ASCII characters as input. The function should return the value of each character as a hexadecimal string.

```c
def ascii_to_hex(input_string)
```



# Problem No. 6

Create a Python Function to find out whether a given string is a valid regex or not

```
def validate(string)
```



# Problem No. 7

Create a Python function to find all pythogorean triplets whose sum lies between p and q, inclusive, and return a dictionary where the key is the sum and the value is a list of all tuples whose sides add up to the key.

```c
def pythagorean_triplet(p, q),
```




# Problem No. 8

Create a Python function that returns the nth prime number 

```c
def nth_prime(n)
```



# Problem No. 9

Create a Python function that returns a list of all combinations of dictionaries that are identical to each other for all combinations of dictionaries provided. Equivalence requires that all included lists are also identical in content but not in sortedness. Make no assumption about the order of keys or the depth of the data. Your compare function must use recursion.

```c
def dict_compare(*args):
```




# Problem No. 10

Create a Python function which will return the longest common subsequence between two strings.
```c
def longest_substring(string1, string2)
```