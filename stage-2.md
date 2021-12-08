---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: stage-2
permalink: /stage-2/
---

# The hacker is back!!!
### And they've learned their lessons

You gave your teacher what for! Your excellent consultancy work and research have led to a new firewall across the school! The school even bought in a very expensive new email filtering system and has had an assembly about phishing. The attacker knows that they're not likely to manage to get past you now! But you discover they're now trying to run code remotely on your school computers! (Clearly, that firewall isn't as impressive as you were lead to believe)

--- 

### You've managed to intercept a piece of code the hacker was trying to run on all the computers in the school

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
### Task 1

Figure out what the code is trying to do!

### Task 2

Research dictionary attacks, figure out what they are and how you can defend against them. 

--- 

### Extension Activity

Just as you figured out the last piece, the hacker is trying to run a slightly modified version, what does this version do differently?

```python
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
### Need some help?

#### Hint 1 - What does the code do?
<button onclick="revealHintOne()">Reveal Hint 1</button>

<p id="hint1"></p>

<script>
function revealHintOne() {
  document.getElementById("hint1").innerText = "Try to think about what the following line of code does computer_login_system.attempt_login(student, word), and think about what would happen in these two lines of code if(true): print(\"true\") if(false: print(\"false\"))";
}
</script>


#### Hint 2 - What are dictionary attacks 

<button onclick="revealHintTwo()">Reveal Hint 2</button>

<p id="hint2"></p>


<script>
function revealHintTwo() {
  document.getElementById("hint2").innerText = "Have you ever reused a password? Or even worse, have you ever reused the same common password as someone else? How could an attacker take advantage of that?";
}
</script>

Or skip to the [answers](../../CITC/answers)

---

### Continue
I've [decided on my answer](../../CITC/stage-3-check)

---

[Go Back](../../CITC/stage-2-check)