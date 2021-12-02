---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

## You've joined the dark side

You've decided that quite simply, the council aren't paying you enough. You've solved their phishing problem, you've blocked hackers from executing malicious code remotely, and they didn't even pay for the fancy firewall you wanted! You've decided to join the hacker! Your new colleague managed to learn through their phishing emails that a lot of students add small strings after their passwords. e.g. password123, paddy2000, scotland2021.

--- 

### Task 1

Using this information, adapt the program the hacker used to take a list of suffixes (123, 2000, 2021, etc) as well. The program should be able to check all the passwords it checked before for every student, but it should now also try all these passwords with every suffix in your list!

You can work on your own, or in pairs. If you're working in pairs, try to take advantage of ***pair programming!***

The following piece of code might be a useful hint, if you're struggling, try creating some first names and some surnames and run the code on a bit of paper first!

```python
def find_all_firstname_surname_combinations(firstname_list, surname_list):
    potential_names = []
    for firstname in firstname_list:
        for surname in surname_list:
            potential_names.append(firstname + " " + surname)
    return potential_names
```

Here's the original hacker code to remind you:

```python
import computer_login_system
def gain_access(student_list, words_to_try):
    victims = []
    for student in student_list:    
        for word in words_to_try:
            if (computer_login_system.attempt_login(student, word) is True):
                victims.append(student)
    return victims
    
```

### Task 2

Write a small summary detailing what you've learned over this set of lessons, cover the following:

What have you learned today about how hackers might entice you to do things?
Have you become more supicious about links and information on the internet? 
What have you learned about making decisions in time-sensitive circumstances?
    
---   
## Congratulations!

If you've completed all of that you've successfully completed the lesson. I thoroughly hope you enjoyed yourself and would love to hear your feedback! Please send any feedback to s1840770@ed.ac.uk

--- 
[Go Back](../../CITC/stage-2-check)