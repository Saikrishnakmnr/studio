# RacharlaGPT Digital Market — Static / No NPM

This version is intentionally **HTML + CSS + JavaScript only**. There is no `npm start`, no `npm install`, no Node runtime and no build command.

Upload the folder directly to existing HTML hosting, GitHub Pages or Cloudflare Pages.

## Supabase
Run `supabase_schema.sql` in Supabase. Put only the public URL and anon key in `config.js`.

## Razorpay
The official Checkout UI is loaded from Razorpay. Secure order creation/signature verification belong in the included Supabase Edge Functions. Put Razorpay secret values into Supabase Edge Function secrets, never into HTML/JS.

## AI
Gemini and ACE keys must remain server-side. The static storefront does not expose them.

## Logo
`assets/racharlagpt-logo.svg` is the permanent business logo and clearly displays the RacharlaGPT name.
