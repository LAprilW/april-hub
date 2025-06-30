april‑hub

Elevator pitch: A lightweight, dark‑mode–ready résumé & project showcase built with Next.js—because recruiters shouldn’t need night‑vision goggles.

👋 About Me

Hi! I’m April—former pro dog groomer turned aspiring software developer. I’m currently earning an A.S. in Computer Science at University of the People, with plans to continue on to the B.S. (and maybe the M.S.—because why stop at halftime?). When I’m not debugging code, you’ll find me training poodles or scouring Spartanburg for the next great taco.

📸 Live Demo & Screenshots

Live site: https://YOUR‑DEPLOY‑URL.com (replace once deployed)

Screenshots / GIFs: Add a couple of light‑ and dark‑theme shots here.

✨ Features

Dark / Light Theme Toggle (persists via localStorage)

Mobile‑First, Responsive Layout (Tailwind CSS)

Sections: About • Skills & Tools • Projects (auto‑pulls pinned repos via GitHub API) • Experience • Education • Contact

Continuous Deployment: Push to main automatically deploys to Vercel (via GitHub Actions).

SEO & Social Meta Tags ready for sharing on LinkedIn/Twitter.

100 % Lighthouse‑score target (performance, a11y, best practices).

🛠️ Tech Stack

Layer

Tools & Libraries

Framework

Next.js 14 (App Router) + React 18

Styling

Tailwind CSS 3 + @tailwindcss/typography

Animation

Framer Motion

Icons

Heroicons

Language

TypeScript

Testing

Jest + React Testing Library

Lint / Format

ESLint, Prettier, Husky & Lint‑Staged

🚀 Getting Started

# 1. Clone the repo
$ git clone https://github.com/YOUR‑HANDLE/april‑hub.git
$ cd april‑hub

# 2. Install dependencies
$ pnpm install   # or npm / yarn

# 3. Start the dev server
$ pnpm dev       # default: http://localhost:3000

Environment Variables

Variable

Purpose

NEXT_PUBLIC_GITHUB

Your GitHub handle (API)

FORM_ENDPOINT

Formspree / Resend URL

Create a .env.local file with the keys above.

⚙️ CI / CD

GitHub Actions workflow deploy.yml:

Runs lint + test on every push

Deploys to Vercel on success

Caches pnpm for faster builds

(Workflow file lives under .github/workflows/.)

🗺️ Roadmap



🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

Fork the project

Create your feature branch (git checkout ‑b feat/AmazingFeature)

Commit your changes (git commit ‑m 'feat: add amazing feature')

Push to the branch (git push origin feat/…)

Open a Pull Request

📜 License

Distributed under the MIT License. See LICENSE for more information.

🙏 Acknowledgments

Next.js Documentation

Tailwind CSS

Framer Motion

Formspree for easy form handling

Made with ☕, 🎧 lo‑fi beats, and the occasional dog‑hair in the keyboard.

