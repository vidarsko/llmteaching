# Resources 

## Internet resources for learning prompt engineering 

!!! abstract "Prompt hub blog ([https://www.prompthub.us/blog](https://www.prompthub.us/blog))"
    This blog is a good starting point for learning about prompt engineering. It contains a lot of information about how to use prompts to improve the performance of large language models (LLMs).


!!! abstract "Learnprompting.orgs documentation ([https://learnprompting.org/docs/intro](https://learnprompting.org/docs/intro))"
    Learnprompting.org is a commercial site offering courses in prompt engineering across a range of topics, including image generation, text generation, and more. 
    The documentation (as of 2024-05-08) is freely available and contains a lot of good information on prompt engineering.

!!! abstract "Prompting guide ([https://www.promptingguide.ai/](https://www.promptingguide.ai/))"
    This is a thorough introduction to the science of prompt engineering. 

## Literature

### Books

!!! abstract "_Maskiner som tenker: Algoritmenes hemmeligheter og veien til kunstig intelligens_ (2023). (English: Machines that think: The secrets of the algorithms and the road to artificial intelligence). Strümke, I.  Kagge forlag AS."
    This book introduces the field of artificial intelligence in a popular science fashion and is a good starting point for those who want to learn more about the field. The book is written in Norwegian.

### Research papers and blog posts on prompt engineering

!!! abstract "_Prompt Engineering_ (2023). Weng, L. [https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/)"
    This blog post is a good introduction to prompt engineering. It explains the basics of prompt engineering and how it can be used to improve the performance of large language models.

!!! abstract "_Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks_ (2021). Lewis, P., Perez, E., Piktus, A., Petroni, F., Karpukhin, V., Goyal, N., Küttler, H., Lewis, M., Yih, W., Rocktäschel, T., Riedel, S., & Kiela, D. arXiv. [https://doi.org/10.48550/arXiv.2005.11401](https://doi.org/10.48550/arXiv.2005.11401)"
    The authors explore the use of RAG to improve LLMs.

!!! abstract "_Self-Consistency Improves Chain of Thought Reasoning in Language Models_ (2023). Wang, X., Wei, J., Schuurmans, D., Le, Q., Chi, E., Narang, S., Chowdhery, A., & Zhou, D. arXiv. [https://doi.org/10.48550/arXiv.2203.11171](https://doi.org/10.48550/arXiv.2203.11171)"
    Self-consistency is a technique in which you generate several responses to a question and see if the results are consistent with each other. The authors show that this technique can improve the performance of LLMs.

!!! abstract "_Chain-of-Thought Prompting Elicits Reasoning in Large Language Models_ (2023). Wei, J., Wang, X., Schuurmans, D., Bosma, M., Ichter, B., Xia, F., Chi, E., Le, Q., & Zhou, D.  arXiv. [https://doi.org/10.48550/arXiv.2201.11903](https://doi.org/10.48550/arXiv.2201.11903)"
    The authors show that chain-of-thought prompting can improve the reasoning capabilities of LLMs.

!!! abstract "_Better Zero-Shot Reasoning with Role-Play Prompting_ (2024). Kong, A., Zhao, S., Chen, H., Li, Q., Qin, Y., Sun, R., Zhou, X., Wang, E., & Dong, X.   arXiv. [https://doi.org/10.48550/arXiv.2308.07702](https://doi.org/10.48550/arXiv.2308.07702)."
    Assigning roles to a prompt can increase the reasoning capabilities of LLMs.


### Research papers on using LLMs in education

!!! abstract "_Teaching Maxwell Equations with LLM Assistance_ (2023). Sawicki. [https://www.researchgate.net/publication/374174720_Teaching_Maxwell_Equations_with_LLM_Assistance](https://www.researchgate.net/publication/374174720_Teaching_Maxwell_Equations_with_LLM_Assistance)."
    In this paper, the authors describe six ways of using LLMs in physics education: to provide organisational information, organize short quizzes, provide individual explanation, create individual tasks, create exam problems and checking solutions.
    They then rate the performance of GPT4, GPT3.5, Bing and Bard (Google's LLM before Gemini) on these tasks.
    Results were promising. 

!!! abstract "_AI-TA: Towards an Intelligent Question-Answer Teaching Assistant using Open-Source LLMs_ (2023). Hicke, Y., Agarwal, A., Ma, Q., & Denny, P.  [https://doi.org/10.48550/arXiv.2311.02775](https://doi.org/10.48550/arXiv.2311.02775)."
    In this paper, they compare different methods of creating an AI teaching assistant (AI-TA) using LLMs.
    They employ fine-tuning methods such as supervised fine-tuning (SFT) based on a collection of Q&A, direct preference optimization (DPO) and retrieval augmented generation (RAG), see [Introduction to large language models](/llms#training).
    They judge the quality of the AI-TA based on the usefullness and accuracy of the results.
    They compare the performance of LLaMa 2 (metas open-source LLM) with SFT, DPO and RAG to GPT-4 with and without RAG, and find that GPT4 with RAG is superior to the other methods. 