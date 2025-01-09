# Prompt Templates

When asking large language models, like ChatGPT, it may make sense to ask similar questions over and over follow 
standardized formats to have comparable results. For this, prompt-templates might be helpful.
Just copy the template you like and paste it into the chat window of your favorite language model.
Make sure to replace the `<placeholders>´ with your actual content.

## Prompting for a DMP

```
Given the following Project Description and DMP Template, please generate a Data Management Plan (DMP) for the project.

## Project Description

<Enter your project description here>

## DMP Template

<Enter your template here>

## Your Task

Write a project-specific DMP based on the given project description and DMP template.
```

## Prompting for feedback

```
I have written a DMP and my boss was unhappy with it. Unfortunately, they didn't have time to provide detailed feedback. 
Please generate constructive feedback for the DMP.

## DMP

<Your DMP here>

## Your Task
Give me a list of action points allowing me to improve the DMP.
```

Or

```
I have written the following DMP and would like to know what's missing.

## DMP

<Your DMP here>

## Your task
What is missing in the DMP?
```

## Prompting for explanations

```
Explain the following text in your own words:

## Text to explain

<Your Text here>

## Your Task

Explain the text like I am a 5-year-old.
Answer the following questions:
- What is the text about?
- What do the technical terms mean?
- In which context might this text be relevant?
```

## Prompting for DMP-specific stuff

```
Which topics are typically covered in a Data Management Plan (DMP)?
```

```
What can the section "Backup / Archiving" in a Data Management Plan (DMP) contain?
```

```
What does access control mean in the context of a Data Management Plan (DMP)?
```
