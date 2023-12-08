# Python-Sheet
## Arithmetic Operations
```python
## Division
result = 14.5 / 3
print(result)  # Output: 4.833333

## Floor Division
result = 14.5 // 3
print(result)  # Output: 4.0 rounds down to the nearest whole number

## Modulo
result = 14.5 % 3
print(result)  # Output: 2.5

## Exponentiation
result = 2 ** 3
print(result)  # Output: 8

## Addition
result = 10 + 5
print(result)  # Output: 15

## Subtraction
result = 10 - 5
print(result)  # Output: 5

## Multiplication
result = 10 * 5
print(result)  # Output: 50

## Increment
number = 5
number += 1
print(number)  # Output: 6

## Decrement
number = 5
number -= 1
print(number)  # Output: 4
```
## Type Conversion 
```python
## Integer to Float
int_to_float = float(10)
print(int_to_float)  # Output: 10.0

## Float to Integer
float_to_int = int(10.5)
print(float_to_int)  # Output: 10

## Integer to String
int_to_str = str(123)
print(int_to_str)    # Output: '123'

## Float to String
float_to_str = str(3.14)
print(float_to_str)  # Output: '3.14'

## String to Integer
str_to_int = int('42')
print(str_to_int)    # Output: 42

## String to Float
str_to_float = float('3.14')
print(str_to_float)  # Output: 3.14

## List to String
list_to_str = str([1, 2, 3])
print(list_to_str)   # Output: '[1, 2, 3]'

## String to List
str_to_list = eval('[1, 2, 3]')
print(str_to_list)   # Output: [1, 2, 3]

## Tuple to List
tuple_to_list = list((1, 2, 3))
print(tuple_to_list)  # Output: [1, 2, 3]

## List to Tuple
list_to_tuple = tuple([1, 2, 3])
print(list_to_tuple)  # Output: (1, 2, 3)

## Set to List
set_to_list = list({1, 2, 3})
print(set_to_list)    # Output: [1, 2, 3]

## List to Set
list_to_set = set([1, 2, 3])
print(list_to_set)    # Output: {1, 2, 3}
```

## String Formatting
```python
thing_to_do = "Take it"
way_to_do_it = "easy"
pronoun = "dude"

formatted_string = f"{thing_to_do} {way_to_do_it} {pronoun}. But {thing_to_do}!"
print(formatted_string)
```

## For Loops
```python
animals = ['tiger', 'lion', 'bar']
for animal in animals:
    print(animal)

for i in range(5):
    print(i)
```
## While Loop
```python
count = 0
while count < 9:
    count += 1
    print(count)
```
## List Operations
```python
new_list = [1, 3, 4, 4, 4, 4, 4, 4, 4, 4, 4, 5, 5, 5]
new_list.append('peanutbutter')
print(new_list)

new_list.pop()
print(new_list)

new_list.remove(4)
print(new_list)
```
## Dictionaries
```python
my_dict = {
    'name': 'John',
    'age': 25,
    'is_student': False,
    (1, 2): 'a tuple key',
    3.14: 'a float key'
}

for key, value in my_dict.items():
    print(f'{key}: {value}')

print(my_dict['name'])
```
## Conditionals
```python
number = 34
if number >= 34:
    print('yes')
elif number < 33:
    print('no')
else:
    print('not a number!!')
```
## Functions
```python
def add(a, b):
    return a + b

print(add(43, 45))
```
## Exercises
```python
where_are_my_things = {
    'games': 'closet',
    'food': 'fridge',
    'stickynotes': 'drawer'
}

for key, value in where_are_my_things.items():
    print(f"My {key} is in the {value}")

def fizz_buzz():
    number = 1
    while number < 99:
        number += 1
        if number % 3 == 0:
            print('fizz')
        elif number % 5 == 0:
            print('buzz')
        else:
            print(number)

fizz_buzz()
```
