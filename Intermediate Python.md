### Exercises1

* Create a list of the first names of your family members.
```python
family= ['Yiman','Sen','Shuhua','Zhoulong']
```
* Print the name of the last person in the list.
```python
family[-1]
```
* Print the length of the name of the first person in the list.
```python
len(family[0])
```
* Change one of the names from their real name to their nickname.
```python
family[1]='Sensen'
```
* Append a new person to the list.
```python
family.append('Zhuzhu')
```
* Change the name of the new person to lowercase using the string method 'lower'.
```python
family[-1] = family[-1].lower()
```
* Sort the list in reverse alphabetical order.
Bonus: Sort the list by the length of the names (shortest to longest).
```python
sorted(family)
sorted(family, reverse=True)
sorted(family,key=len)
```
