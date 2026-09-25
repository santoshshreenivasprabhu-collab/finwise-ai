# FinWise AI

FinWise AI is a React + TypeScript + Vite personal finance manager using Supabase for authentication/data and a Supabase Edge Function for AI categorization and insights.

## Run locally

1. Install dependencies: `npm install`
2. Create a `.env` file with:
   - `VITE_SUPABASE_URL`
   - `VITE_SUPABASE_ANON_KEY`
3. Start: `npm run dev`

## Important

The `.env` file is intentionally excluded from this repository. Configure the Supabase environment variables in the target hosting/development environment instead.

The Supabase Edge Function `supabase/functions/smart-endpoint` expects its server-side secrets to remain configured in Supabase; do not commit OpenRouter or service-role secrets to GitHub.
