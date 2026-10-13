---
course:
  code: PA1453
  name: Software Architectures and Quality
term: HT2026
status: work-in-progress
---

# GenAI Policy

_Note: Throughout this document, "you" refers to students enrolled in the course, "we" refers to course responsibles, examiners, and other teachers involved in grading._

The overarching goal of your work in this course is to demonstrate your ability to analyze architectural issues as well as reflect on the appropriateness of solutions addressing them.
All GenAI use must align with the objectives and intended learning outcomes defined in the [course syllabus](https://bth.azure-api.net/lindplan/courseplanbycode?code=BYLNM&semester=20262&lang=en).
GenAI should support, rather than replace, your demonstration of competencies such as critical thinking and technical writing.

The guidelines below are written in a "Do"/"Don't" format to explain what you are allowed or even encouraged to do, and what you must not do, respectively.
Each guideline has a "Motivation" for you to understand why we have included it in this policy document and an "Example" to illustrate how acceptable behavior can look like.

## 1. General Principles
### 1.1 Full Responsibility and Accountability

* **Do**: Take total ownership of every word, figure, and line of code; verify all AI-assisted output against primary sources. 
* **Don't**: Assume that the AI knows best (using "The AI said so" as a justification for yourself), that the technical details and formulations don't matter, or that the examiners won't notice that you don't understand some parts of it.
* **Motivation**: You are "signing" your report as your intellectual output, just as software architecture are accountable for the designs and recommendations they present in professional contexts. You must be able to explain, justify, and trace the origin of any part of it. In student groups, accountability is collective; all authors are responsible for the entire content.
* **Example**: A student used ChatGPT for structuring a report, found the output to be verbose and superficial. Now knowing how his report should not look like, he started from scratch on his own.

### 1.2 Transparency

* **Do**: Openly discuss your GenAI workflows within your in your group; open discuss it with us, your teachers (e.g., in the workshops), to better understand opportunities, limitations, and risks of specific use cases.
* **Don't**: Be ashamed of using GenAI tools, hide your use of tools from your group members or the teachers.
* **Motivation**: Pragmatically, no policy document can cover every use case. More importantly, transparency is a sign of professional integrity and academic maturity: Tools and processes should be open to review and just as disussable as technical design decisions. We highly value and appreciate being careful and reflective about GenAI use (or any tool use, for that matter).
* **Example**: Show us the prompts you used to explore possible directions for your topic and explain how you worked with the ideas.

## 2. Guidelines throughout the Course
### 2.1 AI-Assisted Exploration of Architectural Concepts

* **Do**: Use GenAI to learn about unfamiliar concepts, discuss general (assignment-independent) architectural ideas.
* **Don't**: Treat GenAI output as established fact. Stop your investigation after receiving an AI-generated explanation (see also 2.3 Human Authorship).
* **Motivation**: Software architects regularly need to learn about technologies, patterns, and domains. GenAI can help you discover relevant ideas, but architectural work requires understanding and judgment, not merely collecting and repeating pre-formulated answers.
* **Example**: Chat with Claude to understand Event Sourcing and discuss situations in which it may be useful (e.g., "Explain it to me like I am 10 years old"). Skim some primary source which Claude pointed out (e.g., [Fowler's 2005 article](https://martinfowler.com/eaaDev/EventSourcing.html), or [Ch. 6 of Lawrence's 2026 book](https://learning.oreilly.com/library/view/message-and-event-driven/9780137998654/ch06.html)). Then you, not Claude, decide for youself whether it is relevant for your situation.

### 2.2 Human Analysis and Decision-Making

* **Do**: Do your own analysis and first design for an architecture, then use GenAI to critique it, challenge your assumptions, and identify weaknesses.
* **Don't**: Ask GenAI to perform any of the tasks described in the assignment description on your behalf. Delegate architectural decisions to GenAI.
* **Motivation**: Among the key responsibilities of a software architect is to analyze architectural problems, evaluate trade-offs, and make design decisions. A central learning outcome of this course is therefore your ability to perform this reasoning yourself. You should not aim for "perfect", but for "good enough". It is better to come up with a simple architecture design that has some drawbacks but which you fully understand than submitting a clean-looking, likely over-engineered solution of which you understand less than half.
* **Example**: You identified run-time modifiability as an important quality attribute and consider applying the Client-Server pattern. In a discussion with ChatGPT, it asks whether there even are multiple hardware devices connected via a network, and you realize that you need to look for a non-distributed pattern.

### 2.3 Human Authorship of Text

* **Do**: Use AI to shorten your work. Write in your own words, then use AI to identify parts to cut. Use language-focused tools like Grammarly's Proofreader to refine grammar, spelling, and flow of text you have already written in full. (Attention: Chat-based systems like ChatGPT require extra care because they are designed to please their users and always offer to do more than you asked them to!)
* **Don't**: Use AI to generate your work. Provide keywords to an AI and ask it to "write a paragraph", i.e., make it longer. Use tools like Grammarly's Humanizer to obscure the origin of generated text. Leave terms in the text which you don't understand, but which sound professional or scientific.
* **Motivation**: _"Writing is thinking. To write well is to think clearly. That's why it's so hard."_ ([David McCullough](https://www.goodreads.com/quotes/320581-writing-is-thinking-to-write-well-is-to-think-clearly)). It causes friction that is necessary for any learning to happen. Wrestling with ideas and thoughts and converting them into text and visuals is a core professional skill. Generated content may often look polished, but it lacks clarity, deliberate choice of what you want to tell your audience, semantic correctness, and maintainability.
* **Example**: Write a draft of a report section yourself, then use an LLM-based system to check for parts that are repetitive or could be re-ordered.

### 2.4 Human Authorship of Images

* **Do**: Create technical diagrams, tables, images, etc. yourself. You may use AI tools to choose a "nicer" color scheme, font, and similar non-substantial aspects of the work.
* **Don't**: Ask AI to create an architecture diagram.
* **Motivation**: Generated diagrams, tables, images, etc. lack the deliberate choice of what you want to tell your audience and maintainability. E.g., architectural diagrams that are generated as pixel graphics (or in any other format that you cannot easily edit), lock you into certain tools.
* **Example**: Use free and open-source tools like Draw.ioLinks to an external site. to create clean and maintainable diagrams, then ask an AI _"Are they clear mistakes or inconsistencies?"_. Alternatively, you could also draw your diagrams by hand, and ask an AI tool to convert the photo into a maintable MermaidLinks to an external site. diagram code.

### 2.5 Opposition (Peer Review)

* **Do**: There is little good use for AI for an opposition. You may use AI to help you structure your own notes taken on your classmate's architecture design.
* **Don't**: Use AI to analyze a classmate's architecture design. Present AI-generated arguments which you do not fully understand.
* **Motivation**: Being able to critically examine the work of others is a learning outcome in this course. Also: Uploading somebody else's work to public AI services violates GDPR and copyright. Additionally, consider the other perspective: Receiving generated opposition is highly annoying because your are arguing against something the opponent does not even understand themselves.
* **Example**: Understand your peer's work and take manual notes on its strengths and weaknesses. You may feed only your own notes rather to an AI tool, e.g., to reduce redundant or inconsistent critique.

## 3. Documentation and Consequences
### 3.1 Mandatory Disclosure

* **Do**: Report any and all AI tool use cases clearly in your report. For each use case, include prompts and generated outputs in an appendix or attachment.
* **Don't**: Skip tools or use cases in your statement. Omit tools used for "minor" tasks like language polishing.
* **Motivation**: Professional software engineering and academic work are not built on obscurity, but rely on transparency and traceability. Any manual activity or tool use can introduce errors or biases. A clear record of how the work was produced allows others to review the process, identify potential sources of error, and establish accountability.
* **Example**: Include a statement such as _"Grammarly was used for language refinement; Scopus AI assisted in finding initial literature for Section 2, prompts and search results are in Appendix B, ..."_. Attach generated code and any raw data to your submission (e.g., ZIP file or public Git repo).

### 3.2 Verification and Disciplinary Actions

* **Oral Follow-Up**: The examiners may conduct an oral follow-up with in-depth questions regarding your report. Failure to demonstrate understanding of the submission handed in under your name results in a Fail grade.
* **Disciplinary Board**: In addition to an oral follow-up, we will report suspected misuse of GenAI, i.e., violations of the guidelines defined above, to BTH's Disciplinary Board. They will then conduct interviews with you and may sanction a violation of the rules with a suspension, meaning no campus and library access, blocked university account, no student support, not allowed to attend lectures or to be assessed and gain credits (in any course).
* **Example**: Last year, a student who presented an AI-generated table in an architecture report as their own work was suspended for 6 weeks.
