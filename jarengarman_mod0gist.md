# Mod 0 Gist - Jaren Garman

### he/him - 2412

## About Me

Hi all! I spent the past five years training to be a pilot, with the ultimate goal of becoming an airline pilot. It took me long enough to realize that I wasn't truly happy with my career choice and I wanted to go back to my first passion: computers! I love solving problems with computers and I'm so excited to start with Turing so I can expand my understanding of how things work behind the scenes and learn how to build cool stuff.

## Intro Video Link

[Video Link](https://www.loom.com/share/78f3a2fba6fb4e78b0332a9cd8823af9?sid=fef5efca-a50d-455a-907f-579dc116b0ed)

# Prework CFUs

## Markdown Lesson

[Mod 0 Plan Gist Link](https://gist.github.com/JarenGarman/d6380fdcca43ef2e86d907838cee186d#file-jarengarman_mod0plan-md)

### What is markdown?

Markdown is a relatively simple language used to make formatting for HTML faster and easier

### What is your favorite markdown resource? (link or screenshot)

Definitely this [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

### What is the file extension for a markdown file?

.md

### What are the different header options?

There are three header options based on size. The largest being H1, medium is H2, and smallest is H3. Example:

```
# H1
## H2
### H3
```

### How do you create a bulleted list?

To create a bulleted, or unordered list, you place each list item on it's own line starting with a hyphen and a space. Example:

```
- List Item
- Another List Item
- Even More List Items??
```

### How do you insert a hyperlink?

To insert a hyperlink, you place the title of the link in brackets followed by the link itself in parantheses. Example: `[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)`

### How do you insert code into a markdown file?

Inserting code can be done in one of two ways: inline code, or as a code block. For inline code, you use a single backtic before and after the code you want to insert. For a code block, you use three backtics on both ends of the code block. Example:

````
Inline: `A single line of code goes here`
Code Block:
```
Multiple lines
of code
go here
```
````

## Terminal Lesson

### How do you quickly open up your Terminal on your computer?

Command + Space, search terminal, press enter.

### From your home directory, you have a Turing directory, then a Mod 0 directory. How would you create another directory inside the Mod 0 directory called Projects? (Note: there may be multiple correct answers.)

If I am doing more with the folder afterwards, I would `cd turing/mod0` and then `mkdir Projects`. If not, in my opinion it would be quicker to simply `mkdir turing/mod0/Projects`

### Working off the above question, how would you add a new file to the Projects directory called first_project.md?

`cd turing/mod0/Projects` then `touch first_project.md`

### If you were in the Projects directory, what would you type to get back to the Turing directory?

`cd ../..`

### From your Turing directory, how would you view all the directories and files within that Turing directoy?

`ls`

## Visual Studio Code Lesson

### How do you open your current directory in VS Code from the Terminal?

`code .`

### What is your favorite keyboard shortcut for VS Code? What does it do?

`opt + shift + down arrow` copies the current line and pastes it in a new line below.

### What resource will you use to continue learning VS Code shortcuts?

[This](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf) official reference sheet from Visual Studio for macOS.

### Which keyboard shortcut will you practice tomorrow?

A couple simple ones: `cmd + b` to toggle the sidebar and `shift + cmd + v` to open the markdown preview.

### Do you have auto-save turned on in VS Code? If no, why not?

I do, although I probably don't need it given I habitually `cmd + s` any time I make a change anyhow.

# Session 1 CFUs

## Data Types

### How confident do you feel with the content on Data Types so far?

I feel pretty confident with data types, although one part that stumped me a few times was storing things like date of birth or zip codes as strings. It makes sense when I think through it, we won't be doing math on those numbers and zip codes in particular might have characters that aren't numbers in them so they will need to be strings. That's just something I'll have to keep checking myself on moving forward.

### Is there any additional learning you need or want to do before moving to the next lesson?

Nothing in particular!

### What questions do you have about Data Types?

How strict is the distinction between integers and floats? Can you do math between them and if so, what data type is the output?

## Arrays

### How confident do you feel with the content on Arrays so far?

I feel confident with arrays, seems like you could really do a lot with them.

### Is there any additional learning you need or want to do before moving to the next lesson?

Not that I can think of.

### What questions do you have about Arrays?

After declaring an array, can you then replace a particular value like we can with variables?

## Asking Technical Questions

### What are the steps you will take when asking a technical question?

First, use all available resources to try to answer the question myself. This could be the original lesson, the official documentation, or google. Then, use the "rubber ducking" strategy by explaining the problem to an inanimate object and see if that helps me answer it. If all else fails, I will ask my teammates with the following layout:

1. What were you trying to do?
2. What were you expecting to happen?
3. What happened instead?
4. What have you attempted/googled/read to find a solution?

### We lay out these steps in a particular order. What do you think the reasoning behind this might be?

I think the reasoning is to save time. For example, if we started by asking our teammates then we would have to wait for a response and who knows how long that could take? By following these steps in this order, we make a much more efficient use of our time and our teammates' time.

### How will you refer back to this question-asking strategy while in Mods 1 and beyond? (ex: add these steps to your notes, write them on a sticky note, etc.)

I can definitely see myself referring back to this all the time, it's really helpful to see it described in a succint way. I've bookmarked the page for quick reference.

## DTR Prep

### How would you describe your preferred working style? (Alone,in groups, etc.)

I prefer to do the bulk of my work alone, with some synch time and always having my teammates a slack away.

### What strengths do you bring to a team?

I consider myself to be a good motivator and I can often clear up confusion between other team members.

### What’s gone well or poorly in your previous group project settings? What can you do to either ensure those best practices carry over into projects here or to avoid common pitfalls that might come up?

In the past, I have taken the lead in group projects and been self-assured that my way must be best and I might as well do most of the work anyways. To avoid this pitfall, I need to recognize that we are a team and that the most likely scenario is that my way is not the best way for everybody, and that anything we build we will build together.

### How do you prefer to handle disagreements that come up? (Yes, they will come up!)

Come together as a team and critically think through the problem, then collectively decide on the best option; put it to a vote!

### How do you communicate best? What tools do you need to communicate well with your teammates?

I find that my tone can easily get lost through text so my best way to communicate would be on a synchronous call or possibly even through a voice note or loom video.

### How do you prefer to receive feedback? How do you prefer to give feedback?

I prefer to give and receive feedback on a video call for the same reason in the last question, so the tone of voice can't be misconstrued in the text. However, I will encourage any kind of feedback my teammates prefer to give.

### What scheduling constraints do you have? What are your preferred work times outside of normal school hours?

My preferred work times would be about four hours after school ends on the weekdays and I could carve out some hours on the weekends if necessary. I am more than willing to be flexible with my times as long as I know about a day or two beforehand.

# Session 2 CFUs

## Calendaring & Time Management

### What time will you dedicate to pre-teaching upcoming lessons?

I plan to spend at least an hour before each class pre-teaching the lessons.

### What time will you dedicate to reviewing lessons?

I'll also dedicate an hour after each day to review lessons.

### What time will you dedicate to project work time? (Sometimes you will have time during class hours to work on projects.)

I will dedicate three hours after reviewing to project work time. Depending on the circumstances during the week, I will also dedicate some time on the weekend to catch up on anything I might have missed, somewhere around 5 hours each day.

### What time are you carving out for your own mental and emotional health needs?

I will have 38 hours of the weekend to myself (22 hours if you take out sleeping) and I will have a few hours every morning before each class.

### How will you spend your weekends?

Doing whatever the hell I want! For the most part. I plan on setting aside 10 hours total (5 per day) each weekend for Turing work. This time is flexible, some weeks I may need to increase it and some weeks I may be able to decrease it. I can also shift hours between Saturday and Sunday to have more free time on one of them vs the other.

## Git Workflow

### How confident do you feel in your understanding and fluency with the Git workflow?

I feel fairly confident on the Git workflow, the video and exercises felt easy enough to keep up with.

### What do you still need to practice or learn? How will you do that?

The whole process overall. I would also like to get into the habit of running `git status` and `git diff` whenever I make any changes to see what's happening behind the scenes.

### What part of the Git Workflow is still confusing for you?

Nothing that I can think of right now!

## Problem Solving

[Repl repo](https://replit.com/@JarenGarman/m0lessonsrepl)

### This process is definitely slower than starting by writing code. Why might this be helpful, even though it takes more time?

There are a few reasons pseudocode is helpful. For one, it can help you find a more efficient solution to the problem than if you just started coding. It can also lead to a deeper understanding of the code itself.

### Some pseudocoding is more helpful when we sit down to start writing the actual code. What are some characteristics of helpful pseudocode?

I think helpful pseudocode would be clear and concise, with some references to specific methods or mentions when a new method needs to be created.

# Session 3 CFUs

## GitHub

### How confident do you feel in your understanding and fluency with Github?

I feel very confident with understanding Github as I've used it a bit before starting Turing. Of course, I could always use additional practice and I'm excited to learn more!

### What do you still need to practice or learn? How will you do that?

I still need to practice disconnecting and reconnecting to a remote repository, luckily I can get some practice coming up because Github flagged my account so I'll have to do this process a few more times!

### What part of Github is still confusing for you?

Nothing that I can think of at the moment.

## Conditionals

[Github repo](https://github.com/JarenGarman/m0_be_conditionals)

### When is it useful to use a `conditional` in your code?

Conditionals are useful if you have multiple variables and you need to compare them to each other or you need to check values against each other.

### If you could do this assignment over, what would you do differently?

I would have done it at my desk with my external monitor plugged in. I didn't realize how much more space it gives me and how much I use it until I didn't have it.

### What about your thinking, learning, or work today brought you the most satisfaction? Why?

I was really satisfied with how quickly I was able to complete the coding challenges. I do have a tiny amount of experience in C++ and Java, but that was from over a decade ago when I was in middle school.

## Methods

[Github repo](https://github.com/JarenGarman/methods_cfu_am0)

### Reflect on your learning and work today. What are you most proud of?

I am most proud of my ability to read and understand the ruby docs for the methods and their purposes. They do seem to make it easy though. I love the examples!

### What is the power of using methods in our applications?

Methods allow you to generalize certain tasks so you don't have to type out the same few lines of code every time you need to do a particular task. You can change the inputs (arguments) whenever you need to call the method for different values.

## Beyond Mod 0 Plan

[Beyond Mod 0 Plan Video](https://www.loom.com/share/ad0b52a7e9bf4711a9525ee7967c2c96)

## Final Reflections

### As you look back on your time in Mod 0, what are you most proud of?

I am most proud of my problem-solving ability and how quickly I was able to catch on during class. I hope to keep this up by alotting ample time to pre-teach lessons before the synch classes so I can prepare any questions I might have.

### What did you learn about yourself, as a person or a student, during Mod 0?

I learned that I do work well in a group setting, especially when my classmates ask questions that I wouldn't have even thought of.

### What is one thing you want to remember as you start this new journey to become a software developer at Turing?

Similar to the last question, I want to remember the value of working with others. Working as a team and boosting each other will make us all better in the long term and will be our best chance to succeed at Turing and beyond.

### Finally, share some gratitude for the people who were most supportive to you throughout this Mod 0 experience!

A huge thank you to guys Alec and Thomas obviously!! For your upbeat attitudes in class, your encouragement for participation, and your willingness to help anybody who needed it. I also want to thank Mark for his help with the Github flagging issue and I want to thank Sebastian, Beverly, and everybody else who asked great questions during class to help us all learn more. I can't wait to get started with Mod 1!
