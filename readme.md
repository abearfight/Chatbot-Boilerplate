# Chatbot Boilerplate

A Next.js chatbot supporting multiple AI providers.

## Features

### Framework & Performance
- Next.js 13+ (App Router)
- React Server Components & Server Actions
- Optimized for performance

### UI
- UI built with shadcn/ui and Tailwind CSS
- Accessible components via Radix UI
- Clean and intuitive interface

### Backend & Data
- Chat history stored in PostgreSQL
- Supports configurable file storage solutions
- User authentication via NextAuth.js

### AI Integration
- Default support for OpenAI's GPT-4o
- Easily switch to other providers like Gemini, DeepSeek, Anthropic, and more via its AI integration layer.

## Local Development Setup

1.  **Clone Repository:**
    ```bash
    git clone [https://github.com/abearfight/Multi-Api-Next-JS-Chatbot.git](https://github.com/abearfight/Multi-Api-Next-JS-Chatbot.git)
    cd Multi-Api-Next-JS-Chatbot
    ```

2.  **Configure Environment:**
    - Copy `.env.example` to `.env`.
    - Populate `.env` with your API keys, database connection details, and other required configurations.

3.  **Install Dependencies:**
    ```bash
    npm install
    ```

4.  **Run Development Server:**
    ```bash
    npm run dev
    ```
    Access at `http://localhost:3000`.

## Contributions

Contributions, issues, and feature requests are welcome.
- Open an issue.
- Submit a pull request.

## License

MIT Licensed.

---
Repository: [https://github.com/abearfight/Multi-Api-Next-JS-Chatbot.git](https://github.com/abearfight/Multi-Api-Next-JS-Chatbot.git)
