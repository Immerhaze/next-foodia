# Mealtaim 🍽️

AI-powered recipe generator that creates personalized meal plans based on your health profile, dietary preferences, allergies and weekly budget.

🔗 **[Live Demo](https://next-foodia-nicolas-romero-carrillos-projects.vercel.app/)**

## What it does

Fill out a form with your physical data (weight, height, age, activity level), dietary type (vegan, omnivore, pescatarian, etc.), any allergies or intolerances, medical conditions and weekly budget in CLP — and the app generates a fully personalized recipe plan.

Results can be **downloaded as PDF** or **sent directly to your email**.

## Tech Stack

- **Next.js** — App Router
- **Vercel AI SDK** — AI-powered recipe generation
- **TypeScript**
- **Tailwind CSS**

## Features

- 🧬 Personalized by body type, goal (gain/lose weight) and diet
- 🚫 Allergy & intolerance filtering (nuts, gluten, lactose, etc.)
- 🏥 Medical condition awareness (diabetes, hypertension, IBS, etc.)
- 💰 Budget-aware meal planning (CLP)
- 📄 PDF export & email delivery

## Run locally

```bash
git clone https://github.com/Immerhaze/next-foodia
cd next-foodia
npm install
npm run dev
```

> Requires a Vercel AI SDK API key in `.env.local`

---

Built by [Nicode](https://www.linkedin.com/in/nicolas-romero--nicode/)
