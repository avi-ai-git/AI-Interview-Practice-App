# Instructions

This folder contains only the supporting files that make sense for the current version of the app.

The app now has one main loop:

```text
Question
Answer
Feedback out of 10
Next question
```

There is no separate score button anymore. Every submitted answer is reviewed automatically.

## Files

1. `demo_job_descriptions.md` gives simple job descriptions you can paste into the app.
2. `testing_checklist.md` gives practical tests before deployment.
3. `review_prep.md` helps explain the code during a project review.
4. `security_notes.md` explains the guardrails in plain English.

## Suggested review demo

1. Start with `anthropic/claude-haiku-4.5`.
2. Paste the Product Growth Manager demo job description.
3. Start the interview with the answer box empty.
4. Give a weak answer and show red feedback.
5. Give a stronger answer using Situation, Task, Action, and Result.
6. Show that the app gives feedback automatically before asking the next question.
7. Explain how the app protects the API key and handles prompt injection.
