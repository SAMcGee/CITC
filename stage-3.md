---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

## Now you get to think like a hacker

You managed to learn through your phishing emails that a lot of students add small strings after their passwords. e.g. password123, paddy2000, scotland2021.

--- 

# FINAL TASK

Using this information, adapt the program the hacker used to take a list of suffixes (123, 2000, 2021, etc) as well. The program should be able to check all the passwords it checked before for every student, but it should now also try all these passwords with every suffix in your list!

Here's the original hacker code to remind you:

```python
import computer_login_system
def gain_access(student_list, words_to_try):
    victims = []
    for student in student_list:    
        for word in words_to_try:
            if (computer_login_system.attempt_login(student, word) is True):
                victims.add(student)
     return victims
    
```
    
---   

[Go Back](../../CITC/)