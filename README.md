# Slovarik

Slovarik is a personal vocabulary app for learning foreign words and practicing translations.

## MVP Requirements

1. **Word Input**
   - Add words through HTTP API and Telegram bot.
   - Use shared application logic for both interfaces.

2. **AI Word Analysis**
   - Detect the word's language.
   - Generate transcription.
   - Identify word meanings.
   - Generate translations for each meaning.

3. **Vocabulary Storage**
   - Store words, meanings, transcriptions, and translations.
   - Prevent duplicate records.
   - Maintain data integrity and semantic relationships between words.

4. **Vocabulary Retrieval**
   - Retrieve saved words with their meanings and translations.
   - Support language filtering and pagination.

The first version focuses on Russian and English, with support for more languages in the future.

## Tech Stack

- **Backend:** Node.js, TypeScript, Fastify.
- **Database:** PostgreSQL, `pg`, SQL.
- **AI:** LLM API.
- **Telegram:** Telegram Bot API.
- **Monorepo:** pnpm workspaces.
- **Deployment:** Docker Compose, VPS.

A web interface using React, TypeScript, Vite, and Tailwind CSS is planned for future development.
