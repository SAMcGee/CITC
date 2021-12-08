---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: stage-2-check
permalink: /stage-2-check/
---

### The hacker's gone for now

Your research has led to the following discoveries: 

1. Firewalls are rule-based, and although they could block this attack, all the hacker has to do is copy the website to a different domain and we have to keep updating our rules! Though this method can certainly help, it costs the hacker money, time, and energy to set it all up again.

2. Email filters are never 100% accurate with detecting spam emails, often they accidentally flag legitimate emails. They can be configured to only flag emails which they are very confident are spam, which can help, though it is never perfect. 

3. Teaching people about phishing is not perfect, we all make mistakes. But by learning about how hackers attack networks and by remembering to take your time and consider all the information you have available, it makes it much less likely for you to fall for a phishing email.

You've decided that ultimately none of these methods can stop phishing alone, but together they might have a chance. So you've told your teacher and wrote a rather, colourful, letter to your local council!

***Quick Quiz***:
    How many cyberattacks do you think start with someone clicking on a phishing email? Click on a button to have a guess

| 31% | 61% | 91% | 
| ----------- | ----------- | ----------- |
| <input onclick="change(31)" type="button" value="Guess" id="myButton1"> | <input onclick="change(61)" type="button" value="Guess" id="myButton2"> | <input onclick="change(91)" type="button" value="Guess" id="myButton3"> |

<p id="answer"></p>

<script>
function change(number) {
  if (number != 91) {
    document.getElementById("answer").innerText = String(number) + "\% is incorrect, try again!"
  } else {
    document.getElementById("answer").innerText = String(number) + "\% Correct! 91\% of cyber attacks start with a phishing email"
  }
  
}
</script>

### Some questions for you to think about

1. What do a lot of phishing emails have in common, look at our example and think about what a phishing email might look like for banking scams or 'regaining access to an account'?
2. What things made you suspicious by analysing the body of the email?
3. Do you think there are any lessons about analysing information which you could use in other subjects which you’ve learned in this exercise?

---
### Continue
I've [thought about the questions](../../CITC/stage-2)

---

[Go Back](../../CITC/)