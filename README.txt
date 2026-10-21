Vaseline Cera-Glow x Dis-Chem Canal Walk - client review demo
==============================================================

What's in this folder
- index.html   The whole demo. Bootstrap, jQuery and all images are built in, so it needs nothing else.
- vercel.json  Keeps the page out of search engines and makes sure the client always sees the latest version.

Deploy with the Vercel CLI (about 2 minutes)
1. Install the CLI once:        npm i -g vercel
2. Open a terminal in this folder (the one containing index.html).
3. Log in:                      vercel login
4. Deploy to production:        vercel --prod
   - "Set up and deploy?"            -> Y
   - Scope                           -> your Berelo account/team
   - "Link to existing project?"     -> N
   - Project name                    -> vaseline-cera-glow-canal-walk
   - "In which directory is your code located?" -> ./   (press Enter)
   - Accept the defaults for any build settings (there is no build step).
5. Send the client the Production URL it prints, e.g. https://vaseline-cera-glow-canal-walk.vercel.app

To update later: replace index.html and run  vercel --prod  again from this folder. The URL stays the same.

Access check
Vercel protects preview links by default, so share the Production URL, not the long preview URL.
Open the link in a private/incognito window before sending it. If it asks for a Vercel login, go to
Project > Settings > Deployment Protection and set Vercel Authentication to "Standard Protection"
(covers previews only) or turn it off.

Demo notes
- The DEMO bar at the top lets the client preview the error states and the countdown before launch,
  while live and after it has ended.
- The countdown uses the real campaign window: Wed 28 Oct 2026 09:00 to Sun 1 Nov 2026 21:00 (SAST).
- No real data is sent anywhere. The form only simulates registration.
