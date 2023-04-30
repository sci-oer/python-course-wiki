# Practice Activities for [Lists](/lists)


### Self Study Questions

1. What is the difference between `append()` and `extend()` methods in Python lists?
<details>
<summary>click here for one possible answer</summary>
  
`append()` method adds a single element to the end of the list while `extend()` method takes an iterable and adds each element of the iterable to the end of the list. For example, `my_list.append([1, 2, 3])` would add the entire list `[1, 2, 3]` as a single element to `my_list`, whereas `my_list.extend([1, 2, 3])` would add each element in the iterable `[1, 2, 3]` to the end of `my_list`.
</details>

2. How do you remove the first occurrence of a specific element in a Python list?
<details>
<summary>click here for one possible answer</summary>
  
You can use the `remove()` method to remove the first occurrence of a specific element in a list. For example, `my_list.remove(2)` would remove the first occurrence of the element `2` in `my_list`. If the element is not present in the list, a `ValueError` will be raised.
</details>

3. How do you sort a Python list in reverse order?
<details>
<summary>click here for one possible answer</summary>
  
You can use the `reverse=True` parameter in the `sort()` method to sort a list in reverse order. For example, `my_list.sort(reverse=True)` would sort `my_list` in descending order.
</details>

4. How can you check if a specific element exists in a Python list?
<details>
<summary>click here for one possible answer</summary>
  
You can use the `in` operator to check if a specific element exists in a list. For example, `2 in my_list` would return `True` if the element `2` is present in `my_list`, and `False` otherwise.
</details>

5. How do you create a copy of a Python list?
<details>
<summary>click here for one possible answer</summary>
  
You can use the `copy()` method to create a copy of a list. For example, `new_list = my_list.copy()` would create a new list `new_list` with the same elements as `my_list`. Alternatively, you can use the slicing notation to create a copy of a list: `new_list = my_list[:]`.
</details>

### Practice Problems

1. Write a Python program that takes in a list of numbers from the user, and then prints out the largest and smallest numbers in the list. For example, if the user enters the numbers [5, 10, 2, 8, 3], the program should output "Largest number: 10" and "Smallest number: 2".

A solution to this practice problem can be found on the file system of the docker container at: `/course/practiceProblems/lists/userEntryLists`

2. Write a Python program that generates a list of random numbers between 1 and 100, and then prints out the average, median, and mode of the list. For example, if the generated list is [20, 30, 40, 50, 60, 70, 80, 90], the program should output "Average: 55.0", "Median: 55.0", and "Mode: None". (Note that in this case, there is no mode since each value appears only once in the list.)

A solution to this practice problem can be found on the file system of the docker container at: `/course/practiceProblems/lists/randomNumberLists`