## Ricardo Gunther

Front-end developer and Computer Science student at Atitus Educação. I build web and mobile products with Next.js, React, TypeScript and Tailwind CSS — and I own the back-end side of what I ship, working with Node.js and PHP.

---

### Stack

**Front-end** · Next.js · React · TypeScript · Expo · Tailwind CSS · TanStack Query · Zustand

**Back-end** · Node.js · PHP (Laravel) · Python

**Data** · PostgreSQL · Supabase · Prisma

**Infra & quality** · Docker · Git · GitHub Actions · Netlify · Jest · Playwright · Zod · Winston

---

### Projects

#### [Rancho Feito](https://github.com/Ricardobgunther/ranchofeito) *(private, in development)* · [ranchofeito.com.br](https://ranchofeito.com.br)

Meal-planning startup: customers describe their routine, get a weekly meal plan, and turn it into a shopping list or a ready-made box ordered from a local market. I lead the front-end; the back-end is built by another developer, aligned through a shared API contract.

- Mobile-first web app in Next.js 16 (App Router), React 19, TypeScript (strict) and Tailwind CSS v4 with brand tokens
- Server state with TanStack Query, local state with Zustand, validation with Zod
- In-browser mock back-end, switchable per area, so every flow runs end to end before the API ships
- Three areas: customer (adaptive onboarding with voice answers, weekly plan, recipes, shopping list, boxes and orders), market (orders, substitutions, catalog with CSV import) and admin
- In-app notifications, installable PWA and LGPD tools (data export and account deletion)
- End-to-end tests with Playwright and axe accessibility checks; lint, typecheck and build in CI on GitHub Actions

#### [Andressa Dalcin — Nutritionist Landing Page](https://github.com/Ricardobgunther/andressa-dalcin) *(private)*

Conversion-focused, mobile-first landing page for a nutritionist in Passo Fundo, designed to turn visits into WhatsApp bookings.

- Plain static HTML, CSS and JS with no framework, for fast loads on mobile
- Dependency-free Python build script that generates the SEO head, JSON-LD (MedicalBusiness, Person, FAQPage, VideoObject), sitemap, robots and 404
- Local SEO: NAP matching the Google Business Profile, Open Graph image and preview mode with `noindex`
- Optimized media: WebP images, lazy loading, self-hosted fonts and short video previews encoded with ffmpeg
- Continuous deploy on Netlify, with content kept within the nutrition council's advertising rules

#### [Jonara Calderan — Landing Page](https://github.com/Ricardobgunther/jonarapage) *(private)*

Marketing site for a photographer and advertiser, built with Next.js 14 (App Router), TypeScript and Tailwind CSS.

- Portfolio fed automatically from Behance via RSS, with a 1h cache and a fallback when the source goes down
- Contact form validated end to end with Zod, persisted to Supabase with RLS, honeypot and rate limiting
- Transactional emails through Resend (notification and auto-reply), without blocking the request on failure
- Full SEO (Open Graph, JSON-LD, sitemap), AAA accessibility and optimized Core Web Vitals

#### [meridian](https://github.com/Ricardobgunther/meridian)

Multi-tenant SaaS application in Laravel and TypeScript.

- Authentication, email invites, organization management and dashboard
- Automated tests and CI set up with GitHub Actions

---

### Experience

#### ZapAgenda — WhatsApp-based scheduling SaaS

- Support and scheduling chatbot integrated with the Evolution API
- Mobile app built with Expo, real-time communication over WebSockets
- Back-end in Node.js and TypeScript, with Prisma on PostgreSQL hosted on Supabase
- Push notifications with OneSignal and access protection through Cloudflare
- Validation with Zod and Joi, structured logging with Winston and testing with Jest
- Containerized environments with Docker

---

### Contact

**Email** · ricardobg2004@gmail.com

**GitHub** · [@Ricardobgunther](https://github.com/Ricardobgunther)
