---
layout: post
comments: true
title: Difference between Python "Lists" and "Tuples"
date: 01-06-2020 12:35:10 -0000
---

SD-WAN MEF 70 standards applied on SD-WAN service providers will make standard way of delivering services.

First, lets take a look into the similarities between lists and tuples

1. Both are containers, a sequence of objects of any type
2. Both are ordered: they maintain the order of the elements (unlike sets and dictionaries)


Now, lets take a look at the Cultural difference between lists and tuples. Lists are used when you have elements of similar type of unknown length. Tuples are used when you have elements of different types of known length.

For example:

+ Find out the names of students in a class: This should ideally return a list of strings, where each element in the list is a string representing names and we do not know the exact number of students.

```python
["Varun", "Amrutha", "Sara", "Joseph", "Ali”] # The elements are of same type(string)
```

+ Representing a student in a class: A student has different attributes like name, student_id, class, school, day_scholar which can be represented as a tuple like so:

```python
("Varun", 10, "6", "DPS", True)  # The elements are of different type. 
```
In this aspect, tuples represent a database record.

__To conclude__: Keep in mind the Technical difference between lists and tuples. However, lists are generally used when you have homogenous items of unknown length and tuples are used when you have heterogenous items of known length.


