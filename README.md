# Adam Navarro — Portfolio

Built with [Astro](https://astro.build) · Deployed on [Vercel](https://vercel.com)

## Getting Started

### 1. Install dependencies
```bash
npm install
```

### 2. Run locally
```bash
npm run dev
```
Open http://localhost:4321 in your browser.

### 3. Build for production
```bash
npm run build
```

---

## Customizing Your Content

### Update project titles & tags
Edit `src/components/Work.astro` — find the `projects` array at the top and update:
- `title` — your actual project name
- `tags` — relevant tags (industry, skill, etc.)
- `image` — URL or local path to your screenshot
- `link` — your Figma prototype URL

### Replace project images with your own
Put your images in `public/images/` and reference them like:
```
image: "/images/my-project.png"
```

### Update About section
Edit `src/components/About.astro` to update your bio, expertise, industries, and tools.

---

## Deploying to Vercel

1. Push this folder to a GitHub repository
2. Go to https://vercel.com → New Project → Import your repo
3. Click **Deploy** — no configuration needed, Vercel detects Astro automatically
4. You'll get a free URL like `yourname.vercel.app`

## Connecting Your GoDaddy Domain

1. In Vercel: Project → Settings → Domains → Add your domain
2. Vercel shows you an **A record** and **CNAME** to add
3. In GoDaddy: My Products → DNS → Manage → delete the old A record → add the new ones
4. Wait 5–30 minutes for DNS propagation
5. Vercel automatically adds free HTTPS/SSL ✓
