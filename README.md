# Conversation

A minimalist one-to-one AI chat application for Vercel.

## Configuration
Set **OPENAI_API_KEY** in Vercel Project Settings → Environment Variables for Production, Preview and Development. Never commit the secret.

The homepage will load without a key, but chatting requires one.

## Notes
Session messages stay in browser memory and reset with New Conversation or reload. Before a public launch, add authentication, rate limits, abuse prevention, and a spending cap to prevent unexpected API costs.
