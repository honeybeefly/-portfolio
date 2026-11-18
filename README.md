# SHARANYA HP — Evening Skyline Portfolio
> **Next.js App Router • TypeScript • Tailwind CSS • Warm amber palette • Skyline photography**

A polished, responsive portfolio with a high-resolution Shanghai skyline photograph, warm golden accents, keyboard-accessible navigation, and filterable project cards.

---

## ⚡ Quick Start (Local Development)

```bash
# 1. Navigate into project folder
cd portfolio

# 2. Install dependencies (if not already installed)
npm install

# 3. Start the Next.js local development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the live portfolio.

---

## 🎨 Where to Customize Your Data & Placeholders

All information is neatly organized in single editable files with comments:

| Content | File Path | Instructions |
|---|---|---|
| **Projects & Demos** | `src/data/projects.ts` | Edit project titles, descriptions, GitHub links, and Netlify demo URLs. |
| **Workshops & Events** | `src/data/workshops.ts` | Add new workshops, GDG sessions, AWS certificates, and Ideathons. |
| **Personal Info & Bio** | `src/data/owner.ts` | Update your phone number, social links, email, college details, and work ethics. |
| **Profile Photo** | `public/images/profile.jpg` | Replace with your actual portrait photo. |
| **Hero Skyline Photo** | `public/images/shanghai-city-night.jpg` | Replace with another high-resolution city photo if desired. Retain the photographer credit in the footer when replacing this CC BY 4.0 image. |

---

## 🚀 One-Click Deployment to Netlify

1. Push this repository to your GitHub account:
   ```bash
   git init
   git add .
   git commit -m "feat: warm evening skyline portfolio"
   git remote add origin https://github.com/<your-username>/sharanya-portfolio.git
   git branch -M main
   git push -u origin main
   ```
2. Go to [Netlify.com](https://www.netlify.com/) and click **"Add new site"** → **"Import an existing project"**.
3. Select your GitHub repository.
4. The included `netlify.toml` will automatically configure:
   - **Build command:** `npm run build`
   - **Publish directory:** `.next`
   - **Netlify Plugin:** `@netlify/plugin-nextjs`
   - Contact links open the visitor's email client; no form service is required.

---

## 🛡️ Page Architecture (in exact requested order)
1. **Home (Hero):** Prominent night skyline photograph, profile introduction, and navigation links.
2. **About & Studies:** Profile, education, and skills.
3. **Projects & Workshops:** Filterable project grid (All / Cybersecurity / Web / Cloud) with GitHub and demo links, plus an interactive event timeline.
4. **Interests & Hobbies:** Technical interests and personal hobbies, along with the **Open to Internships & Project Work** banner.
5. **Work Ethics & Teamwork:** Four foundational pillars and collaborative leadership examples.
6. **Contact:** Direct email and social links, with photo attribution and license.
