[TOC]

# use _ in for loops
## loop
```python
for _ in range(10):
    function()
```
which means that we are **not using the counter variable inside the loop**. 
Instead, we only want Python to call function ten times and need the _ to have valid syntax.
[link](https://stackoverflow.com/questions/26895362/what-does-in-python-do)
## place holder
instance, _ = models.MyModel.objects.get_or_create(name="Whee")
