# lanesbrew ☕

A coffee shop photo wall experience where customers can capture and share their moments at lanesbrew coffee house.

## Features
- 📸 Capture photos with your device camera
- 📝 Add captions to your photos (up to 10 characters)
- 📌 Pin photos to the community wall
- 🔄 Real-time updates powered by Supabase
- 🎞️ Polaroid-style layout with random rotations

## Tech Stack
- Vanilla JavaScript
- Supabase (Database + Storage)
- CSS3 for styling

## Setup
1. Clone this repository
2. Ensure your Supabase database has a `polaroids` table with:
   - `id` (uuid, primary key)
   - `image_url` (text)
   - `caption` (text, optional)
   - `created_at` (timestamp, default: now())

3. Ensure your Supabase storage has a `Polaroids` bucket configured for public access

4. Deploy to Vercel, Netlify, or any static host

## Deployment
This site is ready to deploy to Vercel:
```bash
vercel deploy
```

Or connect your GitHub repo to Vercel for automatic deployments on each push.