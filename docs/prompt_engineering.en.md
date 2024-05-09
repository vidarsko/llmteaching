# Principles of prompt engineering

Since the introduction of Google, most of us have developed a sense in how to write effective search queries. 
Perhaps even more with language models, it is important to provide them with the right context and information to get the best results.

In explaining the pricinples of prompt engineering, we will make repeated reference to the analogy of the language model as the ship navigating in the sea that is meaning space, see the [site about LLMs here](/llms) for more information.

There are many extensive guides and courses to master prompt engineering out there, see the [resources page](/resources) for more information, but we have summarized the most important principles in the acronym "CRESTO".

??? info "Context"

    Providing language models with context is one of the most generally applicable principles to leverage the power effectively. 

    Providing a context amounts to placing the ship in the right waters. 

    A particularly useful application of this, is to create a collection of snippets, ready to be used with the LLM. 

    - Give it a text or a list of facts
    - Give it a text on the topic that you have already written, perhaps with [the world's most dangerous writing app](/resources/)

??? bug "Role"

    Give yourself and/or it a clear role. "I am very bad at programming, explain it to me in a simple way" or "You are an extremely skilled educator."

    You can think of providing a role as designing the ship. Does it go fast, slow, is it a cargo ship, a warship, a cruise ship?

    - Write in the style of Hemingway/Shakespeare/Orwell/a lawyer/a teacher
    - Write the text for a child/university student/professor/journalist/politician

??? example "Examples"  

    Provide examples of how you want the answer, or what kind of ideas you want it to come up with.

    Examples are like giving the captain of the ship a list of previous successful voyages.

    - Give it examples of good texts that you want to emulate
    - Give it examples of what you want to avoid: "Don't write like this"

??? tip "Scope" 

    Tell the language model what field you are in and what it should stick to. If you know approximately where the solution to your problem lies, inform it of this.

    Tell the captain which waters are safe and which are dangerous.

    - "Only use information from the last 5 years"
    - "Only use information from the field of physics"
    - "Cite sources"

??? question "Task"

    Most importantly, give it a precise task, including what style you want it to write in.

    This is like telling the captain where to go and what to do when it gets there.

    - Write a text that explains the concept of prompt engineering
    - Write with a tone that is formal/casual/serious/funny/scientific/popular science/pessimistic/optimistic/concise/verbose/persuasive/informative.

??? abstract "Output format"

    Tell the language model how you want your answer: as a bullet list? Table? Poem?

    Upon arriving a destination, there might be several treasures to be found. Tell the captain how to present them.

    - Give me the output as a list/table/poem.


