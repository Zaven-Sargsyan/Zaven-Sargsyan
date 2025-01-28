<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Personalized Study Assistant

Final project for the Building AI course

## Summary

The Personalized Study Assistant is your friendly AI-powered tool to help you ace exams or learn new topics. It creates study plans, quizzes, and tracks your progress—all tailored to your preferences, goals, and time availability. Say goodbye to unorganized study sessions!

## Background

Let’s face it: studying can be overwhelming. Many of us struggle with questions like, “Where do I even start?” or “Am I actually making progress?” This problem is common for students, professionals preparing for certifications, or anyone diving into self-learning.

My motivation comes from wanting to make learning less stressful and more engaging. Everyone deserves a study buddy who’s available 24/7, keeps them on track, and celebrates their wins.

This project tackles:
* The lack of personalized study plans
* Difficulty in tracking meaningful progress
* The chaos of managing time effectively

## How is it used?

This tool is simple and interactive, designed for anyone with access to Python. Here’s how it works:

1. Fire it up and tell the assistant what topics you want to study.
2. Input how much time you have to spare.
3. The assistant generates a personalized study plan and quizzes you as you go.
4. It tracks your progress and motivates you to keep going.

Perfect for:
* Students cramming for exams
* Lifelong learners diving into new subjects
* Professionals prepping for certifications

Here’s a sneak peek of what it feels like to use it:
```
Welcome to the Personalized Study Assistant!
What's your name? John
Hello, John! Let's set up your study plan.
Available topics: Math, Science, History
Select topics you'd like to study (comma-separated): Math, Science
How many minutes can you study today? 30

Your Study Plan for Today:
- Math: 2 questions
- Science: 2 questions

Let's start your quiz!
Topic: Math
What is 2 + 2?
Your answer: 4
Answer recorded!
...
```

## Data sources and AI methods

Currently, the tool uses predefined topics and questions stored in a Python dictionary. For future versions, I’d love to integrate:
* [OpenAI APIs](https://openai.com/api/) for generating dynamic, topic-specific questions
* Open educational resources for a wider range of study materials

The core AI methods include:
* Random sampling to select quiz questions
* Simple progress tracking to give users instant feedback

| Input       | Description                |
| ----------- | -------------------------- |
| User topics | Topics selected by the user |
| Time        | Study time provided         |

| Output      | Description                |
| ----------- | -------------------------- |
| Study plan  | Custom schedule for the day|
| Quiz        | Randomly selected questions|
| Progress    | Tracks questions completed |

## Challenges

While this tool is a great start, it has its limitations:
* It doesn’t yet evaluate your answers for correctness.
* It relies on predefined questions, so content variety is limited.
* There’s no graphical interface (yet), making it less user-friendly for non-technical users.

Ethical considerations:
* Ensuring user data (like progress) is kept private.
* Avoiding bias in study materials.

## What next?

I envision this project growing into a full-fledged web or mobile app, complete with:
* Smart answer evaluation with detailed feedback
* Dynamic question generation using AI
* Adaptive learning algorithms to keep it challenging and fun

What I’d need to take it further:
* Skills in web and mobile development (think Flask or React!)
* Deeper knowledge of machine learning for personalized learning paths
* Access to educational datasets or APIs

## Acknowledgments

* Shoutout to the Building AI course by Reaktor Innovations and the University of Helsinki for sparking this idea
* Thanks to open-source education tools that inspired me
* [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
