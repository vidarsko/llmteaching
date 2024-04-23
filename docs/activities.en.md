# Suggestions for activities

## Debate

Choose a topic within physics that is suitable for debate. For example, 'strengths and weaknesses of Bohr's atomic model' or 'quantum mechanics vs. general relativity - which is better,' and divide the class into two groups. Then ask the students to spend 30 minutes with the language model to prepare for the debate, for example by having it generate counterarguments.

| Competencies trained | Prompt principles trained |
|----------------------|-------------------|
| [C1: Explaining the technology](learning_outcomes.md#C1:-Explaining-the-technology) | [Context](prompt_engineering.md#context) |
| | [Role](prompt_engineering.md#role) |



## Uniting diverse perspectives

Choose some physics phenomena that may seem counterintuitive. For example: 'Newton’s third law states that force equals counterforce in a collision,' 'It takes 8 minutes from when the sun ceases to exist until we notice anything at all,' and 'You cannot attach a magnet to a car to pull yourself forward.' Then have the students write down what they already know that makes these facts difficult to understand. For example: 'In a collision between a train and a car, it’s worse for the car,' 'When I turn off the light in the bathroom, I notice it immediately,' and 'I can lift things with magnets; it seems like magic.' Then ask the students to use the language model to reconcile these contradictions. Maybe you can outline the entire range in the space of meaning?

## Reading support

Give the students a scientific article that is interesting (or let them find one themselves, if they are extra motivated). Copy the text content and paste it into a language model. Ask it to explain the article to you. 

!!! quote "Prompt suggestion"
    Here is a physics article I found interesting:

    ```
    [paste article]
    ```

    I am a high-school physics student with only limited knowledge of physics. I would like you to explain this article to me in a pedagogical manner. I want you to answer my questions very briefly.

Notice how we have given the language model context, roles, and the format for how it should respond. The preference for brief answers is a personal choice


## Preparation for lab 

Laboratory work is often very difficult because there are many skills that need to be trained simultaneously: understanding of physics, technical skills, reading instructions, and calculating uncertainty. Therefore, it can be useful to set aside 30 minutes before the lab to paste the lab instructions into the language model and then ask it questions.

!!! quote "Prompt suggestion"
    I am supposed to do this laboratory experiment shortly. Here are the lab instructions:

    ```
    [paster lab instructions]
    ```

    I am a high school physics student with only limited knowledge of physics. I would like you to explain these lab instructions to me in a pedagogical manner. I want you to answer very briefly to my questions.

## Lab report writing 

Students may not find writing lab reports the most exciting activity, perhaps, but with language models, you have the opportunity for your students to receive rough feedback from the robot first. Ask students to paste their response into the language model, along with your criteria for how you want the report to be (context). If students submit reports with obvious deficiencies, send it back immediately and ask them to get such feedback from the language model before you give your feedback. Of course, we should not stop giving personal feedback, but perhaps we are on our way into a time where we no longer need to constantly remind students to include figure captions and equipment lists.

## Computational essays

Differentiation is key in programming tasks. Let students explore a physical phenomenon using programming and state that what they have discovered should be presented in front of the class or submitted as a Google Colab notebook. It may not be obvious what it means to explore a physical phenomenon using programming, but a starting point could be to look at this collection of so-called 'Computational essays'. Give students several options:

Create a simulation of a double pendulum in Python (have a working minimal example on hand in case some students are struggling to get started). Find a question you're curious about regarding the pendulum's motion (e.g., when does the motion transition to become 'chaotic') and create a presentation where you compile what you have found.
Simulate a throw with air resistance! Find an interesting question and create a presentation on what you have discovered.
Find your own physical system and question. Create a presentation on what you have found.
