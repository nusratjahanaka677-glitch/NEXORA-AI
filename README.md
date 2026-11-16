# NEXORA AI

A mobile-friendly all-in-one creator platform starter with a working dashboard, Studio navigation, local project saving, and an optional server-side Gemini assistant connection.

## What works now
- Responsive dashboard and navigation
- Studio pages for websites, Roblox, games, cartoon/animation, 3D, images/video, coding, phone assistance, and Superpower Lab
- Create and save project notes locally in the browser
- Download a project brief as a text file
- Server health check
- Optional Gemini assistant endpoint, with API key kept on the server

## Important limitations
This is a working first version / foundation, not a magic system that can create every finished asset automatically. Roblox publishing, 3D generation, video generation, phone settings control, and control of third-party games require separate supported tools, permissions, and integrations. The Superpower Lab is for games you own or games that explicitly permit the feature; it does not bypass other games' protections.

## Run
1. Install Node.js on a computer or supported cloud IDE.
2. Extract this ZIP.
3. In the project folder run `npm install`
4. Copy `.env.example` to `.env`
5. Run `npm start`
6. Open `http://localhost:3000`

On Android, use a cloud IDE that supports Node.js or deploy the project to a compatible host. Free hosting tiers and limits can change.

## Connect Gemini (optional)
- Create and manage your own API key through Google's official AI developer platform.
- Put the key in `.env` as `GEMINI_API_KEY=...`
- Restart the server.
- Do not paste API keys into public HTML, GitHub, or chat messages.
- Provider free quotas, availability, and terms can change; check the provider's current terms.

## Next development stages
1. Add authentication and secure user accounts.
2. Add database and cloud project storage.
3. Connect dedicated image, video, 3D, and game-generation providers.
4. Build export pipelines for Roblox-compatible assets and scripts.
5. Add project testing, moderation, and deployment integrations.
