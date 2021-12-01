---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: stage-1-help
permalink: /stage-1-help/
---

### Some hints to help!

--- 

### Hint 1 - Firewalls 
<button onclick="revealHintOne()">Reveal Hint 1</button>

<p id="hint1"></p>


<script>
function revealHintOne() {
  document.getElementById("hint1").innerText = "Firewalls can block connections coming into the school network, but they can also block connections coming from the school network. Why might this be helpful?";
}
</script>


### Hint 2 - Emails 

<button onclick="revealHintTwo()">Reveal Hint 2</button>

<p id="hint2"></p>


<script>
function revealHintTwo() {
  document.getElementById("hint2").innerText = "Does any solution completly solve the problem with email filters? Is it possible for a computer to completly understand what is spam and what isn't, is it possible for a human?";
}
</script>


### Hint 3 - Teaching Users

<button onclick="revealHintThree()">Reveal Hint 3</button>

<p id="hint3"></p>


<script>
function revealHintThree() {
  document.getElementById("hint3").innerText = "Have a look at the email example again, how did you spot it was fake? Could you think of a way of explaining this to other people?";
}
</script>

--- 

[Go Back](../../CITC/)