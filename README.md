Christebob Creative Platform (MVP)

A warm, story-driven web application for kids, parents, and educators.

Purpose
- Minimal lovable product (MLP) to launch the Christebob universe: landing page, AI chat, stories & books modules, basic admin console, and Supabase backend.
- Tech preview: Next.js 14 (App Router), TypeScript, React 18, TailwindCSS, Supabase, OpenAI.

Quick start (development)
1. Clone
   git clone https://github.com/Christebob/Christebob_Creative_V2.git
   cd Christebob_Creative_V2
2. Install
   npm install
3. Copy env example
   cp .env.example .env.local
   Fill in the values (Supabase, OpenAI, 11Labs if available)
4. Run locally
   npm run dev
5. Lint / typecheck / build
   npm run lint
   npm run build

Environment variables (.env.example)
- See .env.example in repo for required keys.

Supabase
- This project uses Supabase for Auth and DB. Create a project at supabase.com and add keys to .env.local.

API integrations
- OpenAI: used for “Talk to Christebob” chat (server-side API key).
- 11Labs: placeholder key for future voice features.

Admin console
- Basic CRUD endpoints and a simple admin UI will be provided in the app. Protect admin routes via Supabase Auth.

Deployment
- Deploy to Vercel. Set the same environment variables in the Vercel dashboard.

Contributing
- Open an issue or pull request.
- Keep changes minimal and documented.

License
- Add license info or TODO if you want a specific license.