# EduGenie

**A Google Gemini-powered learning assistant**

EduGenie is an AI study companion designed to make learning more interactive and personal. Ask questions in everyday language, explore difficult topics step by step, and use generated practice activities to reinforce what you have learned.

> **Repository status:** This README describes the EduGenie project. The application code currently in this repository is still FitBuddy AI, so the features and setup below are a project description—not instructions for running an implemented EduGenie application.

## What EduGenie aims to offer

- **Conversational tutoring** — ask follow-up questions and get explanations tailored to your level.
- **Topic explanations** — break down challenging ideas into clear, manageable steps.
- **Study support** — turn a topic or set of notes into summaries, revision prompts, and practice questions.
- **Interactive practice** — use quizzes to check understanding and identify topics to revisit.
- **Gemini-powered responses** — generate learning assistance with Google's Gemini models.

AI responses can be inaccurate or incomplete. Check important facts against trusted learning materials, and treat generated explanations as study support rather than a replacement for a teacher or subject expert.

## Planned technology

- Google Gemini API for AI-generated learning support
- A web application interface for interacting with the assistant

The repository does not yet contain an EduGenie implementation or verified EduGenie setup instructions.

## Gemini API key

When Gemini integration is implemented, create an API key in [Google AI Studio](https://aistudio.google.com/apikey) and configure it as a **server-side environment variable**. Do not put API keys in browser code, commit them to source control, or share them publicly.

Example environment variable name:

```text
GEMINI_API_KEY=your-gemini-api-key
```

Use a local, untracked `.env` file for development if the backend supports it. The actual variable names, model selection, and startup commands should be documented here once the EduGenie application code is in place.

## Privacy

Do not submit passwords, financial details, or other sensitive personal information to an AI chat. Before using EduGenie with personal notes or learning records, review how the application stores and sends that information.

## Development status

EduGenie is currently documented as a project concept. The checked-out app remains FitBuddy AI; its existing source, dependencies, and run commands have not been changed as part of this README update.
