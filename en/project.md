--- step ---
---
title: Understanding tuples in Python
---

In the Python programming language, there are several types of data structure you can use. Two of the most common types of data structure are lists and tuples.

*[data structure]: a method of storing data to be accessed by your program

In Python, a tuple can hold any type of data, and is surrounded by parentheses.

```python
my_data = ('Here', 'is', 'my', 'data')
```

The data in a tuple can not be removed, and neither can you add extra data once the tuple has been created. The order of the data in a tuple will always remain the same.

Tuples are very useful for storing data that is going to remain constant throughout your program.

```python
red = (255, 0, 0) ## red is always red, so this is constant
edinburgh = (55.9533, 3.1883) ## the latitude and longitude of Edinburgh doesn't change
smarties = ('red', 'orange', 'blue', 'green', 'yellow', 'pink', 'violet', 'brown')
```

You can find out which item is at which position in a tuple by looking at the `index` of the item.

*[index]: the position of an item in a data structure

```python
smarties[0]
>>> eed
smarties[5]
>>> pink
```

You can also loop over the items in a tuple.

```python
for color in smarties:
    print(color)
```
--- /step ---
