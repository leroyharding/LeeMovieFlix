# 🎬 LeeMovieFlix — Feature Wishlist

> A curated list of features that would take the app from great to **elite-tier streaming experience**. Organized by priority and complexity.

---

## 🔥 High Impact — Must-Haves

| # | Feature | Description | Complexity |
|---|---------|-------------|------------|
| 1 | **Continue Watching** | Track playback progress per title with visual progress bars on cards. Resume exactly where you left off. | ✅ Medium |
| 2 | **Auto-Play Next Episode** | Netflix-style countdown ("Next episode in 10s...") after an episode ends. Full binge mode. | Medium |
| 3 | **Cast & Crew Browser** | Tap an actor's name in the info modal → see their full filmography. Discover movies through people. | Easy |
| 4 | **"Similar Movies" Section** | Show TMDB's `/similar` and `/recommendations` results inside the info modal. "If you liked this, try..." | Easy |
| 5 | **Advanced Search Filters** | Filter by year range, minimum rating, genre combo, and sort order. Power-user discovery. | Medium |
| 6 | **Random Pick / "I'm Feeling Lucky"** | Can't decide? One button picks a random highly-rated movie matching your taste. Great for TV remotes. | Easy |

---

## ⭐ Premium Experience

| # | Feature | Description | Complexity |
|---|---------|-------------|------------|
| 7 | **User Ratings & Reviews** | Rate movies 1–5 stars after watching. See your own ratings on cards. Track what you thought of everything. | Easy |
| 8 | **Custom Named Lists** | Beyond the single Watchlist — create lists like "Date Night", "Action Marathon", "Watch with Dad". | Medium |
| 9 | **Watch Statistics Dashboard** | Total movies watched, hours streamed, favourite genres, most-watched actors — beautiful charts and stats. | Medium |
| 10 | **Mood-Based Discovery** | "What mood are you in?" picker (😂 Funny → 😱 Scary → 🥰 Romantic → 🤯 Mind-Bending). Maps to curated genre combos. | Easy |
| 11 | **Top 10 Animated Banner** | A Netflix-style numbered Top 10 row with large horizontal posters and animated rank numbers. | Medium |
| 12 | **Startup Splash Animation** | Cinematic logo reveal on app launch — fade-in with glow effect. First impressions matter. | Easy |

---

## 🛡️ Family & Safety

| # | Feature | Description | Complexity |
|---|---------|-------------|------------|
| 13 | **Parental Controls / Kids Mode** | PIN-locked toggle. When active, filters content to PG/G ratings only. Safe for younger viewers. | Medium |
| 14 | **Content Rating Badges** | Show MPAA ratings (PG-13, R, etc.) on cards and info modals. TMDB provides this data via `release_dates`. | Easy |
| 15 | **Screen Time Reminder** | Optional "You've been watching for 2 hours" gentle notification. Healthy viewing habits. | Easy |

---

## 🎨 UI & Polish

| # | Feature | Description | Complexity |
|---|---------|-------------|------------|
| 16 | **Ambient Screensaver Mode** | After 5 min idle, cycle through beautiful backdrop images from trending movies with smooth Ken Burns effect. | Medium |
| 17 | **Hero Banner / Spotlight** | Large featured movie banner at the top of the home screen (like Netflix/Disney+). Auto-rotates through trending titles. | Medium |
| 18 | **Sound Effects** | Subtle UI sounds on navigation — soft clicks, whooshes on page transitions. Makes TV experience feel premium. | Easy |
| 19 | **Multiple Themes** | Beyond skins — full dark/OLED-black/light modes. Maybe even seasonal themes (Halloween 🎃, Christmas 🎄). | Easy |
| 20 | **Animated Card Hover Effects** | 3D tilt/parallax on card focus. Scale-up with backdrop blur. Makes browsing feel alive. | Easy |

---

## 🔧 Power User & Technical

| # | Feature | Description | Complexity |
|---|---------|-------------|------------|
| 21 | **Subtitle Language Preference** | Set preferred subtitle language globally. Pass it as a parameter to streaming providers. | Easy |
| 22 | **Backup & Restore** | Export watchlist, history, ratings, and settings to a JSON file. Import on another device. | Easy |
| 23 | **Server Health Indicator** | Show a green/yellow/red dot next to each streaming provider showing if it's currently online. | Medium |
| 24 | **Changelog / What's New** | In-app popup on first launch after update showing what changed. Users love knowing what's new. | Easy |
| 25 | **Keyboard Shortcuts Overlay** | Press "?" to see all available keyboard/remote shortcuts. Accessibility win. | Easy |

---

## 🚀 Ambitious / Future Vision

| # | Feature | Description | Complexity |
|---|---------|-------------|------------|
| 26 | **Multi-Device Sync** | Sync watchlist, history, and progress across devices via Firebase/cloud. Watch on TV, continue on phone. | Hard |
| 27 | **Watch Party Mode** | Share a room code with a friend — synchronized playback with a mini chat overlay. | Hard |
| 28 | **Voice Search** | "OK, play The Batman" — integrate with Android TV voice input for hands-free control. | Hard |
| 29 | **Movie Night Scheduler** | Pick a movie + set a date/time. App shows a countdown and auto-launches at the scheduled time. | Medium |
| 30 | **AI Recommendations** | Use viewing history to generate personalized "For You" suggestions beyond TMDB's generic recommendations. | Hard |

---

## 📊 Priority Ranking

> [!TIP]
> **Recommended build order** — start with the easiest, highest-impact features:

### Phase 1 — Quick Wins (1-2 hours each)
1. Cast & Crew Browser (#3)
2. Similar Movies Section (#4)
3. Random Pick (#6)
4. Content Rating Badges (#14)
5. Startup Splash Animation (#12)
6. Changelog Popup (#24)

### Phase 2 — Core Upgrades (half-day each)
7. Continue Watching with progress bars (#1)
8. Auto-Play Next Episode (#2)
9. User Ratings (#7)
10. Advanced Search Filters (#5)
11. Hero Banner (#17)

### Phase 3 — Premium Polish
12. Custom Named Lists (#8)
13. Watch Statistics Dashboard (#9)
14. Parental Controls (#13)
15. Top 10 Banner (#11)
16. Ambient Screensaver (#16)

### Phase 4 — Future Vision
17. Backup & Restore (#22)
18. Multi-Device Sync (#26)
19. Voice Search (#28)
20. Watch Party (#27)

---

> [!NOTE]
> All features are designed to work within the existing single-file architecture and Android TV/remote navigation constraints. TMDB API provides the data for most of these features at no extra cost.

*Last updated: May 11, 2026 — LeeMovieFlix v1.3.3*
