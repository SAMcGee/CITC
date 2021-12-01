---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: stage-2
permalink: /stage-2/
---

# The hacker is back!!!
### And they're learned their lessons

You gave your teacher what for! They've installed a new firewall across the school, they bought in a very expensive new email filtering system and the school has an assembly about phishing. The attacker knows that they're not likely to manage to get past you now! But you discover they're now trying to run things on your school computers!

--- 

### You've managed to intercept a piece of code the hacker was trying to run on all the computers in the school

```python
import popuplib
import computer_login_system
def gain_access(student_list, words_to_try):
    victims = []
    for student in student_list:    
        for word in words_to_try:
            if (computer_login_system.attempt_login(student, word) is True):
                victims.add(student)
     return victims
    
```
### Task 1

Figure out what the code is trying to do!

### Task 2

Research dictionary attacks, figure out what they are and how you can defend against them. 

--- 

### Extension Activity

Just as you figured out the last piece, the hacker is trying to run a slightly modified version, what does this version do differently?

```python

import popuplib
import computer_login_system
def gain_access(student_list, words_to_try):
    victims = {}
    for student in student_list:    
        for word in words_to_try:
            if (computer_login_system.attempt_login(student, word) is True):
                victims[student] = word
     return victims
```

---

[Go Back](../../CITC/)