---
Course Code: PA2577
Name:  Applied Cloud Computing And Big Data 
---

# GenAI Policy

_Note: Throughout this document, "you" refers to students enrolled in the course, "we" refers to examiners/supervisors/teaching team._

The goal of the course assignments is to demonstrate your ability to make use of basic software engineering tools that are an integral part of a modern software development environment. This includes your editor, compilers, debugger, automated test tools, programming language specific documentation tools, microservice container tools, etc.

All GenAI use must align with the objectives and intended learning outcomes defined in the [course syllabus](https://plan.bth.se/courses/PA1489).
GenAI should support, rather than replace, your demonstration of competencies such as critical thinking and scientific writing.


# Sources

This document is partially based on the GenAI policy template by Franz Zieris:

> GenAI Policy Template, Franz Zieris, Blekinge Insitute of Technology, 2026.
> Available at: https://github.com/bth-dipt-teaching/genai-policy/blob/main/template.md
> Licensed under CC BY 4.0.

    The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL
    NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and
    "OPTIONAL" in this document are to be interpreted as described in
    [RFC 2119](https://www.rfc-editor.org/info/rfc2119/).

The document further makes use of the [AI Assessment Scale (AIAS)](https://aiassessmentscale.com/) developed by Mike Perkins, Leon Furze, Jasper Roe, and Jason MacVaugh in 2023/2024.

---

# General Principles

## Full Responsibility and Accountability

- You **MUST** take total ownership of every word, figure, and line of code; verify all AI-assisted output against primary sources.
- You **MUST NOT** assume that the AI knows best (e.g., using "The AI said so" as a justification), that details do not matter, or that examiners will not notice.
- You **SHOULD** make sure you understand the output of your AI tool and then write/use your own interpretation of it.
- **Motivation**: You are effectively "signing" your assignments as your intellectual output.
  You must be able to explain, justify, and trace the origin of any part of it.
  In group work, accountability is collective; all authors are responsible for the entire content.
- **Example**: A student experimented with ChatGPT for generating some program code for a task, but then re-typed it by themselves on a level where they understand what the code does.


## Do not Plagiarise

- **Comment**: This is a wider question than just the use of GenAI, but it applies equally to material produced by GenAI tools.
- You **MUST** properly cite and credit any material used in your assignments. This includes the _work_ of others, and this includes output from GenAI tools.
- You **MUST NOT** copy-paste or otherwise present the work of others as if it was your own.
- You **SHOULD** make it a habit to always summarise text that you want to use and to immediately add a reference to where you got it from.
- You **MAY** include the prompts you used to generate code or text from a GenAI tool, in order to discuss it with your teacher.
- **Motivation 1**: The assignments are an opportunity for you to show what _you_ have learned. By including sources and/or prompts we are able to help you learn more.
- **Motivation 2**: Plagiarism is a serious academic offence: You _must always_ give credit to the original author(s).
- **Example**: A student asks Claude to generate different suggestions for the code for a particular task, but then writes their own version which is a combination of several suggestions. They add the prompts used in a source code comment and discuss these with the teacher.
- **Example**: A student finds several ready-made solutions to a programming task online, and writes their own solution inspired by what they have read. They include links to the used pages in a source code comment.


## Use AI Tools to Explain, not to Do.

- You **MAY** use AI to explain different commands and overall workflow.
- You **MAY** see this as an opportunity to pratice your ability to find and read documentation and instruction manuals instead of relying on AI tools.
- You **SHOULD** make sure that you understand the tools that you use.
- You **SHOULD** verify what the AI tells you through independent tests.
- You **SHOULD NOT** rely on that the GenAI understand the tools for you.
- You **MUST NOT** blame the AI for any mistakes it does. Those mistakes are yours to catch.
- **Motivation**: You must at least be able to identify when GenAI tools suggests something wrong.
  Your value as an engineer is further increased if you are also able to work independently with minimal tool or AI support.
- **Example**: An engineer asked an AI tool to generate code to implement a feature and realised that the generated code would break the running system and cost millions of dollars. If they had not independently reviewed the generated code before committing they would not have caught this.
- **Comment**: In industry, the line between explaining and doing is blurred, but SHOULD only be crossed by engineers _who already know what they are doing_. 


# Specific Guidelines

## Installing Software
- You **MAY** use AI to assist with installing the required software.
- You **SHOULD** make sure you have a package manager installed that can automate most software installations, for the future.
- **Motivation**: This is not an examined part of the course and you should preferrably not get stuck on this point so you are free to do as you please.
  In order to gain more control and understanding, it is better if you use a dedicated package manager.
- **Example**: A student is struggling to get git working in WSL2, so they ask Copilot for help, and follows the instructions received.

## Answers to Quizzes
- You **SHOULD NOT** use any GenAI tools to answer the questions.
- You **SHOULD NOT** use any GenAI tools to summarise the research articles.
- You **MAY** use GenAI tools to improve your language.
- **Motivation**: The quizzes do not contribute to the grade; they serve as an indication for yourself to summarise what you have learnt so far, and for us to keep track of your progress through the material, and for us to steer you in the right direction.
  Likewise, we require summaries of the research articles only to provide a clear incentive for you to read them. The summaries are for your own benefit, and if you do not read the article in the first place, you will not benefit from an AI-generated summary of it.
- **Example**: A student used ChatGPT to answer the questions only to realise that they still needed to learn the material referenced in the question.

## Working with Containers
- You **MAY** be inspired by existing Dockerfiles, Docker compose files, and Kubernetes files that you find online.
- You **MAY** use GenAI tools to generate a Dockerfile, Docker compose file, or a Kubernetes file for you, that you then interpret and re-type in your own project. Focus on directing AI to achieve your goals while demonstrating your critical thinking.
- You **MUST** ensure that your Dockerfiles, Docker compose files, and Kubernetes files _only_ do what is necessary.
- You **MUST** ensure that any edited Dockerfile, Docker compose file, or Kubernetes file is _only_ changed where you expect it to be.
- You **MUST** be able to read and explain a Dockerfile, a Docker compose file, and a Kubernetes file.
- **Motivation**: AI tools regularly generate too much code or too complex solutions, whereas manually written examples are often shorter and more to the point.
  Reading many examples of existing Dockerfiles, Docker compose files, and Kubernetes files, and using them as inspiration for your own projects means that you learn how to see through the AI's tendency to over-complicate and bloat so that you are instead able to understand and focus on the core principles.
- **Example**: A student asks Claude Code for help to write the remaining service specifications in a partially completed Docker compose file, but writes the specification for environment variables and dependencies on other services manually. They then compare the new file with the original one and makes sure that there are no other accidental changes.
- **Comment**: Because of the tendency to bloat and over-complicate, AI generated software code is actually really bad for learning. It is much easier to read and understand a minimal example generated by an engineer.

## Project Implementation (Assignment "Build Something")
- You **MUST NOT** use GenAI tools to write any source code or code documentation.
- You **SHOULD NOT** use GenAI tools to generate the accompanying report.
- You **MAY** read and be inspired by other Kubernetes/microservice projects.
- You **MAY** use GenAI to explain existing source code for you.
- You **MAY** use AI for planning, idea development, and research. Your final submission should show how you have developed and refined these ideas.
- You **SHOULD** discuss with your friends.
- **Motivation**: The parts of the implemented projects that we look at is mostly trivial, the intended learning outcome is the ability to build microservices that communicate with each other, and the Kubernetes files necessary to launch the application. 
  Discussing with your friends is a vital learning tool, and the big difference between that and using an AI tool is that your friends know when to stop explaining and let you find the solution on your own.
  The submitted report mostly serves as an introduction to the implemented project to facilitate for us when marking, and we therefore prefer the report to be concise and to the point. We also ask some reasoning questions that mostly serve as eye-openers for you about what more must be considered if this were a real project.
- **Example**: A student is struggling with how to write the source code for an assignment, so they discuss with their classmates who show and explain how they solved the same task.
 
## Modifying Existing Implementations
- You **MUST NOT** submit source code which is fully AI generated. You must demonstrate your core skills and knowledge.
- You **MAY** use GenAI tools to explain the existing codebase.
- You **MAY** use AI for planning, idea development, and research. Your final submission should show how you have developed and refined these ideas.
- You **SHOULD** discuss with your friends.
- **Motivation**: Mechanisms such as map/reduce are at the core of any Big Data processing, and knowing how to use them is an essential skill.
  Learning how to use any tool comes from trying it out and understanding if, when, and how it fails.
- **Example**: A student uses Claude to further explain the given implementation instructions and to suggest several different examples of how to implement the task, but then manually types their own solution.

## Assignment Reports (Big Data Analytics assignments)
- You **MUST NOT** use GenAI tools to write the reports.
- You **MAY** use AI for planning, idea development, and research. Your final submission should show how you have developed and refined these ideas.
- You **MAY** use GenAI to improve language and grammar.
- **Motivation**: It is through your own analysis that you understand the limitations of Big Data Analytics. Focus on directing AI to achieve your goals while demonstrating your critical thinking.
- **Comment**: We have noticed that AI tools struggle with the analysis assignments in this course: they invent data, and they draw incorrect conclusions. If you actually generate the data, plot them, and squint at the graphs for twenty seconds, you are able to make a more meaningful and correct analysis than any AI attempt we have so far seen.
- **Comment 2**: Yes, it takes time to generate the data. That is the point, this is why it is called *Big Data*.
- **Example**: A student use an AI tool to understand how to plot the data and which statistical tests to run, but does the actual analysis themselves. They also remember to explain what is seen in the graphs through their own understanding of how the given source code solves the task.
