Prompt Engineering for In-Context Learning
CSCI 520
Benjamin O’Neill
bgoneill@wm.edu

This repository contains the prompts, model outputs, and analysis for the Prompt Engineering for In-Context Learning assignment. The goal of this assignment was to explore the capabilities of large language models (LLMs) in software engineering tasks by designing effective prompts.

Selected Models: ChatGPT, Claude, Gemini, and LLaMA

Temperature Settings: ChatGPT and LLaMA were both set to a temperature of 0.7 manually through the GitHub models, while Gemini is suspected to be around 1 and Claude is suspected to be around 0.6. I selected 0.7 as a setting, as I wanted a somewhat comparable temperature between the four models, and I’d rather have an outlier be more random than the pack (Gemini) than less random than the pack (Claude).

Max Prompt Length: ChatGPT and LLaMA were both set to have a maximum of 1500 tokens, primarily because the models would simply cut off their answers if not given enough length, which would result in possibly missing key summarizations of the responses. Neither Gemini nor Claude had a setting that could be controlled that would limit the total number of tokens, so they were allowed to run to completion. 1500 was generally enough for all models to form a complete answer.

Combinations: I decided that I wanted to compare each model to one another a roughly equal number of times, and I knew there were 6 possible combinations to compare models. Because later questions become more complicated, I had each comparison occur repetitively in sequence. Each comparison happened at least 3 times, but no more than 4 times.

Counts (Out of 44)
Zero Shot Prompt: 20
Few Shot Prompt: 6
Chain-of-Thought: 7
Self-Consistency: 5
Prompt-Chaining: 6

Assignment Description

The assignment involves designing and testing prompts for various software engineering tasks using LLMs. Students are required to use at least two different prompting strategies for each of the 22 given problems, compare the outputs of at least two different LLMs, and analyze the results. The tasks cover code understanding and generation, including summarization, bug fixing, and classification. The final submission includes a GitHub repository with the prompts, outputs, scripts, and a PDF report detailing the analysis.
