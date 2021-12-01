---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: stage-2-help
permalink: /stage-2-help/
---

### Some hints to help!

--- 

### Hint 1 - What does the code do?
<button onclick="revealHintOne()">Reveal Hint 1</button>

<p id="hint1"></p>

<script>
function revealHintOne() {
  document.getElementById("hint1").innerText = "Try to think about what the following line of code does computer_login_system.attempt_login(student, word), and think about what would happen in these two lines of code if(true): print(\"true\") if(false: print(\"false\"))";
}
</script>


### Hint 2 - What are dictionary attacks 

<button onclick="revealHintTwo()">Reveal Hint 2</button>

<p id="hint2"></p>


<script>
function revealHintTwo() {
  document.getElementById("hint2").innerText = "Have you ever reused a password? Or even worse, have you ever reused the same common password as someone else? How could an attacker take advantage of that?";
}
</script>

--- 

[Go Back](../../CITC/stage-2)