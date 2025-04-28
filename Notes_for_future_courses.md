# In the introduction to different models:

# To Do Konstantin

- Creating Custom Gem on Gemini, memory (ev Gemini)
- Using others CustomGPTs on ChatGPT
- Customizing, system prompt on ChatGPT
- Source for agents graphic: https://medium.com/codex/what-are-ai-agents-your-step-by-step-guide-to-build-your-own-df54193e2de3

# To Do Hannah

- Include writing exercise into the chatbot essentials session?

## Intro

- Delete slide 10 deep learning/neural networks
- Maybe delete word embeddings

---
- Übersicht Modeltypen in Intro: 
  - Reasoning (kann nicht suchen)
  - Flash/Mini: kleiner, effizienter
  - Deep Research
- Exercise to test different models:
- Exercise Mathematik Beispiel in Reasoning und Flash/Mini reingeben
- Reasoning riddle: surgeon and son: https://www.oneusefulthing.org/p/on-jagged-agi-o3-gemini-25-and-everything
- Reasoning via reinforcement learning: https://benjamintodd.substack.com/p/teaching-ai-to-reason-this-years
- Stahl und Federn Beispiel
- Features
  - Google Search
  - Canvas mode
  - Integration...
- Multimodal interactions slide: instead give overview of features and explain that they change quickly over time
- Slide 17: stattdessen Models (2 bilder für gpt und gemini im images folder)

- Add reinforcement learning
- Exercises/part to play with different models

# Models and model features

- Which models exist slide
  - GPT 4.5 (for writing and exploring ideas - is this ChatGPT Deep Research?), 
  - o3 for reasoning and o4 mini. 
  - GPT 4.1 instead of 4: larger window of up to one million tokens of context, gpt4.1 mini, gpt-41 nano. More lightweight. 4.1. is 26 percent cheaper than gpt-4o.
  - GPT-4.5 preview will be deprectated on July 14th? https://www.theverge.com/news/647896/openai-chatgpt-gpt-4-1-mini-nano-launch-availability
  - GPT 5 in a few months
- Claude 3.7
- Update part about o1 to o3
  - o3 mini: quick reasoning (wie Deepseek R1), particularly good for programming
  - better: 04 mini. 
  - trained to problem solve, and use tools agentically (search, write code, generae graphs, explain, etc)

## Claude

- Claude features: integrates with Google Workspace (calendar, Docs), Research: search in your work context and on the web, verified citations (not yet available in Austria)
- Organize in Projects

## ChatGPT features

- projects
- Libary: all your generated images
    - deleting: you need to delete the conversation 
    - (date visible in library when you click on the image, or write a prompt, that will take you back to the conversation)


# Include Deep Research: Google Deep Research, Claude Research

  - Think for much longer
  - provides verified sources
  - limited access with ChatGPT plus (10 questions/ month, 120 as a Pro User - still correct?)
  - still includes unreliable sources, can include hallucinations)
- It asks for clarifications before it writes the report

## Customizing session

- Personalizing GPT: Settings - personalization, or also: Customize ChatGPT
  - Update about the memory function, recommended settings if users want memory vs. not. 3 images with examples by Hannah and where to find it. 
    - new memory feature out since 10 April 2025 for plus users
  - see image in customizing/images: customizing_GPT_individualized_user_info_and_instructions.png. Is this the new system prompt?
  - Info I provide here: 
    - gender, age, some personal attributes I think are relevant, interests, my education, 
    my research topics during the PhD and after (my expertise areas), education I am currently pursuing.
- 1 image about data controls settings in main folder. Interesting: saves shared links

- Gems in Gemini: Gem manager
  - Gems by google, and creating your own (no access to gems by other users?)
  - add up to 10 files, give instructions, and name

# Gemini

- Gemini 2.5 Pro (experimental, free, just less agentic ability)
    - slightly less capable but faster and cheaper models (Gemini 2.5 Flash, and Grok-3-mini)
- Since Gemini 2.0: 
  - multimodal input and output, search, use of programs
  - gemini flash (more efficient, a bit smaller)
- Google Gemini Agents: take care of tasks on its own
- Gemini & ChatGPT app: speak German
- Integration with Google Docs, Gmail, Drive
- Connect to Apps: Youtube, google maps, flights, hotels, workspace, calendar, tasks etc

# Ethan Mollick Newsletter: Which model to use?

- Has a great image comparing the model's features & skills:
- Post: https://www.oneusefulthing.org/p/which-ai-to-use-now-an-updated-opinionated
- Image: https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fd4ce87d9-1ee9-401f-8609-8bafea0eacf9_1560x472.png

# Ethics (Konstantin)

- Privacy has changed: https://www.oneusefulthing.org/i/155502334/privacy-and-other-factors
- Gemini & Claude do not train on your data, opt-out for ChatGPT
- From the blogpost/newsletter: "very major provider (except DeepSeek) now offers some form of privacy-focused mode: ChatGPT lets you opt out of training, and Claude says it will not train on your data as does Gemini. 
- The exception is if you're handling truly sensitive data like medical records – in those cases, you'll still want to look into enterprise versions of these tools that offer additional security guarantees and meet regulatory requirements."
- Gemini Apps Activity: 
  - save activity for 3, 18 or 36 months
  - required for google drive/apps integration

# Prompting (Ethan Molick good enough prompting)

- Most important: there is no correct way of prompting that applies universally. [Ref](https://ai-analytics.wharton.upenn.edu/generative-ai-labs/research-and-technical-reports/tech-report-prompt-engineering-is-complicated-and-contingent/)
- It's hard to predict what will work in a particular use case.
- Prompting tricks are not universal (like being polite). 
- Formatting is consistently important. 
  - (Although the study tested this with the format: "Format your response as follows: 'The correct answer is (insert answer here)'"). 
  - So it's conflated with the prompt "the correct answer is"
- There is no clear science of prompt engineering. AI is inconcistent and weird. 
- treat AI just like an infinitely patient new coworker who forgets everything you tell them each new conversation
- Treat as human citation: OpenAI’s ChatGPT-4.5 Passes Turing Test With 73% Success Rate [ref](https://arxiv.org/pdf/2503.23674)
