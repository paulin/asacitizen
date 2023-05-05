---
layout: post
title:  "As A Citizen, I created User Stories"
categories: Governance User Stories
date: 2019-04-19
---
![1](/assets/images/userstorymachine.png){:width="80%" :style="display:block; margin-left:auto; margin-right:auto"}

User Stories are hard to write, but they are worth it when you want to efficiently build or add onto a complex system. After more than 20 years of experience I would say this is the starting point for sorting out any idea. When encountering any large system, I always try to break it down into User Stories first. I use a technique that came about from writing code and doing requirement analysis that has served me and my clients well for finding the blind spots in an idea. Sometimes, this involves discovering missing functionality, separating out ideas that have been grouped together, and helping to prioritize competing goals. In this article I will take you through this process so you can try it.


## Why the United States Constitution?
For fun I choose the United States Constitution as an example. From my perspective, it was a brilliantly designed blueprint to plan out the start and growth of my country. It amazes me that anything created by 55 people over 116 days could end up with ONLY a 4 page handwritten document. It came with plenty of flaws and drama, but it was designed to be expanded upon. That’s why we have 10 amendments with the Bill of Rights and later an additional 17 amendments. Think about that for a moment, this is essentially a rulebook that has been ratified since 1788 when New York was the 11th state to ratify it. It ONLY has an additional 27 amendments. I have seen countless business requirements documents that are many hundred pages and those were made with just a few people in the course of a week. It is truly inspirational to see something so important kept so concise.


Before we dive into this, I want you to realize that I do not have a legal background. I have an engineering background. I realize there is a massive body of knowledge that stems from the Constitution, and I certainly do not want to offend anyone with my interpretations. It ended up being an 18 page Google Doc. If you have some ideas or want access, please email me at: mattpaulin.com@gmail.com

## If you want to just view it, follow this [link](https://goo.gl/5QmaQL).

# A quick review about User Stories.
In case you don’t know what a User Story is, think of it as one sentence that explains what one type of user can do in a system. It is very focused on one feature and always written from the perspective of that user.
I like to think of them like the old Mad Lib sentences where you fill in the blanks.

As a *ROLE* I want to *TASK* so that *INTENT* because *REASON*.

In this case you have to fill in the; ROLE, TASK, INTENT, and REASON to complete the sentence.

You simply have to make a list of everything in this format. Sounds simple at first, but it makes you really think about who wants what sort of feature and why. The REASON is most useful when you hand this to engineering and design teams. This really helps them empathize with the user when they make decisions so they can propose other solutions that solve the same problem in better ways than the originators ever thought of.


# Step 1: Read and create your first draft User Stories
This is the most exhausting part, but you have to read everything in detail. For every sentence you have to ask; “who is this for?”, “what feature does this imply?”. From that, create your User Stories by filling in the blanks.

### Tip 1: Split Requirements:
Split requirements: As you go along, keep an eye out for the word “and”. This usually implies two features in the same sentence. As part of the process, it needs to be rewritten as two stories.

### Tip 2: Grouping:
Group by the same user type: You will find User Stories for the same types of users all over the place. As you go along, group them into the same places.

### Tip 3: Citations:
Give citations back to the original documents: The original documents could be everything from an interview, to a video, to a book. You need to include citations back to them so that you can always show where this came from. For example, I tried to tie it back to sections of the actual Constitution.The end result can be fairly lengthy, but it is possible to reflect on the different sections independently and find inconsistencies.

# Step 2: Refactor
Refactoring is a software engineering process where we restructure the code without changing the behavior. This involves regrouping, renaming, and removing duplicate functionality. When you have multiple versions of documents, you can find duplications simply by moving similar User Stories near each other.


In the case of the Constitution, I started to notice that there are certain roles that extended from another role. For example, an “Officer” was any “Citizen” who held public office. This helped simplify the role of “President”, “Vice President”, “Senator”, and “Representative” since I didn’t have to repeat the same stories in each category.


Another part I spent some time thinking about were the amendments. There are 27 of them and at first I had thought to tag each User Story with the amendment that it came from. Then, while refactoring I found that these should be preserved. In that case, I made sure that for the Citizen role, all the amendments affected the citizen. The reason here is that there is significant value in the order of these amendments. I eventually decided to keep them broken out for the Citizen role, but for many of the other roles it made sense to group the User Stories with all the rest.

### Tip 4: Flipping roles:
In some cases, you will encounter Stories that say one role cannot do something. I prefer to see it from the perspective of what a user can do. So, when you find one of these move it to the role that can do something and change it to a can version. When looking at a set of user requirements, it tends to only state what a user can do. What is interesting about the Constitution is that it talks a fair amount about what certain roles cannot do.


For example, Article 1, Section 10, Clause 1 is written as


`“No State shall enter into any Treaty, Alliance, or Confederation; grant Letters of Marque and Reprisal; coin Money; emit Bills of Credit; make any Thing but gold and silver Coin a Tender in Payment of Debts; pass any Bill of Attainder, ex post facto Law, or Law impairing the Obligation of Contracts, or grant any Title of Nobility.”`

There is a lot written in here, but you can see that no State shall coin tender. I prefer to write it as the following because it gives a little more detail as to why.

As a State I want Congress to have the sole power to coin money so that I don’t undermine the United States

### Tip 5: Renaming:
Don’t be afraid to rename a role. Sometimes there are two groups using the same name or during findings you realize that there is a much better name to use that is more natural or descriptive.

In the case of the Constitution, I wanted to rename “Indian” with “Native American” so that the vocabulary is updated to today’s conventions. As you build out your User Stories, keep an eye out for similar issues.

# Step 3: Prioritizing the Stories
Typically, after this point I would have the Stories grouped and ordered. Then, we would do a meeting where we prioritize them into the most critical features, the next features, and the future features.  My preference is to do this with color. Typically, I make the most important features black, the second features blue, and the future features grey.

But the Constitution isn’t a software specification, and it has already been implemented. I suppose you could claim that everything before the Bill of Rights was the first version. Then all the amendments beyond the 11th are future features. However, it just doesn’t make as much sense when all of it is already implemented, and I am just analyzing it in retrospect. Priorities make sense for planning, not as much for analysis.

# Conclusion
Deconstructing the Constitution into User Stories was a fun way to get a sense of how and why the United States government works the way it does. It helps to predict what could happen and to look for flaws. You can apply this technique for any situation where you have a complex requirements document or an unstructured set of ideas.

## Whats next?
I can’t help but come up with some ideas while doing this task. For example, the Constitution only represents Constitutional Law. What if you used this same technique for Common Law and grew out all the rights of a Citizen? It would allow for someone to see what cases defined the rights they currently have.


Another idea is that I could repeat this process for a different government’s constitution and compare the differences. If you do this on a global scale, it would give a really interesting analysis of how citizens are viewed by their governments around the world.
If you have ideas, I’m happy to share the work I have done. Please email me at mattpaulin.com@gmail.com
