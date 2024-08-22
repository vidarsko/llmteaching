# Good use cases of large language models

Large language models (LLMs) are versatile tools that can be used in a variety of contexts. Here are some examples.

## Making flow charts in LaTeX

Flow charts are a common way to represent processes and workflows.
They are used in a variety of contexts, including software development, business process modeling, and academic research.
Large language models can be used to generate such flow diagrams using TikZ in LaTeX.

## As a reverse dictionary

Ever had a word on the tip of your tongue but couldn't remember it?

As opposed to a normal dictionary, where you look up a word to find its meaning, a reverse dictionary allows you to describe a word and get a list of words that match that description.
Large language models are excellent for this.

## Hard-to-solve, easy-to-check problems

The above is a type of problem that is easy to check but hard to solve.
LLMs are excellent to use in such circumstances, because they can generate solutions that can be easily checked.
For example, it may be hard to formulate an answer to a question, but easy to check if a given answer is correct.
Or in coding, if you are looking for code to solve a specific problem, it may be hard to write the code, but easy to check if a given code snippet solves the problem.

## Change data formats

LLMs can be used to convert data from one format to another.

## Personal notebook

There are some services that allow AI to search in your notes for you. Perplexity and notion. 


## Reading large amounts of text for you

If you need to read a lot of text (like law data) and you are only looking for a certain specific piece of information, you can use LLMs to read the text for you and extract the information you need.


## Language checker

Make your own GPT prompt that can be used as a language checker. 
Here is a template

!!! note "Language checker template"
    ```
    You are given a text snippet, which may be in English or Norwegian. Your job is to provide feedback on the text snippet in the following format:
    - Spelling mistakes: A bullet point list of the spelling mistakes in the text.
    - Grammatical mistakes: A bullet point list of the grammatical errors in the text.
    - Clarity: A bullet point list of possibly ambiguous or unclear sentences.
    If there are no issues in a category, state "No issues found" and move on. Do NOT write the corrected text for me.
    ```

## Pre-screening hand-ins as a teacher

Create a prompt that can be used to pre-screen hand-ins as a teacher.
By writing a prompt that asks the model to check for different criteria, you may be able to have the studetns get their primary feedback from the model, and then you can focus on the more qualitative aspects of the hand-in.
A suggestion for how such a prompt could look is given below.

!!! note "Pre-screening hand-ins template"
    ```
    You are given a text snippet, which is a hand-in from a student. Your job is to provide feedback on the text snippet in the following format. For each point, provide a bullet point list of the issues you find in the text, and feedback on how the student can improve:
    - Structure: The structure of the report should be according to the Imrad structure: Introduction, Method, Results, and Discussion.
    - Length: The full report should not exceed 2000 words. Provide concrete suggestions on what to remove or condense if it is too long.
    - References: The report should have at least 5 references in the APA format.
    - Figure text: All figures should have a caption that explains what the figure shows and one sentence explaining its significance. 
    - Spelling and grammar: The text should be free of spelling and grammatical errors.
    - Clarity: The text should be clear.


## Other fun resources

Hugging face qr code generator 


