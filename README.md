# Lu'miere — It's a cake o'clock

Single-file SPA for **Lu'miere Signature**, a cake studio in Jakarta. Frost-glass hero, scroll-controlled frame sequence (240 frames), 3D card-shuffle deck, customer auth + cart + checkout, admin product/order management. All client-side, localStorage-backed.

🌐 Live: <https://lumiere-signature.netlify.app>

## Stack
- Single `index.html` (~2.6k lines) — vanilla JS SPA with hash routing
- Tailwind via CDN, Fraunces + Outfit + Alfa Slab One via Google Fonts
- Persistence: `localStorage`
- Hosting: Netlify

## Run locally
Just open `index.html` in a browser — no build step.

## Demo accounts
- Admin: `admin@lumiere.id` / `admin123`
- User:  `user@lumiere.id`  / `user123`

Or use the quick-login buttons in the nav.

## Project structure
```
lumiere/
├── index.html              # whole app
└── assets/
    ├── lumiere-logo.png    # brand mark (transparent)
    ├── L_rotate.mp4        # hero ambient bg video
    ├── L_Scroll.mp4        # source for scroll sequence
    └── scroll-frames/      # 240 pre-rendered frames (1920×1080 JPG)
        └── f_000.jpg ... f_239.jpg
```
