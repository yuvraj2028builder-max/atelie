# Atelier — Premium Booking Tool for Delhi NCR Makeup Artists

Landing page + Sign Up / Sign In (Supabase Auth: email, Google, phone OTP) + Artist Onboarding (Step 1).

- Static site: `index.html` + `assets/` — no build step needed.
- Deploy: connect this repo to Vercel (Framework Preset: Other, Root Directory: ./) — every push auto-deploys to the same live URL.
- Backend: Supabase project (URL + anon public key are configured inside index.html — both are public-safe values).
- Google Client ID / Secret live ONLY inside the Supabase dashboard (Authentication > Providers > Google). Never put them in this repo.
- After every deploy URL change, update Supabase > Authentication > URL Configuration (Site URL + Redirect URLs) to the live Vercel URL.
