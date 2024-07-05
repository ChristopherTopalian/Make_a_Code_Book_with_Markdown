```python
# print.py

print('Hi Everyone')
input('')

```

```python
# print_with_line_break.py

print('Hi Everyone\nHappy Scripting')
input('')

```

```python
# print_with_multiple_line_breaks.py

print('Hi Everyone\n\nHappy Scripting')
input('')

```

```python
# sleep.py

import time

time.sleep(4.0)

print('4 seconds passed')
input('')

```

```python
# 002_sleep_print_if_else.py

import time

print('Hi Friend')

time.sleep(3.0)

print('Is the sun shining?')

sunShining = input('y/n\n')

if (sunShining == 'y'):
    print('Nice that it is sunny out')
else:
    print('The sun will be there soon')

input('')

```

```python
# while_by_input.py

import time

x = input('Type 1 and press Enter\n')

while x == '1':
    time.sleep(4.0)
    print('4 seconds passed')

input('')

```

