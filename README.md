# sv

Everything you need to build a Svelte project, powered by [`sv`](https://github.com/sveltejs/cli).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npx sv create

# create a new project in my-app
npx sv create my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```
🔹 1. Add Setup Instructions to Your README

You should clearly explain how others can run the app locally:

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Benard-ICT/family-legacy-app.git
cd family-legacy-app

2. Install Dependencies

npm install

3. Add Supabase Environment Variables

Create a .env file in the root directory and add:

VITE_SUPABASE_URL=your-supabase-url
VITE_SUPABASE_ANON_KEY=your-anon-key

(Replace with your actual Supabase credentials)
4. Start the Development Server

npm run dev

The app will run at http://localhost:5173


---

### 🔹 2. **Create a `.env.example` File**
Add a safe sample file like:

```env
VITE_SUPABASE_URL=https://your-project.supabase.co
VITE_SUPABASE_ANON_KEY=your-anon-key

This helps others know which environment variables they need without exposing real keys.
🔹 3. Deploy the App (Optional)

If you want others to test it without installing:

    Use platforms like:

        Vercel

        Netlify

        Render
You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.
