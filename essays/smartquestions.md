---
layout: essay
type: essay
title: "What We Can Gain From Asking Smarter Questions"
date: 2023-09-5
published: true
labels:
  - Smart Questions
  - 
---
## Introduction
There are some questions that we just don’t know the answer to. In most cases we turn to the internet to help us answer this question since all we have to do is pull out our phone and type in the question into a google search page. Moreover, it is easily accessible for us to be able to get our questions answered, but what if our questions don’t have an answer to them. This is where we need to be able to ask a question, and whether that question is a good question or bad question depends on how the question is asked. Furthermore, for this essay we will take a look at why smart questions are important for smart software engineers, the difference between a smart and not smart question, and how the responses of these questions help to reflect the smartness of the question.

## Smart Questions for Software Engineers
Smart questions are very crucial for software engineers as asking a good question can lead to a better response to that question. For example, you don’t want to ask a question just for someone to say just search the web because that would indicate your question wasn’t a very good question. This is especially important for software engineers because code can be very different from person to person and from machine to machine so by asking a smart question we can be sure the response to the question is exactly what we need. Another reason why asking smart questions are important for software engineers is because a lot of the time software engineers will run into problems that have never occurred before such as bugs.

## Smart and Not Smart Questions

### Example of a Smart Question
An example of a smart question is shown here: [Smart Question](https://stackoverflow.com/questions/52522565/git-is-not-working-after-macos-update-xcrun-error-invalid-active-developer-p/52522566#52522566 ).
As we can see in this example the develop asks, “Git is not working after macOS update ("xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools")” and goes through their process of what happened prior to get the error that they did, they also were to provide that they were using an macOS system, and has a precise and informative problem. As we can see from the top solution to the problem we are able to get a step by step guide to fix the problem and more than one solution if the first solution doesn’t work. This shows that by asking a smart question we can get an effective and efficient answer to our questions.

Good Question Example:
```
I updated to the latest OS, and/or restarted my computer (this happens on every major update, but this time all I did was restart my computer on 2022-09-13).

This morning I navigated to my work's codebase in the command line on my MacBook Pro, typed in "git status" in the repository and received an error:

(In 9/2022, this error was much different, but I didn't capture it)

xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun

Git will not work!

How do I fix Git, and the command-line tools?

```
Good Question Reply Example:
```
Go back to your terminal and enter:

xcode-select --install
You'll then receive the following output:

xcode-select: note: install requested for command line developer tools
You will then be prompted in a window to update Xcode Command Line tools. (which could take a while)

Open a new terminal window and your development tools should be returned.

Addition: With any major or semi-major update you'll need to update the command line tools in order to get them functioning properly again. Check Xcode with any update. This goes beyond Mojave...

After that restart your terminal

Alternatively, IF that fails, and it might.... you'll get a pop-up box saying "Software not found on server", proceed to solution 2.

```

### Example of a Not Smart Question
An example of a not smart question is shown here: [Not Smart Question](https://stackoverflow.com/questions/42997442/how-to-use-zingchart-in-javascript).
As we can see in this example the developer asks. “i want to use zingChart in my project using javascript can anyone have idea how to do ?”. This question is not a smart question because we can see the grammar is off, the question doesn’t provide the symptoms of the problem, and this problem has probably been solved elsewhere if the developer decided to do a quick google search. As we can see with the answer to the question in the post it just says to paste this without any explanation and gives a link to the zingchart website where they have the documentation for zingchart. This shows how a not smart question can lead to an answer that isn’t efficient and effective, because the developer could have gone to the zingchart site from the beginning. 

Bad Question Example:
```

i want to use zingChart in my project using javascript can anyone have idea how to do ?

```
Bad Question Reply Example:
```
just put this code ..

<script src="https://cdn.zingchart.com/zingchart.min.js"></script>
  <script>
    zingchart.MODULESDIR = "https://cdn.zingchart.com/modules/";
    ZC.LICENSE = ["569d52cefae586f634c54f86dc99e6a9", "ee6b7db5b51705a13dc2339db3edaf6d"];
  </script>
Now you are able to use zingChart.. read more [ZingChart](https://www.zingchart.com/docs/getting-started/your-first-javascript-chart). 
```
## To Conclude
After learning about smart and not smart questions we should be able to determine what makes a question smart, how the response helps to determine the smartness of a question, and why smart questions are important to software engineers. This is very important because by knowing how to  ask smart questions we can get efficient and effective solutions that can help us to solve any problems that may arise. 

 
      .
