# Synth Trading Bot Extension — End-to-End Video Script

**Purpose:** Demo the full user experience for the Synth Trading Bot (DemoBot) browser extension.  
**Audience:** Viewers who want to see setup, popup, dashboard, and news in one flow.  
**Prereq for recording:** DemoBot engine running at `http://127.0.0.1:8000` (or your configured URL).

---

## Scene 1 — Intro (≈15 sec)

**[Screen: Browser with extension icon visible in toolbar]**

**Script:**  
“This is the Synth Trading Bot extension — a Chrome extension that gives you a trading dashboard and quick controls for a Synth-powered trading engine. You get a compact popup for at-a-glance stats and a full dashboard for positions, signals, news, and Synth API activity.”

---

## Scene 2 — Install & First-Time Setup: Options (≈30 sec)

**[Action: Click extension icon once, then right-click → Options, or go to Extensions → DemoBot → Options]**

**Script:**  
“Before the extension can show live data, it needs to know where your trading engine is running. Open Options from the extension menu or from the dashboard link we’ll see in a moment.”

**[Action: Open Options page; show Engine base URL field]**

**Script:**  
“In Options, set the Engine base URL — usually `http://127.0.0.1:8000` or `http://localhost:8000` if the engine runs on your machine. Click Save. The status will confirm it’s saved.”

**[Action: Enter URL, click Save, show “Saved.”]**

**Script:**  
“Once this is set, the popup and dashboard will talk to your engine.”

---

## Scene 3 — Popup: Quick Overview (≈45 sec)

**[Action: Click extension icon to open popup]**

**Script:**  
“Clicking the extension icon opens the popup — your quick control center without leaving the page you’re on.”

**[Point to each section while speaking:]**

**Script:**  
“At the top you see connection status — ‘Engine OK’ when the engine is reachable.  
The Funds section shows your deposit and remaining capital, and you can unlock the deposit field to edit it. Exposure by asset breaks down how much is in each symbol.  
Stats show today’s P&amp;L, total P&amp;L, win rate, today’s trades, total trades, and wins versus losses.  
Spot &amp; Strike lists the main assets — BTC, ETH, indices, and so on — with their allocation weights and current spot prices.  
News gives a short summary and a link to open the full News view in the dashboard.  
Positions shows open and closed count; you can change the period — today, week, month, year, or all — and see a compact list of each position with side, entry, and P&amp;L.  
At the bottom, ‘Open Dashboard’ opens the full dashboard in a new tab.”

**[Action: Click “Open Dashboard”]**

**Script:**  
“Let’s open the full dashboard.”

---

## Scene 4 — Dashboard: Header & Main View (≈60 sec)

**[Screen: Dashboard tab — Dashboard (Overview) selected]**

**Script:**  
“The dashboard is the main workspace. The header shows Synth Trading Dashboard and your key numbers: engine connection status, net liquidation value, total P&amp;L, and trades today. On the right there’s a link to Options if you need to change the engine URL.”

**[Scroll to Funds, Stats, Spot & Strike, News summary]**

**Script:**  
“On the Dashboard tab you have the Funds card — deposit and remaining, with exposure by asset — and the Stats grid: today P&amp;L, total P&amp;L, win rate, today’s and total trades, and wins versus losses.  
Spot &amp; Strike shows the same assets as the popup with allocation percentages and live spot prices.  
The News box shows today’s summary; the full news workflow is in the News tab.”

**[Scroll to Positions table]**

**Script:**  
“Below that, Positions lists every position — open and closed — with status, asset, side, quantity, entry, stop, take-profit levels, partial closes, and P&amp;L. You can filter by period: today, week, month, year, or all. For open positions there’s a Close button if you want to manually close one.”

**[Optional: Show changing period dropdown; optionally show clicking Close on a position and result]**

**Script:**  
“Signals below show the latest trading signals from the last six hours — asset, bias, edge, whether the trade was allowed, and if not, the skip reason — for example exposure limits.  
Finally, Synth API Calls lists recent calls to the Synth API so you can see how the engine is using it.”

---

## Scene 5 — News Tab (≈40 sec)

**[Action: Click “News” in the dashboard nav]**

**Script:**  
“The News tab is where you manage market news. You can ‘Scrape &amp; Summarize’ to fetch new articles and build a summary, or ‘Summarize from DB’ to re-summarize from existing stored news.”

**[Action: Point to summary, sticky notes, asset bias, raw table]**

**Script:**  
“You get today’s summary, optional sticky notes, and an asset bias view showing sentiment per asset. The raw news table lists individual headlines and snippets with links to sources. This feeds into the bot’s context for signals and risk.”

---

## Scene 6 — Wrap-Up (≈15 sec)

**[Screen: Popup or dashboard, then extension icon]**

**Script:**  
“So: set your engine URL in Options, use the popup for a quick snapshot and to open the dashboard, and use the dashboard for positions, signals, news, and Synth API activity. The Synth Trading Bot extension keeps everything one click away from your browser toolbar.”

**[Optional: Show popup again]**

**Script:**  
“Thanks for watching.”

---

## Checklist Before Recording

- [ ] DemoBot engine running and healthy at the configured URL
- [ ] Extension loaded (Chrome → Extensions → Load unpacked, or already installed)
- [ ] Options saved with correct engine URL
- [ ] Browser window size and zoom consistent (e.g. 100%)
- [ ] No sensitive data in positions or account (or use dummy/sandbox engine)
- [ ] Optional: Prepare 1–2 open positions and some signals so tables aren’t empty

---

## Suggested Total Length

About **3–4 minutes** at a steady pace. Shorten by trimming the popup walkthrough or the News tab; lengthen by showing Close position or doing a live “Scrape &amp; Summarize” on the News tab.
