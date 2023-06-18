# Prompt Engineering for Programmers 
This is the Welcome section of the [Top Training for Programers: Prompt Engineering for Programmers](https://godsol.gumroad.com/l/prompt-engineering-for-programmers) using ChatGPT + other AI Code Tools

Here's the introduction, which includes a valueable set of parameters. I teach this syntax, and use a combination of parameter sytax and natural language in practice.

Our training uses Tree of Thought (ToT) methods to communicate with the AI what we want to get the changes we want. 



# 👋 Welcome 👨‍💻

<aside>
🦁 Welcome to Prompt Engineering for Programmers. Here you’ll find theory explaining what goes into a prompt, one shot prompts to set up sophisticated responses, full walkthroughs to build just about anything, and further links to all kinds of resources.

</aside>

# Welcome to your first day.

You’re in the right place at the right time. 

With the open-source movement in full swing, and now tools to write code almost instantly, there’s nothing holding you back but your imagination, and some core know-how (which you’ll get here.)

This book will take you through all you need to know to get quality code from ChatGPT, and provide Code God “Cogo” personality and hundreds of ideas in the form of prompts to give you a head start. We will dive into theory by getting the most from GPT-4 in ChatGPT by testing out Cogo.

## If you’re looking for immediate results, I recommend skipping to Cogo, a powerful personality to generate projects.

You'll find Coco in the section in this document, which you can jumpstart directly into coding. Chances are you've already played around with coding and chat GPT, so playing with cougar will show you just how amazing it is 

https://www.youtube.com/watch?v=MjFKJztu1DQ

You can now bootstrap any project by copy/pasting Cogo parameters into a Google doc, etc., saving your preferences, and then modifying it when you have an idea for an app. 

## Mastering the ancient skillset of planning

**The art of prompt engineering** does not replace the **art of software design** nor hard-earned experience with languages and tech stacks. ChatGPT’s magic is the ability to bridge the gap between an idea and an application launch. 

Building full-stack applications without artificial intelligence will give you knowledge of one stack of technology, and help you greatly in building through artificial intelligence. This resource assumes you’ve had a bit of experience with at least one tech stack. **Your tech stack is likely perfectly supported** if it existed before 2021.

Having a knowledge of what to build (what’s viable in the market), and wisdom of what to build with (**libraries, languages and paradigms)** is now more valuable than coding skills. If you have never coded before, you may fall into the common pitfalls when it comes to **massaging returned code snippets into finished applications**, and may run into problems with the tech stacks that are automatically chosen if you aren’t specific in your prompts (something we handle thoroughly in this resource).

To truly utilize the power of AI in your coding, **double down on theory and knowledge of long-time libraries**. Question GPT’s choice of libraries constantly. Optimize your current path of development first before re-inventing the wheel, and don’t be afraid to reach into new areas you have always wanted to go. 

> If you're an app developer, reach into designing games or machine learning, if you're specialized in web development and yet-to-build a mobile app, now is your chance. If you’re new to programming completely, take the time ask chatGPT to teach you a language.
> 

There are no consequences until the code is implemented. This gives you wide room to get to know and learn GPT-3 and GPT-4 using ChatGPT, Bing, and more. Give back the code in a new prompt and ask for an explanation if you need. If you’re a new programmer, you can leapfrog seasoned developers in terms of getting good code snippets from AI, but their experience and knowledge may be what’s needed to determine if the code will work. It’s up to you to seek more knowledge from chat GPT itself, but also to take time to implement, and learn other aspects of successful web design 

<aside>
🦁 Actually.. since GPT-4 came out, there’s even less need to be a good planner for simple applications. Check the next section for simple scripts

</aside>

Part of my mission with this course is to fulfill a third undiscussed role, **optimizing your interactions with the chat bot**. Things like maintaining your setup prompts so one or two in a new window can give you context to start off on a project component. Saving you more than the time to read this resource. We are facing limitations simply because of the newness of the technology come on so I do my best to write with both solid understanding of the exact parameters that go into the code, and a bit of a blind eye when what we tell to the AI doesn't come back quite as we explicitly spelled out, as is the example of forgetting of a style of commenting on subsequent queries.

ChatGPT is an opportunity to learn or refresh **core foundations of programming** and computer science. When learning, I encourage you to seek out boundaries and relations within chatGPT, then explore technical aspects in real documentation. AI is, well, still not as intelligent as we want it to be.

My name is Gudasol 🜛  I’m an OG [coder](https://github.com/dougbutner), releasing my first full-stack app nearly half my life ago, at age 16. Having discovered AI, I found it fascinating to get good code back, and to have AI shorten my lengthy, unruly code. I’ve created this resource to save you time, so let’s get started 🦁

# Preparation is still 🔑

As we progress through learning how to code in chat GPT, and build real world applications, I encourage you to remember the pencil and paper. I invite you to sketch your UI under a tree, write the function names, sketch out every single component, and do your data designs with simple t’s and keys, and then bring in the AI last. 

We often cross the bridge to make our ideas real too early, which is a greater danger than ever with AI code snippets. If we take the time to know each part and structure in the app-creation process by sketching this out on paper or an app like Sketch first, we are utilizing our creative power as much as possible, meaning we can delegate the coding to ChatGPT, not the ideas.

<aside>
🦁 We’ll go over planning for ChatGPT creation, and you’re welcome to use your own methods as well.

</aside>

## The Scope of PEFP

This resource is about getting back **good code via well-engineered prompts**. Everything related may be covered. Check the overview to see what we’ll be covering and what has already been covered.

## The Overview

You’ll learn how to talk to ChatGPT, and wisely keep a document ready to copy and paste from with favorite prompts. 

<aside>
🙏 I want to bring you the MOST valuable content in the shortest time. If there’s a section you think could be improved, I welcome you to reach out.

</aside>

## Taking these Lessons

<aside>
👨‍🏫 **Open every collapsable arrow.** Try prompts that interest you. Report errors in [Discord](https://discord.gg/E5JNECjXxd).

</aside>

Open each section to get a feel for the resource. I’ll introduce you to each section and share engineered prompts that are a combination of ChatGPT’s own suggestions and wise edits.

## Setting Up ChatGPT

The personalities that we provide allow a context to exist within your application. To better understand context, I'd like to share my favorite syntax for interacting with ChatGPT. 

Every word that we type in the chat GPT helps to create the context. We’re taught to interact with with natural language, and that the predictive model will understand this, but it’s just as effective to use a structure like in the block below to set any context. You can even add similar blocks to other prompts you find outside this resource, and outside the scope of programming. 

This is a shortened version of the “god mode” as I like to call it. It’s more to teach you how to set up context, if you’re eager to code, feel free to jump to Cogo.

```cpp
// --- Set Up ChatGPT Context example  --- \\

Let set some strict guideline for this chat. Going forward return only code snippets, and explain only in code comments.

language: javascript, jsdoc
libraries: react, jsdoc
comment_style: descriptive //
capitalization: camelCase
function_declaration: named
error_handling: try-catch
code_complexity: complex
code_modularity: modular
code_readability: clear
code_efficiency: optimized
code_scalability: scalable

```

It’s important to remember the limitations of computer systems. If you are having trouble, remove the unneeded parameters. The ones starting with code_ can be removed. We’ll also use some other parameters in this resource. 

## My Goals as your prompt instructor

My goal is to save you time with understanding and developing your own workflow for your tech stack. That’s the value I want to provide for your much-needed contribution. Personally though, I also want to learn with you and with the world as this new tech develops, and even build some part of that. The tools are Cogo + MaMi + packs of prompts, and the understanding is the ability to choose the minimal best thing to say to get the best possible response from ChatGPT and other AI code tools.

I focus my teaching in this resource towards **people who want to make an app**, as that's who I was in the past, and we naturally gravitate towards helping a younger version of ourselves. 

Your intentions for learning may be quite different, you may want to learn programming, you want to see what AI can do, perhaps you just want to **make an idea you’ve had for years real and are here to learn how to do that**. I encourage you to integrate information with your existing motives, knowledge, etc. in whatever way you can, and discuss here in comments (corrections, suggestions) or in [discord](https://discord.gg/E5JNECjXxd) if I can do a better job to meet your unique needs, or if you would like to share information that may help fellow students. 

Thank you for your vote of confidence with your purchase. 


This is the Welcome section of the [Top Training for Programers: Prompt Engineering for Programmers](https://godsol.gumroad.com/l/prompt-engineering-for-programmers) using ChatGPT + other AI Code Tools
