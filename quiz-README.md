# QuizForge

A browser-based quiz generator that uses AI to create custom multiple choice quizzes on any topic you want. Type in a subject, pick a difficulty, and it builds you a 5-question quiz in seconds.

## What it does

- Accepts any topic as input (history, science, programming, pop culture, anything)
- Three difficulty levels: easy, medium, hard
- Generates 5 unique multiple choice questions each time
- Shows instant feedback after each answer with an explanation
- Tracks your score and gives a breakdown at the end

## How to use it

Open index.html in your browser. You will need an API key from console.anthropic.com to generate quizzes. Sign up there for free, create a key, and paste it into the field on the app. The key is never stored or sent anywhere other than directly to the API.

Enter a topic, choose a difficulty, hit generate, and the quiz builds itself in about 5-10 seconds.

## Stack

HTML, CSS, and vanilla JavaScript. Calls the AI API directly from the browser with no backend needed.

## Notes

Since this calls an external API, you need an internet connection for the quiz generation to work. The questions are generated fresh each time so you will get different questions even on the same topic.
