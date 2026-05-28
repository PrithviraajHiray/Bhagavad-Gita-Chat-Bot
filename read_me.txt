# GitaGuidance AI

GitaGuidance AI is a spiritual, context-aware chatbot web application designed to help users navigate life's dilemmas, stress, and anxieties by leveraging the eternal wisdom of the **Shrimad Bhagavad Gita**. By combining a curated scriptural database with advanced language models via the OpenRouter API, the application delivers personalized, compassionate, and practical guidance grounded strictly in authentic Vedic philosophy.

---

## Key Features

* **Scripture-Grounded AI Chat**: Translates modern problems into targeted scriptural guidance by mapping user dilemmas to matching Sanskrit shlokas.
* **Persistent Conversation Memory**: Retains conversation history securely across browser sessions using `localStorage` so the AI can reference past discussions.
* **Daily Shloka**: Dynamically updates on the frontend dashboard to display an inspiring verse from the Gita for daily reflection.
* **Journey Summarization**: Distills your entire chat history into a structured "Spiritual Growth Report" highlighting core lessons.
* **Personal Mantra Generator**: Crafts a custom, one-sentence spiritual affirmation based on your active conversation to help you stay grounded.

---

## Project Structure

```markdown
GitaGuidanceAI/
├── index.html     # Frontend UI structure and layout
├── style.css      # Custom peacock-feather color aesthetics and animations
├── app.js         # State management, local storage memory, and API orchestration
└── gita_db.json   # Structured database housing Gita verses and daily mapping