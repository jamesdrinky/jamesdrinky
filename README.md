### James Drinkwater

Financial Mathematics student at the University of Leeds who builds and ships production software. I like problems where the maths and the product meet: pricing, valuation, settlement and markets.

Most of my work lives in private repos because it runs real businesses. Below is what's in them. I'm happy to walk through any of the code on a call.

📫 james@drinky.com · [LinkedIn](https://www.linkedin.com/in/james-drinkwater-b88b04341)

#### What I've built

**[Investigator Events](https://investigatorevents.com)**: the global events and community platform for the private investigations industry
- Freelance product and engineering lead, Mar 2026 to now, hired by the founder of Conflict International. I'm the only developer. I decide what to build, design it, code it and ship it, working directly with the founder.
- Live on web, the App Store and Google Play: 500+ users (260+ members, 400+ newsletter subscribers), 80+ professional associations, 430+ events in 45+ countries.
- 820+ commits. Next.js, TypeScript, Supabase (Postgres, row-level security, auth), Capacitor for the iOS and Android apps, Resend for email, Vercel cron jobs, Sentry, and Upstash rate limiting.
- Built a social feed, stories, RSVPs that show who's going, messaging, reviews, push notifications, a weekly newsletter pipeline, an automated daily event scraper with a review queue, and a licensing map built with D3.
- Performance work cut page weight by up to 90% on the heaviest pages through image optimisation, code splitting and caching.

**[Motor-IQ](https://www.motor-iq.com)**: pricing intelligence for UK used-car dealers
- Valuation engine: nine weighted spec signals give a 100-point similarity index between cars. A mileage-adjusted median of comparable sales sets fair value, with a confidence score. Buy, maybe or pass calls are made net of preparation costs.
- Validated against a hedonic ridge regression I built in NumPy (253 listings, 5-fold cross-validation). Both priced a typical car to within about 20%. A separate spec regression on 38 BMWs found engine size, not trim, drove price (t = 7.3).
- 400+ commits. A Chrome extension (Manifest V3) reads listings in the dealer's browser. Also includes a web dashboard, an iOS app with number-plate scanning, and Stripe subscription billing (trials, webhooks, gating).
- Next.js 16, React 19, Prisma with Neon Postgres, custom session auth (scrypt), and a react-three-fiber 3D landing page.

**Poker IQ**: a league platform for a home poker game
- Plackett–Luce skill ratings from finishing positions.
- A greedy debt-settlement algorithm that clears any night in at most n−1 payments, with all money held as integer pence.
- Live blind clock, rebuys and knockouts, hand capture, and season standings. Next.js, Prisma and Postgres, plus a native iOS app in progress.

**GymIQ**: an iOS training tracker
- Native SwiftUI app plus a Next.js and Prisma web app, with an automatic load-progression algorithm.

**Autotrader Group plc (LSE: AUTO)**: an independent equity research pitch
- Buy case with a 580p target (17% upside): a 5-year DCF (WACC 9.4%, 2.5% terminal growth) with sensitivity analysis, cross-checked against listed classifieds peers such as Rightmove and Scout24.

#### Finance and digital assets

- **Equilibrium Group**, Capital Markets & Enterprise intern (Jul to Sep 2026). Profiled the top 10 tokenised money-market fund issuers (including BlackRock BUIDL, Franklin BENJI and Ondo) by structure, chain and custody. Researched use cases for an on-chain fund assurance product covering NAV verification and supply reconciliation. Wrote team updates on Swift's deposit pilot, DTCC's Collateral AppChain and MiCA.
- **BSc Financial Mathematics, University of Leeds** (2025 to 2028). Computational Maths & Modelling 75%, Management Accounting 79%. Course representative.
- Certificate in Financial Studies, LIBF: A*, top 1% nationally.

#### Toolkit

`Python` `NumPy` `SQL` `PostgreSQL` `TypeScript` `React` `Next.js` `Swift` `Supabase` `Prisma` `Stripe` `Vercel` `Excel` `DCF and regression modelling`
