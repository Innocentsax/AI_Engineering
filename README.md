# LLM Engineering - Master AI and LLMs

## Instant Gratification instructions with Llama 3.2 **not** Llama 3.3

### Important note: see my warning about Llama3.3 below - it's too large for home computers! Stick with llama3.2 - several students have missed this warning...

We will start the course by installing Ollama so you can see results immediately!
1. Download and install Ollama from https://ollama.com noting that on a PC you might need to have administrator permissions for the install to work properly
2. On a PC, start a Command prompt / Powershell (Press Win + R, type `cmd`, and press Enter). On a Mac, start a Terminal (Applications > Utilities > Terminal).
3. Run `ollama run llama3.2` or for smaller machines try `ollama run llama3.2:1b` - **please note** steer clear of Meta's latest model llama3.3 because at 70B parameters that's way too large for most home computers!  
4. If this doesn't work: you may need to run `ollama serve` in another Powershell (Windows) or Terminal (Mac), and try step 3 again. On a PC, you may need to be running in an Admin instance of Powershell.  
5. And if that doesn't work on your box, I've set up this on the cloud. This is on Google Colab, which will need you to have a Google account to sign in, but is free:  https://colab.research.google.com/drive/1-_f5XZPsChvfU1sJ0QqCePtIuc55LSdu?usp=sharing

Any problems, please contact me!

## Before the Setup instructions - a special note

Early on in the course (on Day 2), I give a demo of a very cool, popular product called Claude Code. It's an AI coding tool, similar to Cursor that we use on the course. I'm only showing this as an example of Agentic AI in action; it's not a tool that's covered explicitly on this course, particularly as we're in Cursor. But if you want to use Claude Code yourself, the Quick Start guide from Anthropic is [here](https://docs.claude.com/en/docs/claude-code/quickstart).

## OK - now on to Setup instructions

After we do the Ollama quick project, and after I introduce myself and the course, we get to work with the full environment setup.  

Hopefully I've done a decent job of making these guides bulletproof - but please contact me right away if you hit roadblocks:

Setup instructions: [Setup Instructions All Platforms](setup/SETUP-new.md)

### Free alternative to Paid APIs

See [Guide 9](guides/09_ai_apis_and_ollama.ipynb) in the guides directory for the detailed approach with exact code for Ollama, Gemini, OpenRouter and more!

### How this Repo is organized

There are folders for each of the "weeks", representing modules of the class, culminating in a powerful autonomous Agentic AI solution in Week 8 that draws on many of the prior weeks.    
Follow the setup instructions above, then open the Week 1 folder and prepare for joy.

## Starting in Week 3, we'll also be using Google Colab for running with GPUs

You should be able to use the free tier or minimal spend to complete all the projects in the class. I personally signed up for Colab Pro+ and I'm loving it - but it's not required.

Learn about Google Colab and set up a Google account (if you don't already have one) [here](https://colab.research.google.com/)

The colab links are in the folders for Week 3 and Week 7 - if you open up the lab for each day, you'll find a direct link to the colab.

### Monitoring API charges

You can keep your API spend very low throughout this course; you can monitor spend at the dashboards: [here](https://platform.openai.com/usage) for OpenAI, [here](https://console.anthropic.com/settings/cost) for Anthropic.

The charges for the exercsies in this course should always be quite low, but if you'd prefer to keep them minimal, then be sure to always choose the cheapest versions of models:
1. For OpenAI: Always use model `gpt-4.1-nano` in the code
2. For Anthropic: Always use model `claude-3-haiku-20240307` in the code instead of the other Claude models
3. During week 7, look out for my instructions for using the cheaper dataset
