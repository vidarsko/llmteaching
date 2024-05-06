# Principles of prompt engineering

Since the introduction of Google, most of us have developed a sense in how to write effective search queries. 
Perhaps even more with language models, it is important to provide them with the right context and information to get the best results.
Having existed for a few years, some general guidelines are starting to emerge on how to write effective prompts for language models, and we have summarized them in the acronym CRESTO.

In explaining the pricinples of prompt engineering, we will make repeated reference to the analogy of the language model as the ship navigating in the sea that is meaning space, see the [site about LLMs](/llms) for more information.

??? info "Context"

    Providing language models with context is one of the most generally applicable principles to leverage the power effectively. 

    Providing a context amounts to placing the ship in the right waters. 

??? bug "Role"

    Give yourself and/or it a clear role. "I am very bad at programming, explain it to me in a simple way" or "You are an extremely skilled educator."

    You can think of providing a role as designing the ship. Does it go fast, slow, is it a cargo ship, a warship, a cruise ship?

??? example "Examples"  

    Provide examples of how you want the answer, or what kind of ideas you want it to come up with.

    Examples are like giving the captain of the ship a list of previous successful voyages.

??? tip "Scope" 

    Tell the language model what field you are in and what it should stick to. If you know approximately where the solution to your problem lies, inform it of this.

    Tell the captain which waters are safe and which are dangerous.

??? question "Task"

    Most importantly, give it a precise task.

    This is like telling the captain where to go and what to do when it gets there.

??? abstract "Output format"

    Tell the language model how you want your answer: as a bullet list? Table? Poem?

    Upon arriving a destination, there might be several treasures to be found. Tell the captain how to present them.

