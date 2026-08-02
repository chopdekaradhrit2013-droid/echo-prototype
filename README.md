# Echo — Working Prototype

Premium social media app prototype built with pure HTML + Tailwind CSS + vanilla JS.

## How to run

### Option 1: Open directly
Just open `index.html` in any modern browser (Chrome, Safari, Firefox).

### Option 2: GitHub Codespaces / github.dev (recommended for iPad)
1. Open this repo in github.dev or Codespaces
2. Right-click `index.html` → Open with Live Server (or use the simple preview)

### Option 3: Local static server
```bash
npx serve .
# or
python3 -m http.server 3000
```

## Screens included
- Home Feed (with stories + engagement)
- Discover (masonry + trending creators)
- Create Post
- Chats list
- Individual Chat (with voice messages, typing indicator)
- Notifications
- Profile
- Settings

## Design system
- Black OLED (`#0D0D0D`)
- Electric blue (`#4F8CFF`)
- Glassmorphism + soft glows
- Bottom navigation with glowing Echo Create button
- Fully interactive navigation

## Next steps (for full product)
- Convert to React + Vite + TypeScript + shadcn/ui
- Add Supabase auth + database
- Real-time chats with WebSockets
- Media upload
- Reels player with actual video

Built for browser / iPad-first development workflow.
