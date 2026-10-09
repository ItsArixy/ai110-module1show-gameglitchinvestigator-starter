# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
It opened up a REACt-style game prompt. The idea was to select your difficulty and input a number with hints telling you to go up or down.
- List at least two concrete bugs you noticed at the start  
The score would always go down, despite getting the correct number. And trying to select a new mode or game would prompt the game to crash/not work by still thinking its the same game mode.

**Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input | Expected Behavior | Actual Behavior | Console Output / Error |
|-------|-------------------|-----------------|------------------------|
| | | | | No Score Decrease  Decrease with Correct Response
| | | | | 
| | | | |

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)? Claude
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result). How the functions create a certain exception error and how that can be handled.
- Give one example of an AI suggestion you did not accept as written (including what the AI suggested, why you rejected or changed it, and how you verified your version). It does not have to be a suggestion that was wrong: over-engineered, out of scope, harder to read, or a poor fit for this codebase all count. Harder to read than the regular base and needed certain things being simplier in scope.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed? If the intended result is returned.
- Describe at least one test you ran (manual or using pytest)  Manuel run
  and what it showed you about your code.
- Did AI help you design or understand any tests? How? It helped me understand certain inheritance issues.

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit? How to host private session through your local host ports for solo development.

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git. How to repatedly test things through a coding base.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code. How AI can be used as a helper tool to look through code at a faster rate for solo development.
