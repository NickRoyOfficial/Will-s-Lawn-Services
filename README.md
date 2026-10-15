# Will’s Lawn Services concept

Static website. No dependencies, package install, build step, tracking, or backend.

Run locally with `python3 -m http.server 8000` and open http://localhost:8000.

## Cloudflare Workers

Connect this repository to the existing `will-s-lawn-services` Worker, choose production branch `main`, leave the build command empty, and use `npx wrangler deploy` as the deploy command. `wrangler.jsonc` configures static asset hosting; `.assetsignore` limits uploads to website files. No runtime environment variables are required.

Review URL: https://will-s-lawn-services.nickroyofficial.workers.dev/

The estimate form prepares a text message to the verified business number, 207-274-0429. Visitors explicitly open and send the text themselves. A copy fallback is available for desktop. No messages or personal information are stored by this website.

## Content and assets

- Original company photos supplied by the user from the business’s Google listing. Thumbnail originals remain limited in resolution; replace the matching files in `assets/` when originals become available.
- Vector logo recreated from the supplied shirt photograph. All lettering is outlined.
- Services and phone number transcribed from the supplied shirt: lawn care, landscaping, mulching, loaming, cleanouts, and cleanups.
- Poland, Maine location and matching phone corroborated at https://www.bbb.org/us/me/poland/profile/lawn-maintenance/wills-lawn-services-0021-511926 . No wider service area, reviews, credentials, or response-time promises are assumed.
- Google Fonts: DM Sans and Instrument Serif, with system fallbacks.
- The concept intentionally includes `noindex,nofollow` and an independent-concept footer. Review these before an authorized production launch.
