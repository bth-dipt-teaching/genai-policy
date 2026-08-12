---
course:
  code: PA1483
  name: Software Architecture
term: HT2026
status: published
---

# GenAI Policy

_Note: Throughout this document, "you" refers to students enrolled in the course, "we" refers to course responsibles, examiners, and other teachers involved in grading._

The overarching goal of your work in this course is to demonstrate your ability to analyze architectural issues as well as reflect on the appropriateness of solutions addressing them. All GenAI use must align with the objectives and intended learning outcomes defined in the [course syllabus](https://bth.azure-api.net/lindplan/courseplanbycode?code=BW6AU&semester=20262&lang=en). GenAI should support, rather than replace, your demonstration of competencies such as critical thinking and technical writing.

The guidelines below are written in a "Do"/"Don't" format to explain what you are allowed or even encouraged to do, and what you must not do, respectively. Each guideline has a "Motivation" for you to understand why we have included it in this policy document and an "Example" to illustrate how acceptable behavior can look like.

---

# 1. General Principles

## 1.1 Full Responsibility and Accountability

- **Do**: Take total ownership of every word, figure, and line of code; verify all AI-assisted output against primary sources.
- **Don't**: Assume that the AI knows best (using _"The AI said so"_ as a justification for yourself), that the technical details and formulations don't matter, or that the examiners won't notice that you don't understand some parts of it.
- **Motivation**: You are "signing" your report as your intellectual output, just as software architecture are accountable for the designs and recommendations they present in professional contexts. You must be able to explain, justify, and trace the origin of any part of it. In student groups, accountability is collective; all authors are responsible for the entire content.
- **Example**: A student used ChatGPT for structuring a report, found the output to be verbose and superficial. Now knowing how his report should not look like, he started from scratch on his own.

## 1.2 Transparency

- **Do**: Openly discuss your GenAI workflows within your in your group; open discuss it with us, your teachers (e.g., in the bookable Q&A timeslots), to better understand opportunities, limitations, and risks of specific use cases.
- **Don't**: Hide your use of tools.
- **Motivation**: Pragmatically, no policy document can cover every use case. More importantly, transparency is a sign of professional integrity and academic maturity: Tools and processes should be open to review and just as disussable as technical design decisions. We highly value and appreciate being careful and reflective about GenAI use (or any tool use, for that matter).
- **Example**: Show us the prompts you used to explore possible directions for your topic and explain how you worked with the ideas.

---

# 2. Guidelines Throughout the Course

## 2.1 AI-Assisted Exploration of Architectural Concepts

- **Do**: Use GenAI to learn about unfamiliar concepts, discuss general (assignment-independent) architectural ideas.
- **Don't**: Treat GenAI output as established fact. Stop your investigation after receiving an AI-generated explanation (see also _2.3 Human Authorship_).
- **Motivation**: Software architects regularly need to learn about technologies, patterns, and domains. GenAI can help you discover relevant ideas, but architectural work requires understanding and judgment, not merely collecting and repeating pre-formulated answers.
- **Example**: Chat with Claude to understand Event Sourcing and discuss situations in which it may be useful (e.g., _"Explain it to me like I am 10 years old"_). Skim some primary source which Claude pointed out (e.g., [Fowler's 2005 article](https://martinfowler.com/eaaDev/EventSourcing.html), or [Ch. 6 of Lawrence's 2026 book](https://learning.oreilly.com/library/view/message-and-event-driven/9780137998654/ch06.html)). Then you, not Claude, decide for youself whether it is relevant for your situation.

## 2.2 Human Analysis and Decision-Making

- **Do**: Develop your own initial architecture analysis first, then use GenAI to critique it, challenge your assumptions, and identify weaknesses.
- **Don't**: Ask GenAI to perform the assignment tasks on your behalf. Delegate architectural decisions to GenAI.
- **Motivation**: Among the key responsibilities of a software architect is to analyze architectural problems, evaluate trade-offs, and make design decisions. A central learning outcome of this course is therefore your ability to perform this reasoning yourself. You should not aim for "perfect", but for "good enough". It is better to come up with a simple architecture design that has some drawbacks but which you fully understand than submitting a clean-looking, likely over-engineered solution of which you understand less than half.
- **Example**: You identified _run-time modifiability_ as an important quality attribute and consider applying the Client-Server pattern. In a discussion with ChatGPT, it asks whether there even are multiple hardware devices connected via a network, and you realize that you need to look for a non-distributed pattern.

## 2.3 Human Authorship

- **Do**: Use AI to shorten your work. Write in your own words, then use AI to identify parts to cut. Use language-focused tools like Grammarly's Proofreader to refine grammar, spelling, and flow of text you have already written in full. The same holds for diagrams, tables, etc.
  - Attention: Chat-based systems like ChatGPT require extra care because they are designed to please their users and always offer to do more than you asked them to! 
- **Don't**: Use AI to generate your work. Provide keywords to an AI and ask it to "write a paragraph", i.e., make it longer. Use tools like Grammarly's Humanizer to obscure the origin of generated text. Leave terms in the text which you don't understand, but which sound professional or scientific. 
- **Motivation**: _"Writing is thinking. To write well is to think clearly. That's why it's so hard."_ ([David McCullough](https://www.goodreads.com/quotes/320581-writing-is-thinking-to-write-well-is-to-think-clearly)). It causes friction that is necessary for any learning to happen. Wrestling with ideas and thoughts and converting them into text and visuals is a core professional skill. Generated content may often look polished, but it lacks clarity, deliberate choice of what you want to tell your audience, semantic correctness, and maintainability (e.g., architectural diagrams as pixel instead of vector graphics).
- **Example**: Write a draft of a report section yourself, then use an LLM-based system to check for parts that are repetitive or could be re-ordered. Use free and open-source tools like [Draw.io](https://www.drawio.com/) to create clean and maintainable diagrams, then ask an AI _"Are they clear mistakes or inconsistencies?"_.

## 2.4 AI-Assisted Coding

- **Do**: For data analyses (e.g., Assignment 2), you may use GenAI to create scripts for querying API endpoints, extracting and analyzing data according to your specifications. Santity-check both the scripts and the data, and attach them to your submission (see _3.1 Mandatory Disclosure_).
- **Don't**: Let the AI fetch data from unknown sources or process data in opaque ways. Report AI-generated interpretations of analysis results without independent and human verification.
- **Motivation**: Being able to code is not a learning outcome in this course, and GenAI is reasonably good at performing such standard technical tasks. Of course, you remain fully responsible, and we expect to audit any generated code and output thereof.
- **Example**: Ask Claude Code to write a Python script to fetch repository meta-data from GitHub and to calculate monthly averages for the number of opened and closed pull requests. You review both the scripts and the generated CSV data files, and draw your own conclusions for your report.

---

# 3. Documentation and Consequences

## 3.1 Mandatory Disclosure

- **Do**: Report any and all AI tool use cases clearly in your report. For each use case, include prompts and generated outputs in an appendix or attachment.
- **Don't**: Skip tools or use cases in your statement. Omit tools used for "minor" tasks like language polishing.
- **Motivation**: Professional software engineering and academic work are not built on obscurity, but rely on transparency and traceability. Any manual activity or tool use can introduce errors or biases. A clear record of how the work was produced allows others to review the process, identify potential sources of error, and establish accountability.
- **Example**: Include a statement such as _"Grammarly was used for language refinement; Scopus AI assisted in finding initial literature for Section 2, prompts and search results are in Appendix B, ..."_. Attach generated code and any raw data to your submission (e.g., ZIP file or public Git repo).

## 3.2 Verification and Disciplinary Actions

- **Oral Follow-Up**: The examiners may conduct an oral follow-up with in-depth questions regarding your report. Failure to demonstrate understanding of the submission handed in under your name results in a **Fail** grade.
- **Disciplinary Board**: In addition to an oral follow-up, we will report suspected misuse of GenAI, i.e., violations of the guidelines defined above, to BTH's Disciplinary Board. They will then conduct interviews with you and may sanction a violation of the rules with a _suspension_, meaning no campus and library access, blocked university account, no student support, not allowed to attend lectures or to be assessed and gain credits (in any course).
- **Example**: Last year, a student who presented an AI-generated table in an architecture report as their own work was suspended for 6 weeks.
